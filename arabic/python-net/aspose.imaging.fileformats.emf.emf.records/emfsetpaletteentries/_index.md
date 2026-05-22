---
title: "فئة EmfSetPaletteEntries"
type: docs
weight: 1250
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/
---

**Summary:** The EMR_SETPALETTEENTRIES record defines RGB color values in a range of entries for an existing<br/>            LogPalette (section 2.2.17) object.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetPaletteEntries

**Inheritance:** EmfObjectManipulationRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfSetPaletteEntries(source)](#EmfSetPaletteEntries_source_1) | ينشئ مثيلاً جديداً من الفئة [EmfSetPaletteEntries](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| argb_32_pal_entries | int[] | r/w | الحصول أو تعيين مصفوفة من كائنات LogPaletteEntry (section 2.2.18) <br/>            بطول NumberOfEntries، والتي تحدد بيانات مدخلات لوحة الألوان. لا تحتوي أعضاء Values <br/>            على أي قيم. |
| ih_pal | int | r/w | الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد فهرس جدول كائنات EMF للوحة الألوان. |
| numberof_entries | int | r/w | الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد عدد المدخلات. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| بداية | int | r/w | الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد فهرس أول مدخل لتعيينه. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetPaletteEntries(source) {#EmfSetPaletteEntries_source_1}


```
 EmfSetPaletteEntries(source) 
```

ينشئ مثيلاً جديداً من الفئة [EmfSetPaletteEntries](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/)

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


