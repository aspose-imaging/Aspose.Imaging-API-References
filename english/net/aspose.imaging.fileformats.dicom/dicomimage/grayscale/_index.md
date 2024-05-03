---
title: DicomImage.Grayscale
second_title: Aspose.Imaging for .NET API Reference
description: DicomImage method. Easily transform images into their grayscale representation simplifying visual analysis and processing tasks. Perfect for developers seeking to enhance image clarity reduce complexity and facilitate efficient grayscalebased algorithms for diverse applications
type: docs
weight: 230
url: /net/aspose.imaging.fileformats.dicom/dicomimage/grayscale/
---
## DicomImage.Grayscale method

Easily transform images into their grayscale representation, simplifying visual analysis and processing tasks. Perfect for developers seeking to enhance image clarity, reduce complexity, and facilitate efficient grayscale-based algorithms for diverse applications.

```csharp
public override void Grayscale()
```

## Examples

The following example transforms a colored DICOM image to its grayscale representation. Grayscale images are composed exclusively of shades of gray and carry only intensity information.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    dicomImage.Grayscale();
    dicomImage.Save(dir + "sample.Grayscale.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


