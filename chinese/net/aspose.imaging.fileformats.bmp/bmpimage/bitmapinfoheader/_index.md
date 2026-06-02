---
title: "BmpImage.BitmapInfoHeader"
second_title: "Aspose.Imaging for .NET API 参考"
description: "BmpImage 属性。使用此简洁函数可快速访问位图图像的关键细节。非常适合需要检索图像头信息的开发者。"
type: docs
weight: 20
url: /zh/net/aspose.imaging.fileformats.bmp/bmpimage/bitmapinfoheader/
---
## BmpImage.BitmapInfoHeader property

使用此简洁函数快速获取位图图像的关键细节。非常适合需要检索图像头信息的开发人员。

```csharp
public BitmapInfoHeader BitmapInfoHeader { get; }
```

### Property Value

位图信息头。

## 示例

以下示例从 BMP 标头获取信息并将其打印到控制台。

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
    Aspose.Imaging.FileFormats.Bmp.BitmapInfoHeader header = bmpImage.BitmapInfoHeader;

    System.Console.WriteLine("The number of palette colors that are required for displaying the bitmap: {0}", header.BitmapColorsImportant);
    System.Console.WriteLine("The number of palette colors used in the bitmap: {0}", header.BitmapColorsUsed);
    System.Console.WriteLine("The bitmap compression: {0}", header.BitmapCompression);
    System.Console.WriteLine("The bitmap height: {0}", header.BitmapHeight);
    System.Console.WriteLine("The bitmap width: {0}", header.BitmapWidth);
    System.Console.WriteLine("The bitmap raw data size in bytes: {0}", header.BitmapImageSize);
    System.Console.WriteLine("The number of planes: {0}", header.BitmapPlanes);
    System.Console.WriteLine("The horizontal resolution of the bitmap, in pixels-per-meter: {0}", header.BitmapXPelsPerMeter);
    System.Console.WriteLine("The vertical resolution of the bitmap, in pixels-per-meter: {0}", header.BitmapYPelsPerMeter);
    System.Console.WriteLine("The number of bits per pixel: {0}", header.BitsPerPixel);
    System.Console.WriteLine("The extra bits masks: {0}", header.ExtraBitMasks);
    System.Console.WriteLine("The header size in bytes: {0}", header.HeaderSize);
}

//输出可能如下所示：
//显示位图所需的调色板颜色数量：0
//位图中使用的调色板颜色数量：0
//位图压缩方式：0
//位图高度：375
//位图宽度：500
//位图原始数据大小（字节）：562500
//平面数量：1
//位图的水平分辨率（像素/米）：0
//位图的垂直分辨率（像素/米）：0
//每像素位数：24
//额外位掩码：
//标头大小（字节）：40
```

### 另请参见

* class [BitmapInfoHeader](../../bitmapinfoheader/)
* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)


