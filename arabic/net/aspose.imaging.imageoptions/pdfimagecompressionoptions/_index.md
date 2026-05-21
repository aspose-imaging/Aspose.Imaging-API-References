---
title: "التعداد PdfImageCompressionOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "التعداد Aspose.Imaging.ImageOptions.PdfImageCompressionOptions. خيارات ضغط صور PDF"
type: docs
weight: 10480
url: /ar/net/aspose.imaging.imageoptions/pdfimagecompressionoptions/
---
## PdfImageCompressionOptions enumeration

خيارات ضغط صور PDF

```csharp
public enum PdfImageCompressionOptions
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Auto | `0` | يختار تلقائيًا أنسب ضغط لكل صورة. |
| None | `1` | يحفظ بايتات الصورة الخام مما ينتج عنه أحجام ملفات PDF أكبر. |
| Rle | `2` | ضغط Run Length. |
| Flate | `3` | ضغط Flate. |
| LzwBaselinePredictor | `4` | اختيار المتنبئ مقيد بـ PNG Paeth predictor لتسريع العملية. في الممارسة العملية يحقق أداءً مفاجئًا جيدًا. أفضل من LzwOptimizedPredictor. |
| LzwOptimizedPredictor | `5` | اختيار المتنبئ أكثر تعقيدًا ويجب أن ينتج أحجام صور أصغر لكنه يستغرق وقتًا أطول. تقول RFC 2083 إنه الخيار الأفضل. ولكن على بيانات الاختبار، المتنبئ الأساسي LzwBaselinePredictor يتفوق، مما يترك المتنبئ المحسن خلفه بنسبة تحسين معدل الضغط من 25-40%. |
| Jpeg | `6` | ضغط Jpeg. لا يدعم الشفافية. |
| Ccitt3 | `7` | /CCITTFaxDecode/DecodeParms/K 0/Columns 173 لا يدعم الشفافية. |
| Ccitt4 | `8` | /CCITTFaxDecode/DecodeParms/K -1/Columns 173 لا يدعم الشفافية. |

### انظر أيضًا

* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


