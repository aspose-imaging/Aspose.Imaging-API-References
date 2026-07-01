---
title: "PngColorType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل نوع لون صورة PNG."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.png/pngcolortype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PngColorType extends System.Enum
```

يمثل نوع لون صورة PNG.
## الحقول

| حقل | الوصف |
| --- | --- |
| [Grayscale](#Grayscale) | يمثل نوع اللون حيث كل بكسل هو عينة تدرج رمادي. |
| [Truecolor](#Truecolor) | يمثل نوع اللون حيث كل بكسل هو ثلاثية R,G,B. |
| [IndexedColor](#IndexedColor) | يمثل نوع اللون حيث كل بكسل هو فهرس لوحة ألوان؛ يجب أن يظهر جزء PLTE. |
| [GrayscaleWithAlpha](#GrayscaleWithAlpha) | يمثل نوع اللون حيث كل بكسل هو عينة تدرج رمادي تليها عينة ألفا. |
| [TruecolorWithAlpha](#TruecolorWithAlpha) | يمثل نوع اللون حيث كل بكسل هو ثلاثية R,G,B تليها عينة ألفا. |

## Example: The following example shows how to compress a PNG image, using indexed color with best fit palette

``` java

// يحمّل صورة png        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // استخدم نوع اللون المفهرس
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // استخدم أقصى ضغط
    options.setCompressionLevel(9);
    // احصل على أقرب لوحة ألوان 8‑بت تغطي أكبر عدد ممكن من البكسلات، بحيث تكون الصورة مُلوَّنة بلوحة ألوان.
    // يكاد يكون غير قابل للتمييز بصريًا عن نسخة غير ملوّنة.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// يجب تقليل حجم ملف الإخراج بشكل كبير
```

### Grayscale {#Grayscale}
```
public static final int Grayscale
```


يمثل نوع اللون حيث كل بكسل هو عينة تدرج رمادي.

### Truecolor {#Truecolor}
```
public static final int Truecolor
```


يمثل نوع اللون حيث كل بكسل هو ثلاثية R,G,B.

### IndexedColor {#IndexedColor}
```
public static final int IndexedColor
```


يمثل نوع اللون حيث كل بكسل هو فهرس لوحة ألوان؛ يجب أن يظهر جزء PLTE.

### GrayscaleWithAlpha {#GrayscaleWithAlpha}
```
public static final int GrayscaleWithAlpha
```


يمثل نوع اللون حيث كل بكسل هو عينة تدرج رمادي تليها عينة ألفا.

### TruecolorWithAlpha {#TruecolorWithAlpha}
```
public static final int TruecolorWithAlpha
```


يمثل نوع اللون حيث كل بكسل هو ثلاثية R,G,B تليها عينة ألفا.

