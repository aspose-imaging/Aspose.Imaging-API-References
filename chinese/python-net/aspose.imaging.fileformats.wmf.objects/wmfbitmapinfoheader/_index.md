---
title: "WmfBitmapInfoHeader 类"
type: docs
weight: 70
url: /zh/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---

**Summary:** The BitmapInfoHeader Object contains information about the dimensions and color format of a device-independent<br/>                bitmap (DIB).

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfBitmapInfoHeader

**Inheritance:** WmfBitmapBaseHeader

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [WmfBitmapInfoHeader()](#WmfBitmapInfoHeader__1) | 初始化 WmfBitmapInfoHeader 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| STRUCTURE_SIZE [static] | int | r | 结构大小 |
| bit_count | [DibBitCount](/imaging/python-net/aspose.imaging.apsbuilder.dib/dibbitcount/) | r/w | 获取或设置一个 16 位无符号整数，定义每个像素的格式<br/>                以及 DIB 中的最大颜色数。此值<br/>                必须位于 [WmfBitmapBaseHeader.bit_count](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) 枚举中（第 2.1.1.3 节）。 |
| color_important | int | r/w | 获取或设置一个 32 位无符号整数，定义显示 DIB 所需的颜色索引数量<br/>                DIB。<br/>                如果此值为零，则需要所有颜色索引 |
| color_used | int | r/w | 获取或设置一个 32 位无符号整数，指定 DIB 使用的颜色表中的索引数量，如下：<br/>                如果此值为零，DIB 使用与 BitCount 值对应的最大颜色数。<br/>                如果此值非零且 BitCount 值小于 16，则此值指定 DIB 使用的颜色数量。<br/>                如果此值非零且 BitCount 值为 16 或更大，则此值指定用于优化系统调色板性能的颜色表大小。<br/>                注意：如果此值非零且大于基于 BitCount 值的颜色表可能的最大大小，则应假定最大颜色表大小。 |
| compression | [WmfCompression](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfcompression/) | r/w | 获取或设置一个 32 位无符号整数，定义 DIB 的压缩模式。此值必须位于<br/>                Compression 枚举（第 2.1.1.7 节）中。<br/>                如果 DIB 是自上而下的位图（由 Height 值指示），则此值不得指定压缩格式。 |
| header_size | int | r/w | 获取或设置一个 32 位无符号整数，定义此<br/>                对象的大小（字节）。 |
| height | int | r/w | 获取或设置一个 32 位有符号整数，定义 DIB 的高度（像素）。此值不得为零。<br/>                如果此值为正，DIB 为自下而上的位图，原点位于左下角。<br/>                如果此值为负，DIB 为自上而下的位图，原点位于左上角。自上而下的位图<br/>                不支持压缩。<br/>                如果 Compression 值指定 JPEG 或 PNG 格式，则此字段应指定解压后图像文件的高度。 |
| image_size | int | r/w | 获取或设置一个 32 位无符号整数，定义图像的大小（字节）。<br/>                如果 Compression 值为 BI_RGB，则此值应为零并且必须被忽略。<br/>                如果 Compression 值为 BI_JPEG 或 BI_PNG，则此值必须分别指定 JPEG 或 PNG 图像缓冲区的大小。 |
| planes | int | r/w | 获取或设置一个 16 位无符号整数，定义目标设备的<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) 数量。此值必须为<br/>                0x0001。 |
| width | int | r/w | 获取或设置一个 32 位有符号整数，定义 DIB 的宽度（像素）。此值必须为正。<br/>                如果 Compression 值指定 JPEG 或 PNG 格式，则此字段应指定解压后图像文件的宽度。 |
| x_pels_per_meter | int | r/w | 获取或设置一个 32 位有符号整数，定义目标设备对 DIB 的水平分辨率（像素/米） |
| y_pels_per_meter | int | r/w | 获取或设置一个 32 位有符号整数，定义目标设备对 DIB 的垂直分辨率（像素/米） |


### Constructor: WmfBitmapInfoHeader() {#WmfBitmapInfoHeader__1}


```
 WmfBitmapInfoHeader() 
```

初始化 WmfBitmapInfoHeader 类的新实例

