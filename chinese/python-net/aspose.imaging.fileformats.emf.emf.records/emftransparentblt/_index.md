---
title: "EmfTransparentBlt 类"
type: docs
weight: 1450
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emftransparentblt/
---

**Summary:** The EMR_TRANSPARENTBLT record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, treating a specified color as transparent, stretching or compressing the output <br/>            to fit the dimensions of the destination, if necessary

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfTransparentBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfTransparentBlt(source)](#EmfTransparentBlt_source_1) | 初始化一个新的 [EmfTransparentBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emftransparentblt/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象定义<br/>            目标在设备单位中的边界矩形。 |
| cx_dest | int | r/w | 获取或设置一个 32 位有符号整数，指定目标矩形的逻辑宽度。 |
| cx_src | int | r/w | 获取或设置一个 32 位有符号整数，指定源矩形的逻辑宽度。 |
| cy_dest | int | r/w | 获取或设置一个 32 位有符号整数，指定目标矩形的逻辑高度。 |
| cy_src | int | r/w | 获取或设置一个 32 位有符号整数，指定源矩形的逻辑高度。 |
| size | int | r/w | 获取或设置记录的大小 |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | 获取或设置一个包含源位图的缓冲区，该缓冲区不需要与 EMR_TRANSPARENTBLT 记录的固定部分<br/>            连续。因此，此缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。 |
| src_bk_argb_32_color | int | r/w | 获取或设置一个 WMF ColorRef 对象，用于指定源位图的背景颜色。 |
| transparent_argb_32_color | int | r/w | 获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），用于指定<br/>            源位图中应视为透明的颜色。 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | 获取或设置一个 32 位无符号整数，用于指定如何解释源位图头部的 <br/>            颜色表中的值。该值必须位于 DIBColors 枚举中（第 2.1.9 节）。 |
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


### Constructor: EmfTransparentBlt(source) {#EmfTransparentBlt_source_1}


```
 EmfTransparentBlt(source) 
```

初始化一个新的 [EmfTransparentBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emftransparentblt/) 类实例。

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


