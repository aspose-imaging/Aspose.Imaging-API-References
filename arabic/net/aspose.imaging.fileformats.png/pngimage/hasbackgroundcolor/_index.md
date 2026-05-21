---
title: "PngImage.HasBackgroundColor"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية PngImage. تسترجع قيمة منطقية تشير إلى ما إذا كانت الصورة تحتوي على لون خلفية. هذه الخاصية مفيدة للتطبيقات التي تحتاج إلى تحديد ما إذا كانت الصورة تشمل لون خلفية، وهو ما قد يكون مهمًا لمهام معالجة مختلفة مثل التركيب أو العرض أو التصدير."
type: docs
weight: 60
url: /ar/net/aspose.imaging.fileformats.png/pngimage/hasbackgroundcolor/
---
## PngImage.HasBackgroundColor property

يسترجع قيمة منطقية تُظهر ما إذا كانت الصورة تحتوي على لون خلفية. هذه الخاصية مفيدة للتطبيقات التي تحتاج إلى معرفة ما إذا كانت الصورة تشمل لون خلفية، وهو ما قد يكون مهمًا لمهام معالجة مختلفة مثل التركيب، التصيير، أو التصدير.

```csharp
public override bool HasBackgroundColor { get; set; }
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


