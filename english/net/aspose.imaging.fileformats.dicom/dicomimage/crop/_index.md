---
title: Crop
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 200
url: /net/aspose.imaging.fileformats.dicom/dicomimage/crop/
---
## DicomImage.Crop method (1 of 2)

Crop the image to remove unwanted areas and focus on essential content with this simple method. Ideal for developers seeking to customize the visual composition of images, ensuring they convey the desired message effectively.

```csharp
public override void Crop(Rectangle rectangle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | Rectangle | The rectangle. |

### Examples

The following example crops a DICOM image. The cropping area is be specified via Aspose.Imaging.Rectangle.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Crop the image. The cropping area is the rectangular central area of the image.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(dicomImage.Width / 4, dicomImage.Height / 4, dicomImage.Width / 2, dicomImage.Height / 2);
    dicomImage.Crop(area);

    // Save the cropped image to PNG
    dicomImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* struct [Rectangle](../../../aspose.imaging/rectangle)
* class [DicomImage](../../dicomimage)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* assembly [Aspose.Imaging](../../../)

---

## DicomImage.Crop method (2 of 2)

Adjust the cropping area of the image by applying shifts with this versatile method. Perfect for developers who need precise control over the cropping process, ensuring that important details are retained while eliminating unnecessary elements.

```csharp
public override void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Parameter | Type | Description |
| --- | --- | --- |
| leftShift | Int32 | The left shift. |
| rightShift | Int32 | The right shift. |
| topShift | Int32 | The top shift. |
| bottomShift | Int32 | The bottom shift. |

### Examples

The following example crops a DICOM image. The cropping area is specified via Left, Top, Right, Bottom margins.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Crop again. Set a margin of 10% of the image size.
    int horizontalMargin = dicomImage.Width / 10;
    int verticalMargin = dicomImage.Height / 10;
    dicomImage.Crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Save the cropped image to PNG.
    dicomImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [DicomImage](../../dicomimage)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
