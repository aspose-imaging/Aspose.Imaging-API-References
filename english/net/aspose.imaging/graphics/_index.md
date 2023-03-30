---
title: Graphics
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 9450
url: /net/aspose.imaging/graphics/
---
## Graphics class

Represents the graphics according to the graphics engine used in the current assembly.

```csharp
public sealed class Graphics
```

## Constructors

| Name | Description |
| --- | --- |
| [Graphics](graphics)(Image) | Initializes a new instance of the [`Graphics`](../graphics) class. |

## Properties

| Name | Description |
| --- | --- |
| [Clip](../../aspose.imaging/graphics/clip) { get; set; } | Gets or sets the clip region. |
| [CompositingQuality](../../aspose.imaging/graphics/compositingquality) { get; set; } | Gets or sets the compositing quality. |
| [DpiX](../../aspose.imaging/graphics/dpix) { get; } | Gets the horizontal resolution of this Aspose.Imaging.Graphics. |
| [DpiY](../../aspose.imaging/graphics/dpiy) { get; } | Gets the vertical resolution of this Aspose.Imaging.Graphics. |
| [Image](../../aspose.imaging/graphics/image) { get; } | Gets the image. |
| [InterpolationMode](../../aspose.imaging/graphics/interpolationmode) { get; set; } | Gets or sets the interpolation mode. |
| [IsInBeginUpdateCall](../../aspose.imaging/graphics/isinbeginupdatecall) { get; } | Gets a value indicating whether graphics is in BeginUpdate call state. |
| [PageScale](../../aspose.imaging/graphics/pagescale) { get; set; } | Gets or sets the scaling between world units and page units for this Aspose.Imaging.Graphics. |
| [PageUnit](../../aspose.imaging/graphics/pageunit) { get; set; } | Gets or sets the unit of measure used for page coordinates in this Aspose.Imaging.Graphics. |
| [PaintableImageOptions](../../aspose.imaging/graphics/paintableimageoptions) { get; set; } | Gets or sets image options, used to create paintable vactor images to draw. |
| [SmoothingMode](../../aspose.imaging/graphics/smoothingmode) { get; set; } | Gets or sets the smoothing mode. |
| [TextRenderingHint](../../aspose.imaging/graphics/textrenderinghint) { get; set; } | Gets or sets the text rendering hint. |
| [Transform](../../aspose.imaging/graphics/transform) { get; set; } | Gets or sets a copy of the geometric world transformation for this [`Graphics`](../graphics). |

## Methods

| Name | Description |
| --- | --- |
| [BeginUpdate](../../aspose.imaging/graphics/beginupdate)() | Starts caching of the following graphics operations. The graphics effects applied afterwards will not be applied immediately instead the EndUpdate will cause applying all the effects at once. |
| [Clear](../../aspose.imaging/graphics/clear)(Color) | Clears the graphics surface using the specified color. |
| [DrawArc](../../aspose.imaging/graphics/drawarc)(Pen, Rectangle, float, float) | Draws an arc representing a portion of an ellipse specified by a [`Rectangle`](../rectangle) structure. |
| [DrawArc](../../aspose.imaging/graphics/drawarc)(Pen, RectangleF, float, float) | Draws an arc representing a portion of an ellipse specified by a [`RectangleF`](../rectanglef) structure. |
| [DrawArc](../../aspose.imaging/graphics/drawarc)(Pen, float, float, float, float, float, float) | Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height. |
| [DrawArc](../../aspose.imaging/graphics/drawarc)(Pen, int, int, int, int, int, int) | Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier)(Pen, Point, Point, Point, Point) | Draws a Bézier spline defined by four [`Point`](../point) structures. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier)(Pen, PointF, PointF, PointF, PointF) | Draws a Bézier spline defined by four [`PointF`](../pointf) structures. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier)(Pen, float, float, float, float, float, float, float, float) | Draws a Bézier spline defined by four ordered pairs of coordinates that represent points. |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers)(Pen, PointF[]) | Draws a series of Bézier splines from an array of [`PointF`](../pointf) structures. |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers)(Pen, Point[]) | Draws a series of Bézier splines from an array of [`Point`](../point) structures. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve)(Pen, PointF[]) | Draws a closed cardinal spline defined by an array of [`PointF`](../pointf) structures. This method uses a default tension of 0.5 and Alternate fill mode. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve)(Pen, Point[]) | Draws a closed cardinal spline defined by an array of [`Point`](../point) structures. This method uses a default tension of 0.5 and Alternate fill mode. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve)(Pen, PointF[], float) | Draws a closed cardinal spline defined by an array of [`PointF`](../pointf) structures using a specified tension. This method uses a default Alternate fill mode. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve)(Pen, Point[], float) | Draws a closed cardinal spline defined by an array of [`Point`](../point) structures using a specified tension. This method uses a default Alternate fill mode. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve)(Pen, PointF[]) | Draws a cardinal spline through a specified array of [`PointF`](../pointf) structures. This method uses a default tension of 0.5. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve)(Pen, Point[]) | Draws a cardinal spline through a specified array of [`Point`](../point) structures. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve)(Pen, PointF[], float) | Draws a cardinal spline through a specified array of [`PointF`](../pointf) structures using a specified tension. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve)(Pen, Point[], float) | Draws a cardinal spline through a specified array of [`Point`](../point) structures using a specified tension. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve)(Pen, PointF[], int, int) | Draws a cardinal spline through a specified array of [`PointF`](../pointf) structures. The drawing begins offset from the beginning of the array. This method uses a default tension of 0.5. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve)(Pen, PointF[], int, int, float) | Draws a cardinal spline through a specified array of [`PointF`](../pointf) structures using a specified tension. The drawing begins offset from the beginning of the array. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve)(Pen, Point[], int, int, float) | Draws a cardinal spline through a specified array of [`Point`](../point) structures using a specified tension. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse)(Pen, Rectangle) | Draws an ellipse specified by a bounding [`Rectangle`](../rectangle) structure. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse)(Pen, RectangleF) | Draws an ellipse defined by a bounding [`RectangleF`](../rectanglef). |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse)(Pen, float, float, float, float) | Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse)(Pen, int, int, int, int) | Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width. |
| [DrawImage](../../aspose.imaging/graphics/drawimage)(Image, Point) | Draws the specified [`Image`](./image), using its original physical size, at the specified location. |
| [DrawImage](../../aspose.imaging/graphics/drawimage)(Image, PointF) | Draws the specified [`Image`](./image), using its original physical size, at the specified location. |
| [DrawImage](../../aspose.imaging/graphics/drawimage)(Image, PointF[]) | Draws the specified portion of the specified *image* at the specified location and with the specified size. |
| [DrawImage](../../aspose.imaging/graphics/drawimage)(Image, Point[]) | Draws the specified portion of the specified *image* at the specified location and with the specified size. |
| [DrawImage](../../aspose.imaging/graphics/drawimage)(Image, Rectangle) | Draws the specified [`Image`](./image) at the specified location and with the specified size. |
| [DrawImage](../../aspose.imaging/graphics/drawimage)(Image, RectangleF) | Draws the specified [`Image`](./image) at the specified location and with the specified size. |
| [DrawImage](../../aspose.imaging/graphics/drawimage)(Image, float, float) | Draws the specified [`Image`](./image), using its original physical size, at the specified location. |
| [DrawImage](../../aspose.imaging/graphics/drawimage)(Image, int, int) | Draws the specified image, using its original physical size, at the location specified by a coordinate pair. |
| [DrawImage](../../aspose.imaging/graphics/drawimage)(Image, PointF[], RectangleF) | Draws the specified portion of the specified *image* at the specified location and with the specified size. |
| [DrawImage](../../aspose.imaging/graphics/drawimage)(Image, Point[], Rectangle) | Draws the specified portion of the specified *image* at the specified location and with the specified size. |
| [DrawImage](../../aspose.imaging/graphics/drawimage)(Image, Rectangle, GraphicsUnit) | Draws the specified [`Image`](./image) at the specified location and with the specified size. |
| [DrawImage](../../aspose.imaging/graphics/drawimage)(Image, RectangleF, GraphicsUnit) | Draws the specified [`Image`](./image) at the specified location and with the specified size. |
| [DrawImage](../../aspose.imaging/graphics/drawimage)(Image, PointF[], RectangleF, GraphicsUnit) | Draws the specified portion of the specified *image* at the specified location and with the specified size. |
| [DrawImage](../../aspose.imaging/graphics/drawimage)(Image, Point[], Rectangle, GraphicsUnit) | Draws the specified portion of the specified *image* at the specified location and with the specified size. |
| [DrawImage](../../aspose.imaging/graphics/drawimage)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Draws the specified [`Image`](./image) at the specified location and with the specified size. |
| [DrawImage](../../aspose.imaging/graphics/drawimage)(Image, Rectangle, Rectangle, GraphicsUnit) | Draws the specified [`Image`](./image) at the specified location and with the specified size. |
| [DrawImage](../../aspose.imaging/graphics/drawimage)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Draws the specified [`Image`](./image) at the specified location and with the specified size. |
| [DrawImage](../../aspose.imaging/graphics/drawimage)(Image, RectangleF, RectangleF, GraphicsUnit) | Draws the specified [`Image`](./image) at the specified location and with the specified size. |
| [DrawImage](../../aspose.imaging/graphics/drawimage)(Image, float, float, float, float) | Draws the specified [`Image`](./image) at the specified location and with the specified size. |
| [DrawImage](../../aspose.imaging/graphics/drawimage)(Image, int, int, int, int) | Draws the specified [`Image`](./image) at the specified location and with the specified size. |
| [DrawImage](../../aspose.imaging/graphics/drawimage)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Draws the specified portion of the specified *image* at the specified location and with the specified size. |
| [DrawImage](../../aspose.imaging/graphics/drawimage)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Draws the specified portion of the specified *image* at the specified location and with the specified size. |
| [DrawImage](../../aspose.imaging/graphics/drawimage)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Draws the specified [`Image`](./image) at the specified location and with the specified size. |
| [DrawImage](../../aspose.imaging/graphics/drawimage)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Draws the specified [`Image`](./image) at the specified location and with the specified size. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled)(Image, Point) | Draws a specified image using its original physical size at a specified location. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled)(Image, Rectangle) | Draws a specified image using its original physical size at a specified location. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled)(Image, int, int) | Draws the specified image using its original physical size at the location specified by a coordinate pair. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled)(Image, int, int, int, int) | Draws a specified image using its original physical size at a specified location. |
| [DrawImageUnscaledAndClipped](../../aspose.imaging/graphics/drawimageunscaledandclipped)(Image, Rectangle) | Draws the specified image without scaling and clips it, if necessary, to fit in the specified rectangle. |
| [DrawLine](../../aspose.imaging/graphics/drawline)(Pen, Point, Point) | Draws a line connecting two [`Point`](../point) structures. |
| [DrawLine](../../aspose.imaging/graphics/drawline)(Pen, PointF, PointF) | Draws a line connecting two [`PointF`](../pointf) structures. |
| [DrawLine](../../aspose.imaging/graphics/drawline)(Pen, float, float, float, float) | Draws a line connecting the two points specified by the coordinate pairs. |
| [DrawLine](../../aspose.imaging/graphics/drawline)(Pen, int, int, int, int) | Draws a line connecting the two points specified by the coordinate pairs. |
| [DrawLines](../../aspose.imaging/graphics/drawlines)(Pen, PointF[]) | Draws a series of line segments that connect an array of [`PointF`](../pointf) structures. |
| [DrawLines](../../aspose.imaging/graphics/drawlines)(Pen, Point[]) | Draws a series of line segments that connect an array of [`Point`](../point) structures. |
| [DrawPath](../../aspose.imaging/graphics/drawpath)(Pen, GraphicsPath) | Draws a [`GraphicsPath`](../graphicspath). |
| [DrawPie](../../aspose.imaging/graphics/drawpie)(Pen, Rectangle, float, float) | Draws a pie shape defined by an ellipse specified by a [`Rectangle`](../rectangle) structure and two radial lines. |
| [DrawPie](../../aspose.imaging/graphics/drawpie)(Pen, RectangleF, float, float) | Draws a pie shape defined by an ellipse specified by a [`RectangleF`](../rectanglef) structure and two radial lines. |
| [DrawPie](../../aspose.imaging/graphics/drawpie)(Pen, float, float, float, float, float, float) | Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines. |
| [DrawPie](../../aspose.imaging/graphics/drawpie)(Pen, int, int, int, int, int, int) | Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines. |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon)(Pen, PointF[]) | Draws a polygon defined by an array of [`PointF`](../pointf) structures. |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon)(Pen, Point[]) | Draws a polygon defined by an array of [`Point`](../point) structures. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle)(Pen, Rectangle) | Draws a rectangle specified by a [`Rectangle`](../rectangle) structure. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle)(Pen, RectangleF) | Draws a rectangle specified by a [`RectangleF`](../rectanglef) structure. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle)(Pen, float, float, float, float) | Draws a rectangle specified by a coordinate pair, a width, and a height. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle)(Pen, int, int, int, int) | Draws a rectangle specified by a coordinate pair, a width, and a height. |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles)(Pen, RectangleF[]) | Draws a series of rectangles specified by [`RectangleF`](../rectanglef) structures. |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles)(Pen, Rectangle[]) | Draws a series of rectangles specified by [`Rectangle`](../rectangle) structures. |
| [DrawString](../../aspose.imaging/graphics/drawstring)(string, Font, Brush, PointF) | Draws the specified text string at the specified location with the specified [`Brush`](../brush) and [`Font`](../font) objects. |
| [DrawString](../../aspose.imaging/graphics/drawstring)(string, Font, Brush, RectangleF) | Draws the specified text string in the specified rectangle with the specified [`Brush`](../brush) and [`Font`](../font) objects. |
| [DrawString](../../aspose.imaging/graphics/drawstring)(string, Font, Brush, float, float) | Draws the specified text string at the specified location with the specified [`Brush`](../brush) and [`Font`](../font) objects. |
| [DrawString](../../aspose.imaging/graphics/drawstring)(string, Font, Brush, PointF, StringFormat) | Draws the specified text string at the specified location with the specified [`Brush`](../brush) and [`Font`](../font) objects using the formatting attributes of the specified [`StringFormat`](../stringformat). |
| [DrawString](../../aspose.imaging/graphics/drawstring)(string, Font, Brush, RectangleF, StringFormat) | Draws the specified text string in the specified rectangle with the specified [`Brush`](../brush) and [`Font`](../font) objects using the formatting attributes of the specified [`StringFormat`](../stringformat). |
| [DrawString](../../aspose.imaging/graphics/drawstring)(string, Font, Brush, float, float, StringFormat) | Draws the specified text string at the specified location with the specified [`Brush`](../brush) and [`Font`](../font) objects using the formatting attributes of the specified [`StringFormat`](../stringformat). |
| [EndUpdate](../../aspose.imaging/graphics/endupdate)() | Finishes caching of the graphics operations started after BeginUpdate was called. The preceding graphics operations will be applied at once when calling this method. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve)(Brush, PointF[]) | Fills the interior of a closed cardinal spline curve defined by an array of [`PointF`](../pointf) structures. This method uses a default tension of 0.5 and Alternate fill mode. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve)(Brush, Point[]) | Fills the interior of a closed cardinal spline curve defined by an array of [`Point`](../point) structures. This method uses a default tension of 0.5 and Alternate fill mode. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve)(Brush, PointF[], FillMode) | Fills the interior of a closed cardinal spline curve defined by an array of [`PointF`](../pointf) structures using the specified fill mode. This method uses a default tension of 0.5. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve)(Brush, Point[], FillMode) | Fills the interior of a closed cardinal spline curve defined by an array of [`Point`](../point) structures using the specified fill mode. This method uses a default tension of 0.5. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve)(Brush, PointF[], FillMode, float) | Fills the interior of a closed cardinal spline curve defined by an array of [`PointF`](../pointf) structures using the specified fill mode and tension. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve)(Brush, Point[], FillMode, float) | Fills the interior of a closed cardinal spline curve defined by an array of [`Point`](../point) structures using the specified fill mode and tension. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse)(Brush, Rectangle) | Fills the interior of an ellipse defined by a bounding rectangle specified by a [`Rectangle`](../rectangle) structure. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse)(Brush, RectangleF) | Fills the interior of an ellipse defined by a bounding rectangle specified by a [`RectangleF`](../rectanglef) structure. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse)(Brush, float, float, float, float) | Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse)(Brush, int, int, int, int) | Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height. |
| [FillPath](../../aspose.imaging/graphics/fillpath)(Brush, GraphicsPath) | Fills the interior of a [`GraphicsPath`](../graphicspath). |
| [FillPie](../../aspose.imaging/graphics/fillpie)(Brush, Rectangle, float, float) | Fills the interior of a pie section defined by an ellipse specified by a [`RectangleF`](../rectanglef) structure and two radial lines. |
| [FillPie](../../aspose.imaging/graphics/fillpie)(Brush, RectangleF, float, float) | Fills the interior of a pie section defined by an ellipse specified by a [`RectangleF`](../rectanglef) structure and two radial lines. |
| [FillPie](../../aspose.imaging/graphics/fillpie)(Brush, float, float, float, float, float, float) | Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines. |
| [FillPie](../../aspose.imaging/graphics/fillpie)(Brush, int, int, int, int, int, int) | Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon)(Brush, PointF[]) | Fills the interior of a polygon defined by an array of points specified by [`PointF`](../pointf) structures and Alternate. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon)(Brush, Point[]) | Fills the interior of a polygon defined by an array of points specified by [`Point`](../point) structures and Alternate. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon)(Brush, PointF[], FillMode) | Fills the interior of a polygon defined by an array of points specified by [`PointF`](../pointf) structures using the specified fill mode. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon)(Brush, Point[], FillMode) | Fills the interior of a polygon defined by an array of points specified by [`Point`](../point) structures using the specified fill mode. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle)(Brush, Rectangle) | Fills the interior of a rectangle specified by a [`Rectangle`](../rectangle) structure. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle)(Brush, RectangleF) | Fills the interior of a rectangle specified by a [`RectangleF`](../rectanglef) structure. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle)(Brush, float, float, float, float) | Fills the interior of a rectangle specified by a pair of coordinates, a width and a height. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle)(Brush, int, int, int, int) | Fills the interior of a rectangle specified by a pair of coordinates, a width and a height. |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles)(Brush, RectangleF[]) | Fills the interiors of a series of rectangles specified by [`RectangleF`](../rectanglef) structures. |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles)(Brush, Rectangle[]) | Fills the interiors of a series of rectangles specified by [`Rectangle`](../rectangle) structures. |
| [FillRegion](../../aspose.imaging/graphics/fillregion)(Brush, Region) | Fills the interior of a [`Region`](../region). |
| [MeasureString](../../aspose.imaging/graphics/measurestring)(string, Font, SizeF, StringFormat) | Measures the specified text string with specified parameters |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform)(Matrix) | Multiplies the [`Matrix`](../matrix) that represents the local geometric transform of this [`Graphics`](../graphics) by the specified [`Matrix`](../matrix) by prepending the specified [`Matrix`](../matrix). |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform)(Matrix, MatrixOrder) | Multiplies the [`Matrix`](../matrix) that represents the local geometric transform of this [`Graphics`](../graphics) by the specified [`Matrix`](../matrix) in the specified order. |
| [ResetTransform](../../aspose.imaging/graphics/resettransform)() | Resets the [`Transform`](./transform) property to identity. |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform)(float) | Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform. |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform)(float, MatrixOrder) | Rotates the local geometric transform by the specified amount in the specified order. |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform)(float, float) | Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform. |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform)(float, float, MatrixOrder) | Scales the local geometric transform by the specified amounts in the specified order. |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform)(float, float) | Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform. |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform)(float, float, MatrixOrder) | Translates the local geometric transform by the specified dimensions in the specified order. |

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

* namespace [Aspose.Imaging](../../aspose.imaging)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
