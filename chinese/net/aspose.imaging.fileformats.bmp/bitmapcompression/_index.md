---
title: "枚举 BitmapCompression"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Bmp.BitmapCompression 枚举。指定不同的位图压缩方法"
type: docs
weight: 1380
url: /zh/net/aspose.imaging.fileformats.bmp/bitmapcompression/
---
## BitmapCompression enumeration

指定不同的位图压缩方法。

```csharp
public enum BitmapCompression : uint
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Rgb | `0` | 无压缩。 |
| Rle8 | `1` | RLE 8 位/像素压缩。只能用于 8 位/像素的位图。 |
| Rle4 | `2` | RLE 4 位/像素压缩。只能用于 4 位/像素的位图。 |
| Bitfields | `3` | RGB 位字段。只能用于 16 位和 32 位/像素的位图。 |
| Jpeg | `4` | JPEG 压缩。位图包含 JPEG 图像。 |
| Png | `5` | PNG 压缩。位图包含 PNG 图像。 |
| AlphaBitfields | `6` | RGBA 位字段。只能用于 16 位和 32 位/像素的位图。 |
| Dxt1 | `827611204` | DXT1 压缩。位图包含纹理。 |

## 示例

示例展示了如何使用 Rgb 压缩类型导出 BmpImage。

```csharp
[C#]

string sourcePath = "input.png";
// 从文件加载 PNG 图像。
using (Image pngImage = Image.Load(sourcePath))
{
    // BMP 图像默认以透明度支持保存，这是通过使用 BitmapCompression.Bitfields 压缩方法实现的。
    // 要使用 Rgb 压缩方法保存 BMP 图像，应指定 Compression 属性设置为 BitmapCompression.Rgb 的 BmpOptions。
    pngImage.Save(outputPath, new BmpOptions() { Compression = BitmapCompression.Rgb });
}
```

示例展示了如何从 Png 文件导出 BmpImage 并保留 alpha 通道，以透明度保存 Bmp 文件。

```csharp
[C#]

string sourcePath = "input.png";
// 从文件加载 PNG 图像。
using (Image pngImage = Image.Load(sourcePath))
{
    // BMP 图像默认以透明度支持保存。
    // 如果您想显式指定此模式，应将 BmpOptions 的 Compression 属性设置为 BitmapCompression.Bitfields。
    // BitmapCompression.Bitfields 压缩方法是 BmpOptions 中的默认压缩方法。
    // 因此，通过以下任一方式都可以实现导出带透明度的 Bmp 图像的相同结果。
    // 使用隐式默认选项：
    pngImage.Save(outputPath);
    // 使用显式默认选项：
    pngImage.Save(outputPath, new BmpOptions());
    // 指定 BitmapCompression.Bitfields 压缩方法：
    pngImage.Save(outputPath, new BmpOptions() { Compression = BitmapCompression.Bitfields });
}
```

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Bmp](../../aspose.imaging.fileformats.bmp/)
* assembly [Aspose.Imaging](../../)


