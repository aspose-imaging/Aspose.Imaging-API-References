---
title: DrawImage
second_title: Aspose.Imaging für .NET-API-Referenz
description: Zeichnet das angegebene Bild an der angegebenen Position.
type: docs
weight: 40
url: /de/aspose.imaging.fileformats.svg.graphics/svggraphics2d/drawimage/
---
## DrawImage(RasterImage, Point) {#drawimage}

Zeichnet das angegebene Bild an der angegebenen Position.

```csharp
public void DrawImage(RasterImage image, Point origin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | RasterImage | Das gezeichnete Bild. |
| origin | Point | Der Speicherort des gezeichneten Bildes. |

### Siehe auch

* class [RasterImage](../../../aspose.imaging/rasterimage)
* struct [Point](../../../aspose.imaging/point)
* class [SvgGraphics2D](../../svggraphics2d)
* namensraum [Aspose.Imaging.FileFormats.Svg.Graphics](../../svggraphics2d)
* Montage [Aspose.Imaging](../../../)

---

## DrawImage(RasterImage, Point, Size) {#drawimage_1}

Zeichnet das angegebene Bild der angegebenen Größe an der angegebenen Position.

```csharp
public void DrawImage(RasterImage image, Point origin, Size size)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | RasterImage | Das gezeichnete Bild. |
| origin | Point | Der Speicherort des gezeichneten Bildes. |
| size | Size | Die gewünschte Größe des gezeichneten Bildes. |

### Beispiele

Dieses Beispiel zeigt, wie man ein SVG-Bild der angegebenen Größe erstellt und mit SvgGraphics2D verschiedene Formen darauf zeichnet.

```csharp
[C#]

string dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;
int dpi = 96;

Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D graphics = new Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D(imageWidth, imageHeight, dpi);

// Zeichnen Sie mit einem 1 Pixel breiten schwarzen Stift ein schwarzes Rechteck entlang der Bildränder.
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, imageWidth, imageHeight);

// Fülle ein Rechteck mit der Farbe von weißem Rauch.
graphics.FillRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.WhiteSmoke, 1), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), 10, 10, 580, 380);

// Zeichnen Sie zwei diagonale Linien mit einem 1 Pixel breiten dunkelgrünen Stift.
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, imageWidth, imageHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, imageHeight, imageWidth, 0);

// Zeichne einen Bogen innerhalb des Rechtecks {0, 0, 200, 200} mit einem 2 Pixel breiten blauen Stift.
graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Einen Bogen füllen
graphics.FillArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.LightCoral, 10), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.LightSkyBlue), new Aspose.Imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Zeichne einen kubischen Bezier mit einem 2 Pixel breiten roten Stift.
graphics.DrawCubicBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2),
    new Aspose.Imaging.PointF(0, 0),
    new Aspose.Imaging.PointF(200, 133),
    new Aspose.Imaging.PointF(400, 166),
    new Aspose.Imaging.PointF(600, 400));

// Zeichnen Sie ein Rasterbild der angegebenen Größe an der angegebenen Position.
// Das Bild wird so skaliert, dass es in das gewünschte Rechteck passt.
using (Aspose.Imaging.RasterImage imageToDraw = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    graphics.DrawImage(imageToDraw, new Aspose.Imaging.Point(400, 200), new Aspose.Imaging.Size(100, 50));
}

// Zeichne eine Textzeichenfolge
graphics.DrawString(new Aspose.Imaging.Font("Arial", 48, Aspose.Imaging.FontStyle.Regular), "Hello World!", new Aspose.Imaging.Point(200, 300), Aspose.Imaging.Color.DarkRed);

// Erstellen Sie einen zu füllenden Pfad
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

// Füllen Sie den Pfad mit einem gelben Pinsel und einem grünen Stift, um Umrisse zu zeichnen
graphics.FillPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Yellow), pathToFill);

// Erstellen Sie einen zu zeichnenden Pfad
Aspose.Imaging.GraphicsPath pathToDraw = new Aspose.Imaging.GraphicsPath();
Aspose.Imaging.Figure figureToDraw = new Aspose.Imaging.Figure();
pathToDraw.AddFigure(figureToDraw);

figureToDraw.AddShapes(new Aspose.Imaging.Shape[]
    {
        new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(200, 200, 200, 200), 0, 360),
    });

// Zeichnen Sie den Pfad mit einem 5 Pixel breiten orangefarbenen Stift.
graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 5), pathToDraw);

// Holen Sie sich das endgültige SVG-Bild, das alle Zeichenbefehle enthält
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = graphics.EndRecording())
{
    svgImage.Save(dir + "test.output.svg");
}
```

### Siehe auch

* class [RasterImage](../../../aspose.imaging/rasterimage)
* struct [Point](../../../aspose.imaging/point)
* struct [Size](../../../aspose.imaging/size)
* class [SvgGraphics2D](../../svggraphics2d)
* namensraum [Aspose.Imaging.FileFormats.Svg.Graphics](../../svggraphics2d)
* Montage [Aspose.Imaging](../../../)

---

## DrawImage(Rectangle, Rectangle, RasterImage) {#drawimage_2}

Zeichnet den angegebenen Teil des angegebenen Bilds an der angegebenen Position und mit der angegebenen Größe.

```csharp
public void DrawImage(Rectangle srcRect, Rectangle destRect, RasterImage image)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcRect | Rectangle | Der zu zeichnende Teil des Bildobjekts. |
| destRect | Rectangle | Die Position und Größe des gezeichneten Bildes. Das Bild wird so skaliert, dass es in das Rechteck passt. |
| image | RasterImage | Das zu zeichnende Bild. |

### Siehe auch

* struct [Rectangle](../../../aspose.imaging/rectangle)
* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [SvgGraphics2D](../../svggraphics2d)
* namensraum [Aspose.Imaging.FileFormats.Svg.Graphics](../../svggraphics2d)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
