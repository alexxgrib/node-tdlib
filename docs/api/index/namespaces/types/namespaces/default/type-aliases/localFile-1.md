[**TDLib**](../../../../../../README.md) • **Docs**

***

[TDLib](../../../../../../modules.md) / [index](../../../../../README.md) / [types](../../../README.md) / [default](../README.md) / localFile

# Type Alias: localFile

> **localFile**: `object`

Represents a local file

## Type declaration

### \_

> **\_**: `"localFile"`

### can\_be\_deleted

> **can\_be\_deleted**: [`Bool`](Bool.md)

True, if the file can be deleted

### can\_be\_downloaded

> **can\_be\_downloaded**: [`Bool`](Bool.md)

True, if it is possible to download or generate the file

### download\_offset

> **download\_offset**: [`int53`](int53-1.md)

Download will be started from this offset. downloaded_prefix_size is calculated from this offset

### downloaded\_prefix\_size

> **downloaded\_prefix\_size**: [`int53`](int53-1.md)

If is_downloading_completed is false, then only some prefix of the file starting from download_offset is ready to be read. downloaded_prefix_size is the size of that prefix in bytes

### downloaded\_size

> **downloaded\_size**: [`int53`](int53-1.md)

Total downloaded file size, in bytes. Can be used only for calculating download progress. The actual file size may be bigger, and some parts of it may contain garbage

### is\_downloading\_active

> **is\_downloading\_active**: [`Bool`](Bool.md)

True, if the file is currently being downloaded (or a local copy is being generated by some other means)

### is\_downloading\_completed

> **is\_downloading\_completed**: [`Bool`](Bool.md)

True, if the local copy is fully available

### path

> **path**: `string`

Local path to the locally available file part; may be empty

## Defined in

dist/generated/types.d.ts:3647