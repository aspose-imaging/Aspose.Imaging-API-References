---
title: "EmfPolyTextOutW 类"
type: docs
weight: 890
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/
---

**Summary:** The EMR_POLYTEXTOUTW record draws one or more Unicode text strings using the current font and text colors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyTextOutW

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPolyTextOutW()](#EmfPolyTextOutW__1) | 初始化 [EmfPolyTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/) 类的新实例。 |
| [EmfPolyTextOutW(source)](#EmfPolyTextOutW_source_2) | 初始化 [EmfPolyTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），用于指定 <br/> 设备单位中的边界矩形。 |
| ex_scale | float | r/w | 获取或设置一个 32 位浮点值，指定在图形模式为 GM_COMPATIBLE 时，从页面单位到 <br/> .01mm 单位的 X 缩放比例。 |
| ey_scale | float | r/w | 获取或设置一个 32 位浮点值，指定在图形模式为 GM_COMPATIBLE 时，从页面单位到 <br/> .01mm 单位的 Y 缩放比例。 |
| graphics_mode | [EmfGraphicsMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/) | r/w | 获取或设置一个 32 位无符号整数，指定当前的图形模式，<br/> 来自 GraphicsMode 枚举（第 2.1.16 节）。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
| w_emr_text | [EmfText[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emftext/) | r/w | 获取或设置一个 EmrText 对象数组（第 2.2.5 节），该数组指定以 16 位 Unicode UTF16-LE 字符表示的输出 <br/>            字符串，以及文本属性和间距值。<br/>            EmrText 对象的数量由 cStrings 指定。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfPolyTextOutW() {#EmfPolyTextOutW__1}


```
 EmfPolyTextOutW() 
```

初始化 [EmfPolyTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/) 类的新实例。

### Constructor: EmfPolyTextOutW(source) {#EmfPolyTextOutW_source_2}


```
 EmfPolyTextOutW(source) 
```

初始化 [EmfPolyTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/) 类的新实例。

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


