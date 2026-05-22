---
title: "EmfStretchDiBits فئة"
type: docs
weight: 1410
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---

**Summary:** The EMR_STRETCHDIBITS record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, optionally in combination with a brush pattern, according to a specified raster <br/>            operation, stretching or compressing the output to fit the dimensions of the destination, if necessary.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfStretchDiBits

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfStretchDiBits(source)](#EmfStretchDiBits_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfStretchDiBits](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bit_blt_raster_operation | [WmfTernaryRasterOperation](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfternaryrasteroperation/) | r/w | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑bit يحدد رمز عملية الراستر <br/>            . هذه الرموز تحدد كيفية دمج بيانات اللون للمستطيل المصدر مع <br/>            بيانات اللون للمستطيل الوجهة وربما نمط الفرشاة، لتحقيق اللون النهائي. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد<br/>            المستطيل الحدودي للوجهة بوحدات الجهاز. |
| cx_dest | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد العرض المنطقي للمستطيل الوجهة. |
| cx_src | int | r/w | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑bit يحدد العرض بالبكسل للمستطيل المصدر. |
| cy_dest | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد الارتفاع المنطقي للمستطيل الوجهة. |
| cy_src | int | r/w | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑bit يحدد الارتفاع بالبكسل للمستطيل المصدر. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | يحصل أو يضبط مخزنًا يحتوي على bitmap المصدر، والذي لا يلزم أن يكون <br/>            متجاورًا مع الجزء الثابت من سجل EMR_STRETCHDIBITS. وبالتالي، الحقول في <br/>            هذا المخزن التي تحمل تسمية "UndefinedSpace" هي اختيارية ويجب تجاهلها. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد كيفية تفسير القيم في <br/>            جدول الألوان في رأس صورة المصدر. يجب أن تكون هذه القيمة ضمن تعداد DIBColors (القسم 2.1.9). |
| x_dest | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العلوية اليسرى <br/>            للمستطيل الوجهة. |
| x_src | int | r/w | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑bit يحدد إحداثي x بالبكسل للزاوية العلوية اليسرى <br/>            للمستطيل المصدر. |
| y_dest | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العلوية اليسرى <br/>            للمستطيل الوجهة. |
| y_src | int | r/w | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑bit يحدد إحداثي y بالبكسل للزاوية العلوية اليسرى <br/>            للمستطيل المصدر. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfStretchDiBits(source) {#EmfStretchDiBits_source_1}


```
 EmfStretchDiBits(source) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfStretchDiBits](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/).

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


