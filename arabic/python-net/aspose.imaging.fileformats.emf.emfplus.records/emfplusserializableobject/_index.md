---
title: "الفئة EmfPlusSerializableObject"
type: docs
weight: 440
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/
---

**Summary:** The EmfPlusSerializableObject record defines an image effects parameter block that has been<br/>            serialized into a data buffer.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSerializableObject

**Inheritance:** EmfPlusObjectRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusSerializableObject(source)](#EmfPlusSerializableObject_source_1) | تهيئة نسخة جديدة من الفئة [EmfPlusSerializableObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| المخزن المؤقت | System.Byte | r/w | الحصول أو تعيين مصفوفة من بايتات BufferSize التي تحتوي على كتلة معلمات تأثيرات الصورة المتسلسلة<br/>            والتي تتطابق مع GUID في حقل ObjectGUID. يجب أن تكون واحدة من<br/>            كائنات تأثيرات الصورة (القسم 2.2.3). |
| حجم_المخزن_المؤقت | int | r/w | الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد الحجم بالبايتات لحقل Buffer المحاذى على 32 بت. |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | الحصول أو تعيين عدد صحيح غير موقع 16‑بت غير مستخدم. يجب أن يتم تعيين هذا الحقل إلى صفر<br/>            ويجب تجاهله عند الاستلام. |
| image_effect | [EmfPlusImageEffectsObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype/) | r/w | الحصول أو تعيين تأثير الصورة. |
| object_guid | [GuidPacketRepresentation](/imaging/python-net/aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation/) | r/w | الحصول أو تعيين قيمة تمثيل حزمة GUID ([MS-DTYP] القسم 2.3.4.2)<br/>            لتأثير الصورة. يجب أن تتطابق هذه القيمة مع أحد معرفات ImageEffects (القسم 2.1.3.1). |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusSerializableObject(source) {#EmfPlusSerializableObject_source_1}


```
 EmfPlusSerializableObject(source) 
```

تهيئة نسخة جديدة من الفئة [EmfPlusSerializableObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

