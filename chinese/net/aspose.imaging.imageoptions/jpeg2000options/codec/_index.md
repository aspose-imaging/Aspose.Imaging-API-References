---
title: "Jpeg2000Options.Codec"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Jpeg2000Options 属性。获取或设置 JPEG2000 编解码器"
type: docs
weight: 20
url: /zh/net/aspose.imaging.imageoptions/jpeg2000options/codec/
---
## Jpeg2000Options.Codec property

获取或设置 JPEG2000 编解码器

```csharp
public Jpeg2000Codec Codec { get; set; }
```

### Property Value

JPEG2000 编解码器

## 示例

此示例展示了如何创建 PNG 图像并使用所需选项将其保存为 JPEG2000。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100x100 像素的 PNG 图像。
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // 将整幅图像填充为红色。
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.Jpeg2000Options saveOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

    // 使用不可逆离散小波变换 9-7
    saveOptions.Irreversible = true;

    // JP2 是 JPEG 2000 码流的“容器”格式。
    // J2K 是未包装的原始压缩数据。
    saveOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

    // 保存到文件
    pngImage.Save(dir + "output.j2k", saveOptions);
}
```

此示例展示了如何创建具有所需选项的 JPEG2000 图像并将其保存到文件。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.Jpeg2000Options createOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

// 使用不可逆离散小波变换 9-7
createOptions.Irreversible = true;

// JP2 是 JPEG 2000 码流的“容器”格式。
// J2K 是未包装的原始压缩数据。
createOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

// 创建 100x100 像素的 JPEG2000 图像。
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

    // 将整幅图像填充为红色。
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

    // 保存到文件
    jpeg2000Image.Save(dir + "sample.output.j2k");
}
```

### 另请参见

* enum [Jpeg2000Codec](../../../aspose.imaging.fileformats.jpeg2000/jpeg2000codec/)
* class [Jpeg2000Options](../)
* namespace [Aspose.Imaging.ImageOptions](../../jpeg2000options/)
* assembly [Aspose.Imaging](../../../)


