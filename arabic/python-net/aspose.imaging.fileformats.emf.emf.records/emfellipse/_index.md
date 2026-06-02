---
title: "EmfEllipse فئة"
type: docs
weight: 370
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/
---

**Summary:** The EMR_ELLIPSE record specifies an ellipse. The center of the ellipse is the center of the specified <br/>            bounding rectangle. The ellipse is outlined by using the current pen and is filled by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfEllipse

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfEllipse()](#EmfEllipse__1) | يُنشئ مثيلًا جديدًا من [EmfEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/) فئة. |
| [EmfEllipse(source)](#EmfEllipse_source_2) | يُنشئ مثيلًا جديدًا من [EmfEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/) فئة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن RectL 128-بت (WMF)، محدد في [MS-WMF] القسم 2.2.2.19، والذي <br/>            يحدد المستطيل الحدودي الشامل-الشامل. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfEllipse() {#EmfEllipse__1}


```
 EmfEllipse() 
```

يُنشئ مثيلًا جديدًا من [EmfEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/) فئة.

### Constructor: EmfEllipse(source) {#EmfEllipse_source_2}


```
 EmfEllipse(source) 
```

يُنشئ مثيلًا جديدًا من [EmfEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/) فئة.

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


