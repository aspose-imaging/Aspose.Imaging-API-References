---
title: "TiffImage.PremultiplyComponents"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية TiffImage. تشير إلى ما إذا كانت المكونات تحتاج إلى الضرب المسبق لضمان معالجة فعّالة للعناصر البصرية. حسّن عمليات العرض بتبديل هذه الخاصية لتبسيط سير عمل الرسومات لأداء محسن"
type: docs
weight: 100
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/premultiplycomponents/
---
## TiffImage.PremultiplyComponents property

أشر إذا كانت المكونات تحتاج إلى الضرب المسبق، لضمان معالجة فعّالة للعناصر البصرية. حسّن عمليات العرض عن طريق تبديل هذه الخاصية، مما يبسط سير عمل الرسومات لأداء محسن.

```csharp
public override bool PremultiplyComponents { get; set; }
```

### Property Value

`true` إذا كان يجب ضرب المكونات مسبقًا؛ وإلا `false`.

## أمثلة

المثال التالي ينشئ صورة TIFF جديدة، يحفظ البكسلات شبه الشفافة المحددة، ثم يحمل تلك البكسلات ويحصل على الألوان النهائية في الشكل المضروب مسبقًا.

```csharp
[C#]

int imageWidth = 3;
int imageHeight = 2;

Aspose.Imaging.Color[] colors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.FromArgb(127, 255, 0, 0),
    Aspose.Imaging.Color.FromArgb(127, 0, 255, 0),
    Aspose.Imaging.Color.FromArgb(127, 0, 0, 255),
    Aspose.Imaging.Color.FromArgb(127, 255, 255, 0),
    Aspose.Imaging.Color.FromArgb(127, 255, 0, 255),
    Aspose.Imaging.Color.FromArgb(127, 0, 255, 255),
};

Aspose.Imaging.ImageOptions.TiffOptions createOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.TiffDeflateRgba);
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Create(createOptions, imageWidth, imageHeight))
{
    // حفظ البكسلات لكامل الصورة.
    image.SavePixels(image.Bounds, colors);

    // يتم تخزين البكسلات في الصورة الأصلية بالشكل غير المضروب مسبقًا.
    // يجب تحديد الخيار المقابل صراحةً للحصول على مكونات اللون المضروبة مسبقًا.
    // يتم حساب مكونات اللون المضروبة مسبقًا باستخدام الصيغ التالية:
    // red = original_red * alpha / 255;
    // green = original_green * alpha / 255;
    // blue = original_blue * alpha / 255;
    image.PremultiplyComponents = true;
    Aspose.Imaging.Color[] premultipliedColors = image.LoadPixels(image.Bounds);

    for (int i = 0; i < colors.Length; i++)
    {
        System.Console.WriteLine("Original color: {0}", colors[i].ToString());
        System.Console.WriteLine("Premultiplied color: {0}", premultipliedColors[i].ToString());
    }
}

//سيظهر الناتج كما يلي:
//اللون الأصلي: Color [A=127, R=255, G=0, B=0]
//اللون المضروب مسبقًا: Color [A=127, R=127, G=0, B=0]
//اللون الأصلي: Color [A=127, R=0, G=255, B=0]
//اللون المضروب مسبقًا: Color [A=127, R=0, G=127, B=0]
//اللون الأصلي: Color [A=127, R=0, G=0, B=255]
//اللون المضروب مسبقًا: Color [A=127, R=0, G=0, B=127]
//اللون الأصلي: Color [A=127, R=255, G=255, B=0]
//اللون المضروب مسبقًا: Color [A=127, R=127, G=127, B=0]
//اللون الأصلي: Color [A=127, R=255, G=0, B=255]
//اللون المسبق الضرب: Color [A=127, R=127, G=0, B=127]
//اللون الأصلي: Color [A=127, R=0, G=255, B=255]
//اللون المسبق الضرب: Color [A=127, R=0, G=127, B=127]
```

### انظر أيضًا

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


