---
title: DjvuImage.Crop
second_title: Aspose.Imaging for .NET API Reference
description: DjvuImage method. Crop trims your image to focus on specific details or remove unwanted elements enhancing its composition and visual impact. Whether youre adjusting photos for social media creating website banners or designing print materials this tool helps you refine your images with precision and clarity
type: docs
weight: 220
url: /net/aspose.imaging.fileformats.djvu/djvuimage/crop/
---
## Crop(Rectangle) {#crop}

"Crop" trims your image to focus on specific details or remove unwanted elements, enhancing its composition and visual impact. Whether you're adjusting photos for social media, creating website banners, or designing print materials, this tool helps you refine your images with precision and clarity.

```csharp
public override void Crop(Rectangle rectangle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | Rectangle | The rectangle. |

## Examples

The following example crops a DJVU image. The cropping area is be specified via Aspose.Imaging.Rectangle.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // Crop the image. The cropping area is the rectangular central area of the image.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(djvuImage.Width / 4, djvuImage.Height / 4, djvuImage.Width / 2, djvuImage.Height / 2);
    djvuImage.Crop(area);

    // Save the cropped image to PNG
    djvuImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Crop with shifts allows you to precisely adjust the position and dimensions of the cropped area within an image. This feature is invaluable for refining compositions, aligning elements, and emphasizing focal points in your visuals. By incorporating shifts into the cropping process, you can achieve pixel-perfect precision and fine-tune the framing of your images with ease.

```csharp
public override void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Parameter | Type | Description |
| --- | --- | --- |
| leftShift | Int32 | The left shift. |
| rightShift | Int32 | The right shift. |
| topShift | Int32 | The top shift. |
| bottomShift | Int32 | The bottom shift. |

### See Also

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


