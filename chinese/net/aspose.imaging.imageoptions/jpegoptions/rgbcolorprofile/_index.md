---
title: "JpegOptions.RgbColorProfile"
second_title: "Aspose.Imaging for .NET API 参考"
description: "JpegOptions 属性。CMYK jpeg 图像的目标 RGB 色彩配置文件。用于保存图像。必须与 CMYKColorProfile 配对，以实现正确的颜色转换。"
type: docs
weight: 170
url: /zh/net/aspose.imaging.imageoptions/jpegoptions/rgbcolorprofile/
---
## JpegOptions.RgbColorProfile property

CMYK jpeg 图像的目标 RGB 色彩配置文件。用于保存图像。必须与 CMYKColorProfile 配对，以实现正确的颜色转换。

```csharp
public StreamSource RgbColorProfile { get; set; }
```

## 示例

以下示例使用自定义 ICC 配置文件加载 PNG 并将其保存为 CMYK JPEG。随后加载 CMYK JPEG 并将其保存回 PNG。RGB 到 CMYK 以及 CMYK 到 RGB 的颜色转换均使用自定义 ICC 配置文件执行。

```csharp
[C#]

string dir = "c:\\temp\\";

// 加载 PNG 并将其保存为 CMYK JPEG
using (Aspose.Imaging.FileFormats.Png.PngImage image = (Aspose.Imaging.FileFormats.Png.PngImage)Image.Load(dir + "sample.png"))
{
    using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
    using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
    {
        Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();
        saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Cmyk;

        // 使用自定义 ICC 配置文件
        saveOptions.RgbColorProfile = new Aspose.Imaging.Sources.StreamSource(rgbProfileStream);
        saveOptions.CmykColorProfile = new Aspose.Imaging.Sources.StreamSource(cmykProfileStream);

        image.Save(dir + "output.cmyk.jpg", saveOptions);
    }
}

// 加载 CMYK JPEG 并将其保存为 PNG
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage image = (Aspose.Imaging.FileFormats.Jpeg.JpegImage)Image.Load(dir + "output.cmyk.jpg"))
{
    using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
    using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
    {
        // 使用自定义 ICC 配置文件
        image.RgbColorProfile = new Aspose.Imaging.Sources.StreamSource(rgbProfileStream);
        image.CmykColorProfile = new Aspose.Imaging.Sources.StreamSource(cmykProfileStream);

        Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
        image.Save(dir + "output.rgb.png", saveOptions);
    }
}
```

### 另请参见

* class [StreamSource](../../../aspose.imaging.sources/streamsource/)
* class [JpegOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../jpegoptions/)
* assembly [Aspose.Imaging](../../../)


