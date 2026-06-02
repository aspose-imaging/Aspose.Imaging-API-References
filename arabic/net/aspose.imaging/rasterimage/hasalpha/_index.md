---
title: "RasterImage.HasAlpha"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية RasterImage. يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على قناة ألفا"
type: docs
weight: 10
url: /ar/net/aspose.imaging/rasterimage/hasalpha/
---
## RasterImage.HasAlpha property

يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على ألفا.

```csharp
public virtual bool HasAlpha { get; }
```

### Property Value

`true` إذا كان هذا الكائن يحتوي على قناة ألفا؛ وإلا `false`.

## أمثلة

المثال التالي يحمل صورًا نقطية ويطبع معلومات حول تنسيق البيانات الخام وقناة ألفا.

```csharp
[C#]

// ملفات الصورة للتحميل.
string[] fileNames = new string[]
{
    @"c:\temp\sample.bmp",
    @"c:\temp\alpha.png",
};

foreach (string fileName in fileNames)
{
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
    {
        Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
        System.Console.WriteLine("ImageFile={0}, FileFormat={1}, HasAlpha={2}", fileName, rasterImage.RawDataFormat, rasterImage.HasAlpha);
    }
}

// قد يبدو الإخراج هكذا:
// ImageFile=c:\temp\sample.bmp, FileFormat=Rgb24Bpp, used channels: 8,8,8, HasAlpha=False
// ImageFile=c:\temp\alpha.png, FileFormat=RGBA32Bpp, used channels: 8,8,8,8, HasAlpha=True
```

المثال التالي يوضح كيفية استخراج معلومات حول تنسيق البيانات الخام وقناة ألفا من صورة BMP.

```csharp
[C#]

// إنشاء صورة BMP بعمق 32 بت بحجم 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 32, null))
{
    System.Console.WriteLine("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}", bmpImage.FileFormat, bmpImage.RawDataFormat, bmpImage.HasAlpha);
};

// إنشاء صورة BMP بعمق 24 بت بحجم 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 24, null))
{
    System.Console.WriteLine("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}", bmpImage.FileFormat, bmpImage.RawDataFormat, bmpImage.HasAlpha);
};

// عمومًا، لا يدعم BMP قناة ألفا لذا سيظهر الناتج هكذا:
// FileFormat = Bmp, RawDataFormat = Rgb32Bpp, used channels: 8,8,8,8, HasAlpha = False
// FileFormat = Bmp, RawDataFormat = Rgb24Bpp, used channels: 8,8,8, HasAlpha = False
```

### انظر أيضًا

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


