**[Polkadot JS UI libraries](../README.md)**

[Globals](../globals.md) › [&quot;ledger&quot;](../modules/_ledger_.md) › [Ledger](_ledger_.ledger.md)

# Class: Ledger

## Hierarchy

* **Ledger**

## Index

### Constructors

* [constructor](_ledger_.ledger.md#constructor)

### Methods

* [getAddress](_ledger_.ledger.md#getaddress)
* [getVersion](_ledger_.ledger.md#getversion)
* [sign](_ledger_.ledger.md#sign)

## Constructors

###  constructor

\+ **new Ledger**(`type`: [LedgerTypes](../modules/_ledger_.md#ledgertypes)): *[Ledger](_ledger_.ledger.md)*

*Defined in [ledger.ts:43](https://github.com/polkadot-js/ui/blob/6fce4b7/packages/ui-keyring/src/ledger.ts#L43)*

**Parameters:**

Name | Type |
------ | ------ |
`type` | [LedgerTypes](../modules/_ledger_.md#ledgertypes) |

**Returns:** *[Ledger](_ledger_.ledger.md)*

## Methods

###  getAddress

▸ **getAddress**(`confirm`: boolean, `account`: number, `change`: number, `addressIndex`: number): *Promise‹[LedgerAddress](../interfaces/_ledger_.ledgeraddress.md)›*

*Defined in [ledger.ts:93](https://github.com/polkadot-js/ui/blob/6fce4b7/packages/ui-keyring/src/ledger.ts#L93)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`confirm` | boolean | false |
`account` | number |  LEDGER_DEFAULT_ACCOUNT |
`change` | number |  LEDGER_DEFAULT_CHANGE |
`addressIndex` | number |  LEDGER_DEFAULT_INDEX |

**Returns:** *Promise‹[LedgerAddress](../interfaces/_ledger_.ledgeraddress.md)›*

___

###  getVersion

▸ **getVersion**(): *Promise‹[LedgerVersion](../interfaces/_ledger_.ledgerversion.md)›*

*Defined in [ledger.ts:104](https://github.com/polkadot-js/ui/blob/6fce4b7/packages/ui-keyring/src/ledger.ts#L104)*

**Returns:** *Promise‹[LedgerVersion](../interfaces/_ledger_.ledgerversion.md)›*

___

###  sign

▸ **sign**(`message`: Uint8Array, `account`: number, `change`: number, `addressIndex`: number): *Promise‹[LedgerSignature](../interfaces/_ledger_.ledgersignature.md)›*

*Defined in [ledger.ts:116](https://github.com/polkadot-js/ui/blob/6fce4b7/packages/ui-keyring/src/ledger.ts#L116)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`message` | Uint8Array | - |
`account` | number |  LEDGER_DEFAULT_ACCOUNT |
`change` | number |  LEDGER_DEFAULT_CHANGE |
`addressIndex` | number |  LEDGER_DEFAULT_INDEX |

**Returns:** *Promise‹[LedgerSignature](../interfaces/_ledger_.ledgersignature.md)›*