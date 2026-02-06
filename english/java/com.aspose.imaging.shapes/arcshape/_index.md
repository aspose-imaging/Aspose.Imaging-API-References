---
title: ArcShape
second_title: Aspose.Imaging for Java API Reference
description: Represents an arc shape.
type: docs
weight: 10
url: /java/com.aspose.imaging.shapes/arcshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape), [com.aspose.imaging.shapes.RectangleShape](../../com.aspose.imaging.shapes/rectangleshape), [com.aspose.imaging.shapes.EllipseShape](../../com.aspose.imaging.shapes/ellipseshape), [com.aspose.imaging.shapes.PieShape](../../com.aspose.imaging.shapes/pieshape)

**All Implemented Interfaces:**
[com.aspose.imaging.IOrderedShape](../../com.aspose.imaging/iorderedshape)
```
public final class ArcShape extends PieShape implements IOrderedShape
```

Represents an arc shape.
## Constructors

| Constructor | Description |
| --- | --- |
| [ArcShape()](#ArcShape--) | Initializes a new instance of the `ArcShape` class. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)](#ArcShape-com.aspose.imaging.RectangleF-float-float-) | Initializes a new instance of the `ArcShape` class. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)](#ArcShape-com.aspose.imaging.RectangleF-float-float-boolean-) | Initializes a new instance of the `ArcShape` class. |
## Methods

| Method | Description |
| --- | --- |
| [getSegments()](#getSegments--) | Gets the shape segments. |
| [getStartPoint()](#getStartPoint--) | Gets the starting shape point. |
| [getEndPoint()](#getEndPoint--) | Gets the ending shape point. |
| [isClosed()](#isClosed--) | Gets or sets a value indicating whether ordered shape is closed. |
| [setClosed(boolean value)](#setClosed-boolean-) | Gets or sets a value indicating whether ordered shape is closed. |
| [reverse()](#reverse--) | Reverses the order of points for this shape. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Gets the object's bounds. |
| [equals(Object obj)](#equals-java.lang.Object-) | Check if objects are equal. |
| [hashCode()](#hashCode--) | Get hash code of the current object. |

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

### ArcShape() {#ArcShape--}
```
public ArcShape()
```


Initializes a new instance of the `ArcShape` class.

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle) {#ArcShape-com.aspose.imaging.RectangleF-float-float-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)
```


Initializes a new instance of the `ArcShape` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | The rectangle. |
| startAngle | float | The start angle. |
| sweepAngle | float | The sweep angle. |

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed) {#ArcShape-com.aspose.imaging.RectangleF-float-float-boolean-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)
```


Initializes a new instance of the `ArcShape` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | The rectangle. |
| startAngle | float | The start angle. |
| sweepAngle | float | The sweep angle. |
| isClosed | boolean | If set to `true` the arc is closed. The closed arc is actually degenerates to an ellipse. |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Gets the shape segments.

Value: The shape segments.

**Returns:**
com.aspose.imaging.ShapeSegment[]
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
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Gets or sets a value indicating whether ordered shape is closed. When processing closed ordered shape the starting and ending points have no meaning.

Value: `True` if this ordered shape is closed; otherwise, `false`.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Gets or sets a value indicating whether ordered shape is closed. When processing closed ordered shape the starting and ending points have no meaning.

Value: `True` if this ordered shape is closed; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Check if objects are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The other object. |

**Returns:**
boolean - The equality comparison result.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Get hash code of the current object.

**Returns:**
int - The hash code.
