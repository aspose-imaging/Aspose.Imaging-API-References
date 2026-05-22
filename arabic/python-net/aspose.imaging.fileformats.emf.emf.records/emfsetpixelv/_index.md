---
title: "فئة EmfSetPixelV"
type: docs
weight: 1260
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/
---

**Summary:** The EMR_SETPIXELV record defines the color of the pixel at the specified logical coordinates.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetPixelV

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfSetPixelV()](#EmfSetPixelV__1) | ينشئ مثيلًا جديدًا من [EmfSetPixelV](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/) الفئة. |
| [EmfSetPixelV(source)](#EmfSetPixelV_source_2) | ينشئ مثيلًا جديدًا من [EmfSetPixelV](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/) الفئة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| argb_32_color | int | r/w | يحصل أو يضبط كائن ColorRef WMF 32-بت ([MS-WMF] القسم 2.2.2.8) يحدد لون البكسل. |
| pixel | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | يحصل أو يضبط كائن PointL WMF 64-بت ([MS-WMF] القسم 2.2.2.15) يحدد <br/>            الإحداثيات المنطقية للبكسل. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetPixelV() {#EmfSetPixelV__1}


```
 EmfSetPixelV() 
```

ينشئ مثيلًا جديدًا من [EmfSetPixelV](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/) الفئة.

### Constructor: EmfSetPixelV(source) {#EmfSetPixelV_source_2}


```
 EmfSetPixelV(source) 
```

ينشئ مثيلًا جديدًا من [EmfSetPixelV](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/) الفئة.

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


