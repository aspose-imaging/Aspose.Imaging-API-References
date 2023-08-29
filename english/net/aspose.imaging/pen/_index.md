---
title: Pen
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 10980
url: /net/aspose.imaging/pen/
---
## Pen class

Defines an object used to draw lines, curves and figures.

```csharp
public class Pen : TransparencySupporter
```

## Constructors

| Name | Description |
| --- | --- |
| [Pen](pen)(Brush) | Initializes a new instance of the [`Pen`](../pen) class with the specified [`Brush`](./brush). |
| [Pen](pen)(Color) | Initializes a new instance of the [`Pen`](../pen) class with the specified color. |
| [Pen](pen)(Brush, float) | Initializes a new instance of the [`Pen`](../pen) class with the specified [`Brush`](./brush) and [`Width`](./width). |
| [Pen](pen)(Color, float) | Initializes a new instance of the [`Pen`](../pen) class with the specified [`Color`](./color) and [`Width`](./width) properties. |

## Properties

| Name | Description |
| --- | --- |
| [Alignment](../../aspose.imaging/pen/alignment) { get; set; } | Gets or sets the alignment for this [`Pen`](../pen). |
| [Brush](../../aspose.imaging/pen/brush) { get; set; } | Gets or sets the [`Brush`](./brush) that determines attributes of this [`Pen`](../pen). |
| [Color](../../aspose.imaging/pen/color) { get; set; } | Gets or sets the color of this [`Pen`](../pen). |
| [CompoundArray](../../aspose.imaging/pen/compoundarray) { get; set; } | Gets or sets an array of values that specifies a compound pen. A compound pen draws a compound line made up of parallel lines and spaces. |
| [CustomEndCap](../../aspose.imaging/pen/customendcap) { get; set; } | Gets or sets a custom cap to use at the end of lines drawn with this [`Pen`](../pen). |
| [CustomStartCap](../../aspose.imaging/pen/customstartcap) { get; set; } | Gets or sets a custom cap to use at the beginning of lines drawn with this [`Pen`](../pen). |
| [DashCap](../../aspose.imaging/pen/dashcap) { get; set; } | Gets or sets the cap style used at the end of the dashes that make up dashed lines drawn with this [`Pen`](../pen). |
| [DashOffset](../../aspose.imaging/pen/dashoffset) { get; set; } | Gets or sets the distance from the start of a line to the beginning of a dash pattern. |
| [DashPattern](../../aspose.imaging/pen/dashpattern) { get; set; } | Gets or sets an array of custom dashes and spaces. |
| [DashStyle](../../aspose.imaging/pen/dashstyle) { get; set; } | Gets or sets the style used for dashed lines drawn with this [`Pen`](../pen). |
| [EndCap](../../aspose.imaging/pen/endcap) { get; set; } | Gets or sets the cap style used at the end of lines drawn with this [`Pen`](../pen). |
| [LineJoin](../../aspose.imaging/pen/linejoin) { get; set; } | Gets or sets the join style for the ends of two consecutive lines drawn with this [`Pen`](../pen). |
| [MiterLimit](../../aspose.imaging/pen/miterlimit) { get; set; } | Gets or sets the limit of the thickness of the join on a mitered corner. |
| [Opacity](../../aspose.imaging/transparencysupporter/opacity) { get; set; } | Gets or sets the object's opacity. The value should be between 0 and 1. Value of 0 means that object is fully visible, value of 1 means the object is fully opaque. |
| [PenType](../../aspose.imaging/pen/pentype) { get; } | Gets the style of lines drawn with this [`Pen`](../pen). |
| [StartCap](../../aspose.imaging/pen/startcap) { get; set; } | Gets or sets the cap style used at the beginning of lines drawn with this [`Pen`](../pen). |
| [Transform](../../aspose.imaging/pen/transform) { get; set; } | Gets or sets a copy of the geometric transformation for this [`Pen`](../pen). |
| [Width](../../aspose.imaging/pen/width) { get; set; } | Gets or sets the width of this [`Pen`](../pen), in units of the Graphics object used for drawing. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.imaging/pen/equals)(object) | Check if objects are equal. |
| override [GetHashCode](../../aspose.imaging/pen/gethashcode)() | Get hash code of the current object. |
| [MultiplyTransform](../../aspose.imaging/pen/multiplytransform)(Matrix) | Multiplies the transformation matrix for this [`Pen`](../pen) by the specified [`Matrix`](../matrix). |
| [MultiplyTransform](../../aspose.imaging/pen/multiplytransform)(Matrix, MatrixOrder) | Multiplies the transformation matrix for this [`Pen`](../pen) by the specified [`Matrix`](../matrix) in the specified order. |
| [ResetTransform](../../aspose.imaging/pen/resettransform)() | Resets the geometric transformation matrix for this [`Pen`](../pen) to identity. |
| [RotateTransform](../../aspose.imaging/pen/rotatetransform)(float) | Rotates the local geometric transformation by the specified angle. This method prepends the rotation to the transformation. |
| [RotateTransform](../../aspose.imaging/pen/rotatetransform)(float, MatrixOrder) | Rotates the local geometric transformation by the specified angle in the specified order. |
| [ScaleTransform](../../aspose.imaging/pen/scaletransform)(float, float) | Scales the local geometric transformation by the specified factors. This method prepends the scaling matrix to the transformation. |
| [ScaleTransform](../../aspose.imaging/pen/scaletransform)(float, float, MatrixOrder) | Scales the local geometric transformation by the specified factors in the specified order. |
| [SetLineCap](../../aspose.imaging/pen/setlinecap)(LineCap, LineCap, DashCap) | Sets the values that determine the style of cap used to end lines drawn by this [`Pen`](../pen). |
| [TranslateTransform](../../aspose.imaging/pen/translatetransform)(float, float) | Translates the local geometric transformation by the specified dimensions. This method prepends the translation to the transformation. |
| [TranslateTransform](../../aspose.imaging/pen/translatetransform)(float, float, MatrixOrder) | Translates the local geometric transformation by the specified dimensions in the specified order. |

### Examples

This example shows the creation and usage Pen objects. The example creates a new Image and draw Rectangles on Image surface.

```csharp
[C#]

//Create an instance of BmpOptions and set its various properties
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Create an instance of FileCreateSource and assign it as Source for the instance of BmpOptions
//Second Boolean parameter determines if the file to be created IsTemporal or not
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\sample.bmp", false);

//Create an instance of Image at specified Path
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //Create an instance of Graphics and initialize it with Image object
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //Clear the Graphics sutface with White Color
    graphics.Clear(Aspose.Imaging.Color.White);

    //Create an instance of Pen with color Red and width 5
    Aspose.Imaging.Pen pen = new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 5f);

    //Create an instance of HatchBrush and set its properties
    Aspose.Imaging.Brushes.HatchBrush brush = new Aspose.Imaging.Brushes.HatchBrush();
    brush.BackgroundColor = Aspose.Imaging.Color.Wheat;
    brush.ForegroundColor = Aspose.Imaging.Color.Red;

    //Create an instance of Pen
    //initialize it with HatchBrush object and width
    Aspose.Imaging.Pen brusedpen = new Pen(brush, 5);

    //Draw Rectangles by specifying Pen object
    graphics.DrawRectangles(pen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(210, 210), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 310), new Aspose.Imaging.Size(100, 100))
    });

    //Draw Rectangles by specifying Pen object
    graphics.DrawRectangles(brusedpen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 310), new Aspose.Imaging.Size(100, 100))
    });

    // save all changes.
    image.Save();
}
```

### See Also

* class [TransparencySupporter](../transparencysupporter)
* namespace [Aspose.Imaging](../../aspose.imaging)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
