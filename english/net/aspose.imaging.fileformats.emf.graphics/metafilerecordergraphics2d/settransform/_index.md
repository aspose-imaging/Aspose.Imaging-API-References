---
title: MetafileRecorderGraphics2D.SetTransform
second_title: Aspose.Imaging for .NET API Reference
description: MetafileRecorderGraphics2D method. Sets the transform
type: docs
weight: 290
url: /net/aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/settransform/
---
## MetafileRecorderGraphics2D.SetTransform method

Sets the transform.

```csharp
public void SetTransform(Matrix transform)
```

| Parameter | Type | Description |
| --- | --- | --- |
| transform | Matrix | The new transform matrix. |

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

* class [Matrix](../../../aspose.imaging/matrix/)
* class [MetafileRecorderGraphics2D](../)
* namespace [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d/)
* assembly [Aspose.Imaging](../../../)


