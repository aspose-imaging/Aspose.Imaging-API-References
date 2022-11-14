---
title: TiffUndefinedType
second_title: Aspose.Imaging for Java API Reference
description: The tiff undefined type.
type: docs
weight: 23
url: /java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffundefinedtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public class TiffUndefinedType extends TiffDataType
```

The tiff undefined type.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffUndefinedType(int tagId)](#TiffUndefinedType-int-) | Initializes a new instance of the `TiffUndefinedType` class. |
## Methods

| Method | Description |
| --- | --- |
| [getData()](#getData--) | Gets or sets the data. |
| [setData(byte[] value)](#setData-byte---) | Gets or sets the data. |
| [getCount()](#getCount--) | Gets the count of elements. |
| [getTagType()](#getTagType--) | Gets the tag type. |
| [getDataSize()](#getDataSize--) | Gets the additional data size in bytes (in case the 12 bytes is not enough to fit the tag data). |
| [getValue()](#getValue--) | Gets or sets the value this data type contains. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Gets or sets the value this data type contains. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Writes the additional tag data. |
### TiffUndefinedType(int tagId) {#TiffUndefinedType-int-}
```
public TiffUndefinedType(int tagId)
```


Initializes a new instance of the `TiffUndefinedType` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagId | int | The tag id. |

### getData() {#getData--}
```
public byte[] getData()
```


Gets or sets the data.

Value: The data.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Gets or sets the data.

Value: The data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getCount() {#getCount--}
```
public long getCount()
```


Gets the count of elements.

Value: The count of elements.

**Returns:**
long
### getTagType() {#getTagType--}
```
public int getTagType()
```


Gets the tag type.

Value: The tag type.

**Returns:**
int
### getDataSize() {#getDataSize--}
```
public long getDataSize()
```


Gets the additional data size in bytes (in case the 12 bytes is not enough to fit the tag data).

Value: The additional data size in bytes.

**Returns:**
long
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
