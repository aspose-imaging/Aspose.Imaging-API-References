---
title: "فئة EmfExtTextOutA"
type: docs
weight: 470
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextouta/
---

**Summary:** The EMR_EXTTEXTOUTA record draws an ASCII text string using the current font and text colors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtTextOutA

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfExtTextOutA()](#EmfExtTextOutA__1) | يُنشئ مثيلًا جديدًا للفئة [EmfExtTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextouta/) class. |
| [EmfExtTextOutA(source)](#EmfExtTextOutA_source_2) | يُنشئ مثيلًا جديدًا للفئة [EmfExtTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextouta/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| a_emr_text | [EmfText](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emftext/) | r/w | يحصل أو يعيّن كائن EmrText (القسم 2.2.5) يحدد سلسلة الإخراج بحروف ASCII 8‑بت <br/>            وسمات النص، وقيم التباعد. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19). لا يُستخدم ويجب <br/>            تجاهله عند الاستلام. |
| ex_scale | float | r/w | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد معامل التحجيم لتطبيقه على <br/>            محور X لتحويل وحدات مساحة الصفحة إلى وحدات .01 مم. يجب أن يُستخدم هذا فقط إذا كان وضع الرسومات المحدد بواسطة iGraphicsMode هو GM_COMPATIBLE. |
| ey_scale | float | r/w | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد معامل التحجيم لتطبيقه على <br/>            محور Y لتحويل وحدات مساحة الصفحة إلى وحدات .01 مم. يجب أن يُستخدم هذا فقط إذا كان وضع الرسومات المحدد بواسطة iGraphicsMode هو GM_COMPATIBLE. |
| graphics_mode | [EmfGraphicsMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد وضع الرسومات من تعداد <br/>            GraphicsMode (القسم 2.1.16). |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfExtTextOutA() {#EmfExtTextOutA__1}


```
 EmfExtTextOutA() 
```

يُنشئ مثيلًا جديدًا للفئة [EmfExtTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextouta/) class.

### Constructor: EmfExtTextOutA(source) {#EmfExtTextOutA_source_2}


```
 EmfExtTextOutA(source) 
```

يُنشئ مثيلًا جديدًا للفئة [EmfExtTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextouta/) class.

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


