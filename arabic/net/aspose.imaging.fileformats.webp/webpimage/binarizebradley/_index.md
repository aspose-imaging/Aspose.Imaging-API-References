---
title: "WebPImage.BinarizeBradley"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة WebPImage. تطبيق التحويل إلى صورة ثنائية على الصورة باستخدام خوارزمية عتبة برادلي التكيفية مع عتبة الصورة المتكاملة. تقوم هذه الطريقة بحساب العتبات المحلية ديناميكيًا بناءً على جوار الصورة، مما يعزز القدرة على التكيف مع ظروف الإضاءة المتغيرة ويضمن تجزئة قوية للمهام المعالجة اللاحقة داخل تطبيقك"
type: docs
weight: 120
url: /ar/net/aspose.imaging.fileformats.webp/webpimage/binarizebradley/
---
## WebPImage.BinarizeBradley method

تطبيق التحويل إلى ثنائي على الصورة باستخدام خوارزمية العتبة التكيفية لبرادلي مع عتبة الصورة المتكاملة. تقوم هذه الطريقة بحساب عتبات محلية ديناميكيًا بناءً على جوار الصورة، مما يعزز القدرة على التكيف مع ظروف الإضاءة المتغيرة ويضمن تجزئة قوية للمهام اللاحقة داخل تطبيقك.

```csharp
public override void BinarizeBradley(double brightnessDifference, int windowSize)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| brightnessDifference | Double | فرق السطوع بين البكسل ومتوسط نافذة s × s من البكسلات المتمركزة حول هذا البكسل. |
| windowSize | Int32 | حجم نافذة s × s من البكسلات المتمركزة حول هذا البكسل |

### انظر أيضًا

* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)


