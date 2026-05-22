---
title: "EmfSetPixelV 类"
type: docs
weight: 1260
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/
---

**Summary:** The EMR_SETPIXELV record defines the color of the pixel at the specified logical coordinates.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetPixelV

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfSetPixelV()](#EmfSetPixelV__1) | 初始化一个新的 [EmfSetPixelV](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/) 类的实例。 |
| [EmfSetPixelV(source)](#EmfSetPixelV_source_2) | 初始化一个新的 [EmfSetPixelV](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| argb_32_color | int | r/w | 获取或设置一个指定像素颜色的 32 位 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节）。 |
| pixel | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | 获取或设置一个指定像素的 <br/>            逻辑坐标的 64 位 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节）。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfSetPixelV() {#EmfSetPixelV__1}


```
 EmfSetPixelV() 
```

初始化一个新的 [EmfSetPixelV](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/) 类的实例。

### Constructor: EmfSetPixelV(source) {#EmfSetPixelV_source_2}


```
 EmfSetPixelV(source) 
```

初始化一个新的 [EmfSetPixelV](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/) 类的实例。

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


