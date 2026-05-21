---
title: "الفئة EmfPolyPolygon16"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPolyPolygon16. سجل EMR_POLYPOLYGON16 يحدد سلسلة من المضلعات المغلقة. يتم تحديد حدود كل مضلع باستخدام القلم الحالي وتعبئته باستخدام الفرشاة الحالية ووضع تعبئة المضلع. يمكن للمضلعات المرسومة بواسطة هذا السجل أن تتداخل."
type: docs
weight: 4140
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/
---
## EmfPolyPolygon16 class

سجل EMR_POLYPOLYGON16 يحدد سلسلة من المضلعات المغلقة. كل مضلع يُحدَّد حدوده باستخدام القلم الحالي، ويُملأ باستخدام الفرشاة الحالية ووضع تعبئة المضلع. يمكن أن تتداخل المضلعات المرسومة بواسطة هذا السجل.

```csharp
public sealed class EmfPolyPolygon16 : EmfPolyPolyShape
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPolyPolygon16](emfpolypolygon16/#constructor)() | يُهيئ مثيلاً جديداً من الفئة `EmfPolyPolygon16`. |
| [EmfPolyPolygon16](emfpolypolygon16/#constructor_1)(EmfRecord) | يُهيئ مثيلاً جديداً من الفئة `EmfPolyPolygon16`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolypolyshape/apoints/) { get; set; } | يحصل أو يعيّن مصفوفة من كائنات WMF PointS، المحددة في [MS-WMF] القسم 2.2.2.16، التي تحدد مصفوفة النقاط. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfboundedrecord/bounds/) { get; set; } | يحصل أو يعيّن كائن WMF RectL 128‑بت ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل المحيط بوحدات الجهاز. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

## ملاحظات

يجب أن يتم تحديد حدود كل مضلع باستخدام القلم الحالي، وتعبئته باستخدام الفرشاة الحالية ووضع تعبئة المضلع المحدد في سياق جهاز التشغيل. يمكن أن تتداخل المضلعات المعرفة بهذا السجل.

### انظر أيضًا

* class [EmfPolyPolyShape](../emfpolypolyshape/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


