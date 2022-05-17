---
title: MetafileRecorderGraphics2D
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 6490
url: /net/aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/
---
## MetafileRecorderGraphics2D class

The metafiles recorder graphics

```csharp
public abstract class MetafileRecorderGraphics2D
```

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](backgroundcolor) { get; set; } | Gets or sets the color of the background. |
| [Clip](clip) { get; set; } | Gets or sets a Region that limits the drawing region of this Graphics |
| [ClipBounds](clipbounds) { get; } | Gets the clip bounds. |

## Methods

| Name | Description |
| --- | --- |
| [Clear](clear)() | Clears the state of the graphics object |
| [DrawArc](drawarc)(Pen, Rectangle, float, float) | Draws an arc representing a portion of an ellipse specified by a Rectangle structure. |
| [DrawCubicBezier](drawcubicbezier)(Pen, Point, Point, Point, Point) | Draws the cubic bezier. |
| [DrawEllipse](drawellipse)(Pen, Rectangle) | Draws the ellipse. |
| [DrawImage](drawimage)(RasterImage, Point) | Draws the specified Image, using its original physical size, at the specified location. |
| [DrawImage](drawimage)(byte[], Rectangle, GraphicsUnit) | Draws the image. |
| [DrawImage](drawimage)(RasterImage, Rectangle, Rectangle, GraphicsUnit) | Draws the specified portion of the specified Image at the specified location and with the specified size. |
| [DrawLine](drawline)(Pen, Point, Point) | Draws the line. |
| [DrawLine](drawline)(Pen, int, int, int, int) | Draws the line. |
| [DrawPath](drawpath)(Pen, GraphicsPath) | Draws the path. |
| [DrawPie](drawpie)(Pen, Rectangle, float, float) | Draws the pie. |
| [DrawPolyCubicBezier](drawpolycubicbezier)(Pen, Point[]) | Draws the poly cubic bezier. |
| [DrawPolygon](drawpolygon)(Pen, Point[]) | Draws the polygon. |
| [DrawPolyline](drawpolyline)(Pen, Point[]) | Draws the polyline. |
| [DrawRectangle](drawrectangle)(Pen, Rectangle) | Draws the rectangle. |
| [DrawRectangle](drawrectangle)(Pen, int, int, int, int) | Draws the rectangle. |
| [DrawString](drawstring)(string, Font, Color, int, int) | Draws the string. |
| [DrawString](drawstring)(string, Font, Color, int, int, float) | Draws the string. |
| [ExcludeClip](excludeclip)(Rectangle) | Updates the clip region of this Graphics to exclude the area specified by a Rectangle structure. |
| [ExcludeClip](excludeclip)(Region) | Updates the clip region of this Graphics to exclude the area specified by a Region. |
| [FillEllipse](fillellipse)(Brush, Rectangle) | Fills the ellipse. |
| [FillPath](fillpath)(Pen, Brush, GraphicsPath) | Fills the path. |
| [FillPie](fillpie)(Brush, Rectangle, float, float) | Fills the pie. |
| [FillPolygon](fillpolygon)(Brush, Point[]) | Fills the polygon. |
| [FillPolygon](fillpolygon)(Brush, Point[], FillMode) | Fills the polygon. |
| [FillRectangle](fillrectangle)(Brush, Rectangle) | Fills the rectangle. |
| [GetTransform](gettransform)() | Gets the world transform. |
| [IntersectClip](intersectclip)(RectangleF) | Updates the clip region of this Graphics to the intersection of the current clip region and the specified Rectangle structure. |
| [IntersectClip](intersectclip)(Region) | Updates the clip region of this Graphics to the intersection of the current clip region and the specified Region. |
| [MultiplyTransform](multiplytransform)(Matrix) | Multiplies the world transformation of this Graphics and specified the Matrix. |
| [MultiplyTransform](multiplytransform)(Matrix, MatrixOrder) | Multiplies the world transformation of this Graphics and specified the Matrix in the specified order. |
| [ResetClip](resetclip)() | Resets the clip. |
| [RotateTransform](rotatetransform)(float) | Applies the specified rotation to the transformation matrix of this Graphics. |
| [RotateTransform](rotatetransform)(float, PointF, MatrixOrder) | Applies the specified rotation to the transformation matrix of this Graphics in the specified order. |
| [ScaleTransform](scaletransform)(float, float) | Applies the specified scaling operation to the transformation matrix of this Graphics by prepending it to the object's transformation matrix. |
| [ScaleTransform](scaletransform)(float, float, MatrixOrder) | Applies the specified scaling operation to the transformation matrix of this Graphics in the specified order. |
| [SetTransform](settransform)(Matrix) | Sets the transform. |
| [TranslateTransform](translatetransform)(float, float) | Changes the origin of the coordinate system by prepending the specified translation to the transformation matrix of this Graphics. |
| [TranslateTransform](translatetransform)(float, float, MatrixOrder) | Changes the origin of the coordinate system by applying the specified translation to the transformation matrix of this Graphics in the specified order. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.Graphics](../../aspose.imaging.fileformats.emf.graphics)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
