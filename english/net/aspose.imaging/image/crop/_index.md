---
title: Image.Crop
second_title: Aspose.Imaging for .NET API Reference
description: Image method. Crops the specified rectangle
type: docs
weight: 210
url: /net/aspose.imaging/image/crop/
---
## Crop(Rectangle) {#crop}

Crops the specified rectangle.

```csharp
public virtual void Crop(Rectangle rectangle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | Rectangle | The rectangle. |

## Examples

The following example crops a raster image. The cropping area is be specified via Aspose.Imaging.Rectangle.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    // Crop the image. The cropping area is the rectangular central area of the image.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    image.Crop(area);

    // Save the cropped image to PNG
    image.Save(dir + "sample.Crop.png");
}
```

### See Also

* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Crop image with shifts.

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Parameter | Type | Description |
| --- | --- | --- |
| leftShift | Int32 | The left shift. |
| rightShift | Int32 | The right shift. |
| topShift | Int32 | The top shift. |
| bottomShift | Int32 | The bottom shift. |

## Examples

The following example crops a raster image. The cropping area is specified via Left, Top, Right, Bottom margins.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    // Crop again. Set a margin of 10% of the image size.
    int horizontalMargin = rasterImage.Width / 10;
    int verticalMargin = rasterImage.Height / 10;
    image.Crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Save the cropped image to PNG.
    image.Save(dir + "sample.Crop.png");
}
```

### See Also

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


