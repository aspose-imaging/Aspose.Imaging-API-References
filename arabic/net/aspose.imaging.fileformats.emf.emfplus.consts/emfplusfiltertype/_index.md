---
title: "تعداد EmfPlusFilterType"
second_title: "Aspose.Imaging for .NET API Reference"
description: "تعداد Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusFilterType. يحدد تعداد FilterType أنواع خوارزميات الترشيح التي يمكن استخدامها لتحسين جودة النص والرسومات وعرض الصور."
type: docs
weight: 4920
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/
---
## EmfPlusFilterType enumeration

يحدد تعداد FilterType أنواع خوارزميات الترشيح التي يمكن استخدامها لتحسين جودة النص والرسومات وعرض الصورة.

```csharp
public enum EmfPlusFilterType : byte
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| FilterTypeNone | `0` | يحدد أنه لا يتم إجراء الترشيح. |
| FilterTypePoint | `1` | يحدد أن كل بكسل هدف يتم حسابه عن طريق أخذ عينة من أقرب بكسل من صورة المصدر. |
| FilterTypeLinear | `2` | يحدد أن الاستيفاء الخطي يتم باستخدام المتوسط المرجح لمنطقة 2×2 بكسل حول بكسل المصدر. |
| FilterTypeTriangle | `3` | يحدد أن كل بكسل في الصورة المصدر يساهم بالتساوي في الصورة الهدف. هذا هو أبطأ خوارزمية ترشيح. |
| FilterTypeBox | `4` | يحدد خوارزمية مرشح صندوق، حيث يتم حساب كل بكسل هدف عن طريق متوسط مستطيل من بكسلات المصدر. هذه الخوارزمية مفيدة فقط عند تقليل حجم الصورة. |
| FilterTypePyramidalQuad | `6` | يحدد أنه يتم استخدام مرشح خيمة مكوّن من 4 عينات. |
| FilterTypeGaussianQuad | `7` | يحدد أنه يتم استخدام مرشح غاوسي مكوّن من 4 عينات، مما يخلق تأثير ضبابية على الصورة. |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


