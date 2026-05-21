---
title: "RasterImage.PremultiplyComponents"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية RasterImage. تحصل أو تعين قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا"
type: docs
weight: 60
url: /ar/net/aspose.imaging/rasterimage/premultiplycomponents/
---
## RasterImage.PremultiplyComponents property

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا.

```csharp
public virtual bool PremultiplyComponents { get; set; }
```

### Property Value

`true` إذا كان يجب ضرب مكونات الصورة مسبقًا؛ وإلا `false`.

## أمثلة

المثال التالي ينشئ صورة نقطية جديدة، يحفظ البكسلات شبه الشفافة المحددة، ثم يحمل تلك البكسلات ويحصل على الألوان النهائية في الشكل المضروب مسبقًا.

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

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
createOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, imageWidth, imageHeight))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // حفظ البكسلات لكامل الصورة.
    rasterImage.SavePixels(rasterImage.Bounds, colors);

    // يتم تخزين البكسلات في الصورة الأصلية بالشكل غير المضروب مسبقًا.
    // يجب تحديد الخيار المقابل صراحةً للحصول على مكونات اللون المضروبة مسبقًا.
    // يتم حساب مكونات اللون المضروبة مسبقًا باستخدام الصيغ التالية:
    // red = original_red * alpha / 255;
    // green = original_green * alpha / 255;
    // blue = original_blue * alpha / 255;
    rasterImage.PremultiplyComponents = true;
    Aspose.Imaging.Color[] premultipliedColors = rasterImage.LoadPixels(rasterImage.Bounds);

    for (int i = 0; i < colors.Length; i++)
    {
        System.Console.WriteLine("Original color: {0}", colors[i].ToString());
        System.Console.WriteLine("Premultiplied color: {0}", premultipliedColors[i].ToString());
    }
}
```

### انظر أيضًا

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


