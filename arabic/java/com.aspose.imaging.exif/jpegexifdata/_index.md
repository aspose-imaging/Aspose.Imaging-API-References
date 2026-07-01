---
title: "JpegExifData"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "حاوية بيانات EXIF لملفات jpeg."
type: docs
weight: 12
url: /ar/java/com.aspose.imaging.exif/jpegexifdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.exif.TiffDataTypeController](../../com.aspose.imaging.exif/tiffdatatypecontroller), [com.aspose.imaging.exif.ExifData](../../com.aspose.imaging.exif/exifdata)
```
public final class JpegExifData extends ExifData
```

حاوية بيانات EXIF لملفات jpeg.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [JpegExifData()](#JpegExifData--) | ينشئ مثيلاً جديدًا للفئة `JpegExifData`. |
| [JpegExifData(TiffDataType[] exifData)](#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---) | ينشئ مثيلاً جديدًا للفئة `JpegExifData` ببيانات من مصفوفة. |
| [JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---) | ينشئ مثيلاً جديدًا للفئة `JpegExifData` ببيانات من مصفوفة. |
| [JpegExifData(ExifData exifData)](#JpegExifData-com.aspose.imaging.exif.ExifData-) | ينشئ مثيلاً جديدًا للفئة [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) ببيانات من مصفوفة. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [MAX_EXIF_SEGMENT_SIZE](#MAX-EXIF-SEGMENT-SIZE) | الحد الأقصى لحجم مقطع EXIF بالبايت المسموح به. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getArtist()](#getArtist--) | يحصل أو يضبط الفنان. |
| [setArtist(String value)](#setArtist-java.lang.String-) | يحصل أو يضبط الفنان. |
| [getBitsPerSample()](#getBitsPerSample--) | يحصل أو يضبط عدد البتات لكل عينة. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | يحصل أو يضبط عدد البتات لكل عينة. |
| [getCompression()](#getCompression--) | يحصل أو يضبط الضغط. |
| [setCompression(int value)](#setCompression-int-) | يحصل أو يضبط الضغط. |
| [getCopyright()](#getCopyright--) | يحصل أو يضبط حقوق النشر. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | يحصل أو يضبط حقوق النشر. |
| [getDateTime()](#getDateTime--) | يحصل أو يضبط التاريخ والوقت. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | يحصل أو يضبط التاريخ والوقت. |
| [getImageDescription()](#getImageDescription--) | يحصل أو يضبط وصف الصورة. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | يحصل أو يضبط وصف الصورة. |
| [getImageLength()](#getImageLength--) | يحصل أو يضبط طول الصورة. |
| [setImageLength(long value)](#setImageLength-long-) | يحصل أو يضبط طول الصورة. |
| [getImageWidth()](#getImageWidth--) | يحصل أو يضبط عرض الصورة. |
| [setImageWidth(long value)](#setImageWidth-long-) | يحصل أو يضبط عرض الصورة. |
| [getModel()](#getModel--) | يحصل أو يضبط النموذج. |
| [setModel(String value)](#setModel-java.lang.String-) | يحصل أو يضبط النموذج. |
| [getPhotometricInterpretation()](#getPhotometricInterpretation--) | يحصل أو يضبط التفسير الضوئي. |
| [setPhotometricInterpretation(int value)](#setPhotometricInterpretation-int-) | يحصل أو يضبط التفسير الضوئي. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | يحصل أو يضبط تكوين المستوى. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | يحصل أو يضبط تكوين المستوى. |
| [getPrimaryChromaticities()](#getPrimaryChromaticities--) | يحصل أو يضبط تشبع الألوان للثلاث ألوان أساسية في الصورة. |
| [setPrimaryChromaticities(TiffRational[] value)](#setPrimaryChromaticities-com.aspose.imaging.fileformats.tiff.TiffRational---) | يحصل أو يضبط تشبع الألوان للثلاث ألوان أساسية في الصورة. |
| [getReferenceBlackWhite()](#getReferenceBlackWhite--) | يحصل أو يضبط الإشارة إلى الأسود والأبيض. |
| [setReferenceBlackWhite(TiffRational[] value)](#setReferenceBlackWhite-com.aspose.imaging.fileformats.tiff.TiffRational---) | يحصل أو يضبط الإشارة إلى الأسود والأبيض. |
| [getResolutionUnit()](#getResolutionUnit--) | يحصل أو يضبط وحدة الدقة. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | يحصل أو يضبط وحدة الدقة. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | يحصل أو يضبط عدد العينات لكل بكسل. |
| [setSamplesPerPixel(int value)](#setSamplesPerPixel-int-) | يحصل أو يضبط عدد العينات لكل بكسل. |
| [getSoftware()](#getSoftware--) | يحصل أو يضبط البرنامج. |
| [setSoftware(String value)](#setSoftware-java.lang.String-) | يحصل أو يضبط البرنامج. |
| [getTransferFunction()](#getTransferFunction--) | يحصل أو يضبط دالة النقل. |
| [setTransferFunction(int[] value)](#setTransferFunction-int---) | يحصل أو يضبط دالة النقل. |
| [getXResolution()](#getXResolution--) | يحصل أو يضبط دقة x. |
| [setXResolution(TiffRational value)](#setXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط دقة x. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | يحصل أو يضبط معاملات المصفوفة للتحويل من بيانات صورة RGB إلى YCbCr. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---) | يحصل أو يضبط معاملات المصفوفة للتحويل من بيانات صورة RGB إلى YCbCr. |
| [getYCbCrPositioning()](#getYCbCrPositioning--) | يحصل أو يعيّن موضع مكوّنات التشبع اللوني بالنسبة إلى مكوّن الإضاءة. |
| [setYCbCrPositioning(int value)](#setYCbCrPositioning-int-) | يحصل أو يعيّن موضع مكوّنات التشبع اللوني بالنسبة إلى مكوّن الإضاءة. |
| [getYCbCrSubSampling()](#getYCbCrSubSampling--) | يحصل أو يعيّن نسبة أخذ العينات لمكوّنات التشبع اللوني بالنسبة إلى مكوّن الإضاءة. |
| [setYCbCrSubSampling(int[] value)](#setYCbCrSubSampling-int---) | يحصل أو يعيّن نسبة أخذ العينات لمكوّنات التشبع اللوني بالنسبة إلى مكوّن الإضاءة. |
| [getYResolution()](#getYResolution--) | يحصل أو يضبط دقة y. |
| [setYResolution(TiffRational value)](#setYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط دقة y. |
| [serializeExifData()](#serializeExifData--) | يسلسِل بيانات EXIF. |
### JpegExifData() {#JpegExifData--}
```
public JpegExifData()
```


ينشئ مثيلاً جديدًا للفئة `JpegExifData`.

### JpegExifData(TiffDataType[] exifData) {#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] exifData)
```


ينشئ مثيلاً جديدًا للفئة `JpegExifData` ببيانات من مصفوفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| exifData | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | مصفوفة من علامات EXIF مع العلامات المشتركة وعلامات GPS. |

### JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


ينشئ مثيلاً جديدًا للفئة `JpegExifData` ببيانات من مصفوفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | العلامات المشتركة. |
| exifTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | علامات EXIF. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | علامات GPS. |

### JpegExifData(ExifData exifData) {#JpegExifData-com.aspose.imaging.exif.ExifData-}
```
public JpegExifData(ExifData exifData)
```


ينشئ مثيلاً جديدًا للفئة [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) ببيانات من مصفوفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| exifData | [ExifData](../../com.aspose.imaging.exif/exifdata) | مصفوفة من علامات EXIF مع العلامات المشتركة وعلامات GPS. |

### MAX_EXIF_SEGMENT_SIZE {#MAX-EXIF-SEGMENT-SIZE}
```
public static final int MAX_EXIF_SEGMENT_SIZE
```


الحد الأقصى لحجم مقطع EXIF بالبايت المسموح به.

### getArtist() {#getArtist--}
```
public String getArtist()
```


يحصل أو يضبط الفنان.

القيمة: الفنان.

**Returns:**
java.lang.String
### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


يحصل أو يضبط الفنان.

القيمة: الفنان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


يحصل أو يضبط عدد البتات لكل عينة.

القيمة: عدد البتات لكل عينة.

**Returns:**
int[]
### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


يحصل أو يضبط عدد البتات لكل عينة.

القيمة: عدد البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int[] |  |

### getCompression() {#getCompression--}
```
public int getCompression()
```


يحصل أو يضبط الضغط.

القيمة: الضغط.

**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


يحصل أو يضبط الضغط.

القيمة: الضغط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


يحصل أو يضبط حقوق النشر.

القيمة: حقوق النشر.

**Returns:**
java.lang.String
### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


يحصل أو يضبط حقوق النشر.

القيمة: حقوق النشر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


يحصل أو يضبط التاريخ والوقت.

القيمة: التاريخ والوقت.

**Returns:**
java.lang.String
### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


يحصل أو يضبط التاريخ والوقت.

القيمة: التاريخ والوقت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


يحصل أو يضبط وصف الصورة.

القيمة: وصف الصورة.

**Returns:**
java.lang.String
### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


يحصل أو يضبط وصف الصورة.

القيمة: وصف الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


يحصل أو يضبط طول الصورة.

القيمة: طول الصورة.

**Returns:**
long
### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


يحصل أو يضبط طول الصورة.

القيمة: طول الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


يحصل أو يضبط عرض الصورة.

القيمة: عرض الصورة.

**Returns:**
long
### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


يحصل أو يضبط عرض الصورة.

القيمة: عرض الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getModel() {#getModel--}
```
public String getModel()
```


يحصل أو يضبط النموذج.

القيمة: الطراز.

**Returns:**
java.lang.String
### setModel(String value) {#setModel-java.lang.String-}
```
public void setModel(String value)
```


يحصل أو يضبط النموذج.

القيمة: الطراز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getPhotometricInterpretation() {#getPhotometricInterpretation--}
```
public int getPhotometricInterpretation()
```


يحصل أو يضبط التفسير الضوئي.

القيمة: التفسير الضوئي.

**Returns:**
int
### setPhotometricInterpretation(int value) {#setPhotometricInterpretation-int-}
```
public void setPhotometricInterpretation(int value)
```


يحصل أو يضبط التفسير الضوئي.

القيمة: التفسير الضوئي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


يحصل أو يضبط تكوين المستوى.

القيمة: تكوين المستوى.

**Returns:**
int
### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


يحصل أو يضبط تكوين المستوى.

القيمة: تكوين المستوى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPrimaryChromaticities() {#getPrimaryChromaticities--}
```
public TiffRational[] getPrimaryChromaticities()
```


يحصل أو يضبط تشبع الألوان للثلاث ألوان أساسية في الصورة.

القيمة: اللونية للثلاث ألوان الأساسية في الصورة.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setPrimaryChromaticities(TiffRational[] value) {#setPrimaryChromaticities-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setPrimaryChromaticities(TiffRational[] value)
```


يحصل أو يضبط تشبع الألوان للثلاث ألوان أساسية في الصورة.

القيمة: اللونية للثلاث ألوان الأساسية في الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getReferenceBlackWhite() {#getReferenceBlackWhite--}
```
public TiffRational[] getReferenceBlackWhite()
```


يحصل أو يضبط الإشارة إلى الأسود والأبيض.

القيمة: الإشارة إلى الأسود والأبيض.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setReferenceBlackWhite(TiffRational[] value) {#setReferenceBlackWhite-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setReferenceBlackWhite(TiffRational[] value)
```


يحصل أو يضبط الإشارة إلى الأسود والأبيض.

القيمة: الإشارة إلى الأسود والأبيض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


يحصل أو يضبط وحدة الدقة.

القيمة: وحدة الدقة.

**Returns:**
int
### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


يحصل أو يضبط وحدة الدقة.

القيمة: وحدة الدقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


يحصل أو يضبط عدد العينات لكل بكسل.

القيمة: عدد العينات لكل بكسل.

**Returns:**
int
### setSamplesPerPixel(int value) {#setSamplesPerPixel-int-}
```
public void setSamplesPerPixel(int value)
```


يحصل أو يضبط عدد العينات لكل بكسل.

القيمة: عدد العينات لكل بكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


يحصل أو يضبط البرنامج.

القيمة: البرنامج.

**Returns:**
java.lang.String
### setSoftware(String value) {#setSoftware-java.lang.String-}
```
public void setSoftware(String value)
```


يحصل أو يضبط البرنامج.

القيمة: البرنامج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getTransferFunction() {#getTransferFunction--}
```
public int[] getTransferFunction()
```


يحصل أو يضبط دالة النقل.

القيمة: دالة النقل.

**Returns:**
int[]
### setTransferFunction(int[] value) {#setTransferFunction-int---}
```
public void setTransferFunction(int[] value)
```


يحصل أو يضبط دالة النقل.

القيمة: دالة النقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int[] |  |

### getXResolution() {#getXResolution--}
```
public TiffRational getXResolution()
```


يحصل أو يضبط دقة x.

القيمة: دقة x.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setXResolution(TiffRational value) {#setXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXResolution(TiffRational value)
```


يحصل أو يضبط دقة x.

القيمة: دقة x.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


يحصل أو يضبط معاملات المصفوفة للتحويل من بيانات صورة RGB إلى YCbCr.

القيمة: معاملات المصفوفة للتحويل من بيانات الصورة RGB إلى YCbCr.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


يحصل أو يضبط معاملات المصفوفة للتحويل من بيانات صورة RGB إلى YCbCr.

القيمة: معاملات المصفوفة للتحويل من بيانات الصورة RGB إلى YCbCr.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getYCbCrPositioning() {#getYCbCrPositioning--}
```
public int getYCbCrPositioning()
```


يحصل أو يعيّن موضع مكوّنات التشبع اللوني بالنسبة إلى مكوّن الإضاءة.

القيمة: موضع مكوّنات التشبع اللوني بالنسبة إلى مكوّن الإضاءة.

**Returns:**
int
### setYCbCrPositioning(int value) {#setYCbCrPositioning-int-}
```
public void setYCbCrPositioning(int value)
```


يحصل أو يعيّن موضع مكوّنات التشبع اللوني بالنسبة إلى مكوّن الإضاءة.

القيمة: موضع مكوّنات التشبع اللوني بالنسبة إلى مكوّن الإضاءة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getYCbCrSubSampling() {#getYCbCrSubSampling--}
```
public int[] getYCbCrSubSampling()
```


يحصل أو يعيّن نسبة أخذ العينات لمكوّنات التشبع اللوني بالنسبة إلى مكوّن الإضاءة.

القيمة: نسبة أخذ العينات لمكوّنات التشبع اللوني بالنسبة إلى مكوّن الإضاءة.

**Returns:**
int[]
### setYCbCrSubSampling(int[] value) {#setYCbCrSubSampling-int---}
```
public void setYCbCrSubSampling(int[] value)
```


يحصل أو يعيّن نسبة أخذ العينات لمكوّنات التشبع اللوني بالنسبة إلى مكوّن الإضاءة.

القيمة: نسبة أخذ العينات لمكوّنات التشبع اللوني بالنسبة إلى مكوّن الإضاءة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int[] |  |

### getYResolution() {#getYResolution--}
```
public TiffRational getYResolution()
```


يحصل أو يضبط دقة y.

القيمة: دقة y.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setYResolution(TiffRational value) {#setYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYResolution(TiffRational value)
```


يحصل أو يضبط دقة y.

القيمة: دقة y.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### serializeExifData() {#serializeExifData--}
```
public byte[] serializeExifData()
```


يسلسِل بيانات EXIF. يكتب قيم الوسوم ومحتوياتها. أكثر وسم يؤثر على الحجم هو محتويات وسم الصورة المصغرة.

**Returns:**
byte[] - بيانات EXIF المتسلسلة.

يجب أن يكون حجم الجزء الكلي أقل من أو يساوي MaxExifSegmentSize بايت لضمان إنتاج صورة JPEG صحيحة. تلميح: حاول تقليل حجم الصورة المصغرة أو تغيير ضغطها في حال كان حجم قسم EXIF كبيرًا جدًا.
