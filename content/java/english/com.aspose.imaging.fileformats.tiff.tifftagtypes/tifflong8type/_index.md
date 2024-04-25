---
title: TiffLong8Type
second_title: Aspose.Imaging for Java API Reference
description: The Tiff unsigned 64-bit type.
type: docs
weight: 17
url: /com.aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype)
```
public class TiffLong8Type extends TiffCommonArrayType
```

The Tiff unsigned 64-bit type.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffLong8Type(int tagId)](#TiffLong8Type-int-) | Initializes a new instance of the [TiffLong8Type](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type) class. |
| [TiffLong8Type(int tagId, long[] values)](#TiffLong8Type-int-long---) | Initializes a new instance of the [TiffLong8Type](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type) class. |
## Methods

| Method | Description |
| --- | --- |
| [getValues()](#getValues--) | Gets the values. |
| [setValues(long[] value)](#setValues-long---) | Sets the values. |
| [getValuesContainer()](#getValuesContainer--) | Gets the values container. |
| [getTagType()](#getTagType--) | Gets the tag type. |
| [getValue()](#getValue--) | Gets the value this data type contains. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Sets the value this data type contains. |
| [getElementSize()](#getElementSize--) | Gets size of element. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Writes the additional tag data. |
### TiffLong8Type(int tagId) {#TiffLong8Type-int-}
```
public TiffLong8Type(int tagId)
```


Initializes a new instance of the [TiffLong8Type](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagId | int | The tag id. |

### TiffLong8Type(int tagId, long[] values) {#TiffLong8Type-int-long---}
```
public TiffLong8Type(int tagId, long[] values)
```


Initializes a new instance of the [TiffLong8Type](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagId | int | The tag id. |
| values | long[] |  |

### getValues() {#getValues--}
```
public final long[] getValues()
```


Gets the values.

Value: The tag values.

**Returns:**
long[] - the values.
### setValues(long[] value) {#setValues-long---}
```
public final void setValues(long[] value)
```


Sets the values.

Value: The tag values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long[] | the values. |

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


Sets the value this data type contains.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | the value this data type contains. |

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
