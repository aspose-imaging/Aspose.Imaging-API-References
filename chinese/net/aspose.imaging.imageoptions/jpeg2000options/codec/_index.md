---
title: Codec
second_title: Aspose.Imaging for .NET API 参考
description: 获取或设置 JPEG2000 编解码器
type: docs
weight: 20
url: /zh/net/aspose.imaging.imageoptions/jpeg2000options/codec/
---
## Jpeg2000Options.Codec property

获取或设置 JPEG2000 编解码器

```csharp
public Jpeg2000Codec Codec { get; set; }
```

### 适当的价值

JPEG2000 编解码器

### 例子

此示例说明如何创建 PNG 图像并将其保存到 JPEG2000 并使用所需的选项。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.Jpeg2000Options createOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

    // 使用不可逆离散小波变换 9-7
createOptions.Irreversible = true;

    // JP2 是 JPEG 2000 码流的“容器”格式。
    // J2K 是原始压缩数据，没有包装器。
createOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

    // 创建一个 100x100 像素的 JPEG2000 图像。
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

        // 用红色填充整个图像。
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

        // 保存到文件
    jpeg2000Image.Save(dir + "sample.output.j2k");
}
```

此示例说明如何使用所需选项创建 JPEG2000 图像并将其保存到文件中。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.Jpeg2000Options createOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

    // 使用不可逆离散小波变换 9-7
createOptions.Irreversible = true;

    // JP2 是 JPEG 2000 码流的“容器”格式。
    // J2K 是原始压缩数据，没有包装器。
createOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

    // 创建一个 100x100 像素的 JPEG2000 图像。
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

        // 用红色填充整个图像。
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

        // 保存到文件
    jpeg2000Image.Save(dir + "sample.output.j2k");
}
```

### 也可以看看

* enum [Jpeg2000Codec](../../../aspose.imaging.fileformats.jpeg2000/jpeg2000codec)
* class [Jpeg2000Options](../../jpeg2000options)
* 命名空间 [Aspose.Imaging.ImageOptions](../../jpeg2000options)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->