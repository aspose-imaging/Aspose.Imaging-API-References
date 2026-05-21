---
title: "TiffImage.SetResolution"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة TiffImage. تحدد الدقة لـ RasterImage المحدد مما يتيح تحكمًا دقيقًا في عرض الصورة وخصائص العرض. دمج هذه الوظيفة لتحسين المخرجات البصرية وضمان التوافق مع أجهزة ومنصات الإخراج المتنوعة، مما يعزز تجربة المستخدم العامة"
type: docs
weight: 390
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/setresolution/
---
## TiffImage.SetResolution method

تحدد الدقة لـ [`RasterImage`](../../../aspose.imaging/rasterimage/)، مما يتيح تحكمًا دقيقًا في عرض الصورة وخصائص العرض. دمج هذه الوظيفة لتحسين المخرجات البصرية وضمان التوافق مع أجهزة ومنصات الإخراج المتنوعة، مما يعزز تجربة المستخدم العامة.

```csharp
public override void SetResolution(double dpiX, double dpiY)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| dpiX | Double | الدقة الأفقية، بوحدة النقاط في البوصة، لـ [`RasterImage`](../../../aspose.imaging/rasterimage/). |
| dpiY | Double | الدقة العمودية، بوحدة النقاط في البوصة، لـ [`RasterImage`](../../../aspose.imaging/rasterimage/). |

## أمثلة

المثال التالي يوضح كيفية ضبط الدقة الأفقية/العمودية لصورة TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // الحصول على الدقة الأفقية والعمودية لـ TiffImage.
    double horizontalResolution = tiffImage.HorizontalResolution;
    double verticalResolution = tiffImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // استخدم طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        tiffImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", tiffImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", tiffImage.VerticalResolution);
    }
}
```

### انظر أيضًا

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


