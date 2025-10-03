---
title: TiffImage.AddFrame
second_title: Aspose.Imaging for .NET API Reference
description: TiffImage method. Incorporate the specified frame seamlessly into the image expanding its content and versatility. Utilize this method to enhance image composition and management empowering efficient handling of multiframe images within your application
type: docs
weight: 130
url: /net/aspose.imaging.fileformats.tiff/tiffimage/addframe/
---
## TiffImage.AddFrame method

Incorporate the specified frame seamlessly into the image, expanding its content and versatility. Utilize this method to enhance image composition and management, empowering efficient handling of multi-frame images within your application.

```csharp
public void AddFrame(TiffFrame frame)
```

| Parameter | Type | Description |
| --- | --- | --- |
| frame | TiffFrame | The frame to add. |

## Examples

The following example shows how to compose a mutlipage TIFF from individual raster images.

```csharp
[C#]

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource("c:\\temp\\multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // This is Font and Brush for drawing text on individual frames.
    Aspose.Imaging.Font font = new Aspose.Imaging.Font("Arial", 64);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.White);

    // Create 5 frames
    for (int i = 1; i <= 5; i++)
    {
        Aspose.Imaging.ImageOptions.PngOptions createPngOptions = new Aspose.Imaging.ImageOptions.PngOptions();
        createPngOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

        // Create a PNG image and draw the number of page on it.
        Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)Image.Create(createPngOptions, 100, 100);
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(pngImage);
        gr.DrawString(i.ToString(), font, brush, 10, 10);

        // Create a frame based on the PNG image.
        Aspose.Imaging.FileFormats.Tiff.TiffFrame frame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(pngImage);

        // Add the frame to the TIFF image.
        tiffImage.AddFrame(frame);
    }

    // The image was created with a single default frame. Let's remove it.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame activeFrame = tiffImage.ActiveFrame;
    tiffImage.ActiveFrame = tiffImage.Frames[1];
    tiffImage.RemoveFrame(0);

    // Don't forget to dispose the frame if you won't add it to some other TiffImage
    activeFrame.Dispose();

    tiffImage.Save();
}
```

### See Also

* class [TiffFrame](../../tiffframe/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


