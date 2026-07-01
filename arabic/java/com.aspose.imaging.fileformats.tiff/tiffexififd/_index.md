---
title: "TiffExifIfd"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "فئة دليل ملف صورة TIFF Exif."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.tiff/tiffexififd/
---
**Inheritance:**
java.lang.Object
```
public class TiffExifIfd
```

فئة دليل ملف صورة TIFF Exif.

يحتوي على مؤشر إلى Exif IFD. التوافقية، Exif IFD له نفس البنية كما في IFD المحدد في TIFF. عادةً، ومع ذلك، لا يحتوي على بيانات صورة كما في حالة TIFF. راجع http://www.exiv2.org/tags.html و http://www.awaresystems.be/imaging/tiff/tifftags/exififd.html لمزيد من التفاصيل.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TiffExifIfd()](#TiffExifIfd--) | ينشئ مثيلاً جديداً من الفئة `TiffExifIfd`. |
| [TiffExifIfd(long ifdOffset)](#TiffExifIfd-long-) | ينشئ مثيلاً جديداً من الفئة `TiffExifIfd`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [hasValue()](#hasValue--) | يحصل على قيمة تشير إلى ما إذا كان لهذا المثيل قيمة. |
| [getOffset()](#getOffset--) | يحصل أو يعيّن المؤشر إلى EXIF IFD. |
| [setOffset(long value)](#setOffset-long-) | يحصل أو يعيّن المؤشر إلى EXIF IFD. |
### TiffExifIfd() {#TiffExifIfd--}
```
public TiffExifIfd()
```


ينشئ مثيلاً جديداً من الفئة `TiffExifIfd`.

### TiffExifIfd(long ifdOffset) {#TiffExifIfd-long-}
```
public TiffExifIfd(long ifdOffset)
```


ينشئ مثيلاً جديداً من الفئة `TiffExifIfd`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | ifdOffset | long | مؤشر إلى Exif IFD. |

التوافقية، Exif IFD له نفس البنية كما في IFD المحدد في TIFF. عادةً، ومع ذلك، لا يحتوي على بيانات صورة كما في حالة TIFF. |

### hasValue() {#hasValue--}
```
public boolean hasValue()
```


يحصل على قيمة تشير إلى ما إذا كان لهذا المثيل قيمة.

**Returns:**
منطقي - `true` إذا كان لهذا المثيل قيمة؛ وإلا `false`.
### getOffset() {#getOffset--}
```
public long getOffset()
```


يحصل أو يعيّن المؤشر إلى EXIF IFD.

**Returns:**
طويل - المؤشر إلى EXIF IFD.
### setOffset(long value) {#setOffset-long-}
```
public void setOffset(long value)
```


يحصل أو يعيّن المؤشر إلى EXIF IFD.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long | المؤشر إلى EXIF IFD. |

