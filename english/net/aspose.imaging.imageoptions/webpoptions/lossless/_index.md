---
title: WebPOptions.Lossless
second_title: Aspose.Imaging for .NET API Reference
description: WebPOptions property. Gets or sets a value indicating whether this WebPOptions is lossless
type: docs
weight: 40
url: /net/aspose.imaging.imageoptions/webpoptions/lossless/
---
## WebPOptions.Lossless property

Gets or sets a value indicating whether this [`WebPOptions`](../) is lossless.

```csharp
public bool Lossless { get; set; }
```

### Property Value

`true` if lossless; otherwise, `false`.

## Examples

This example shows how to create a WebP image from another raster image with different compression quality.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a GIF animation
using (Aspose.Imaging.Image image = new Aspose.Imaging.Image.Load(dir + "test.gif"))
{
    // for lossless compression, increasing the quality setting increases the compression quality and decreases the file size
    image.Save(
        dir + "output_lossless_20.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 20 }); // file size: 42 KB

    image.Save(
        dir + "output_lossless_50.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 50 }); // file size: 41 KB

    image.Save(
        dir + "output_lossless_80.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 80 }); // file size: 40 KB


    // for lossy compression, increasing the Quality value increases the image quality and increases the file size
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

### See Also

* class [WebPOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../webpoptions/)
* assembly [Aspose.Imaging](../../../)


