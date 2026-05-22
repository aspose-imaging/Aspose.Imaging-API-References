---
title: "فئة EmfPlgBlt"
type: docs
weight: 750
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---

**Summary:** The EMR_PLGBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            parallelogram, with the application of a color mask bitmap.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPlgBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlgBlt(source)](#EmfPlgBlt_source_1) | ينشئ مثلاً جديداً من الفئة [EmfPlgBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| aptl_dest | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | يحصل أو يعيّن مصفوفة من ثلاثة كائنات WMF PointL ([MS-WMF] القسم 2.2.2.15) التي <br/>            تحدد ثلاثة زوايا لمنطقة وجهة متوازي أضلاع لعملية نقل الكتلة.<br/>            الزاوية العلوية اليسرى للمستطيل المصدر تُطابق النقطة الأولى في هذه المصفوفة، <br/>            الزاوية العلوية اليمنى تُطابق النقطة الثانية، والزاوية السفلية اليسرى تُطابق النقطة الثالثة. الزاوية السفلية اليمنى للمستطيل المصدر تُطابق النقطة الرابعة الضمنية في <br/>            متوازي الأضلاع، والتي تُحسب من الثلاث نقاط الأولى (A, B, و C) باعتبارها <br/>            متجهات. <br/>            D = B + C A |
| bk_src_argb_32_color | int | r/w | يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) يحدد <br/>            لون خلفية صورة المصدر. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) يحدد <br/>            المستطيل الحدّي، بوحدات الجهاز، للإخراج إلى الوجهة. |
| cx_src | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد العرض المنطقي للمستطيل المصدر. |
| cy_src | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد الارتفاع المنطقي للمستطيل المصدر. |
| mask_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | يحصل أو يعيّن مخزنًا يحتوي على صورة القناع، والتي ليست <br/>            مطلوبة أن تكون متجاورة مع الجزء الثابت من سجل EMR_PLGBLT أو مع بعضها البعض. <br/>            بناءً على ذلك، الحقول في هذا المخزن التي تم تسمية \"UndefinedSpace\" اختيارية ويجب تجاهلها. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | يحصل أو يعيّن مخزنًا يحتوي على صورة المصدر، والتي ليست <br/>            مطلوبة أن تكون متجاورة مع الجزء الثابت من سجل EMR_PLGBLT أو مع بعضها البعض. <br/>            بناءً على ذلك، الحقول في هذا المخزن التي تم تسمية \"UndefinedSpace\" اختيارية ويجب تجاهلها. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
| usage_mask | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد كيفية تفسير القيم في <br/>            جدول الألوان في رأس صورة القناع bitmap. يجب أن تكون هذه القيمة ضمن تعداد DIBColors. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد كيفية تفسير القيم في <br/>            جدول الألوان في رأس صورة المصدر. يجب أن تكون هذه القيمة ضمن تعداد DIBColors. |
| x_form_src | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | يحصل أو يعيّن كائن XForm (القسم 2.2.28) الذي يحدد تحويلًا من مساحة العالم إلى مساحة الصفحة لتطبيقه على صورة البت المصدر. |
| x_mask | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بتًا يحدد الإحداثي السيني المنطقي للزاوية العلوية اليسرى لصور القناع. |
| x_src | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العلوية اليسرى <br/>            للمستطيل المصدر. |
| y_mask | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بتًا يحدد الإحداثي الصادي المنطقي للزاوية العلوية اليسرى لصور القناع. |
| y_src | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العلوية اليسرى <br/>            للمستطيل المصدر. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPlgBlt(source) {#EmfPlgBlt_source_1}


```
 EmfPlgBlt(source) 
```

ينشئ مثلاً جديداً من الفئة [EmfPlgBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/).

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


