---
title: TiffDataType
second_title: Aspose.Imaging for Java API Reference
description: The tiff data type.
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.tiff/tiffdatatype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

The tiff data type.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffDataType()](#TiffDataType--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Gets the count of elements. |
| [getId()](#getId--) | Gets tag id integer representation. |
| [getTagId()](#getTagId--) | Gets the tag id. |
| [getTagType()](#getTagType--) | Gets the tag type. |
| [getAlignedDataSize()](#getAlignedDataSize--) | Gets the additional data size in bytes (in case the 12 bytes is not enough to fit the tag data). |
| [getDataSize()](#getDataSize--) | Gets the additional data size in bytes (in case the 12 bytes is not enough to fit the tag data). |
| [getValue()](#getValue--) | Gets the value this data type contains. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Sets the value this data type contains. |
| [isValid()](#isValid--) | Gets a value indicating whether tag data is valid. |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-long-) | Reads the tag data. |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.imaging.fileformats.tiff.TiffDataType-) | Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [deepClone()](#deepClone--) | Performs a deep clone of this instance. |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | Writes the tag data. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Writes the additional tag data. |
| [toString()](#toString--) | Returns a `System.String` that represents this instance. |
### TiffDataType() {#TiffDataType--}
```
public TiffDataType()
```


### getCount() {#getCount--}
```
public abstract long getCount()
```


Gets the count of elements.

**Returns:**
long - The count of elements.
### getId() {#getId--}
```
public int getId()
```


Gets tag id integer representation.

**Returns:**
int - The tag id integer representation
### getTagId() {#getTagId--}
```
public int getTagId()
```


Gets the tag id.

**Returns:**
int - The tag id.
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


Gets the tag type.

**Returns:**
int - The tag type.
### getAlignedDataSize() {#getAlignedDataSize--}
```
public long getAlignedDataSize()
```


Gets the additional data size in bytes (in case the 12 bytes is not enough to fit the tag data).

**Returns:**
long - The additional data size in bytes.

This is the data bytes count aligned to word boundary.
### getDataSize() {#getDataSize--}
```
public abstract long getDataSize()
```


Gets the additional data size in bytes (in case the 12 bytes is not enough to fit the tag data).

**Returns:**
long - The additional data size in bytes.

This is exact bytes count.
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Gets the value this data type contains.

**Returns:**
java.lang.Object - The value.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Sets the value this data type contains.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | The value. |

### isValid() {#isValid--}
```
public boolean isValid()
```


Gets a value indicating whether tag data is valid. The valid tag contains data which may be preserved. The invalid tag cannot be stored.

**Returns:**
boolean - `true` if tag data is valid; otherwise, `false`.
### readTag(TiffStreamReader dataStream, long position) {#readTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-long-}
```
public static TiffDataType readTag(TiffStreamReader dataStream, long position)
```


Reads the tag data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) | The data stream. |
| position | long | The tag position. |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - The read tag.
### compareTo(TiffDataType obj) {#compareTo-com.aspose.imaging.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | An object to compare with this instance. |

**Returns:**
int - A 32-bit signed integer that indicates the relative order of the objects being compared. The return value has these meanings: Value Meaning Less than zero This instance is less than `obj`. Zero This instance is equal to `obj`. Greater than zero This instance is greater than `obj`.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


Performs a deep clone of this instance.

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


Writes the tag data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | The data stream. |
| additionalDataOffset | long | The offset to write additional data to. |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
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
