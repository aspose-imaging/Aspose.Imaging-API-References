---
title: PdfImageCompressionOptions
second_title: Aspose.Imaging لمرجع NET API
description: خيارات ضغط الصور بتنسيق PDF
type: docs
weight: 10100
url: /ar/net/aspose.imaging.imageoptions/pdfimagecompressionoptions/
---
## PdfImageCompressionOptions enumeration

خيارات ضغط الصور بتنسيق PDF

```csharp
public enum PdfImageCompressionOptions
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| Auto | `0` | تحديد الضغط الأنسب تلقائيًا لكل صورة. |
| None | `1` | يحفظ بايت الصورة الخام مما ينتج عنه أحجام ملفات pdf أكبر. |
| Rle | `2` | تشغيل ضغط الطول . |
| Flate | `3` | ضغط Flate . |
| LzwBaselinePredictor | `4` | تحديد المتنبئ مقصور على توقع PNG Paeth لتسريع العملية. من الناحية العملية ، يؤدي أداءً جيدًا بشكل مدهش. افضل منLzwOptimizedPredictor . |
| LzwOptimizedPredictor | `5` | تحديد المتنبئ أكثر تعقيدًا ويجب أن ينتج عنه أحجام صور أصغر ولكن يستغرق وقتًا أطول. يقول RFC 2083 إنها أفضل طريقة للذهاب. ولكن في بيانات الاختبار الأساسية ، توقعLzwBaselinePredictor ركلات الحمار تاركة المتنبئ الأمثل بنسبة 25-40٪ مكاسب معدل الضغط. |
| Jpeg | `6` | ضغط Jpeg . لا يدعم الشفافية . |
| Ccitt3 | `7` | / CCITTFaxDecode / DecodeParms / K 0 / Columns 173 لا يدعم الشفافية. |
| Ccitt4 | `8` | / CCITTFaxDecode / DecodeParms / K -1 / Columns 173 لا يدعم الشفافية. |

### أنظر أيضا

* مساحة الاسم [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->