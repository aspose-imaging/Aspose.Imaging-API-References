---
title: Figure
second_title: Aspose.Imaging for Java API Reference
description: The figure.
type: docs
weight: 44
url: /java/com.aspose.imaging/figure/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

The figure. A container for shapes.
## Constructors

| Constructor | Description |
| --- | --- |
| [Figure()](#Figure--) | Initializes a new [Figure](../../com.aspose.imaging/figure) instance. |
## Methods

| Method | Description |
| --- | --- |
| [getShapes()](#getShapes--) | Gets the figure shapes. |
| [getBounds()](#getBounds--) | Gets or sets the object's bounds. |
| [isClosed()](#isClosed--) | Gets a value indicating whether this figure is closed. |
| [setClosed(boolean value)](#setClosed-boolean-) | Sets a value indicating whether this figure is closed. |
| [getSegments()](#getSegments--) | Gets the whole figure segments. |
| [addShape(Shape shape)](#addShape-com.aspose.imaging.Shape-) | Adds a shape to the figure. |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.imaging.Shape---) | Adds a range of shapes to the figure. |
| [removeShape(Shape shape)](#removeShape-com.aspose.imaging.Shape-) | Removes a shape from the figure. |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.imaging.Shape---) | Removes a range of shapes from the figure. |
| [reverse()](#reverse--) | Reverses this figure shapes order and shapes point order. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Gets the object's bounds. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Gets the object's bounds. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Applies the specified transformation to the shape. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified object is equal to the current object. |
| [hashCode()](#hashCode--) | Serves as the default hash function. |

## Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.
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

### Figure() {#Figure--}
```
public Figure()
```


Initializes a new [Figure](../../com.aspose.imaging/figure) instance. A constructor required for a JSON deserialization.

### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


Gets the figure shapes.

**Returns:**
com.aspose.imaging.Shape[] - The figure shapes.
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Gets or sets the object's bounds.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Gets a value indicating whether this figure is closed. A closed figure will make a difference only in case where the first and the last figure's shapes are continuous shapes. In such case the first point of the first shape will be connected by a straight line from the last point of the last shape.

**Returns:**
boolean - `True` if this figure is closed; otherwise, `false`.
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Sets a value indicating whether this figure is closed. A closed figure will make a difference only in case where the first and the last figure's shapes are continuous shapes. In such case the first point of the first shape will be connected by a straight line from the last point of the last shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | `True` if this figure is closed; otherwise, `false`. |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Gets the whole figure segments.

**Returns:**
com.aspose.imaging.ShapeSegment[] - The figure segments.
### addShape(Shape shape) {#addShape-com.aspose.imaging.Shape-}
```
public void addShape(Shape shape)
```


Adds a shape to the figure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.imaging/shape) | The shape to add. |


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

### addShapes(Shape[] shapes) {#addShapes-com.aspose.imaging.Shape---}
```
public void addShapes(Shape[] shapes)
```


Adds a range of shapes to the figure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.imaging/shape) | The shapes to add. |

### removeShape(Shape shape) {#removeShape-com.aspose.imaging.Shape-}
```
public void removeShape(Shape shape)
```


Removes a shape from the figure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.imaging/shape) | The shape to remove. |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.imaging.Shape---}
```
public void removeShapes(Shape[] shapes)
```


Removes a range of shapes from the figure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.imaging/shape) | The shapes range to remove. |

### reverse() {#reverse--}
```
public void reverse()
```


Reverses this figure shapes order and shapes point order.

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

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified object is equal to the current object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The compared object. |

**Returns:**
boolean - The result of equals
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as the default hash function.

**Returns:**
int - A hash code for the current object.
