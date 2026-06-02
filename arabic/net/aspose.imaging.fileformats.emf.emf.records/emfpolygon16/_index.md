---
title: "الفئة EmfPolygon16"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPolygon16 الفئة. سجل EMR_POLYGON16 يحدد مضلعًا يتكون من نقطتين أو أكثر متصلة بخطوط مستقيمة. يتم تحديد حدود المضلع باستخدام القلم الحالي وتعبئته باستخدام الفرشاة الحالية ووضع تعبئة المضلع. يتم إغلاق المضلع تلقائيًا برسم خط من آخر نقطة إلى الأولى."
type: docs
weight: 4210
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfpolygon16/
---
## EmfPolygon16 class

سجل EMR_POLYGON16 يحدد مضلعًا يتكون من نقطتين أو أكثر متصلة بخطوط مستقيمة. يتم تحديد حدود المضلع باستخدام القلم الحالي وتعبئته باستخدام الفرشاة الحالية ووضع تعبئة المضلع. يُغلق المضلع تلقائيًا برسم خط من آخر نقطة إلى الأولى.

```csharp
public sealed class EmfPolygon16 : EmfPolyShape
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPolygon16](emfpolygon16/#constructor)() | ينشئ مثيلًا جديدًا للفئة `EmfPolygon16`. |
| [EmfPolygon16](emfpolygon16/#constructor_1)(EmfRecord) | ينشئ مثيلًا جديدًا للفئة `EmfPolygon16`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolyshape/apoints/) { get; set; } | يحصل أو يعيّن مصفوفة من كائنات WMF PointL ([MS-WMF] القسم 2.2.2.15) التي تحدد بيانات النقاط، بوحدات منطقية. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfboundedrecord/bounds/) { get; set; } | يحصل أو يعيّن كائن WMF RectL 128‑بت ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل المحيط بوحدات الجهاز. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

## ملاحظات

The polygon SHOULD be outlined using the current pen and filled using the current brush and polygon fill mode. The polygon SHOULD be closed automatically by drawing a line from the last vertex to the first

### انظر أيضًا

* class [EmfPolyShape](../emfpolyshape/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


