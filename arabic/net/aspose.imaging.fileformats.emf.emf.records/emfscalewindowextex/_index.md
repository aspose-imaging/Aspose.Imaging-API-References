---
title: "الفئة EmfScaleWindowExtex"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfScaleWindowExtex. يعيد سجل EMR_SCALEWINDOWEXTEX تحديد النافذة لسياق جهاز التشغيل باستخدام النسب التي تكونها المضاعفات والمقاسم المحددة."
type: docs
weight: 4350
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/
---
## EmfScaleWindowExtex class

سجل EMR_SCALEWINDOWEXTEX يعيد تحديد النافذة لسياق جهاز التشغيل باستخدام النسب التي تكونها المضاعفات والمقاسم المحددة.

```csharp
public sealed class EmfScaleWindowExtex : EmfStateRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfScaleWindowExtex](emfscalewindowextex/#constructor)() | ينشئ مثيلًا جديدًا للفئة `EmfScaleWindowExtex`. |
| [EmfScaleWindowExtex](emfscalewindowextex/#constructor_1)(EmfRecord) | ينشئ مثيلًا جديدًا للفئة `EmfScaleWindowExtex`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |
| [XDenom](../../aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/xdenom/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا بحجم 32 بت يحدد المقسوم الأفقي. يجب ألا يكون صفرًا. |
| [XNum](../../aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/xnum/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا بحجم 32 بت يحدد المضاعف الأفقي. يجب ألا يكون صفرًا. |
| [YDenom](../../aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/ydenom/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا بحجم 32 بت يحدد المقسوم العمودي. يجب ألا يكون صفرًا. |
| [YNum](../../aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/ynum/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا بحجم 32 بت يحدد المضاعف العمودي. يجب ألا يكون صفرًا. |

## ملاحظات

لا يمكن تغيير الامتداد إذا كان سياق الجهاز يستخدم وضع تعيين مقياس ثابت. فقط MM_ISOTROPIC و MM_ANISOTROPIC ليسا بمقياس ثابت. يتم تعديل امتدادات النافذة كما يلي. xNewWE = (xOldWE * xNum) / xDenom yNewWE = (yOldWE * yNum) / yDenom

### انظر أيضًا

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


