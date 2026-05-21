---
title: "EmfPlusDrawClosedCurve.PointData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية EmfPlusDrawClosedCurve. تحصل أو تعيين بيانات النقاط. مصفوفة من Count نقاط تحدد نقاط النهاية للخطوط التي تعرف المنحنى. في منحنى كاردينال مغلق، يستمر المنحنى عبر النقطة الأخيرة في مصفوفة PointData ويتصل بالنقطة الأولى في المصفوفة. نوع البيانات في هذه المصفوفة يحدد بواسطة حقل Flags كما يلي: نوع البيانات معنى EmfPlusPointR كائن القسم 2.2.2.37 إذا تم ضبط علم P في Flags فإن النقاط تحدد مواقع نسبية. EmfPlusPointF كائن القسم 2.2.2.36 إذا تم ضبط علمي P و C في Flags فإن النقاط تحدد مواقع مطلقة. EmfPlusPoint كائن القسم 2.2.2.35 إذا كان علم P غير مضبوط وعلم C مضبوط في Flags فإن النقاط تحدد مواقع نسبية."
type: docs
weight: 40
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/pointdata/
---
## EmfPlusDrawClosedCurve.PointData property

يحصل أو يعيّن بيانات النقاط. مصفوفة من Count نقاط تحدد نقاط النهاية للخطوط التي تُعرّف المنحنى. في منحنى كاردينال مغلق، يستمر المنحنى عبر النقطة الأخيرة في مصفوفة PointData ويتصل بالنقطة الأولى في المصفوفة. نوع البيانات في هذه المصفوفة يُحدد بواسطة حقل Flags، كما يلي: نوع البيانات معنى EmfPlusPointR object (القسم 2.2.2.37) إذا كان علم P مُعينًا في Flags، فإن النقاط تحدد مواقع نسبية. EmfPlusPointF object (القسم 2.2.2.36) إذا كان علما P و C مُعينين في حقل Flags، فإن النقاط تحدد مواقع مطلقة. EmfPlusPoint object (القسم 2.2.2.35) إذا كان علم P غير مُعين وعلم C مُعين في حقل Flags، فإن النقاط تحدد مواقع نسبية.

```csharp
public PointF[] PointData { get; set; }
```

### انظر أيضًا

* struct [PointF](../../../aspose.imaging/pointf/)
* class [EmfPlusDrawClosedCurve](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusdrawclosedcurve/)
* assembly [Aspose.Imaging](../../../)


