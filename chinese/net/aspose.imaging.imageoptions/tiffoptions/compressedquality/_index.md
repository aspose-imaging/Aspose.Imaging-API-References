---
title: "TiffOptions.CompressedQuality"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffOptions 属性。获取或设置压缩图像质量。与 JPEG 压缩一起使用"
type: docs
weight: 80
url: /zh/net/aspose.imaging.imageoptions/tiffoptions/compressedquality/
---
## TiffOptions.CompressedQuality property

获取或设置压缩图像质量。与 JPEG 压缩一起使用。

```csharp
public int CompressedQuality { get; set; }
```

## 示例

此示例展示了如何使用 JPEG 压缩和指定的压缩图像质量创建 TIFF 图像。

```csharp
[C#]

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load("c:\\temp\\zeebra.tif"))
{
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    // 设置 RGB 颜色模型。
    tiffOptions.Photometric = TiffPhotometrics.Rgb;
    // 设置 JPEG 压缩。
    tiffOptions.Compression = TiffCompressions.Jpeg;
    tiffOptions.CompressedQuality = 50;
    // 为每个颜色分量设置 8 位。
    tiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };
    
    image.Save("zeebra.tif-50.tiff", tiffOptions);
}
```

### 另请参见

* class [TiffOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../tiffoptions/)
* assembly [Aspose.Imaging](../../../)


