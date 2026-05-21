---
title: "PngImage.RawDataFormat"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية PngImage. تصل إلى تنسيق البيانات الخام للصورة. توفر هذه الخاصية نظرة على كيفية هيكلة بيانات الصورة داخليًا، مما يمكن أن يكون مفيدًا لمهام معالجة الصور المتقدمة أو تحويل الصيغ."
type: docs
weight: 120
url: /ar/net/aspose.imaging.fileformats.png/pngimage/rawdataformat/
---
## PngImage.RawDataFormat property

يصل إلى تنسيق البيانات الخام للصورة. توفر هذه الخاصية نظرة على كيفية تنظيم بيانات الصورة داخليًا، وهو ما يمكن أن يكون مفيدًا لمهام معالجة الصور المتقدمة أو تحويل الصيغ.

```csharp
public override PixelDataFormat RawDataFormat { get; }
```

## أمثلة

يوضح المثال التالي كيفية تحميل صور PNG وطباعة معلومات حول تنسيق البيانات الخام وقناة ألفا.

```csharp
[C#]

// صور PNG للتحميل.
string[] fileNames = new string[]
{
    @"c:\temp\sample.png",
    @"c:\temp\alpha.png",
};

foreach (string fileName in fileNames)
{
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
    {
        Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)image;
        System.Console.WriteLine("ImageFile={0}, FileFormat={1}, HasAlpha={2}", fileName, pngImage.RawDataFormat, pngImage.HasAlpha);
    }
}

// قد يبدو الإخراج هكذا:
// ImageFile=c:\temp\sample.png, FileFormat=Rgb24Bpp, used channels: 8,8,8, HasAlpha=False
// ImageFile=c:\temp\alpha.png, FileFormat=RGBA32Bpp, used channels: 8,8,8,8, HasAlpha=True
```

### انظر أيضًا

* class [PixelDataFormat](../../../aspose.imaging/pixeldataformat/)
* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)


