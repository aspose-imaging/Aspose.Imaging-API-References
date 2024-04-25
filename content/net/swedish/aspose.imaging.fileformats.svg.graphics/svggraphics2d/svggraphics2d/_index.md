---
title: SvgGraphics2D
second_title: Aspose.Imaging för .NET API-referens
description: Initierar en ny instans avSvgGraphics2Daspose.imaging.fileformats.svg.graphics/svggraphics2d class.
type: docs
weight: 10
url: /sv/aspose.imaging.fileformats.svg.graphics/svggraphics2d/svggraphics2d/
---
## SvgGraphics2D(int, int, int) {#constructor_1}

Initierar en ny instans av[`SvgGraphics2D`](../../svggraphics2d) class.

```csharp
public SvgGraphics2D(int width, int height, int dpi)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | Int32 | Bredden på den utgående Svg-bilden. |
| height | Int32 | Bredden på den utgående Svg-bilden. |
| dpi | Int32 | Enhetens upplösning, t.ex. 96 punkter per tum. |

### Exempel

Det här exemplet visar hur man skapar en SVG-bild av den angivna storleken och rastrerar den till PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

int imageWidth = 100;
int imageHeight = 100;
int dpi = 96;

// Skapa en SVG-bild på 100x100 px.
Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D graphics = new Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D(imageWidth, imageHeight, dpi);

Aspose.Imaging.Pen pen = new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 10);
Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

// Fyll hela bilden i rött.
// Rita en gul rektangel på 10px bred längs bildgränserna.
graphics.FillRectangle(pen, brush, 0, 0, imageWidth, imageHeight);

// Få den sista Svg-bilden som innehåller alla ritkommandon
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = graphics.EndRecording())
{
    svgImage.Save(dir + "test.output.svg");
}
```

Det här exemplet visar hur man skapar en SVG-bild av den angivna storleken och ritar olika former på den med SvgGraphics2D.

```csharp
[C#]

string dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;
int dpi = 96;

Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D graphics = new Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D(imageWidth, imageHeight, dpi);

// Rita en svart rektangel längs bildkanterna med en 1-pixel bred svart penna.
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, imageWidth, imageHeight);

// Fyll en rektangel med färgen på vit rök.
graphics.FillRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.WhiteSmoke, 1), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), 10, 10, 580, 380);

// Rita två diagonala linjer med en 1-pixel bred mörkgrön penna.
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, imageWidth, imageHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, imageHeight, imageWidth, 0);

// Rita en båge inom rektangeln {0, 0, 200, 200} med en 2-pixel bred blå penna.
graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Fyll en båge
graphics.FillArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.LightCoral, 10), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.LightSkyBlue), new Aspose.Imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Rita en kubisk bezier med en 2-pixel bred röd penna.
graphics.DrawCubicBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2),
    new Aspose.Imaging.PointF(0, 0),
    new Aspose.Imaging.PointF(200, 133),
    new Aspose.Imaging.PointF(400, 166),
    new Aspose.Imaging.PointF(600, 400));

// Rita en rasterbild av den angivna storleken på den angivna platsen.
// Bilden skalas för att passa den önskade rektangeln.
using (Aspose.Imaging.RasterImage imageToDraw = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    graphics.DrawImage(imageToDraw, new Aspose.Imaging.Point(400, 200), new Aspose.Imaging.Size(100, 50));
}

// Rita en textsträng
graphics.DrawString(new Aspose.Imaging.Font("Arial", 48, Aspose.Imaging.FontStyle.Regular), "Hello World!", new Aspose.Imaging.Point(200, 300), Aspose.Imaging.Color.DarkRed);

// Skapa en sökväg att fylla
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

// Fyll banan med en gul pensel och en grön penna för att rita konturerna
graphics.FillPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Yellow), pathToFill);

// Skapa en bana att rita
Aspose.Imaging.GraphicsPath pathToDraw = new Aspose.Imaging.GraphicsPath();
Aspose.Imaging.Figure figureToDraw = new Aspose.Imaging.Figure();
pathToDraw.AddFigure(figureToDraw);

figureToDraw.AddShapes(new Aspose.Imaging.Shape[]
    {
        new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(200, 200, 200, 200), 0, 360),
    });

// Rita banan med en 5-pixel bred orange penna.
graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 5), pathToDraw);

// Hämta den slutliga SVG-bilden som innehåller alla ritkommandon
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = graphics.EndRecording())
{
    svgImage.Save(dir + "test.output.svg");
}
```

### Se även

* class [SvgGraphics2D](../../svggraphics2d)
* namnutrymme [Aspose.Imaging.FileFormats.Svg.Graphics](../../svggraphics2d)
* hopsättning [Aspose.Imaging](../../../)

---

## SvgGraphics2D(SvgImage) {#constructor}

Initierar en ny instans av[`SvgGraphics2D`](../../svggraphics2d) class.

```csharp
public SvgGraphics2D(SvgImage image)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | SvgImage | Bilden att utföra ritoperationer på. |

### Se även

* class [SvgImage](../../../aspose.imaging.fileformats.svg/svgimage)
* class [SvgGraphics2D](../../svggraphics2d)
* namnutrymme [Aspose.Imaging.FileFormats.Svg.Graphics](../../svggraphics2d)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
