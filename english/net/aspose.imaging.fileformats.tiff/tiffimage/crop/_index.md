---
title: TiffImage.Crop
second_title: Aspose.Imaging for .NET API Reference
description: TiffImage method. Crop the image using a specified rectangular region allowing precise selection of desired content. Integrate this method into your image processing workflow to efficiently remove unwanted areas and focus on essential details enhancing the overall clarity and composition of the image
type: docs
weight: 230
url: /net/aspose.imaging.fileformats.tiff/tiffimage/crop/
---
## Crop(Rectangle) {#crop}

Crop the image using a specified rectangular region, allowing precise selection of desired content. Integrate this method into your image processing workflow to efficiently remove unwanted areas and focus on essential details, enhancing the overall clarity and composition of the image.

```csharp
public override void Crop(Rectangle rectangle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | Rectangle | The rectangle. |

## Examples

The following example crops a TIFF image. The cropping area is be specified via Aspose.Imaging.Rectangle.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Crop the image. The cropping area is the rectangular central area of the image.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(tiffImage.Width / 4, tiffImage.Height / 4, tiffImage.Width / 2, tiffImage.Height / 2);
    tiffImage.Crop(area);

    // Save the cropped image to PNG
    tiffImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Perform cropping on the image by specifying shifts in the left, right, top, and bottom directions. This method enables precise selection of the desired portion of the image, facilitating efficient removal of unwanted areas and focusing on essential content. Integrate this functionality into your image processing pipeline to enhance clarity and composition as needed within your application.

```csharp
public override void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Parameter | Type | Description |
| --- | --- | --- |
| leftShift | Int32 | The left shift. |
| rightShift | Int32 | The right shift. |
| topShift | Int32 | The top shift. |
| bottomShift | Int32 | The bottom shift. |

## Examples

The following example crops a TIFF image. The cropping area is specified via Left, Top, Right, Bottom margins.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Crop again. Set a margin of 10% of the image size.
    int horizontalMargin = tiffImage.Width / 10;
    int verticalMargin = tiffImage.Height / 10;
    tiffImage.Crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Save the cropped image to PNG.
    tiffImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


