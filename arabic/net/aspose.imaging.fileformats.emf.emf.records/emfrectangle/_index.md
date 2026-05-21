---
title: "الفئة EmfRectangle"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfRectangle. السجل EMR_RECTANGLE يرسم مستطيلًا. يتم تحديد حدود المستطيل باستخدام القلم الحالي وتعبئته باستخدام الفرشاة الحالية"
type: docs
weight: 4280
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfrectangle/
---
## EmfRectangle class

سجل EMR_RECTANGLE يرسم مستطيلًا. يتم تحديد حدود المستطيل باستخدام القلم الحالي وتعبئته باستخدام الفرشاة الحالية.

```csharp
public sealed class EmfRectangle : EmfDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfRectangle](emfrectangle/#constructor)() | ينشئ مثيلًا جديدًا للفئة `EmfRectangle`. |
| [EmfRectangle](emfrectangle/#constructor_1)(EmfRecord) | ينشئ مثيلًا جديدًا للفئة `EmfRectangle`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Box](../../aspose.imaging.fileformats.emf.emf.records/emfrectangle/box/) { get; set; } | يحصل أو يعيّن كائن WMF RectL 128‑بت، المحدد في [MS-WMF] القسم 2.2.2.19، الذي يحدد المستطيل الشامل للرسم. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

## ملاحظات

الموضع الحالي لا يُستخدم ولا يُحدّث بواسطة Rectangle. إذا تم استخدام قلم PS_NULL، فإن أبعاد المستطيل تكون أقل ببيكسل واحد في الارتفاع وأقل ببيكسل واحد في العرض.

### انظر أيضًا

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


