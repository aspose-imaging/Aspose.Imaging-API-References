---
title: TiffShortType
second_title: Aspose.Imaging for Java API Reference
description: The tiff short type.
type: docs
weight: 22
url: /java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffshorttype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class TiffShortType extends TiffCommonArrayType implements Serializable
```

The tiff short type.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffShortType()](#TiffShortType--) |  |
| [TiffShortType(int tagId)](#TiffShortType-int-) | Initializes a new instance of the `TiffShortType` class. |
## Methods

| Method | Description |
| --- | --- |
| [getValues()](#getValues--) | Gets or sets the data. |
| [setValues(int[] value)](#setValues-int---) | Gets or sets the data. |
| [getElementSize()](#getElementSize--) | Gets the element size in bytes. |
| [getValuesContainer()](#getValuesContainer--) | Gets the values container. |
| [getTagType()](#getTagType--) | Gets the tag type. |
| [getValue()](#getValue--) | Gets or sets the value this data type contains. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Gets or sets the value this data type contains. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Writes the additional tag data. |
### TiffShortType() {#TiffShortType--}
```
public TiffShortType()
```


### TiffShortType(int tagId) {#TiffShortType-int-}
```
public TiffShortType(int tagId)
```


Initializes a new instance of the `TiffShortType` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagId | int | The tag id. |

### getValues() {#getValues--}
```
public int[] getValues()
```


Gets or sets the data.

Value: The data.

**Returns:**
int[]
### setValues(int[] value) {#setValues-int---}
```
public void setValues(int[] value)
```


Gets or sets the data.

Value: The data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### getElementSize() {#getElementSize--}
```
public long getElementSize()
```


Gets the element size in bytes.

Value: The element size in bytes.

**Returns:**
long
### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Gets the values container.

Value: The values container.

**Returns:**
com.aspose.ms.System.Array
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
