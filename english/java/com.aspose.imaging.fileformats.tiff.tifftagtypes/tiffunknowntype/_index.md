---
title: TiffUnknownType
second_title: Aspose.Imaging for Java API Reference
description: The unknown tiff type.
type: docs
weight: 27
url: /java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public final class TiffUnknownType extends TiffDataType
```

The unknown tiff type. In case the tiff tag cannot be recognized this type is instanced.

Note the `TiffUnknownType` is not serialized back to stream.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue)](#TiffUnknownType-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-int-int-long-long-) | Initializes a new instance of the `TiffUnknownType` class. |
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Gets the count of elements. |
| [getOffsetOrValue()](#getOffsetOrValue--) | Gets the offset value for an additional data or value itself in case count is 1. |
| [getStream()](#getStream--) | Gets the stream to read additional data from. |
| [getTagType()](#getTagType--) | Gets the tag type. |
| [getAdditionalDataSize(byte sizeOfTagValue)](#getAdditionalDataSize-byte-) | Gets the additional tag value size in bytes (in case the tag can not fit the whole tag value). |
| [getValue()](#getValue--) | Gets or sets the value this data type contains. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Gets or sets the value this data type contains. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Writes the additional tag data. |
| [toString()](#toString--) | Returns a `System.String` that represents this instance. |
### TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue) {#TiffUnknownType-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-int-int-long-long-}
```
public TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue)
```


Initializes a new instance of the `TiffUnknownType` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | [TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) | The stream to read from. |
| tagType | int | Type of the tag. |
| tagId | int | The tag id. |
| count | long | The count value. |
| offsetOrValue | long | The offset or value. |

### getCount() {#getCount--}
```
public long getCount()
```


Gets the count of elements.

Value: The count of elements.

**Returns:**
long
### getOffsetOrValue() {#getOffsetOrValue--}
```
public long getOffsetOrValue()
```


Gets the offset value for an additional data or value itself in case count is 1.

Value: The offset or value.

**Returns:**
long
### getStream() {#getStream--}
```
public TiffStreamReader getStream()
```


Gets the stream to read additional data from.

Value: The stream to read data from.

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader)
### getTagType() {#getTagType--}
```
public int getTagType()
```


Gets the tag type.

Value: The tag type.

**Returns:**
int
### getAdditionalDataSize(byte sizeOfTagValue) {#getAdditionalDataSize-byte-}
```
public long getAdditionalDataSize(byte sizeOfTagValue)
```


Gets the additional tag value size in bytes (in case the tag can not fit the whole tag value).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sizeOfTagValue | byte | Size of tag value: 4 or 8 for BigTiff. |

**Returns:**
long - The additional data size in bytes.
### getValue() {#getValue--}
```
public Object getValue()
```


Gets or sets the value this data type contains.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Gets or sets the value this data type contains.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public long writeAdditionalData(TiffStreamWriter dataStream)
```


Writes the additional tag data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | The data stream. |

**Returns:**
long - The actual bytes written.
### toString() {#toString--}
```
public String toString()
```


Returns a `System.String` that represents this instance.

**Returns:**
java.lang.String - A `System.String` that represents this instance.
