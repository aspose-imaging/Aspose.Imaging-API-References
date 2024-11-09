---
title: DicomImage.Save
second_title: Aspose.Imaging for .NET API Reference
description: DicomImage method. Easily save your image data to a specified stream in the desired file format using this convenient method. Whether youre working with JPEG PNG or another format this function ensures that your image data is saved efficiently and accurately making it ideal for developers looking to streamline their filesaving processes
type: docs
weight: 300
url: /net/aspose.imaging.fileformats.dicom/dicomimage/save/
---
## DicomImage.Save method

Easily save your image data to a specified stream in the desired file format using this convenient method. Whether you're working with JPEG, PNG, or another format, this function ensures that your image data is saved efficiently and accurately, making it ideal for developers looking to streamline their file-saving processes.

```csharp
public override void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to save the image's data to. |
| optionsBase | ImageOptionsBase | The save options. |
| boundsRectangle | Rectangle | The destination image bounds rectangle. Set the empty rectangle for use sourse bounds. |

## Examples

The following example loads a DICOM image from a file, then saves the image to a PNG file stream.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width / 2, image.Height / 2);
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "output.png", System.IO.FileMode.Create))
    {
        // Save the upper-left quarter of the image to a file stream.
        image.Save(outputStream, saveOptions, bounds);
    }
}
```

### See Also

* class [ImageOptionsBase](../../../aspose.imaging/imageoptionsbase/)
* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


