---
title: EmfRecorderGraphics2D.FromEmfImage
second_title: Aspose.Imaging for .NET API Reference
description: EmfRecorderGraphics2D method. Gets an instance of the EmfRecorderGraphics2D containing all records from the Emf image
type: docs
weight: 20
url: /net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/fromemfimage/
---
## EmfRecorderGraphics2D.FromEmfImage method

Gets an instance of the [`EmfRecorderGraphics2D`](../) containing all records from the Emf image.

```csharp
public static EmfRecorderGraphics2D FromEmfImage(EmfImage emfImage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| emfImage | EmfImage | The Emf image to read records from. |

### Return Value

An instance of the [`EmfRecorderGraphics2D`](../)

## Examples

This example shows how to load a EMF image from a file and draw a text string over it.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D graphics =
        Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D.FromEmfImage(emfImage);

    // First, get the image size
    int width = emfImage.Width;
    int height = emfImage.Height;

    // Second, calculate a transformation to put a text string along the main diagonal of the image -
    // from the upper-left to the bootom-right corner.
    float emFontSize = 96f;
    float d = (float)System.Math.Sqrt(width * width + height * height);
    float scaleFactor = d / (emFontSize * 5f);

    float tan = ((float)height) / width;                
    double radians = System.Math.Atan(tan);
    double degrees = (180 * radians) / System.Math.PI;

    Aspose.Imaging.Matrix transform = new Aspose.Imaging.Matrix();
    transform.Rotate((float)degrees);
    transform.Scale(scaleFactor, scaleFactor);

    // Then, set the transform.
    graphics.SetTransform(transform);

    // Finally, put a watermark (text string of pink color) along the main diagonal.
    graphics.DrawString("WATERMARK", new Aspose.Imaging.Font("Courier New", emFontSize), Aspose.Imaging.Color.LightPink, 0, 0/*, (float)degrees*/);

    // Save the image with watermark to another EMF file.
    using (Aspose.Imaging.FileFormats.Emf.EmfImage scaledEmfImage = graphics.EndRecording())
    {
        scaledEmfImage.Save(dir + "test.scaled.emf");
    }
}
```

### See Also

* class [EmfImage](../../../aspose.imaging.fileformats.emf/emfimage/)
* class [EmfRecorderGraphics2D](../)
* namespace [Aspose.Imaging.FileFormats.Emf.Graphics](../../emfrecordergraphics2d/)
* assembly [Aspose.Imaging](../../../)


