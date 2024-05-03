---
title: DicomImage.BinarizeBradley
second_title: Aspose.Imaging for .NET API Reference
description: DicomImage method. Binarize images with Bradleys adaptive thresholding algorithm leveraging integral image thresholding for improved performance. Ideal for developers looking to automatically segment images based on local variations in brightness ensuring accurate object detection and extraction in varying lighting conditions
type: docs
weight: 160
url: /net/aspose.imaging.fileformats.dicom/dicomimage/binarizebradley/
---
## DicomImage.BinarizeBradley method

Binarize images with Bradley's adaptive thresholding algorithm, leveraging integral image thresholding for improved performance. Ideal for developers looking to automatically segment images based on local variations in brightness, ensuring accurate object detection and extraction in varying lighting conditions.

```csharp
public override void BinarizeBradley(double brightnessDifference, int windowSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| brightnessDifference | Double | The brightness difference between pixel and the average of an s x s window of pixels centered around this pixel. |
| windowSize | Int32 | The size of s x s window of pixels centered around this pixel |

## Examples

The following example binarizes a DICOM image with Bradley's adaptive thresholding algorithm with the specified window size. Binarized images contain only 2 colors - black and white.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Binarize the image with a brightness difference of 5. The brightness is a difference between a pixel and the average of an 10 x 10 window of pixels centered around this pixel.
    dicomImage.BinarizeBradley(5, 10);
    dicomImage.Save(dir + "sample.BinarizeBradley5_10x10.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


