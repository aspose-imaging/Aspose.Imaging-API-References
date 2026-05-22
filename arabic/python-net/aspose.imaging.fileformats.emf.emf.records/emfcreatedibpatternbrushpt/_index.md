---
title: "فئة EmfCreateDibPatternBrushPt"
type: docs
weight: 290
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/
---

**Summary:** The EMR_CREATEDIBPATTERNBRUSHPT record defines a pattern brush for graphics operations. The<br/>            pattern is specified by a DIB.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateDibPatternBrushPt

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfCreateDibPatternBrushPt()](#EmfCreateDibPatternBrushPt__1) | يُنشئ مثيلًا جديدًا من الفئة [EmfCreateDibPatternBrushPt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/) . |
| [EmfCreateDibPatternBrushPt(source)](#EmfCreateDibPatternBrushPt_source_2) | يُنشئ مثيلًا جديدًا من الفئة [EmfCreateDibPatternBrushPt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bitmap_buffer | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | يحصل أو يعيّن مخزنًا يحتوي على DIB مضغوط على شكل كائن WMF<br/>            DeviceIndependentBitmap ([MS-WMF] القسم 2.2.2.9). لا يلزم أن يكون<br/>            متجاورًا مع الجزء الثابت من سجل EMR_CREATEDIBPATTERNBRUSHPT. |
| ih_brush | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد فهرس فرشاة النمط<br/>            في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن<br/>            أو تعديله. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
| usage | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد كيفية تفسير القيم في جدول الألوان<br/>            في رأس DIB. يجب أن تكون هذه القيمة ضمن تعداد DIBColors (القسم 2.1.9). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCreateDibPatternBrushPt() {#EmfCreateDibPatternBrushPt__1}


```
 EmfCreateDibPatternBrushPt() 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfCreateDibPatternBrushPt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/) .

### Constructor: EmfCreateDibPatternBrushPt(source) {#EmfCreateDibPatternBrushPt_source_2}


```
 EmfCreateDibPatternBrushPt(source) 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfCreateDibPatternBrushPt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/) .

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


