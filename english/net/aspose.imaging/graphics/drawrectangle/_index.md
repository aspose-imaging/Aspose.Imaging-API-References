---
title: Graphics.DrawRectangle
second_title: Aspose.Imaging for .NET API Reference
description: Graphics method. Draws a rectangle specified by a RectangleF structure
type: docs
weight: 310
url: /net/aspose.imaging/graphics/drawrectangle/
---
## DrawRectangle(Pen, RectangleF) {#drawrectangle_1}

Draws a rectangle specified by a [`RectangleF`](../../rectanglef/) structure.

```csharp
public void DrawRectangle(Pen pen, RectangleF rect)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | A [`Pen`](../../pen/) that determines the color, width, and style of the rectangle. |
| rect | RectangleF | A [`RectangleF`](../../rectanglef/) structure that represents the rectangle to draw. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null. |

### See Also

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawRectangle(Pen, Rectangle) {#drawrectangle}

Draws a rectangle specified by a [`Rectangle`](../../rectangle/) structure.

```csharp
public void DrawRectangle(Pen pen, Rectangle rect)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | A [`Pen`](../../pen/) that determines the color, width, and style of the rectangle. |
| rect | Rectangle | A [`Rectangle`](../../rectangle/) structure that represents the rectangle to draw. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null. |

## Examples

This example uses Graphics class to create primitive shapes on the Image surface. To demonstrate the operation, the example creates a new Image in PNG format and draw primitive shapes on Image surface using Draw methods exposed by Graphics class

```csharp
[C#]

//Creates an instance of FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //Create an instance of PngOptions and set its various properties
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //Set the Source for PngOptions
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Create an instance of Image 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //Create and initialize an instance of Graphics class
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Clear Graphics surface
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        //Draw an Arc by specifying the Pen object having Black color, 
        //a Rectangle surrounding the Arc, Start Angle and Sweep Angle
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        //Draw a Bezier by specifying the Pen object having Blue color and co-ordinate Points.
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //Draw a Curve by specifying the Pen object having Green color and an array of Points
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //Draw an Ellipse using the Pen object and a surrounding Rectangle
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //Draw a Line 
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        //Draw a Pie segment
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        //Draw a Polygon by specifying the Pen object having Red color and an array of Points
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //Draw a Rectangle
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //Create a SolidBrush object and set its various properties
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //Draw a String using the SolidBrush object and Font, at specific Point
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // save all changes.
        image.Save();
    }
}
```

### See Also

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawRectangle(Pen, float, float, float, float) {#drawrectangle_3}

Draws a rectangle specified by a coordinate pair, a width, and a height.

```csharp
public void DrawRectangle(Pen pen, float x, float y, float width, float height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | A [`Pen`](../../pen/) that determines the color, width, and style of the rectangle. |
| x | Single | The x-coordinate of the upper-left corner of the rectangle to draw. |
| y | Single | The y-coordinate of the upper-left corner of the rectangle to draw. |
| width | Single | The width of the rectangle to draw. |
| height | Single | The height of the rectangle to draw. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null. |

### See Also

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawRectangle(Pen, int, int, int, int) {#drawrectangle_2}

Draws a rectangle specified by a coordinate pair, a width, and a height.

```csharp
public void DrawRectangle(Pen pen, int x, int y, int width, int height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and style of the rectangle. |
| x | Int32 | The x-coordinate of the upper-left corner of the rectangle to draw. |
| y | Int32 | The y-coordinate of the upper-left corner of the rectangle to draw. |
| width | Int32 | Width of the rectangle to draw. |
| height | Int32 | Height of the rectangle to draw. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null. |

### See Also

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)


