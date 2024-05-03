---
title: PngImage.HasAlpha
second_title: Aspose.Imaging for .NET API Reference
description: PngImage property. Returns a boolean value indicating whether the image has an alpha channel which determines its transparency. This property is useful for applications that need to handle transparency allowing developers to determine whether additional processing is required to handle transparent areas in the image
type: docs
weight: 50
url: /net/aspose.imaging.fileformats.png/pngimage/hasalpha/
---
## PngImage.HasAlpha property

Returns a boolean value indicating whether the image has an alpha channel, which determines its transparency. This property is useful for applications that need to handle transparency, allowing developers to determine whether additional processing is required to handle transparent areas in the image.

```csharp
public override bool HasAlpha { get; }
```

### Property Value

`true` if this instance has alpha; otherwise, `false`.

## Examples

The following example shows how to check if a PNG image supports alpha-channel.

```csharp
[C#]

// Get all supported PNG color types.
System.Array colorTypes = System.Enum.GetValues(typeof(Aspose.Imaging.FileFormats.Png.PngColorType));

foreach (Aspose.Imaging.FileFormats.Png.PngColorType colorType in colorTypes)
{
    Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    createOptions.Source = new Sources.StreamSource(new System.IO.MemoryStream());
    createOptions.ColorType = colorType;

    using (Aspose.Imaging.Image image = Image.Create(createOptions, 100, 100))
    {
        Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)image;

        if (pngImage.HasAlpha)
        {
            System.Console.WriteLine("A {0} PNG image supports alpha channel", createOptions.ColorType);
        }
        else
        {
            System.Console.WriteLine("A {0} PNG image doesn't support alpha channel", createOptions.ColorType);
        }
    }
}

// The output looks like this:
// A Grayscale PNG image doesn't support alpha channel
// A Truecolor PNG image doesn't support alpha channel
// A IndexedColor PNG image doesn't support alpha channel
// A GrayscaleWithAlpha PNG image supports alpha channel
// A TruecolorWithAlpha PNG image supports alpha channel
```

### See Also

* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)


