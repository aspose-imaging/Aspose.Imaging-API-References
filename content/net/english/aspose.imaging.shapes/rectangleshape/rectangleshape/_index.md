---
title: RectangleShape
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 10
url: /aspose.imaging.shapes/rectangleshape/rectangleshape/
---
## RectangleShape constructor (1 of 2)

Initializes a new instance of the [`RectangleShape`](../../rectangleshape) class.

```csharp
public RectangleShape()
```

### See Also

* class [RectangleShape](../../rectangleshape)
* namespace [Aspose.Imaging.Shapes](../../rectangleshape)
* assembly [Aspose.Imaging](../../../)

---

## RectangleShape constructor (2 of 2)

Initializes a new instance of the [`RectangleShape`](../../rectangleshape) class.

```csharp
public RectangleShape(RectangleF rectangle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | RectangleF | The rectangle. |

### Examples

This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end DrawPath method exposed by Graphics class is called to render the paths on surface.

```csharp
[C#]

//Create an instance of FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    //Create an instance of TiffOptions and set its various properties
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    //Set the source for the instance of ImageOptions
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Create an instance of Image 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        //Create and initialize an instance of Graphics class
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Clear Graphics surface
        graphics.Clear(Color.Wheat);

        //Create an instance of GraphicsPath class
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        //Create an instance of Figure class
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        //Add Shapes to Figure object
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        //Add Figure object to GraphicsPath
        graphicspath.AddFigure(figure);

        //Draw path with Pen object of color Black
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // save all changes.
        image.Save();
    }
}
```

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

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* class [RectangleShape](../../rectangleshape)
* namespace [Aspose.Imaging.Shapes](../../rectangleshape)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
