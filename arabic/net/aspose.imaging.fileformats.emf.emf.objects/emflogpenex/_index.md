---
title: "الفئة EmfLogPenEx"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfLogPenEx class. يحدد كائن LogPenEx عرض النمط واللون لقلم منطقي موسع"
type: docs
weight: 3180
url: /ar/net/aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---
## EmfLogPenEx class

كائن LogPenEx يحدد النمط والعرض واللون لقلم منطقي موسع.

```csharp
public sealed class EmfLogPenEx : EmfBasePen
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfLogPenEx](emflogpenex/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [Argb32ColorRef](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/argb32colorref/) { get; set; } | يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8). يعتمد تفسير هذا الحقل على قيمة BrushStyle، كما هو موضح في الجدول لاحقًا في هذا القسم. |
| [BrushDibPattern](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/brushdibpattern/) { get; set; } | يحصل أو يعيّن نمط الفرشاة dib. |
| [BrushHatch](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/brushhatch/) { get; set; } | يحصل أو يعيّن نمط تظليل الفرشاة. يعتمد تعريف هذا الحقل على قيمة BrushStyle، كما هو موضح في الجدول لاحقًا في هذا القسم. |
| [BrushStyle](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/brushstyle/) { get; set; } | يحصل أو يعيّن عدد صحيح غير موقع 32 بت يحدد نمط الفرشاة للقلم من تعداد WMF BrushStyle ([MS-WMF] القسم 2.1.1.4). إذا كان نوع القلم في حقل PenStyle هو PS_GEOMETRIC، يجب أن تكون هذه القيمة إما BS_SOLID أو BS_HATCHED. يمكن أن تكون قيمة هذا الحقل BS_NULL، ولكن فقط إذا كان نمط الخط المحدد في PenStyle هو PS_NULL. ينبغي استخدام نمط BS_NULL لتحديد فرشاة لا تأثير لها. |
| [NumStyleEntities](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/numstyleentities/) { get; } | يحصل على عدد العناصر في المصفوفة المحددة في حقل StyleEntry. يجب أن تكون هذه القيمة صفرًا إذا لم يحدد PenStyle القيمة PS_USERSTYLE. |
| override [PenStyle](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/penstyle/) { get; set; } | يحصل أو يعيّن نمط القلم |
| [StyleEntry](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/styleentry/) { get; set; } | يحصل أو يعيّن مصفوفة اختيارية من الأعداد الصحيحة غير الموقعية 32 بت التي تحدد أطوال الشرطات والفجوات في الخط المرسوم بهذا القلم، عندما تكون قيمة PenStyle هي PS_USERSTYLE لنمط الخط للقلم. تحتوي المصفوفة على عدد من الإدخالات المحددة بواسطة NumStyleEntries، لكنها تُعامل كما لو أنها تتكرر إلى ما لا نهاية. الإدخال الأول في المصفوفة يحدد طول الشرط الأول. الإدخال الثاني يحدد طول الفجوة الأولى. بعد ذلك تتناوب أطوال الشرطات والفجوات. إذا كان نوع القلم في حقل PenStyle هو PS_GEOMETRIC، تُحدد الأطوال بوحدات منطقية؛ وإلا تُحدد بالأجهزة. |
| [Width](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/width/) { get; set; } | يحصل أو يعيّن عدد صحيح غير موقع 32 بت يحدد عرض الخط المرسوم بالقلم. إذا كان نوع القلم في حقل PenStyle هو PS_GEOMETRIC، فإن هذه القيمة هي العرض بوحدات منطقية؛ وإلا يُحدد العرض بوحدات الجهاز. إذا كان نوع القلم في حقل PenStyle هو PS_COSMETIC، يجب أن تكون هذه القيمة 0x00000001. |

### انظر أيضًا

* class [EmfBasePen](../emfbasepen/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


