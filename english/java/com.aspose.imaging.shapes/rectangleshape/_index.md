---
title: RectangleShape
second_title: Aspose.Imaging for Java API Reference
description: Represents a rectangular shape.
type: docs
weight: 17
url: /java/com.aspose.imaging.shapes/rectangleshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape)
```
public class RectangleShape extends RectangleProjectedShape
```

Represents a rectangular shape.
## Constructors

| Constructor | Description |
| --- | --- |
| [RectangleShape()](#RectangleShape--) | Initializes a new instance of the `RectangleShape` class. |
| [RectangleShape(RectangleF rectangle)](#RectangleShape-com.aspose.imaging.RectangleF-) | Initializes a new instance of the `RectangleShape` class. |
## Methods

| Method | Description |
| --- | --- |
| [getSegments()](#getSegments--) | Gets the shape segments. |

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

### RectangleShape() {#RectangleShape--}
```
public RectangleShape()
```


Initializes a new instance of the `RectangleShape` class.

### RectangleShape(RectangleF rectangle) {#RectangleShape-com.aspose.imaging.RectangleF-}
```
public RectangleShape(RectangleF rectangle)
```


Initializes a new instance of the `RectangleShape` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | The rectangle. |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Gets the shape segments.

Value: The shape segments.

**Returns:**
com.aspose.imaging.ShapeSegment[]
