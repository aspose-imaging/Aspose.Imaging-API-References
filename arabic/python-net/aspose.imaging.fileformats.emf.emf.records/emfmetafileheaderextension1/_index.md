---
title: "فئة EmfMetafileHeaderExtension1"
type: docs
weight: 620
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/
---

**Summary:** The EmfMetafileHeaderExtension1 record is the header record used in the first extension to EMF metafiles.<br/>            Following the EmfHeaderExtension1 field, the remaining fields are optional and can be present in any order.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1

**Inheritance:** EmfMetafileHeader

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfMetafileHeaderExtension1(header)](#EmfMetafileHeaderExtension1_header_1) | يُنشئ مثيلًا جديدًا للفئة [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) class. |
| [EmfMetafileHeaderExtension1(header)](#EmfMetafileHeaderExtension1_header_2) | يُنشئ مثيلًا جديدًا للفئة [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| وصف_emf | string | r/w | يحصل أو يعيّن وصف EMF<br/>            سلسلة Unicode UTF16-LE منتهية بصفر اختيارية بطول ومحتوى عشوائي. <br/>            يتم تحديد موقعها في السجل وعدد الأحرف بواسطة حقلي offDescription <br/>            و nDescription، على التوالي، في EmfHeader. إذا كانت قيمة أي من الحقلين <br/>            صفرًا، لا توجد سلسلة وصف. |
| emf_description_buffer | System.Byte | r/w | يحصل أو يعيّن مخزن وصف EMF<br/>            مصفوفة اختيارية من البايتات تحتوي على سلسلة وصف EMF، والتي <br/>            لا يلزم أن تكون متجاورة مع الجزء الثابت من سجل EmfMetafileHeader. وبالتالي، الحقل في هذا المخزن المسمى "UndefinedSpace" <br/>            اختياري ويجب تجاهله. |
| emf_header | [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) | r/w | يحصل أو يعيّن كائن Header (القسم 2.2.9)، الذي يحتوي على معلومات حول محتوى<br/>            وبنية ملف الميتا. |
| emf_header_extension1 | [EmfHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/) | r/w | يحصل أو يعيّن كائن HeaderExtension1، الذي يحدد معلومات إضافية حول الصورة في ملف الميتا. |
| emf_header_record_buffer | System.Byte | r/w | يحصل أو يعيّن مصفوفة اختيارية من البايتات تحتوي على باقي سجل رأس EMF. <br/>            يجب أن يكون حجم هذا الحقل مضاعفًا ل 4 بايتات. |
| emf_pixel_format_buffer | System.Byte | r/w | يحصل أو يعيّن مصفوفة اختيارية من البايتات تحتوي على موصّف تنسيق بكسل EMF، والتي لا يلزم أن تكون متجاورة مع الجزء الثابت من سجل EmfMetafileHeaderExtension1 أو مع سلسلة وصف EMF. وبالتالي، الحقل في هذا المخزن المسمى "UndefinedSpace" <br/>            اختياري ويجب تجاهله. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_header(header)](#create_from_header_header_1) | يُنشئ مثيلًا جديدًا للفئة [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) class. |
| [create_from_header_extension1(header)](#create_from_header_extension1_header_2) | يُنشئ مثيلًا جديدًا للفئة [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) class. |
| [create_from_record(record)](#create_from_record_record_3) | ينشئ مثيلًا جديدًا من الفئة [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
| [create_from_type(type)](#create_from_type_type_4) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfMetafileHeaderExtension1(header) {#EmfMetafileHeaderExtension1_header_1}


```
 EmfMetafileHeaderExtension1(header) 
```

يُنشئ مثيلًا جديدًا للفئة [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) class.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | الرأس. |

### Constructor: EmfMetafileHeaderExtension1(header) {#EmfMetafileHeaderExtension1_header_2}


```
 EmfMetafileHeaderExtension1(header) 
```

يُنشئ مثيلًا جديدًا للفئة [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) class.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) | الرأس. |

### Method: create_from_header(header)  [static] {#create_from_header_header_1}


```
 create_from_header(header) 
```

يُنشئ مثيلًا جديدًا للفئة [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) class.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | الرأس. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) |  |


### Method: create_from_header_extension1(header)  [static] {#create_from_header_extension1_header_2}


```
 create_from_header_extension1(header) 
```

يُنشئ مثيلًا جديدًا للفئة [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) class.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) | الرأس. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) |  |


### Method: create_from_record(record)  [static] {#create_from_record_record_3}


```
 create_from_record(record) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | السجل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_4}


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


