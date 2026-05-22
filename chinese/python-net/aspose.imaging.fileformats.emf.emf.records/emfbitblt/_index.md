---
title: "EmfBitBlt 类"
type: docs
weight: 70
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfbitblt/
---

**Summary:** The EMR_BITBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            rectangle, optionally in combination with a brush pattern, according to a specified raster operation.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfBitBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfBitBlt(source)](#EmfBitBlt_source_1) | 初始化 [EmfBitBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfbitblt/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bit_blt_raster_operation | [WmfTernaryRasterOperation](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfternaryrasteroperation/) | r/w | 获取或设置一个 32 位无符号整数，指定光栅操作<br/>            代码。此代码定义如何将源矩形的颜色数据与<br/>            目标矩形的颜色数据以及可选的画笔图案组合，以获得最终颜色。 |
| bk_src_argb_32_color | int | r/w | 获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），用于指定<br/>            源位图的背景颜色。 |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象定义<br/>            目标在设备单位中的边界矩形。 |
| cx_dest | int | r/w | 获取或设置一个 32 位有符号整数，指定源矩形和<br/>            目标矩形的逻辑宽度。 |
| cy_dest | int | r/w | 获取或设置一个 32 位有符号整数，指定源矩形和<br/>            目标矩形的逻辑高度。 |
| size | int | r/w | 获取或设置记录的大小 |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | 获取或设置包含源位图的缓冲区，该缓冲区不需要 <br/>            与 EMR_BITBLT 记录的固定部分连续。因此，此缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | 获取或设置一个 32 位无符号整数，用于指定如何解释源位图头部颜色表中的值<br/>            。该值必须属于 DIBColors 枚举（第 2.1.9 节）。 |
| x_dest | int | r/w | 获取或设置一个 32 位有符号整数，指定逻辑 x 坐标 <br/>            目标矩形左上角。 |
| x_src | int | r/w | 获取或设置一个 32 位有符号整数，指定逻辑 x 坐标 <br/>            源矩形左上角。 |
| xform_src | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | 获取或设置一个 XForm 对象（第 2.2.28 节），指定要应用于源位图的世界空间到页面空间的变换。 |
| y_dest | int | r/w | 获取或设置一个 32 位有符号整数，指定逻辑 y 坐标 <br/>            目标矩形左上角。 |
| y_src | int | r/w | 获取或设置一个 32 位有符号整数，指定逻辑 y 坐标 <br/>            源矩形左上角。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfBitBlt(source) {#EmfBitBlt_source_1}


```
 EmfBitBlt(source) 
```

初始化 [EmfBitBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfbitblt/) 类的新实例。

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


