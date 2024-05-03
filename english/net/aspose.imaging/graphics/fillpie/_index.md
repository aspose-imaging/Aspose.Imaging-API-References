---
title: Graphics.FillPie
second_title: Aspose.Imaging for .NET API Reference
description: Graphics method. Fills the interior of a pie section defined by an ellipse specified by a RectangleF structure and two radial lines
type: docs
weight: 380
url: /net/aspose.imaging/graphics/fillpie/
---
## FillPie(Brush, Rectangle, float, float) {#fillpie}

Fills the interior of a pie section defined by an ellipse specified by a [`RectangleF`](../../rectanglef/) structure and two radial lines.

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) that determines the characteristics of the fill. |
| rect | Rectangle | [`Rectangle`](../../rectangle/) structure that represents the bounding rectangle that defines the ellipse from which the pie section comes. |
| startAngle | Single | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweepAngle | Single | Angle in degrees measured clockwise from the *startAngle* parameter to the second side of the pie section. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* is null. |

## Examples

The following example shows how to compose an animated GIF image from individual GIF blocks.

```csharp
[C#]

string dir = "c:\\temp\\";

// Create a GIF image 100 x 100 px.
// The first block is fully black by default.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // The first circle is red
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // The second circle is black
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Gradually inscrease the angle of the red arc shape.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // Gradually inscrease the angle of the black arc and wipe out the red arc.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush2, block.Bounds, 0, angle);
        gr.FillPie(brush1, block.Bounds, angle, 360 - angle);

        gifImage.AddBlock(block);
    }

    gifImage.Save(dir + "animated_radar.gif");
}
```

### See Also

* class [Brush](../../brush/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

Fills the interior of a pie section defined by an ellipse specified by a [`RectangleF`](../../rectanglef/) structure and two radial lines.

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) that determines the characteristics of the fill. |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) structure that represents the bounding rectangle that defines the ellipse from which the pie section comes. |
| startAngle | Single | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweepAngle | Single | Angle in degrees measured clockwise from the *startAngle* parameter to the second side of the pie section. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* is null. |

### See Also

* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines.

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) that determines the characteristics of the fill. |
| x | Single | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| y | Single | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| width | Single | Width of the bounding rectangle that defines the ellipse from which the pie section comes. |
| height | Single | Height of the bounding rectangle that defines the ellipse from which the pie section comes. |
| startAngle | Single | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweepAngle | Single | Angle in degrees measured clockwise from the *startAngle* parameter to the second side of the pie section. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* is null. |

### See Also

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines.

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) that determines the characteristics of the fill. |
| x | Int32 | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| y | Int32 | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| width | Int32 | Width of the bounding rectangle that defines the ellipse from which the pie section comes. |
| height | Int32 | Height of the bounding rectangle that defines the ellipse from which the pie section comes. |
| startAngle | Int32 | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweepAngle | Int32 | Angle in degrees measured clockwise from the *startAngle* parameter to the second side of the pie section. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* is null. |

### See Also

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)


