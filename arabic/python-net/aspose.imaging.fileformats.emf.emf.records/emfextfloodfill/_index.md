---
title: "فئة EmfExtFloodFill"
type: docs
weight: 450
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/
---

**Summary:** The EMR_EXTFLOODFILL record fills an area of the display surface with the current brush

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtFloodFill

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfExtFloodFill(source)](#EmfExtFloodFill_source_1) | يُنشئ مثيلًا جديدًا من الفئة [EmfExtFloodFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| argb_32_color | int | r/w | يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8)، والذي يُستخدم مع <br/>            FloodFillMode لتحديد المنطقة التي يجب ملؤها. |
| flood_fill_mode | [EmfFloodFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emffloodfill/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد كيفية استخدام قيمة اللون <br/>            لتحديد المنطقة لعملية ملء الفيض. يجب أن تكون القيمة ضمن تعداد FloodFill <br/>            (القسم 2.1.13). |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | يحصل أو يعيّن كائن WMF PointL ([MS-WMF] القسم 2.2.2.15)، والذي يحدد <br/>            الإحداثيات، بوحدات منطقية، حيث يبدأ الملء. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfExtFloodFill(source) {#EmfExtFloodFill_source_1}


```
 EmfExtFloodFill(source) 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfExtFloodFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/) .

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


