---
title: "Enum WmfOutPrecision"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Wmf.Consts.WmfOutPrecision enum. يحدد تعداد OutPrecision القيم لدقة الإخراج والتي تمثل المتطلبات لمطابقة مخطط الخط لمعايير الخط المحددة بما في ذلك الارتفاع والعرض واتجاه الحرف والانحراف والمسافة ونوع الخط."
type: docs
weight: 8440
url: /ar/net/aspose.imaging.fileformats.wmf.consts/wmfoutprecision/
---
## WmfOutPrecision enumeration

يعرّف تعداد OutPrecision القيم لدقة الإخراج، وهي المتطلبات التي يحتاجها مخطط الخطوط لمطابقة معلمات الخط المحددة، بما في ذلك الارتفاع، العرض، اتجاه الحرف، الانحراف، التباعد، ونوع الخط.

```csharp
public enum WmfOutPrecision : byte
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Default | `0` | قيمة تحدد السلوك الافتراضي. |
| String | `1` | قيمة تُرجع عندما يتم تعداد الخطوط المرسومة. |
| Stroke | `3` | قيمة تُرجع عندما يتم تعداد خطوط TrueType وغيرها من الخطوط القابلة للتحديد، والخطوط المتجهية. |
| Tt | `4` | قيمة تحدد اختيار خط TrueType عندما يحتوي النظام على عدة خطوط بنفس الاسم. |
| Device | `5` | قيمة تحدد اختيار خط الجهاز عندما يحتوي النظام على عدة خطوط بنفس الاسم. |
| Raster | `6` | قيمة تحدد اختيار خط مُرصّص عندما يحتوي النظام على عدة خطوط بنفس الاسم. |
| TtOnly | `7` | قيمة تحدد المتطلب لخطوط TrueType فقط. إذا لم يكن هناك أي خطوط TrueType مثبتة في النظام، يتم تحديد السلوك الافتراضي. |
| Outline | `8` | قيمة تحدد المتطلب لخطوط TrueType وغيرها من الخطوط المتجهة. |
| ScreenOutline | `9` | قيمة تحدد تفضيلًا لخطوط TrueType وغيرها من الخطوط المتجهة. |
| PsOnly | `10` | قيمة تحدد المتطلب لخطوط PostScript فقط. إذا لم يكن هناك أي خطوط PostScript مثبتة في النظام، يتم تحديد السلوك الافتراضي. |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


