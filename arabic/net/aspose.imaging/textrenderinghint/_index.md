---
title: "تعداد TextRenderingHint"
second_title: "Aspose.Imaging for .NET API Reference"
description: "تعداد Aspose.Imaging.TextRenderingHint. يحدد جودة عرض النص"
type: docs
weight: 11780
url: /ar/net/aspose.imaging/textrenderinghint/
---
## TextRenderingHint enumeration

يحدد جودة عرض النص.

```csharp
public enum TextRenderingHint
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| SystemDefault | `0` | كل حرف يتم رسمه باستخدام صورة البت الخاصة بالرمز، مع تلميح العرض الافتراضي للنظام. سيتم رسم النص باستخدام أي إعدادات تنعيم الخط التي اختارها المستخدم للنظام. |
| SingleBitPerPixelGridFit | `1` | كل حرف يتم رسمه باستخدام صورة البت الخاصة بالرمز. يتم استخدام التلميح لتحسين مظهر الحرف على الجذوع والانحناءات. |
| SingleBitPerPixel | `2` | كل حرف يتم رسمه باستخدام صورة البت الخاصة بالرمز. لا يتم استخدام التلميح. |
| AntiAliasGridFit | `3` | كل حرف يتم رسمه باستخدام صورة البت المضادة للتعرج للرمز مع التلميح. جودة أفضل بكثير بفضل مضاد التعرج، لكن بتكلفة أداء أعلى. |
| AntiAlias | `4` | كل حرف يتم رسمه باستخدام صورة البت المضادة للتعرج للرمز دون التلميح. جودة أفضل بفضل مضاد التعرج. قد تكون اختلافات عرض الجذع ملحوظة لأن التلميح معطل. |
| ClearTypeGridFit | `5` | كل حرف يتم رسمه باستخدام صورة البت ClearType للرمز مع التلميح. أعلى إعداد للجودة. يُستخدم للاستفادة من ميزات خط ClearType. |

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


