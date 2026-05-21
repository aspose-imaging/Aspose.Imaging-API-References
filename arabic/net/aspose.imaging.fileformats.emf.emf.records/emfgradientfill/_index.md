---
title: "الفئة EmfGradientFill"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfGradientFill. سجل EMR_GRADIENTFILL يحدد تعبئة المستطيلات أو المثلثات بتدرجات اللون."
type: docs
weight: 3860
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfgradientfill/
---
## EmfGradientFill class

سجل EMR_GRADIENTFILL يحدد ملء المستطيلات أو المثلثات بتدرجات اللون.

```csharp
public sealed class EmfGradientFill : EmfDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfGradientFill](emfgradientfill/)(EmfRecord) | ينشئ مثيلًا جديدًا من الفئة `EmfGradientFill`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfgradientfill/bounds/) { get; set; } | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيلًا محيطًا، بوحدات جهاز شاملة-شاملة. |
| [NTri](../../aspose.imaging.fileformats.emf.emf.records/emfgradientfill/ntri/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد المستطيلات أو المثلثات التي سيتم تعبئتها. |
| [NVer](../../aspose.imaging.fileformats.emf.emf.records/emfgradientfill/nver/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد الرؤوس. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |
| [UlMode](../../aspose.imaging.fileformats.emf.emf.records/emfgradientfill/ulmode/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد وضع تعبئة التدرج. يجب أن تكون القيمة ضمن تعداد GradientFill (القسم 2.1.15). |
| [VertexData](../../aspose.imaging.fileformats.emf.emf.records/emfgradientfill/vertexdata/) { get; set; } | يحصل أو يعيّن كائنات تحدد رؤوس المستطيلات أو المثلثات والألوان المقابلة لها. |

## ملاحظات

سجل EMR_GRADIENTFILL يحدد أن رؤوس المثلث الثلاثة يجب أن تعبئ الشكل بتدرجات لونية ناعمة.[85] سجل EMR_GRADIENTFILL يحدد أن رؤوس المستطيل العلوية اليسرى والسفلية اليمنى يجب أن تعبئ الشكل بتدرجات لونية ناعمة. هناك وضعا تعبئة تدرج في تعداد GradientFill يمكن استخدامها عند رسم مستطيل. في وضع GRADIENT_FILL_RECT_H، يُملأ المستطيل من اليسار إلى اليمين. في وضع GRADIENT_FILL_RECT_V، يُملأ المستطيل من الأعلى إلى الأسفل. ملاحظة: يجب أن يتجاهل سجل EMR_GRADIENTFILL حقول Alpha في كائنات TriVertex. يمكن استخدام سجل EMR_ALPHABLEND (القسم 2.3.1.1) الذي يتبع مباشرة سجل EMR_GRADIENTFILL لتطبيق تدرج شفافية ألفا على المنطقة المملوءة.

### انظر أيضًا

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


