---
title: "EmfCreateDibPatternBrushPt 类"
type: docs
weight: 290
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/
---

**Summary:** The EMR_CREATEDIBPATTERNBRUSHPT record defines a pattern brush for graphics operations. The<br/>            pattern is specified by a DIB.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateDibPatternBrushPt

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfCreateDibPatternBrushPt()](#EmfCreateDibPatternBrushPt__1) | 初始化 [EmfCreateDibPatternBrushPt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/) 类的新实例。 |
| [EmfCreateDibPatternBrushPt(source)](#EmfCreateDibPatternBrushPt_source_2) | 初始化 [EmfCreateDibPatternBrushPt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bitmap_buffer | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | 获取或设置包含打包 DIB 的缓冲区，形式为 WMF<br/>            DeviceIndependentBitmap 对象（[MS-WMF] 第 2.2.2.9 节）。它不需要与 EMR_CREATEDIBPATTERNBRUSHPT 记录的固定部分连续。 |
| ih_brush | int | r/w | 获取或设置 32 位无符号整数，指定模式刷对象在 EMF 对象表中的索引<br/>            （第 3.1.1.1 节）。必须保存此索引，以便可以重用或修改此对象。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
| usage | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | 获取或设置一个 32 位无符号整数，指定如何解释 DIB 标头中颜色<br/>            表的值。此值必须位于 DIBColors 枚举中（第 2.1.9 节）。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfCreateDibPatternBrushPt() {#EmfCreateDibPatternBrushPt__1}


```
 EmfCreateDibPatternBrushPt() 
```

初始化 [EmfCreateDibPatternBrushPt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/) 类的新实例。

### Constructor: EmfCreateDibPatternBrushPt(source) {#EmfCreateDibPatternBrushPt_source_2}


```
 EmfCreateDibPatternBrushPt(source) 
```

初始化 [EmfCreateDibPatternBrushPt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/) 类的新实例。

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


