---
title: TiffDoubleType
second_title: Aspose.Imaging for Java API Reference
description: The tiff double type.
type: docs
weight: 13
url: /java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype)
```
public final class TiffDoubleType extends TiffCommonArrayType
```

The tiff double type.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffDoubleType(int tagId)](#TiffDoubleType-int-) | Initializes a new instance of the `TiffDoubleType` class. |
## Methods

| Method | Description |
| --- | --- |
| [getValues()](#getValues--) | Gets the values. |
| [setValues(double[] value)](#setValues-double---) | Sets the values. |
| [getValuesContainer()](#getValuesContainer--) | Gets the values container. |
| [getTagType()](#getTagType--) | Gets the tag type. |
| [getElementSize()](#getElementSize--) | Gets the element size in bytes. |
| [getValue()](#getValue--) | Gets the value this data type contains. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Sets the value this data type contains. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Writes the additional tag data. |
### TiffDoubleType(int tagId) {#TiffDoubleType-int-}
```
public TiffDoubleType(int tagId)
```


Initializes a new instance of the `TiffDoubleType` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagId | int | The tag id. |

### getValues() {#getValues--}
```
public double[] getValues()
```


Gets the values.

**Returns:**
double[] - The values.
### setValues(double[] value) {#setValues-double---}
```
public void setValues(double[] value)
```


Sets the values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double[] | The values. |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Gets the values container.

**Returns:**
com.aspose.ms.System.Array - The values container.
### getTagType() {#getTagType--}
```
public int getTagType()
```


Gets the tag type.

**Returns:**
int - The tag type.
### getElementSize() {#getElementSize--}
```
public long getElementSize()
```


Gets the element size in bytes.

**Returns:**
long - The element size in bytes.
### getValue() {#getValue--}
```
public Object getValue()
```


Gets the value this data type contains.

**Returns:**
java.lang.Object - The value.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Sets the value this data type contains.

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
