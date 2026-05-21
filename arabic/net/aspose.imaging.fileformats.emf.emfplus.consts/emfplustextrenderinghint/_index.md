---
title: "تعداد EmfPlusTextRenderingHint"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusTextRenderingHint تعداد. يحدد تعداد TextRenderingHint أنواع تحسين النص وإزالة التعرجات التي تؤثر على جودة عرض النص."
type: docs
weight: 5220
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/
---
## EmfPlusTextRenderingHint enumeration

تحدد تعداد TextRenderingHint أنواع توجيه النص وإزالة التعرجات، مما يؤثر على جودة عرض النص.

```csharp
public enum EmfPlusTextRenderingHint : byte
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| TextRenderingHintSystemDefault | `0` | يحدد أنه يجب رسم كل حرف نصي باستخدام أي إعدادات تنعيم الخط التي تم تكوينها على نظام التشغيل. |
| TextRenderingHintSingleBitPerPixelGridFit | `1` | يحدد أنه يجب رسم كل حرف نصي باستخدام صورة البت الخاصة بالرمز. قد يُستخدم التنعيم لتحسين مظهر جذوع الأحرف المنحنية. |
| TextRenderingHintSingleBitPerPixel | `2` | يحدد أنه يجب رسم كل حرف نصي باستخدام صورة البت الخاصة بالرمز. لا يُستخدم التنعيم. |
| TextRenderingHintAntialiasGridFit | `3` | يحدد أنه يجب رسم كل حرف نصي باستخدام صورة البت المضادة للتنعيم للرمز مع التنعيم. يكون العرض عالي الجودة بفضل إزالة التعرجات، لكن بتكلفة أداء أعلى. |
| TextRenderingHintAntialias | `4` | يحدد أنه يتم رسم كل حرف نصي باستخدام صورة البت المضادة للتنعيم للرمز دون تحسين. ينتج جودة أفضل بفضل إزالة التعرجات، لكن قد تكون اختلافات عرض الجذع ملحوظة لأن التحسين مُعطل. |
| TextRenderingHintClearTypeGridFit | `5` | يحدد أنه يجب رسم كل حرف نصي باستخدام صورة البت ClearType للرمز مع التنعيم. هذا هو أعلى إعداد لتحسين النص، والذي يُستخدم للاستفادة من ميزات خط ClearType. |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


