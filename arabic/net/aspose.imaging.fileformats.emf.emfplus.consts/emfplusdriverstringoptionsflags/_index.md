---
title: "التعداد EmfPlusDriverStringOptionsFlags"
second_title: "Aspose.Imaging for .NET API Reference"
description: "التعداد Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusDriverStringOptionsFlags. تحدد علامات DriverStringOptions خصائص تموضع النص الرسومي وعرضه. يمكن دمج هذه العلامات لتحديد خيارات متعددة."
type: docs
weight: 4910
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdriverstringoptionsflags/
---
## EmfPlusDriverStringOptionsFlags enumeration

تحدد أعلام DriverStringOptions خصائص تموضع نص الرسومات وعرضه. يمكن دمج هذه الأعلام لتحديد خيارات متعددة.

```csharp
[Flags]
public enum EmfPlusDriverStringOptionsFlags
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| DriverStringOptionsCmapLookup | `1` | إذا تم تعيينه، يجب تحديد مواضع رموز الحروف في جدول بحث خريطة الأحرف. إذا لم يُحدد، يجب الحصول على مواضع الرموز من مصفوفة إحداثيات. |
| DriverStringOptionsVertical | `2` | إذا تم تعيينه، يجب عرض السلسلة عموديًا. إذا لم يُحدد، يجب عرض السلسلة أفقيًا. |
| DriverStringOptionsRealizedAdvance | `4` | إذا تم تعيينه، يجب حساب مواضع رموز الحروف نسبةً إلى موضع الرمز الأول. إذا لم يُحدد، يجب الحصول على مواضع الرموز من مصفوفة إحداثيات. |
| DriverStringOptionsLimitSubpixel | `8` | إذا تم تعيينه، يجب استخدام ذاكرة أقل لتخزين رموز مضادة للتنعيم، مما ينتج عرض نص بجودة أقل. إذا لم يُحدد، يجب استخدام ذاكرة أكثر، مما ينتج عرض نص بجودة أعلى. |

## ملاحظات

يتم تحديد إخراج نص الرسومات في سجلات [`EmfPlusDrawDriverString`](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/).

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


