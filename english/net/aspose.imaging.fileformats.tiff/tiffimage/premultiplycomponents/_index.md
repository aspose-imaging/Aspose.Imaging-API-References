---
title: TiffImage.PremultiplyComponents
second_title: Aspose.Imaging for .NET API Reference
description: TiffImage property. Indicate if components necessitate premultiplication ensuring efficient handling of visual elements. Enhance rendering processes by toggling this property streamlining graphic workflows for optimized performance
type: docs
weight: 100
url: /net/aspose.imaging.fileformats.tiff/tiffimage/premultiplycomponents/
---
## TiffImage.PremultiplyComponents property

Indicate if components necessitate premultiplication, ensuring efficient handling of visual elements. Enhance rendering processes by toggling this property, streamlining graphic workflows for optimized performance.

```csharp
public override bool PremultiplyComponents { get; set; }
```

### Property Value

`true` if components must be premultiplied; otherwise, `false`.

## Examples

The following example creates a new TIFF image, saves the specified semi-transparent pixels, then loads those pixels and gets final colors in the premultiplied form.

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
    // Save pixels for the whole image.
    image.SavePixels(image.Bounds, colors);

    // The pixels are stored in the original image in the non-premultiplied form.
    // Need to specify the corresponding option explicitly to obtain premultiplied color components.
    // The premultiplied color components are calculated by the formulas:
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

//The output will look like this:
//Original color: Color [A=127, R=255, G=0, B=0]
//Premultiplied color: Color [A=127, R=127, G=0, B=0]
//Original color: Color [A=127, R=0, G=255, B=0]
//Premultiplied color: Color [A=127, R=0, G=127, B=0]
//Original color: Color [A=127, R=0, G=0, B=255]
//Premultiplied color: Color [A=127, R=0, G=0, B=127]
//Original color: Color [A=127, R=255, G=255, B=0]
//Premultiplied color: Color [A=127, R=127, G=127, B=0]
//Original color: Color [A=127, R=255, G=0, B=255]
//Premultiplied color: Color [A=127, R=127, G=0, B=127]
//Original color: Color [A=127, R=0, G=255, B=255]
//Premultiplied color: Color [A=127, R=0, G=127, B=127]
```

### See Also

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


