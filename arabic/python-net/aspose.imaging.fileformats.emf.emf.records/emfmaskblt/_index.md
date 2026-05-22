---
title: "EmfMaskBlt فئة"
type: docs
weight: 600
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---

**Summary:** The EMR_MASKBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            rectangle, optionally in combination with a brush pattern and with the application of a color mask <br/>            bitmap, according to specified foreground and background raster operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMaskBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfMaskBlt(source)](#EmfMaskBlt_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfMaskBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| argb_32_bk_color_src | int | r/w | يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد <br/>            لون الخلفية للصور النقطية المصدر. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد<br/>            المستطيل الحدودي للوجهة بوحدات الجهاز. |
| cx_dest | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد العرض المنطقي للمستطيل الوجهة. |
| cy_dest | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد الارتفاع المنطقي للمستطيل الوجهة. |
| mask_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | يحصل أو يعيّن مخزنًا يحتوي على صور القناع، والتي لا <br/>            يلزم أن تكون متجاورة مع الجزء الثابت من سجل EMR_MASKBLT أو مع بعضها البعض. وبالتالي، الحقول في هذا المخزن التي تم تسميةها "UndefinedSpace" هي اختيارية و <br/>            يجب تجاهلها. |
| rop4 | [EmfRop4](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/) | r/w | يحصل أو يعيّن عملية نقطية رباعية، التي تحدد عمليات نقطية ثلاثية لألوان المقدمة والخلفية لصورة bitmap. <br/>            هذه القيم تحدد كيفية دمج بيانات اللون للمستطيل المصدر مع بيانات اللون للمستطيل الهدف. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | يحصل أو يعيّن مخزنًا يحتوي على صور المصدر، والتي لا <br/>            يلزم أن تكون متجاورة مع الجزء الثابت من سجل EMR_MASKBLT أو مع بعضها البعض. وبالتالي، الحقول في هذا المخزن التي تم تسميةها "UndefinedSpace" هي اختيارية و <br/>            يجب تجاهلها. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
| usage_mask | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد كيفية تفسير القيم في <br/>            جدول الألوان في رأس صورة القناع bitmap. يجب أن تكون هذه القيمة ضمن تعداد DIBColors. |
| usage_src | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد كيفية تفسير القيم في <br/>            جدول الألوان في رأس صورة المصدر. يجب أن تكون هذه القيمة ضمن تعداد DIBColors (القسم 2.1.9). |
| x_dest | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العلوية اليسرى <br/>            للمستطيل الوجهة. |
| x_mask | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بتًا يحدد الإحداثي السيني المنطقي للزاوية العلوية اليسرى لصور القناع. |
| x_src | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العلوية اليسرى <br/>            للمستطيل المصدر. |
| xform_src | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | يحصل أو يعيّن كائن XForm (القسم 2.2.28) الذي يحدد تحويلًا من مساحة العالم إلى مساحة الصفحة لتطبيقه على صورة البت المصدر. |
| y_dest | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العلوية اليسرى <br/>            للمستطيل الوجهة. |
| y_mask | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بتًا يحدد الإحداثي الصادي المنطقي للزاوية العلوية اليسرى لصور القناع. |
| y_src | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العلوية اليسرى <br/>            للمستطيل المصدر. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfMaskBlt(source) {#EmfMaskBlt_source_1}


```
 EmfMaskBlt(source) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfMaskBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/) .

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


