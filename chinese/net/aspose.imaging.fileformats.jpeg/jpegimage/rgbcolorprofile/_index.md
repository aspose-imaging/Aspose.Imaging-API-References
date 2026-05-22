---
title: "JpegImage.RgbColorProfile"
second_title: "Aspose.Imaging for .NET API 参考"
description: "JpegImage 属性。针对 CMYK 和 YCCK JPEG 图像的 RGB 色彩配置文件确保准确的颜色转换和呈现。它必须与 CMYKColorProfile 配对，以保持颜色渲染的一致性和保真度。此配对对于需要精确颜色管理和图像再现的应用程序至关重要，确保 RGB 数据得到正确解释和显示。"
type: docs
weight: 150
url: /zh/net/aspose.imaging.fileformats.jpeg/jpegimage/rgbcolorprofile/
---
## JpegImage.RgbColorProfile property

CMYK 和 YCCK JPEG 图像的 RGB 颜色配置文件可确保准确的颜色转换和呈现。它必须与 CMYKColorProfile 配对，以保持颜色渲染的一致性和保真度。此配对对于需要精确颜色管理和图像再现的应用程序至关重要，确保 RGB 数据得到正确解释和显示。

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
* class [JpegImage](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage/)
* assembly [Aspose.Imaging](../../../)


