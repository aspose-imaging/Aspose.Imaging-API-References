---
title: "TiffFrame.HasAlpha"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية TiffFrame. يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على ألفا"
type: docs
weight: 70
url: /ar/net/aspose.imaging.fileformats.tiff/tiffframe/hasalpha/
---
## TiffFrame.HasAlpha property

يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على ألفا.

```csharp
public override bool HasAlpha { get; }
```

### Property Value

`true` إذا كان هذا الكائن يحتوي على قناة ألفا؛ وإلا `false`.

## أمثلة

المثال التالي يقوم بتحميل صورة TIFF ويطبع معلومات حول تنسيق البيانات الخام وقناة الألفا.

```csharp
[C#]

string dir = "c:\\temp\\";

string fileName = dir + "sample.tif";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // إذا كان للإطار النشط في TIFF قناة ألفا، فإن صورة TIFF بالكامل تُعتبر أنها تحتوي على قناة ألفا.
    System.Console.WriteLine("ImageFile={0}, FileFormat={1}, HasAlpha={2}", fileName, tiffImage.RawDataFormat, tiffImage.HasAlpha);

    int i = 0;
    foreach (Aspose.Imaging.FileFormats.Tiff.TiffFrame frame in tiffImage.Frames)
    {
        System.Console.WriteLine("Frame={0}, FileFormat={1}, HasAlpha={2}", ++i, frame.RawDataFormat, frame.HasAlpha);
    }
}

// قد يبدو الإخراج هكذا:
// ImageFile=c:\temp\sample.tif, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=1, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=2, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
```

### انظر أيضًا

* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)


