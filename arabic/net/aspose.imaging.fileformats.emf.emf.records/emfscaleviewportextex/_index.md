---
title: "الفئة EmfScaleViewportExtex"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfScaleViewportExtex. سجل EMR_SCALEVIEWPORTEXTEX يعيد تحديد منطقة العرض لسياق الجهاز باستخدام النسب المتكوّنة من المضاعفات والمقامات المحددة."
type: docs
weight: 4340
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/
---
## EmfScaleViewportExtex class

سجل EMR_SCALEVIEWPORTEXTEX يعيد تحديد نافذة العرض لسياق الجهاز باستخدام النسب التي تكونها المضاعفات والمقاسم المحددة.

```csharp
public sealed class EmfScaleViewportExtex : EmfStateRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfScaleViewportExtex](emfscaleviewportextex/#constructor)() | ينشئ مثيلًا جديدًا من الفئة `EmfScaleViewportExtex`. |
| [EmfScaleViewportExtex](emfscaleviewportextex/#constructor_1)(EmfRecord) | ينشئ مثيلًا جديدًا من الفئة `EmfScaleViewportExtex`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |
| [XDenom](../../aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/xdenom/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد المقام الأفقي. لا يمكن أن يكون صفرًا. |
| [XNum](../../aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/xnum/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد المضاعف الأفقي. لا يمكن أن يكون صفرًا. |
| [YDenom](../../aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/ydenom/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد المقام العمودي. لا يمكن أن يكون صفرًا. |
| [YNum](../../aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/ynum/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد المضاعف العمودي. لا يمكن أن يكون صفرًا. |

## ملاحظات

لا يمكن تغيير الامتداد إذا كان سياق الجهاز يستخدم وضع تخطيط بمقياس ثابت. فقط MM_ISOTROPIC و MM_ANISOTROPIC ليسا بمقياس ثابت. يتم تعديل امتدادات منطقة العرض كما يلي. xNewWE = (xOldWE * xNum) / xDenom yNewWE = (yOldWE * yNum) / yDenom

### انظر أيضًا

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


