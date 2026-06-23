---
title: "ManualMaskingArgs"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل الوسائط المحددة لطريقة القناع اليدوية."
type: docs
weight: 15
url: /ar/java/com.aspose.imaging.masking.options/manualmaskingargs/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.masking.options.IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs)
```
public class ManualMaskingArgs implements IMaskingArgs
```

يمثل الوسائط المحددة لطريقة القناع اليدوية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ManualMaskingArgs()](#ManualMaskingArgs--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getMask()](#getMask--) | يحصل على مجموعة الأشكال الرسومية التي تُشكل القناع. |
| [setMask(GraphicsPath value)](#setMask-com.aspose.imaging.GraphicsPath-) | يضبط مجموعة الأشكال الرسومية التي تشكل القناع. |

## Example: This example shows how to decompose a raster image into multiple images using image masking and a manual mask.
يوضح هذا المثال كيفية تفكيك صورة نقطية إلى صور متعددة باستخدام قناع الصورة وقناع يدوي. قناع الصورة هو تقنية معالجة صور تُستخدم لتقسيم الخلفية عن كائنات الصورة في المقدمة.
``` java
String dir = "c:\\temp\\";

// حدد قناعًا يدويًا.
com.aspose.imaging.GraphicsPath manualMask = new com.aspose.imaging.GraphicsPath();
com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();
figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 40, 40)));
figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 20, 50, 30)));
manualMask.addFigure(figure);

// اضبط القناع اليدوي.
com.aspose.imaging.masking.options.ManualMaskingArgs args = new com.aspose.imaging.masking.options.ManualMaskingArgs();
args.setMask(manualMask);

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Blue hills.png");
try {
    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // استخدم خوارزمية التجميع اليدوي.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.Manual);

    // جميع الأشكال التي تُكوّن القناع سيتم دمجها في واحد.
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // أقصى حجم متوقع لصورة PNG بنظام TrueColor مع قناة Alpha.
    int estimatedMaxImageSize = image.getWidth() * image.getHeight() * 4;

    // سيتم تخزين كل مجموعة (مقطع) في ملف PNG منفصل.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[estimatedMaxImageSize])));

    // لون الخلفية سيكون برتقاليًا.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // منطقة صورة المصدر التي سيُطبق عليها القناع.
    maskingOptions.setMaskingArea(new com.aspose.imaging.Rectangle(50, 50, 120, 120));

    // إنشاء نسخة من فئة ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // قسّم الصورة المصدر إلى عدة مجموعات (قطاعات).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // احصل على الصور من نتيجة القناع واحفظها بصيغة PNG.
        for (int i = 0; i < maskingResults.getLength(); i++) {
            String outputFileName = String.format("Blue hills.Segment%s.png", maskingResults.get_Item(i).getObjectNumber());
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

### ManualMaskingArgs() {#ManualMaskingArgs--}
```
public ManualMaskingArgs()
```


### getMask() {#getMask--}
```
public final GraphicsPath getMask()
```


يحصل على مجموعة الأشكال الرسومية التي تُشكل القناع.

القيمة: القناع.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - the set of graphic shapes that form mask.
### setMask(GraphicsPath value) {#setMask-com.aspose.imaging.GraphicsPath-}
```
public final void setMask(GraphicsPath value)
```


يضبط مجموعة الأشكال الرسومية التي تشكل القناع.

القيمة: القناع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | مجموعة الأشكال الرسومية التي تشكل القناع. |

