---
title: GraphicsPath.AddFigures
second_title: Aspose.Imaging for .NET API Reference
description: GraphicsPath method. Adds new figures
type: docs
weight: 60
url: /net/aspose.imaging/graphicspath/addfigures/
---
## GraphicsPath.AddFigures method

Adds new figures.

```csharp
public void AddFigures(Figure[] figures)
```

| Parameter | Type | Description |
| --- | --- | --- |
| figures | Figure[] | The figures to add. |

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

* class [Figure](../../figure/)
* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)


