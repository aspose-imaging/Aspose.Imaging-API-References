---
title: "فئة EmfPlusDrawImage"
type: docs
weight: 130
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/
---

**Summary:** The EmfPlusDrawImage record specifies drawing a scaled image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawImage

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusDrawImage(source)](#EmfPlusDrawImage_source_1) | يُنشئ مثلاً جديدًا من الفئة [EmfPlusDrawImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| مضغوط | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت PointData مضغوطة.<br/> إذا تم الضبط، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38).<br/> إذا لم يتم الضبط، يحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39). |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| image_attributes_id | int | r/w | يحصل أو يعيّن معرف سمات الصورة<br/>            عدد صحيح غير موقع 32-بت يحدد فهرس كائن EmfPlusImageAttributes اختياري (القسم 2.2.1.5) في جدول كائنات EMF+. |
| object_id | System.Byte | r/w | يحصل أو يضبط معرف الكائن.<br/>            فهرس كائن EmfPlusImage (القسم 2.2.1.4) في جدول كائنات EMF+<br/>            الذي يحدد الصورة التي سيتم عرضها. يجب أن تكون القيمة بين 0 و 63 شاملًا. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | يحصل أو يعيّن بيانات المستطيل<br/>            إما كائن EmfPlusRect أو EmfPlusRectF يحدد الصندوق المحيط بالصورة.<br/>            الجزء من الصورة المحدد بحقل SrcRect يُقاس ليتناسب مع هذا المستطيل. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | يحصل أو يعيّن المستطيل المصدر<br/>            كائن EmfPlusRectF يحدد جزءًا من الصورة ليُعرض.<br/>            الجزء من الصورة المحدد بهذا المستطيل يُقاس ليتناسب مع المستطيل الوجهة المحدد بحقل RectData. |
| src_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | يحصل أو يعيّن وحدة المصدر<br/>            عدد صحيح موقّع 32-بت يحدد وحدات حقل SrcRect.<br/>            يجب أن تكون القيمة هي العنصر UnitTypePixel من تعداد UnitType (القسم 2.1.1.33). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusDrawImage(source) {#EmfPlusDrawImage_source_1}


```
 EmfPlusDrawImage(source) 
```

يُنشئ مثلاً جديدًا من الفئة [EmfPlusDrawImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

