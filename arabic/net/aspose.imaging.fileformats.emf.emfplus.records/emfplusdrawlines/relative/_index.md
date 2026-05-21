---
title: "EmfPlusDrawLines.Relative"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية EmfPlusDrawLines. تحصل أو تعين قيمة تشير إلى ما إذا كان هذا EmfPlusDrawClosedCurve نسبيًا. هذه البتة تشير إلى ما إذا كان حقل PointData يحدد مواقع نسبية أو مطلقة. إذا كان مُحددًا، فإن كل عنصر في PointData يحدد موقعًا في مساحة الإحداثيات يكون نسبياً إلى الموقع المحدد بالعنصر السابق في المصفوفة. في حالة العنصر الأول في PointData يُفترض وجود موقع سابق عند الإحداثيات 00. إذا كان غير مُحدد، فإن PointData يحدد مواقع مطلقة وفقًا لعلم C. ملاحظة: إذا تم تعيين هذا العلم، فإن علم Compressed أعلاه غير معرف ويجب تجاهله."
type: docs
weight: 60
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/relative/
---
## EmfPlusDrawLines.Relative property

يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [`EmfPlusDrawClosedCurve`](../../emfplusdrawclosedcurve/) نسبياً. هذه البتة تشير إلى ما إذا كان حقل PointData يحدد مواقع نسبية أو مطلقة. إذا تم الضبط، كل عنصر في PointData يحدد موقعًا في مساحة الإحداثيات يكون نسبياً إلى الموقع المحدد بواسطة العنصر السابق في المصفوفة. في حالة العنصر الأول في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا تم الإلغاء، يحدد PointData مواقع مطلقة وفقًا لعلامة C. ملاحظة: إذا تم ضبط هذه العلامة، تكون علامة Compressed (أعلاه) غير معرفة ويجب تجاهلها

```csharp
public bool Relative { get; set; }
```

### Property Value

`true` إذا كان نسبياً؛ وإلا `false`.

### انظر أيضًا

* class [EmfPlusDrawLines](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusdrawlines/)
* assembly [Aspose.Imaging](../../../)


