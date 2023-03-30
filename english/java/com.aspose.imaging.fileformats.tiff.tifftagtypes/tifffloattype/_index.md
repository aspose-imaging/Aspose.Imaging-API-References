---
title: TiffFloatType
second_title: Aspose.Imaging for Java API Reference
description: The tiff float type.
type: docs
weight: 14
url: /java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype)
```
public final class TiffFloatType extends TiffCommonArrayType
```

The tiff float type.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffFloatType(int tagId)](#TiffFloatType-int-) | Initializes a new instance of the `TiffFloatType` class. |
## Methods

| Method | Description |
| --- | --- |
| [getValues()](#getValues--) | Gets the values. |
| [setValues(float[] value)](#setValues-float---) | Sets the values. |
| [getElementSize()](#getElementSize--) | Gets the element size in bytes. |
| [getValuesContainer()](#getValuesContainer--) | Gets the values container. |
| [getTagType()](#getTagType--) | Gets the tag type. |
| [getValue()](#getValue--) | Gets the value this data type contains. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Sets the value this data type contains. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Writes the additional tag data. |
### TiffFloatType(int tagId) {#TiffFloatType-int-}
```
public TiffFloatType(int tagId)
```


Initializes a new instance of the `TiffFloatType` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagId | int | The tag id. |

### getValues() {#getValues--}
```
public float[] getValues()
```


Gets the values.

**Returns:**
float[] - The values.
### setValues(float[] value) {#setValues-float---}
```
public void setValues(float[] value)
```


Sets the values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] | The values. |

### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Gets the element size in bytes.

**Returns:**
byte - The element size in bytes.
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
