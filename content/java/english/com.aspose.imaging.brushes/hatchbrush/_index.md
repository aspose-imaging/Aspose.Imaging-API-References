---
title: HatchBrush
second_title: Aspose.Imaging for Java API Reference
description: Defines a rectangular brush with a hatch style a foreground color and a background color.
type: docs
weight: 10
url: /com.aspose.imaging.brushes/hatchbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public final class HatchBrush extends Brush
```

Defines a rectangular brush with a hatch style, a foreground color, and a background color. This class cannot be inherited.
## Constructors

| Constructor | Description |
| --- | --- |
| [HatchBrush()](#HatchBrush--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getForegroundColor()](#getForegroundColor--) | Gets the color of hatch lines. |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.imaging.Color-) | Sets the color of hatch lines. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets the color of spaces between the hatch lines. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Sets the color of spaces between the hatch lines. |
| [getHatchStyle()](#getHatchStyle--) | Gets the hatch style of this brush. |
| [setHatchStyle(int value)](#setHatchStyle-int-) | Sets the hatch style of this brush. |

## Example: This example shows the creation and usage Pen objects.
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

### HatchBrush() {#HatchBrush--}
```
public HatchBrush()
```


### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Gets the color of hatch lines.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of hatch lines.
### setForegroundColor(Color value) {#setForegroundColor-com.aspose.imaging.Color-}
```
public void setForegroundColor(Color value)
```


Sets the color of hatch lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | The color of hatch lines. |


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

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gets the color of spaces between the hatch lines.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of spaces between the hatch lines.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Sets the color of spaces between the hatch lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | The color of spaces between the hatch lines. |


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

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Gets the hatch style of this brush.

**Returns:**
int
### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


Sets the hatch style of this brush.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

