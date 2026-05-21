---
title: "تعداد EmfStretchMode"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfStretchMode تعداد. تُستخدم تعداد StretchMode لتحديد كيفية إضافة أو إزالة بيانات اللون من الصور النقطية التي يتم تمديدها أو ضغطها."
type: docs
weight: 2960
url: /ar/net/aspose.imaging.fileformats.emf.emf.consts/emfstretchmode/
---
## EmfStretchMode enumeration

يُستخدم تعداد StretchMode لتحديد كيفية إضافة بيانات اللون أو إزالتها من الصور النقطية التي يتم تمديدها أو ضغطها.

```csharp
public enum EmfStretchMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| STRETCH_ANDSCANS | `1` | ينفّذ عملية AND منطقية باستخدام قيم اللون للبكسلات المُزالة والموجودة. إذا كانت الصورة النقطية أحادية اللون، فإن هذا الوضع يحافظ على البكسلات السوداء على حساب البكسلات البيضاء. |
| STRETCH_ORSCANS | `2` | ينفّذ عملية OR منطقية باستخدام قيم اللون للبكسلات المُزالة والموجودة. إذا كانت الصورة النقطية أحادية اللون، فإن هذا الوضع يحافظ على البكسلات البيضاء على حساب البكسلات السوداء. |
| STRETCH_DELETESCANS | `3` | يحذف البكسلات. هذا الوضع يحذف جميع خطوط البكسلات المحذوفة دون محاولة الحفاظ على معلوماتها. |
| STRETCH_HALFTONE | `4` | يقوم بترسيم البكسلات من المستطيل المصدر إلى كتل من البكسلات في المستطيل الوجهة. اللون المتوسط على كتلة البكسلات الوجهة يقترب من لون البكسلات المصدر. |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


