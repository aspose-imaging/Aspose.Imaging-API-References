---
title: GraphicsPath
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 9440
url: /net/aspose.imaging/graphicspath/
---
## GraphicsPath class

Represents a series of connected lines and curves. This class cannot be inherited.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Constructors

| Name | Description |
| --- | --- |
| [GraphicsPath](graphicspath)() | Initializes a new instance of the [`GraphicsPath`](../graphicspath) class. |
| [GraphicsPath](graphicspath)(Figure[]) | Initializes a new instance of the [`GraphicsPath`](../graphicspath) class. |
| [GraphicsPath](graphicspath)(FillMode) | Initializes a new instance of the [`GraphicsPath`](../graphicspath) class. |
| [GraphicsPath](graphicspath)(Figure[], FillMode) | Initializes a new instance of the [`GraphicsPath`](../graphicspath) class. |

## Properties

| Name | Description |
| --- | --- |
| override [Bounds](../../aspose.imaging/graphicspath/bounds) { get; } | Gets or sets the object's bounds. |
| [Figures](../../aspose.imaging/graphicspath/figures) { get; } | Gets the path figures. |
| [FillMode](../../aspose.imaging/graphicspath/fillmode) { get; set; } | Gets or sets a [`FillMode`](../fillmode) enumeration that determines how the interiors of shapes in this [`GraphicsPath`](../graphicspath) are filled. |

## Methods

| Name | Description |
| --- | --- |
| [AddFigure](../../aspose.imaging/graphicspath/addfigure)(Figure) | Adds a new figure. |
| [AddFigures](../../aspose.imaging/graphicspath/addfigures)(Figure[]) | Adds new figures. |
| [AddPath](../../aspose.imaging/graphicspath/addpath)(GraphicsPath) | Appends the specified [`GraphicsPath`](../graphicspath) to this path. |
| [AddPath](../../aspose.imaging/graphicspath/addpath)(GraphicsPath, bool) | Appends the specified [`GraphicsPath`](../graphicspath) to this path. |
| [DeepClone](../../aspose.imaging/graphicspath/deepclone)() | Performs a deep clone of this graphics path. |
| override [Equals](../../aspose.imaging/graphicspath/equals)(object) | Check if objects are equal. |
| [Flatten](../../aspose.imaging/graphicspath/flatten)() | Converts each curve in this path into a sequence of connected line segments. |
| [Flatten](../../aspose.imaging/graphicspath/flatten)(Matrix) | Applies the specified transform and then converts each curve in this [`GraphicsPath`](../graphicspath) into a sequence of connected line segments. |
| [Flatten](../../aspose.imaging/graphicspath/flatten)(Matrix, float) | Converts each curve in this [`GraphicsPath`](../graphicspath) into a sequence of connected line segments. |
| override [GetBounds](../../aspose.imaging/graphicspath/getbounds)(Matrix) | Gets the object's bounds. |
| override [GetBounds](../../aspose.imaging/graphicspath/getbounds)(Matrix, Pen) | Gets the object's bounds. |
| override [GetHashCode](../../aspose.imaging/graphicspath/gethashcode)() | Get hash code of the current object. |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible)(Point, Pen) | Indicates whether the specified point is contained within (under) the outline of this [`GraphicsPath`](../graphicspath) when drawn with the specified [`Pen`](../pen). |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible)(PointF, Pen) | Indicates whether the specified point is contained within (under) the outline of this [`GraphicsPath`](../graphicspath) when drawn with the specified [`Pen`](../pen). |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible)(float, float, Pen) | Indicates whether the specified point is contained within (under) the outline of this [`GraphicsPath`](../graphicspath) when drawn with the specified [`Pen`](../pen). |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible)(int, int, Pen) | Indicates whether the specified point is contained within (under) the outline of this [`GraphicsPath`](../graphicspath) when drawn with the specified [`Pen`](../pen). |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible)(Point, Pen, Graphics) | Indicates whether the specified point is contained within (under) the outline of this [`GraphicsPath`](../graphicspath) when drawn with the specified [`Pen`](../pen) and using the specified [`Graphics`](../graphics). |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible)(PointF, Pen, Graphics) | Indicates whether the specified point is contained within (under) the outline of this [`GraphicsPath`](../graphicspath) when drawn with the specified [`Pen`](../pen) and using the specified [`Graphics`](../graphics). |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible)(float, float, Pen, Graphics) | Indicates whether the specified point is contained within (under) the outline of this [`GraphicsPath`](../graphicspath) when drawn with the specified [`Pen`](../pen) and using the specified [`Graphics`](../graphics). |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible)(int, int, Pen, Graphics) | Indicates whether the specified point is contained within (under) the outline of this [`GraphicsPath`](../graphicspath) when drawn with the specified [`Pen`](../pen) and using the specified [`Graphics`](../graphics). |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible)(Point) | Indicates whether the specified point is contained within this [`GraphicsPath`](../graphicspath). |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible)(PointF) | Indicates whether the specified point is contained within this [`GraphicsPath`](../graphicspath). |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible)(float, float) | Indicates whether the specified point is contained within this [`GraphicsPath`](../graphicspath). |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible)(int, int) | Indicates whether the specified point is contained within this [`GraphicsPath`](../graphicspath). |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible)(Point, Graphics) | Indicates whether the specified point is contained within this [`GraphicsPath`](../graphicspath). |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible)(PointF, Graphics) | Indicates whether the specified point is contained within this [`GraphicsPath`](../graphicspath). |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible)(float, float, Graphics) | Indicates whether the specified point is contained within this [`GraphicsPath`](../graphicspath) in the visible clip region of the specified [`Graphics`](../graphics). |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible)(int, int, Graphics) | Indicates whether the specified point is contained within this [`GraphicsPath`](../graphicspath), using the specified [`Graphics`](../graphics). |
| [RemoveFigure](../../aspose.imaging/graphicspath/removefigure)(Figure) | Removes a figure. |
| [RemoveFigures](../../aspose.imaging/graphicspath/removefigures)(Figure[]) | Removes figures. |
| [Reset](../../aspose.imaging/graphicspath/reset)() | Empties the graphics path and sets the [`FillMode`](../fillmode) to Alternate. |
| [Reverse](../../aspose.imaging/graphicspath/reverse)() | Reverses the order of figures, shapes, and points in each shape of this [`GraphicsPath`](../graphicspath). |
| override [Transform](../../aspose.imaging/graphicspath/transform)(Matrix) | Applies the specified transformation to the shape. |
| [Warp](../../aspose.imaging/graphicspath/warp)(PointF[], RectangleF) | Applies a warp transform, defined by a rectangle and a parallelogram, to this [`GraphicsPath`](../graphicspath). |
| [Warp](../../aspose.imaging/graphicspath/warp)(PointF[], RectangleF, Matrix) | Applies a warp transform, defined by a rectangle and a parallelogram, to this [`GraphicsPath`](../graphicspath). |
| [Warp](../../aspose.imaging/graphicspath/warp)(PointF[], RectangleF, Matrix, WarpMode) | Applies a warp transform, defined by a rectangle and a parallelogram, to this [`GraphicsPath`](../graphicspath). |
| [Warp](../../aspose.imaging/graphicspath/warp)(PointF[], RectangleF, Matrix, WarpMode, float) | Applies a warp transform, defined by a rectangle and a parallelogram, to this [`GraphicsPath`](../graphicspath). |
| [Widen](../../aspose.imaging/graphicspath/widen)(Pen) | Adds an additional outline to the path. |
| [Widen](../../aspose.imaging/graphicspath/widen)(Pen, Matrix) | Adds an additional outline to the [`GraphicsPath`](../graphicspath). |
| [Widen](../../aspose.imaging/graphicspath/widen)(Pen, Matrix, float) | Replaces this [`GraphicsPath`](../graphicspath) with curves that enclose the area that is filled when this path is drawn by the specified pen. |

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

### See Also

* class [ObjectWithBounds](../objectwithbounds)
* namespace [Aspose.Imaging](../../aspose.imaging)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
