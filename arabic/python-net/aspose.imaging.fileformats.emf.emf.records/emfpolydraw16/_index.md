---
title: "فئة EmfPolyDraw16"
type: docs
weight: 810
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolydraw16/
---

**Summary:** The EMR_POLYDRAW16 record specifies a set of line segments and Bezier curves.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyDraw16

**Inheritance:** EmfPolyShape

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPolyDraw16(source)](#EmfPolyDraw16_source_1) | ينشئ مثيلاً جديداً من الفئة [EmfPolyDraw16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolydraw16/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| a_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | يحصل أو يعيّن مصفوفة من كائنات WMF PointL ([MS-WMF] القسم 2.2.2.15) التي تحدد بيانات النقاط، بوحدات منطقية. |
| ab_types | [EmfPointEnum[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfpointenum/) | r/w | الحصول أو تعيين مصفوفة بطول Count من البايتات التي تحدد أنواع النقاط. هذه القيمة <br/>            MUST تكون ضمن تعداد Point (section 2.1.26). |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL بحجم 128 بت ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل الحدّي، بوحدات الجهاز. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPolyDraw16(source) {#EmfPolyDraw16_source_1}


```
 EmfPolyDraw16(source) 
```

ينشئ مثيلاً جديداً من الفئة [EmfPolyDraw16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolydraw16/)

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


