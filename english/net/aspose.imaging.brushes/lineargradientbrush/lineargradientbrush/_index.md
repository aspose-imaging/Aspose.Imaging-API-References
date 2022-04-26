---
title: LinearGradientBrush
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 10
url: /net/aspose.imaging.brushes/lineargradientbrush/lineargradientbrush/
---
## LinearGradientBrush constructor (1 of 7)

Initializes a new instance of the [`LinearGradientBrush`](../../lineargradientbrush) class with default parameters. The starting color is black, the ending color is white, the angle is 45 degrees and the rectangle is located in (0,0) with size (1,1).

```csharp
public LinearGradientBrush()
```

### See Also

* class [LinearGradientBrush](../../lineargradientbrush)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush)
* assembly [Aspose.Imaging](../../../)

---

## LinearGradientBrush constructor (2 of 7)

Initializes a new instance of the [`LinearGradientBrush`](../../lineargradientbrush) class with the specified points and colors.

```csharp
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```

| Parameter | Type | Description |
| --- | --- | --- |
| point1 | Point | A [`Point`](../../../aspose.imaging/point) structure that represents the starting point of the linear gradient. |
| point2 | Point | A [`Point`](../../../aspose.imaging/point) structure that represents the endpoint of the linear gradient. |
| color1 | Color | A [`Color`](../../../aspose.imaging/color) structure that represents the starting color of the linear gradient. |
| color2 | Color | A [`Color`](../../../aspose.imaging/color) structure that represents the ending color of the linear gradient. |

### Examples

The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Create a permanent, not temporary file source.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // The linear gradient from the left-top to the right-bottom corner of the image.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Fill the active frame with a linear gradient brush.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage.ActiveFrame);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // Grayscale options
    Aspose.Imaging.ImageOptions.TiffOptions createTiffFrameOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());
    createTiffFrameOptions.Photometric = Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
    createTiffFrameOptions.BitsPerSample = new ushort[] { 8 };

    // Create a grayscale copy of the active frame.
    // The pixel data is preserved but converted to the desired format.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame grayscaleFrame = Aspose.Imaging.FileFormats.Tiff.TiffFrame.CreateFrameFrom(tiffImage.ActiveFrame, createTiffFrameOptions);

    // Add the newly created frame to the TIFF image.
    tiffImage.AddFrame(grayscaleFrame);

    tiffImage.Save();
}
```

### See Also

* struct [Point](../../../aspose.imaging/point)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush)
* assembly [Aspose.Imaging](../../../)

---

## LinearGradientBrush constructor (3 of 7)

Initializes a new instance of the [`LinearGradientBrush`](../../lineargradientbrush) class with the specified points and colors.

```csharp
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```

| Parameter | Type | Description |
| --- | --- | --- |
| point1 | PointF | A [`PointF`](../../../aspose.imaging/pointf) structure that represents the starting point of the linear gradient. |
| point2 | PointF | A [`PointF`](../../../aspose.imaging/pointf) structure that represents the endpoint of the linear gradient. |
| color1 | Color | A [`Color`](../../../aspose.imaging/color) structure that represents the starting color of the linear gradient. |
| color2 | Color | A [`Color`](../../../aspose.imaging/color) structure that represents the ending color of the linear gradient. |

### See Also

* struct [PointF](../../../aspose.imaging/pointf)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush)
* assembly [Aspose.Imaging](../../../)

---

## LinearGradientBrush constructor (4 of 7)

Initializes a new instance of the [`LinearGradientBrush`](../../lineargradientbrush) class based on a rectangle, starting and ending colors, and an orientation angle.

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | A [`RectangleF`](../../../aspose.imaging/rectanglef) structure that specifies the bounds of the linear gradient. |
| color1 | Color | A [`Color`](../../../aspose.imaging/color) structure that represents the starting color for the gradient. |
| color2 | Color | A [`Color`](../../../aspose.imaging/color) structure that represents the ending color for the gradient. |
| angle | Single | The angle, measured in degrees clockwise from the x-axis, of the gradient's orientation line. |

### See Also

* struct [Rectangle](../../../aspose.imaging/rectangle)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush)
* assembly [Aspose.Imaging](../../../)

---

## LinearGradientBrush constructor (5 of 7)

Initializes a new instance of the [`LinearGradientBrush`](../../lineargradientbrush) class based on a rectangle, starting and ending colors, and an orientation angle.

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | RectangleF | A [`RectangleF`](../../../aspose.imaging/rectanglef) structure that specifies the bounds of the linear gradient. |
| color1 | Color | A [`Color`](../../../aspose.imaging/color) structure that represents the starting color for the gradient. |
| color2 | Color | A [`Color`](../../../aspose.imaging/color) structure that represents the ending color for the gradient. |
| angle | Single | The angle, measured in degrees clockwise from the x-axis, of the gradient's orientation line. |

### See Also

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush)
* assembly [Aspose.Imaging](../../../)

---

## LinearGradientBrush constructor (6 of 7)

Initializes a new instance of the [`LinearGradientBrush`](../../lineargradientbrush) class based on a rectangle, starting and ending colors, and an orientation angle.

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | A [`RectangleF`](../../../aspose.imaging/rectanglef) structure that specifies the bounds of the linear gradient. |
| color1 | Color | A [`Color`](../../../aspose.imaging/color) structure that represents the starting color for the gradient. |
| color2 | Color | A [`Color`](../../../aspose.imaging/color) structure that represents the ending color for the gradient. |
| angle | Single | The angle, measured in degrees clockwise from the x-axis, of the gradient's orientation line. |
| isAngleScalable | Boolean | if set to `true` the angle is changed during transformations with this [`LinearGradientBrush`](../../lineargradientbrush). |

### See Also

* struct [Rectangle](../../../aspose.imaging/rectangle)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush)
* assembly [Aspose.Imaging](../../../)

---

## LinearGradientBrush constructor (7 of 7)

Initializes a new instance of the [`LinearGradientBrush`](../../lineargradientbrush) class based on a rectangle, starting and ending colors, and an orientation angle.

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | RectangleF | A [`RectangleF`](../../../aspose.imaging/rectanglef) structure that specifies the bounds of the linear gradient. |
| color1 | Color | A [`Color`](../../../aspose.imaging/color) structure that represents the starting color for the gradient. |
| color2 | Color | A [`Color`](../../../aspose.imaging/color) structure that represents the ending color for the gradient. |
| angle | Single | The angle, measured in degrees clockwise from the x-axis, of the gradient's orientation line. |
| isAngleScalable | Boolean | if set to `true` the angle is changed during transformations with this [`LinearGradientBrush`](../../lineargradientbrush). |

### See Also

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
