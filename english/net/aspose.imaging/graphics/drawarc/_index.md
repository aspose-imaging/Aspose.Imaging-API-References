---
title: DrawArc
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 170
url: /net/aspose.imaging/graphics/drawarc/
---
## Graphics.DrawArc method (1 of 4)

Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height.

```csharp
public void DrawArc(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) that determines the color, width, and style of the arc. |
| x | Single | The x-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| y | Single | The y-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| width | Single | Width of the rectangle that defines the ellipse. |
| height | Single | Height of the rectangle that defines the ellipse. |
| startAngle | Single | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweepAngle | Single | Angle in degrees measured clockwise from the *startAngle* parameter to ending point of the arc. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null. |

### See Also

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* namespace [Aspose.Imaging](../../graphics)
* assembly [Aspose.Imaging](../../../)

---

## Graphics.DrawArc method (2 of 4)

Draws an arc representing a portion of an ellipse specified by a [`RectangleF`](../../rectanglef) structure.

```csharp
public void DrawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) that determines the color, width, and style of the arc. |
| rect | RectangleF | [`RectangleF`](../../rectanglef) structure that defines the boundaries of the ellipse. |
| startAngle | Single | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweepAngle | Single | Angle in degrees measured clockwise from the *startAngle* parameter to ending point of the arc. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null |

### See Also

* class [Pen](../../pen)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* namespace [Aspose.Imaging](../../graphics)
* assembly [Aspose.Imaging](../../../)

---

## Graphics.DrawArc method (3 of 4)

Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height.

```csharp
public void DrawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) that determines the color, width, and style of the arc. |
| x | Int32 | The x-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| y | Int32 | The y-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| width | Int32 | Width of the rectangle that defines the ellipse. |
| height | Int32 | Height of the rectangle that defines the ellipse. |
| startAngle | Int32 | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweepAngle | Int32 | Angle in degrees measured clockwise from the *startAngle* parameter to ending point of the arc. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null. |

### See Also

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* namespace [Aspose.Imaging](../../graphics)
* assembly [Aspose.Imaging](../../../)

---

## Graphics.DrawArc method (4 of 4)

Draws an arc representing a portion of an ellipse specified by a [`Rectangle`](../../rectangle) structure.

```csharp
public void DrawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) that determines the color, width, and style of the arc. |
| rect | Rectangle | [`RectangleF`](../../rectanglef) structure that defines the boundaries of the ellipse. |
| startAngle | Single | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweepAngle | Single | Angle in degrees measured clockwise from the *startAngle* parameter to ending point of the arc. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null. |

### Examples

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

* class [Pen](../../pen)
* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* namespace [Aspose.Imaging](../../graphics)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
