---
title: "TiffImage.HasAlpha"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية TiffImage. تحديد ما إذا كانت الصورة تحتوي على قناة ألفا، مما يوفر معلومات حيوية لعمليات العرض والتجميع. دمج هذه الميزة لتحسين سير عمل المعالجة البصرية وضمان تمثيل دقيق ومعالجة العناصر الشفافة."
type: docs
weight: 60
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/hasalpha/
---
## TiffImage.HasAlpha property

حدد ما إذا كانت الصورة تحتوي على قناة ألفا، مما يوفر معلومات حاسمة لعمليات العرض والتجميع. دمج هذه الميزة لتحسين سير عمل المعالجة البصرية، وضمان تمثيل دقيق ومعالجة للعناصر الشفافة.

```csharp
public override bool HasAlpha { get; }
```

### Property Value

قناة ألفا موجودة.

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

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


