---
title: "PdfImageCompressionOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "خيارات ضغط صور PDF"
type: docs
weight: 35
url: /ar/java/com.aspose.imaging.imageoptions/pdfimagecompressionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfImageCompressionOptions extends System.Enum
```

خيارات ضغط صور PDF
## الحقول

| حقل | الوصف |
| --- | --- |
| [Auto](#Auto) | يختار تلقائيًا الضغط الأنسب لكل صورة. |
| [None](#None) | يحفظ بايتات الصورة الخام مما يؤدي إلى أحجام ملفات PDF أكبر. |
| [Rle](#Rle) | ضغط طول التشغيل. |
| [Flate](#Flate) | ضغط Flate. |
| [LzwBaselinePredictor](#LzwBaselinePredictor) | اختيار المتنبئ مقيد بـ PNG Paeth predictor لتسريع العملية. |
| [LzwOptimizedPredictor](#LzwOptimizedPredictor) | اختيار المتنبئ أكثر تعقيدًا ويجب أن ينتج أحجام صور أصغر لكنه يستغرق وقتًا أطول. |
| [Jpeg](#Jpeg) | ضغط Jpeg. |
| [Ccitt3](#Ccitt3) | /CCITTFaxDecode/DecodeParms/K 0/Columns 173 لا يدعم الشفافية. |
| [Ccitt4](#Ccitt4) | /CCITTFaxDecode/DecodeParms/K -1/Columns 173 لا يدعم الشفافية. |
### Auto {#Auto}
```
public static final int Auto
```


يختار تلقائيًا الضغط الأنسب لكل صورة.

### None {#None}
```
public static final int None
```


يحفظ بايتات الصورة الخام مما يؤدي إلى أحجام ملفات PDF أكبر.

### Rle {#Rle}
```
public static final int Rle
```


ضغط طول التشغيل.

### Flate {#Flate}
```
public static final int Flate
```


ضغط Flate.

### LzwBaselinePredictor {#LzwBaselinePredictor}
```
public static final int LzwBaselinePredictor
```


اختيار المتنبئ مقيد بـ PNG Paeth predictor لتسريع العملية. في الممارسة العملية يُظهر أداءً مفاجئًا جيدًا. أفضل من [LzwOptimizedPredictor](../../com.aspose.imaging.imageoptions/pdfimagecompressionoptions\#LzwOptimizedPredictor).

### LzwOptimizedPredictor {#LzwOptimizedPredictor}
```
public static final int LzwOptimizedPredictor
```


اختيار المتنبئ أكثر تعقيدًا ويجب أن ينتج أحجام صور أصغر لكنه يستغرق وقتًا أطول. تقول RFC 2083 إنه الطريقة المثلى. ولكن على بيانات الاختبار، المتنبئ الأساسي [LzwBaselinePredictor](../../com.aspose.imaging.imageoptions/pdfimagecompressionoptions\#LzwBaselinePredictor) يتفوق، مما يترك المتنبئ المحسن خلفه بنسبة تحسين ضغط تتراوح بين 25-40٪.

### Jpeg {#Jpeg}
```
public static final int Jpeg
```


ضغط Jpeg. لا يدعم الشفافية.

### Ccitt3 {#Ccitt3}
```
public static final int Ccitt3
```


/CCITTFaxDecode/DecodeParms/K 0/Columns 173 لا يدعم الشفافية.

### Ccitt4 {#Ccitt4}
```
public static final int Ccitt4
```


/CCITTFaxDecode/DecodeParms/K -1/Columns 173 لا يدعم الشفافية.

