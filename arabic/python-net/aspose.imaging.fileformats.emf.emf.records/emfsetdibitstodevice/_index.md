---
title: "فئة EmfSetDiBitsToDevice"
type: docs
weight: 1150
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/
---

**Summary:** The EMR_SETDIBITSTODEVICE record specifies a block transfer of pixels from specified scan lines of <br/>            a source bitmap to a destination rectangle.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetDiBitsToDevice

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfSetDiBitsToDevice(source)](#EmfSetDiBitsToDevice_source_1) | ينشئ مثيلًا جديدًا من [EmfSetDiBitsToDevice](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/) الفئة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد<br/>            المستطيل الحدودي للوجهة بوحدات الجهاز. |
| c_scans | int | r/w | يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد عدد خطوط المسح. |
| cx_src | int | r/w | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑bit يحدد العرض بالبكسل للمستطيل المصدر. |
| cy_src | int | r/w | يحصل أو يضبط عددًا صحيحًا موقعًا 32-بت يحدد الارتفاع بالبكسل للمستطيل المصدر. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | يحصل أو يضبط مخزنًا يحتوي على صورة البت المصدر، والتي لا يلزم أن تكون <br/>            متجاورة مع الجزء الثابت من سجل EMR_SETDIBITSTODEVICE. وبالتالي، الحقول <br/>            في هذا المخزن التي تم تسمية "UndefinedSpace" اختيارية ويجب تجاهلها. |
| start_scan | int | r/w | يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد أول سطر مسح في المصفوفة. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد كيفية تفسير القيم في <br/>            جدول الألوان في رأس صورة المصدر. يجب أن تكون هذه القيمة ضمن تعداد DIBColors (القسم 2.1.9). |
| x_dest | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العلوية اليسرى <br/>            للمستطيل الوجهة. |
| x_src | int | r/w | يحصل أو يضبط عددًا صحيحًا موقعًا 32-بت يحدد الإحداثي س في البكسل للزاوية السفلية اليسرى <br/>            للمستطيل المصدر. |
| y_dest | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العلوية اليسرى <br/>            للمستطيل الوجهة. |
| y_src | int | r/w | يحصل أو يضبط عددًا صحيحًا موقعًا 32-بت يحدد الإحداثي ص في البكسل للزاوية السفلية اليسرى <br/>            للمستطيل المصدر. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetDiBitsToDevice(source) {#EmfSetDiBitsToDevice_source_1}


```
 EmfSetDiBitsToDevice(source) 
```

ينشئ مثيلًا جديدًا من [EmfSetDiBitsToDevice](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/) الفئة.

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


