---
title: RasterImage.PremultiplyComponents
second_title: Aspose.Imaging for .NET API Reference
description: RasterImage property. Gets or sets a value indicating whether the image components must be premultiplied
type: docs
weight: 60
url: /net/aspose.imaging/rasterimage/premultiplycomponents/
---
## RasterImage.PremultiplyComponents property

Gets or sets a value indicating whether the image components must be premultiplied.

```csharp
public virtual bool PremultiplyComponents { get; set; }
```

### Property Value

`true` if the image components must be premultiplied; otherwise, `false`.

## Examples

The following example creates a new raster image, saves the specified semi-transparent pixels, then loads those pixels and gets final colors in the premultiplied form.

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

    // Save pixels for the whole image.
    rasterImage.SavePixels(rasterImage.Bounds, colors);

    // The pixels are stored in the original image in the non-premultiplied form.
    // Need to specify the corresponding option explicitly to obtain premultiplied color components.
    // The premultiplied color components are calculated by the formulas:
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

### See Also

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


