---
title: GraphicsPath
second_title: Aspose.Imaging for Java API Reference
description: Represents a series of connected lines and curves.
type: docs
weight: 52
url: /java/com.aspose.imaging/graphicspath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

Represents a series of connected lines and curves. This class cannot be inherited.
## Constructors

| Constructor | Description |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | Initializes a new instance of the `GraphicsPath` class. |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.imaging.Figure---) | Initializes a new instance of the `GraphicsPath` class. |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.imaging.Figure---int-) | Initializes a new instance of the `GraphicsPath` class. |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | Initializes a new instance of the `GraphicsPath` class. |
## Methods

| Method | Description |
| --- | --- |
| [getFillMode()](#getFillMode--) | Gets a `com.aspose.imaging.FillMode` enumeration that determines how the interiors of shapes in this `com.aspose.imaging.GraphicsPath` are filled. |
| [setFillMode(int value)](#setFillMode-int-) | Sets a `com.aspose.imaging.FillMode` enumeration that determines how the interiors of shapes in this `com.aspose.imaging.GraphicsPath` are filled. |
| [getFigures()](#getFigures--) | Gets the path figures. |
| [getBounds()](#getBounds--) | Gets or sets the object's bounds. |
| [reset()](#reset--) | Empties the graphics path and sets the `com.aspose.imaging.FillMode` to `F:com.aspose.imaging.fillMode.alternate`. |
| [reverse()](#reverse--) | Reverses the order of figures, shapes, and points in each shape of this `com.aspose.imaging.graphicsPath`. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Indicates whether the specified point is contained within this `com.aspose.imaging.graphicsPath`. |
| [isVisible(PointF point)](#isVisible-com.aspose.imaging.PointF-) | Indicates whether the specified point is contained within this `com.aspose.imaging.graphicsPath`. |
| [isVisible(int x, int y)](#isVisible-int-int-) | Indicates whether the specified point is contained within this `com.aspose.imaging.graphicsPath`. |
| [isVisible(Point point)](#isVisible-com.aspose.imaging.Point-) | Indicates whether the specified point is contained within this `com.aspose.imaging.graphicsPath`. |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.imaging.Graphics-) | Indicates whether the specified point is contained within this `com.aspose.imaging.GraphicsPath` in the visible clip region of the specified `com.aspose.imaging.graphics`. |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-) | Indicates whether the specified point is contained within this `com.aspose.imaging.graphicsPath`. |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.imaging.Graphics-) | Indicates whether the specified point is contained within this `com.aspose.imaging.GraphicsPath`, using the specified `com.aspose.imaging.graphics`. |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-) | Indicates whether the specified point is contained within this `com.aspose.imaging.graphicsPath`. |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.imaging.Pen-) | Indicates whether the specified point is contained within (under) the outline of this `com.aspose.imaging.GraphicsPath` when drawn with the specified `com.aspose.imaging.pen`. |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-) | Indicates whether the specified point is contained within (under) the outline of this `com.aspose.imaging.GraphicsPath` when drawn with the specified `com.aspose.imaging.pen`. |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Indicates whether the specified point is contained within (under) the outline of this `com.aspose.imaging.GraphicsPath` when drawn with the specified `com.aspose.imaging.Pen` and using the specified `com.aspose.imaging.graphics`. |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Indicates whether the specified point is contained within (under) the outline of this `com.aspose.imaging.GraphicsPath` when drawn with the specified `com.aspose.imaging.Pen` and using the specified `com.aspose.imaging.graphics`. |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.imaging.Pen-) | Indicates whether the specified point is contained within (under) the outline of this `com.aspose.imaging.GraphicsPath` when drawn with the specified `com.aspose.imaging.pen`. |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-) | Indicates whether the specified point is contained within (under) the outline of this `com.aspose.imaging.GraphicsPath` when drawn with the specified `com.aspose.imaging.pen`. |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Indicates whether the specified point is contained within (under) the outline of this `com.aspose.imaging.GraphicsPath` when drawn with the specified `com.aspose.imaging.Pen` and using the specified `com.aspose.imaging.graphics`. |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Indicates whether the specified point is contained within (under) the outline of this `com.aspose.imaging.GraphicsPath` when drawn with the specified `com.aspose.imaging.Pen` and using the specified `com.aspose.imaging.graphics`. |
| [flatten()](#flatten--) | Converts each curve in this path into a sequence of connected line segments. |
| [flatten(Matrix matrix)](#flatten-com.aspose.imaging.Matrix-) | Applies the specified transform and then converts each curve in this `com.aspose.imaging.GraphicsPath` into a sequence of connected line segments. |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.imaging.Matrix-float-) | Converts each curve in this `com.aspose.imaging.GraphicsPath` into a sequence of connected line segments. |
| [widen(Pen pen)](#widen-com.aspose.imaging.Pen-) | Adds an additional outline to the path. |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-) | Adds an additional outline to the `com.aspose.imaging.graphicsPath`. |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-float-) | Replaces this `com.aspose.imaging.GraphicsPath` with curves that enclose the area that is filled when this path is drawn by the specified pen. |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-) | Applies a warp transform, defined by a rectangle and a parallelogram, to this `com.aspose.imaging.graphicsPath`. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-) | Applies a warp transform, defined by a rectangle and a parallelogram, to this `com.aspose.imaging.graphicsPath`. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-) | Applies a warp transform, defined by a rectangle and a parallelogram, to this `com.aspose.imaging.graphicsPath`. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-float-) | Applies a warp transform, defined by a rectangle and a parallelogram, to this `com.aspose.imaging.graphicsPath`. |
| [addFigure(Figure figure)](#addFigure-com.aspose.imaging.Figure-) | Adds a new figure. |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.imaging.Figure---) | Adds new figures. |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.imaging.Figure-) | Removes a figure. |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.imaging.Figure---) | Removes figures. |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.imaging.GraphicsPath-) | Appends the specified `com.aspose.imaging.GraphicsPath` to this path. |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.imaging.GraphicsPath-boolean-) | Appends the specified `com.aspose.imaging.GraphicsPath` to this path. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Gets the object's bounds. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Gets the object's bounds. |
| [deepClone()](#deepClone--) | Performs a deep clone of this graphics path. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Applies the specified transformation to the shape. |

## Example
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

### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


Initializes a new instance of the `GraphicsPath` class.

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.imaging.Figure---}
```
public GraphicsPath(Figure[] figures)
```


Initializes a new instance of the `GraphicsPath` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | The figures to initialize from. |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.imaging.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


Initializes a new instance of the `GraphicsPath` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | The figures to initialize from. |
| fillMode | int | The fill mode. |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


Initializes a new instance of the `GraphicsPath` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fillMode | int | The fill mode. |

### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


Gets a `com.aspose.imaging.FillMode` enumeration that determines how the interiors of shapes in this `com.aspose.imaging.GraphicsPath` are filled.

**Returns:**
int - The fill mode. A `com.aspose.imaging.FillMode` enumeration that specifies how the interiors of shapes in this `com.aspose.imaging.GraphicsPath` are filled.
### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


Sets a `com.aspose.imaging.FillMode` enumeration that determines how the interiors of shapes in this `com.aspose.imaging.GraphicsPath` are filled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The fill mode. |

### getFigures() {#getFigures--}
```
public Figure[] getFigures()
```


Gets the path figures.

**Returns:**
com.aspose.imaging.Figure[] - The path figures.
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Gets or sets the object's bounds.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### reset() {#reset--}
```
public void reset()
```


Empties the graphics path and sets the `com.aspose.imaging.FillMode` to `F:com.aspose.imaging.fillMode.alternate`.

### reverse() {#reverse--}
```
public void reverse()
```


Reverses the order of figures, shapes, and points in each shape of this `com.aspose.imaging.graphicsPath`.

### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Indicates whether the specified point is contained within this `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |

**Returns:**
boolean - This method returns true if the specified point is contained within this `com.aspose.imaging.GraphicsPath`; otherwise, false.
### isVisible(PointF point) {#isVisible-com.aspose.imaging.PointF-}
```
public boolean isVisible(PointF point)
```


Indicates whether the specified point is contained within this `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | A `com.aspose.imaging.PointF` that represents the point to test. |

**Returns:**
boolean - This method returns true if the specified point is contained within this `com.aspose.imaging.GraphicsPath`; otherwise, false.
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


Indicates whether the specified point is contained within this `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |

**Returns:**
boolean - This method returns true if the specified point is contained within this `com.aspose.imaging.GraphicsPath`; otherwise, false.
### isVisible(Point point) {#isVisible-com.aspose.imaging.Point-}
```
public boolean isVisible(Point point)
```


Indicates whether the specified point is contained within this `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | A `com.aspose.imaging.Point` that represents the point to test. |

**Returns:**
boolean - This method returns true if the specified point is contained within this `com.aspose.imaging.GraphicsPath`; otherwise, false.
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


Indicates whether the specified point is contained within this `com.aspose.imaging.GraphicsPath` in the visible clip region of the specified `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | The `com.aspose.imaging.Graphics` for which to test visibility. |

**Returns:**
boolean - This method returns true if the specified point is contained within this `com.aspose.imaging.GraphicsPath`; otherwise, false.
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


Indicates whether the specified point is contained within this `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.imaging/pointf) | A `com.aspose.imaging.PointF` that represents the point to test. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | The `com.aspose.imaging.Graphics` for which to test visibility. |

**Returns:**
boolean - This method returns true if the specified point is contained within this; otherwise, false.
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


Indicates whether the specified point is contained within this `com.aspose.imaging.GraphicsPath`, using the specified `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | The `com.aspose.imaging.Graphics` for which to test visibility. |

**Returns:**
boolean - This method returns true if the specified point is contained within this `com.aspose.imaging.GraphicsPath`; otherwise, false.
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


Indicates whether the specified point is contained within this `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pt | [Point](../../com.aspose.imaging/point) | A `com.aspose.imaging.Point` that represents the point to test. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | The `com.aspose.imaging.Graphics` for which to test visibility. |

**Returns:**
boolean - This method returns true if the specified point is contained within this `com.aspose.imaging.GraphicsPath`; otherwise, false.
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


Indicates whether the specified point is contained within (under) the outline of this `com.aspose.imaging.GraphicsPath` when drawn with the specified `com.aspose.imaging.pen`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |
| pen | [Pen](../../com.aspose.imaging/pen) | The `com.aspose.imaging.Pen` to test. |

**Returns:**
boolean - This method returns true if the specified point is contained within the outline of this `com.aspose.imaging.GraphicsPath` when drawn with the specified `com.aspose.imaging.Pen`; otherwise, false.
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


Indicates whether the specified point is contained within (under) the outline of this `com.aspose.imaging.GraphicsPath` when drawn with the specified `com.aspose.imaging.pen`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | A `com.aspose.imaging.PointF` that specifies the location to test. |
| pen | [Pen](../../com.aspose.imaging/pen) | The `com.aspose.imaging.Pen` to test. |

**Returns:**
boolean - This method returns true if the specified point is contained within the outline of this `com.aspose.imaging.GraphicsPath` when drawn with the specified `com.aspose.imaging.Pen`; otherwise, false.
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


Indicates whether the specified point is contained within (under) the outline of this `com.aspose.imaging.GraphicsPath` when drawn with the specified `com.aspose.imaging.Pen` and using the specified `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |
| pen | [Pen](../../com.aspose.imaging/pen) | The `com.aspose.imaging.Pen` to test. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | The `com.aspose.imaging.Graphics` for which to test visibility. |

**Returns:**
boolean - This method returns true if the specified point is contained within (under) the outline of this `com.aspose.imaging.GraphicsPath` as drawn with the specified `com.aspose.imaging.Pen`; otherwise, false.
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


Indicates whether the specified point is contained within (under) the outline of this `com.aspose.imaging.GraphicsPath` when drawn with the specified `com.aspose.imaging.Pen` and using the specified `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.imaging/pointf) | A `com.aspose.imaging.PointF` that specifies the location to test. |
| pen | [Pen](../../com.aspose.imaging/pen) | The `com.aspose.imaging.Pen` to test. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | The `com.aspose.imaging.Graphics` for which to test visibility. |

**Returns:**
boolean - This method returns true if the specified point is contained within (under) the outline of this `com.aspose.imaging.GraphicsPath` as drawn with the specified `com.aspose.imaging.Pen`; otherwise, false.
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


Indicates whether the specified point is contained within (under) the outline of this `com.aspose.imaging.GraphicsPath` when drawn with the specified `com.aspose.imaging.pen`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |
| pen | [Pen](../../com.aspose.imaging/pen) | The `com.aspose.imaging.Pen` to test. |

**Returns:**
boolean - This method returns true if the specified point is contained within the outline of this `com.aspose.imaging.GraphicsPath` when drawn with the specified `com.aspose.imaging.Pen`; otherwise, false.
### isOutlineVisible(Point point, Pen pen) {#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(Point point, Pen pen)
```


Indicates whether the specified point is contained within (under) the outline of this `com.aspose.imaging.GraphicsPath` when drawn with the specified `com.aspose.imaging.pen`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | A `com.aspose.imaging.Point` that specifies the location to test. |
| pen | [Pen](../../com.aspose.imaging/pen) | The `com.aspose.imaging.Pen` to test. |

**Returns:**
boolean - This method returns true if the specified point is contained within the outline of this `com.aspose.imaging.GraphicsPath` when drawn with the specified `com.aspose.imaging.Pen`; otherwise, false.
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


Indicates whether the specified point is contained within (under) the outline of this `com.aspose.imaging.GraphicsPath` when drawn with the specified `com.aspose.imaging.Pen` and using the specified `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |
| pen | [Pen](../../com.aspose.imaging/pen) | The `com.aspose.imaging.Pen` to test. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | The `com.aspose.imaging.Graphics` for which to test visibility. |

**Returns:**
boolean - This method returns true if the specified point is contained within the outline of this `com.aspose.imaging.GraphicsPath` as drawn with the specified `com.aspose.imaging.Pen`; otherwise, false.
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


Indicates whether the specified point is contained within (under) the outline of this `com.aspose.imaging.GraphicsPath` when drawn with the specified `com.aspose.imaging.Pen` and using the specified `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pt | [Point](../../com.aspose.imaging/point) | A `com.aspose.imaging.Point` that specifies the location to test. |
| pen | [Pen](../../com.aspose.imaging/pen) | The `com.aspose.imaging.Pen` to test. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | The `com.aspose.imaging.Graphics` for which to test visibility. |

**Returns:**
boolean - This method returns true if the specified point is contained within the outline of this `com.aspose.imaging.GraphicsPath` as drawn with the specified `com.aspose.imaging.Pen`; otherwise, false.
### flatten() {#flatten--}
```
public void flatten()
```


Converts each curve in this path into a sequence of connected line segments.

### flatten(Matrix matrix) {#flatten-com.aspose.imaging.Matrix-}
```
public void flatten(Matrix matrix)
```


Applies the specified transform and then converts each curve in this `com.aspose.imaging.GraphicsPath` into a sequence of connected line segments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | A `com.aspose.imaging.Matrix` by which to transform this `com.aspose.imaging.GraphicsPath` before flattening. |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.imaging.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


Converts each curve in this `com.aspose.imaging.GraphicsPath` into a sequence of connected line segments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | A `com.aspose.imaging.Matrix` by which to transform this `com.aspose.imaging.GraphicsPath` before flattening. |
| flatness | float | Specifies the maximum permitted error between the curve and its flattened approximation. A value of 0.25 is the default. Reducing the flatness value will increase the number of line segments in the approximation. |

### widen(Pen pen) {#widen-com.aspose.imaging.Pen-}
```
public void widen(Pen pen)
```


Adds an additional outline to the path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | A `com.aspose.imaging.Pen` that specifies the width between the original outline of the path and the new outline this method creates. |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


Adds an additional outline to the `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | A `com.aspose.imaging.Pen` that specifies the width between the original outline of the path and the new outline this method creates. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | A `com.aspose.imaging.Matrix` that specifies a transform to apply to the path before widening. |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


Replaces this `com.aspose.imaging.GraphicsPath` with curves that enclose the area that is filled when this path is drawn by the specified pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | A `com.aspose.imaging.Pen` that specifies the width between the original outline of the path and the new outline this method creates. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | A `com.aspose.imaging.Matrix` that specifies a transform to apply to the path before widening. |
| flatness | float | A value that specifies the flatness for curves. |

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


Applies a warp transform, defined by a rectangle and a parallelogram, to this `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | An array of `com.aspose.imaging.PointF` structures that define a parallelogram to which the rectangle defined by `srcRect` is transformed. The array can contain either three or four elements. If the array contains three elements, the lower-right corner of the parallelogram is implied by the first three points. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | A `com.aspose.imaging.RectangleF` that represents the rectangle that is transformed to the parallelogram defined by `destPoints`. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


Applies a warp transform, defined by a rectangle and a parallelogram, to this `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | An array of `com.aspose.imaging.PointF` structures that define a parallelogram to which the rectangle defined by `srcRect` is transformed. The array can contain either three or four elements. If the array contains three elements, the lower-right corner of the parallelogram is implied by the first three points. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | A `com.aspose.imaging.RectangleF` that represents the rectangle that is transformed to the parallelogram defined by `destPoints`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | A `com.aspose.imaging.Matrix` that specifies a geometric transform to apply to the path. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


Applies a warp transform, defined by a rectangle and a parallelogram, to this `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | An array of `com.aspose.imaging.PointF` structures that defines a parallelogram to which the rectangle defined by `srcRect` is transformed. The array can contain either three or four elements. If the array contains three elements, the lower-right corner of the parallelogram is implied by the first three points. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | A `com.aspose.imaging.RectangleF` that represents the rectangle that is transformed to the parallelogram defined by `destPoints`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | A `com.aspose.imaging.Matrix` that specifies a geometric transform to apply to the path. |
| warpMode | int | A `com.aspose.imaging.WarpMode` enumeration that specifies whether this warp operation uses perspective or bilinear mode. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


Applies a warp transform, defined by a rectangle and a parallelogram, to this `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | An array of `com.aspose.imaging.PointF` structures that define a parallelogram to which the rectangle defined by `srcRect` is transformed. The array can contain either three or four elements. If the array contains three elements, the lower-right corner of the parallelogram is implied by the first three points. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | A `com.aspose.imaging.RectangleF` that represents the rectangle that is transformed to the parallelogram defined by `destPoints`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | A `com.aspose.imaging.Matrix` that specifies a geometric transform to apply to the path. |
| warpMode | int | A `com.aspose.imaging.WarpMode` enumeration that specifies whether this warp operation uses perspective or bilinear mode. |
| flatness | float | A value from 0 through 1 that specifies how flat the resulting path is. For more information, see the `com.aspose.imaging.GraphicsPath.flatten` methods. |

### addFigure(Figure figure) {#addFigure-com.aspose.imaging.Figure-}
```
public void addFigure(Figure figure)
```


Adds a new figure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.imaging/figure) | The figure to add. |


**Example:**
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

### addFigures(Figure[] figures) {#addFigures-com.aspose.imaging.Figure---}
```
public void addFigures(Figure[] figures)
```


Adds new figures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | The figures to add. |


**Example:**
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

### removeFigure(Figure figure) {#removeFigure-com.aspose.imaging.Figure-}
```
public void removeFigure(Figure figure)
```


Removes a figure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.imaging/figure) | The figure to remove. |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.imaging.Figure---}
```
public void removeFigures(Figure[] figures)
```


Removes figures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | The figures to remove. |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.imaging.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


Appends the specified `com.aspose.imaging.GraphicsPath` to this path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | The `com.aspose.imaging.GraphicsPath` to add. |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.imaging.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


Appends the specified `com.aspose.imaging.GraphicsPath` to this path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | The `com.aspose.imaging.GraphicsPath` to add. |
| connect | boolean | A Boolean value that specifies whether the first figure in the added path is part of the last figure in this path. A value of true specifies that the first figure in the added path is part of the last figure in this path. A value of false specifies that the first figure in the added path is separate from the last figure in this path. |

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
### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


Performs a deep clone of this graphics path.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - A deep clone of the graphics path.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Applies the specified transformation to the shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | The transformation to apply. |

