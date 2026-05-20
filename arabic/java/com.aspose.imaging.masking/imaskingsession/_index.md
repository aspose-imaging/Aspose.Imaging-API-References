---
title: "IMatchingSession"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "جلسة التمويه"
type: docs
weight: 12
url: /ar/java/com.aspose.imaging.masking/imaskingsession/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public interface IMaskingSession extends System.IDisposable
```

جلسة التمويه
## الطرق

| طريقة | الوصف |
| --- | --- |
| [decompose()](#decompose--) | ينفّذ عملية تفكيك أولية تقريبية |
| [decomposeAsync()](#decomposeAsync--) | ينشئ المهمة غير المتزامنة التي يمكنها تنفيذ عملية تفكيك أولية تقريبية |
| [improveDecomposition(IMaskingArgs maskingArguments)](#improveDecomposition-com.aspose.imaging.masking.options.IMaskingArgs-) | ينفّذ عملية تفكيك لإعادة التدريب |
| [improveDecompositionAsync(IMaskingArgs maskingArguments)](#improveDecompositionAsync-com.aspose.imaging.masking.options.IMaskingArgs-) | ينشئ المهمة غير المتزامنة التي يمكنها تنفيذ عملية تفكيك لإعادة التدريب |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | احفظ حالة الجلسة إلى الدفق المحدد. |
| [save(System.IO.Stream stream)](#save-com.aspose.ms.System.IO.Stream-) | احفظ حالة الجلسة إلى الدفق المحدد. |
| [save(String filePath)](#save-java.lang.String-) | يحفظ حالة الجلسة إلى الملف المحدد. |

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

### decompose() {#decompose--}
```
public abstract MaskingResult decompose()
```


ينفّذ عملية تفكيك أولية تقريبية

**Returns:**
[MaskingResult](../../com.aspose.imaging.masking.result/maskingresult) - Result of masking operation as array of segment image providers.

**Example: Saving the masking session to a file for long sessions, as well as for the possibility of resuming the session in another environment.**

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

### decomposeAsync() {#decomposeAsync--}
```
public abstract IMaskingAsyncTask decomposeAsync()
```


ينشئ المهمة غير المتزامنة التي يمكنها تنفيذ عملية تفكيك أولية تقريبية

**Returns:**
[IMaskingAsyncTask](../../com.aspose.imaging.masking/imaskingasynctask) - The asynchronous decompose task
### improveDecomposition(IMaskingArgs maskingArguments) {#improveDecomposition-com.aspose.imaging.masking.options.IMaskingArgs-}
```
public abstract MaskingResult improveDecomposition(IMaskingArgs maskingArguments)
```


ينفّذ عملية تفكيك لإعادة التدريب

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| maskingArguments | [IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs) | معاملات التمويه. |

**Returns:**
[MaskingResult](../../com.aspose.imaging.masking.result/maskingresult) - Result of masking operation as array of segment image providers.

**Example: Saving the masking session to a file for long sessions, as well as for the possibility of resuming the session in another environment.**

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

### improveDecompositionAsync(IMaskingArgs maskingArguments) {#improveDecompositionAsync-com.aspose.imaging.masking.options.IMaskingArgs-}
```
public abstract IMaskingAsyncTask improveDecompositionAsync(IMaskingArgs maskingArguments)
```


ينشئ المهمة غير المتزامنة التي يمكنها تنفيذ عملية تفكيك لإعادة التدريب

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| maskingArguments | [IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs) | معاملات التمويه. |

**Returns:**
[IMaskingAsyncTask](../../com.aspose.imaging.masking/imaskingasynctask) - The asynchronous decompose task
### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public abstract void save(OutputStream stream)
```


احفظ حالة الجلسة إلى الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.OutputStream | المجرى. |

### save(System.IO.Stream stream) {#save-com.aspose.ms.System.IO.Stream-}
```
public abstract void save(System.IO.Stream stream)
```


احفظ حالة الجلسة إلى الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | com.aspose.ms.System.IO.Stream | المجرى. |

### save(String filePath) {#save-java.lang.String-}
```
public abstract void save(String filePath)
```


يحفظ حالة الجلسة إلى الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف. |

