---
title: "الفئة EmfPlusFillPath"
type: docs
weight: 250
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/
---

**Summary:** Fill path record<br/>            FLAGS:<br/>            16-bit unsigned integer that provides information about how the operation is to be performed,<br/>            and about the structure of the record.<br/>            0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1<br/>            S X X X X X X X |   ObjectId    |<br/>            S (1 bit): This bit indicates the type of data in the BrushId field.<br/>            If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table.<br/>            X (1 bit): Reserved and MUST be ignored.<br/>            ObjectId (1 byte): The index of the EmfPlusPath object (section 2.2.1.6) to fill, in the EMF+ Object Table. The value MUST be zero to 63, inclusive.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillPath

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusFillPath(source)](#EmfPlusFillPath_source_1) | ينشئ مثيلًا جديدًا للفئة [EmfPlusFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| brush_id | int | r/w | الحصول أو تعيين معرف الفرشاة<br/>            عدد صحيح غير موقع 32 بت يحدد الفرشاة، المحتوى الذي يتم تحديده <br/>            بواسطة البت S في حقل Flags. |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| is_color | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الحالة ملونة.<br/> إذا تم الضبط، يحدد BrushId لونًا ككائن EmfPlusARGB (القسم 2.2.2.1). إذا لم يتم الضبط،<br/> يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+. |
| object_id | System.Byte | r/w | يحصل أو يعيّن معرف الكائن.<br/> فهرس كائن EmfPlusPath (القسم 2.2.1.6) لتعبئته، في<br/> جدول كائنات EMF+. يجب أن تكون القيمة بين الصفر و63 شاملًا. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusFillPath(source) {#EmfPlusFillPath_source_1}


```
 EmfPlusFillPath(source) 
```

ينشئ مثيلًا جديدًا للفئة [EmfPlusFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

