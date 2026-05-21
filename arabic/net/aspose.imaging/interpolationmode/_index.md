---
title: "التعداد InterpolationMode"
second_title: "Aspose.Imaging for .NET API Reference"
description: "التعداد Aspose.Imaging.InterpolationMode. يحدد تعداد InterpolationMode الخوارزمية المستخدمة عند تحجيم أو تدوير الصور."
type: docs
weight: 10730
url: /ar/net/aspose.imaging/interpolationmode/
---
## InterpolationMode enumeration

يحدد تعداد `InterpolationMode` الخوارزمية المستخدمة عند تحجيم أو تدوير الصور.

```csharp
public enum InterpolationMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Invalid | `-1` | وضع الاستيفاء غير صالح. |
| Default | `0` | يحدد الوضع الافتراضي. |
| Low | `1` | يحدد استيفاء منخفض الجودة. |
| High | `2` | يحدد استيفاء عالي الجودة. |
| Bilinear | `3` | يحدد استيفاء ثنائي الخطوط. لا يتم إجراء تصفية مسبقة. هذا الوضع غير مناسب لتصغير صورة إلى أقل من 50٪ من حجمها الأصلي. |
| Bicubic | `4` | يحدد استيفاء ثلاثي المكعب. لا يتم إجراء تصفية مسبقة. هذا الوضع غير مناسب لتصغير صورة إلى أقل من 25٪ من حجمها الأصلي. |
| NearestNeighbor | `5` | يحدد استيفاء أقرب جار. |
| HighQualityBilinear | `6` | يحدد استيفاء ثنائي الخطوط عالي الجودة. يتم إجراء تصفية مسبقة لضمان تصغير عالي الجودة. |
| HighQualityBicubic | `7` | يحدد استيفاء ثلاثي المكعب عالي الجودة. يتم إجراء تصفية مسبقة لضمان تصغير عالي الجودة. ينتج هذا الوضع أعلى جودة للصور المحوّلة. |

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


