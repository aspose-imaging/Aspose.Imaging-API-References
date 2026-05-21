---
title: "PngImage.HasTransparentColor"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية PngImage. تُوفر قيمة منطقية تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف. هذه الخاصية حاسمة للتطبيقات التي تحتاج إلى معالجة الشفافية، مما يسمح للمطورين بتحديد ما إذا كان هناك حاجة إلى معالجة إضافية للتعامل مع المناطق الشفافة في الصورة."
type: docs
weight: 70
url: /ar/net/aspose.imaging.fileformats.png/pngimage/hastransparentcolor/
---
## PngImage.HasTransparentColor property

يوفر قيمة منطقية تُظهر ما إذا كانت الصورة تحتوي على لون شفاف. هذه الخاصية حاسمة للتطبيقات التي تحتاج إلى التعامل مع الشفافية، مما يسمح للمطورين بتحديد ما إذا كانت هناك حاجة لمعالجة إضافية للتعامل مع المناطق الشفافة في الصورة.

```csharp
public override bool HasTransparentColor { get; set; }
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

* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)


