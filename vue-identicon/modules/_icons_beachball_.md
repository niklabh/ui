> # External module: "icons/Beachball"

## Index

### Variables

* [Beachball](_icons_beachball_.md#const-beachball)

## Variables

### `Const` Beachball

• **Beachball**: *`VueConstructor<Data & object & object & Vue>`* =  Vue.extend({
  template: `<div v-html="html" />`,
  props: ['address', 'size'],
  data: function (): Data {
    return {
      html: `<div />`
    };
  },
  created: function (): void {
    this.createHtml();
  },
  methods: {
    createHtml: function (): void {
      this.html = generate(this.address, this.size).outerHTML;
    }
  }
})

*Defined in [icons/Beachball.ts:16](https://github.com/polkadot-js/ui/blob/e481af9/packages/vue-identicon/src/icons/Beachball.ts#L16)*

**`name`** Beachball

**`description`** The Beachball identicon