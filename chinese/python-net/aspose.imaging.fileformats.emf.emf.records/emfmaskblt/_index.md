---
title: "EmfMaskBlt 类"
type: docs
weight: 600
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---

**Summary:** The EMR_MASKBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            rectangle, optionally in combination with a brush pattern and with the application of a color mask <br/>            bitmap, according to specified foreground and background raster operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMaskBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfMaskBlt(source)](#EmfMaskBlt_source_1) | 初始化 [EmfMaskBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| argb_32_bk_color_src | int | r/w | 获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），它指定源位图的<br/>背景颜色。 |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象定义<br/>            目标在设备单位中的边界矩形。 |
| cx_dest | int | r/w | 获取或设置一个 32 位有符号整数，指定目标矩形的逻辑宽度。 |
| cy_dest | int | r/w | 获取或设置一个 32 位有符号整数，指定目标矩形的逻辑高度。 |
| mask_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | 获取或设置一个包含掩码位图的缓冲区，这些位图不<br/>            需要与 EMR_MASKBLT 记录的固定部分或彼此连续。因此，此缓冲区中标记为 "UndefinedSpace" 的字段是可选的，且<br/>            必须被忽略。 |
| rop4 | [EmfRop4](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/) | r/w | 获取或设置一个四元光栅操作，指定位图前景色和背景色的三元光栅操作。<br/>            这些值定义了如何将源矩形的颜色数据与目标矩形的颜色数据组合。 |
| size | int | r/w | 获取或设置记录的大小 |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | 获取或设置一个包含源位图的缓冲区，这些位图不<br/>            需要与 EMR_MASKBLT 记录的固定部分或彼此连续。因此，此缓冲区中标记为 "UndefinedSpace" 的字段是可选的，且<br/>            必须被忽略。 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
| usage_mask | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | 获取或设置一个 32 位无符号整数，指定如何解释掩码位图头部颜色表中的值。<br/>            此值必须属于 DIBColors 枚举。 |
| usage_src | int | r/w | 获取或设置一个 32 位无符号整数，用于指定如何解释源位图头部颜色表中的值<br/>            。该值必须属于 DIBColors 枚举（第 2.1.9 节）。 |
| x_dest | int | r/w | 获取或设置一个 32 位有符号整数，指定逻辑 x 坐标 <br/>            目标矩形左上角。 |
| x_mask | int | r/w | 获取或设置一个 32 位有符号整数，指定掩码位图左上角的逻辑 x 坐标。 |
| x_src | int | r/w | 获取或设置一个 32 位有符号整数，指定逻辑 x 坐标 <br/>            源矩形左上角。 |
| xform_src | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | 获取或设置一个 XForm 对象（第 2.2.28 节），指定要应用于源位图的世界空间到页面空间的变换。 |
| y_dest | int | r/w | 获取或设置一个 32 位有符号整数，指定逻辑 y 坐标 <br/>            目标矩形左上角。 |
| y_mask | int | r/w | 获取或设置一个 32 位有符号整数，指定掩码位图左上角的逻辑 y 坐标。 |
| y_src | int | r/w | 获取或设置一个 32 位有符号整数，指定逻辑 y 坐标 <br/>            源矩形左上角。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfMaskBlt(source) {#EmfMaskBlt_source_1}


```
 EmfMaskBlt(source) 
```

初始化 [EmfMaskBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/) 类的新实例。

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


