---
title: Pen.Pen
second_title: Aspose.Imaging for .NET API Reference
description: Pen constructor. Initializes a new instance of the Pen class with the specified color
type: docs
weight: 10
url: /net/aspose.imaging/pen/pen/
---
## Pen(Color) {#constructor_2}

Initializes a new instance of the [`Pen`](../) class with the specified color.

```csharp
public Pen(Color color)
```

| Parameter | Type | Description |
| --- | --- | --- |
| color | Color | A [`Color`](../color/) structure that indicates the color of this [`Pen`](../). |

### See Also

* struct [Color](../../color/)
* class [Pen](../)
* namespace [Aspose.Imaging](../../pen/)
* assembly [Aspose.Imaging](../../../)

---

## Pen(Color, float) {#constructor_3}

Initializes a new instance of the [`Pen`](../) class with the specified [`Color`](../color/) and [`Width`](../width/) properties.

```csharp
public Pen(Color color, float width)
```

| Parameter | Type | Description |
| --- | --- | --- |
| color | Color | A [`Color`](../color/) structure that indicates the color of this [`Pen`](../). |
| width | Single | A value indicating the width of this [`Pen`](../). |

## Examples

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

* struct [Color](../../color/)
* class [Pen](../)
* namespace [Aspose.Imaging](../../pen/)
* assembly [Aspose.Imaging](../../../)

---

## Pen(Brush) {#constructor}

Initializes a new instance of the [`Pen`](../) class with the specified [`Brush`](../brush/).

```csharp
public Pen(Brush brush)
```

| Parameter | Type | Description |
| --- | --- | --- |
| brush | Brush | A [`Brush`](../brush/) that determines the fill properties of this [`Pen`](../). |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* is null. |

### See Also

* class [Brush](../../brush/)
* class [Pen](../)
* namespace [Aspose.Imaging](../../pen/)
* assembly [Aspose.Imaging](../../../)

---

## Pen(Brush, float) {#constructor_1}

Initializes a new instance of the [`Pen`](../) class with the specified [`Brush`](../brush/) and [`Width`](../width/).

```csharp
public Pen(Brush brush, float width)
```

| Parameter | Type | Description |
| --- | --- | --- |
| brush | Brush | A [`Brush`](../brush/) that determines the characteristics of this [`Pen`](../). |
| width | Single | The width of the new [`Pen`](../). |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* is null. |

### See Also

* class [Brush](../../brush/)
* class [Pen](../)
* namespace [Aspose.Imaging](../../pen/)
* assembly [Aspose.Imaging](../../../)


