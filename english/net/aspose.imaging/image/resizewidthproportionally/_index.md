---
title: Image.ResizeWidthProportionally
second_title: Aspose.Imaging for .NET API Reference
description: Image method. Resizes the width proportionally. The default NearestNeighbourResample is used
type: docs
weight: 280
url: /net/aspose.imaging/image/resizewidthproportionally/
---
## ResizeWidthProportionally(int) {#resizewidthproportionally}

Resizes the width proportionally. The default NearestNeighbourResample is used.

```csharp
public void ResizeWidthProportionally(int newWidth)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | The new width. |

### See Also

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## ResizeWidthProportionally(int, ResizeType) {#resizewidthproportionally_2}

Resizes the width proportionally.

```csharp
public virtual void ResizeWidthProportionally(int newWidth, ResizeType resizeType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | The new width. |
| resizeType | ResizeType | Type of the resize. |

## Examples

This example loads an image and resizes it proportionally using various resizing methods. Only the width is specified, the height is calculated automatically.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Scale up by 2 times using Nearest Neighbour resampling.
    image.ResizeWidthProportionally(image.Width* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Scale down by 2 times using Nearest Neighbour resampling.
    image.ResizeWidthProportionally(image.Width / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "downsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Scale up by 2 times using Bilinear resampling.
    image.ResizeWidthProportionally(image.Width* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Scale down by 2 times using Bilinear resampling.
    image.ResizeWidthProportionally(image.Width / 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "downsample.bilinear.gif");
}
```

### See Also

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## ResizeWidthProportionally(int, ImageResizeSettings) {#resizewidthproportionally_1}

Resizes the width proportionally.

```csharp
public virtual void ResizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | The new width. |
| settings | ImageResizeSettings | The image resize settings. |

### See Also

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


