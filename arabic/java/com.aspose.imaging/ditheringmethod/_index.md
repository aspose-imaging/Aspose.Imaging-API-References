---
title: "DitheringMethod"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "طريقة التخفيف."
type: docs
weight: 41
url: /ar/java/com.aspose.imaging/ditheringmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DitheringMethod extends System.Enum
```

طريقة التخفيف.
## الحقول

| حقل | الوصف |
| --- | --- |
| [ThresholdDithering](#ThresholdDithering) | تلوين بالعتبة. |
| [FloydSteinbergDithering](#FloydSteinbergDithering) | تلوين فلويد-شتاينبرغ. |

## Example: The following example loads a raster image and performs threshold and floyd dithering using different palette depth.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // نفّذ تلوين بالعتبة باستخدام لوحة ألوان 4-بت تحتوي على 16 لونًا.
    // كلما زادت عدد البتات المحددة، ارتفعت الجودة وزاد حجم الصورة الناتجة.
    // لاحظ أن لوحات الألوان 1-بت، 4-بت و8-بت فقط هي المدعومة حاليًا.
    rasterImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4);

    rasterImage.save(dir + "sample.ThresholdDithering4.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // نفّذ تلوين فلويد باستخدام لوحة ألوان 1-بت تحتوي فقط على لونين - أسود وأبيض.
    // كلما زادت عدد البتات المحددة، ارتفعت الجودة وزاد حجم الصورة الناتجة.
    // لاحظ أن لوحات الألوان 1-بت، 4-بت و8-بت فقط هي المدعومة حاليًا.
    rasterImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1);

    rasterImage.save(dir + "sample.FloydSteinbergDithering1.png");
} finally {
    image.dispose();
}
```

### ThresholdDithering {#ThresholdDithering}
```
public static final int ThresholdDithering
```


تدرج العتبة. أبسط وأسرع خوارزمية تدرج.

### FloydSteinbergDithering {#FloydSteinbergDithering}
```
public static final int FloydSteinbergDithering
```


تدرج فلويد-شتاينبرغ. خوارزمية تدرج أكثر تعقيدًا، تستخدم قيم شدة الجيران الأقرب.

