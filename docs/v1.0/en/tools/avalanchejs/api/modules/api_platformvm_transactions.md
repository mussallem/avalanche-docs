[avalanche](../README.md) › [API-PlatformVM-Transactions](api_platformvm_transactions.md)

# Module: API-PlatformVM-Transactions

## Index

### Classes

* [Tx](../classes/api_platformvm_transactions.tx.md)
* [UnsignedTx](../classes/api_platformvm_transactions.unsignedtx.md)

### Functions

* [SelectTxClass](api_platformvm_transactions.md#const-selecttxclass)

## Functions

### `Const` SelectTxClass

▸ **SelectTxClass**(`txtype`: number, ...`args`: Array‹any›): *[BaseTx](../classes/api_platformvm_basetx.basetx.md)*

*Defined in [src/apis/platformvm/tx.ts:83](https://github.com/ava-labs/avalanchejs/blob/a2feb77/src/apis/platformvm/tx.ts#L83)*

Takes a buffer representing the output and returns the proper [BaseTx](../classes/api_avm_basetx.basetx.md) instance.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`txtype` | number | The id of the transaction type  |
`...args` | Array‹any› | - |

**Returns:** *[BaseTx](../classes/api_platformvm_basetx.basetx.md)*

An instance of an [BaseTx](../classes/api_avm_basetx.basetx.md)-extended class.
