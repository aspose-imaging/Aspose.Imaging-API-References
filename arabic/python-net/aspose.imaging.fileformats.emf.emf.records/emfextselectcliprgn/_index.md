---
title: "فئة EmfExtSelectClipRgn"
type: docs
weight: 460
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/
---

**Summary:** The EMR_EXTSELECTCLIPRGN record combines the specified region with the current clip region <br/>            using the specified mode. <br/>            Note  Fields that are not described in this section are specified in section 2.3.2.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtSelectClipRgn

**Inheritance:** EmfClippingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfExtSelectClipRgn()](#EmfExtSelectClipRgn__1) | يُنشئ مثيلاً جديدًا من الفئة [EmfExtSelectClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/). |
| [EmfExtSelectClipRgn(source)](#EmfExtSelectClipRgn_source_2) | يُنشئ مثيلاً جديدًا من الفئة [EmfExtSelectClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| region_mode | [EmfRegionMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfregionmode/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد طريقة استخدام المنطقة. يجب أن تكون القيمة <br/>            ضمن تعداد RegionMode (القسم 2.1.29). |
| rgn_data | [EmfRegionData](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondata/) | r/w | يحصل أو يعيّن مصفوفة بايت بطول RgnDataSize تحدد كائن RegionData <br/>            بوحدات منطقية. إذا كان RegionMode هو RGN_COPY، يمكن حذف هذه البيانات ويجب <br/>            ضبط منطقة القص إلى المنطقة الافتراضية (NULL). |
| rgn_data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد حجم بيانات المنطقة بالبايت. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfExtSelectClipRgn() {#EmfExtSelectClipRgn__1}


```
 EmfExtSelectClipRgn() 
```

يُنشئ مثيلاً جديدًا من الفئة [EmfExtSelectClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/).

### Constructor: EmfExtSelectClipRgn(source) {#EmfExtSelectClipRgn_source_2}


```
 EmfExtSelectClipRgn(source) 
```

يُنشئ مثيلاً جديدًا من الفئة [EmfExtSelectClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/).

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


