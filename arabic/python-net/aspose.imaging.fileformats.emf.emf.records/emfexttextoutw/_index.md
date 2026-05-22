---
title: "EmfExtTextOutW فئة"
type: docs
weight: 480
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/
---

**Summary:** The EMR_EXTTEXTOUTW record draws an ASCII text string using the current font and text colors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtTextOutW

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfExtTextOutW()](#EmfExtTextOutW__1) | يُنشئ نسخة جديدة من الفئة [EmfExtTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/). |
| [EmfExtTextOutW(source)](#EmfExtTextOutW_source_2) | يُنشئ نسخة جديدة من الفئة [EmfExtTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19). لا يُستخدم ويجب <br/>            تجاهله عند الاستلام. |
| ex_scale | float | r/w | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد معامل التحجيم لتطبيقه على <br/>            محور X لتحويل وحدات مساحة الصفحة إلى وحدات .01 مم. يجب أن يُستخدم هذا فقط إذا كان وضع الرسومات المحدد بواسطة iGraphicsMode هو GM_COMPATIBLE. |
| ey_scale | float | r/w | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد معامل التحجيم لتطبيقه على <br/>            محور Y لتحويل وحدات مساحة الصفحة إلى وحدات .01 مم. يجب أن يُستخدم هذا فقط إذا كان وضع الرسومات المحدد بواسطة iGraphicsMode هو GM_COMPATIBLE. |
| graphics_mode | [EmfGraphicsMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد وضع الرسومات من تعداد <br/>            GraphicsMode (القسم 2.1.16). |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
| w_emr_text | [EmfText](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emftext/) | r/w | يحصل أو يعيّن كائن EmrText (القسم 2.2.5) يحدد سلسلة الإخراج في أحرف Unicode UTF16-LE 16-بت، مع سمات النص وقيم التباعد. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfExtTextOutW() {#EmfExtTextOutW__1}


```
 EmfExtTextOutW() 
```

يُنشئ نسخة جديدة من الفئة [EmfExtTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/).

### Constructor: EmfExtTextOutW(source) {#EmfExtTextOutW_source_2}


```
 EmfExtTextOutW(source) 
```

يُنشئ نسخة جديدة من الفئة [EmfExtTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/).

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


