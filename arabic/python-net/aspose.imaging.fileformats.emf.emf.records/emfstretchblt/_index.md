---
title: "فئة EmfStretchBlt"
type: docs
weight: 1400
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/
---

**Summary:** The EMR_STRETCHBLT record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, optionally in combination with a brush pattern, according to a specified raster<br/>            operation, stretching or compressing the output to fit the dimensions of the destination, if necessary.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfStretchBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfStretchBlt()](#EmfStretchBlt__1) | ينشئ مثيلاً جديدًا من الفئة [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/). |
| [EmfStretchBlt(source)](#EmfStretchBlt_source_2) | ينشئ مثيلاً جديدًا من الفئة [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| argb_32_bk_color_src | int | r/w | يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد <br/>            لون الخلفية للصور النقطية المصدر. |
| bit_blt_raster_operation | [WmfTernaryRasterOperation](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfternaryrasteroperation/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد رمز عملية النقطية <br/>           . يحدد هذا الرمز كيفية دمج بيانات اللون للمستطيل المصدر مع <br/>            بيانات اللون للمستطيل الوجهة وربما نمط الفرشاة، للحصول على اللون النهائي. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد<br/>            المستطيل الحدودي للوجهة بوحدات الجهاز. |
| cx_dest | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد العرض المنطقي للمستطيل الوجهة. |
| cx_src | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد العرض المنطقي للمستطيل المصدر. |
| cy_dest | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد الارتفاع المنطقي للمستطيل الوجهة. |
| cy_src | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد الارتفاع المنطقي للمستطيل المصدر. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن مستطيل الوجهة. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | يحصل أو يعيّن مخزنًا يحتوي على الصورة النقطية المصدر، والتي لا يلزم أن تكون <br/>            متجاورة مع الجزء الثابت من سجل EMR_STRETCHBLT. وبالتالي، الحقول في هذا <br/>            المخزن التي تم تسميةها "UndefinedSpace" اختيارية ويجب تجاهلها. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن مستطيل المصدر. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد كيفية تفسير القيم في <br/>            جدول الألوان في رأس صورة المصدر. يجب أن تكون هذه القيمة ضمن تعداد DIBColors (القسم 2.1.9). |
| x_dest | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العلوية اليسرى <br/>            للمستطيل الوجهة. |
| x_src | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العلوية اليسرى <br/>            للمستطيل المصدر. |
| xform_src | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | يحصل أو يعيّن كائن XForm (القسم 2.2.28) الذي يحدد تحويلًا من مساحة العالم إلى مساحة الصفحة لتطبيقه على صورة البت المصدر. |
| y_dest | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العلوية اليسرى <br/>            للمستطيل الوجهة. |
| y_src | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العلوية اليسرى <br/>            للمستطيل المصدر. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfStretchBlt() {#EmfStretchBlt__1}


```
 EmfStretchBlt() 
```

ينشئ مثيلاً جديدًا من الفئة [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/).

### Constructor: EmfStretchBlt(source) {#EmfStretchBlt_source_2}


```
 EmfStretchBlt(source) 
```

ينشئ مثيلاً جديدًا من الفئة [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/).

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


