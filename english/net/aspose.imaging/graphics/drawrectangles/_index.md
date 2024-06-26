---
title: Graphics.DrawRectangles
second_title: Aspose.Imaging for .NET API Reference
description: Graphics method. Draws a series of rectangles specified by RectangleF structures
type: docs
weight: 320
url: /net/aspose.imaging/graphics/drawrectangles/
---
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

Draws a series of rectangles specified by [`RectangleF`](../../rectanglef/) structures.

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and style of the outlines of the rectangles. |
| rects | RectangleF[] | Array of [`RectangleF`](../../rectanglef/) structures that represent the rectangles to draw. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null. -or- *rects* is null. |

### See Also

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

Draws a series of rectangles specified by [`Rectangle`](../../rectangle/) structures.

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and style of the outlines of the rectangles. |
| rects | Rectangle[] | Array of [`Rectangle`](../../rectangle/) structures that represent the rectangles to draw. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null. -or- *rects* is null. |

## Examples

This example shows the creation and usage Pen objects. The example creates a new Image and draw Rectangles on Image surface.

```csharp
[C#]

//Create an instance of BmpOptions and set its various properties
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Create an instance of FileCreateSource and assign it as Source for the instance of BmpOptions
//Second Boolean parameter determines if the file to be created IsTemporal or not
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\sample.bmp", false);

//Create an instance of Image at specified Path
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //Create an instance of Graphics and initialize it with Image object
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //Clear the Graphics sutface with White Color
    graphics.Clear(Aspose.Imaging.Color.White);

    //Create an instance of Pen with color Red and width 5
    Aspose.Imaging.Pen pen = new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 5f);

    //Create an instance of HatchBrush and set its properties
    Aspose.Imaging.Brushes.HatchBrush brush = new Aspose.Imaging.Brushes.HatchBrush();
    brush.BackgroundColor = Aspose.Imaging.Color.Wheat;
    brush.ForegroundColor = Aspose.Imaging.Color.Red;

    //Create an instance of Pen
    //initialize it with HatchBrush object and width
    Aspose.Imaging.Pen brusedpen = new Pen(brush, 5);

    //Draw Rectangles by specifying Pen object
    graphics.DrawRectangles(pen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(210, 210), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 310), new Aspose.Imaging.Size(100, 100))
    });

    //Draw Rectangles by specifying Pen object
    graphics.DrawRectangles(brusedpen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 310), new Aspose.Imaging.Size(100, 100))
    });

    // save all changes.
    image.Save();
}
```

### See Also

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)


