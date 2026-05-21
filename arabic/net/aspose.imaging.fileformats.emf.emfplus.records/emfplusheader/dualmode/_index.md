---
title: "EmfPlusHeader.DualMode"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية EmfPlusHeader. تحصل أو تعين قيمة تشير إلى ما إذا كان الوضع المزدوج. إذا تم تعيين هذا العلم فإن ذلك يشير إلى أن ملف الميتا هو وضع مزدوج مما يعني أنه يحتوي على مجموعتين من السجلات كل واحدة تحدد محتوى الرسومات بالكامل. إذا كان غير معين فإن محتوى الرسومات يُحدد بسجلات EMF وربما سجلات EMF التي تسبقها سجل EmfPlusGetDC. إذا تم تعيين هذا العلم يجب أن تكون سجلات EMF وحدها كافية لتعريف محتوى الرسومات. لاحظ أنه سواء تم تعيين علم الوضع المزدوج أم لا فإن بعض سجلات EMF تكون دائمًا موجودة وهي سجلات التحكم في EMF والسجلات التي تحتوي على سجلات EMF. سجلات التحكم في EMF محددة في قسم MSEMF 2.3.4"
type: docs
weight: 20
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/dualmode/
---
## EmfPlusHeader.DualMode property

يحصل أو يعيّن قيمة تشير إلى ما إذا كان [dual mode]. إذا تم تعيينها، فإن هذه العلامة تشير إلى أن ملف التعريف هذا هو \"dual-mode\", مما يعني أنه يحتوي على مجموعتين من السجلات، كل واحدة تحدد محتوى الرسومات بالكامل. إذا لم تُحدد، يتم تحديد محتوى الرسومات بواسطة سجلات EMF+, وربما سجلات EMF التي تسبقها سجل EmfPlusGetDC. إذا تم تعيين هذه العلامة، يجب أن تكون سجلات EMF وحدها كافية لتعريف محتوى الرسومات. لاحظ أنه سواء تم تعيين علامة \"dual-mode\" أم لا، فإن بعض سجلات EMF تكون موجودة دائمًا، وهي سجلات التحكم في EMF والسجلات التي تحتوي على سجلات EMF+. سجلات التحكم في EMF محددة في [MS-EMF] القسم 2.3.4.

```csharp
public bool DualMode { get; set; }
```

### Property Value

`true` إذا كان [dual mode]؛ وإلا `false`.

### انظر أيضًا

* class [EmfPlusHeader](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusheader/)
* assembly [Aspose.Imaging](../../../)


