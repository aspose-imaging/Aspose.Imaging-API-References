---
title: JpegOptions.RgbColorProfile
second_title: Aspose.Imaging for .NET API Reference
description: JpegOptions property. The destination RGB color profile for CMYK jpeg images. Use for saving images. Must be in pair with CMYKColorProfile for correct color conversion
type: docs
weight: 170
url: /net/aspose.imaging.imageoptions/jpegoptions/rgbcolorprofile/
---
## JpegOptions.RgbColorProfile property

The destination RGB color profile for CMYK jpeg images. Use for saving images. Must be in pair with CMYKColorProfile for correct color conversion.

```csharp
public StreamSource RgbColorProfile { get; set; }
```

## Examples

The following example loads PNG and saves it to CMYK JPEG using custom ICC profile. Then loads CMYK JPEG and saves it back to PNG. The color conversion from RGB to CMYK and from CMYK to RGB is performed using custom ICC profiles.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load PNG and save it to CMYK JPEG
using (Aspose.Imaging.FileFormats.Png.PngImage image = (Aspose.Imaging.FileFormats.Png.PngImage)Image.Load(dir + "sample.png"))
{
    using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
    using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
    {
        Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();
        saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Cmyk;

        // Use custom ICC profiles
        saveOptions.RgbColorProfile = new Aspose.Imaging.Sources.StreamSource(rgbProfileStream);
        saveOptions.CmykColorProfile = new Aspose.Imaging.Sources.StreamSource(cmykProfileStream);

        image.Save(dir + "output.cmyk.jpg", saveOptions);
    }
}

// Load CMYK JPEG and save it to PNG
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage image = (Aspose.Imaging.FileFormats.Jpeg.JpegImage)Image.Load(dir + "output.cmyk.jpg"))
{
    using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
    using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
    {
        // Use custom ICC profiles
        image.RgbColorProfile = new Aspose.Imaging.Sources.StreamSource(rgbProfileStream);
        image.CmykColorProfile = new Aspose.Imaging.Sources.StreamSource(cmykProfileStream);

        Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
        image.Save(dir + "output.rgb.png", saveOptions);
    }
}
```

### See Also

* class [StreamSource](../../../aspose.imaging.sources/streamsource/)
* class [JpegOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../jpegoptions/)
* assembly [Aspose.Imaging](../../../)


