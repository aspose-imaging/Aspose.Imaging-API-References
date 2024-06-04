---
title: DicomImage.BinarizeFixed
second_title: Aspose.Imaging for .NET API Reference
description: DicomImage method. Easily convert the image into a binary format using a predefined threshold with this straightforward method. Ideal for developers looking to simplify image processing tasks by segmenting the image into foreground and background components based on specified intensity levels
type: docs
weight: 160
url: /net/aspose.imaging.fileformats.dicom/dicomimage/binarizefixed/
---
## DicomImage.BinarizeFixed method

Easily convert the image into a binary format using a predefined threshold with this straightforward method. Ideal for developers looking to simplify image processing tasks by segmenting the image into foreground and background components based on specified intensity levels.

```csharp
public override void BinarizeFixed(byte threshold)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threshold | Byte | Threshold value. If corresponding gray value of a pixel is greater than threshold, a value of 255 will be assigned to it, 0 otherwise. |

## Examples

The following example binarizes a DICOM image with the predefined threshold. Binarized images contain only 2 colors - black and white.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Binarize the image with a threshold value of 127.
    // If a corresponding gray value of a pixel is greater than 127, a value of 255 will be assigned to it, 0 otherwise.
    dicomImage.BinarizeFixed(127);
    dicomImage.Save(dir + "sample.BinarizeFixed.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


