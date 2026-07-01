---
title: "AutoMaskingArgs"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل الوسائط المحددة لطرق القناع الآلية"
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.masking.options/automaskingargs/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.masking.options.IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

يمثل الوسائط المحددة لطرق القناع الآلية
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getNumberOfObjects()](#getNumberOfObjects--) | يحصل على عدد الكائنات لتقسيم الصورة الأولية إليها (اختياري)، القيمة الافتراضية هي 2 (كائن والخلفية). |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | يضبط عدد الكائنات لتقسيم الصورة الأولية إليها (اختياري)، القيمة الافتراضية هي 2 (كائن والخلفية). |
| [getObjectsRectangles()](#getObjectsRectangles--) | يحصل على مستطيلات الكائنات التي تنتمي إلى الكائنات المفصولة (اختياري). |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.imaging.Rectangle---) | يضبط مستطيلات الكائنات التي تنتمي إلى الكائنات المفصولة (اختياري). |
| [getObjectsPoints()](#getObjectsPoints--) | يحصل على النقاط التي تنتمي إلى الكائنات المفصولة (اختياري) إحداثيات NumberOfObjects التي تنتمي إلى كائنات NumberOfObjects في الصورة الأولية. |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.imaging.Point-----) | يضبط النقاط التي تنتمي إلى الكائنات المفصولة (اختياري) إحداثيات NumberOfObjects التي تنتمي إلى كائنات NumberOfObjects في الصورة الأولية. |
| [getOrphanedPoints()](#getOrphanedPoints--) | يحصل على النقاط التي لم تعد تنتمي إلى أي كائن (اختياري). |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.imaging.Point---) | يضبط النقاط التي لم تعد تنتمي إلى أي كائن (اختياري). |
| [getPrecision()](#getPrecision--) | يحصل على دقة طريقة التقسيم (اختياري). |
| [setPrecision(double value)](#setPrecision-double-) | يضبط دقة طريقة التقسيم (اختياري). |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | يحصل على الحد الأقصى لعدد التكرارات. |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | يضبط الحد الأقصى لعدد التكرارات. |

## Example: This example shows how to decompose a raster image into multiple images using image masking and the K-means segmentation algorithm.
يوضح هذا المثال كيفية تفكيك صورة نقطية إلى عدة صور باستخدام قناع الصورة وخوارزمية تجزئة K-means. قناع الصورة هو تقنية معالجة صور تُستخدم لتقسيم الخلفية عن كائنات الصورة في المقدمة.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Blue hills.png");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // حدد عدد المجموعات (الكائنات المفصولة). القيمة الافتراضية هي 2، كائن المقدمة والخلفية.
    args.setNumberOfObjects(3);

    // حدد الحد الأقصى لعدد التكرارات.
    args.setMaxIterationNumber(50);

    // حدد دقة طريقة التجزئة (اختياري).
    args.setPrecision(1);

    // سيتم تخزين كل مجموعة (مقطع) في ملف PNG منفصل.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // استخدم تجميع K-means.
    // يتيح تجميع K-means تقسيم الصورة إلى عدة مجموعات مستقلة (مقاطع).
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.KMeans);
    maskingOptions.setDecompose(true);
    maskingOptions.setArgs(args);

    // لون الخلفية سيكون برتقاليًا.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // إنشاء نسخة من فئة ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // قسّم الصورة المصدر إلى عدة مجموعات (قطاعات).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);
    try
    {
        // احصل على الصور من نتيجة القناع واحفظها بصيغة PNG.
        for (int i = 0; i < maskingResults.getLength(); i++) {
            final IMaskingLayer resultsItem = maskingResults.get_Item(i);
            String outputFileName = String.format("Blue hills.Segment%s.png", resultsItem.getObjectNumber());
            Image resultImage = resultsItem.getImage();
            try {
                resultImage.save(dir + outputFileName);
            } finally {
                resultImage.close();
            }
        }
    }
    finally
    {
        maskingResults.close();
    }
} finally {
    image.close();
}
```


## Example: This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method.
يوضح هذا المثال كيفية تحديد اقتراحات لخوارزمية قناع الصورة لتحسين دقة طريقة التجزئة (التجميع). قناع الصورة هو تقنية معالجة صور تُستخدم لتقسيم الخلفية عن كائنات الصورة في المقدمة.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // اقتراح #1.
    // حلل الصورة بصريًا وحدد منطقة الاهتمام. نتيجة التجزئة ستشمل فقط الكائنات التي تقع بالكامل داخل هذه المنطقة.
    args.setObjectsRectangles(new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(86, 6, 270, 364),
            });

    // اقتراح #2.
    // حلل الصورة بصريًا وحدد النقاط التي تنتمي إلى الكائنات المفصولة.
    args.setObjectsPoints(new com.aspose.imaging.Point[][]
            {
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(103, 326)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(280, 43)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(319, 86)},
            });

    // سيتم تخزين كل مجموعة (مقطع) في ملف PNG منفصل.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // استخدم تجميع GraphCut.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // لون الخلفية سيكون برتقاليًا.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // إنشاء نسخة من فئة ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // قسّم الصورة المصدر إلى عدة مجموعات (قطاعات).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // احصل على الصور من نتيجة القناع واحفظها بصيغة PNG.
        for (int i = 0; i < maskingResults.getLength(); i++) {
            String outputFileName = String.format("Gorilla.Segment%s.png", maskingResults.get_Item(i).getObjectNumber());
            Image resultImage = maskingResults.get_Item(i).getImage();
            try {
                resultImage.save(dir + outputFileName);
            } finally {
                resultImage.close();
            }
        }
    }
    finally
    {
        maskingResults.close();
    }
} finally {
    image.close();
}
```


## Example: Using a segment mask to speed up the segmentation process

``` java
// خيارات تصدير القناع
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// استخدم تجميع GraphCut.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// لون الخلفية سيكون شفافًا.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getTransparent());
maskingOptions.setExportOptions(exportOptions);

String dir = "c:\\temp\\";
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
try
{
    com.aspose.imaging.Size imageSize = image.getSize();

    // تقليل حجم الصورة لتسريع عملية التجزئة
    image.resizeHeightProportionally(600, com.aspose.imaging.ResizeType.HighQualityResample);

    // إنشاء نسخة من فئة ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // قسّم الصورة المصدر إلى عدة مجموعات (قطاعات).
    com.aspose.imaging.masking.result.MaskingResult maskingResult = masking.decompose(maskingOptions);
    try
    {
        // الحصول على قناع المقدمة
        com.aspose.imaging.RasterImage foregroundMask = maskingResult.get_Item(1).getMask();
        try
        {
            // زيادة حجم القناع إلى حجم الصورة الأصلية
            foregroundMask.resize(imageSize.getWidth(), imageSize.getHeight(), com.aspose.imaging.ResizeType.NearestNeighbourResample);

            // تطبيق القناع على الصورة الأصلية للحصول على قطاع مقدمة
            com.aspose.imaging.RasterImage originImage = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
            try
            {
                com.aspose.imaging.masking.ImageMasking.applyMask(originImage, foregroundMask, maskingOptions);
                originImage.save(dir + "BigImage_foreground.png", exportOptions);
            }
            finally
            {
                originImage.close();
            }
        }
        finally
        {
            foregroundMask.close();
        }
    }
    finally
    {
        maskingResult.close();
    }
}
finally
{
    image.close();
}
```


## Example: Saving the masking session to a file for long sessions, as well as for the possibility of resuming the session in another environment.

``` java
String dir = "c:\\temp\\";
String sessionBackupFile = dir + "session.bak";

// خيارات تصدير القناع
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// استخدم تجميع GraphCut.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// لون الخلفية سيكون برتقاليًا.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
maskingOptions.setExportOptions(exportOptions);

// بدء جلسة للمرة الأولى وحفظها إلى ملف
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // إنشاء نسخة من فئة ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    com.aspose.imaging.masking.IMaskingSession session = masking.createSession(maskingOptions);
    try
    {
        com.aspose.imaging.masking.result.MaskingResult maskingResult = session.decompose();
        try
        {
            com.aspose.imaging.RasterImage segmentImage = maskingResult.get_Item(1).getImage();
            try
            {
                segmentImage.save(dir + "step1.png");
            }
            finally
            {
                segmentImage.close();
            }
        }
        finally
        {
            maskingResult.close();
        }

        session.save(sessionBackupFile);
    }
    finally
    {
        session.dispose();
    }
}
finally
{
    image.close();
}

// استئناف جلسة القناع من ملف
com.aspose.imaging.RasterImage image2 = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // إنشاء نسخة من فئة ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image2);

    com.aspose.imaging.masking.IMaskingSession session = masking.loadSession(sessionBackupFile);
    try
    {
        com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

        // حلل الصورة بصريًا وحدد النقاط التي تنتمي إلى الكائنات المفصولة.
        args.setObjectsPoints(new Point[][]
                {
                        new Point[]
                                {
                                        new Point(0, 0), new Point(0, 1), new Point(1, 0),
                                        new Point(1, 1), new Point(2, 0), new Point(2, 1),
                                        new Point(3, 0), new Point(3, 1)
                                },
                });
        com.aspose.imaging.masking.result.MaskingResult maskingResult = session.improveDecomposition(args);
        try
        {
            // نقل صريح لخيارات التصدير، لأنها غير قابلة للتسلسل
            maskingResult.MaskingOptions.setExportOptions(exportOptions);

            com.aspose.imaging.RasterImage segmentImage = maskingResult.get_Item(1).getImage();
            try
            {
                segmentImage.save(dir + "step2.png");
            }
            finally
            {
                segmentImage.close();
            }
        }
        finally
        {
            maskingResult.close();
        }
    }
    finally
    {
        session.dispose();
    }
}
finally
{
    image2.close();
}
```

### AutoMaskingArgs() {#AutoMaskingArgs--}
```
public AutoMaskingArgs()
```


### getNumberOfObjects() {#getNumberOfObjects--}
```
public final int getNumberOfObjects()
```


يحصل على عدد الكائنات لتقسيم الصورة الأولية إليها (اختياري)، القيمة الافتراضية هي 2 (كائن والخلفية).

القيمة: عدد الكائنات.

**Returns:**
int - عدد الكائنات لتقسيم الصورة الأولية إليها (اختياري)، القيمة الافتراضية هي 2 (كائن والخلفية).
### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


يضبط عدد الكائنات لتقسيم الصورة الأولية إليها (اختياري)، القيمة الافتراضية هي 2 (كائن والخلفية).

القيمة: عدد الكائنات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | عدد الكائنات لتقسيم الصورة الأولية إليها (اختياري)، القيمة الافتراضية هي 2 (كائن والخلفية). |

### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


يحصل على مستطيلات الكائنات التي تنتمي إلى كائنات منفصلة (اختياري). يُستخدم هذا المعامل لزيادة دقة طريقة التجزئة.

القيمة: مستطيلات الكائنات.

**Returns:**
com.aspose.imaging.Rectangle[] - مستطيلات الكائنات التي تنتمي إلى كائنات منفصلة (اختياري).
### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.imaging.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


يضبط مستطيلات الكائنات التي تنتمي إلى كائنات منفصلة (اختياري). يُستخدم هذا المعامل لزيادة دقة طريقة التجزئة.

القيمة: مستطيلات الكائنات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) | مستطيلات الكائنات التي تنتمي إلى كائنات منفصلة (اختياري). |

### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


يحصل على النقاط التي تنتمي إلى كائنات منفصلة (اختياري) إحداثيات NumberOfObjects التي تنتمي إلى كائنات NumberOfObjects من الصورة الأصلية. يُستخدم هذا المعامل لزيادة دقة طريقة التجزئة.

القيمة: نقاط الكائنات.

**Returns:**
com.aspose.imaging.Point[][] - النقاط التي تنتمي إلى كائنات منفصلة (اختياري) إحداثيات NumberOfObjects التي تنتمي إلى كائنات NumberOfObjects من الصورة الأصلية.
### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.imaging.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


يضبط النقاط التي تنتمي إلى كائنات منفصلة (اختياري) إحداثيات NumberOfObjects التي تنتمي إلى كائنات NumberOfObjects من الصورة الأصلية. يُستخدم هذا المعامل لزيادة دقة طريقة التجزئة.

القيمة: نقاط الكائنات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) | النقاط التي تنتمي إلى كائنات منفصلة (اختياري) إحداثيات NumberOfObjects التي تنتمي إلى كائنات NumberOfObjects من الصورة الأصلية. |

### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


يحصل على النقاط التي لم تعد تنتمي إلى أي كائن (اختياري). يُستخدم هذا المعامل فقط في حالة إعادة التجزئة.

القيمة: النقاط اليتيمة.

**Returns:**
com.aspose.imaging.Point[] - النقاط التي لم تعد تنتمي إلى أي كائن (اختياري).
### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.imaging.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


يضبط النقاط التي لم تعد تنتمي إلى أي كائن (اختياري). يُستخدم هذا المعامل فقط في حالة إعادة التجزئة.

القيمة: النقاط اليتيمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) | النقاط التي لم تعد تنتمي إلى أي كائن (اختياري). |

### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


يحصل على دقة طريقة التقسيم (اختياري).

القيمة: دقة طريقة التجزئة (اختياري).

**Returns:**
double - دقة طريقة التجزئة (اختياري).
### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


يضبط دقة طريقة التقسيم (اختياري).

القيمة: دقة طريقة التجزئة (اختياري).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | double | دقة طريقة التجزئة (اختياري). |

### getMaxIterationNumber() {#getMaxIterationNumber--}
```
public final int getMaxIterationNumber()
```


يحصل على الحد الأقصى لعدد التكرارات.

القيمة: الحد الأقصى الأقصى لعدد التكرارات.

**Returns:**
int - الحد الأقصى لعدد التكرارات.
### setMaxIterationNumber(int value) {#setMaxIterationNumber-int-}
```
public final void setMaxIterationNumber(int value)
```


يضبط الحد الأقصى لعدد التكرارات.

القيمة: الحد الأقصى الأقصى لعدد التكرارات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | الحد الأقصى لعدد التكرارات. |

