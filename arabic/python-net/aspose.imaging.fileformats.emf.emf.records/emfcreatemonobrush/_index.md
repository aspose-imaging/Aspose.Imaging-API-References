---
title: "فئة EmfCreateMonoBrush"
type: docs
weight: 300
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/
---

**Summary:** The EMR_CREATEMONOBRUSH record defines a monochrome pattern brush for graphics operations.<br/>            The pattern is specified by a monochrome DIB.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateMonoBrush

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfCreateMonoBrush(source)](#EmfCreateMonoBrush_source_1) | يُنشئ مثيلًا جديدًا للفئة [EmfCreateMonoBrush](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bitmap_buffer | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | يحصل أو يعيّن مخزنًا يحتوي على DIB مضغوط على شكل كائن WMF<br/>            DeviceIndependentBitmap ([MS-WMF] القسم 2.2.2.9). لا يلزم أن يكون<br/>            متجاورًا مع الجزء الثابت من سجل EMR_CREATEDIBPATTERNBRUSHPT. |
| ih_brush | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد فهرس كائن فرشاة النمط أحادي اللون<br/>            في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى<br/>            يمكن إعادة استخدام هذا الكائن أو تعديلّه. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
| usage | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد كيفية تفسير القيم في جدول الألوان<br/>            في رأس DIB. يجب أن تكون هذه القيمة ضمن تعداد DIBColors (القسم 2.1.9). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCreateMonoBrush(source) {#EmfCreateMonoBrush_source_1}


```
 EmfCreateMonoBrush(source) 
```

يُنشئ مثيلًا جديدًا للفئة [EmfCreateMonoBrush](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/) class.

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


