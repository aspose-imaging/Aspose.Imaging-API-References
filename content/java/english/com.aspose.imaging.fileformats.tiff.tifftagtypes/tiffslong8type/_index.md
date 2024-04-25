---
title: TiffSLong8Type
second_title: Aspose.Imaging for Java API Reference
description: The Tiff unsigned 64-bit type.
type: docs
weight: 21
url: /com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype)
```
public class TiffSLong8Type extends TiffCommonArrayType
```

The Tiff unsigned 64-bit type.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffSLong8Type(int tagId)](#TiffSLong8Type-int-) | Initializes a new instance of the [TiffSLong8Type](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type) class. |
## Methods

| Method | Description |
| --- | --- |
| [getValues()](#getValues--) | Gets the values. |
| [setValues(long[] values)](#setValues-long---) | Sets the values. |
| [getValuesContainer()](#getValuesContainer--) | Gets the values container. |
| [getTagType()](#getTagType--) | Gets the tag type. |
| [getValue()](#getValue--) | Gets the value this data type contains. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Gets the value this data type contains. |
| [getElementSize()](#getElementSize--) | Gets size of element. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Writes the additional tag data. |
### TiffSLong8Type(int tagId) {#TiffSLong8Type-int-}
```
public TiffSLong8Type(int tagId)
```


Initializes a new instance of the [TiffSLong8Type](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagId | int | The tag id. |

### getValues() {#getValues--}
```
public final long[] getValues()
```


Gets the values.

Value: The tag values.

**Returns:**
long[] - the values.
### setValues(long[] values) {#setValues-long---}
```
public void setValues(long[] values)
```


Sets the values.

Value: The tag values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| values | long[] | The values. |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Gets the values container.

**Returns:**
com.aspose.ms.System.Array - the values container.
### getTagType() {#getTagType--}
```
public int getTagType()
```


Gets the tag type.

Value: The tag type.

**Returns:**
int - the tag type.
### getValue() {#getValue--}
```
public Object getValue()
```


Gets the value this data type contains.

**Returns:**
java.lang.Object - the value this data type contains.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Gets the value this data type contains.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | The value this data type contains. |

### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Gets size of element.

**Returns:**
byte - size of element.
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
