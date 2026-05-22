---
title: "EmfCreateBrushIndirect 类"
type: docs
weight: 260
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/
---

**Summary:** The EMR_CREATEBRUSHINDIRECT record defines a logical brush for graphics operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateBrushIndirect

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfCreateBrushIndirect()](#EmfCreateBrushIndirect__1) | 初始化 [EmfCreateBrushIndirect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/) 类的新实例。 |
| [EmfCreateBrushIndirect(source)](#EmfCreateBrushIndirect_source_2) | 初始化 [EmfCreateBrushIndirect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| ih_brush | int | r/w | 获取或设置一个 32 位无符号整数，指定逻辑画笔对象在 EMF 对象表（第 3.1.1.1 节）中的索引<br/>            。必须保存此索引，以便能够<br/>            重新使用或修改该对象。 |
| log_brush | [EmfLogBrushEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/) | r/w | 获取或设置一个 LogBrushEx 对象（第 2.2.12 节），指定逻辑画笔的样式、颜色和<br/>            图案。此对象中的 BrushStyle 字段必须为 BS_SOLID、BS_HATCHED 或 BS_NULL。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfCreateBrushIndirect() {#EmfCreateBrushIndirect__1}


```
 EmfCreateBrushIndirect() 
```

初始化 [EmfCreateBrushIndirect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/) 类的新实例。

### Constructor: EmfCreateBrushIndirect(source) {#EmfCreateBrushIndirect_source_2}


```
 EmfCreateBrushIndirect(source) 
```

初始化 [EmfCreateBrushIndirect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/) 类的新实例。

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


