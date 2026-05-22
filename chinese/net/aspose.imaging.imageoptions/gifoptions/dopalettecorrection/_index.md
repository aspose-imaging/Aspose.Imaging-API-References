---
title: "GifOptions.DoPaletteCorrection"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GifOptions 属性。获取或设置指示是否应用调色板校正的值"
type: docs
weight: 50
url: /zh/net/aspose.imaging.imageoptions/gifoptions/dopalettecorrection/
---
## GifOptions.DoPaletteCorrection property

获取或设置指示是否应用调色板校正的值。

```csharp
public bool DoPaletteCorrection { get; set; }
```

### Property Value

`true` 表示已应用调色板校正；否则为 `false`。

## 备注

调色板校正的含义是，每当图像导出为 GIF 时，源图像的颜色将被分析以构建最匹配的调色板（如果图像调色板不存在或在选项中未指定）。分析过程会花费一些时间，但输出图像将拥有最匹配的颜色调色板，视觉效果更佳。

## 示例

此示例展示了如何使用各种选项将 BMP 图像保存为 GIF 格式。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(1000, 1000))
{
    // 用蓝黄渐变填充整幅图像。
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Yellow);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(bmpImage);
    graphics.FillRectangle(gradientBrush, bmpImage.Bounds);

    Aspose.Imaging.ImageOptions.GifOptions saveOptions = new Aspose.Imaging.ImageOptions.GifOptions();

    // 存储一种颜色所需的位数减 1。
    saveOptions.ColorResolution = 7;

    // 调色板校正的含义是，每当图像导出为 GIF 时，源图像的颜色将被分析
    // 为了构建最佳匹配的调色板（如果图像调色板不存在或在选项中未指定）
    saveOptions.DoPaletteCorrection = true;

    // 以渐进方式加载 GIF 图像。
    // 交错的 GIF 不会从上到下线性显示扫描线，而是重新排列它们
    // 因此，即使在 GIF 完全加载之前，其内容也会变得清晰。
    saveOptions.Interlaced = true;

    // 另存为无损 GIF。
    using (System.IO.Stream stream = System.IO.File.OpenWrite(dir + "output.gif"))
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the lossless GIF: {0} bytes.", stream.Length);
    }

    // 设置允许的最大像素差异。如果大于零，将使用有损压缩。
    // 推荐的最佳有损压缩值为 80。30 表示非常轻的压缩，200 表示较重的压缩。
    saveOptions.MaxDiff = 80;

    // 另存为有损 GIF。
    using (System.IO.Stream stream = System.IO.File.OpenWrite(dir + "output.lossy.gif"))
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the lossy GIF: {0} bytes.", stream.Length);
    }
}

//输出可能如下所示：
//无损 GIF 的大小：212816 字节。
//有损 GIF 的大小：89726 字节。
```

### 另请参见

* class [GifOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../gifoptions/)
* assembly [Aspose.Imaging](../../../)


