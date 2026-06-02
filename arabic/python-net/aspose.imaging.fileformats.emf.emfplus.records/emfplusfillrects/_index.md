---
title: "فئة EmfPlusFillRects"
type: docs
weight: 280
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/
---

**Summary:** The EmfPlusFillRects record specifies filling the interiors of a series of rectangles

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillRects

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusFillRects(source)](#EmfPlusFillRects_source_1) | إنشاء نسخة جديدة من الفئة [EmfPlusFillRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| brush_id | int | r/w | الحصول أو تعيين معرف الفرشاة<br/>            عدد صحيح غير موقع 32‑بت يحدد الفرشاة، والمحتوى يتم تحديده بواسطة بت S في حقل Flags. |
| compressed | bool | r/w | الحصول أو تعيين قيمة تشير إلى ما إذا كان هذا [EmfPlusFillRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/) مضغوطًا.<br/>            إذا تم التعيين، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38). إذا لم يتم التعيين، يحتوي RectData<br/>             على كائن EmfPlusRectF (القسم 2.2.2.39). |
| data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يجب أن يحدد عدد البايتات المتوافقة مع 32 بت في حقل RecordData التالي.<br/>            لا تشمل هذه العدد رأس السجل البالغ 12 بايت. |
| العلامات | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل.<br/> |
| is_color | bool | r/w | الحصول أو تعيين قيمة تشير إلى ما إذا كانت هذه الحالة لونية.<br/>            إذا تم التعيين، يحدد BrushId اللون ككائن EmfPlusARGB (القسم 2.2.2.1).<br/>            إذا لم يتم التعيين، يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+. |
| rect_data | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | الحصول أو تعيين بيانات المستطيل<br/>            مصفوفة من كائنات EmfPlusRect أو EmfPlusRectF بطول Count التي تحدد بيانات المستطيل. |
| الحجم | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات المتوافقة مع 32 بت في السجل بالكامل، بما في ذلك رأس السجل البالغ 12 بايت والبيانات الخاصة بالسجل.<br/> |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | يحصل على عدد صحيح غير موقع 16 بت يحدد نوع السجل. |


### Constructor: EmfPlusFillRects(source) {#EmfPlusFillRects_source_1}


```
 EmfPlusFillRects(source) 
```

إنشاء نسخة جديدة من الفئة [EmfPlusFillRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | المصدر. |

