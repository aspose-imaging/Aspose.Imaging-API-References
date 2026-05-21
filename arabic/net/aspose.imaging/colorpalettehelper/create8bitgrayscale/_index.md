---
title: "ColorPaletteHelper.Create8BitGrayscale"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة ColorPaletteHelper. تنشئ لوحة تدرج الرمادي 8 بت"
type: docs
weight: 40
url: /ar/net/aspose.imaging/colorpalettehelper/create8bitgrayscale/
---
## ColorPaletteHelper.Create8BitGrayscale method

ينشئ لوحة تدرج رمادي 8 بت.

```csharp
public static IColorPalette Create8BitGrayscale(bool minIsWhite)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| minIsWhite | Boolean | إذا تم تعيينه إلى `true` تبدأ اللوحة باللون الأبيض، وإلا تبدأ باللون الأسود. |

### قيمة الإرجاع

لوحة تدرج الرمادي 8 بت.

## أمثلة

المثال التالي ينشئ صورة BMP بتدرج رمادي مُلوَّنة بلوحة ألوان ثم يحفظها إلى ملف

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.BmpOptions createOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

// احفظ إلى ملف
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.palette8bit.bmp", false);
    
// استخدم 8 بتات لكل بكسل لتقليل حجم صورة الإخراج.
createOptions.BitsPerPixel = 8;

// حدد لوحة ألوان تدرج رمادي قياسية 8‑bit التي تغطي جميع ألوان التدرج الرمادي.
// إذا كانت الصورة المعالجة تحتوي فقط على ألوان تدرج رمادي، فإن نسختها المُلوَّنة بلوحة ألوان
// تكون غير قابلة للتمييز بصريًا عن نسخة غير مُلوَّنة بلوحة ألوان.
createOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

// احفظ دون ضغط.
// يمكنك أيضًا استخدام ضغط RLE-8 لتقليل حجم الصورة الناتجة.
createOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

// حدد الدقة الأفقية والعمودية إلى 96 نقطة في البوصة.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

// أنشئ صورة BMP بحجم 100 × 100 بكسل واحفظها إلى ملف
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(image.Width, image.Height),
        Aspose.Imaging.Color.Black,
        Aspose.Imaging.Color.White);

    // املأ الصورة بتدرج رمادي
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save();
}
```

### انظر أيضًا

* interface [IColorPalette](../../icolorpalette/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.Imaging](../../colorpalettehelper/)
* assembly [Aspose.Imaging](../../../)


