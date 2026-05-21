---
title: "WebPFrameBlock.HasAlpha"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية WebPFrameBlock. تحصل على قيمة تشير إلى ما إذا كانت هذه الحالة تحتوي على قناة ألفا"
type: docs
weight: 80
url: /ar/net/aspose.imaging.fileformats.webp/webpframeblock/hasalpha/
---
## WebPFrameBlock.HasAlpha property

يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على ألفا.

```csharp
public override bool HasAlpha { get; }
```

### Property Value

`true` إذا كان هذا الكائن يحتوي على قناة ألفا؛ وإلا `false`.

## أمثلة

المثال التالي يحمل صورة WEBP ويطبع معلومات حول تنسيق البيانات الخام وقناة ألفا.

```csharp
[C#]

string dir = "c:\\temp\\";

string fileName = dir + "sample.webp";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // إذا كان للإطار النشط في TIFF قناة ألفا، فإن صورة TIFF بالكامل تُعتبر أنها تحتوي على قناة ألفا.
    System.Console.WriteLine("ImageFile={0}, FileFormat={1}, HasAlpha={2}", fileName, webpImage.RawDataFormat, webpImage.HasAlpha);

    int i = 0;
    foreach (Aspose.Imaging.FileFormats.Webp.IFrame frame in webpImage.Blocks)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock frameBlock = frame as Aspose.Imaging.FileFormats.Webp.WebPFrameBlock;
        if (frameBlock != null)
        {
            System.Console.WriteLine("Frame={0}, FileFormat={1}, HasAlpha={2}", i++, frameBlock.RawDataFormat, frameBlock.HasAlpha);
        }
    }
}

// قد يبدو الإخراج هكذا:
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, القنوات المستخدمة: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, القنوات المستخدمة: 1, HasAlpha=False
```

### انظر أيضًا

* class [WebPFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpframeblock/)
* assembly [Aspose.Imaging](../../../)


