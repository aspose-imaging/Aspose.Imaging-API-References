---
title: TiffLongType
second_title: Aspose.Imaging for Java API Reference
description: The tiff long type.
type: docs
weight: 16
url: /java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tifflongtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype)
```
public final class TiffLongType extends TiffCommonArrayType
```

The tiff long type.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffLongType(int tagId)](#TiffLongType-int-) | Initializes a new instance of the `TiffLongType` class. |
## Methods

| Method | Description |
| --- | --- |
| [getValues()](#getValues--) | Gets or sets the values. |
| [setValues(long[] value)](#setValues-long---) | Gets or sets the values. |
| [getValuesContainer()](#getValuesContainer--) | Gets the values container. |
| [getElementSize()](#getElementSize--) | Gets the element size in bytes. |
| [getTagType()](#getTagType--) | Gets the tag type. |
| [getValue()](#getValue--) | Gets or sets the value this data type contains. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Gets or sets the value this data type contains. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Writes the additional tag data. |
### TiffLongType(int tagId) {#TiffLongType-int-}
```
public TiffLongType(int tagId)
```


Initializes a new instance of the `TiffLongType` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagId | int | The tag id. |

### getValues() {#getValues--}
```
public long[] getValues()
```


Gets or sets the values.

Value: The values.

**Returns:**
long[]
### setValues(long[] value) {#setValues-long---}
```
public void setValues(long[] value)
```


Gets or sets the values.

Value: The values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long[] |  |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Gets the values container.

Value: The values container.

**Returns:**
com.aspose.ms.System.Array
### getElementSize() {#getElementSize--}
```
public long getElementSize()
```


Gets the element size in bytes.

Value: The element size in bytes.

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
