---
title: "فئة EmfPolyTextOutA"
type: docs
weight: 880
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/
---

**Summary:** The EMR_POLYTEXTOUTA record draws one or more ASCII text strings using the current font and text colors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyTextOutA

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPolyTextOutA()](#EmfPolyTextOutA__1) | يُنشئ مثيلاً جديدًا من الفئة [EmfPolyTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/). |
| [EmfPolyTextOutA(source)](#EmfPolyTextOutA_source_2) | يُنشئ مثيلاً جديدًا من الفئة [EmfPolyTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| a_emr_text | [EmfText[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emftext/) | r/w | يحصل أو يعيّن مصفوفة من كائنات EmrText (القسم 2.2.5) التي تحدد سلاسل الإخراج <br/>            بترميز ASCII 8‑بت، مع سمات النص وقيم التباعد. عدد كائنات EmrText يحدده cStrings. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19)، الذي يحدد <br/>            المستطيل المحيط بوحدات الجهاز. |
| ex_scale | float | r/w | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقياس X من وحدات الصفحة إلى وحدات .01 مم إذا كان وضع الرسومات GM_COMPATIBLE. |
| ey_scale | float | r/w | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقياس Y من وحدات الصفحة إلى وحدات .01 مم إذا كان وضع الرسومات GM_COMPATIBLE. |
| graphics_mode | [EmfGraphicsMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد وضع الرسومات الحالي، <br/>            من تعداد GraphicsMode (القسم 2.1.16). |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPolyTextOutA() {#EmfPolyTextOutA__1}


```
 EmfPolyTextOutA() 
```

يُنشئ مثيلاً جديدًا من الفئة [EmfPolyTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/).

### Constructor: EmfPolyTextOutA(source) {#EmfPolyTextOutA_source_2}


```
 EmfPolyTextOutA(source) 
```

يُنشئ مثيلاً جديدًا من الفئة [EmfPolyTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/).

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


