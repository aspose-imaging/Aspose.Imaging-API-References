---
title: AddBlock
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 80
url: /net/aspose.imaging.fileformats.webp/webpimage/addblock/
---
## WebPImage.AddBlock method

Adds a new Webp block.

```csharp
public void AddBlock(IFrame block)
```

| Parameter | Type | Description |
| --- | --- | --- |
| block | IFrame | The Webp block to add. |

### Examples

This example shows how to create a multi-frame animated WebP image with the specified options.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
createOptions.AnimBackgroundColor = (uint)Aspose.Imaging.Color.Gray.ToArgb();

// The default frame plus 36 + 36 additional frames.
createOptions.AnimLoopCount = 36 + 36 + 1;

// Create a WebP image of 100x100 px.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    // The first circle is red
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // The second circle is black
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Gradually inscrease the angle of the red arc shape.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush1, block.Bounds, 0, angle);

        webPImage.AddBlock(block);
    }

    // Gradually inscrease the angle of the black arc and wipe out the red arc.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);

        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush2, block.Bounds, 0, angle);
        graphics.FillPie(brush1, block.Bounds, angle, 360 - angle);

        webPImage.AddBlock(block);
    }

    // Save to a WebP file
    webPImage.Save(dir + "output.webp");
}
```

### See Also

* interface [IFrame](../../iframe)
* class [WebPImage](../../webpimage)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
