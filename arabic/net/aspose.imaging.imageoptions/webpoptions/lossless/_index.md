---
title: "WebPOptions.Lossless"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية WebPOptions. تحصل أو تعيّن قيمة تشير إلى ما إذا كان هذا WebPOptions بدون فقدان"
type: docs
weight: 40
url: /ar/net/aspose.imaging.imageoptions/webpoptions/lossless/
---
## WebPOptions.Lossless property

تحصل أو تعيّن قيمة تشير إلى ما إذا كان هذا [`WebPOptions`](../) بدون فقدان.

```csharp
public bool Lossless { get; set; }
```

### Property Value

`true` إذا كان بدون فقدان؛ وإلا `false`.

## أمثلة

يوضح هذا المثال كيفية إنشاء صورة WebP من صورة نقطية أخرى مع جودة ضغط مختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل رسوم متحركة GIF
using (Aspose.Imaging.Image image = new Aspose.Imaging.Image.Load(dir + "test.gif"))
{
    // لضغط بدون فقدان، زيادة إعداد الجودة يزيد من جودة الضغط ويقلل من حجم الملف
    image.Save(
        dir + "output_lossless_20.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 20 }); // file size: 42 KB

    image.Save(
        dir + "output_lossless_50.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 50 }); // file size: 41 KB

    image.Save(
        dir + "output_lossless_80.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 80 }); // file size: 40 KB


    // لضغط بفقدان، زيادة قيمة الجودة يزيد من جودة الصورة ويزيد من حجم الملف
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

### انظر أيضًا

* class [WebPOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../webpoptions/)
* assembly [Aspose.Imaging](../../../)


