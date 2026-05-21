---
title: "الفئة EmfSetRop2"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetRop2. سجل EMR_SETROP2 يحدد وضع عملية نقطية ثنائية."
type: docs
weight: 4590
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/
---
## EmfSetRop2 class

سجل EMR_SETROP2 يعرّف وضعية عملية نقطية ثنائية.

```csharp
public sealed class EmfSetRop2 : EmfStateRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfSetRop2](emfsetrop2/#constructor)() | يُنشئ مثيلاً جديدًا للفئة `EmfSetRop2`. |
| [EmfSetRop2](emfsetrop2/#constructor_1)(EmfRecord) | يُنشئ مثيلاً جديدًا للفئة `EmfSetRop2`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Rop2Mode](../../aspose.imaging.fileformats.emf.emf.records/emfsetrop2/rop2mode/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد وضع عملية النقطية ويجب أن يكون ضمن تعداد عمليات النقطية الثنائية في WMF ([MS-WMF] القسم 2.1.1.2). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

## ملاحظات

تحدد أوضاع خلط عمليات النقطية الثنائية كيفية دمج ألوان المصدر والوجهة عند الرسم بالقلم الحالي. أوضاع الخلط هي رموز عمليات نقطية ثنائية، تمثل جميع الدوال البوليانية الممكنة لمتغيرين، باستخدام عمليات AND و OR و XOR (أو الحصري)، وعملية NOT الأحادية. وضع الخلط مخصص لأجهزة النقطية فقط؛ ولا يتوفر لأجهزة المتجهات.

### انظر أيضًا

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


