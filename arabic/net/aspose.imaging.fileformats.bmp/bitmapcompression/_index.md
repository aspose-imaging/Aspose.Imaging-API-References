---
title: "تعداد BitmapCompression"
second_title: "Aspose.Imaging for .NET API Reference"
description: "تعداد Aspose.Imaging.FileFormats.Bmp.BitmapCompression. يحدد طرق ضغط الصور النقطية المختلفة"
type: docs
weight: 1380
url: /ar/net/aspose.imaging.fileformats.bmp/bitmapcompression/
---
## BitmapCompression enumeration

يحدد طرق ضغط البت ماب المختلفة.

```csharp
public enum BitmapCompression : uint
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Rgb | `0` | بدون ضغط. |
| Rle8 | `1` | ضغط RLE 8-بت/بكسل. يمكن استخدامه فقط مع صور نقطية 8-بت/بكسل. |
| Rle4 | `2` | ضغط RLE 4-بت/بكسل. يمكن استخدامه فقط مع صور نقطية 4-بت/بكسل. |
| Bitfields | `3` | حقول بت RGB. يمكن استخدامها فقط مع صور نقطية 16 و 32-بت/بكسل. |
| Jpeg | `4` | ضغط JPEG. الصورة النقطية تحتوي على صورة JPEG. |
| Png | `5` | ضغط PNG. الصورة النقطية تحتوي على صورة PNG. |
| AlphaBitfields | `6` | حقول بت RGBA. يمكن استخدامها فقط مع صور نقطية 16 و 32-بت/بكسل. |
| Dxt1 | `827611204` | ضغط DXT1. الصورة النقطية تحتوي على نسيج. |

## أمثلة

يوضح المثال كيفية تصدير BmpImage بنوع الضغط Rgb.

```csharp
[C#]

string sourcePath = "input.png";
// حمِّل صورة PNG من ملف.
using (Image pngImage = Image.Load(sourcePath))
{
    // يتم حفظ صورة BMP بدعم الشفافية افتراضيًا، ويتم ذلك باستخدام طريقة الضغط BitmapCompression.Bitfields.
    // لحفظ صورة BMP باستخدام طريقة الضغط Rgb، يجب تحديد BmpOptions مع خاصية Compression مضبوطة على BitmapCompression.Rgb.
    pngImage.Save(outputPath, new BmpOptions() { Compression = BitmapCompression.Rgb });
}
```

يوضح المثال كيفية تصدير BmpImage من ملف Png مع الحفاظ على قناة ألفا، وحفظ ملف Bmp مع الشفافية.

```csharp
[C#]

string sourcePath = "input.png";
// حمِّل صورة PNG من ملف.
using (Image pngImage = Image.Load(sourcePath))
{
    // يتم حفظ صورة BMP بدعم الشفافية افتراضيًا.
    // إذا كنت ترغب في تحديد هذا الوضع صراحةً، يجب ضبط خاصية Compression في BmpOptions على BitmapCompression.Bitfields.
    // طريقة الضغط BitmapCompression.Bitfields هي طريقة الضغط الافتراضية في BmpOptions.
    // لذلك يمكن تحقيق نفس نتيجة تصدير صورة Bmp مع الشفافية إما بإحدى الطرق التالية.
    // مع خيارات افتراضية ضمنية:
    pngImage.Save(outputPath);
    // مع خيارات افتراضية صريحة:
    pngImage.Save(outputPath, new BmpOptions());
    // تحديد طريقة الضغط BitmapCompression.Bitfields:
    pngImage.Save(outputPath, new BmpOptions() { Compression = BitmapCompression.Bitfields });
}
```

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Bmp](../../aspose.imaging.fileformats.bmp/)
* assembly [Aspose.Imaging](../../)


