---
title: "TiffFrame.VerticalResolution"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية TiffFrame. تحصل أو تعين الدقة العمودية بوحدات البكسل لكل بوصة لهذا RasterImage."
type: docs
weight: 110
url: /ar/net/aspose.imaging.fileformats.tiff/tiffframe/verticalresolution/
---
## TiffFrame.VerticalResolution property

تحصل أو تعين الدقة العمودية، بوحدات البكسل لكل بوصة، لهذا [`RasterImage`](../../../aspose.imaging/rasterimage/).

```csharp
public override double VerticalResolution { get; set; }
```

### Property Value

الدقة العمودية.

## أمثلة

المثال التالي يوضح كيفية ضبط الدقة الأفقية/العمودية لإطار TIFF منفصل.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمّل صورة TIFF من ملف.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    int i = 0;
    foreach (Aspose.Imaging.FileFormats.Tiff.TiffFrame frame in tiffImage.Frames)
    {
        // احصل على الدقة الأفقية والعمودية لإطار TiffFrame.
        double horizontalResolution = frame.HorizontalResolution;
        double verticalResolution = frame.VerticalResolution;
        System.Console.WriteLine("The horizontal resolution of frame {0}, pixels per inch: {1}", i, horizontalResolution);
        System.Console.WriteLine("The vertical resolution, of frame {0}, pixels per inch: {1}", i, verticalResolution);

        if (horizontalResolution != 96.0 || verticalResolution != 96.0)
        {
            // استخدم طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
            System.Console.WriteLine("Set resolution values to 96 dpi");
            frame.SetResolution(96.0, 96.0);

            System.Console.WriteLine("The horizontal resolution of frame {0}, pixels per inch: {1}", i, horizontalResolution);
            System.Console.WriteLine("The vertical resolution, of frame {0}, pixels per inch: {1}", i, verticalResolution);
        }

        ++i;
    }
}
```

### انظر أيضًا

* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)


