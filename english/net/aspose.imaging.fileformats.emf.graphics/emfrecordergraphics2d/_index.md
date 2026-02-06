---
title: Class EmfRecorderGraphics2D
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D class. The Emf recorder graphics
type: docs
weight: 6610
url: /net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/
---
## EmfRecorderGraphics2D class

The Emf recorder graphics

```csharp
public sealed class EmfRecorderGraphics2D : MetafileRecorderGraphics2D
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfRecorderGraphics2D](emfrecordergraphics2d/)(Rectangle, Size, Size) | Initializes a new instance of the `EmfRecorderGraphics2D` class. |

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/backgroundcolor/) { get; set; } | Gets or sets the color of the background. |
| [BackgroundMode](../../aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/backgroundmode/) { get; set; } | Gets or sets the background mode. |
| [Clip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clip/) { get; set; } | Gets or sets a Region that limits the drawing region of this Graphics |
| [ClipBounds](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clipbounds/) { get; } | Gets the clip bounds. |

## Methods

| Name | Description |
| --- | --- |
| static [FromEmfImage](../../aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/fromemfimage/)(EmfImage) | Gets an instance of the `EmfRecorderGraphics2D` containing all records from the Emf image. |
| [Clear](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clear/)() | Clears the state of the graphics object |
| [DrawArc](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawarc/)(Pen, Rectangle, float, float) | Draws an arc representing a portion of an ellipse specified by a Rectangle structure. |
| [DrawCubicBezier](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawcubicbezier/)(Pen, Point, Point, Point, Point) | Draws the cubic bezier. |
| [DrawEllipse](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawellipse/)(Pen, Rectangle) | Draws the ellipse. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage/)(RasterImage, Point) | Draws the specified Image, using its original physical size, at the specified location. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage/)(byte[], Rectangle, GraphicsUnit) | Draws the image. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage/)(Stream, Rectangle, GraphicsUnit) | Draws the image. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage/)(RasterImage, Rectangle, Rectangle, GraphicsUnit) | Draws the specified portion of the specified Image at the specified location and with the specified size. |
| [DrawLine](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline/)(Pen, Point, Point) | Draws the line. |
| [DrawLine](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline/)(Pen, int, int, int, int) | Draws the line. |
| [DrawPath](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpath/)(Pen, GraphicsPath) | Draws the path. |
| [DrawPie](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpie/)(Pen, Rectangle, float, float) | Draws the pie. |
| [DrawPolyCubicBezier](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolycubicbezier/)(Pen, Point[]) | Draws the poly cubic bezier. |
| [DrawPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolygon/)(Pen, Point[]) | Draws the polygon. |
| [DrawPolyline](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolyline/)(Pen, Point[]) | Draws the polyline. |
| [DrawRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawrectangle/)(Pen, Rectangle) | Draws the rectangle. |
| [DrawRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawrectangle/)(Pen, int, int, int, int) | Draws the rectangle. |
| [DrawString](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring/)(string, Font, Color, int, int) | Draws the string. |
| [DrawString](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring/)(string, Font, Color, int, int, float) | Draws the string. |
| [EndRecording](../../aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/endrecording/)() | Ends the recording. |
| [ExcludeClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/excludeclip/)(Rectangle) | Updates the clip region of this Graphics to exclude the area specified by a Rectangle structure. |
| [ExcludeClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/excludeclip/)(Region) | Updates the clip region of this Graphics to exclude the area specified by a Region. |
| [FillEllipse](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillellipse/)(Brush, Rectangle) | Fills the ellipse. |
| [FillPath](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpath/)(Pen, Brush, GraphicsPath) | Fills the path. |
| [FillPie](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpie/)(Brush, Rectangle, float, float) | Fills the pie. |
| [FillPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpolygon/)(Brush, Point[]) | Fills the polygon. |
| [FillPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpolygon/)(Brush, Point[], FillMode) | Fills the polygon. |
| [FillRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillrectangle/)(Brush, Rectangle) | Fills the rectangle. |
| [GetTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/gettransform/)() | Gets the world transform. |
| [IntersectClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/intersectclip/)(RectangleF) | Updates the clip region of this Graphics to the intersection of the current clip region and the specified Rectangle structure. |
| [IntersectClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/intersectclip/)(Region) | Updates the clip region of this Graphics to the intersection of the current clip region and the specified Region. |
| [MultiplyTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/multiplytransform/)(Matrix) | Multiplies the world transformation of this Graphics and specified the Matrix. |
| [MultiplyTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/multiplytransform/)(Matrix, MatrixOrder) | Multiplies the world transformation of this Graphics and specified the Matrix in the specified order. |
| [ResetClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/resetclip/)() | Resets the clip. |
| [RotateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/rotatetransform/)(float) | Applies the specified rotation to the transformation matrix of this Graphics. |
| [RotateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/rotatetransform/)(float, PointF, MatrixOrder) | Applies the specified rotation to the transformation matrix of this Graphics in the specified order. |
| [ScaleTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/scaletransform/)(float, float) | Applies the specified scaling operation to the transformation matrix of this Graphics by prepending it to the object's transformation matrix. |
| [ScaleTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/scaletransform/)(float, float, MatrixOrder) | Applies the specified scaling operation to the transformation matrix of this Graphics in the specified order. |
| [SetTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/settransform/)(Matrix) | Sets the transform. |
| [TranslateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/translatetransform/)(float, float) | Changes the origin of the coordinate system by prepending the specified translation to the transformation matrix of this Graphics. |
| [TranslateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/translatetransform/)(float, float, MatrixOrder) | Changes the origin of the coordinate system by applying the specified translation to the transformation matrix of this Graphics in the specified order. |

### See Also

* class [MetafileRecorderGraphics2D](../metafilerecordergraphics2d/)
* namespace [Aspose.Imaging.FileFormats.Emf.Graphics](../../aspose.imaging.fileformats.emf.graphics/)
* assembly [Aspose.Imaging](../../)


