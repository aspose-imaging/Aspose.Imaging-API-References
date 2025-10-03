---
title: TiffImage.RemoveFrame
second_title: Aspose.Imaging for .NET API Reference
description: TiffImage method. Effortlessly eliminate the frame identified by its index from the image sequence streamlining frame management within your application. Integrate this functionality to enhance efficiency and precision in frame manipulation facilitating seamless organization and presentation of image content
type: docs
weight: 300
url: /net/aspose.imaging.fileformats.tiff/tiffimage/removeframe/
---
## RemoveFrame(int) {#removeframe}

Effortlessly eliminate the frame identified by its index from the image sequence, streamlining frame management within your application. Integrate this functionality to enhance efficiency and precision in frame manipulation, facilitating seamless organization and presentation of image content.

```csharp
public TiffFrame RemoveFrame(int index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Index of frame to be removed. |

### Return Value

The removed frame.

## Remarks

Note: do not forget to Dispose the frame if you will not add it to some other TiffImage.

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

---

## RemoveFrame(TiffFrame) {#removeframe_1}

Efficiently remove the specified frame from the image sequence, facilitating streamlined frame management within your application. Integrate this functionality to enhance precision and flexibility in frame manipulation, ensuring seamless organization and presentation of image content.

```csharp
public void RemoveFrame(TiffFrame frame)
```

| Parameter | Type | Description |
| --- | --- | --- |
| frame | TiffFrame | The frame to remove. |

## Remarks

Note: do not forget to Dispose the frame if you will not add it to some other TiffImage.

### See Also

* class [TiffFrame](../../tiffframe/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


