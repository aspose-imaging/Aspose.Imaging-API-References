---
title: "الفئة EmfPlusObject"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusObject الفئة. سجل EmfPlusObject يحدد كائنًا للاستخدام في عمليات الرسومات. يمكن لتعريف الكائن أن يمتد عبر سجلات متعددة وهو ما يشير إليه قيمة حقل Flags."
type: docs
weight: 6280
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---
## EmfPlusObject class

السجل EmfPlusObject يحدد كائنًا للاستخدام في عمليات الرسوميات. يمكن أن تمتد تعريفات الكائن عبر سجلات متعددة، وهو ما يُشير إليه قيمة حقل Flags.

```csharp
public sealed class EmfPlusObject : EmfPlusObjectRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusObject](emfplusobject/)(EmfPlusRecord) | ينشئ مثيلًا جديدًا من الفئة `EmfPlusObject`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [IsContinuable](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/iscontinuable/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه المثيلة قابلة للاستمرار. يشير إلى أن تعريف الكائن يستمر في سجل EmfPlusObject التالي. هذا العلم لا يُضبط أبدًا في السجل النهائي الذي يحدد الكائن. |
| [ObjectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/objectdata/) { get; set; } | يحصل أو يعيّن مصفوفة من البايتات التي تحتوي على بيانات لنوع الكائن المحدد في حقل Flags. قد يختلف المحتوى والتنسيق للبيانات حسب كل نوع كائن. راجع تعريفات الكائنات الفردية في القسم 2.2.1 لمزيد من المعلومات. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/objectid/) { get; set; } | يحصل أو يعيّن معرف الكائن. الفهرس في جدول كائنات EMF+ لربطه بالكائن الذي تم إنشاؤه بواسطة هذا السجل. يجب أن تكون القيمة من صفر إلى 63، شاملة. |
| [ObjectType](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/objecttype/) { get; set; } | يحصل أو يعيّن نوع الكائن. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [TotalObjectSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/totalobjectsize/) { get; set; } | يحصل أو يعيّن الحجم الكلي للكائن. إذا كان السجل قابلًا للاستمرار، عندما يتم تعيين بت الاستمرار، سيكون هذا الحقل موجودًا. الكائنات المستمرة لديها سجلات EMF+ متعددة تبدأ بـ EmfPlusContineudObjectRecord. كل سجل EmfPlusContinuedObjectRecord سيحتوي على TotalObjectSize. بمجرد قراءة عدد البايتات المحدد بـ TotalObjectSize، لن يُعامل السجل التالي من EMF+ كجزء من الكائن المستمر. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

## ملاحظات

سجل EmfPlusObject عام؛ يُستخدم لجميع أنواع الكائنات. القيم الخاصة بأنواع كائنات معينة موجودة في حقل ObjectData. يُوصف نموذج مفهومي لإدارة كائنات الرسومات في قسم إدارة كائنات الرسومات (الفصل 3.1.2).

### انظر أيضًا

* class [EmfPlusObjectRecordType](../emfplusobjectrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


