---
title: SvgGraphics2D.DrawImage
second_title: Aspose.Imaging for .NET API Reference
description: SvgGraphics2D method. Draws the specified image at the specified location
type: docs
weight: 40
url: /net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/drawimage/
---
## DrawImage(RasterImage, Point) {#drawimage}

Draws the specified image at the specified location.

```csharp
public void DrawImage(RasterImage image, Point origin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | RasterImage | The drawn image. |
| origin | Point | The location of the drawn image. |

### See Also

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* struct [Point](../../../aspose.imaging/point/)
* class [SvgGraphics2D](../)
* namespace [Aspose.Imaging.FileFormats.Svg.Graphics](../../svggraphics2d/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(RasterImage, Point, Size) {#drawimage_1}

Draws the specified image of the specified size at the specified location.

```csharp
public void DrawImage(RasterImage image, Point origin, Size size)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | RasterImage | The drawn image. |
| origin | Point | The location of the drawn image. |
| size | Size | The desired size of the drawn image. |

## Examples

This example shows how to create an SVG image of the specified size and draw different shapes on it using SvgGraphics2D.

```csharp
[C#]

string dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;
int dpi = 96;

Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D graphics = new Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D(imageWidth, imageHeight, dpi);

// Draw a black rectangle along the image borders using a 1-pixel-wide black pen.
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, imageWidth, imageHeight);

// Fill a rectangle with the color of white-smoke.
graphics.FillRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.WhiteSmoke, 1), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), 10, 10, 580, 380);

// Draw two diagonal lines using a 1-pixel-wide darkgreen pen.
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, imageWidth, imageHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, imageHeight, imageWidth, 0);

// Draw an arc within the rectangle {0, 0, 200, 200} using a 2-pixel-wide blue pen.
graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Fill an arc
graphics.FillArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.LightCoral, 10), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.LightSkyBlue), new Aspose.Imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Draw a cubic bezier using a 2-pixel-wide red pen.
graphics.DrawCubicBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2),
    new Aspose.Imaging.PointF(0, 0),
    new Aspose.Imaging.PointF(200, 133),
    new Aspose.Imaging.PointF(400, 166),
    new Aspose.Imaging.PointF(600, 400));

// Draw a raster image of the specified size at the specified location.
// The image is scaled to fit the desired rectangle.
using (Aspose.Imaging.RasterImage imageToDraw = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    graphics.DrawImage(imageToDraw, new Aspose.Imaging.Point(400, 200), new Aspose.Imaging.Size(100, 50));
}

// Draw a text string
graphics.DrawString(new Aspose.Imaging.Font("Arial", 48, Aspose.Imaging.FontStyle.Regular), "Hello World!", new Aspose.Imaging.Point(200, 300), Aspose.Imaging.Color.DarkRed);

// Create a path to fill
Aspose.Imaging.Figure figureToFill = new Aspose.Imaging.Figure();
figureToFill.IsClosed = true;

Aspose.Imaging.GraphicsPath pathToFill = new Aspose.Imaging.GraphicsPath();
pathToFill.AddFigure(figureToFill);

figureToFill.AddShapes(new Shape[]
    {
        new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.Rectangle(400, 0, 200, 100), 45, 300),
        new Aspose.Imaging.Shapes.BezierShape(
            new Aspose.Imaging.PointF[]
            {
                new Aspose.Imaging.PointF(300, 200),
                new Aspose.Imaging.PointF(400, 200),
                new Aspose.Imaging.PointF(500, 100),
                new Aspose.Imaging.PointF(600, 200),
            }),
        new Aspose.Imaging.Shapes.PolygonShape(
            new Aspose.Imaging.PointF[]
            {
                new Aspose.Imaging.PointF(300, 100),
            }),
        new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(0, 100, 200, 200)),
    });

// Fill the path using a yellow brush and a green pen to draw outline
graphics.FillPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Yellow), pathToFill);

// Create a path to draw
Aspose.Imaging.GraphicsPath pathToDraw = new Aspose.Imaging.GraphicsPath();
Aspose.Imaging.Figure figureToDraw = new Aspose.Imaging.Figure();
pathToDraw.AddFigure(figureToDraw);

figureToDraw.AddShapes(new Aspose.Imaging.Shape[]
    {
        new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(200, 200, 200, 200), 0, 360),
    });

// Draw the path using a 5-pixel-wide orange pen.
graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 5), pathToDraw);

// Get the final SVG image which includes all drawing commands
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = graphics.EndRecording())
{
    svgImage.Save(dir + "test.output.svg");
}
```

### See Also

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* struct [Point](../../../aspose.imaging/point/)
* struct [Size](../../../aspose.imaging/size/)
* class [SvgGraphics2D](../)
* namespace [Aspose.Imaging.FileFormats.Svg.Graphics](../../svggraphics2d/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Rectangle, Rectangle, RasterImage) {#drawimage_2}

Draws the specified portion of the specified image at the specified location and with the specified size.

```csharp
public void DrawImage(Rectangle srcRect, Rectangle destRect, RasterImage image)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcRect | Rectangle | The portion of the image object to draw. |
| destRect | Rectangle | The location and size of the drawn image. The image is scaled to fit the rectangle. |
| image | RasterImage | The image to draw. |

### See Also

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [SvgGraphics2D](../)
* namespace [Aspose.Imaging.FileFormats.Svg.Graphics](../../svggraphics2d/)
* assembly [Aspose.Imaging](../../../)


