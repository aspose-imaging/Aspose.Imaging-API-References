---
title: Class PieShape
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.Shapes.PieShape class. Represents a pie shape
type: docs
weight: 11430
url: /net/aspose.imaging.shapes/pieshape/
---
## PieShape class

Represents a pie shape.

```csharp
public class PieShape : EllipseShape
```

## Constructors

| Name | Description |
| --- | --- |
| [PieShape](pieshape/#constructor)() | Initializes a new instance of the `PieShape` class. |
| [PieShape](pieshape/#constructor_1)(RectangleF, float, float) | Initializes a new instance of the `PieShape` class. |

## Properties

| Name | Description |
| --- | --- |
| override [Bounds](../../aspose.imaging.shapes/rectangleprojectedshape/bounds/) { get; } | Gets the object's bounds. |
| override [Center](../../aspose.imaging.shapes/rectangleprojectedshape/center/) { get; } | Gets the shape's center. |
| override [HasSegments](../../aspose.imaging.shapes/rectangleprojectedshape/hassegments/) { get; } | Gets a value indicating whether shape has segments. |
| [LeftBottom](../../aspose.imaging.shapes/rectangleprojectedshape/leftbottom/) { get; } | Gets the left bottom rectangle point. |
| [LeftTop](../../aspose.imaging.shapes/rectangleprojectedshape/lefttop/) { get; } | Gets the left top rectangle point. |
| [RectangleHeight](../../aspose.imaging.shapes/rectangleprojectedshape/rectangleheight/) { get; } | Gets the rectangle height. |
| [RectangleWidth](../../aspose.imaging.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | Gets the rectangle width. |
| [RightBottom](../../aspose.imaging.shapes/rectangleprojectedshape/rightbottom/) { get; } | Gets the right bottom rectangle point. |
| [RightTop](../../aspose.imaging.shapes/rectangleprojectedshape/righttop/) { get; } | Gets the right top rectangle point. |
| override [Segments](../../aspose.imaging.shapes/pieshape/segments/) { get; } | Gets the shape segments. |
| [StartAngle](../../aspose.imaging.shapes/pieshape/startangle/) { get; set; } | Gets or sets the start angle. |
| [SweepAngle](../../aspose.imaging.shapes/pieshape/sweepangle/) { get; set; } | Gets or sets the sweep angle. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.imaging.shapes/pieshape/equals/)(object) | Check if objects are equal. |
| override [GetBounds](../../aspose.imaging.shapes/rectangleprojectedshape/getbounds/)(Matrix) | Gets the object's bounds. |
| override [GetBounds](../../aspose.imaging.shapes/rectangleprojectedshape/getbounds/)(Matrix, Pen) | Gets the object's bounds. |
| override [GetHashCode](../../aspose.imaging.shapes/pieshape/gethashcode/)() | Get hash code of the current object. |
| override [Transform](../../aspose.imaging.shapes/rectangleprojectedshape/transform/)(Matrix) | Applies the specified transformation to the shape. |

## Examples

This example creates a new Image and draws a variety of shapes using Figures and GraphicsPath on the Image surface

```csharp
[C#]

//Creates an instance of BmpOptions and set its various properties            
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Create an instance of FileCreateSource and assign it as Source for the instance of BmpOptions
//Second Boolean parameter determines if the file to be created IsTemporal or not
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"c:\temp\output.bmp", false);

//Create an instance of Image 
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //Create and initialize an instance of Graphics class
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //Clear Graphics surface
    graphics.Clear(Color.Wheat);

    //Create an instance of GraphicsPath class
    Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

    //Create an instance of Figure class
    Aspose.Imaging.Figure figure1 = new Aspose.Imaging.Figure();

    //Add Shape to Figure object
    figure1.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.Imaging.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Create an instance of Figure class
    Aspose.Imaging.Figure figure2 = new Aspose.Imaging.Figure();

    //Add Shape to Figure object
    figure2.AddShape(new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.Imaging.Shapes.PolygonShape(new[] { new Aspose.Imaging.PointF(150, 10), new Aspose.Imaging.PointF(150, 200), new Aspose.Imaging.PointF(250, 300), new Aspose.Imaging.PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(200, 200))));

    //Add Figure object to GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //Draw path with Pen object of color Black
    graphics.DrawPath(new Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

    // save all changes.
    image.Save();
}
```

### See Also

* class [EllipseShape](../ellipseshape/)
* namespace [Aspose.Imaging.Shapes](../../aspose.imaging.shapes/)
* assembly [Aspose.Imaging](../../)


