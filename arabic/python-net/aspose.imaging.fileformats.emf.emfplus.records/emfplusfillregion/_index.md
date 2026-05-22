---
title: "فئة EmfPlusFillRegion"
type: docs
weight: 290
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/
---

**Summary:** The EmfPlusFillRegion record specifies filling the interior of a graphics region

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillRegion

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusFillRegion(source)](#EmfPlusFillRegion_source_1) | يُنشئ مثلاً جديدًا من الفئة [EmfPlusFillRegion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| brush_id | int | r/w | الحصول أو تعيين معرف الفرشاة<br/>            عدد صحيح غير موقع 32‑بت يحدد الفرشاة، والمحتوى يتم تحديده بواسطة بت S في حقل Flags. |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| is_color | bool | r/w | الحصول أو تعيين قيمة تشير إلى ما إذا كان هذا المثيل لونيًا.<br/>            إذا تم تعيينه، يحدد BrushId لونًا ككائن EmfPlusARGB (القسم 2.2.2.1). <br/>            إذا لم يتم تعيينه، يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+. |
| object_id | System.Byte | r/w | يحصل أو يعيّن معرف الكائن.<br/>            فهرس كائن EmfPlusRegion (القسم 2.2.1.8) للتعبئة، في جدول كائنات EMF+. يجب أن تكون القيمة بين الصفر و63، شاملًا. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusFillRegion(source) {#EmfPlusFillRegion_source_1}


```
 EmfPlusFillRegion(source) 
```

يُنشئ مثلاً جديدًا من الفئة [EmfPlusFillRegion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

