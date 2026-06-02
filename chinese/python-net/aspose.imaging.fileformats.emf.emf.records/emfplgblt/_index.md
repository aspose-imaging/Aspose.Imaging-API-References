---
title: "EmfPlgBlt 类"
type: docs
weight: 750
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---

**Summary:** The EMR_PLGBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            parallelogram, with the application of a color mask bitmap.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPlgBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlgBlt(source)](#EmfPlgBlt_source_1) | 初始化一个新的 [EmfPlgBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| aptl_dest | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | 获取或设置一个包含三个 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节）的数组，<br/>            指定块传输的平行四边形目标区域的三个角。<br/>            源矩形的左上角映射到该数组的第一个点，<br/>            右上角映射到第二个点，左下角映射到第三个点。源矩形的右下角映射到平行四边形中隐含的第四点，<br/>            该点通过将前三个点（A、B 和 C）视为向量来计算。<br/>            D = B + C A |
| bk_src_argb_32_color | int | r/w | 获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.8 节），该对象指定源位图的<br/>            背景颜色。 |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象定义了输出到目标的<br/>            边界矩形（设备单位）。 |
| cx_src | int | r/w | 获取或设置一个 32 位有符号整数，指定源矩形的逻辑宽度。 |
| cy_src | int | r/w | 获取或设置一个 32 位有符号整数，指定源矩形的逻辑高度。 |
| mask_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | 获取或设置一个包含掩码位图的缓冲区，该缓冲区不需要与 EMR_PLGBLT 记录的固定部分或彼此连续。<br/>            相应地，此缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。 |
| size | int | r/w | 获取或设置记录的大小 |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | 获取或设置一个包含源位图的缓冲区，该缓冲区不需要与 EMR_PLGBLT 记录的固定部分或彼此连续。<br/>            相应地，此缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
| usage_mask | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | 获取或设置一个 32 位无符号整数，指定如何解释掩码位图头部颜色表中的值。<br/>            此值必须属于 DIBColors 枚举。 |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | 获取或设置一个 32 位无符号整数，指定如何解释源位图头部中的颜色表值。<br/>            此值必须属于 DIBColors 枚举。 |
| x_form_src | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | 获取或设置一个 XForm 对象（第 2.2.28 节），指定要应用于源位图的世界空间到页面空间的变换。 |
| x_mask | int | r/w | 获取或设置一个 32 位有符号整数，指定掩码位图左上角的逻辑 x 坐标。 |
| x_src | int | r/w | 获取或设置一个 32 位有符号整数，指定逻辑 x 坐标 <br/>            源矩形左上角。 |
| y_mask | int | r/w | 获取或设置一个 32 位有符号整数，指定掩码位图左上角的逻辑 y 坐标。 |
| y_src | int | r/w | 获取或设置一个 32 位有符号整数，指定逻辑 y 坐标 <br/>            源矩形左上角。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfPlgBlt(source) {#EmfPlgBlt_source_1}


```
 EmfPlgBlt(source) 
```

初始化一个新的 [EmfPlgBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/) 类的实例。

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


