[Polkadot JS UI libraries](../README.md) › [Globals](../globals.md) › ["defaults/ui"](_defaults_ui_.md)

# External module: "defaults/ui"

## Index

### Variables

* [ICONS](_defaults_ui_.md#const-icons)
* [ICON_DEFAULT](_defaults_ui_.md#const-icon_default)
* [ICON_DEFAULT_HOST](_defaults_ui_.md#const-icon_default_host)
* [LANGUAGE_DEFAULT](_defaults_ui_.md#const-language_default)
* [UIMODES](_defaults_ui_.md#const-uimodes)
* [UIMODE_DEFAULT](_defaults_ui_.md#const-uimode_default)
* [UITHEMES](_defaults_ui_.md#const-uithemes)
* [UITHEME_DEFAULT](_defaults_ui_.md#const-uitheme_default)

## Variables

### `Const` ICONS

• **ICONS**: *[Option](_types_.md#option)[]* = [
  {
    info: 'default',
    text: 'Default for the connected node',
    value: 'default'
  },
  {
    info: 'polkadot',
    text: 'Polkadot',
    value: 'polkadot'
  },
  {
    info: 'substrate',
    text: 'Substrate',
    value: 'substrate'
  },
  {
    info: 'beachball',
    text: 'Beachball',
    value: 'beachball'
  }
]

*Defined in [defaults/ui.ts:51](https://github.com/polkadot-js/ui/blob/55fd7977/packages/ui-settings/src/defaults/ui.ts#L51)*

___

### `Const` ICON_DEFAULT

• **ICON_DEFAULT**: *"default"* = "default"

*Defined in [defaults/ui.ts:45](https://github.com/polkadot-js/ui/blob/55fd7977/packages/ui-settings/src/defaults/ui.ts#L45)*

___

### `Const` ICON_DEFAULT_HOST

• **ICON_DEFAULT_HOST**: *"polkadot" | "substrate"* = isPolkadot
  ? 'polkadot'
  : 'substrate'

*Defined in [defaults/ui.ts:47](https://github.com/polkadot-js/ui/blob/55fd7977/packages/ui-settings/src/defaults/ui.ts#L47)*

___

### `Const` LANGUAGE_DEFAULT

• **LANGUAGE_DEFAULT**: *"default"* = "default"

*Defined in [defaults/ui.ts:9](https://github.com/polkadot-js/ui/blob/55fd7977/packages/ui-settings/src/defaults/ui.ts#L9)*

___

### `Const` UIMODES

• **UIMODES**: *[Option](_types_.md#option)[]* = [
  {
    info: 'full',
    text: 'Fully featured',
    value: 'full'
  },
  {
    info: 'light',
    text: 'Basic features only',
    value: 'light'
  }
]

*Defined in [defaults/ui.ts:15](https://github.com/polkadot-js/ui/blob/55fd7977/packages/ui-settings/src/defaults/ui.ts#L15)*

___

### `Const` UIMODE_DEFAULT

• **UIMODE_DEFAULT**: *"light" | "full"* = !isPolkadot && typeof window !== 'undefined' && window.location.host.includes('ui-light')
  ? 'light'
  : 'full'

*Defined in [defaults/ui.ts:11](https://github.com/polkadot-js/ui/blob/55fd7977/packages/ui-settings/src/defaults/ui.ts#L11)*

___

### `Const` UITHEMES

• **UITHEMES**: *[Option](_types_.md#option)[]* = [
  {
    info: 'polkadot',
    text: 'Polkadot',
    value: 'polkadot'
  },
  {
    info: 'substrate',
    text: 'Substrate',
    value: 'substrate'
  }
]

*Defined in [defaults/ui.ts:32](https://github.com/polkadot-js/ui/blob/55fd7977/packages/ui-settings/src/defaults/ui.ts#L32)*

___

### `Const` UITHEME_DEFAULT

• **UITHEME_DEFAULT**: *"polkadot" | "substrate"* = isPolkadot
  ? 'polkadot'
  : 'substrate'

*Defined in [defaults/ui.ts:28](https://github.com/polkadot-js/ui/blob/55fd7977/packages/ui-settings/src/defaults/ui.ts#L28)*
