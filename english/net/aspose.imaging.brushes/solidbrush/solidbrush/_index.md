---
title: SolidBrush.SolidBrush
second_title: Aspose.Imaging for .NET API Reference
description: SolidBrush constructor. Initializes a new instance of the SolidBrush class
type: docs
weight: 10
url: /net/aspose.imaging.brushes/solidbrush/solidbrush/
---
## SolidBrush() {#constructor}

Initializes a new instance of the [`SolidBrush`](../) class.

```csharp
public SolidBrush()
```

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

* class [SolidBrush](../)
* namespace [Aspose.Imaging.Brushes](../../solidbrush/)
* assembly [Aspose.Imaging](../../../)

---

## SolidBrush(Color) {#constructor_1}

Initializes a new instance of the [`SolidBrush`](../) class.

```csharp
public SolidBrush(Color color)
```

| Parameter | Type | Description |
| --- | --- | --- |
| color | Color | The solid brush color. |

### See Also

* struct [Color](../../../aspose.imaging/color/)
* class [SolidBrush](../)
* namespace [Aspose.Imaging.Brushes](../../solidbrush/)
* assembly [Aspose.Imaging](../../../)


