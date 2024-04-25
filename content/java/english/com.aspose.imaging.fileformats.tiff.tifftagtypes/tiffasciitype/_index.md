---
title: TiffASCIIType
second_title: Aspose.Imaging for Java API Reference
description: The tiff ascii type.
type: docs
weight: 10
url: /com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public final class TiffASCIIType extends TiffDataType
```

The tiff ascii type.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffASCIIType(int tagId)](#TiffASCIIType-int-) | Initializes a new instance of the `TiffASCIIType` class. |
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Gets or sets the text. |
| [setText(String value)](#setText-java.lang.String-) | Gets or sets the text. |
| [getCount()](#getCount--) | Gets the count of elements. |
| [getTagType()](#getTagType--) | Gets the tag type. |
| [getValue()](#getValue--) | Gets or sets the value this data type contains. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Gets or sets the value this data type contains. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Writes the additional tag data. |
### TiffASCIIType(int tagId) {#TiffASCIIType-int-}
```
public TiffASCIIType(int tagId)
```


Initializes a new instance of the `TiffASCIIType` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagId | int | The tag id. |

### getText() {#getText--}
```
public String getText()
```


Gets or sets the text.

**Returns:**
java.lang.String - The text.
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Gets or sets the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The text. |

### getCount() {#getCount--}
```
public long getCount()
```


Gets the count of elements.

**Returns:**
long - The count of elements.
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
