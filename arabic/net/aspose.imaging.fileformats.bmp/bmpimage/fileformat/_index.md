---
title: "BmpImage.FileFormat"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية BmpImage. استرجع قيمة تنسيق الملف بسهولة باستخدام هذه الخاصية السهلة الاستخدام. مثالية للمطورين الذين يبحثون عن وصول سريع إلى معلومات حول تنسيق الملف."
type: docs
weight: 50
url: /ar/net/aspose.imaging.fileformats.bmp/bmpimage/fileformat/
---
## BmpImage.FileFormat property

استرجع بسهولة قيمة تنسيق الملف باستخدام هذه الخاصية سهلة الاستخدام. مثالي للمطورين الذين يبحثون عن وصول سريع إلى معلومات حول تنسيق الملف

```csharp
public override FileFormat FileFormat { get; }
```

## أمثلة

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

* enum [FileFormat](../../../aspose.imaging/fileformat/)
* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)


