---
title: SetResolution
second_title: Aspose.Imaging لمرجع NET API
description: يضبط الدقة لهذا الغرضRasterImageaspose.imaging/rasterimage .
type: docs
weight: 390
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/setresolution/
---
## TiffImage.SetResolution method

يضبط الدقة لهذا الغرض[`RasterImage`](../../../aspose.imaging/rasterimage) .

```csharp
public override void SetResolution(double dpiX, double dpiY)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| dpiX | Double | الدقة الأفقية ، بالنقاط في البوصة ، من[`RasterImage`](../../../aspose.imaging/rasterimage). |
| dpiY | Double | الدقة الرأسية ، بالنقاط في البوصة ، من[`RasterImage`](../../../aspose.imaging/rasterimage). |

### أمثلة

يوضح المثال التالي كيفية تعيين الدقة الأفقية / الرأسية لصورة TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // احصل على دقة أفقية ورأسية لصورة TiffImage.
    double horizontalResolution = tiffImage.HorizontalResolution;
    double verticalResolution = tiffImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // استخدم طريقة SetResolution لتحديث قيم الدقة في مكالمة واحدة.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        tiffImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", tiffImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", tiffImage.VerticalResolution);
    }
}
```

### أنظر أيضا

* class [TiffImage](../../tiffimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
