---
title: "EmfPlusDrawBeziers.PointData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية EmfPlusDrawBeziers. تحصل أو تعين بيانات النقاط. مصفوفة من عدد Count من النقاط التي تحدد نقاط البداية والنهاية ونقاط التحكم لمنحنيات بيزيير. إحداثيات النهاية لمنحنى بيزيير واحد هي إحداثيات البداية للمنحنى التالي. تُستخدم نقاط التحكم لإنتاج تأثير بيزيير. نوع البيانات في هذه المصفوفة يُحدَّد بحقل Flags كما يلي: EmfPlusPointR القسم 2.2.2.37 إذا تم تعيين علامة P في Flags فإن النقاط تحدد مواقع نسبية. EmfPlusPointF القسم 2.2.2.36 إذا كانت علامات P و C غير مفعلة في حقل Flags فإن النقاط تحدد مواقع مطلقة. EmfPlusPoint القسم 2.2.2.35 إذا كانت علامة P غير مفعلة وعلامة C مفعلة في حقل Flags فإن النقاط تحدد مواقع نسبية. لا يمر منحنى بيزيير عبر نقاط التحكم الخاصة به. نقاط التحكم تعمل كـ"
type: docs
weight: 40
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/pointdata/
---
## EmfPlusDrawBeziers.PointData property

يحصل أو يعيّن بيانات النقاط مصفوفة من Count نقاط تحدد نقاط البداية والنهاية ونقاط التحكم لمنحنيات بيزيير. إحداثيات النهاية لمنحنى بيزيير واحد هي إحداثيات البداية للمنحنى التالي. تُستخدم نقاط التحكم لإنتاج تأثير بيزيير. نوع البيانات في هذه المصفوفة يُحدّد بواسطة حقل Flags كما يلي: نوع البيانات معنى كائن EmfPlusPointR (القسم 2.2.2.37) إذا تم تعيين علامة P في Flags، فإن النقاط تحدد مواقع نسبية. كائن EmfPlusPointF (القسم 2.2.2.36) إذا كانت بتا P و C غير مفعّلتين في حقل Flags، فإن النقاط تحدد مواقع مطلقة. كائن EmfPlusPoint (القسم 2.2.2.35) إذا كانت بتة P غير مفعّلة وتم تفعيل بتة C في حقل Flags، فإن النقاط تحدد مواقع نسبية. لا يمر منحنى بيزيير عبر نقاط التحكم الخاصة به. نقاط التحكم تعمل كـ

```csharp
public PointF[] PointData { get; set; }
```

### انظر أيضًا

* struct [PointF](../../../aspose.imaging/pointf/)
* class [EmfPlusDrawBeziers](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusdrawbeziers/)
* assembly [Aspose.Imaging](../../../)


