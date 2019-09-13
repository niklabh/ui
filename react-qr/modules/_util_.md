**[Polkadot JS UI libraries](../README.md)**

[Globals](../globals.md) › [&quot;util&quot;](_util_.md)

# External module: "util"

## Index

### Functions

* [createAddressPayload](_util_.md#createaddresspayload)
* [createFrames](_util_.md#createframes)
* [createImgSize](_util_.md#createimgsize)
* [createSignPayload](_util_.md#createsignpayload)
* [decodeString](_util_.md#decodestring)
* [encodeNumber](_util_.md#encodenumber)
* [encodeString](_util_.md#encodestring)

## Functions

###  createAddressPayload

▸ **createAddressPayload**(`address`: string, `genesisHash`: string): *Uint8Array*

*Defined in [util.ts:32](https://github.com/polkadot-js/ui/blob/b9f45d1/packages/react-qr/src/util.ts#L32)*

**Parameters:**

Name | Type |
------ | ------ |
`address` | string |
`genesisHash` | string |

**Returns:** *Uint8Array*

___

###  createFrames

▸ **createFrames**(`input`: Uint8Array): *Uint8Array[]*

*Defined in [util.ts:46](https://github.com/polkadot-js/ui/blob/b9f45d1/packages/react-qr/src/util.ts#L46)*

**Parameters:**

Name | Type |
------ | ------ |
`input` | Uint8Array |

**Returns:** *Uint8Array[]*

___

###  createImgSize

▸ **createImgSize**(`size?`: string | number): *Record‹string, string›*

*Defined in [util.ts:66](https://github.com/polkadot-js/ui/blob/b9f45d1/packages/react-qr/src/util.ts#L66)*

**Parameters:**

Name | Type |
------ | ------ |
`size?` | string &#124; number |

**Returns:** *Record‹string, string›*

___

###  createSignPayload

▸ **createSignPayload**(`address`: string, `cmd`: number, `payload`: string | Uint8Array): *Uint8Array*

*Defined in [util.ts:36](https://github.com/polkadot-js/ui/blob/b9f45d1/packages/react-qr/src/util.ts#L36)*

**Parameters:**

Name | Type |
------ | ------ |
`address` | string |
`cmd` | number |
`payload` | string &#124; Uint8Array |

**Returns:** *Uint8Array*

___

###  decodeString

▸ **decodeString**(`value`: Uint8Array): *string*

*Defined in [util.ts:26](https://github.com/polkadot-js/ui/blob/b9f45d1/packages/react-qr/src/util.ts#L26)*

**Parameters:**

Name | Type |
------ | ------ |
`value` | Uint8Array |

**Returns:** *string*

___

###  encodeNumber

▸ **encodeNumber**(`value`: number): *Uint8Array*

*Defined in [util.ts:12](https://github.com/polkadot-js/ui/blob/b9f45d1/packages/react-qr/src/util.ts#L12)*

**Parameters:**

Name | Type |
------ | ------ |
`value` | number |

**Returns:** *Uint8Array*

___

###  encodeString

▸ **encodeString**(`value`: string): *Uint8Array*

*Defined in [util.ts:16](https://github.com/polkadot-js/ui/blob/b9f45d1/packages/react-qr/src/util.ts#L16)*

**Parameters:**

Name | Type |
------ | ------ |
`value` | string |

**Returns:** *Uint8Array*