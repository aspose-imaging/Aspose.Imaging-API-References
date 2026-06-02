---
title: "فئة EmfSmallTextOut"
type: docs
weight: 1380
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/
---

**Summary:** The EMR_SMALLTEXTOUT record outputs a string.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSmallTextOut

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfSmallTextOut(source)](#EmfSmallTextOut_source_1) | ينشئ مثلاً جديداً من الفئة [EmfSmallTextOut](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL اختياري 128‑بت ([MS-WMF] القسم 2.2.2.19) يحدد المستطيل الحدّي بوحدات الجهاز. |
| c_chars | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد الأحرف 16‑بت في<br/>            السلسلة. السلسلة ليست منتهية بـ null. |
| ex_scale | float | r/w | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقدار توسيع النص في اتجاه x. |
| ey_scale | float | r/w | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقدار توسيع النص في اتجاه y. |
| fu_options | [EmfExtTextOutOptions](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد خيارات إخراج النص المراد استخدامها. هذه<br/>            الخيارات تُحدَّد بواسطة قيمة واحدة أو مجموعة من القيم من تعداد ExtTextOutOptions<br/>            (القسم 2.1.11). |
| graphics_mode | [EmfGraphicsMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد وضع الرسومات، من تعداد<br/>            GraphicsMode (القسم 2.1.16). |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| text_string | string | r/w | يحصل أو يعيّن سلسلة ذات طول متغيّر تحتوي على نص السلسلة المراد رسمه، إما<br/>            بأكواد أحرف 8‑بت أو 16‑بت، وفقًا لقيمة الحقل fuOptions. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
| x | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد إحداثي x لمكان وضع السلسلة. |
| y | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد إحداثي y لمكان وضع السلسلة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSmallTextOut(source) {#EmfSmallTextOut_source_1}


```
 EmfSmallTextOut(source) 
```

ينشئ مثلاً جديداً من الفئة [EmfSmallTextOut](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | المصدر. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | المصدر. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | نوع السجل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


