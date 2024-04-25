---
title: TiffExifIfd
second_title: Aspose.Imaging for Java API Reference
description: The TIFF Exif image file directory class.
type: docs
weight: 11
url: /com.aspose.imaging.fileformats.tiff/tiffexififd/
---
**Inheritance:**
java.lang.Object
```
public class TiffExifIfd
```

The TIFF Exif image file directory class.

Incapsulates a pointer to the Exif IFD. Interoperability, Exif IFD has the same structure as that of the IFD specified in TIFF. ordinarily, however, it does not contain image data as in the case of TIFF. See http://www.exiv2.org/tags.html and http://www.awaresystems.be/imaging/tiff/tifftags/exififd.html for more details.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffExifIfd()](#TiffExifIfd--) | Initializes a new instance of the `TiffExifIfd` class. |
| [TiffExifIfd(long ifdOffset)](#TiffExifIfd-long-) | Initializes a new instance of the `TiffExifIfd` class. |
## Methods

| Method | Description |
| --- | --- |
| [hasValue()](#hasValue--) | Gets a value indicating whether this instance has value. |
| [getOffset()](#getOffset--) | Gets or sets the pointer to EXIF IFD. |
| [setOffset(long value)](#setOffset-long-) | Gets or sets the pointer to EXIF IFD. |
### TiffExifIfd() {#TiffExifIfd--}
```
public TiffExifIfd()
```


Initializes a new instance of the `TiffExifIfd` class.

### TiffExifIfd(long ifdOffset) {#TiffExifIfd-long-}
```
public TiffExifIfd(long ifdOffset)
```


Initializes a new instance of the `TiffExifIfd` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ifdOffset | long | A pointer to the Exif IFD.

Interoperability, Exif IFD has the same structure as that of the IFD specified in TIFF. ordinarily, however, it does not contain image data as in the case of TIFF. |

### hasValue() {#hasValue--}
```
public boolean hasValue()
```


Gets a value indicating whether this instance has value.

**Returns:**
boolean - `true` if this instance has value; otherwise, `false`.
### getOffset() {#getOffset--}
```
public long getOffset()
```


Gets or sets the pointer to EXIF IFD.

**Returns:**
long - The pointer to EXIF IFD.
### setOffset(long value) {#setOffset-long-}
```
public void setOffset(long value)
```


Gets or sets the pointer to EXIF IFD.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The pointer to EXIF IFD. |

