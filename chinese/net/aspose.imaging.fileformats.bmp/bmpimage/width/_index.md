---
title: "BmpImage.Width"
second_title: "Aspose.Imaging for .NET API 参考"
description: "BmpImage 属性。使用此属性可以轻松获取图像的宽度。非常适合希望快速获取图像尺寸信息的开发者。"
type: docs
weight: 120
url: /zh/net/aspose.imaging.fileformats.bmp/bmpimage/width/
---
## BmpImage.Width property

使用此属性轻松获取图像的宽度。非常适合希望快速获取图像尺寸信息的开发人员。

```csharp
public override int Width { get; }
```

### Property Value

图像宽度。

## 示例

以下示例获取图像的一般信息，包括像素格式、图像尺寸、分辨率、压缩等。

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;                

    System.Console.WriteLine("The pixel format: {0}", bmpImage.RawDataFormat);                
    System.Console.WriteLine("The raw line size in bytes: {0}", bmpImage.RawLineSize);
    System.Console.WriteLine("The bitmap compression: {0}", bmpImage.Compression);
    System.Console.WriteLine("The bitmap width: {0}", bmpImage.Width);
    System.Console.WriteLine("The bitmap height: {0}", bmpImage.Height);
    System.Console.WriteLine("The number of bits per pixel: {0}", bmpImage.BitsPerPixel);

    double hres = bmpImage.HorizontalResolution;
    double vres = bmpImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", hres);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", vres);

    if (hres != 96.0 || vres != 96.0)
    {
        // 您可以考虑使用 SetResolution 方法在一次调用中更新两个分辨率值。
        System.Console.WriteLine("Set resolution values to 96 dpi");
        bmpImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", bmpImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", bmpImage.VerticalResolution);
    }

    //输出可能如下所示：
    //像素格式：Rgb24Bpp，使用的通道：8,8,8
    //原始行大小（字节）：1500
    //位图压缩方式：Rgb
    //位图宽度：500
    //位图高度：375
    //每像素位数：24
    //水平分辨率（每英寸像素数）：0
    //垂直分辨率（每英寸像素数）：0
    //将分辨率值设置为 96 dpi
    //水平分辨率（每英寸像素数）：96.012
    //垂直分辨率（每英寸像素数）：96.012
}
```

以下示例展示了位图压缩如何影响输出图像的大小。

```csharp
[C#]

Aspose.Imaging.FileFormats.Bmp.BitmapCompression[] compressions = new Aspose.Imaging.FileFormats.Bmp.BitmapCompression[]
{
    Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb,
    Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rle8,
};

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// 创建仅包含红色和绿色的单色调色板。
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

foreach (Aspose.Imaging.FileFormats.Bmp.BitmapCompression compression in compressions)
{
    // 创建一个 8 位 BMP 图像，尺寸为 100 x 100 像素。
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 8, palette, compression, 0.0, 0.0))
    {
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

        // 将整幅图像填充为红色。
        Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
        gr.FillRectangle(redBrush, bmpImage.Bounds);

        // 将图像保存到流中以获取输出图像的大小。
        using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
        {
            bmpImage.Save(stream);

            System.Console.WriteLine("---------------------------------------------");
            System.Console.WriteLine("The compression={0}", bmpImage.Compression);
            System.Console.WriteLine("The number of bits per pixel={0}", bmpImage.BitsPerPixel);
            System.Console.WriteLine("The image dimensions={0} x {1}", bmpImage.Width, bmpImage.Height);
            System.Console.WriteLine("The raw line size={0}", bmpImage.RawLineSize);
            System.Console.WriteLine("The output size in bytes={0}", stream.Length);
        }
    }
}

// 输出如下：
// ---------------------------------------------
// 压缩方式 = Rgb
// 每像素位数 = 8
// 图像尺寸 = 100 x 100
// 原始行大小 = 100
// 输出大小（字节） = 11078
// ---------------------------------------------
// 压缩方式 = Rle8
// 每像素位数 = 8
// 图像尺寸 = 100 x 100
// 原始行大小 = 100
// 输出大小（字节） = 856
```

### 另请参见

* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)


