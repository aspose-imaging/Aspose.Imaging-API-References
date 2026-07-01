---
title: "MultiPageOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "الفئة الأساسية للأنساق التي تدعم صفحات متعددة"
type: docs
weight: 30
url: /ar/java/com.aspose.imaging.imageoptions/multipageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MultiPageOptions
```

الفئة الأساسية للأنساق التي تدعم صفحات متعددة
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MultiPageOptions()](#MultiPageOptions--) | يُنشئ مثيلًا جديدًا من الفئة `MultiPageOptions`. |
| [MultiPageOptions(int[] pages)](#MultiPageOptions-int---) | يُنشئ مثيلًا جديدًا من الفئة `MultiPageOptions`. |
| [MultiPageOptions(int[] pages, Rectangle exportArea)](#MultiPageOptions-int---com.aspose.imaging.Rectangle-) | يُنشئ مثيلًا جديدًا من الفئة `MultiPageOptions`. |
| [MultiPageOptions(String[] pageTitles)](#MultiPageOptions-java.lang.String---) | يُنشئ مثيلًا جديدًا من الفئة `MultiPageOptions`. |
| [MultiPageOptions(String[] pageTitles, Rectangle exportArea)](#MultiPageOptions-java.lang.String---com.aspose.imaging.Rectangle-) | يُنشئ مثيلًا جديدًا من الفئة `MultiPageOptions`. |
| [MultiPageOptions(IntRange[] ranges)](#MultiPageOptions-com.aspose.imaging.IntRange---) | يُنشئ مثيلًا جديدًا من الفئة `MultiPageOptions`. |
| [MultiPageOptions(IntRange[] ranges, Rectangle exportArea)](#MultiPageOptions-com.aspose.imaging.IntRange---com.aspose.imaging.Rectangle-) | يُنشئ مثيلًا جديدًا من الفئة `MultiPageOptions`. |
| [MultiPageOptions(IntRange range)](#MultiPageOptions-com.aspose.imaging.IntRange-) | يُنشئ مثيلًا جديدًا من الفئة `MultiPageOptions`. |
| [MultiPageOptions(IntRange range, Rectangle exportArea)](#MultiPageOptions-com.aspose.imaging.IntRange-com.aspose.imaging.Rectangle-) | يُنشئ مثيلًا جديدًا من الفئة `MultiPageOptions`. |
| [MultiPageOptions(int page)](#MultiPageOptions-int-) | يُنشئ مثيلًا جديدًا من الفئة `MultiPageOptions`. |
| [MultiPageOptions(int page, Rectangle exportArea)](#MultiPageOptions-int-com.aspose.imaging.Rectangle-) | يُنشئ مثيلًا جديدًا من الفئة `MultiPageOptions`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPages()](#getPages--) | يحصل أو يضبط الصفحات. |
| [setPages(int[] value)](#setPages-int---) | يحصل أو يضبط الصفحات. |
| [getPageTitles()](#getPageTitles--) | يحصل أو يضبط عناوين الصفحات. |
| [setPageTitles(String[] value)](#setPageTitles-java.lang.String---) | يحصل أو يضبط عناوين الصفحات. |
| [getTimeInterval()](#getTimeInterval--) | يحصل على الفاصل الزمني. |
| [setTimeInterval(TimeInterval value)](#setTimeInterval-com.aspose.imaging.imageoptions.TimeInterval-) | يضبط الفاصل الزمني. |
| [getPageRasterizationOptions()](#getPageRasterizationOptions--) | يحصل على خيارات تمثيل الصفحة. |
| [setPageRasterizationOptions(VectorRasterizationOptions[] value)](#setPageRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions---) | يضبط خيارات تمثيل الصفحة. |
| [getExportArea()](#getExportArea--) | يحصل أو يضبط منطقة التصدير. |
| [setExportArea(Rectangle value)](#setExportArea-com.aspose.imaging.Rectangle-) | يحصل أو يضبط منطقة التصدير. |
| [getMode()](#getMode--) | يحصل أو يضبط الوضع. |
| [setMode(int value)](#setMode-int-) | يحصل أو يضبط الوضع. |
| [getOutputLayersNames()](#getOutputLayersNames--) | يحصل أو يضبط أسماء طبقات الإخراج (يعمل إذا كان تنسيق التصدير يدعم تسمية الطبقات، على سبيل المثال لـ Psd) |
| [setOutputLayersNames(String[] value)](#setOutputLayersNames-java.lang.String---) | يحصل أو يضبط أسماء طبقات الإخراج (يعمل إذا كان تنسيق التصدير يدعم تسمية الطبقات، على سبيل المثال لـ Psd) |
| [getMergeLayers()](#getMergeLayers--) | يحصل على قيمة تشير إلى ما إذا كان سيتم [دمج الطبقات]. |
| [setMergeLayers(boolean value)](#setMergeLayers-boolean-) | يضبط قيمة تشير إلى ما إذا كان سيتم [دمج الطبقات]. |
| [initPages(IntRange[] ranges)](#initPages-com.aspose.imaging.IntRange---) | يُهيئ الصفحات من مصفوفة النطاقات |
### MultiPageOptions() {#MultiPageOptions--}
```
public MultiPageOptions()
```


يُنشئ مثيلًا جديدًا من الفئة `MultiPageOptions`.

### MultiPageOptions(int[] pages) {#MultiPageOptions-int---}
```
public MultiPageOptions(int[] pages)
```


يُنشئ مثيلًا جديدًا من الفئة `MultiPageOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الصفحات | int[] | الصفحات. |

### MultiPageOptions(int[] pages, Rectangle exportArea) {#MultiPageOptions-int---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(int[] pages, Rectangle exportArea)
```


يُنشئ مثيلًا جديدًا من الفئة `MultiPageOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الصفحات | int[] | مصفوفة الصفحات. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | منطقة التصدير. |

### MultiPageOptions(String[] pageTitles) {#MultiPageOptions-java.lang.String---}
```
public MultiPageOptions(String[] pageTitles)
```


يُنشئ مثيلًا جديدًا من الفئة `MultiPageOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageTitles | java.lang.String[] | عناوين الصفحات. |

### MultiPageOptions(String[] pageTitles, Rectangle exportArea) {#MultiPageOptions-java.lang.String---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(String[] pageTitles, Rectangle exportArea)
```


يُنشئ مثيلًا جديدًا من الفئة `MultiPageOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageTitles | java.lang.String[] | عناوين الصفحات. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | منطقة التصدير. |

### MultiPageOptions(IntRange[] ranges) {#MultiPageOptions-com.aspose.imaging.IntRange---}
```
public MultiPageOptions(IntRange[] ranges)
```


يُنشئ مثيلًا جديدًا من الفئة `MultiPageOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | الـ `IntRange`. |

### MultiPageOptions(IntRange[] ranges, Rectangle exportArea) {#MultiPageOptions-com.aspose.imaging.IntRange---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(IntRange[] ranges, Rectangle exportArea)
```


يُنشئ مثيلًا جديدًا من الفئة `MultiPageOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | الـ `IntRange`. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | منطقة التصدير. |

### MultiPageOptions(IntRange range) {#MultiPageOptions-com.aspose.imaging.IntRange-}
```
public MultiPageOptions(IntRange range)
```


يُنشئ مثيلًا جديدًا من الفئة `MultiPageOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.imaging/intrange) | الـ `IntRange`. |

### MultiPageOptions(IntRange range, Rectangle exportArea) {#MultiPageOptions-com.aspose.imaging.IntRange-com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(IntRange range, Rectangle exportArea)
```


يُنشئ مثيلًا جديدًا من الفئة `MultiPageOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.imaging/intrange) | الـ `IntRange`. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | منطقة التصدير. |

### MultiPageOptions(int page) {#MultiPageOptions-int-}
```
public MultiPageOptions(int page)
```


يُنشئ مثيلًا جديدًا من الفئة `MultiPageOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| صفحة | int | فهرس الصفحة. |

### MultiPageOptions(int page, Rectangle exportArea) {#MultiPageOptions-int-com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(int page, Rectangle exportArea)
```


يُنشئ مثيلًا جديدًا من الفئة `MultiPageOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| صفحة | int | فهرس الصفحة. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | منطقة التصدير. |

### getPages() {#getPages--}
```
public int[] getPages()
```


يحصل أو يضبط الصفحات.

القيمة: الصفحات.

**Returns:**
int[]
### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


يحصل أو يضبط الصفحات.

القيمة: الصفحات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int[] |  |


**Example: This example shows how to convert a multi-page DJVU image to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// تحميل صورة DJVU من تدفق ملف.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        com.aspose.imaging.imageoptions.TiffOptions saveOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // لاحظ أنه إذا كانت الصورة ملونة، فسيتم تحويلها تلقائيًا إلى صيغة أبيض/أسود وفقًا للخيار أدناه:
        saveOptions.setBitsPerSample(new int[]{1});

        saveOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.DjvuMultiPageOptions());

        // بشكل افتراضي، سيتم تخزين جميع الصفحات في ملف TIFF الناتج، ولكن يمكن تحديد مجموعة الصفحات المطلوبة صراحةً.
        // سيتم تصدير الصفحة الأولى والثانية فقط.
        saveOptions.getMultiPageOptions().setPages(new int[]{0, 1});

        // تعيين عناوين الصفحات.
        saveOptions.getMultiPageOptions().setPageTitles(new String[]{"The First Page", "The Second Page"});

        // حفظ إلى TIFF
        djvuImage.save(dir + "sample.tif", saveOptions);
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}
```

### getPageTitles() {#getPageTitles--}
```
public String[] getPageTitles()
```


يحصل أو يضبط عناوين الصفحات.

القيمة: عناوين الصفحات.

**Returns:**
java.lang.String[]
### setPageTitles(String[] value) {#setPageTitles-java.lang.String---}
```
public void setPageTitles(String[] value)
```


يحصل أو يضبط عناوين الصفحات.

القيمة: عناوين الصفحات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String[] |  |


**Example: This example shows how to convert a multi-page DJVU image to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// تحميل صورة DJVU من تدفق ملف.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        com.aspose.imaging.imageoptions.TiffOptions saveOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // لاحظ أنه إذا كانت الصورة ملونة، فسيتم تحويلها تلقائيًا إلى صيغة أبيض/أسود وفقًا للخيار أدناه:
        saveOptions.setBitsPerSample(new int[]{1});

        saveOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.DjvuMultiPageOptions());

        // بشكل افتراضي، سيتم تخزين جميع الصفحات في ملف TIFF الناتج، ولكن يمكن تحديد مجموعة الصفحات المطلوبة صراحةً.
        // سيتم تصدير الصفحة الأولى والثانية فقط.
        saveOptions.getMultiPageOptions().setPages(new int[]{0, 1});

        // تعيين عناوين الصفحات.
        saveOptions.getMultiPageOptions().setPageTitles(new String[]{"The First Page", "The Second Page"});

        // حفظ إلى TIFF
        djvuImage.save(dir + "sample.tif", saveOptions);
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}
```

### getTimeInterval() {#getTimeInterval--}
```
public final TimeInterval getTimeInterval()
```


يحصل على الفاصل الزمني.

القيمة: الفاصل الزمني.

**Returns:**
[TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) - the time interval.
### setTimeInterval(TimeInterval value) {#setTimeInterval-com.aspose.imaging.imageoptions.TimeInterval-}
```
public final void setTimeInterval(TimeInterval value)
```


يضبط الفاصل الزمني.

القيمة: الفاصل الزمني.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) | الفاصل الزمني. |

### getPageRasterizationOptions() {#getPageRasterizationOptions--}
```
public final VectorRasterizationOptions[] getPageRasterizationOptions()
```


يحصل على خيارات تمثيل الصفحة.

**Returns:**
com.aspose.imaging.imageoptions.VectorRasterizationOptions[] - خيارات تمثيل الصفحة.
### setPageRasterizationOptions(VectorRasterizationOptions[] value) {#setPageRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions---}
```
public final void setPageRasterizationOptions(VectorRasterizationOptions[] value)
```


يضبط خيارات تمثيل الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [VectorRasterizationOptions\[\]](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | خيارات تمثيل الصفحة. |

### getExportArea() {#getExportArea--}
```
public Rectangle getExportArea()
```


يحصل أو يضبط منطقة التصدير.

القيمة: منطقة التصدير.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setExportArea(Rectangle value) {#setExportArea-com.aspose.imaging.Rectangle-}
```
public void setExportArea(Rectangle value)
```


يحصل أو يضبط منطقة التصدير.

القيمة: منطقة التصدير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getMode() {#getMode--}
```
public int getMode()
```


يحصل أو يضبط الوضع.

القيمة: الوضع.

**Returns:**
int
### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


يحصل أو يضبط الوضع.

القيمة: الوضع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getOutputLayersNames() {#getOutputLayersNames--}
```
public String[] getOutputLayersNames()
```


يحصل أو يضبط أسماء طبقات الإخراج (يعمل إذا كان تنسيق التصدير يدعم تسمية الطبقات، على سبيل المثال لـ Psd)

القيمة: أسماء طبقات الإخراج.

**Returns:**
java.lang.String[]
### setOutputLayersNames(String[] value) {#setOutputLayersNames-java.lang.String---}
```
public void setOutputLayersNames(String[] value)
```


يحصل أو يضبط أسماء طبقات الإخراج (يعمل إذا كان تنسيق التصدير يدعم تسمية الطبقات، على سبيل المثال لـ Psd)

القيمة: أسماء طبقات الإخراج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMergeLayers() {#getMergeLayers--}
```
public final boolean getMergeLayers()
```


يحصل على قيمة تشير إلى ما إذا كان سيتم [دمج الطبقات].

القيمة: `true` إذا تم [merge layers]؛ وإلا `false`.

**Returns:**
منطقي - قيمة تشير إلى ما إذا كان [merge layers].
### setMergeLayers(boolean value) {#setMergeLayers-boolean-}
```
public final void setMergeLayers(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان سيتم [دمج الطبقات].

القيمة: `true` إذا تم [merge layers]؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | قيمة تشير إلى ما إذا كان [merge layers]. |

### initPages(IntRange[] ranges) {#initPages-com.aspose.imaging.IntRange---}
```
public void initPages(IntRange[] ranges)
```


يُهيئ الصفحات من مصفوفة النطاقات

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | النطاقات. |

