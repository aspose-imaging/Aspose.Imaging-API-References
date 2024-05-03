---
title: PngImage.HasBackgroundColor
second_title: Aspose.Imaging for .NET API Reference
description: PngImage property. Retrieves a boolean value indicating whether the image has a background color. This property is useful for applications needing to determine if an image includes a background color which can be important for various processing tasks such as compositing rendering or exporting
type: docs
weight: 60
url: /net/aspose.imaging.fileformats.png/pngimage/hasbackgroundcolor/
---
## PngImage.HasBackgroundColor property

Retrieves a boolean value indicating whether the image has a background color. This property is useful for applications needing to determine if an image includes a background color, which can be important for various processing tasks such as compositing, rendering, or exporting.

```csharp
public override bool HasBackgroundColor { get; set; }
```

## Examples

The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.

```csharp
[C#]

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource("c:\\temp\\transparent.png", false);
createOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.Truecolor;

// Create a TrueColor PNG image of 100x100 px.
using (Aspose.Imaging.Image image = Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)image;
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(pngImage);

    // All red pixels will be considered as fully transparent.
    pngImage.TransparentColor = Aspose.Imaging.Color.Red;
    pngImage.HasTransparentColor = true;

    // All transparent pixels will have a background color.
    pngImage.BackgroundColor = Aspose.Imaging.Color.Green;
    pngImage.HasBackgroundColor = true;

    // Fill the entire image with white color.
    gr.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.White), pngImage.Bounds);

    // Fill the top-left quarter of the image with the transparent color.
    // This makes the top-left quarter colored in the background color.
    Rectangle rect = new Rectangle(0, 0, pngImage.Width / 2, pngImage.Height / 2);
    gr.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red), rect);

    pngImage.Save();
}
```

### See Also

* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)


