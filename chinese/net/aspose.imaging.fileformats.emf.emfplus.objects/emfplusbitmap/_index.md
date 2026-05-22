---
title: "类 EmfPlusBitmap"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusBitmap 类。EmfPlusBitmap 对象指定包含图形图像的位图。"
type: docs
weight: 5290
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/
---
## EmfPlusBitmap class

EmfPlusBitmap 对象指定了包含图形图像的位图。

```csharp
public sealed class EmfPlusBitmap : EmfPlusBaseImageData
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusBitmap](emfplusbitmap/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BitmapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/bitmapdata/) { get; set; } | 获取或设置位图数据 BitmapData（可变）：可变长度数据，定义 Type 字段中指定的位图数据对象。该数据的内容和格式可能因位图类型而异。 |
| [Height](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/height/) { get; set; } | 获取或设置位图高度 Height（4 字节）：一个 32 位有符号整数，指定位图占用区域的像素高度。如果图像根据 Type 字段被压缩，则此值未定义，必须忽略。 |
| [PixelFormat](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/pixelformat/) { get; set; } | 获取或设置像素格式 PixelFormat（4 字节）：一个 32 位无符号整数，指定构成位图图像的像素格式。支持的像素格式在 [`EmfPlusPixelFormat`](../../aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) 枚举（章节 2.1.1.25）中指定。如果图像根据 Type 字段被压缩，则此值未定义，必须忽略。 |
| [Stride](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/stride/) { get; set; } | 获取或设置图像的步幅 Stride（4 字节）：一个 32 位有符号整数，指定从一条扫描线的起始位置到下一条扫描线的字节偏移量。该值等于像素格式字段中指定的每像素字节数乘以宽度字段中指定的像素宽度。此字段的值必须是四的倍数。如果图像已压缩（根据 Type 字段），此值未定义，必须被忽略。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/type/) { get; set; } | 获取或设置图像的类型 Type（4 字节）：一个 32 位无符号整数，指定 BitmapData 字段中数据的类型。此值必须在 [`EmfPlusBitmapDataType`](../../aspose.imaging.fileformats.emf.emfplus.consts/emfplusbitmapdatatype/) 枚举中定义（第 2.1.1.2 节）。 |
| [Width](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/width/) { get; set; } | 获取或设置图像宽度 Width（4 字节）：一个 32 位有符号整数，指定位图占用区域的像素宽度。如果图像已压缩（根据 Type 字段），此值未定义，必须被忽略。 |

### 另请参见

* class [EmfPlusBaseImageData](../emfplusbaseimagedata/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


