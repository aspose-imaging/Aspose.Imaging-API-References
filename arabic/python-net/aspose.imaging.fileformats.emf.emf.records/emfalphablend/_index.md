---
title: "فئة EmfAlphaBlend"
type: docs
weight: 20
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/
---

**Summary:** The EMR_ALPHABLEND record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, including alpha transparency data, according to a specified blending operation.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfAlphaBlend

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfAlphaBlend(source)](#EmfAlphaBlend_source_1) | ينشئ مثلاً جديداً من الفئة [EmfAlphaBlend](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bk_src_argb_32_color | int | r/w | يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد<br/>            لون خلفية صورة المصدر. |
| blend_function | [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/) | r/w | يحصل أو يعيّن بنية تحدد عمليات الدمج للصور المصدرية و<br/>            الصور الوجهة. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد<br/>            المستطيل الحدودي للوجهة بوحدات الجهاز. |
| cx_dest | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد العرض المنطقي للمستطيل الوجهة <br/>            . يجب أن تكون هذه القيمة أكبر من الصفر. |
| cx_src | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد العرض المنطقي للمستطيل المصدر. <br/>            يجب أن تكون هذه القيمة أكبر من الصفر. |
| cy_dest | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد الارتفاع المنطقي للمستطيل الوجهة <br/>            . يجب أن تكون هذه القيمة أكبر من الصفر. |
| cy_src | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد الارتفاع المنطقي للمستطيل المصدر <br/>            . يجب أن تكون هذه القيمة أكبر من الصفر. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | يحصل أو يعيّن مخزنًا يحتوي على صورة المصدر، والتي لا يُشترط أن تكون <br/>            متصلة بالجزء الثابت من سجل EMR_ALPHABLEND. وبالتالي، الحقول في هذا <br/>            المخزن التي تم تسميتها "UndefinedSpace" هي اختيارية ويجب تجاهلها. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد كيفية تفسير القيم في <br/>            جدول الألوان في رأس صورة المصدر. يجب أن تكون هذه القيمة ضمن تعداد DIBColors (القسم 2.1.9). |
| x_dest | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العلوية اليسرى <br/>            للمستطيل الوجهة. |
| x_src | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العلوية اليسرى <br/>            للمستطيل المصدر. |
| xform_sr | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | يحصل أو يعيّن كائن XForm (القسم 2.2.28) الذي يحدد تحويلًا من مساحة العالم إلى مساحة الصفحة لتطبيقه على صورة البت المصدر. |
| y_dest | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العلوية اليسرى <br/>            للمستطيل الوجهة. |
| y_src | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العلوية اليسرى <br/>            للمستطيل المصدر. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfAlphaBlend(source) {#EmfAlphaBlend_source_1}


```
 EmfAlphaBlend(source) 
```

ينشئ مثلاً جديداً من الفئة [EmfAlphaBlend](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/)

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


