---
title: "WebPOptions.Lossless"
second_title: "Aspose.Imaging for .NET API 参考"
description: "WebPOptions 属性。获取或设置一个值，指示此 WebPOptions 是否为无损"
type: docs
weight: 40
url: /zh/net/aspose.imaging.imageoptions/webpoptions/lossless/
---
## WebPOptions.Lossless property

获取或设置一个值，指示此 [`WebPOptions`](../) 是否为无损。

```csharp
public bool Lossless { get; set; }
```

### Property Value

`true` 表示无损；否则为 `false`。

## 示例

此示例展示了如何使用不同的压缩质量从另一幅栅格图像创建 WebP 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 加载 GIF 动画
using (Aspose.Imaging.Image image = new Aspose.Imaging.Image.Load(dir + "test.gif"))
{
    // 对于无损压缩，提升质量设置会提高压缩质量并减小文件大小
    image.Save(
        dir + "output_lossless_20.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 20 }); // file size: 42 KB

    image.Save(
        dir + "output_lossless_50.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 50 }); // file size: 41 KB

    image.Save(
        dir + "output_lossless_80.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 80 }); // file size: 40 KB


    // 对于有损压缩，提升 Quality 值会提升图像质量并增大文件大小
    image.Save(
        dir + "output_lossy_20.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 20 }); // file size: 24 KB

    image.Save(
        dir + "output_lossy_50.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 50 }); // file size: 36 KB

    image.Save(
        dir + "output_lossy_80.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 80 }); // file size: 51 KB
}
```

### 另请参见

* class [WebPOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../webpoptions/)
* assembly [Aspose.Imaging](../../../)


