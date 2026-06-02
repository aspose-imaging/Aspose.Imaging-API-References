---
title: "فئة EmfExtCreatePen"
type: docs
weight: 430
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/
---

**Summary:** The EMR_EXTCREATEPEN record defines an extended logical pen for graphics operations. An<br/>            optional DIB can be specified to use as the line style.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtCreatePen

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfExtCreatePen()](#EmfExtCreatePen__1) | ينشئ مثيلاً جديدًا من الفئة [EmfExtCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/). |
| [EmfExtCreatePen(record)](#EmfExtCreatePen_record_2) | ينشئ مثيلاً جديدًا من الفئة [EmfExtCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bitmap_buffer | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | يحصل أو يعيّن مخزنًا اختياريًا يحتوي على DIB مضغوط على شكل كائن WMF DeviceIndependentBitmap<br/>            ([MS-WMF] القسم 2.2.2.9). لا يلزم أن يكون متجاورًا مع الجزء الثابت من سجل EMR_EXTCREATEPEN |
| elp | [EmfLogPenEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogpenex/) | r/w | يحصل أو يعيّن كائن LogPenEx (القسم 2.2.20) الذي يحدد قلمًا منطقيًا ممتدًا <br/>            بسمات تشمل مصفوفة نمط خط اختياري. |
| ih_pen | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد فهرس كائن القلم المنطقي الممتد <br/>            في جدول كائنات EMF (القسم 3.1.1.1). <br/>            يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديله. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfExtCreatePen() {#EmfExtCreatePen__1}


```
 EmfExtCreatePen() 
```

ينشئ مثيلاً جديدًا من الفئة [EmfExtCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/).

### Constructor: EmfExtCreatePen(record) {#EmfExtCreatePen_record_2}


```
 EmfExtCreatePen(record) 
```

ينشئ مثيلاً جديدًا من الفئة [EmfExtCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | السجل. |

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


