---
title: DicomImage.ResizeHeightProportionally
second_title: Aspose.Imaging for .NET API Reference
description: DicomImage method. Adjust the height of the image while maintaining its aspect ratio with this userfriendly method. Perfect for developers seeking to dynamically resize images while preserving their proportions ensuring optimal display and usability in their applications
type: docs
weight: 250
url: /net/aspose.imaging.fileformats.dicom/dicomimage/resizeheightproportionally/
---
## DicomImage.ResizeHeightProportionally method

Adjust the height of the image while maintaining its aspect ratio with this user-friendly method. Perfect for developers seeking to dynamically resize images while preserving their proportions, ensuring optimal display and usability in their applications.

```csharp
public override void ResizeHeightProportionally(int newHeight, ResizeType resizeType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newHeight | Int32 | The new height. |
| resizeType | ResizeType | Type of the resize. |

## Examples

This example loads a DICOM image and resizes it proportionally using various resizing methods. Only the height is specified, the width is calculated automatically.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // Scale up by 2 times using Nearest Neighbour resampling.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
        
    // Save to PNG with the default options.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // Scale down by 2 times using Nearest Neighbour resampling.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with the default options.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // Scale up by 2 times using Bilinear resampling.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
        
    // Save to PNG with the default options.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // Scale down by 2 times using Bilinear resampling.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Save to PNG with the default options.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


