---
title: "الفئة EmfSetPolyFillMode"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetPolyFillMode. السجل EMR_SETPOLYFILLMODE يحدد وضع ملء المضلع."
type: docs
weight: 4580
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/
---
## EmfSetPolyFillMode class

سجل EMR_SETPOLYFILLMODE يعرّف وضعية تعبئة المضلع.

```csharp
public sealed class EmfSetPolyFillMode : EmfStateRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfSetPolyFillMode](emfsetpolyfillmode/#constructor)() | يُنشئ مثيلاً جديدًا للفئة `EmfSetPolyFillMode`. |
| [EmfSetPolyFillMode](emfsetpolyfillmode/#constructor_1)(EmfRecord) | يُنشئ مثيلاً جديدًا للفئة `EmfSetPolyFillMode`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [PolygonFillMode](../../aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/polygonfillmode/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد وضع ملء المضلع ويجب أن يكون ضمن تعداد PolygonFillMode (القسم 2.1.27). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

## ملاحظات

عمومًا، تختلف الأوضاع فقط في الحالات التي يجب فيها ملء مضلع معقد ومتداخل؛ على سبيل المثال، مضلع خماسي الشكل يشكل نجمة خماسية النقاط مع مضلع خماسي في المركز. في مثل هذه الحالات، يجب أن يملأ وضع ALTERNATE كل منطقة مغلقة أخرى داخل المضلع (نقاط النجمة)، بينما يجب أن يملأ وضع WINDING جميع المناطق (نقاط النجمة والمضلع الخماسي). عندما يكون وضع الملء هو ALTERNATE، يجب ملء المساحة بين الجوانب ذات الأرقام الفردية والزوجية للمضلع في كل خط مسح. أي أن المساحة بين الجانب الأول والثاني يجب أن تُملأ، وكذلك بين الجانب الثالث والرابع، وهكذا. عندما يكون وضع الملء هو WINDING، يجب ملء أي منطقة لها قيمة winding غير صفرية. قيمة winding هي عدد المرات التي يمر فيها القلم المستخدم لرسم المضلع حول المنطقة. اتجاه كل حافة من حواف المضلع مهم.

### انظر أيضًا

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


