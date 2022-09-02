---
title: FillArc
second_title: Aspose.Imaging für .NET-API-Referenz
description: Füllt einen Bogen der einen Teil einer Ellipse darstellt die durch eine Rectangle-Struktur angegeben wird.
type: docs
weight: 100
url: /de/net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/fillarc/
---
## SvgGraphics2D.FillArc method

Füllt einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine Rectangle-Struktur angegeben wird.

```csharp
public void FillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | Der Stift, um den Umriss der Figur zu zeichnen. |
| brush | Brush | Der Pinsel, um das Innere der Figur zu füllen. |
| rect | Rectangle | Die Grenzen der Ellipse. |
| startAngle | Single | Der Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| arcAngle | Single | Der Winkel in Grad, gemessen im Uhrzeigersinn vom startAngle-Parameter zum Endpunkt des Bogens. |

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

* class [Pen](../../../aspose.imaging/pen)
* class [Brush](../../../aspose.imaging/brush)
* struct [Rectangle](../../../aspose.imaging/rectangle)
* class [SvgGraphics2D](../../svggraphics2d)
* namensraum [Aspose.Imaging.FileFormats.Svg.Graphics](../../svggraphics2d)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
