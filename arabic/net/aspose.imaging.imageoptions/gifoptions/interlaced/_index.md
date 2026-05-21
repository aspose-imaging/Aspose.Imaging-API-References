---
title: "GifOptions.Interlaced"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية GifOptions. صحيح إذا كان يجب أن تكون الصورة متشابكة"
type: docs
weight: 80
url: /ar/net/aspose.imaging.imageoptions/gifoptions/interlaced/
---
## GifOptions.Interlaced property

صحيح إذا كان يجب أن تكون الصورة متشابكة.

```csharp
public bool Interlaced { get; set; }
```

## أمثلة

يوضح هذا المثال كيفية حفظ صورة BMP بتنسيق GIF باستخدام خيارات مختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(1000, 1000))
{
    // املأ الصورة بالكامل بالتدرج الأزرق-الأصفر.
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Yellow);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(bmpImage);
    graphics.FillRectangle(gradientBrush, bmpImage.Bounds);

    Aspose.Imaging.ImageOptions.GifOptions saveOptions = new Aspose.Imaging.ImageOptions.GifOptions();

    // عدد البتات المطلوبة لتخزين لون، ناقص 1.
    saveOptions.ColorResolution = 7;

    // يعني تصحيح لوحة الألوان أنه كلما تم تصدير الصورة إلى GIF سيتم تحليل ألوان الصورة الأصلية.
    // من أجل إنشاء أفضل لوحة ألوان مطابقة (في حال عدم وجود لوحة ألوان للصورة أو عدم تحديدها في الخيارات)
    saveOptions.DoPaletteCorrection = true;

    // حمّل صورة GIF بطريقة تدريجية.
    // ملف GIF المتداخل لا يعرض خطوط المسح الخاصة به بشكل خطي من الأعلى إلى الأسفل، بل يعيد ترتيبها
    // لذلك يصبح محتوى GIF واضحًا حتى قبل الانتهاء من تحميله.
    saveOptions.Interlaced = true;

    // احفظ كملف GIF بدون فقدان.
    using (System.IO.Stream stream = System.IO.File.OpenWrite(dir + "output.gif"))
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the lossless GIF: {0} bytes.", stream.Length);
    }

    // حدد الحد الأقصى المسموح به لاختلاف البكسل. إذا كان أكبر من الصفر، سيتم استخدام ضغط بفقدان.
    // القيمة الموصى بها لضغط بفقدان مثالي هي 80. 30 هو ضغط خفيف جدًا، و200 هو ضغط ثقيل.
    saveOptions.MaxDiff = 80;

    // احفظ كملف GIF بفقدان.
    using (System.IO.Stream stream = System.IO.File.OpenWrite(dir + "output.lossy.gif"))
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the lossy GIF: {0} bytes.", stream.Length);
    }
}

//قد يبدو الإخراج هكذا:
//حجم GIF بدون فقدان: 212816 بايت.
//حجم GIF بفقدان: 89726 بايت.
```

### انظر أيضًا

* class [GifOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../gifoptions/)
* assembly [Aspose.Imaging](../../../)


