---
title: "الفئة EmfPlusSerializableObject"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSerializableObject. سجل EmfPlusSerializableObject يعرّف كتلة معلمات تأثيرات الصورة التي تم تسلسلها إلى مخزن بيانات."
type: docs
weight: 6390
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/
---
## EmfPlusSerializableObject class

السجل EmfPlusSerializableObject يعرّف كتلة معلمات تأثيرات الصورة التي تم تسلسلها إلى مخزن بيانات.

```csharp
public sealed class EmfPlusSerializableObject : EmfPlusObjectRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusSerializableObject](emfplusserializableobject/)(EmfPlusRecord) | يقوم بتهيئة نسخة جديدة من الفئة `EmfPlusSerializableObject`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Buffer](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/buffer/) { get; set; } | يحصل أو يضبط مصفوفة من بايتات BufferSize التي تحتوي على كتلة معلمات تأثيرات الصورة المسلسلة والتي تتطابق مع GUID في حقل ObjectGUID. يجب أن تكون هذه واحدة من كائنات Image Effects (القسم 2.2.3). |
| [BufferSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/buffersize/) { get; set; } | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد الحجم بالبايتات لحقل Buffer المحاذى على 32 بت. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| override [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/flags/) { get; set; } | يحصل أو يضبط عددًا صحيحًا غير موقع 16‑بت غير مستخدم. يجب أن يُضبط هذا الحقل على الصفر ويجب تجاهله عند الاستلام. |
| [ImageEffect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/imageeffect/) { get; set; } | يحصل أو يضبط تأثير الصورة. |
| [ObjectGuid](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/objectguid/) { get; set; } | يحصل أو يضبط قيمة تمثيل حزمة GUID ([MS-DTYP] القسم 2.3.4.2) لتأثير الصورة. يجب أن تتطابق هذه القيمة مع أحد معرفات ImageEffects (القسم 2.1.3.1). |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusObjectRecordType](../emfplusobjectrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


