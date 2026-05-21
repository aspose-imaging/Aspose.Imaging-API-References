---
title: "Enum StretchMode"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Wmf.Consts.StretchMode enum. يحدد تعداد StretchMode وضع تمديد البت ماب الذي يحدد كيف يقوم النظام بدمج الصفوف أو الأعمدة من البت ماب مع البكسلات الموجودة"
type: docs
weight: 8270
url: /ar/net/aspose.imaging.fileformats.wmf.consts/stretchmode/
---
## StretchMode enumeration

يحدد تعداد `StretchMode` وضع تمديد البت ماب، الذي يحدد كيف يقوم النظام بدمج الصفوف أو الأعمدة من البت ماب مع البكسلات الموجودة.

```csharp
public enum StretchMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| BlackOnWhite | `1` | ينفّذ عملية AND منطقية باستخدام قيم الألوان للبكسلات المحذوفة والبكسلات الموجودة. إذا كان البت ماب أحادي اللون، فإن هذا الوضع يحافظ على البكسلات السوداء على حساب البكسلات البيضاء. |
| WhiteOnBlack | `2` | ينفّذ عملية OR منطقية باستخدام قيم الألوان للبكسلات المحذوفة والبكسلات الموجودة. إذا كان البت ماب أحادي اللون، فإن هذا الوضع يحافظ على البكسلات البيضاء على حساب البكسلات السوداء. |
| ColorOnColor | `3` | يحذف البكسلات. هذا الوضع يحذف جميع خطوط البكسلات المحذوفة دون محاولة الحفاظ على معلوماتها. |
| HalfTone | `4` | يقوم بترسيم البكسلات من المستطيل المصدر إلى كتل من البكسلات في المستطيل الوجهة. اللون المتوسط على كتلة البكسلات الوجهة يقترب من لون البكسلات المصدر. |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


