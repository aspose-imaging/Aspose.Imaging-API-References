---
title: "Enum EmfPointEnum"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfPointEnum enum. يُستخدم تعداد Point لتحديد كيفية استخدام نقطة في استدعاء رسم."
type: docs
weight: 2880
url: /ar/net/aspose.imaging.fileformats.emf.emf.consts/emfpointenum/
---
## EmfPointEnum enumeration

تعداد Point يُستخدم لتحديد كيفية استخدام نقطة في استدعاء الرسم.

```csharp
[Flags]
public enum EmfPointEnum : byte
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| PT_CLOSEFIGURE | `1` | يمكن دمج نوع PT_LINETO أو PT_BEZIERTO مع هذه القيمة باستخدام عامل OR البتّي للإشارة إلى أن النقطة المقابلة هي النقطة الأخيرة في الشكل وأن الشكل مغلق. |
| PT_LINETO | `2` | يحدد أنه يجب رسم خط من الموضع الحالي إلى هذه النقطة، ثم تصبح هذه النقطة الموضع الحالي الجديد. |
| PT_BEZIERTO | `4` | يحدد أن هذه النقطة هي نقطة تحكم أو نقطة نهاية لمنحنى بيزيير. |
| PT_MOVETO | `6` | يحدد أن هذه النقطة تبدأ شكلاً منفصلاً. تصبح هذه النقطة الموضع الحالي الجديد. |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


