---
title: "EmfGradientFill 类"
type: docs
weight: 560
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfgradientfill/
---

**Summary:** The EMR_GRADIENTFILL record specifies filling rectangles or triangles with gradients of color.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfGradientFill

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfGradientFill(source)](#EmfGradientFill_source_1) | 初始化 [EmfGradientFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfgradientfill/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），指定一个 <br/>            包含-包含设备单位的边界矩形。 |
| n_tri | int | r/w | 获取或设置 32 位无符号整数，指定要填充的矩形或三角形的数量。 |
| n_ver | int | r/w | 获取或设置 32 位无符号整数，指定顶点的数量。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
| ul_mode | [EmfGradientFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgradientfill/) | r/w | 获取或设置 32 位无符号整数，指定渐变填充模式。该值 <br/>            必须位于 GradientFill 枚举中（第 2.1.15 节）。 |
| vertex_data | [EmfVertexData](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfvertexdata/) | r/w | 获取或设置对象，指定矩形或三角形的顶点以及 <br/>            与之对应的颜色。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfGradientFill(source) {#EmfGradientFill_source_1}


```
 EmfGradientFill(source) 
```

初始化 [EmfGradientFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfgradientfill/) 类的新实例。

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


