---
title: "EmfPlusBitmap 类"
type: docs
weight: 50
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/
---

**Summary:** The EmfPlusBitmap object specifies a bitmap that contains a graphics image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBitmap

**Inheritance:** EmfPlusBaseImageData

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusBitmap()](#EmfPlusBitmap__1) | 初始化 EmfPlusBitmap 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bitmap_data | [EmfPlusBaseBitmapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata/) | r/w | 获取或设置位图数据<br/>            BitmapData（可变）：可变长度数据，定义在 Type 字段中指定的位图数据对象。<br/>            数据的内容和格式可能因不同的位图类型而异。 |
| height | int | r/w | 获取或设置位图高度<br/>            Height（4 字节）：一个 32 位有符号整数，指定位图占用区域的像素高度。<br/>            如果图像已压缩，根据 Type 字段，此值未定义，必须忽略。 |
| pixel_format | [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) | r/w | 获取或设置像素格式<br/>            PixelFormat（4 字节）：一个 32 位无符号整数，指定构成位图图像的像素格式。支持的像素格式在 [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) 枚举（第 2.1.1.25 节）中列出。<br/>            如果图像已压缩，根据 Type 字段，此值未定义，必须忽略。 |
| 步幅 | int | r/w | 获取或设置图像的步幅<br/>            Stride（4 字节）：一个 32 位有符号整数，指定一条扫描线起始位置与下一条扫描线之间的字节偏移量。该值等于像素格式字段中指定的每像素字节数乘以宽度字段中指定的像素宽度。此字段的值必须是四的倍数。<br/>            如果图像已压缩，根据 Type 字段，此值未定义，必须忽略。 |
| type | [EmfPlusBitmapDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbitmapdatatype/) | r/w | 获取或设置图像类型<br/>            Type（4 字节）：一个 32 位无符号整数，指定 BitmapData 字段中数据的类型。此值必须在 [EmfPlusBitmapDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbitmapdatatype/) 枚举（第 2.1.1.2 节）中定义。 |
| width | int | r/w | 获取或设置图像宽度<br/>            Width（4 字节）：一个 32 位有符号整数，指定位图占用区域的像素宽度。<br/>            如果图像已压缩，根据 Type 字段，此值未定义，必须忽略。 |


### Constructor: EmfPlusBitmap() {#EmfPlusBitmap__1}


```
 EmfPlusBitmap() 
```

初始化 EmfPlusBitmap 类的新实例

