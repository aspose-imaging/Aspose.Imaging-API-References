---
title: Graphics
second_title: Aspose.Imaging for Java API Reference
description: Represents the graphics according to the graphics engine used in the current assembly.
type: docs
weight: 51
url: /java/com.aspose.imaging/graphics/
---
**Inheritance:**
java.lang.Object
```
public final class Graphics
```

Represents the graphics according to the graphics engine used in the current assembly.
## Constructors

| Constructor | Description |
| --- | --- |
| [Graphics(Image sourceImage)](#Graphics-com.aspose.imaging.Image-) | Initializes a new instance of the `Graphics` class. |
## Methods

| Method | Description |
| --- | --- |
| [getDpiX()](#getDpiX--) | Gets the horizontal resolution of this com.aspose.imaging.graphics. |
| [getDpiY()](#getDpiY--) | Gets the vertical resolution of this com.aspose.imaging.graphics. |
| [getPageUnit()](#getPageUnit--) | Gets or sets the unit of measure used for page coordinates in this com.aspose.imaging.graphics. |
| [setPageUnit(int value)](#setPageUnit-int-) | Gets or sets the unit of measure used for page coordinates in this com.aspose.imaging.graphics. |
| [getPageScale()](#getPageScale--) | Gets or sets the scaling between world units and page units for this com.aspose.imaging.graphics. |
| [setPageScale(float value)](#setPageScale-float-) | Gets or sets the scaling between world units and page units for this com.aspose.imaging.graphics. |
| [getClip()](#getClip--) | Gets or sets the clip region. |
| [setClip(Region value)](#setClip-com.aspose.imaging.Region-) | Gets or sets the clip region. |
| [getTransform()](#getTransform--) | Gets or sets a copy of the geometric world transformation for this `com.aspose.imaging.graphics`. |
| [setTransform(Matrix value)](#setTransform-com.aspose.imaging.Matrix-) | Gets or sets a copy of the geometric world transformation for this `com.aspose.imaging.graphics`. |
| [isInBeginUpdateCall()](#isInBeginUpdateCall--) | Gets a value indicating whether graphics is in BeginUpdate call state. |
| [getImage()](#getImage--) | Gets the image. |
| [getCompositingQuality()](#getCompositingQuality--) | Gets or sets the compositing quality. |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | Gets or sets the compositing quality. |
| [getInterpolationMode()](#getInterpolationMode--) | Gets or sets the interpolation mode. |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | Gets or sets the interpolation mode. |
| [getSmoothingMode()](#getSmoothingMode--) | Gets or sets the smoothing mode. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Gets or sets the smoothing mode. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Gets or sets the text rendering hint. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Gets or sets the text rendering hint. |
| [getPaintableImageOptions()](#getPaintableImageOptions--) | Gets image options, used to create paintable vector images to draw. |
| [setPaintableImageOptions(ImageOptionsBase value)](#setPaintableImageOptions-com.aspose.imaging.ImageOptionsBase-) | Sets image options, used to create paintable vector images to draw. |
| [resetTransform()](#resetTransform--) | Resets the `com.aspose.imaging.graphics.Transform` property to identity. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | Multiplies the `com.aspose.imaging.Matrix` that represents the local geometric transform of this `com.aspose.imaging.Graphics` by the specified `com.aspose.imaging.Matrix` by prepending the specified `com.aspose.imaging.matrix`. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | Multiplies the `com.aspose.imaging.Matrix` that represents the local geometric transform of this `com.aspose.imaging.Graphics` by the specified `com.aspose.imaging.Matrix` in the specified order. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Translates the local geometric transform by the specified dimensions. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Translates the local geometric transform by the specified dimensions in the specified order. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Scales the local geometric transform by the specified amounts. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Scales the local geometric transform by the specified amounts in the specified order. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Rotates the local geometric transform by the specified amount. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Rotates the local geometric transform by the specified amount in the specified order. |
| [beginUpdate()](#beginUpdate--) | Starts caching of the following graphics operations. |
| [endUpdate()](#endUpdate--) | Finishes caching of the graphics operations started after BeginUpdate was called. |
| [clear(Color color)](#clear-com.aspose.imaging.Color-) | Clears the graphics surface using the specified color. |
| [drawLine(Pen pen, Point point1, Point point2)](#drawLine-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Draws a line connecting two `Point` structures. |
| [drawLine(Pen pen, PointF point1, PointF point2)](#drawLine-com.aspose.imaging.Pen-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Draws a line connecting two `PointF` structures. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.imaging.Pen-int-int-int-int-) | Draws a line connecting the two points specified by the coordinate pairs. |
| [drawLine(Pen pen, float x1, float y1, float x2, float y2)](#drawLine-com.aspose.imaging.Pen-float-float-float-float-) | Draws a line connecting the two points specified by the coordinate pairs. |
| [drawLines(Pen pen, Point[] points)](#drawLines-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Draws a series of line segments that connect an array of `Point` structures. |
| [drawLines(Pen pen, PointF[] points)](#drawLines-com.aspose.imaging.Pen-com.aspose.imaging.PointF---) | Draws a series of line segments that connect an array of `PointF` structures. |
| [fillRectangle(Brush brush, Rectangle rect)](#fillRectangle-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-) | Fills the interior of a rectangle specified by a `Rectangle` structure. |
| [fillRectangle(Brush brush, RectangleF rect)](#fillRectangle-com.aspose.imaging.Brush-com.aspose.imaging.RectangleF-) | Fills the interior of a rectangle specified by a `RectangleF` structure. |
| [fillRectangle(Brush brush, float x, float y, float width, float height)](#fillRectangle-com.aspose.imaging.Brush-float-float-float-float-) | Fills the interior of a rectangle specified by a pair of coordinates, a width and a height. |
| [fillRectangle(Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.imaging.Brush-int-int-int-int-) | Fills the interior of a rectangle specified by a pair of coordinates, a width and a height. |
| [fillRectangles(Brush brush, Rectangle[] rects)](#fillRectangles-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle---) | Fills the interiors of a series of rectangles specified by `Rectangle` structures. |
| [fillRectangles(Brush brush, RectangleF[] rects)](#fillRectangles-com.aspose.imaging.Brush-com.aspose.imaging.RectangleF---) | Fills the interiors of a series of rectangles specified by `RectangleF` structures. |
| [drawRectangle(Pen pen, RectangleF rect)](#drawRectangle-com.aspose.imaging.Pen-com.aspose.imaging.RectangleF-) | Draws a rectangle specified by a `RectangleF` structure. |
| [drawRectangle(Pen pen, Rectangle rect)](#drawRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-) | Draws a rectangle specified by a `Rectangle` structure. |
| [drawRectangle(Pen pen, float x, float y, float width, float height)](#drawRectangle-com.aspose.imaging.Pen-float-float-float-float-) | Draws a rectangle specified by a coordinate pair, a width, and a height. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-) | Draws a rectangle specified by a coordinate pair, a width, and a height. |
| [drawRectangles(Pen pen, RectangleF[] rects)](#drawRectangles-com.aspose.imaging.Pen-com.aspose.imaging.RectangleF---) | Draws a series of rectangles specified by `RectangleF` structures. |
| [drawRectangles(Pen pen, Rectangle[] rects)](#drawRectangles-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle---) | Draws a series of rectangles specified by `Rectangle` structures. |
| [drawEllipse(Pen pen, RectangleF rect)](#drawEllipse-com.aspose.imaging.Pen-com.aspose.imaging.RectangleF-) | Draws an ellipse defined by a bounding `RectangleF`. |
| [drawEllipse(Pen pen, float x, float y, float width, float height)](#drawEllipse-com.aspose.imaging.Pen-float-float-float-float-) | Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width. |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-) | Draws an ellipse specified by a bounding `Rectangle` structure. |
| [drawEllipse(Pen pen, int x, int y, int width, int height)](#drawEllipse-com.aspose.imaging.Pen-int-int-int-int-) | Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width. |
| [drawPolygon(Pen pen, PointF[] points)](#drawPolygon-com.aspose.imaging.Pen-com.aspose.imaging.PointF---) | Draws a polygon defined by an array of `PointF` structures. |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Draws a polygon defined by an array of `Point` structures. |
| [drawImage(Image sourceImage, PointF point)](#drawImage-com.aspose.imaging.Image-com.aspose.imaging.PointF-) | Draws the specified `Image`, using its original physical size, at the specified location. |
| [drawImage(Image sourceImage, float x, float y)](#drawImage-com.aspose.imaging.Image-float-float-) | Draws the specified `Image`, using its original physical size, at the specified location. |
| [drawImage(Image sourceImage, RectangleF rect)](#drawImage-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-) | Draws the specified `Image` at the specified location and with the specified size. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-int-) | Draws the specified `Image` at the specified location and with the specified size. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-int-) | Draws the specified `Image` at the specified location and with the specified size. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-int-com.aspose.imaging.ImageAttributes-) | Draws the specified `Image` at the specified location and with the specified size. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-int-com.aspose.imaging.ImageAttributes-) | Draws the specified `Image` at the specified location and with the specified size. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-int-) | Draws the specified `Image` at the specified location and with the specified size. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-int-) | Draws the specified `Image` at the specified location and with the specified size. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-int-com.aspose.imaging.ImageAttributes-) | Draws the specified `Image` at the specified location and with the specified size. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-int-com.aspose.imaging.ImageAttributes-) | Draws the specified `Image` at the specified location and with the specified size. |
| [drawImage(Image image, Point[] destPoints)](#drawImage-com.aspose.imaging.Image-com.aspose.imaging.Point---) | Draws the specified portion of the specified `image` at the specified location and with the specified size. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect)](#drawImage-com.aspose.imaging.Image-com.aspose.imaging.Point---com.aspose.imaging.Rectangle-) | Draws the specified portion of the specified `image` at the specified location and with the specified size. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.imaging.Image-com.aspose.imaging.Point---com.aspose.imaging.Rectangle-int-) | Draws the specified portion of the specified `image` at the specified location and with the specified size. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.imaging.Image-com.aspose.imaging.Point---com.aspose.imaging.Rectangle-int-com.aspose.imaging.ImageAttributes-) | Draws the specified portion of the specified `image` at the specified location and with the specified size. |
| [drawImage(Image image, PointF[] destPoints)](#drawImage-com.aspose.imaging.Image-com.aspose.imaging.PointF---) | Draws the specified portion of the specified `image` at the specified location and with the specified size. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect)](#drawImage-com.aspose.imaging.Image-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-) | Draws the specified portion of the specified `image` at the specified location and with the specified size. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)](#drawImage-com.aspose.imaging.Image-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-int-) | Draws the specified portion of the specified `image` at the specified location and with the specified size. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.imaging.Image-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-int-com.aspose.imaging.ImageAttributes-) | Draws the specified portion of the specified `image` at the specified location and with the specified size. |
| [drawImage(Image sourceImage, float x, float y, float width, float height)](#drawImage-com.aspose.imaging.Image-float-float-float-float-) | Draws the specified `Image` at the specified location and with the specified size. |
| [drawImage(Image sourceImage, Point point)](#drawImage-com.aspose.imaging.Image-com.aspose.imaging.Point-) | Draws the specified `Image`, using its original physical size, at the specified location. |
| [drawImage(Image sourceImage, int x, int y)](#drawImage-com.aspose.imaging.Image-int-int-) | Draws the specified image, using its original physical size, at the location specified by a coordinate pair. |
| [drawImage(Image sourceImage, Rectangle rect)](#drawImage-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-) | Draws the specified `Image` at the specified location and with the specified size. |
| [drawImage(Image sourceImage, int x, int y, int width, int height)](#drawImage-com.aspose.imaging.Image-int-int-int-int-) | Draws the specified `Image` at the specified location and with the specified size. |
| [drawImageUnscaled(Image sourceImage, Point point)](#drawImageUnscaled-com.aspose.imaging.Image-com.aspose.imaging.Point-) | Draws a specified image using its original physical size at a specified location. |
| [drawImageUnscaled(Image sourceImage, int x, int y)](#drawImageUnscaled-com.aspose.imaging.Image-int-int-) | Draws the specified image using its original physical size at the location specified by a coordinate pair. |
| [drawImageUnscaled(Image sourceImage, Rectangle rect)](#drawImageUnscaled-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-) | Draws a specified image using its original physical size at a specified location. |
| [drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)](#drawImageUnscaled-com.aspose.imaging.Image-int-int-int-int-) | Draws a specified image using its original physical size at a specified location. |
| [drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)](#drawImageUnscaledAndClipped-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-) | Draws the specified image without scaling and clips it, if necessary, to fit in the specified rectangle. |
| [drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawArc-com.aspose.imaging.Pen-float-float-float-float-float-float-) | Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height. |
| [drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.RectangleF-float-float-) | Draws an arc representing a portion of an ellipse specified by a `RectangleF` structure. |
| [drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawArc-com.aspose.imaging.Pen-int-int-int-int-int-int-) | Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height. |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Draws an arc representing a portion of an ellipse specified by a `Rectangle` structure. |
| [drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.imaging.Pen-com.aspose.imaging.RectangleF-float-float-) | Draws a pie shape defined by an ellipse specified by a `RectangleF` structure and two radial lines. |
| [drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawPie-com.aspose.imaging.Pen-float-float-float-float-float-float-) | Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines. |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Draws a pie shape defined by an ellipse specified by a `Rectangle` structure and two radial lines. |
| [drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawPie-com.aspose.imaging.Pen-int-int-int-int-int-int-) | Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines. |
| [drawCurve(Pen pen, PointF[] points)](#drawCurve-com.aspose.imaging.Pen-com.aspose.imaging.PointF---) | Draws a cardinal spline through a specified array of `PointF` structures. |
| [drawCurve(Pen pen, PointF[] points, float tension)](#drawCurve-com.aspose.imaging.Pen-com.aspose.imaging.PointF---float-) | Draws a cardinal spline through a specified array of `PointF` structures using a specified tension. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)](#drawCurve-com.aspose.imaging.Pen-com.aspose.imaging.PointF---int-int-) | Draws a cardinal spline through a specified array of `PointF` structures. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.imaging.Pen-com.aspose.imaging.PointF---int-int-float-) | Draws a cardinal spline through a specified array of `PointF` structures using a specified tension. |
| [drawCurve(Pen pen, Point[] points)](#drawCurve-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Draws a cardinal spline through a specified array of `Point` structures. |
| [drawCurve(Pen pen, Point[] points, float tension)](#drawCurve-com.aspose.imaging.Pen-com.aspose.imaging.Point---float-) | Draws a cardinal spline through a specified array of `Point` structures using a specified tension. |
| [drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.imaging.Pen-com.aspose.imaging.Point---int-int-float-) | Draws a cardinal spline through a specified array of `Point` structures using a specified tension. |
| [drawClosedCurve(Pen pen, PointF[] points)](#drawClosedCurve-com.aspose.imaging.Pen-com.aspose.imaging.PointF---) | Draws a closed cardinal spline defined by an array of `PointF` structures. |
| [drawClosedCurve(Pen pen, PointF[] points, float tension)](#drawClosedCurve-com.aspose.imaging.Pen-com.aspose.imaging.PointF---float-) | Draws a closed cardinal spline defined by an array of `PointF` structures using a specified tension. |
| [drawClosedCurve(Pen pen, Point[] points)](#drawClosedCurve-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Draws a closed cardinal spline defined by an array of `Point` structures. |
| [drawClosedCurve(Pen pen, Point[] points, float tension)](#drawClosedCurve-com.aspose.imaging.Pen-com.aspose.imaging.Point---float-) | Draws a closed cardinal spline defined by an array of `Point` structures using a specified tension. |
| [drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)](#drawBezier-com.aspose.imaging.Pen-float-float-float-float-float-float-float-float-) | Draws a Bézier spline defined by four ordered pairs of coordinates that represent points. |
| [drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawBezier-com.aspose.imaging.Pen-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Draws a Bézier spline defined by four `PointF` structures. |
| [drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Draws a Bézier spline defined by four `Point` structures. |
| [drawBeziers(Pen pen, Point[] points)](#drawBeziers-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Draws a series of Bézier splines from an array of `Point` structures. |
| [drawBeziers(Pen pen, PointF[] points)](#drawBeziers-com.aspose.imaging.Pen-com.aspose.imaging.PointF---) | Draws a series of Bézier splines from an array of `PointF` structures. |
| [drawString(String s, Font font, Brush brush, float x, float y)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) | Draws the specified text string at the specified location with the specified `com.aspose.imaging.Brush` and `com.aspose.imaging.Font` objects. |
| [drawString(String s, Font font, Brush brush, PointF point)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-com.aspose.imaging.PointF-) | Draws the specified text string at the specified location with the specified `com.aspose.imaging.Brush` and `com.aspose.imaging.Font` objects. |
| [drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-com.aspose.imaging.StringFormat-) | Draws the specified text string at the specified location with the specified `com.aspose.imaging.Brush` and `com.aspose.imaging.Font` objects using the formatting attributes of the specified `com.aspose.imaging.stringFormat`. |
| [drawString(String s, Font font, Brush brush, PointF point, StringFormat format)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-com.aspose.imaging.PointF-com.aspose.imaging.StringFormat-) | Draws the specified text string at the specified location with the specified `com.aspose.imaging.Brush` and `com.aspose.imaging.Font` objects using the formatting attributes of the specified `com.aspose.imaging.stringFormat`. |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-com.aspose.imaging.RectangleF-) | Draws the specified text string in the specified rectangle with the specified `com.aspose.imaging.Brush` and `com.aspose.imaging.Font` objects. |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-com.aspose.imaging.RectangleF-com.aspose.imaging.StringFormat-) | Draws the specified text string in the specified rectangle with the specified `com.aspose.imaging.Brush` and `com.aspose.imaging.Font` objects using the formatting attributes of the specified `com.aspose.imaging.stringFormat`. |
| [fillEllipse(Brush brush, RectangleF rect)](#fillEllipse-com.aspose.imaging.Brush-com.aspose.imaging.RectangleF-) | Fills the interior of an ellipse defined by a bounding rectangle specified by a `com.aspose.imaging.RectangleF` structure. |
| [fillEllipse(Brush brush, float x, float y, float width, float height)](#fillEllipse-com.aspose.imaging.Brush-float-float-float-float-) | Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height. |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-) | Fills the interior of an ellipse defined by a bounding rectangle specified by a `com.aspose.imaging.Rectangle` structure. |
| [fillEllipse(Brush brush, int x, int y, int width, int height)](#fillEllipse-com.aspose.imaging.Brush-int-int-int-int-) | Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height. |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-) | Fills the interior of a pie section defined by an ellipse specified by a `com.aspose.imaging.RectangleF` structure and two radial lines. |
| [fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.imaging.Brush-com.aspose.imaging.RectangleF-float-float-) | Fills the interior of a pie section defined by an ellipse specified by a `com.aspose.imaging.RectangleF` structure and two radial lines. |
| [fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)](#fillPie-com.aspose.imaging.Brush-float-float-float-float-float-float-) | Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines. |
| [fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)](#fillPie-com.aspose.imaging.Brush-int-int-int-int-int-int-) | Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines. |
| [fillPolygon(Brush brush, PointF[] points)](#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.PointF---) | Fills the interior of a polygon defined by an array of points specified by `com.aspose.imaging.PointF` structures and `FillMode.Alternate`. |
| [fillPolygon(Brush brush, PointF[] points, int fillMode)](#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.PointF---int-) | Fills the interior of a polygon defined by an array of points specified by `com.aspose.imaging.PointF` structures using the specified fill mode. |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---) | Fills the interior of a polygon defined by an array of points specified by `com.aspose.imaging.Point` structures and `FillMode.Alternate`. |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-) | Fills the interior of a polygon defined by an array of points specified by `com.aspose.imaging.Point` structures using the specified fill mode. |
| [fillClosedCurve(Brush brush, PointF[] points)](#fillClosedCurve-com.aspose.imaging.Brush-com.aspose.imaging.PointF---) | Fills the interior of a closed cardinal spline curve defined by an array of `com.aspose.imaging.PointF` structures. |
| [fillClosedCurve(Brush brush, PointF[] points, int fillMode)](#fillClosedCurve-com.aspose.imaging.Brush-com.aspose.imaging.PointF---int-) | Fills the interior of a closed cardinal spline curve defined by an array of `com.aspose.imaging.PointF` structures using the specified fill mode. |
| [fillClosedCurve(Brush brush, PointF[] points, int fillMode, float tension)](#fillClosedCurve-com.aspose.imaging.Brush-com.aspose.imaging.PointF---int-float-) | Fills the interior of a closed cardinal spline curve defined by an array of `com.aspose.imaging.PointF` structures using the specified fill mode and tension. |
| [fillClosedCurve(Brush brush, Point[] points)](#fillClosedCurve-com.aspose.imaging.Brush-com.aspose.imaging.Point---) | Fills the interior of a closed cardinal spline curve defined by an array of `com.aspose.imaging.Point` structures. |
| [fillClosedCurve(Brush brush, Point[] points, int fillMode)](#fillClosedCurve-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-) | Fills the interior of a closed cardinal spline curve defined by an array of `com.aspose.imaging.Point` structures using the specified fill mode. |
| [fillClosedCurve(Brush brush, Point[] points, int fillMode, float tension)](#fillClosedCurve-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-float-) | Fills the interior of a closed cardinal spline curve defined by an array of `com.aspose.imaging.Point` structures using the specified fill mode and tension. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-) | Draws a `com.aspose.imaging.graphicsPath`. |
| [fillPath(Brush brush, GraphicsPath path)](#fillPath-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-) | Fills the interior of a `com.aspose.imaging.graphicsPath`. |
| [fillRegion(Brush brush, Region region)](#fillRegion-com.aspose.imaging.Brush-com.aspose.imaging.Region-) | Fills the interior of a [Region](../../com.aspose.imaging/region). |
| [measureString(String text, Font font, SizeF layoutArea, StringFormat stringFormat)](#measureString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.SizeF-com.aspose.imaging.StringFormat-) | Measures the specified text string with specified parameters |

## Example: This example uses Graphics class to create primitive shapes on the Image surface.
This example uses Graphics class to create primitive shapes on the Image surface. To demonstrate the operation, the example creates a new Image in PNG format and draw primitive shapes on Image surface using Draw methods exposed by Graphics class
``` java
// Creates an instance of FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Create an instance of PngOptions and set its various properties
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Set the Source for PngOptions
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Create an instance of Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // Create and initialize an instance of Graphics class
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Clear Graphics surface
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Draw an Arc by specifying the Pen object having Black com.aspose.imaging.Color,
        // a Rectangle surrounding the Arc, Start Angle and Sweep Angle
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // Draw a Bezier by specifying the Pen object having Blue com.aspose.imaging.Color and co-ordinate Points.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // Draw a Curve by specifying the Pen object having Green com.aspose.imaging.Color and an array of Points
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // Draw an Ellipse using the Pen object and a surrounding Rectangle
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // Draw a Line
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // Draw a Pie segment
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // Draw a Polygon by specifying the Pen object having Red com.aspose.imaging.Color and an array of Points
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // Draw a Rectangle
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // Create a SolidBrush object and set its various properties
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // Draw a String using the SolidBrush object and Font, at specific Point
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // Save all changes.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```


## Example: Support of PixelPerfect text alignment

``` java
String outputFileName = "TestExactAlignment.png";
try (com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions())
{
    pngOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(outputFileName));
    try (com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 100))
    {
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
        graphics.clear(com.aspose.imaging.Color.getWhite());
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getBlack());
        com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 24);
        graphics.drawString("DrawString with ExactAlignment",
                font,
                brush,
                new com.aspose.imaging.PointF(0, 0),
                new com.aspose.imaging.StringFormat(com.aspose.imaging.StringFormatFlags.ExactAlignment));

        graphics.drawString("DrawString without ExactAlignment",
                font,
                brush,
                new com.aspose.imaging.PointF(0, 30),
                new com.aspose.imaging.StringFormat());

        graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed()),
                new com.aspose.imaging.Rectangle(0, 0, 499, 99));
        image.save();
    }
}
```

### Graphics(Image sourceImage) {#Graphics-com.aspose.imaging.Image-}
```
public Graphics(Image sourceImage)
```


Initializes a new instance of the `Graphics` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.imaging/image) | The source image. |

### getDpiX() {#getDpiX--}
```
public float getDpiX()
```


Gets the horizontal resolution of this com.aspose.imaging.graphics.

**Returns:**
float - The value, in dots per inch, for the horizontal resolution supported by this com.aspose.imaging.graphics.
### getDpiY() {#getDpiY--}
```
public float getDpiY()
```


Gets the vertical resolution of this com.aspose.imaging.graphics.

**Returns:**
float - The value, in dots per inch, for the vertical resolution supported by this com.aspose.imaging.graphics.
### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Gets or sets the unit of measure used for page coordinates in this com.aspose.imaging.graphics.

**Returns:**
int - The unit of measure used for page coordinates in this com.aspose.imaging.graphics.
### setPageUnit(int value) {#setPageUnit-int-}
```
public void setPageUnit(int value)
```


Gets or sets the unit of measure used for page coordinates in this com.aspose.imaging.graphics.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The unit of measure used for page coordinates in this com.aspose.imaging.graphics. |

### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


Gets or sets the scaling between world units and page units for this com.aspose.imaging.graphics.

**Returns:**
float - The scaling between world units and page units for this com.aspose.imaging.graphics.
### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


Gets or sets the scaling between world units and page units for this com.aspose.imaging.graphics.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The scaling between world units and page units for this com.aspose.imaging.graphics. |

### getClip() {#getClip--}
```
public Region getClip()
```


Gets or sets the clip region.

**Returns:**
[Region](../../com.aspose.imaging/region) - The clip region.
### setClip(Region value) {#setClip-com.aspose.imaging.Region-}
```
public void setClip(Region value)
```


Gets or sets the clip region.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Region](../../com.aspose.imaging/region) | The clip region. |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Gets or sets a copy of the geometric world transformation for this `com.aspose.imaging.graphics`.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - A copy of the `com.aspose.imaging.Matrix` that represents the geometric world transformation for this `com.aspose.imaging.graphics`.
### setTransform(Matrix value) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix value)
```


Gets or sets a copy of the geometric world transformation for this `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) | A copy of the `com.aspose.imaging.Matrix` that represents the geometric world transformation for this `com.aspose.imaging.graphics`. |

### isInBeginUpdateCall() {#isInBeginUpdateCall--}
```
public boolean isInBeginUpdateCall()
```


Gets a value indicating whether graphics is in BeginUpdate call state.

**Returns:**
boolean - `True` if graphics is in BeginUpdate call state; otherwise, `false`.
### getImage() {#getImage--}
```
public Image getImage()
```


Gets the image.

**Returns:**
[Image](../../com.aspose.imaging/image) - The graphics image.
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


Gets or sets the compositing quality.

**Returns:**
int - The compositing quality.
### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


Gets or sets the compositing quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The compositing quality. |

### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


Gets or sets the interpolation mode.

**Returns:**
int - The interpolation mode.
### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


Gets or sets the interpolation mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The interpolation mode. |

### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


Gets or sets the smoothing mode.

**Returns:**
int - The smoothing mode.
### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


Gets or sets the smoothing mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The smoothing mode. |

### getTextRenderingHint() {#getTextRenderingHint--}
```
public int getTextRenderingHint()
```


Gets or sets the text rendering hint.

**Returns:**
int - The text rendering hint.
### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public void setTextRenderingHint(int value)
```


Gets or sets the text rendering hint.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The text rendering hint. |

### getPaintableImageOptions() {#getPaintableImageOptions--}
```
public ImageOptionsBase getPaintableImageOptions()
```


Gets image options, used to create paintable vector images to draw.

Value: The image options, used to create paintable vector images to draw.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - image options, used to create paintable vector images to draw.
### setPaintableImageOptions(ImageOptionsBase value) {#setPaintableImageOptions-com.aspose.imaging.ImageOptionsBase-}
```
public void setPaintableImageOptions(ImageOptionsBase value)
```


Sets image options, used to create paintable vector images to draw.

Value: The image options, used to create paintable vector images to draw.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | image options, used to create paintable vector images to draw. |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Resets the `com.aspose.imaging.graphics.Transform` property to identity.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplies the `com.aspose.imaging.Matrix` that represents the local geometric transform of this `com.aspose.imaging.Graphics` by the specified `com.aspose.imaging.Matrix` by prepending the specified `com.aspose.imaging.matrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | The `com.aspose.imaging.Matrix` by which to multiply the geometric transform. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplies the `com.aspose.imaging.Matrix` that represents the local geometric transform of this `com.aspose.imaging.Graphics` by the specified `com.aspose.imaging.Matrix` in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | The `com.aspose.imaging.Matrix` by which to multiply the geometric transform. |
| order | int | A `com.aspose.imaging.MatrixOrder` that specifies in which order to multiply the two matrices. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Translates the local geometric transform by the specified dimensions in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |
| order | int | The order (prepend or append) in which to apply the translation. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sx | float | The amount by which to scale the transform in the x-axis direction. |
| sy | float | The amount by which to scale the transform in the y-axis direction. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Scales the local geometric transform by the specified amounts in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sx | float | The amount by which to scale the transform in the x-axis direction. |
| sy | float | The amount by which to scale the transform in the y-axis direction. |
| order | int | A `com.aspose.imaging.MatrixOrder` that specifies whether to append or prepend the scaling matrix. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | The angle of rotation. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Rotates the local geometric transform by the specified amount in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | The angle of rotation. |
| order | int | A `com.aspose.imaging.MatrixOrder` that specifies whether to append or prepend the rotation matrix. |

### beginUpdate() {#beginUpdate--}
```
public void beginUpdate()
```


Starts caching of the following graphics operations. The graphics effects applied afterwards will not be applied immediately instead the EndUpdate will cause applying all the effects at once.

Note the effects after BeginUpdate is called will not be applied in case EndUpdate is not called.


**Example: The following example shows how to set a memory limit when creating a PNG image and drawing complex graphics on it.**
The following example shows how to set a memory limit when creating a PNG image and drawing complex graphics on it. The memory limit is the maximum allowed size (in megabytes) for all internal buffers.
``` java
String workDir = "c:\\temp\\";

final int ImageSize = 2000;
com.aspose.imaging.ImageOptionsBase createOptions = new com.aspose.imaging.imageoptions.PngOptions();
com.aspose.imaging.Image image;
try {
    createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(workDir + "temporary.png"));
    createOptions.setBufferSizeHint(30); // Memory limit is 30 Mb
    image = com.aspose.imaging.Image.create(createOptions, ImageSize, ImageSize);
    try {
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
        // You can use any graphic operations here, all of them will be performed within the established memory limit
        // For example:
        graphics.clear(com.aspose.imaging.Color.getLightSkyBlue());
        graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 3f), 0, 0, image.getWidth(), image.getHeight());
    } finally {
        image.close();
    }
} finally {
    createOptions.close();
}

// A large number of graphic operations are also supported:
final int OperationAreaSize = 10;
createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setBufferSizeHint(30); // Memory limit is 30 Mb
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(workDir + "temporary.png"));

try {
    image = com.aspose.imaging.Image.create(createOptions, ImageSize, ImageSize);
    try {
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
        graphics.beginUpdate();
        graphics.clear(com.aspose.imaging.Color.getLightSkyBlue());
        int x, y;
        for (int column = 0; column * OperationAreaSize < ImageSize; column++) {
            for (int row = 0; row * OperationAreaSize < ImageSize; row++) {
                x = column * OperationAreaSize;
                y = row * OperationAreaSize;

                boolean reversed = (column + row) % 2 != 0;
                if (reversed) {
                    graphics.drawLine(
                            new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed()),
                            x + OperationAreaSize - 2,
                            y,
                            x,
                            y + OperationAreaSize);
                } else {
                    graphics.drawLine(
                            new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed()),
                            x,
                            y,
                            x + OperationAreaSize - 2,
                            y + OperationAreaSize);
                }
            }
        }

        // About 40k operations will be applied here, while they do not take up too much memory
        // (since they are already unloaded into the external file, and will be loaded from there one at a time)
        graphics.endUpdate();
    } finally {
        image.close();
    }
} finally {
    createOptions.close();
}
```

### endUpdate() {#endUpdate--}
```
public void endUpdate()
```


Finishes caching of the graphics operations started after BeginUpdate was called. The preceding graphics operations will be applied at once when calling this method.


**Example: The following example shows how to set a memory limit when creating a PNG image and drawing complex graphics on it.**
The following example shows how to set a memory limit when creating a PNG image and drawing complex graphics on it. The memory limit is the maximum allowed size (in megabytes) for all internal buffers.
``` java
String workDir = "c:\\temp\\";

final int ImageSize = 2000;
com.aspose.imaging.ImageOptionsBase createOptions = new com.aspose.imaging.imageoptions.PngOptions();
com.aspose.imaging.Image image;
try {
    createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(workDir + "temporary.png"));
    createOptions.setBufferSizeHint(30); // Memory limit is 30 Mb
    image = com.aspose.imaging.Image.create(createOptions, ImageSize, ImageSize);
    try {
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
        // You can use any graphic operations here, all of them will be performed within the established memory limit
        // For example:
        graphics.clear(com.aspose.imaging.Color.getLightSkyBlue());
        graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 3f), 0, 0, image.getWidth(), image.getHeight());
    } finally {
        image.close();
    }
} finally {
    createOptions.close();
}

// A large number of graphic operations are also supported:
final int OperationAreaSize = 10;
createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setBufferSizeHint(30); // Memory limit is 30 Mb
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(workDir + "temporary.png"));

try {
    image = com.aspose.imaging.Image.create(createOptions, ImageSize, ImageSize);
    try {
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
        graphics.beginUpdate();
        graphics.clear(com.aspose.imaging.Color.getLightSkyBlue());
        int x, y;
        for (int column = 0; column * OperationAreaSize < ImageSize; column++) {
            for (int row = 0; row * OperationAreaSize < ImageSize; row++) {
                x = column * OperationAreaSize;
                y = row * OperationAreaSize;

                boolean reversed = (column + row) % 2 != 0;
                if (reversed) {
                    graphics.drawLine(
                            new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed()),
                            x + OperationAreaSize - 2,
                            y,
                            x,
                            y + OperationAreaSize);
                } else {
                    graphics.drawLine(
                            new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed()),
                            x,
                            y,
                            x + OperationAreaSize - 2,
                            y + OperationAreaSize);
                }
            }
        }

        // About 40k operations will be applied here, while they do not take up too much memory
        // (since they are already unloaded into the external file, and will be loaded from there one at a time)
        graphics.endUpdate();
    } finally {
        image.close();
    }
} finally {
    createOptions.close();
}
```

### clear(Color color) {#clear-com.aspose.imaging.Color-}
```
public void clear(Color color)
```


Clears the graphics surface using the specified color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | The color to clear the graphics surface by. |


**Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.**
This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface. Example creates a new Image (of type Tiff) and draw paths with the help of GraphicsPath class. At the end DrawPath method exposed by Graphics class is called to render the paths on surface.
``` java
// Create an instance of FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.tif", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Create an instance of TiffOptions and set its various properties
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

    // Set the source for the instance of ImageOptions
    tiffOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Create an instance of Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(tiffOptions, 500, 500);
    try {
        // Create and initialize an instance of Graphics class
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Clear Graphics surface
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Create an instance of GraphicsPath class
        com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

        // Create an instance of Figure class
        com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();

        // Add Shapes to Figure object
        figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300)));
        figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
        figure.addShape(
                new com.aspose.imaging.shapes.PieShape(new com.aspose.imaging.RectangleF(
                        new com.aspose.imaging.PointF(250, 250),
                        new com.aspose.imaging.SizeF(200, 200)),
                        0, 45));

        // Add Figure object to GraphicsPath
        graphicspath.addFigure(figure);

        // Draw path with Pen object of color Black
        graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

        // Save all changes.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### drawLine(Pen pen, Point point1, Point point2) {#drawLine-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public void drawLine(Pen pen, Point point1, Point point2)
```


Draws a line connecting two `Point` structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the line. |
| point1 | [Point](../../com.aspose.imaging/point) | `Point` structure that represents the first point to connect. |
| point2 | [Point](../../com.aspose.imaging/point) | `Point` structure that represents the second point to connect. |


**Example: This example uses Graphics class to create primitive shapes on the Image surface.**
This example uses Graphics class to create primitive shapes on the Image surface. To demonstrate the operation, the example creates a new Image in PNG format and draw primitive shapes on Image surface using Draw methods exposed by Graphics class
``` java
// Creates an instance of FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Create an instance of PngOptions and set its various properties
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Set the Source for PngOptions
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Create an instance of Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // Create and initialize an instance of Graphics class
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Clear Graphics surface
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Draw an Arc by specifying the Pen object having Black com.aspose.imaging.Color,
        // a Rectangle surrounding the Arc, Start Angle and Sweep Angle
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // Draw a Bezier by specifying the Pen object having Blue com.aspose.imaging.Color and co-ordinate Points.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // Draw a Curve by specifying the Pen object having Green com.aspose.imaging.Color and an array of Points
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // Draw an Ellipse using the Pen object and a surrounding Rectangle
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // Draw a Line
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // Draw a Pie segment
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // Draw a Polygon by specifying the Pen object having Red com.aspose.imaging.Color and an array of Points
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // Draw a Rectangle
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // Create a SolidBrush object and set its various properties
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // Draw a String using the SolidBrush object and Font, at specific Point
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // Save all changes.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### drawLine(Pen pen, PointF point1, PointF point2) {#drawLine-com.aspose.imaging.Pen-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public void drawLine(Pen pen, PointF point1, PointF point2)
```


Draws a line connecting two `PointF` structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the line. |
| point1 | [PointF](../../com.aspose.imaging/pointf) | `PointF` structure that represents the first point to connect. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | `PointF` structure that represents the second point to connect. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.imaging.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Draws a line connecting the two points specified by the coordinate pairs.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the line. |
| x1 | int | The x-coordinate of the first point. |
| y1 | int | The y-coordinate of the first point. |
| x2 | int | The x-coordinate of the second point. |
| y2 | int | The y-coordinate of the second point. |

### drawLine(Pen pen, float x1, float y1, float x2, float y2) {#drawLine-com.aspose.imaging.Pen-float-float-float-float-}
```
public void drawLine(Pen pen, float x1, float y1, float x2, float y2)
```


Draws a line connecting the two points specified by the coordinate pairs.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the line. |
| x1 | float | The x-coordinate of the first point. |
| y1 | float | The y-coordinate of the first point. |
| x2 | float | The x-coordinate of the second point. |
| y2 | float | The y-coordinate of the second point. |

### drawLines(Pen pen, Point[] points) {#drawLines-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawLines(Pen pen, Point[] points)
```


Draws a series of line segments that connect an array of `Point` structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the line segments. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Array of `Point` structures that represent the points to connect. |

### drawLines(Pen pen, PointF[] points) {#drawLines-com.aspose.imaging.Pen-com.aspose.imaging.PointF---}
```
public void drawLines(Pen pen, PointF[] points)
```


Draws a series of line segments that connect an array of `PointF` structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the line segments. |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Array of `PointF` structures that represent the points to connect. |

### fillRectangle(Brush brush, Rectangle rect) {#fillRectangle-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rect)
```


Fills the interior of a rectangle specified by a `Rectangle` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `Brush` that determines the characteristics of the fill. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | `Rectangle` structure that represents the rectangle to fill. |

### fillRectangle(Brush brush, RectangleF rect) {#fillRectangle-com.aspose.imaging.Brush-com.aspose.imaging.RectangleF-}
```
public void fillRectangle(Brush brush, RectangleF rect)
```


Fills the interior of a rectangle specified by a `RectangleF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `Brush` that determines the characteristics of the fill. |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | `RectangleF` structure that represents the rectangle to fill. |

### fillRectangle(Brush brush, float x, float y, float width, float height) {#fillRectangle-com.aspose.imaging.Brush-float-float-float-float-}
```
public void fillRectangle(Brush brush, float x, float y, float width, float height)
```


Fills the interior of a rectangle specified by a pair of coordinates, a width and a height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `Brush` that determines the characteristics of the fill. |
| x | float | The x-coordinate of the upper-left corner of the rectangle to fill. |
| y | float | The y-coordinate of the upper-left corner of the rectangle to fill. |
| width | float | Width of the rectangle to fill. |
| height | float | Height of the rectangle to fill. |

### fillRectangle(Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.imaging.Brush-int-int-int-int-}
```
public void fillRectangle(Brush brush, int x, int y, int width, int height)
```


Fills the interior of a rectangle specified by a pair of coordinates, a width and a height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `Brush` that determines the characteristics of the fill. |
| x | int | The x-coordinate of the upper-left corner of the rectangle to fill. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to fill. |
| width | int | Width of the rectangle to fill. |
| height | int | Height of the rectangle to fill. |

### fillRectangles(Brush brush, Rectangle[] rects) {#fillRectangles-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle---}
```
public void fillRectangles(Brush brush, Rectangle[] rects)
```


Fills the interiors of a series of rectangles specified by `Rectangle` structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `Brush` that determines the characteristics of the fill. |
| rects | [Rectangle\[\]](../../com.aspose.imaging/rectangle) | Array of `Rectangle` structures that represent the rectangles to fill. |

### fillRectangles(Brush brush, RectangleF[] rects) {#fillRectangles-com.aspose.imaging.Brush-com.aspose.imaging.RectangleF---}
```
public void fillRectangles(Brush brush, RectangleF[] rects)
```


Fills the interiors of a series of rectangles specified by `RectangleF` structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `Brush` that determines the characteristics of the fill. |
| rects | [RectangleF\[\]](../../com.aspose.imaging/rectanglef) | Array of `Rectangle` structures that represent the rectangles to fill. |

### drawRectangle(Pen pen, RectangleF rect) {#drawRectangle-com.aspose.imaging.Pen-com.aspose.imaging.RectangleF-}
```
public void drawRectangle(Pen pen, RectangleF rect)
```


Draws a rectangle specified by a `RectangleF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | A `Pen` that determines the color, width, and style of the rectangle. |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | A `RectangleF` structure that represents the rectangle to draw. |

### drawRectangle(Pen pen, Rectangle rect) {#drawRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rect)
```


Draws a rectangle specified by a `Rectangle` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | A `Pen` that determines the color, width, and style of the rectangle. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | A `Rectangle` structure that represents the rectangle to draw. |


**Example: This example uses Graphics class to create primitive shapes on the Image surface.**
This example uses Graphics class to create primitive shapes on the Image surface. To demonstrate the operation, the example creates a new Image in PNG format and draw primitive shapes on Image surface using Draw methods exposed by Graphics class
``` java
// Creates an instance of FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Create an instance of PngOptions and set its various properties
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Set the Source for PngOptions
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Create an instance of Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // Create and initialize an instance of Graphics class
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Clear Graphics surface
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Draw an Arc by specifying the Pen object having Black com.aspose.imaging.Color,
        // a Rectangle surrounding the Arc, Start Angle and Sweep Angle
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // Draw a Bezier by specifying the Pen object having Blue com.aspose.imaging.Color and co-ordinate Points.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // Draw a Curve by specifying the Pen object having Green com.aspose.imaging.Color and an array of Points
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // Draw an Ellipse using the Pen object and a surrounding Rectangle
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // Draw a Line
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // Draw a Pie segment
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // Draw a Polygon by specifying the Pen object having Red com.aspose.imaging.Color and an array of Points
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // Draw a Rectangle
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // Create a SolidBrush object and set its various properties
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // Draw a String using the SolidBrush object and Font, at specific Point
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // Save all changes.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### drawRectangle(Pen pen, float x, float y, float width, float height) {#drawRectangle-com.aspose.imaging.Pen-float-float-float-float-}
```
public void drawRectangle(Pen pen, float x, float y, float width, float height)
```


Draws a rectangle specified by a coordinate pair, a width, and a height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | A `Pen` that determines the color, width, and style of the rectangle. |
| x | float | The x-coordinate of the upper-left corner of the rectangle to draw. |
| y | float | The y-coordinate of the upper-left corner of the rectangle to draw. |
| width | float | The width of the rectangle to draw. |
| height | float | The height of the rectangle to draw. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Draws a rectangle specified by a coordinate pair, a width, and a height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the rectangle. |
| x | int | The x-coordinate of the upper-left corner of the rectangle to draw. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to draw. |
| width | int | Width of the rectangle to draw. |
| height | int | Height of the rectangle to draw. |

### drawRectangles(Pen pen, RectangleF[] rects) {#drawRectangles-com.aspose.imaging.Pen-com.aspose.imaging.RectangleF---}
```
public void drawRectangles(Pen pen, RectangleF[] rects)
```


Draws a series of rectangles specified by `RectangleF` structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the outlines of the rectangles. |
| rects | [RectangleF\[\]](../../com.aspose.imaging/rectanglef) | Array of `RectangleF` structures that represent the rectangles to draw. |

### drawRectangles(Pen pen, Rectangle[] rects) {#drawRectangles-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle---}
```
public void drawRectangles(Pen pen, Rectangle[] rects)
```


Draws a series of rectangles specified by `Rectangle` structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the outlines of the rectangles. |
| rects | [Rectangle\[\]](../../com.aspose.imaging/rectangle) | Array of `Rectangle` structures that represent the rectangles to draw. |


**Example: This example shows the creation and usage Pen objects.**
This example shows the creation and usage Pen objects. The example creates a new Image and draw Rectangles on Image surface.
``` java

// Create an instance of BmpOptions and set its various properties
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Create an instance of FileCreateSource and assign it as Source for the instance of BmpOptions
// Second Boolean parameter determines if the file to be created IsTemporal or not
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Create an instance of Image at specified Path
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Create an instance of Graphics and initialize it with Image object
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Clear the Graphics sutface with White Color
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Create an instance of Pen with color Red and width 5
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // Create an instance of HatchBrush and set its properties
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Create an instance of Pen and initialize it with HatchBrush object and width
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Draw Rectangles by specifying Pen object
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Draw Rectangles by specifying Pen object
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Save all changes.
    image.save();
} finally {
    image.dispose();
}
```

### drawEllipse(Pen pen, RectangleF rect) {#drawEllipse-com.aspose.imaging.Pen-com.aspose.imaging.RectangleF-}
```
public void drawEllipse(Pen pen, RectangleF rect)
```


Draws an ellipse defined by a bounding `RectangleF`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the ellipse. |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | `RectangleF` structure that defines the boundaries of the ellipse. |

### drawEllipse(Pen pen, float x, float y, float width, float height) {#drawEllipse-com.aspose.imaging.Pen-float-float-float-float-}
```
public void drawEllipse(Pen pen, float x, float y, float width, float height)
```


Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the ellipse. |
| x | float | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| y | float | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| width | float | Width of the bounding rectangle that defines the ellipse. |
| height | float | Height of the bounding rectangle that defines the ellipse. |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


Draws an ellipse specified by a bounding `Rectangle` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the ellipse. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | `Rectangle` structure that defines the boundaries of the ellipse. |


**Example: This example uses Graphics class to create primitive shapes on the Image surface.**
This example uses Graphics class to create primitive shapes on the Image surface. To demonstrate the operation, the example creates a new Image in PNG format and draw primitive shapes on Image surface using Draw methods exposed by Graphics class
``` java
// Creates an instance of FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Create an instance of PngOptions and set its various properties
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Set the Source for PngOptions
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Create an instance of Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // Create and initialize an instance of Graphics class
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Clear Graphics surface
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Draw an Arc by specifying the Pen object having Black com.aspose.imaging.Color,
        // a Rectangle surrounding the Arc, Start Angle and Sweep Angle
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // Draw a Bezier by specifying the Pen object having Blue com.aspose.imaging.Color and co-ordinate Points.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // Draw a Curve by specifying the Pen object having Green com.aspose.imaging.Color and an array of Points
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // Draw an Ellipse using the Pen object and a surrounding Rectangle
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // Draw a Line
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // Draw a Pie segment
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // Draw a Polygon by specifying the Pen object having Red com.aspose.imaging.Color and an array of Points
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // Draw a Rectangle
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // Create a SolidBrush object and set its various properties
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // Draw a String using the SolidBrush object and Font, at specific Point
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // Save all changes.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### drawEllipse(Pen pen, int x, int y, int width, int height) {#drawEllipse-com.aspose.imaging.Pen-int-int-int-int-}
```
public void drawEllipse(Pen pen, int x, int y, int width, int height)
```


Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the ellipse. |
| x | int | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| y | int | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| width | int | Width of the bounding rectangle that defines the ellipse. |
| height | int | Height of the bounding rectangle that defines the ellipse. |

### drawPolygon(Pen pen, PointF[] points) {#drawPolygon-com.aspose.imaging.Pen-com.aspose.imaging.PointF---}
```
public void drawPolygon(Pen pen, PointF[] points)
```


Draws a polygon defined by an array of `PointF` structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the polygon. |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Array of `PointF` structures that represent the vertices of the polygon. |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


Draws a polygon defined by an array of `Point` structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the polygon. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Array of `Point` structures that represent the vertices of the polygon. |


**Example: This example uses Graphics class to create primitive shapes on the Image surface.**
This example uses Graphics class to create primitive shapes on the Image surface. To demonstrate the operation, the example creates a new Image in PNG format and draw primitive shapes on Image surface using Draw methods exposed by Graphics class
``` java
// Creates an instance of FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Create an instance of PngOptions and set its various properties
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Set the Source for PngOptions
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Create an instance of Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // Create and initialize an instance of Graphics class
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Clear Graphics surface
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Draw an Arc by specifying the Pen object having Black com.aspose.imaging.Color,
        // a Rectangle surrounding the Arc, Start Angle and Sweep Angle
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // Draw a Bezier by specifying the Pen object having Blue com.aspose.imaging.Color and co-ordinate Points.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // Draw a Curve by specifying the Pen object having Green com.aspose.imaging.Color and an array of Points
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // Draw an Ellipse using the Pen object and a surrounding Rectangle
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // Draw a Line
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // Draw a Pie segment
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // Draw a Polygon by specifying the Pen object having Red com.aspose.imaging.Color and an array of Points
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // Draw a Rectangle
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // Create a SolidBrush object and set its various properties
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // Draw a String using the SolidBrush object and Font, at specific Point
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // Save all changes.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### drawImage(Image sourceImage, PointF point) {#drawImage-com.aspose.imaging.Image-com.aspose.imaging.PointF-}
```
public void drawImage(Image sourceImage, PointF point)
```


Draws the specified `Image`, using its original physical size, at the specified location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.imaging/image) | The image to draw with. |
| point | [PointF](../../com.aspose.imaging/pointf) | `PointF` structure that represents the upper-left corner of the drawn image. |

### drawImage(Image sourceImage, float x, float y) {#drawImage-com.aspose.imaging.Image-float-float-}
```
public void drawImage(Image sourceImage, float x, float y)
```


Draws the specified `Image`, using its original physical size, at the specified location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.imaging/image) | The image to draw with. |
| x | float | The x-coordinate of the upper-left corner of the drawn image. |
| y | float | The y-coordinate of the upper-left corner of the drawn image. |

### drawImage(Image sourceImage, RectangleF rect) {#drawImage-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-}
```
public void drawImage(Image sourceImage, RectangleF rect)
```


Draws the specified `Image` at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.imaging/image) | The image to draw with. |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | `RectangleF` structure that specifies the location and size of the drawn image. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)
```


Draws the specified `Image` at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.imaging/image) | The image to draw with. |
| rectDestination | [Rectangle](../../com.aspose.imaging/rectangle) | The destination rectangle. |
| graphicsUnit | int | The graphics unit. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)
```


Draws the specified `Image` at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.imaging/image) | The image to draw with. |
| rectDestination | [RectangleF](../../com.aspose.imaging/rectanglef) | The destination rectangle. |
| graphicsUnit | int | The graphics unit. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-int-com.aspose.imaging.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Draws the specified `Image` at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.imaging/image) | The image to draw with. |
| rectDestination | [Rectangle](../../com.aspose.imaging/rectangle) | The destination rectangle. |
| graphicsUnit | int | The graphics unit. |
| imageAttributes | [ImageAttributes](../../com.aspose.imaging/imageattributes) | The image attributes. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-int-com.aspose.imaging.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Draws the specified `Image` at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.imaging/image) | The image to draw with. |
| rectDestination | [RectangleF](../../com.aspose.imaging/rectanglef) | The destination rectangle to draw in. |
| graphicsUnit | int | The graphics unit. |
| imageAttributes | [ImageAttributes](../../com.aspose.imaging/imageattributes) | The image attributes. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)
```


Draws the specified `Image` at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.imaging/image) | The image to draw with. |
| rectSource | [Rectangle](../../com.aspose.imaging/rectangle) | The rect source. |
| rectDestination | [Rectangle](../../com.aspose.imaging/rectangle) | The rect destination. |
| graphicsUnit | int | The graphics unit. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)
```


Draws the specified `Image` at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.imaging/image) | The image to draw with. |
| rectSource | [RectangleF](../../com.aspose.imaging/rectanglef) | The rect source. |
| rectDestination | [RectangleF](../../com.aspose.imaging/rectanglef) | The rect destination. |
| graphicsUnit | int | The graphics unit. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-int-com.aspose.imaging.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Draws the specified `Image` at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.imaging/image) | The image to draw with. |
| rectSource | [Rectangle](../../com.aspose.imaging/rectangle) | The rect source. |
| rectDestination | [Rectangle](../../com.aspose.imaging/rectangle) | The rect destination. |
| graphicsUnit | int | The graphics unit. |
| imageAttributes | [ImageAttributes](../../com.aspose.imaging/imageattributes) | The image attributes. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.imaging.Image-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-int-com.aspose.imaging.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Draws the specified `Image` at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.imaging/image) | The image to draw with. |
| rectSource | [RectangleF](../../com.aspose.imaging/rectanglef) | The source rectangle. |
| rectDestination | [RectangleF](../../com.aspose.imaging/rectanglef) | The destination rectangle. |
| graphicsUnit | int | The graphics unit to use. |
| imageAttributes | [ImageAttributes](../../com.aspose.imaging/imageattributes) | The image attributes to use. |

### drawImage(Image image, Point[] destPoints) {#drawImage-com.aspose.imaging.Image-com.aspose.imaging.Point---}
```
public void drawImage(Image image, Point[] destPoints)
```


Draws the specified portion of the specified `image` at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The image to draw. |
| destPoints | [Point\[\]](../../com.aspose.imaging/point) | Array of three PointF structures that define a parallelogram. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect) {#drawImage-com.aspose.imaging.Image-com.aspose.imaging.Point---com.aspose.imaging.Rectangle-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect)
```


Draws the specified portion of the specified `image` at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The image to draw. |
| destPoints | [Point\[\]](../../com.aspose.imaging/point) | Array of three PointF structures that define a parallelogram. |
| srcRect | [Rectangle](../../com.aspose.imaging/rectangle) | The source rectangle. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.imaging.Image-com.aspose.imaging.Point---com.aspose.imaging.Rectangle-int-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)
```


Draws the specified portion of the specified `image` at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The image to draw. |
| destPoints | [Point\[\]](../../com.aspose.imaging/point) | Array of three PointF structures that define a parallelogram. |
| srcRect | [Rectangle](../../com.aspose.imaging/rectangle) | The source rectangle. |
| srcUnit | int | The units of measure. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.imaging.Image-com.aspose.imaging.Point---com.aspose.imaging.Rectangle-int-com.aspose.imaging.ImageAttributes-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)
```


Draws the specified portion of the specified `image` at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The image to draw. |
| destPoints | [Point\[\]](../../com.aspose.imaging/point) | Array of three PointF structures that define a parallelogram. |
| srcRect | [Rectangle](../../com.aspose.imaging/rectangle) | The source rectangle. |
| srcUnit | int | The units of measure. |
| imageAttributes | [ImageAttributes](../../com.aspose.imaging/imageattributes) | The image attributes. |

### drawImage(Image image, PointF[] destPoints) {#drawImage-com.aspose.imaging.Image-com.aspose.imaging.PointF---}
```
public void drawImage(Image image, PointF[] destPoints)
```


Draws the specified portion of the specified `image` at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The image to draw. |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Array of three PointF structures that define a parallelogram. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect) {#drawImage-com.aspose.imaging.Image-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect)
```


Draws the specified portion of the specified `image` at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The image to draw. |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Array of three PointF structures that define a parallelogram. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | The source rectangle. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit) {#drawImage-com.aspose.imaging.Image-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-int-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)
```


Draws the specified portion of the specified `image` at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The image to draw. |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Array of three PointF structures that define a parallelogram. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | The source rectangle. |
| srcUnit | int | The units of measure. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.imaging.Image-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-int-com.aspose.imaging.ImageAttributes-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)
```


Draws the specified portion of the specified `image` at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The image to draw. |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Array of three PointF structures that define a parallelogram. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | The source rectangle. |
| srcUnit | int | The units of measure. |
| imageAttributes | [ImageAttributes](../../com.aspose.imaging/imageattributes) | The image attributes. |

### drawImage(Image sourceImage, float x, float y, float width, float height) {#drawImage-com.aspose.imaging.Image-float-float-float-float-}
```
public void drawImage(Image sourceImage, float x, float y, float width, float height)
```


Draws the specified `Image` at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.imaging/image) | The image to draw with. |
| x | float | The x-coordinate of the upper-left corner of the drawn image. |
| y | float | The y-coordinate of the upper-left corner of the drawn image. |
| width | float | Width of the drawn image. |
| height | float | Height of the drawn image. |

### drawImage(Image sourceImage, Point point) {#drawImage-com.aspose.imaging.Image-com.aspose.imaging.Point-}
```
public void drawImage(Image sourceImage, Point point)
```


Draws the specified `Image`, using its original physical size, at the specified location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.imaging/image) | The image to draw with. |
| point | [Point](../../com.aspose.imaging/point) | `Point` structure that represents the location of the upper-left corner of the drawn image. |

### drawImage(Image sourceImage, int x, int y) {#drawImage-com.aspose.imaging.Image-int-int-}
```
public void drawImage(Image sourceImage, int x, int y)
```


Draws the specified image, using its original physical size, at the location specified by a coordinate pair.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.imaging/image) | The image to draw with. |
| x | int | The x-coordinate of the upper-left corner of the drawn image. |
| y | int | The y-coordinate of the upper-left corner of the drawn image. |

### drawImage(Image sourceImage, Rectangle rect) {#drawImage-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-}
```
public void drawImage(Image sourceImage, Rectangle rect)
```


Draws the specified `Image` at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.imaging/image) | The image to draw with. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | `Rectangle` structure that specifies the location and size of the drawn image. |

### drawImage(Image sourceImage, int x, int y, int width, int height) {#drawImage-com.aspose.imaging.Image-int-int-int-int-}
```
public void drawImage(Image sourceImage, int x, int y, int width, int height)
```


Draws the specified `Image` at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.imaging/image) | The image to draw with. |
| x | int | The x-coordinate of the upper-left corner of the drawn image. |
| y | int | The y-coordinate of the upper-left corner of the drawn image. |
| width | int | Width of the drawn image. |
| height | int | Height of the drawn image. |

### drawImageUnscaled(Image sourceImage, Point point) {#drawImageUnscaled-com.aspose.imaging.Image-com.aspose.imaging.Point-}
```
public void drawImageUnscaled(Image sourceImage, Point point)
```


Draws a specified image using its original physical size at a specified location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.imaging/image) | The image to draw with. |
| point | [Point](../../com.aspose.imaging/point) | `Point` structure that specifies the upper-left corner of the drawn image. |

### drawImageUnscaled(Image sourceImage, int x, int y) {#drawImageUnscaled-com.aspose.imaging.Image-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y)
```


Draws the specified image using its original physical size at the location specified by a coordinate pair.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.imaging/image) | The image to draw with. |
| x | int | The x-coordinate of the upper-left corner of the drawn image. |
| y | int | The y-coordinate of the upper-left corner of the drawn image. |

### drawImageUnscaled(Image sourceImage, Rectangle rect) {#drawImageUnscaled-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-}
```
public void drawImageUnscaled(Image sourceImage, Rectangle rect)
```


Draws a specified image using its original physical size at a specified location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.imaging/image) | The image to draw with. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | `Rectangle` that specifies the upper-left corner of the drawn image. The X and Y properties of the rectangle specify the upper-left corner. The Width and Height properties are ignored. |

### drawImageUnscaled(Image sourceImage, int x, int y, int width, int height) {#drawImageUnscaled-com.aspose.imaging.Image-int-int-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)
```


Draws a specified image using its original physical size at a specified location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.imaging/image) | The image to draw with. |
| x | int | The x-coordinate of the upper-left corner of the drawn image. |
| y | int | The y-coordinate of the upper-left corner of the drawn image. |
| width | int | The parameter is not used. |
| height | int | The parameter is not used. |

### drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect) {#drawImageUnscaledAndClipped-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-}
```
public void drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)
```


Draws the specified image without scaling and clips it, if necessary, to fit in the specified rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.imaging/image) | The image to draw with. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | The `Rectangle` in which to draw the image. |

### drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawArc-com.aspose.imaging.Pen-float-float-float-float-float-float-}
```
public void drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the arc. |
| x | float | The x-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| y | float | The y-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| width | float | Width of the rectangle that defines the ellipse. |
| height | float | Height of the rectangle that defines the ellipse. |
| startAngle | float | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweepAngle | float | Angle in degrees measured clockwise from the `startAngle` parameter to ending point of the arc. |

### drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.RectangleF-float-float-}
```
public void drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


Draws an arc representing a portion of an ellipse specified by a `RectangleF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the arc. |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | `RectangleF` structure that defines the boundaries of the ellipse. |
| startAngle | float | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweepAngle | float | Angle in degrees measured clockwise from the `startAngle` parameter to ending point of the arc. |

### drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawArc-com.aspose.imaging.Pen-int-int-int-int-int-int-}
```
public void drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the arc. |
| x | int | The x-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| y | int | The y-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| width | int | Width of the rectangle that defines the ellipse. |
| height | int | Height of the rectangle that defines the ellipse. |
| startAngle | int | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweepAngle | int | Angle in degrees measured clockwise from the `startAngle` parameter to ending point of the arc. |

### drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Draws an arc representing a portion of an ellipse specified by a `Rectangle` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the arc. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | `RectangleF` structure that defines the boundaries of the ellipse. |
| startAngle | float | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweepAngle | float | Angle in degrees measured clockwise from the `startAngle` parameter to ending point of the arc. |


**Example: This example uses Graphics class to create primitive shapes on the Image surface.**
This example uses Graphics class to create primitive shapes on the Image surface. To demonstrate the operation, the example creates a new Image in PNG format and draw primitive shapes on Image surface using Draw methods exposed by Graphics class
``` java
// Creates an instance of FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Create an instance of PngOptions and set its various properties
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Set the Source for PngOptions
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Create an instance of Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // Create and initialize an instance of Graphics class
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Clear Graphics surface
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Draw an Arc by specifying the Pen object having Black com.aspose.imaging.Color,
        // a Rectangle surrounding the Arc, Start Angle and Sweep Angle
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // Draw a Bezier by specifying the Pen object having Blue com.aspose.imaging.Color and co-ordinate Points.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // Draw a Curve by specifying the Pen object having Green com.aspose.imaging.Color and an array of Points
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // Draw an Ellipse using the Pen object and a surrounding Rectangle
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // Draw a Line
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // Draw a Pie segment
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // Draw a Polygon by specifying the Pen object having Red com.aspose.imaging.Color and an array of Points
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // Draw a Rectangle
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // Create a SolidBrush object and set its various properties
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // Draw a String using the SolidBrush object and Font, at specific Point
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // Save all changes.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.imaging.Pen-com.aspose.imaging.RectangleF-float-float-}
```
public void drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


Draws a pie shape defined by an ellipse specified by a `RectangleF` structure and two radial lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the pie shape. |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | `RectangleF` structure that represents the bounding rectangle that defines the ellipse from which the pie shape comes. |
| startAngle | float | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweepAngle | float | Angle measured in degrees clockwise from the `startAngle` parameter to the second side of the pie shape. |

### drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawPie-com.aspose.imaging.Pen-float-float-float-float-float-float-}
```
public void drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the pie shape. |
| x | float | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| y | float | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| width | float | Width of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| height | float | Height of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| startAngle | float | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweepAngle | float | Angle measured in degrees clockwise from the `startAngle` parameter to the second side of the pie shape. |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Draws a pie shape defined by an ellipse specified by a `Rectangle` structure and two radial lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the pie shape. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | `Rectangle` structure that represents the bounding rectangle that defines the ellipse from which the pie shape comes. |
| startAngle | float | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweepAngle | float | Angle measured in degrees clockwise from the `startAngle` parameter to the second side of the pie shape. |


**Example: This example uses Graphics class to create primitive shapes on the Image surface.**
This example uses Graphics class to create primitive shapes on the Image surface. To demonstrate the operation, the example creates a new Image in PNG format and draw primitive shapes on Image surface using Draw methods exposed by Graphics class
``` java
// Creates an instance of FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Create an instance of PngOptions and set its various properties
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Set the Source for PngOptions
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Create an instance of Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // Create and initialize an instance of Graphics class
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Clear Graphics surface
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Draw an Arc by specifying the Pen object having Black com.aspose.imaging.Color,
        // a Rectangle surrounding the Arc, Start Angle and Sweep Angle
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // Draw a Bezier by specifying the Pen object having Blue com.aspose.imaging.Color and co-ordinate Points.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // Draw a Curve by specifying the Pen object having Green com.aspose.imaging.Color and an array of Points
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // Draw an Ellipse using the Pen object and a surrounding Rectangle
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // Draw a Line
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // Draw a Pie segment
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // Draw a Polygon by specifying the Pen object having Red com.aspose.imaging.Color and an array of Points
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // Draw a Rectangle
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // Create a SolidBrush object and set its various properties
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // Draw a String using the SolidBrush object and Font, at specific Point
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // Save all changes.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawPie-com.aspose.imaging.Pen-int-int-int-int-int-int-}
```
public void drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the pie shape. |
| x | int | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| y | int | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| width | int | Width of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| height | int | Height of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| startAngle | int | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweepAngle | int | Angle measured in degrees clockwise from the `startAngle` parameter to the second side of the pie shape. |

### drawCurve(Pen pen, PointF[] points) {#drawCurve-com.aspose.imaging.Pen-com.aspose.imaging.PointF---}
```
public void drawCurve(Pen pen, PointF[] points)
```


Draws a cardinal spline through a specified array of `PointF` structures. This method uses a default tension of 0.5.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and height of the curve. |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Array of `PointF` structures that define the spline. |

### drawCurve(Pen pen, PointF[] points, float tension) {#drawCurve-com.aspose.imaging.Pen-com.aspose.imaging.PointF---float-}
```
public void drawCurve(Pen pen, PointF[] points, float tension)
```


Draws a cardinal spline through a specified array of `PointF` structures using a specified tension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and height of the curve. |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Array of `PointF` structures that represent the points that define the curve. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments) {#drawCurve-com.aspose.imaging.Pen-com.aspose.imaging.PointF---int-int-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```


Draws a cardinal spline through a specified array of `PointF` structures. The drawing begins offset from the beginning of the array. This method uses a default tension of 0.5.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and height of the curve. |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Array of `PointF` structures that define the spline. |
| offset | int | Offset from the first element in the array of the `points` parameter to the starting point in the curve. |
| numberOfSegments | int | Number of segments after the starting point to include in the curve. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.imaging.Pen-com.aspose.imaging.PointF---int-int-float-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```


Draws a cardinal spline through a specified array of `PointF` structures using a specified tension. The drawing begins offset from the beginning of the array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and height of the curve. |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Array of `PointF` structures that define the spline. |
| offset | int | Offset from the first element in the array of the `points` parameter to the starting point in the curve. |
| numberOfSegments | int | Number of segments after the starting point to include in the curve. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### drawCurve(Pen pen, Point[] points) {#drawCurve-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawCurve(Pen pen, Point[] points)
```


Draws a cardinal spline through a specified array of `Point` structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and height of the curve. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Array of `Point` structures that define the spline. |


**Example: This example uses Graphics class to create primitive shapes on the Image surface.**
This example uses Graphics class to create primitive shapes on the Image surface. To demonstrate the operation, the example creates a new Image in PNG format and draw primitive shapes on Image surface using Draw methods exposed by Graphics class
``` java
// Creates an instance of FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Create an instance of PngOptions and set its various properties
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Set the Source for PngOptions
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Create an instance of Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // Create and initialize an instance of Graphics class
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Clear Graphics surface
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Draw an Arc by specifying the Pen object having Black com.aspose.imaging.Color,
        // a Rectangle surrounding the Arc, Start Angle and Sweep Angle
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // Draw a Bezier by specifying the Pen object having Blue com.aspose.imaging.Color and co-ordinate Points.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // Draw a Curve by specifying the Pen object having Green com.aspose.imaging.Color and an array of Points
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // Draw an Ellipse using the Pen object and a surrounding Rectangle
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // Draw a Line
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // Draw a Pie segment
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // Draw a Polygon by specifying the Pen object having Red com.aspose.imaging.Color and an array of Points
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // Draw a Rectangle
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // Create a SolidBrush object and set its various properties
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // Draw a String using the SolidBrush object and Font, at specific Point
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // Save all changes.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### drawCurve(Pen pen, Point[] points, float tension) {#drawCurve-com.aspose.imaging.Pen-com.aspose.imaging.Point---float-}
```
public void drawCurve(Pen pen, Point[] points, float tension)
```


Draws a cardinal spline through a specified array of `Point` structures using a specified tension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and height of the curve. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Array of `Point` structures that define the spline. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.imaging.Pen-com.aspose.imaging.Point---int-int-float-}
```
public void drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```


Draws a cardinal spline through a specified array of `Point` structures using a specified tension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and height of the curve. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Array of `Point` structures that define the spline. |
| offset | int | Offset from the first element in the array of the `points` parameter to the starting point in the curve. |
| numberOfSegments | int | Number of segments after the starting point to include in the curve. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### drawClosedCurve(Pen pen, PointF[] points) {#drawClosedCurve-com.aspose.imaging.Pen-com.aspose.imaging.PointF---}
```
public void drawClosedCurve(Pen pen, PointF[] points)
```


Draws a closed cardinal spline defined by an array of `PointF` structures. This method uses a default tension of 0.5 and `FillMode.Alternate` fill mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and height of the curve. |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Array of `PointF` structures that define the spline. |

### drawClosedCurve(Pen pen, PointF[] points, float tension) {#drawClosedCurve-com.aspose.imaging.Pen-com.aspose.imaging.PointF---float-}
```
public void drawClosedCurve(Pen pen, PointF[] points, float tension)
```


Draws a closed cardinal spline defined by an array of `PointF` structures using a specified tension. This method uses a default `FillMode.Alternate` fill mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and height of the curve. |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Array of `PointF` structures that define the spline. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### drawClosedCurve(Pen pen, Point[] points) {#drawClosedCurve-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawClosedCurve(Pen pen, Point[] points)
```


Draws a closed cardinal spline defined by an array of `Point` structures. This method uses a default tension of 0.5 and `FillMode.Alternate` fill mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and height of the curve. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Array of `Point` structures that define the spline. |

### drawClosedCurve(Pen pen, Point[] points, float tension) {#drawClosedCurve-com.aspose.imaging.Pen-com.aspose.imaging.Point---float-}
```
public void drawClosedCurve(Pen pen, Point[] points, float tension)
```


Draws a closed cardinal spline defined by an array of `Point` structures using a specified tension. This method uses a default `FillMode.Alternate` fill mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and height of the curve. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Array of `Point` structures that define the spline. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4) {#drawBezier-com.aspose.imaging.Pen-float-float-float-float-float-float-float-float-}
```
public void drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)
```


Draws a Bézier spline defined by four ordered pairs of coordinates that represent points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the curve. |
| x1 | float | The x-coordinate of the starting point of the curve. |
| y1 | float | The y-coordinate of the starting point of the curve. |
| x2 | float | The x-coordinate of the first control point of the curve. |
| y2 | float | The y-coordinate of the first control point of the curve. |
| x3 | float | The x-coordinate of the second control point of the curve. |
| y3 | float | The y-coordinate of the second control point of the curve. |
| x4 | float | The x-coordinate of the ending point of the curve. |
| y4 | float | The y-coordinate of the ending point of the curve. |

### drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawBezier-com.aspose.imaging.Pen-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public void drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


Draws a Bézier spline defined by four `PointF` structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the curve. |
| pt1 | [PointF](../../com.aspose.imaging/pointf) | `PointF` structure that represents the starting point of the curve. |
| pt2 | [PointF](../../com.aspose.imaging/pointf) | `PointF` structure that represents the first control point for the curve. |
| pt3 | [PointF](../../com.aspose.imaging/pointf) | `PointF` structure that represents the second control point for the curve. |
| pt4 | [PointF](../../com.aspose.imaging/pointf) | `PointF` structure that represents the ending point of the curve. |

### drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public void drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


Draws a Bézier spline defined by four `Point` structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` structure that determines the color, width, and style of the curve. |
| pt1 | [Point](../../com.aspose.imaging/point) | `Point` structure that represents the starting point of the curve. |
| pt2 | [Point](../../com.aspose.imaging/point) | `Point` structure that represents the first control point for the curve. |
| pt3 | [Point](../../com.aspose.imaging/point) | `Point` structure that represents the second control point for the curve. |
| pt4 | [Point](../../com.aspose.imaging/point) | `Point` structure that represents the ending point of the curve. |


**Example: This example uses Graphics class to create primitive shapes on the Image surface.**
This example uses Graphics class to create primitive shapes on the Image surface. To demonstrate the operation, the example creates a new Image in PNG format and draw primitive shapes on Image surface using Draw methods exposed by Graphics class
``` java
// Creates an instance of FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Create an instance of PngOptions and set its various properties
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Set the Source for PngOptions
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Create an instance of Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // Create and initialize an instance of Graphics class
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Clear Graphics surface
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Draw an Arc by specifying the Pen object having Black com.aspose.imaging.Color,
        // a Rectangle surrounding the Arc, Start Angle and Sweep Angle
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // Draw a Bezier by specifying the Pen object having Blue com.aspose.imaging.Color and co-ordinate Points.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // Draw a Curve by specifying the Pen object having Green com.aspose.imaging.Color and an array of Points
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // Draw an Ellipse using the Pen object and a surrounding Rectangle
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // Draw a Line
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // Draw a Pie segment
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // Draw a Polygon by specifying the Pen object having Red com.aspose.imaging.Color and an array of Points
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // Draw a Rectangle
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // Create a SolidBrush object and set its various properties
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // Draw a String using the SolidBrush object and Font, at specific Point
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // Save all changes.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### drawBeziers(Pen pen, Point[] points) {#drawBeziers-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawBeziers(Pen pen, Point[] points)
```


Draws a series of Bézier splines from an array of `Point` structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the curve. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Array of `Point` structures that represent the points that determine the curve. |

### drawBeziers(Pen pen, PointF[] points) {#drawBeziers-com.aspose.imaging.Pen-com.aspose.imaging.PointF---}
```
public void drawBeziers(Pen pen, PointF[] points)
```


Draws a series of Bézier splines from an array of `PointF` structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `Pen` that determines the color, width, and style of the curve. |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Array of `PointF` structures that represent the points that determine the curve. |

### drawString(String s, Font font, Brush brush, float x, float y) {#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-}
```
public void drawString(String s, Font font, Brush brush, float x, float y)
```


Draws the specified text string at the specified location with the specified `com.aspose.imaging.Brush` and `com.aspose.imaging.Font` objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | java.lang.String | String to draw. |
| font | [Font](../../com.aspose.imaging/font) | `com.aspose.imaging.Font` that defines the text format of the string. |
| brush | [Brush](../../com.aspose.imaging/brush) | `com.aspose.imaging.Brush` that determines the color and texture of the drawn text. |
| x | float | The x-coordinate of the upper-left corner of the drawn text. |
| y | float | The y-coordinate of the upper-left corner of the drawn text. |

### drawString(String s, Font font, Brush brush, PointF point) {#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-com.aspose.imaging.PointF-}
```
public void drawString(String s, Font font, Brush brush, PointF point)
```


Draws the specified text string at the specified location with the specified `com.aspose.imaging.Brush` and `com.aspose.imaging.Font` objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | java.lang.String | String to draw. |
| font | [Font](../../com.aspose.imaging/font) | `com.aspose.imaging.Font` that defines the text format of the string. |
| brush | [Brush](../../com.aspose.imaging/brush) | `com.aspose.imaging.Brush` that determines the color and texture of the drawn text. |
| point | [PointF](../../com.aspose.imaging/pointf) | `com.aspose.imaging.PointF` structure that specifies the upper-left corner of the drawn text. |


**Example: This example demonstrates the use of Font and SolidBrush class to draw strings on Image surface.**
This example demonstrates the use of Font and SolidBrush class to draw strings on Image surface. The example creates a new Image and draw shapes using Figures and GraphicsPath
``` java
//Creates an instance of BmpOptions and set its various properties
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//Create an instance of FileCreateSource and assign it as Source for the instance of BmpOptions
//Second Boolean parameter determines if the file to be created IsTemporal or not
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

//Creates an instance of Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Creates and initialize an instance of Graphics class
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Clears Graphics surface
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Creates an instance of Font
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Times New Roman", 16);

    //Create an instance of SolidBrush having Red Color
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    //Draw a String
    graphics.drawString("Created by Aspose.Imaging for Java", font, brush, new com.aspose.imaging.PointF(100, 100));

    // save all changes
    image.save();
} finally {
    image.dispose();
}
```

### drawString(String s, Font font, Brush brush, float x, float y, StringFormat format) {#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-com.aspose.imaging.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)
```


Draws the specified text string at the specified location with the specified `com.aspose.imaging.Brush` and `com.aspose.imaging.Font` objects using the formatting attributes of the specified `com.aspose.imaging.stringFormat`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | java.lang.String | String to draw. |
| font | [Font](../../com.aspose.imaging/font) | `com.aspose.imaging.Font` that defines the text format of the string. |
| brush | [Brush](../../com.aspose.imaging/brush) | `com.aspose.imaging.Brush` that determines the color and texture of the drawn text. |
| x | float | The x-coordinate of the upper-left corner of the drawn text. |
| y | float | The y-coordinate of the upper-left corner of the drawn text. |
| format | [StringFormat](../../com.aspose.imaging/stringformat) | `com.aspose.imaging.StringFormat` that specifies formatting attributes, such as line spacing and alignment, that are applied to the drawn text. |

### drawString(String s, Font font, Brush brush, PointF point, StringFormat format) {#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-com.aspose.imaging.PointF-com.aspose.imaging.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, PointF point, StringFormat format)
```


Draws the specified text string at the specified location with the specified `com.aspose.imaging.Brush` and `com.aspose.imaging.Font` objects using the formatting attributes of the specified `com.aspose.imaging.stringFormat`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | java.lang.String | String to draw. |
| font | [Font](../../com.aspose.imaging/font) | `com.aspose.imaging.Font` that defines the text format of the string. |
| brush | [Brush](../../com.aspose.imaging/brush) | `com.aspose.imaging.Brush` that determines the color and texture of the drawn text. |
| point | [PointF](../../com.aspose.imaging/pointf) | `com.aspose.imaging.PointF` structure that specifies the upper-left corner of the drawn text. |
| format | [StringFormat](../../com.aspose.imaging/stringformat) | `com.aspose.imaging.StringFormat` that specifies formatting attributes, such as line spacing and alignment, that are applied to the drawn text. |


**Example: Support of PixelPerfect text alignment**

``` java
String outputFileName = "TestExactAlignment.png";
try (com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions())
{
    pngOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(outputFileName));
    try (com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 100))
    {
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
        graphics.clear(com.aspose.imaging.Color.getWhite());
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getBlack());
        com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 24);
        graphics.drawString("DrawString with ExactAlignment",
                font,
                brush,
                new com.aspose.imaging.PointF(0, 0),
                new com.aspose.imaging.StringFormat(com.aspose.imaging.StringFormatFlags.ExactAlignment));

        graphics.drawString("DrawString without ExactAlignment",
                font,
                brush,
                new com.aspose.imaging.PointF(0, 30),
                new com.aspose.imaging.StringFormat());

        graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed()),
                new com.aspose.imaging.Rectangle(0, 0, 499, 99));
        image.save();
    }
}
```

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle) {#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-com.aspose.imaging.RectangleF-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)
```


Draws the specified text string in the specified rectangle with the specified `com.aspose.imaging.Brush` and `com.aspose.imaging.Font` objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | java.lang.String | String to draw. |
| font | [Font](../../com.aspose.imaging/font) | `com.aspose.imaging.Font` that defines the text format of the string. |
| brush | [Brush](../../com.aspose.imaging/brush) | `com.aspose.imaging.Brush` that determines the color and texture of the drawn text. |
| layoutRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF` structure that specifies the location of the drawn text. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-com.aspose.imaging.RectangleF-com.aspose.imaging.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


Draws the specified text string in the specified rectangle with the specified `com.aspose.imaging.Brush` and `com.aspose.imaging.Font` objects using the formatting attributes of the specified `com.aspose.imaging.stringFormat`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | java.lang.String | String to draw. |
| font | [Font](../../com.aspose.imaging/font) | `com.aspose.imaging.Font` that defines the text format of the string. |
| brush | [Brush](../../com.aspose.imaging/brush) | `com.aspose.imaging.Brush` that determines the color and texture of the drawn text. |
| layoutRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF` structure that specifies the location of the drawn text. |
| format | [StringFormat](../../com.aspose.imaging/stringformat) | `com.aspose.imaging.StringFormat` that specifies formatting attributes, such as line spacing and alignment, that are applied to the drawn text. |

### fillEllipse(Brush brush, RectangleF rect) {#fillEllipse-com.aspose.imaging.Brush-com.aspose.imaging.RectangleF-}
```
public void fillEllipse(Brush brush, RectangleF rect)
```


Fills the interior of an ellipse defined by a bounding rectangle specified by a `com.aspose.imaging.RectangleF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `com.aspose.imaging.Brush` that determines the characteristics of the fill. |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF` structure that represents the bounding rectangle that defines the ellipse. |

### fillEllipse(Brush brush, float x, float y, float width, float height) {#fillEllipse-com.aspose.imaging.Brush-float-float-float-float-}
```
public void fillEllipse(Brush brush, float x, float y, float width, float height)
```


Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `com.aspose.imaging.Brush` that determines the characteristics of the fill. |
| x | float | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| y | float | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| width | float | Width of the bounding rectangle that defines the ellipse. |
| height | float | Height of the bounding rectangle that defines the ellipse. |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


Fills the interior of an ellipse defined by a bounding rectangle specified by a `com.aspose.imaging.Rectangle` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `com.aspose.imaging.Brush` that determines the characteristics of the fill. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | `com.aspose.imaging.Rectangle` structure that represents the bounding rectangle that defines the ellipse. |

### fillEllipse(Brush brush, int x, int y, int width, int height) {#fillEllipse-com.aspose.imaging.Brush-int-int-int-int-}
```
public void fillEllipse(Brush brush, int x, int y, int width, int height)
```


Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `com.aspose.imaging.Brush` that determines the characteristics of the fill. |
| x | int | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| y | int | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| width | int | Width of the bounding rectangle that defines the ellipse. |
| height | int | Height of the bounding rectangle that defines the ellipse. |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


Fills the interior of a pie section defined by an ellipse specified by a `com.aspose.imaging.RectangleF` structure and two radial lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `com.aspose.imaging.Brush` that determines the characteristics of the fill. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | `com.aspose.imaging.Rectangle` structure that represents the bounding rectangle that defines the ellipse from which the pie section comes. |
| startAngle | float | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweepAngle | float | Angle in degrees measured clockwise from the `startAngle` parameter to the second side of the pie section. |


**Example: The following example shows how to compose an animated GIF image from individual GIF blocks.**

``` java
String dir = "c:\\temp\\";

// Create a GIF image 100 x 100 px.
// The first block is fully black by default.
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    // The first circle is red
    com.aspose.imaging.brushes.SolidBrush brush1 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    // The second circle is black
    com.aspose.imaging.brushes.SolidBrush brush2 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getBlack());

    // Gradually increase the angle of the red arc shape.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock block = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);

        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(block);
        gr.fillPie(brush1, block.getBounds(), 0, angle);

        gifImage.addBlock(block);
    }

    // Gradually increase the angle of the black arc and wipe out the red arc.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock block = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);

        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(block);
        gr.fillPie(brush2, block.getBounds(), 0, angle);
        gr.fillPie(brush1, block.getBounds(), angle, 360 - angle);

        gifImage.addBlock(block);
    }

    gifImage.save(dir + "animated_radar.gif");
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}
```

### fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.imaging.Brush-com.aspose.imaging.RectangleF-float-float-}
```
public void fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```


Fills the interior of a pie section defined by an ellipse specified by a `com.aspose.imaging.RectangleF` structure and two radial lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `com.aspose.imaging.Brush` that determines the characteristics of the fill. |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF` structure that represents the bounding rectangle that defines the ellipse from which the pie section comes. |
| startAngle | float | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweepAngle | float | Angle in degrees measured clockwise from the `startAngle` parameter to the second side of the pie section. |

### fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle) {#fillPie-com.aspose.imaging.Brush-float-float-float-float-float-float-}
```
public void fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `com.aspose.imaging.Brush` that determines the characteristics of the fill. |
| x | float | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| y | float | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| width | float | Width of the bounding rectangle that defines the ellipse from which the pie section comes. |
| height | float | Height of the bounding rectangle that defines the ellipse from which the pie section comes. |
| startAngle | float | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweepAngle | float | Angle in degrees measured clockwise from the `startAngle` parameter to the second side of the pie section. |

### fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle) {#fillPie-com.aspose.imaging.Brush-int-int-int-int-int-int-}
```
public void fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `com.aspose.imaging.Brush` that determines the characteristics of the fill. |
| x | int | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| y | int | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| width | int | Width of the bounding rectangle that defines the ellipse from which the pie section comes. |
| height | int | Height of the bounding rectangle that defines the ellipse from which the pie section comes. |
| startAngle | int | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweepAngle | int | Angle in degrees measured clockwise from the `startAngle` parameter to the second side of the pie section. |

### fillPolygon(Brush brush, PointF[] points) {#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.PointF---}
```
public void fillPolygon(Brush brush, PointF[] points)
```


Fills the interior of a polygon defined by an array of points specified by `com.aspose.imaging.PointF` structures and `FillMode.Alternate`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `com.aspose.imaging.Brush` that determines the characteristics of the fill. |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Array of `com.aspose.imaging.PointF` structures that represent the vertices of the polygon to fill. |

### fillPolygon(Brush brush, PointF[] points, int fillMode) {#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.PointF---int-}
```
public void fillPolygon(Brush brush, PointF[] points, int fillMode)
```


Fills the interior of a polygon defined by an array of points specified by `com.aspose.imaging.PointF` structures using the specified fill mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `com.aspose.imaging.Brush` that determines the characteristics of the fill. |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Array of `com.aspose.imaging.PointF` structures that represent the vertices of the polygon to fill. |
| fillMode | int | Member of the `com.aspose.imaging.FillMode` enumeration that determines the style of the fill. |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


Fills the interior of a polygon defined by an array of points specified by `com.aspose.imaging.Point` structures and `FillMode.Alternate`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `com.aspose.imaging.Brush` that determines the characteristics of the fill. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Array of `com.aspose.imaging.Point` structures that represent the vertices of the polygon to fill. |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


Fills the interior of a polygon defined by an array of points specified by `com.aspose.imaging.Point` structures using the specified fill mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `com.aspose.imaging.Brush` that determines the characteristics of the fill. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Array of `com.aspose.imaging.Point` structures that represent the vertices of the polygon to fill. |
| fillMode | int | Member of the `com.aspose.imaging.FillMode` enumeration that determines the style of the fill. |

### fillClosedCurve(Brush brush, PointF[] points) {#fillClosedCurve-com.aspose.imaging.Brush-com.aspose.imaging.PointF---}
```
public void fillClosedCurve(Brush brush, PointF[] points)
```


Fills the interior of a closed cardinal spline curve defined by an array of `com.aspose.imaging.PointF` structures. This method uses a default tension of 0.5 and `FillMode.Alternate` fill mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `com.aspose.imaging.Brush` that determines the characteristics of the fill. |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Array of `com.aspose.imaging.PointF` structures that define the spline. |

### fillClosedCurve(Brush brush, PointF[] points, int fillMode) {#fillClosedCurve-com.aspose.imaging.Brush-com.aspose.imaging.PointF---int-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillMode)
```


Fills the interior of a closed cardinal spline curve defined by an array of `com.aspose.imaging.PointF` structures using the specified fill mode. This method uses a default tension of 0.5.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `com.aspose.imaging.Brush` that determines the characteristics of the fill. |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Array of `com.aspose.imaging.PointF` structures that define the spline. |
| fillMode | int | Member of the `com.aspose.imaging.FillMode` enumeration that determines how the curve is filled. |

### fillClosedCurve(Brush brush, PointF[] points, int fillMode, float tension) {#fillClosedCurve-com.aspose.imaging.Brush-com.aspose.imaging.PointF---int-float-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillMode, float tension)
```


Fills the interior of a closed cardinal spline curve defined by an array of `com.aspose.imaging.PointF` structures using the specified fill mode and tension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | A `com.aspose.imaging.Brush` that determines the characteristics of the fill. |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Array of `com.aspose.imaging.PointF` structures that define the spline. |
| fillMode | int | Member of the `com.aspose.imaging.FillMode` enumeration that determines how the curve is filled. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### fillClosedCurve(Brush brush, Point[] points) {#fillClosedCurve-com.aspose.imaging.Brush-com.aspose.imaging.Point---}
```
public void fillClosedCurve(Brush brush, Point[] points)
```


Fills the interior of a closed cardinal spline curve defined by an array of `com.aspose.imaging.Point` structures. This method uses a default tension of 0.5 and `FillMode.Alternate` fill mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `com.aspose.imaging.Brush` that determines the characteristics of the fill. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Array of `com.aspose.imaging.Point` structures that define the spline. |

### fillClosedCurve(Brush brush, Point[] points, int fillMode) {#fillClosedCurve-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillMode)
```


Fills the interior of a closed cardinal spline curve defined by an array of `com.aspose.imaging.Point` structures using the specified fill mode. This method uses a default tension of 0.5.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `com.aspose.imaging.Brush` that determines the characteristics of the fill. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Array of `com.aspose.imaging.Point` structures that define the spline. |
| fillMode | int | Member of the `com.aspose.imaging.FillMode` enumeration that determines how the curve is filled. |

### fillClosedCurve(Brush brush, Point[] points, int fillMode, float tension) {#fillClosedCurve-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-float-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillMode, float tension)
```


Fills the interior of a closed cardinal spline curve defined by an array of `com.aspose.imaging.Point` structures using the specified fill mode and tension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `com.aspose.imaging.Brush` that determines the characteristics of the fill. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Array of `com.aspose.imaging.Point` structures that define the spline. |
| fillMode | int | Member of the `com.aspose.imaging.FillMode` enumeration that determines how the curve is filled. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


Draws a `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `com.aspose.imaging.Pen` that determines the color, width, and style of the path. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `com.aspose.imaging.GraphicsPath` to draw. |


**Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.**
This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface. Example creates a new Image (of type Tiff) and draw paths with the help of GraphicsPath class. At the end DrawPath method exposed by Graphics class is called to render the paths on surface.
``` java
// Create an instance of FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.tif", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Create an instance of TiffOptions and set its various properties
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

    // Set the source for the instance of ImageOptions
    tiffOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Create an instance of Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(tiffOptions, 500, 500);
    try {
        // Create and initialize an instance of Graphics class
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Clear Graphics surface
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Create an instance of GraphicsPath class
        com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

        // Create an instance of Figure class
        com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();

        // Add Shapes to Figure object
        figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300)));
        figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
        figure.addShape(
                new com.aspose.imaging.shapes.PieShape(new com.aspose.imaging.RectangleF(
                        new com.aspose.imaging.PointF(250, 250),
                        new com.aspose.imaging.SizeF(200, 200)),
                        0, 45));

        // Add Figure object to GraphicsPath
        graphicspath.addFigure(figure);

        // Draw path with Pen object of color Black
        graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

        // Save all changes.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### fillPath(Brush brush, GraphicsPath path) {#fillPath-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-}
```
public void fillPath(Brush brush, GraphicsPath path)
```


Fills the interior of a `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `com.aspose.imaging.Brush` that determines the characteristics of the fill. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `com.aspose.imaging.GraphicsPath` that represents the path to fill. |

### fillRegion(Brush brush, Region region) {#fillRegion-com.aspose.imaging.Brush-com.aspose.imaging.Region-}
```
public void fillRegion(Brush brush, Region region)
```


Fills the interior of a [Region](../../com.aspose.imaging/region).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | [Brush](../../com.aspose.imaging/brush) that determines the characteristics of the fill. |
| region | [Region](../../com.aspose.imaging/region) | [Region](../../com.aspose.imaging/region) that represents the area to fill. |

### measureString(String text, Font font, SizeF layoutArea, StringFormat stringFormat) {#measureString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.SizeF-com.aspose.imaging.StringFormat-}
```
public SizeF measureString(String text, Font font, SizeF layoutArea, StringFormat stringFormat)
```


Measures the specified text string with specified parameters

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The text to measure. |
| font | [Font](../../com.aspose.imaging/font) | The font to measure. |
| layoutArea | [SizeF](../../com.aspose.imaging/sizef) | The layout area. |
| stringFormat | [StringFormat](../../com.aspose.imaging/stringformat) | The string format. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - Size in pixels of measured text string
