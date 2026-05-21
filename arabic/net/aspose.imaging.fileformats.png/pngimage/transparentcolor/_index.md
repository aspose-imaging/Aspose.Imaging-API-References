---
title: "PngImage.TransparentColor"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية PngImage. تسترجع اللون الشفاف للصورة إذا كان موجودًا. هذه الخاصية قيمة للتطبيقات التي تتطلب معالجة دقيقة للمناطق الشفافة داخل الصور، مما يسمح للمطورين بالوصول إلى اللون الشفاف المحدد واستخدامه."
type: docs
weight: 130
url: /ar/net/aspose.imaging.fileformats.png/pngimage/transparentcolor/
---
## PngImage.TransparentColor property

يسترجع اللون الشفاف للصورة، إذا كان موجودًا. هذه الخاصية ذات قيمة للتطبيقات التي تتطلب معالجة دقيقة للمناطق الشفافة داخل الصور، مما يتيح للمطورين الوصول إلى اللون الشفاف المحدد واستخدامه.

```csharp
public override Color TransparentColor { get; set; }
```

## أمثلة

يوضح المثال التالي كيفية تعيين ألوان شفافة بالكامل لجزء من صورة PNG ذات ألوان حقيقية لا تدعم قناة ألفا.

```csharp
[C#]

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource("c:\\temp\\transparent.png", false);
createOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.Truecolor;

// أنشئ صورة PNG ذات ألوان حقيقية بحجم 100x100 بكسل.
using (Aspose.Imaging.Image image = Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)image;
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(pngImage);

    // سيتم اعتبار جميع البكسلات الحمراء شفافة بالكامل.
    pngImage.TransparentColor = Aspose.Imaging.Color.Red;
    pngImage.HasTransparentColor = true;

    // ستمتلك جميع البكسلات الشفافة لون خلفية.
    pngImage.BackgroundColor = Aspose.Imaging.Color.Green;
    pngImage.HasBackgroundColor = true;

    // املأ الصورة بالكامل باللون الأبيض.
    gr.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.White), pngImage.Bounds);

    // املأ ربع الصورة العلوي الأيسر باللون الشفاف.
    // هذا يجعل ربع الصورة العلوي الأيسر ملونًا بلون الخلفية.
    Rectangle rect = new Rectangle(0, 0, pngImage.Width / 2, pngImage.Height / 2);
    gr.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red), rect);

    pngImage.Save();
}
```

### انظر أيضًا

* struct [Color](../../../aspose.imaging/color/)
* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)


