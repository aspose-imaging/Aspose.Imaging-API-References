---
title: "EmfExcludeClipRect 类"
type: docs
weight: 410
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/
---

**Summary:** The EMR_EXCLUDECLIPRECT record specifies a new clipping region that consists of the existing <br/>            clipping region minus the specified rectangle. <br/>            Note  Fields that are not described in this section are specified in section 2.3.2.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExcludeClipRect

**Inheritance:** EmfClippingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfExcludeClipRect()](#EmfExcludeClipRect__1) | 初始化 [EmfExcludeClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/) 类的新实例。 |
| [EmfExcludeClipRect(source)](#EmfExcludeClipRect_source_2) | 初始化 [EmfExcludeClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| clip | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），指定以逻辑单位表示的剪裁<br/>            矩形。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfExcludeClipRect() {#EmfExcludeClipRect__1}


```
 EmfExcludeClipRect() 
```

初始化 [EmfExcludeClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/) 类的新实例。

### Constructor: EmfExcludeClipRect(source) {#EmfExcludeClipRect_source_2}


```
 EmfExcludeClipRect(source) 
```

初始化 [EmfExcludeClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | 来源。 |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | 来源。 |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | 记录类型。 |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


