> # External module: "Identicon"

## Index

### Variables

* [Identicon](_identicon_.md#const-identicon)

## Variables

### `Const` Identicon

• **Identicon**: *`VueConstructor<Data & object & object & Vue>`* =  Vue.extend({
  // FIXME These nested divs are not correct, would like a different way
  // here so we don't create a div wrapped for the div wrapper of the icon
  template: `
    <div v-if="type === 'empty' || address === ''">
      <Empty :size="iconSize" />
    </div>
    <div v-else-if="type === 'beachball'">
      <Beachball :address="address" :size="iconSize" />
    </div>
    <div v-else-if="type === 'polkadot'">
      <Polkadot :address="address" :size="iconSize" />
    </div>
    <div v-else>
      <Jdenticon :publicKey="publicKey" :size="iconSize" />
    </div>
  `,
  props: ['prefix', 'size', 'theme', 'value'],
  components: {
    Beachball,
    Empty,
    Jdenticon,
    Polkadot
  },
  data: function (): Data {
    return {
      address: '',
      iconSize: DEFAULT_SIZE,
      publicKey: '0x',
      type: 'empty'
    };
  },
  created: function (): void {
    this.createData();
  },
  methods: {
    createData: function (): void {
      this.iconSize = this.size || DEFAULT_SIZE;

      try {
        this.address = isU8a(this.value) || isHex(this.value)
          ? encodeAddress(this.value as string, this.prefix)
          : this.value;
        this.publicKey = u8aToHex(decodeAddress(this.address, false, this.prefix));
        this.type = this.theme;
      } catch (error) {
        this.address = '';
      }
    }
  }
})

*Defined in [Identicon.ts:28](https://github.com/polkadot-js/ui/blob/dbc9dd7/packages/vue-identicon/src/Identicon.ts#L28)*

**`name`** Identicon

**`description`** The main Identicon component, taking a number of properties

**`example`** 
```html
<Identicon :size="128" :theme="polkadot" :value="..." />
```