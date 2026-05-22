---
title: "EmfRectangle 类"
type: docs
weight: 980
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfrectangle/
---

**Summary:** The EMR_RECTANGLE record draws a rectangle. The rectangle is outlined by using the current pen<br/>            and filled by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfRectangle

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfRectangle()](#EmfRectangle__1) | 初始化一个新的 [EmfRectangle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrectangle/) 类实例。 |
| [EmfRectangle(source)](#EmfRectangle_source_2) | 初始化一个新的 [EmfRectangle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrectangle/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置一个128位 WMF RectL 对象，指定于 [MS-WMF] 第 2.2.2.19 节，<br/>            指定要绘制的包含-包含矩形。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfRectangle() {#EmfRectangle__1}


```
 EmfRectangle() 
```

初始化一个新的 [EmfRectangle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrectangle/) 类实例。

### Constructor: EmfRectangle(source) {#EmfRectangle_source_2}


```
 EmfRectangle(source) 
```

初始化一个新的 [EmfRectangle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrectangle/) 类实例。

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


