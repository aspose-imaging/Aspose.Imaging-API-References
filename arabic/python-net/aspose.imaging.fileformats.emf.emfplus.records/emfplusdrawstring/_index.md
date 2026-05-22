---
title: "فئة EmfPlusDrawString"
type: docs
weight: 190
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---

**Summary:** The EmfPlusDrawString record specifies text output with string formatting

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawString

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusDrawString(source)](#EmfPlusDrawString_source_1) | يُنشئ مثلاً جديداً من الفئة [EmfPlusDrawString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| brush_id | int | r/w | يحصل أو يعيّن معرف الفرشاة<br/>            عدد صحيح غير موقع 32-بت يحدد الفرشاة، ومحتواها يتم تحديده بواسطة البت S في حقل العلامات. يُستخدم هذا التعريف لطلاء لون النص الأمامي؛ أي، فقط الأحرف نفسها. |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| format_id | int | r/w | يحصل أو يعيّن معرف التنسيق<br/>            عدد صحيح غير موقع 32-بت يحدد فهرس كائن EmfPlusStringFormat اختياري (القسم 2.2.1.9) في جدول كائنات EMF+. <br/>            يحدد هذا الكائن معلومات تخطيط النص وتعديلات العرض <br/>            التي تُطبق على سلسلة. |
| is_color | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الحالة ملونة.<br/>            إذا تم التعيين، يحدد BrushId اللون ككائن EmfPlusARGB (القسم 2.2.2.1).<br/>            إذا لم يتم التعيين، يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+. |
| layout_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | يحصل أو يعيّن مستطيل التخطيط<br/>            كائن EmfPlusRectF (القسم 2.2.2.39) الذي يحدد المنطقة المحصورة للوجهة التي ستستقبل السلسلة. |
| length | int | r/w | يحصل أو يعيّن الطول<br/>            عدد صحيح غير موقع 32-بت يحدد عدد الأحرف في السلسلة. |
| object_id | System.Byte | r/w | يحصل أو يعيّن معرف الكائن.<br/>            فهرس كائن EmfPlusFont (القسم 2.2.1.3) في جدول كائنات EMF+ لتصيير النص. يجب أن تكون القيمة بين الصفر و63 شاملًا. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| string_data | string | r/w | يحصل أو يعيّن بيانات السلسلة<br/>            مصفوفة من أحرف Unicode 16-بت تحدد السلسلة التي سيتم رسمها |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusDrawString(source) {#EmfPlusDrawString_source_1}


```
 EmfPlusDrawString(source) 
```

يُنشئ مثلاً جديداً من الفئة [EmfPlusDrawString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

