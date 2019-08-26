> # External module: "icons/Jdenticon"

## Index

### Variables

* [Jdenticon](_icons_jdenticon_.md#const-jdenticon)

## Variables

### `Const` Jdenticon

• **Jdenticon**: *`VueConstructor<Data & object & object & Vue>`* =  Vue.extend({
  template: `<div v-html="svgHtml" />`,
  props: ['publicKey', 'size'],
  data: function (): Data {
    return {
      svgHtml: `<svg viewBox="0 0 64 64" />`
    };
  },
  created: function (): void {
    this.createSvgHtml();
  },
  methods: {
    createSvgHtml: function (): void {
      this.svgHtml = jdenticon.toSvg(this.publicKey.substr(2), this.size);
    }
  }
})

*Defined in [icons/Jdenticon.ts:16](https://github.com/polkadot-js/ui/blob/a5dde02/packages/vue-identicon/src/icons/Jdenticon.ts#L16)*

**`name`** Jdenticon

**`description`** The substrate default via Jdenticon