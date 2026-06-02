---
title: "WebPImage.HasAlpha"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية WebPImage. استرجاع ما إذا كانت الصورة تحتوي على قناة ألفا التي تشير إلى وجود معلومات شفافية. استخدم هذه الخاصية لتحديد ما إذا كانت الصورة تشمل الشفافية، مما يتيح المعالجة المناسبة للعمليات المتعلقة بالألفا داخل تطبيقك"
type: docs
weight: 30
url: /ar/net/aspose.imaging.fileformats.webp/webpimage/hasalpha/
---
## WebPImage.HasAlpha property

استرجع ما إذا كانت الصورة تحتوي على قناة ألفا، مما يشير إلى وجود معلومات الشفافية. استخدم هذه الخاصية لتحديد ما إذا كانت الصورة تشمل الشفافية، مما يتيح المعالجة المناسبة للعمليات المتعلقة بالألفا داخل تطبيقك.

```csharp
public override bool HasAlpha { get; }
```

### Property Value

قناة ألفا موجودة.

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

* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)


