---
title: "فئة EmfPolyTextOutW"
type: docs
weight: 890
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/
---

**Summary:** The EMR_POLYTEXTOUTW record draws one or more Unicode text strings using the current font and text colors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyTextOutW

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPolyTextOutW()](#EmfPolyTextOutW__1) | يُنشئ مثيلًا جديدًا من الفئة [EmfPolyTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/) . |
| [EmfPolyTextOutW(source)](#EmfPolyTextOutW_source_2) | يُنشئ مثيلًا جديدًا من الفئة [EmfPolyTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19)، الذي يحدد <br/>            المستطيل المحيط بوحدات الجهاز. |
| ex_scale | float | r/w | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقياس X من وحدات الصفحة إلى وحدات .01 مم إذا كان وضع الرسومات GM_COMPATIBLE. |
| ey_scale | float | r/w | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقياس Y من وحدات الصفحة إلى وحدات .01 مم إذا كان وضع الرسومات GM_COMPATIBLE. |
| graphics_mode | [EmfGraphicsMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد وضع الرسومات الحالي، <br/>            من تعداد GraphicsMode (القسم 2.1.16). |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
| w_emr_text | [EmfText[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emftext/) | r/w | يحصل أو يعيّن مصفوفة من كائنات EmrText (القسم 2.2.5) التي تحدد سلاسل الإخراج <br/>            في أحرف Unicode UTF16-LE 16‑بت، مع سمات النص وقيم التباعد. عدد كائنات EmrText يحدده cStrings. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPolyTextOutW() {#EmfPolyTextOutW__1}


```
 EmfPolyTextOutW() 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfPolyTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/) .

### Constructor: EmfPolyTextOutW(source) {#EmfPolyTextOutW_source_2}


```
 EmfPolyTextOutW(source) 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfPolyTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/) .

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


