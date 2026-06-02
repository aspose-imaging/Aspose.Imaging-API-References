---
title: "EmfPlusRotateWorldTransform.Angle"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية EmfPlusRotateWorldTransform. يحصل أو يعيّن قيمة نقطية عائمة 32‑بت تحدد زاوية الدوران بالدرجات. تُجرى العملية بإنشاء مصفوفة تحويل جديدة من المخطط التالي   sinAngle  cosAngle  0   cosAngle  sinAngle  0   الشكل 2 مصفوفة تحويل الدوران. يتم ضرب تحويل الفضاء العالمي الحالي بهذه المصفوفة وتصبح النتيجة التحويل العالمي الحالي الجديد. حقل Flags يحدد ترتيب الضرب"
type: docs
weight: 20
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/angle/
---
## EmfPlusRotateWorldTransform.Angle property

يحصل أو يعيّن قيمة عائمة 32‑بت تحدد زاوية الدوران بالدرجات. يتم تنفيذ العملية بإنشاء مصفوفة تحويل جديدة من المخطط التالي: --------------------------------- &#x7C; sin(Angle) &#x7C; cos(Angle) &#x7C; 0 &#x7C; &#x7C; cos(Angle) &#x7C; sin(Angle) &#x7C; 0 &#x7C; --------------------------------- الشكل 2: مصفوفة تحويل الدوران يتم ضرب تحويل الفضاء العالمي الحالي بهذه المصفوفة، وتصبح النتيجة التحويل الحالي للفضاء العالمي الجديد. يحدد حقل Flags ترتيب الضرب.

```csharp
public float Angle { get; set; }
```

### Property Value

الزاوية.

### انظر أيضًا

* class [EmfPlusRotateWorldTransform](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusrotateworldtransform/)
* assembly [Aspose.Imaging](../../../)


