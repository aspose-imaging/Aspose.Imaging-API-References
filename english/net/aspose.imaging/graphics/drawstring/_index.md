---
title: Graphics.DrawString
second_title: Aspose.Imaging for .NET API Reference
description: Graphics method. Draws the specified text string at the specified location with the specified Brush and Font objects
type: docs
weight: 330
url: /net/aspose.imaging/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

Draws the specified text string at the specified location with the specified [`Brush`](../../brush/) and [`Font`](../../font/) objects.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| s | String | String to draw. |
| font | Font | [`Font`](../../font/) that defines the text format of the string. |
| brush | Brush | [`Brush`](../../brush/) that determines the color and texture of the drawn text. |
| x | Single | The x-coordinate of the upper-left corner of the drawn text. |
| y | Single | The y-coordinate of the upper-left corner of the drawn text. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* is null. -or- *s* is null. |

### See Also

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

Draws the specified text string at the specified location with the specified [`Brush`](../../brush/) and [`Font`](../../font/) objects.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| Parameter | Type | Description |
| --- | --- | --- |
| s | String | String to draw. |
| font | Font | [`Font`](../../font/) that defines the text format of the string. |
| brush | Brush | [`Brush`](../../brush/) that determines the color and texture of the drawn text. |
| point | PointF | [`PointF`](../../pointf/) structure that specifies the upper-left corner of the drawn text. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* is null. -or- *s* is null. |

## Examples

This example uses Graphics class to create primitive shapes on the Image surface. To demonstrate the operation, the example creates a new Image in PNG format and draw primitive shapes on Image surface using Draw methods exposed by Graphics class

```csharp
[C#]

//Creates an instance of FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //Create an instance of PngOptions and set its various properties
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //Set the Source for PngOptions
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Create an instance of Image 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //Create and initialize an instance of Graphics class
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Clear Graphics surface
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        //Draw an Arc by specifying the Pen object having Black color, 
        //a Rectangle surrounding the Arc, Start Angle and Sweep Angle
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        //Draw a Bezier by specifying the Pen object having Blue color and co-ordinate Points.
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //Draw a Curve by specifying the Pen object having Green color and an array of Points
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //Draw an Ellipse using the Pen object and a surrounding Rectangle
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //Draw a Line 
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        //Draw a Pie segment
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        //Draw a Polygon by specifying the Pen object having Red color and an array of Points
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //Draw a Rectangle
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //Create a SolidBrush object and set its various properties
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //Draw a String using the SolidBrush object and Font, at specific Point
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // save all changes.
        image.Save();
    }
}
```

### See Also

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

Draws the specified text string at the specified location with the specified [`Brush`](../../brush/) and [`Font`](../../font/) objects using the formatting attributes of the specified [`StringFormat`](../../stringformat/).

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| s | String | String to draw. |
| font | Font | [`Font`](../../font/) that defines the text format of the string. |
| brush | Brush | [`Brush`](../../brush/) that determines the color and texture of the drawn text. |
| x | Single | The x-coordinate of the upper-left corner of the drawn text. |
| y | Single | The y-coordinate of the upper-left corner of the drawn text. |
| format | StringFormat | [`StringFormat`](../../stringformat/) that specifies formatting attributes, such as line spacing and alignment, that are applied to the drawn text. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* is null. -or- *s* is null. |

### See Also

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

Draws the specified text string at the specified location with the specified [`Brush`](../../brush/) and [`Font`](../../font/) objects using the formatting attributes of the specified [`StringFormat`](../../stringformat/).

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| s | String | String to draw. |
| font | Font | [`Font`](../../font/) that defines the text format of the string. |
| brush | Brush | [`Brush`](../../brush/) that determines the color and texture of the drawn text. |
| point | PointF | [`PointF`](../../pointf/) structure that specifies the upper-left corner of the drawn text. |
| format | StringFormat | [`StringFormat`](../../stringformat/) that specifies formatting attributes, such as line spacing and alignment, that are applied to the drawn text. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* is null. -or- *s* is null. |

### See Also

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

Draws the specified text string in the specified rectangle with the specified [`Brush`](../../brush/) and [`Font`](../../font/) objects.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| s | String | String to draw. |
| font | Font | [`Font`](../../font/) that defines the text format of the string. |
| brush | Brush | [`Brush`](../../brush/) that determines the color and texture of the drawn text. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) structure that specifies the location of the drawn text. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* is null. -or- *s* is null. |

### See Also

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

Draws the specified text string in the specified rectangle with the specified [`Brush`](../../brush/) and [`Font`](../../font/) objects using the formatting attributes of the specified [`StringFormat`](../../stringformat/).

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| s | String | String to draw. |
| font | Font | [`Font`](../../font/) that defines the text format of the string. |
| brush | Brush | [`Brush`](../../brush/) that determines the color and texture of the drawn text. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) structure that specifies the location of the drawn text. |
| format | StringFormat | [`StringFormat`](../../stringformat/) that specifies formatting attributes, such as line spacing and alignment, that are applied to the drawn text. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* is null. -or- *s* is null. -or- *brush* is null. |

### See Also

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)


