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
| [JpegExifData()](#JpegExifData--) | يقوم بإنشاء نسخة جديدة من الفئة `JpegExifData`. |
| [JpegExifData(TiffDataType[] exifData)](#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---) | يقوم بإنشاء نسخة جديدة من الفئة `JpegExifData` باستخدام البيانات من المصفوفة. |
| [JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---) | يقوم بإنشاء نسخة جديدة من الفئة `JpegExifData` باستخدام البيانات من المصفوفة. |
| [JpegExifData(ExifData exifData)](#JpegExifData-com.aspose.imaging.exif.ExifData-) | يقوم بإنشاء نسخة جديدة من الفئة [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) باستخدام البيانات من المصفوفة. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [MAX_EXIF_SEGMENT_SIZE](#MAX-EXIF-SEGMENT-SIZE) | الحد الأقصى لحجم مقطع EXIF بالبايت المسموح به. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getArtist()](#getArtist--) | يسترجع أو يعيّن الفنان. |
| [setArtist(String value)](#setArtist-java.lang.String-) | يسترجع أو يعيّن الفنان. |
| [getBitsPerSample()](#getBitsPerSample--) | يحصل أو يعيّن عدد البتات لكل عينة. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | يحصل أو يعيّن عدد البتات لكل عينة. |
| [getCompression()](#getCompression--) | يحصل أو يعيّن الضغط. |
| [setCompression(int value)](#setCompression-int-) | يحصل أو يعيّن الضغط. |
| [getCopyright()](#getCopyright--) | يحصل أو يعيّن حقوق النشر. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | يحصل أو يعيّن حقوق النشر. |
| [getDateTime()](#getDateTime--) | يحصل أو يعيّن التاريخ والوقت. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | يحصل أو يعيّن التاريخ والوقت. |
| [getImageDescription()](#getImageDescription--) | يحصل أو يضبط وصف الصورة. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | يحصل أو يضبط وصف الصورة. |
| [getImageLength()](#getImageLength--) | يحصل أو يضبط طول الصورة. |
| [setImageLength(long value)](#setImageLength-long-) | يحصل أو يضبط طول الصورة. |
| [getImageWidth()](#getImageWidth--) | يحصل أو يضبط عرض الصورة. |
| [setImageWidth(long value)](#setImageWidth-long-) | يحصل أو يضبط عرض الصورة. |
| [getModel()](#getModel--) | يحصل أو يعيّن الطراز. |
| [setModel(String value)](#setModel-java.lang.String-) | يحصل أو يعيّن الطراز. |
| [getPhotometricInterpretation()](#getPhotometricInterpretation--) | يحصل أو يعيّن تفسير الفوتومتري. |
| [setPhotometricInterpretation(int value)](#setPhotometricInterpretation-int-) | يحصل أو يعيّن تفسير الفوتومتري. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | يحصل أو يضبط تكوين المستوى. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | يحصل أو يضبط تكوين المستوى. |
| [getPrimaryChromaticities()](#getPrimaryChromaticities--) | يحصل أو يعيّن اللونية للثلاثة ألوان الأساسية في الصورة. |
| [setPrimaryChromaticities(TiffRational[] value)](#setPrimaryChromaticities-com.aspose.imaging.fileformats.tiff.TiffRational---) | يحصل أو يعيّن اللونية للثلاثة ألوان الأساسية في الصورة. |
| [getReferenceBlackWhite()](#getReferenceBlackWhite--) | يحصل أو يعيّن المرجع الأسود والأبيض. |
| [setReferenceBlackWhite(TiffRational[] value)](#setReferenceBlackWhite-com.aspose.imaging.fileformats.tiff.TiffRational---) | يحصل أو يعيّن المرجع الأسود والأبيض. |
| [getResolutionUnit()](#getResolutionUnit--) | يحصل أو يضبط وحدة الدقة. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | يحصل أو يضبط وحدة الدقة. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | يحصل أو يعيّن عدد العينات لكل بكسل. |
| [setSamplesPerPixel(int value)](#setSamplesPerPixel-int-) | يحصل أو يعيّن عدد العينات لكل بكسل. |
| [getSoftware()](#getSoftware--) | يحصل أو يعيّن البرنامج. |
| [setSoftware(String value)](#setSoftware-java.lang.String-) | يحصل أو يعيّن البرنامج. |
| [getTransferFunction()](#getTransferFunction--) | يحصل أو يعيّن دالة النقل. |
| [setTransferFunction(int[] value)](#setTransferFunction-int---) | يحصل أو يعيّن دالة النقل. |
| [getXResolution()](#getXResolution--) | يحصل أو يضبط دقة x. |
| [setXResolution(TiffRational value)](#setXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط دقة x. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | يحصل أو يعيّن معاملات المصفوفة للتحويل من بيانات الصورة RGB إلى YCbCr. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---) | يحصل أو يعيّن معاملات المصفوفة للتحويل من بيانات الصورة RGB إلى YCbCr. |
| [getYCbCrPositioning()](#getYCbCrPositioning--) | يحصل أو يعيّن موضع مكونات التشبع اللوني بالنسبة إلى مكون الإضاءة. |
| [setYCbCrPositioning(int value)](#setYCbCrPositioning-int-) | يحصل أو يعيّن موضع مكونات التشبع اللوني بالنسبة إلى مكون الإضاءة. |
| [getYCbCrSubSampling()](#getYCbCrSubSampling--) | يحصل أو يعيّن نسبة أخذ العينات لمكونات التشبع اللوني بالنسبة إلى مكون الإضاءة. |
| [setYCbCrSubSampling(int[] value)](#setYCbCrSubSampling-int---) | يحصل أو يعيّن نسبة أخذ العينات لمكونات التشبع اللوني بالنسبة إلى مكون الإضاءة. |
| [getYResolution()](#getYResolution--) | يحصل أو يضبط دقة y. |
| [setYResolution(TiffRational value)](#setYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط دقة y. |
| [serializeExifData()](#serializeExifData--) | يقوم بتسلسل بيانات EXIF. |
### JpegExifData() {#JpegExifData--}
```
public JpegExifData()
```


يقوم بإنشاء نسخة جديدة من الفئة `JpegExifData`.

### JpegExifData(TiffDataType[] exifData) {#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] exifData)
```


يقوم بإنشاء نسخة جديدة من الفئة `JpegExifData` باستخدام البيانات من المصفوفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| exifData | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | مصفوفة من علامات EXIF مع العلامات المشتركة وعلامات GPS. |

### JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


يقوم بإنشاء نسخة جديدة من الفئة `JpegExifData` باستخدام البيانات من المصفوفة.

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


يقوم بإنشاء نسخة جديدة من الفئة [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) باستخدام البيانات من المصفوفة.

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


يسترجع أو يعيّن الفنان.

القيمة: الفنان.

**Returns:**
java.lang.String
### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


يسترجع أو يعيّن الفنان.

القيمة: الفنان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


يحصل أو يعيّن عدد البتات لكل عينة.

القيمة: عدد البتات لكل عينة.

**Returns:**
int[]
### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


يحصل أو يعيّن عدد البتات لكل عينة.

القيمة: عدد البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] |  |

### getCompression() {#getCompression--}
```
public int getCompression()
```


يحصل أو يعيّن الضغط.

القيمة: الضغط.

**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


يحصل أو يعيّن الضغط.

القيمة: الضغط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


يحصل أو يعيّن حقوق النشر.

القيمة: حقوق النشر.

**Returns:**
java.lang.String
### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


يحصل أو يعيّن حقوق النشر.

القيمة: حقوق النشر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


يحصل أو يعيّن التاريخ والوقت.

القيمة: التاريخ والوقت.

**Returns:**
java.lang.String
### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


يحصل أو يعيّن التاريخ والوقت.

القيمة: التاريخ والوقت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

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
| القيمة | java.lang.String |  |

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
| القيمة | long |  |

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
| القيمة | long |  |

### getModel() {#getModel--}
```
public String getModel()
```


يحصل أو يعيّن الطراز.

القيمة: النموذج.

**Returns:**
java.lang.String
### setModel(String value) {#setModel-java.lang.String-}
```
public void setModel(String value)
```


يحصل أو يعيّن الطراز.

القيمة: النموذج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getPhotometricInterpretation() {#getPhotometricInterpretation--}
```
public int getPhotometricInterpretation()
```


يحصل أو يعيّن تفسير الفوتومتري.

القيمة: التفسير الضوئي.

**Returns:**
int
### setPhotometricInterpretation(int value) {#setPhotometricInterpretation-int-}
```
public void setPhotometricInterpretation(int value)
```


يحصل أو يعيّن تفسير الفوتومتري.

القيمة: التفسير الضوئي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


يحصل أو يضبط تكوين المستوى.

القيمة: التكوين المستوي.

**Returns:**
int
### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


يحصل أو يضبط تكوين المستوى.

القيمة: التكوين المستوي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getPrimaryChromaticities() {#getPrimaryChromaticities--}
```
public TiffRational[] getPrimaryChromaticities()
```


يحصل أو يعيّن اللونية للثلاثة ألوان الأساسية في الصورة.

القيمة: اللونية للألوان الثلاثة الأساسية في الصورة.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setPrimaryChromaticities(TiffRational[] value) {#setPrimaryChromaticities-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setPrimaryChromaticities(TiffRational[] value)
```


يحصل أو يعيّن اللونية للثلاثة ألوان الأساسية في الصورة.

القيمة: اللونية للألوان الثلاثة الأساسية في الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getReferenceBlackWhite() {#getReferenceBlackWhite--}
```
public TiffRational[] getReferenceBlackWhite()
```


يحصل أو يعيّن المرجع الأسود والأبيض.

القيمة: المرجع الأسود والأبيض.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setReferenceBlackWhite(TiffRational[] value) {#setReferenceBlackWhite-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setReferenceBlackWhite(TiffRational[] value)
```


يحصل أو يعيّن المرجع الأسود والأبيض.

القيمة: المرجع الأسود والأبيض.

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
| القيمة | int |  |

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


يحصل أو يعيّن عدد العينات لكل بكسل.

القيمة: عدد العينات لكل بكسل.

**Returns:**
int
### setSamplesPerPixel(int value) {#setSamplesPerPixel-int-}
```
public void setSamplesPerPixel(int value)
```


يحصل أو يعيّن عدد العينات لكل بكسل.

القيمة: عدد العينات لكل بكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


يحصل أو يعيّن البرنامج.

القيمة: البرنامج.

**Returns:**
java.lang.String
### setSoftware(String value) {#setSoftware-java.lang.String-}
```
public void setSoftware(String value)
```


يحصل أو يعيّن البرنامج.

القيمة: البرنامج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getTransferFunction() {#getTransferFunction--}
```
public int[] getTransferFunction()
```


يحصل أو يعيّن دالة النقل.

القيمة: دالة النقل.

**Returns:**
int[]
### setTransferFunction(int[] value) {#setTransferFunction-int---}
```
public void setTransferFunction(int[] value)
```


يحصل أو يعيّن دالة النقل.

القيمة: دالة النقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] |  |

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


يحصل أو يعيّن معاملات المصفوفة للتحويل من بيانات الصورة RGB إلى YCbCr.

القيمة: معاملات المصفوفة للتحويل من بيانات صورة RGB إلى YCbCr.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


يحصل أو يعيّن معاملات المصفوفة للتحويل من بيانات الصورة RGB إلى YCbCr.

القيمة: معاملات المصفوفة للتحويل من بيانات صورة RGB إلى YCbCr.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getYCbCrPositioning() {#getYCbCrPositioning--}
```
public int getYCbCrPositioning()
```


يحصل أو يعيّن موضع مكونات التشبع اللوني بالنسبة إلى مكون الإضاءة.

القيمة: موضع مكونات التشبع اللوني بالنسبة لمكون الإضاءة.

**Returns:**
int
### setYCbCrPositioning(int value) {#setYCbCrPositioning-int-}
```
public void setYCbCrPositioning(int value)
```


يحصل أو يعيّن موضع مكونات التشبع اللوني بالنسبة إلى مكون الإضاءة.

القيمة: موضع مكونات التشبع اللوني بالنسبة لمكون الإضاءة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getYCbCrSubSampling() {#getYCbCrSubSampling--}
```
public int[] getYCbCrSubSampling()
```


يحصل أو يعيّن نسبة أخذ العينات لمكونات التشبع اللوني بالنسبة إلى مكون الإضاءة.

القيمة: نسبة أخذ العينات لمكونات التشبع اللوني بالنسبة لمكون الإضاءة.

**Returns:**
int[]
### setYCbCrSubSampling(int[] value) {#setYCbCrSubSampling-int---}
```
public void setYCbCrSubSampling(int[] value)
```


يحصل أو يعيّن نسبة أخذ العينات لمكونات التشبع اللوني بالنسبة إلى مكون الإضاءة.

القيمة: نسبة أخذ العينات لمكونات التشبع اللوني بالنسبة لمكون الإضاءة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] |  |

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


يقوم بتسلسل بيانات EXIF. يكتب قيم العلامات ومحتوياتها. العلامة التي تؤثر أكثر على الحجم هي محتويات علامة Thumbnail.

**Returns:**
byte[] - بيانات EXIF المتسلسلة.

يجب أن يكون حجم الجزء الكلي أقل من أو يساوي MaxExifSegmentSize بايت لضمان إنتاج صورة jpeg صحيحة. ملاحظة: حاول تقليل حجم الصورة المصغرة أو تغيير ضغطها في حال كان حجم قسم EXIF كبيرًا جدًا.
