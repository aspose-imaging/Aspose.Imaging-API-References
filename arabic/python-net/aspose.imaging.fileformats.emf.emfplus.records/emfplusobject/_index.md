---
title: "فئة EmfPlusObject"
type: docs
weight: 330
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---

**Summary:** The EmfPlusObject record specifies an object for use in graphics operations. The object definition<br/>            can span multiple records, which is indicated by the value of the Flags field.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObject

**Inheritance:** EmfPlusObjectRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusObject(source)](#EmfPlusObject_source_1) | يُنشئ مثيلًا جديدًا من الفئة [EmfPlusObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| is_continuable | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الحالة قابلة للاستمرار.<br/> يشير إلى أن تعريف الكائن يستمر في سجل EmfPlusObject التالي.<br/> لا يتم ضبط هذه العلامة أبدًا في السجل النهائي الذي يعرّف الكائن. |
| object_data | [EmfPlusGraphicsObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/) | r/w | يحصل أو يعيّن مصفوفة من البايتات التي تحتوي على بيانات لنوع الكائن المحدد في<br/> حقل Flags. قد يختلف محتوى وتنسيق البيانات لكل نوع كائن. راجع<br/> تعريفات الكائنات الفردية في القسم 2.2.1 لمزيد من المعلومات. |
| object_id | System.Byte | r/w | يحصل أو يعيّن معرف الكائن.<br/> الفهرس في جدول كائنات EMF+ لربطه بالكائن<br/> الذي أنشأه هذا السجل. يجب أن تكون القيمة بين الصفر و63 شاملًا. |
| object_type | [EmfPlusObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusobjecttype/) | r/w | يحصل أو يعيّن نوع الكائن. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| total_object_size | int | r/w | يحصل أو يعيّن الحجم الكلي للكائن.<br/> إذا كان السجل قابلًا للاستمرار، عندما يتم ضبط بتة الاستمرار، سيظهر هذا الحقل.<br/> الكائنات المستمرة لديها سجلات EMF+ متعددة تبدأ بـ EmfPlusContineudObjectRecord. كل سجل EmfPlusContinuedObjectRecord سيحتوي على TotalObjectSize. بمجرد قراءة عدد البايتات المحدد بـ TotalObjectSize، لن يُعامل السجل EMF+ التالي كجزء من الكائن المستمر. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusObject(source) {#EmfPlusObject_source_1}


```
 EmfPlusObject(source) 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfPlusObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

