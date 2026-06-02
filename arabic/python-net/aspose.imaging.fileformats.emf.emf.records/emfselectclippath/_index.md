---
title: "فئة EmfSelectClipPath"
type: docs
weight: 1060
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/
---

**Summary:** The EMR_SELECTCLIPPATH record specifies the current path as a clipping region for a playback <br/>            device context, combining the new region with any existing clipping region using the specified mode.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSelectClipPath

**Inheritance:** EmfClippingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfSelectClipPath()](#EmfSelectClipPath__1) | يُهيئ مثيلًا جديدًا من الفئة [EmfSelectClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/) |
| [EmfSelectClipPath(source)](#EmfSelectClipPath_source_2) | يُهيئ مثيلًا جديدًا من الفئة [EmfSelectClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| region_mode | [EmfRegionMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfregionmode/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد طريقة استخدام المسار. يجب أن تكون القيمة <br/>            في تعداد RegionMode (القسم 2.1.29). |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSelectClipPath() {#EmfSelectClipPath__1}


```
 EmfSelectClipPath() 
```

يُهيئ مثيلًا جديدًا من الفئة [EmfSelectClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/)

### Constructor: EmfSelectClipPath(source) {#EmfSelectClipPath_source_2}


```
 EmfSelectClipPath(source) 
```

يُهيئ مثيلًا جديدًا من الفئة [EmfSelectClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/)

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


