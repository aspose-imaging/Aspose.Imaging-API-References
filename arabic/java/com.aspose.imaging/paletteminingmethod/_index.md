---
title: "PaletteMiningMethod"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "طريقة استخراج لوحة ألوان الصورة"
type: docs
weight: 79
url: /ar/java/com.aspose.imaging/paletteminingmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PaletteMiningMethod extends System.Enum
```

طريقة استخراج لوحة ألوان الصورة
## الحقول

| حقل | الوصف |
| --- | --- |
| [UseCurrentPalette](#UseCurrentPalette) | استخدم لوحة الألوان الموجودة في الصورة |
| [ColorClustering](#ColorClustering) | طريقة تجميع الألوان |
| [Histogram](#Histogram) | طريقة الرسم البياني |

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

### UseCurrentPalette {#UseCurrentPalette}
```
public static final int UseCurrentPalette
```


استخدم لوحة الألوان الموجودة في الصورة

### ColorClustering {#ColorClustering}
```
public static final int ColorClustering
```


طريقة تجميع الألوان

### Histogram {#Histogram}
```
public static final int Histogram
```


طريقة الرسم البياني

