[**TDLib**](../../../../../../README.md) • **Docs**

***

[TDLib](../../../../../../modules.md) / [index](../../../../../README.md) / [types](../../../README.md) / [default](../README.md) / storageStatistics$Input

# Type Alias: storageStatistics$Input

> **storageStatistics$Input**: `object`

Version of [storageStatistics](storageStatistics-1.md) for method parameters.

Contains the exact storage usage statistics split by chats and file type

## Type declaration

### \_

> `readonly` **\_**: `"storageStatistics"`

### by\_chat?

> `readonly` `optional` **by\_chat**: [`vector$Input`](vector$Input.md)\<[`storageStatisticsByChat$Input`](storageStatisticsByChat$Input-1.md)\>

Statistics split by chats

### count?

> `readonly` `optional` **count**: [`int32`](int32-1.md)

Total number of files

### size?

> `readonly` `optional` **size**: [`int53`](int53-1.md)

Total size of files, in bytes

## Defined in

dist/generated/types.d.ts:49320