---
title: "MaskingResult"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "الفئة الأساسية المجردة التي يمكنها توفير صورة النتيجة من نظام إخفاء الصور."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.masking.result/maskingresult/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)

**All Implemented Interfaces:**
java.lang.Iterable
```
public abstract class MaskingResult extends DisposableObject implements Iterable<IMaskingLayer>
```

الفئة الأساسية المجردة التي يمكنها توفير صورة النتيجة من نظام إخفاء الصور.
## الحقول

| حقل | الوصف |
| --- | --- |
| [MaskingOptions](#MaskingOptions) | خيارات القناع |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLayers()](#getLayers--) | يحصل على الطبقات. |
| [getLength()](#getLength--) | يحصل على الطول. |
| [get_Item(int index)](#get-Item-int-) | يحصل على [IMaskingLayer](../../com.aspose.imaging.masking.result/imaskinglayer) في الفهرس المحدد. |
| [iterator()](#iterator--) | يحصل على المُعدِّد. |

## Example: This example shows how to decompose a raster image into multiple images using image masking and the K-means segmentation algorithm.
يُظهر هذا المثال كيفية تفكيك صورة نقطية إلى صور متعددة باستخدام قناع الصورة وخوارزمية تجزئة K-means. قناع الصورة هو تقنية معالجة صور تُستخدم لفصل الخلفية عن كائنات الصورة في المقدمة.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Blue hills.png");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // حدد عدد العناقيد (الكائنات المفصولة). القيمة الافتراضية هي 2، كائن المقدمة والخلفية.
    args.setNumberOfObjects(3);

    // حدد الحد الأقصى لعدد التكرارات.
    args.setMaxIterationNumber(50);

    // حدد دقة طريقة التجزئة (اختياري).
    args.setPrecision(1);

    // سيتم تخزين كل عنقود (قطاع) في ملف PNG منفصل.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // استخدم تجميع K-means.
    // يتيح تجميع K-means تقسيم الصورة إلى عدة عناقيد (قطاعات) مستقلة.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.KMeans);
    maskingOptions.setDecompose(true);
    maskingOptions.setArgs(args);

    // لون الخلفية سيكون برتقاليًا.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // إنشاء نسخة من الفئة ImageMasking.
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
يُظهر هذا المثال كيفية تحديد الاقتراحات لخوارزمية قناع الصورة لتحسين دقة طريقة التجزئة (التجميع). قناع الصورة هو تقنية معالجة صور تُستخدم لفصل الخلفية عن كائنات الصورة في المقدمة.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // الاقتراح #1.
    // حلل الصورة بصريًا وحدد منطقة الاهتمام. سيتضمن نتيجة التجزئة فقط الكائنات التي تقع بالكامل داخل هذه المنطقة.
    args.setObjectsRectangles(new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(86, 6, 270, 364),
            });

    // الاقتراح #2.
    // حلل الصورة بصريًا وحدد النقاط التي تنتمي إلى الكائنات المفصولة.
    args.setObjectsPoints(new com.aspose.imaging.Point[][]
            {
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(103, 326)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(280, 43)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(319, 86)},
            });

    // سيتم تخزين كل عنقود (قطاع) في ملف PNG منفصل.
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

    // إنشاء نسخة من الفئة ImageMasking.
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

    // إنشاء نسخة من الفئة ImageMasking.
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
    // إنشاء نسخة من الفئة ImageMasking.
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

// استئناف جلسة تمويه من ملف
com.aspose.imaging.RasterImage image2 = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // إنشاء نسخة من الفئة ImageMasking.
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

### MaskingOptions {#MaskingOptions}
```
public final MaskingOptions MaskingOptions
```


خيارات القناع

### getLayers() {#getLayers--}
```
public abstract IMaskingLayer[] getLayers()
```


يحصل على الطبقات.

القيمة: الطبقات.

**Returns:**
com.aspose.imaging.masking.result.IMatchingLayer[] - الطبقات.
### getLength() {#getLength--}
```
public final int getLength()
```


يحصل على الطول.

القيمة: الطول.

**Returns:**
int - الطول.

**Example: This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method.**
يُظهر هذا المثال كيفية تحديد الاقتراحات لخوارزمية قناع الصورة لتحسين دقة طريقة التجزئة (التجميع). قناع الصورة هو تقنية معالجة صور تُستخدم لفصل الخلفية عن كائنات الصورة في المقدمة.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // الاقتراح #1.
    // حلل الصورة بصريًا وحدد منطقة الاهتمام. سيتضمن نتيجة التجزئة فقط الكائنات التي تقع بالكامل داخل هذه المنطقة.
    args.setObjectsRectangles(new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(86, 6, 270, 364),
            });

    // الاقتراح #2.
    // حلل الصورة بصريًا وحدد النقاط التي تنتمي إلى الكائنات المفصولة.
    args.setObjectsPoints(new com.aspose.imaging.Point[][]
            {
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(103, 326)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(280, 43)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(319, 86)},
            });

    // سيتم تخزين كل عنقود (قطاع) في ملف PNG منفصل.
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

    // إنشاء نسخة من الفئة ImageMasking.
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

### get_Item(int index) {#get-Item-int-}
```
public final IMaskingLayer get_Item(int index)
```


يحصل على [IMaskingLayer](../../com.aspose.imaging.masking.result/imaskinglayer) في الفهرس المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس. القيمة: الـ [IMaskingLayer](../../com.aspose.imaging.masking.result/imatchinglayer). |

**Returns:**
[IMaskingLayer](../../com.aspose.imaging.masking.result/imaskinglayer) - The masking layer.
### iterator() {#iterator--}
```
public final Iterator<IMaskingLayer> iterator()
```


يحصل على المُعدِّد.

**Returns:**
java.util.Iterator<com.aspose.imaging.masking.result.IMatchingLayer> - المُعدِّد.
