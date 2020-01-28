[Polkadot JS UI libraries](../README.md) › [Globals](../globals.md) › ["defaults"](_defaults_.md)

# External module: "defaults"

## Index

### Variables

* [MAX_PASS_LEN](_defaults_.md#const-max_pass_len)
* [accountRegex](_defaults_.md#const-accountregex)
* [addressRegex](_defaults_.md#const-addressregex)
* [contractRegex](_defaults_.md#const-contractregex)

### Functions

* [accountKey](_defaults_.md#const-accountkey)
* [addressKey](_defaults_.md#const-addresskey)
* [contractKey](_defaults_.md#const-contractkey)

## Variables

### `Const` MAX_PASS_LEN

• **MAX_PASS_LEN**: *32* = 32

*Defined in [packages/ui-keyring/src/defaults.ts:11](https://github.com/polkadot-js/ui/blob/fe4e6df9/packages/ui-keyring/src/defaults.ts#L11)*

___

### `Const` accountRegex

• **accountRegex**: *RegExp‹›* = new RegExp(`^${ACCOUNT_PREFIX}0x[0-9a-f]*`, '')

*Defined in [packages/ui-keyring/src/defaults.ts:29](https://github.com/polkadot-js/ui/blob/fe4e6df9/packages/ui-keyring/src/defaults.ts#L29)*

___

### `Const` addressRegex

• **addressRegex**: *RegExp‹›* = new RegExp(`^${ADDRESS_PREFIX}0x[0-9a-f]*`, '')

*Defined in [packages/ui-keyring/src/defaults.ts:31](https://github.com/polkadot-js/ui/blob/fe4e6df9/packages/ui-keyring/src/defaults.ts#L31)*

___

### `Const` contractRegex

• **contractRegex**: *RegExp‹›* = new RegExp(`^${CONTRACT_PREFIX}0x[0-9a-f]*`, '')

*Defined in [packages/ui-keyring/src/defaults.ts:33](https://github.com/polkadot-js/ui/blob/fe4e6df9/packages/ui-keyring/src/defaults.ts#L33)*

## Functions

### `Const` accountKey

▸ **accountKey**(`address`: string): *string*

*Defined in [packages/ui-keyring/src/defaults.ts:20](https://github.com/polkadot-js/ui/blob/fe4e6df9/packages/ui-keyring/src/defaults.ts#L20)*

**Parameters:**

Name | Type |
------ | ------ |
`address` | string |

**Returns:** *string*

___

### `Const` addressKey

▸ **addressKey**(`address`: string): *string*

*Defined in [packages/ui-keyring/src/defaults.ts:23](https://github.com/polkadot-js/ui/blob/fe4e6df9/packages/ui-keyring/src/defaults.ts#L23)*

**Parameters:**

Name | Type |
------ | ------ |
`address` | string |

**Returns:** *string*

___

### `Const` contractKey

▸ **contractKey**(`address`: string): *string*

*Defined in [packages/ui-keyring/src/defaults.ts:26](https://github.com/polkadot-js/ui/blob/fe4e6df9/packages/ui-keyring/src/defaults.ts#L26)*

**Parameters:**

Name | Type |
------ | ------ |
`address` | string |

**Returns:** *string*
