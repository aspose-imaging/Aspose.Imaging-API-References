---
title: LinearGradientBrush.LinearGradientBrush
second_title: Aspose.Imaging for .NET API Reference
description: LinearGradientBrush constructor. Initializes a new instance of the LinearGradientBrush class
type: docs
weight: 10
url: /net/aspose.imaging.brushes/lineargradientbrush/lineargradientbrush/
---
## LinearGradientBrush(RectangleF, Color, Color, float, bool) {#constructor_6}

Initializes a new instance of the [`LinearGradientBrush`](../) class.

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | RectangleF | The rectangle. |
| color1 | Color | The color1. |
| color2 | Color | The color2. |
| angle | Single | The angle. |
| isAngleScalable | Boolean | if set to `true` [is angle scalable]. |

### See Also

* struct [RectangleF](../../../aspose.imaging/rectanglef/)
* struct [Color](../../../aspose.imaging/color/)
* class [LinearGradientBrush](../)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush/)
* assembly [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Rectangle, Color, Color, float, bool) {#constructor_4}

Initializes a new instance of the [`LinearGradientBrush`](../) class.

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | The rectangle. |
| color1 | Color | The color1. |
| color2 | Color | The color2. |
| angle | Single | The angle. |
| isAngleScalable | Boolean | if set to `true` [is angle scalable]. |

### See Also

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* struct [Color](../../../aspose.imaging/color/)
* class [LinearGradientBrush](../)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush/)
* assembly [Aspose.Imaging](../../../)

---

## LinearGradientBrush(RectangleF, Color, Color, float) {#constructor_5}

Initializes a new instance of the [`LinearGradientBrush`](../) class.

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | RectangleF | The rectangle. |
| color1 | Color | The color1. |
| color2 | Color | The color2. |
| angle | Single | The angle. |

### See Also

* struct [RectangleF](../../../aspose.imaging/rectanglef/)
* struct [Color](../../../aspose.imaging/color/)
* class [LinearGradientBrush](../)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush/)
* assembly [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Rectangle, Color, Color, float) {#constructor_3}

Initializes a new instance of the [`LinearGradientBrush`](../) class.

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | The rectangle. |
| color1 | Color | The color1. |
| color2 | Color | The color2. |
| angle | Single | The angle. |

### See Also

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* struct [Color](../../../aspose.imaging/color/)
* class [LinearGradientBrush](../)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush/)
* assembly [Aspose.Imaging](../../../)

---

## LinearGradientBrush(PointF, PointF, Color, Color) {#constructor_2}

Initializes a new instance of the [`LinearGradientBrush`](../) class.

```csharp
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```

| Parameter | Type | Description |
| --- | --- | --- |
| point1 | PointF | The point1. |
| point2 | PointF | The point2. |
| color1 | Color | The color1. |
| color2 | Color | The color2. |

### See Also

* struct [PointF](../../../aspose.imaging/pointf/)
* struct [Color](../../../aspose.imaging/color/)
* class [LinearGradientBrush](../)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush/)
* assembly [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Point, Point, Color, Color) {#constructor_1}

Initializes a new instance of the [`LinearGradientBrush`](../) class.

```csharp
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```

| Parameter | Type | Description |
| --- | --- | --- |
| point1 | Point | The point1. |
| point2 | Point | The point2. |
| color1 | Color | The color1. |
| color2 | Color | The color2. |

## Examples

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

* struct [Point](../../../aspose.imaging/point/)
* struct [Color](../../../aspose.imaging/color/)
* class [LinearGradientBrush](../)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush/)
* assembly [Aspose.Imaging](../../../)

---

## LinearGradientBrush() {#constructor}

Initializes a new instance of the [`LinearGradientBrush`](../) class with default parameters. The starting color is black, the ending color is white, the angle is 45 degrees and the rectangle is located in (0,0) with size (1,1).

```csharp
public LinearGradientBrush()
```

### See Also

* class [LinearGradientBrush](../)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush/)
* assembly [Aspose.Imaging](../../../)


