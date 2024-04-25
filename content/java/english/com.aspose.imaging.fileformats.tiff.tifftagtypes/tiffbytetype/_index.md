---
title: TiffByteType
second_title: Aspose.Imaging for Java API Reference
description: The tiff byte type.
type: docs
weight: 11
url: /com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffbytetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype)
```
public final class TiffByteType extends TiffCommonArrayType
```

The tiff byte type.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffByteType(int tagId)](#TiffByteType-int-) | Initializes a new instance of the `TiffByteType` class. |
## Methods

| Method | Description |
| --- | --- |
| [getValues()](#getValues--) | Gets or sets the values. |
| [setValues(byte[] value)](#setValues-byte---) | Gets or sets the values. |
| [getValuesContainer()](#getValuesContainer--) | Gets the values container. |
| [getElementSize()](#getElementSize--) | Gets the element size in bytes. |
| [getTagType()](#getTagType--) | Gets the tag type. |
| [getValue()](#getValue--) | Gets or sets the value this data type contains. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Gets or sets the value this data type contains. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Writes the additional tag data. |
### TiffByteType(int tagId) {#TiffByteType-int-}
```
public TiffByteType(int tagId)
```


Initializes a new instance of the `TiffByteType` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagId | int | The tag id. |

### getValues() {#getValues--}
```
public byte[] getValues()
```


Gets or sets the values.

**Returns:**
byte[] - The data.
### setValues(byte[] value) {#setValues-byte---}
```
public void setValues(byte[] value)
```


Gets or sets the values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] | The data. |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Gets the values container.

**Returns:**
com.aspose.ms.System.Array - The values container.
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Gets the element size in bytes.

**Returns:**
byte - The element size in bytes.
### getTagType() {#getTagType--}
```
public int getTagType()
```


Gets the tag type.

**Returns:**
int - The tag type.
### getValue() {#getValue--}
```
public Object getValue()
```


Gets or sets the value this data type contains.

**Returns:**
java.lang.Object - The value.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Gets or sets the value this data type contains.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | The value. |

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
