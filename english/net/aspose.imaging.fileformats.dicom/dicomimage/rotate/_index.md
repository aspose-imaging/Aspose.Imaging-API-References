---
title: DicomImage.Rotate
second_title: Aspose.Imaging for .NET API Reference
description: DicomImage method. Rotate the image around its center with this convenient method. Ideal for developers seeking to adjust image orientation dynamically ensuring optimal presentation and alignment within their applications
type: docs
weight: 280
url: /net/aspose.imaging.fileformats.dicom/dicomimage/rotate/
---
## DicomImage.Rotate method

Rotate the image around its center with this convenient method. Ideal for developers seeking to adjust image orientation dynamically, ensuring optimal presentation and alignment within their applications.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| Parameter | Type | Description |
| --- | --- | --- |
| angle | Single | The rotate angle in degrees. Positive values will rotate clockwise. |
| resizeProportionally | Boolean | if set to `true` you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only `internal` image contents are rotated. |
| backgroundColor | Color | Color of the background. |

## Examples

This example shows how to rotate all pages of a DICOM image and save them all to a multi-frame TIFF image.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a DICOM image from a file stream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "multiframe.dicom"))
{
    using (Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = new Aspose.Imaging.FileFormats.Dicom.DicomImage(stream))
    {
        // Rotate the image around the center by 60 degrees clockwise.
        // Use gray as the background color.
        dicomImage.Rotate(60, true, Aspose.Imaging.Color.Gray);

        Aspose.Imaging.ImageOptions.TiffOptions createOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
        createOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Deflate;

        // Note that if the image is colorful, it will be automatically converted to the grayscale format according to the options below
        createOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
        createOptions.BitsPerSample = new ushort[] { 8 };

        // Create an array of TIFF frames.
        // The number of the frames is equal to the number of the DJVU pages.
        Aspose.Imaging.FileFormats.Tiff.TiffFrame[] tiffFrames = new Aspose.Imaging.FileFormats.Tiff.TiffFrame[dicomImage.DicomPages.Length];

        // Save each page as an individual TIFF frame.
        foreach (Aspose.Imaging.FileFormats.Dicom.DicomPage dicomPage in dicomImage.DicomPages)
        {
            // Create a TIFF frame based on the DICOM page.
            tiffFrames[dicomPage.Index] = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(dicomPage, createOptions);
        }

        // Compose a TIFF image from the frames.
        using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(tiffFrames))
        {
            // Save to a file.
            tiffImage.Save(dir + "multiframe.tif");
        }
    }
}
```

### See Also

* struct [Color](../../../aspose.imaging/color/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


