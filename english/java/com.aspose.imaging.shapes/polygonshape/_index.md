---
title: PolygonShape
second_title: Aspose.Imaging for Java API Reference
description: Represents a polygon shape.
type: docs
weight: 15
url: /java/com.aspose.imaging.shapes/polygonshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape)

**All Implemented Interfaces:**
[com.aspose.imaging.IOrderedShape](../../com.aspose.imaging/iorderedshape)
```
public class PolygonShape extends Shape implements IOrderedShape
```

Represents a polygon shape.
## Constructors

| Constructor | Description |
| --- | --- |
| [PolygonShape()](#PolygonShape--) | Initializes a new instance of the `PolygonShape` class. |
| [PolygonShape(PointF[] points)](#PolygonShape-com.aspose.imaging.PointF---) | Initializes a new instance of the `PolygonShape` class. |
| [PolygonShape(PointF[] points, boolean isClosed)](#PolygonShape-com.aspose.imaging.PointF---boolean-) | Initializes a new instance of the `PolygonShape` class. |
## Methods

| Method | Description |
| --- | --- |
| [getPoints()](#getPoints--) | Gets or sets the curve points. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.imaging.PointF---) | Gets or sets the curve points. |
| [isClosed()](#isClosed--) | Gets or sets a value indicating whether shape is closed. |
| [setClosed(boolean value)](#setClosed-boolean-) | Gets or sets a value indicating whether shape is closed. |
| [getBounds()](#getBounds--) | Gets the object's bounds. |
| [getCenter()](#getCenter--) | Gets the shape's center. |
| [getSegments()](#getSegments--) | Gets the shape segments. |
| [hasSegments()](#hasSegments--) | Gets a value indicating whether shape has segments. |
| [getStartPoint()](#getStartPoint--) | Gets the starting shape point. |
| [getEndPoint()](#getEndPoint--) | Gets the ending shape point. |
| [reverse()](#reverse--) | Reverses the order of points for this shape. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Gets the object's bounds. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Gets the object's bounds. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Applies the specified transformation to the shape. |

## Example: This example creates a new Image and draws a variety of shapes using Figures and GraphicsPath o...
This example creates a new Image and draws a variety of shapes using Figures and GraphicsPath on the Image surface
``` java
//Creates an instance of BmpOptions and set its various properties
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//Create an instance of FileCreateSource and assign it as Source for the instance of BmpOptions
//Second Boolean parameter determines if the file to be created IsTemporal or not
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\output.bmp", false));

//Create an instance of Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Create and initialize an instance of Graphics class
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Clear Graphics surface
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Create an instance of GraphicsPath class
    com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

    //Create an instance of Figure class
    com.aspose.imaging.Figure figure1 = new com.aspose.imaging.Figure();

    //Add Shape to Figure object
    figure1.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
    figure1.addShape(new com.aspose.imaging.shapes.PieShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(110, 110),
                    new com.aspose.imaging.SizeF(200, 200)), 0, 90));

    //Create an instance of Figure class
    com.aspose.imaging.Figure figure2 = new com.aspose.imaging.Figure();

    //Add Shape to Figure object
    figure2.addShape(new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.addShape(new com.aspose.imaging.shapes.PolygonShape(
            new com.aspose.imaging.PointF[]
                    {
                            new com.aspose.imaging.PointF(150, 10),
                            new com.aspose.imaging.PointF(150, 200),
                            new com.aspose.imaging.PointF(250, 300),
                            new com.aspose.imaging.PointF(350, 400)}, true));
    figure2.addShape(new com.aspose.imaging.shapes.RectangleShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(250, 250),
                    new com.aspose.imaging.SizeF(200, 200))));

    //Add Figure object to GraphicsPath
    graphicspath.addFigures(new com.aspose.imaging.Figure[]{figure1, figure2});

    //Draw path with Pen object of color Black
    graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

    // save all changes.
    image.save();
} finally {
    image.dispose();
}
```

### PolygonShape() {#PolygonShape--}
```
public PolygonShape()
```


Initializes a new instance of the `PolygonShape` class.

### PolygonShape(PointF[] points) {#PolygonShape-com.aspose.imaging.PointF---}
```
public PolygonShape(PointF[] points)
```


Initializes a new instance of the `PolygonShape` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | The points array. |

### PolygonShape(PointF[] points, boolean isClosed) {#PolygonShape-com.aspose.imaging.PointF---boolean-}
```
public PolygonShape(PointF[] points, boolean isClosed)
```


Initializes a new instance of the `PolygonShape` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | The points array. |
| isClosed | boolean | If set to `true` the polygon is closed. |

### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


Gets or sets the curve points.

Value: The curve points.

**Returns:**
com.aspose.imaging.PointF[]
### setPoints(PointF[] value) {#setPoints-com.aspose.imaging.PointF---}
```
public void setPoints(PointF[] value)
```


Gets or sets the curve points.

Value: The curve points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Gets or sets a value indicating whether shape is closed.

Value: `true` if shape is closed; otherwise, `false`.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Gets or sets a value indicating whether shape is closed.

Value: `true` if shape is closed; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Gets the object's bounds.

Value: The object's bounds.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Gets the shape's center.

Value: The shape's center.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Gets the shape segments.

Value: The shape segments.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Gets a value indicating whether shape has segments.

Value: `True` if shape has segments; otherwise, `false`.

**Returns:**
boolean
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Gets the starting shape point.

Value: The starting shape point.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


Gets the ending shape point.

Value: The ending shape point.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### reverse() {#reverse--}
```
public void reverse()
```


Reverses the order of points for this shape.

### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Gets the object's bounds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | The matrix to apply before bounds will be calculated. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Gets the object's bounds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | The matrix to apply before bounds will be calculated. |
| pen | [Pen](../../com.aspose.imaging/pen) | The pen to use for object. This can influence the object's bounds size. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Applies the specified transformation to the shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | The transformation to apply. |

