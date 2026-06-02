---
title: "فئة EmfNamedEscape"
type: docs
weight: 660
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfnamedescape/
---

**Summary:** The MR_NAMEDESCAPE record passes arbitrary information to a specified printer driver.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfNamedEscape

**Inheritance:** EmfEscapeRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfNamedEscape(source)](#EmfNamedEscape_source_1) | يُهيئ مثيلًا جديدًا من الفئة [EmfNamedEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfnamedescape/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| cj_driver | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات في حقل <br/>            DriverName. يجب أن تكون هذه القيمة عددًا زوجيًا. |
| cj_in | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات لتمريرها إلى برنامج تشغيل الطابعة. |
| البيانات | System.Byte | r/w | يحصل أو يعيّن البيانات التي يجب تمريرها إلى برنامج تشغيل الطابعة. يجب أن يكون هناك cjIn بايت متاح. |
| driver_name | string | r/w | يحصل أو يعيّن سلسلة من أحرف Unicode 16‑بت تحدد اسم برنامج تشغيل الطابعة الذي سيتلقى البيانات. يجب أن يكون طول هذه القيمة cjDriver بايت، ويجب أن تنتهي بحرف null.<br/>            printer driver that will receive data. This value MUST be cjDriver bytes long, and it MUST be<br/>            terminated with a null character. |
| escape | [WmfMetafileEscapes](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد أمر الهروب لبرنامج تشغيل الطابعة <br/>            لتنفيذه. يجب أن يكون هذا أحد القيم في تعداد WMF MetafileEscapes ([MSWMF] القسم 2.1.1.17). |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfNamedEscape(source) {#EmfNamedEscape_source_1}


```
 EmfNamedEscape(source) 
```

يُهيئ مثيلًا جديدًا من الفئة [EmfNamedEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfnamedescape/)

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


