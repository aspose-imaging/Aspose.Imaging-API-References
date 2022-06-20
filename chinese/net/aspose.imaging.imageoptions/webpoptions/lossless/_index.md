---
title: Lossless
second_title: Aspose.Imaging for .NET API 参考
description: 获取或设置一个值该值指示此WebPOptionsaspose.imaging.imageoptions/webpoptions是否无损
type: docs
weight: 40
url: /zh/net/aspose.imaging.imageoptions/webpoptions/lossless/
---
## WebPOptions.Lossless property

获取或设置一个值，该值指示此[`WebPOptions`](../../webpoptions)是否无损。

```csharp
public bool Lossless { get; set; }
```

### 适当的价值

` true` 如果无损；否则，` false` 。

### 例子

此示例说明如何从另一个具有不同压缩质量的光栅图像创建 WebP 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 加载一个 GIF 动画
using (Aspose.Imaging.Image image = new Aspose.Imaging.Image.Load(dir + "test.gif"))
{
        // 对于无损压缩，增加质量设置会提高压缩质量并减小文件大小
    image.Save(
        dir + "output_lossless_20.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 20 }); // 文件大小：42 KB

    image.Save(
        dir + "output_lossless_50.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 50 });     // 文件大小：41 KB

    image.Save(
        dir + "output_lossless_80.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 80 });     // 文件大小：40 KB


        // 对于有损压缩，增加 Quality 值会提高图像质量并增加文件大小
    image.Save(
        dir + "output_lossy_20.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 20 });     // 文件大小：24 KB

    image.Save(
        dir + "output_lossy_50.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 50 });     // 文件大小：36 KB

    image.Save(
        dir + "output_lossy_80.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 80 });     // 文件大小：51 KB
}
```

### 也可以看看

* class [WebPOptions](../../webpoptions)
* 命名空间 [Aspose.Imaging.ImageOptions](../../webpoptions)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->