---
title: DicomImage.ResizeWidthProportionally
second_title: Aspose.Imaging for .NET API Reference
description: DicomImage method. Adjust the width of the image while maintaining its aspect ratio with this convenient method. Ideal for developers seeking to resize images proportionally ensuring consistent and visually appealing results across different display environment
type: docs
weight: 270
url: /net/aspose.imaging.fileformats.dicom/dicomimage/resizewidthproportionally/
---
## DicomImage.ResizeWidthProportionally method

Adjust the width of the image while maintaining its aspect ratio with this convenient method. Ideal for developers seeking to resize images proportionally, ensuring consistent and visually appealing results across different display environment.

```csharp
public override void ResizeWidthProportionally(int newWidth, ResizeType resizeType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | The new width. |
| resizeType | ResizeType | Type of the resize. |

## Examples

This example loads a DICOM image and resizes it proportionally using various resizing methods. Only the width is specified, the height is calculated automatically.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // Scale up by 2 times using Nearest Neighbour resampling.
    image.ResizeWidthProportionally(image.Width* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with the default options.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // Scale down by 2 times using Nearest Neighbour resampling.
    image.ResizeWidthProportionally(image.Width / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with the default options.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // Scale up by 2 times using Bilinear resampling.
    image.ResizeWidthProportionally(image.Width* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Save to PNG with the default options.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // Scale down by 2 times using Bilinear resampling.
    image.ResizeWidthProportionally(image.Width / 2, Aspose.Imaging.ResizeType.BilinearResample);                

    // Save to PNG with the default options.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


