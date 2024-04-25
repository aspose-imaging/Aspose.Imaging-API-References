---
title: DrawLine
second_title: Aspose.Imaging für .NET-API-Referenz
description: Zeichnet die Linie.
type: docs
weight: 90
url: /de/aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline/
---
## DrawLine(Pen, int, int, int, int) {#drawline_1}

Zeichnet die Linie.

```csharp
public void DrawLine(Pen pen, int x1, int y1, int x2, int y2)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | Stift, der Farbe, Breite und Stil der Figur bestimmt. |
| x1 | Int32 | Die x-Koordinate des ersten Punktes. |
| y1 | Int32 | Die y-Koordinate des ersten Punktes. |
| x2 | Int32 | Die x-Koordinate des zweiten Punktes. |
| y2 | Int32 | Die y-Koordinate des zweiten Punktes. |

### Beispiele

Dieses Beispiel zeigt, wie Sie mit WmfRecorderGraphics2D ein WMF-Bild erstellen und einige geometrische Formen zeichnen.

```csharp
[C#]

string dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;

// Dies ist die Standardbildschirmauflösung.
int dpi = 96;

Aspose.Imaging.Rectangle frame = new Aspose.Imaging.Rectangle(0, 0, imageWidth, imageHeight);

// Erstellen Sie ein WMF-Bild.
Aspose.Imaging.FileFormats.Wmf.Graphics.WmfRecorderGraphics2D graphics =
    new Aspose.Imaging.FileFormats.Wmf.Graphics.WmfRecorderGraphics2D(frame, dpi);

// Zeichnen Sie mit einem 1 Pixel breiten schwarzen Stift ein schwarzes Rechteck entlang der Bildränder.
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, imageWidth, imageHeight);

// Fülle ein Rechteck mit der Farbe von weißem Rauch.
graphics.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), new Aspose.Imaging.Rectangle(10, 10, 580, 380));

// Zeichnen Sie zwei diagonale Linien mit einem 1 Pixel breiten dunkelgrünen Stift.
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, imageWidth, imageHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, imageHeight, imageWidth, 0);

// Zeichne einen Bogen innerhalb des Rechtecks {0, 0, 200, 200} mit einem 2 Pixel breiten blauen Stift.
graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Einen Bogen füllen
graphics.FillPie(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.LightSkyBlue), new Aspose.Imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Zeichne einen kubischen Bezier mit einem 2 Pixel breiten roten Stift.
graphics.DrawCubicBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2),
    new Aspose.Imaging.Point(0, 0),
    new Aspose.Imaging.Point(200, 133),
    new Aspose.Imaging.Point(400, 166),
    new Aspose.Imaging.Point(600, 400));

// Zeichnen Sie ein Rasterbild der angegebenen Größe an der angegebenen Position.
// Das Bild wird so skaliert, dass es in das gewünschte Rechteck passt.
using (Aspose.Imaging.RasterImage imageToDraw = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    graphics.DrawImage(imageToDraw,
        new Aspose.Imaging.Rectangle(400, 200, 100, 50),
        new Aspose.Imaging.Rectangle(0, 0, imageWidth, imageHeight),
        Aspose.Imaging.GraphicsUnit.Pixel);
}

// Zeichne eine Textzeichenfolge
graphics.DrawString("Hello World!", new Aspose.Imaging.Font("Arial", 48, Aspose.Imaging.FontStyle.Regular), Aspose.Imaging.Color.DarkRed, 200, 300);

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

// Um SVG zu rastern, müssen wir Rasterisierungsoptionen angeben.
Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();
Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
saveOptions.VectorRasterizationOptions = rasterizationOptions;

// Holen Sie sich das endgültige WMF-Bild, das alle Zeichenbefehle enthält
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = graphics.EndRecording())
{
    wmfImage.Save(dir + "test.output.wmf");
}
```

Dieses Beispiel zeigt, wie Sie mit EmfRecorderGraphics2D ein EMF-Bild erstellen und einige geometrische Formen darauf zeichnen.

```csharp
[C#]

string dir = "c:\\temp\\";

// Die Bildgröße in Pixel
int deviceWidth = 600;
int deviceHeight = 400;

// Die Bildgröße in Millimetern
int deviceWidthMm = (int)(deviceWidth / 100f);
int deviceHeightMm = (int)(deviceHeight / 100f);

Aspose.Imaging.Rectangle frame = new Aspose.Imaging.Rectangle(0, 0, deviceWidth, deviceHeight);

// Erstellen Sie ein EMF-Bild.
Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D graphics =
    new Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D(
        frame,
        new Aspose.Imaging.Size(deviceWidth, deviceHeight),
        new Aspose.Imaging.Size(deviceWidthMm, deviceHeightMm));

// Zeichnen Sie mit einem 1 Pixel breiten schwarzen Stift ein schwarzes Rechteck entlang der Bildränder.
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, deviceWidth, deviceHeight);

// Fülle ein Rechteck mit der Farbe von weißem Rauch.
graphics.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), new Aspose.Imaging.Rectangle(10, 10, 580, 380));

// Zeichnen Sie zwei diagonale Linien mit einem 1 Pixel breiten dunkelgrünen Stift.
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, deviceWidth, deviceHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, deviceHeight, deviceWidth, 0);

// Zeichne einen Bogen innerhalb des Rechtecks {0, 0, 200, 200} mit einem 2 Pixel breiten blauen Stift.
graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Einen Bogen füllen
graphics.FillPie(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.LightSkyBlue), new Aspose.Imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Zeichne einen kubischen Bezier mit einem 2 Pixel breiten roten Stift.
graphics.DrawCubicBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2),
    new Aspose.Imaging.Point(0, 0),
    new Aspose.Imaging.Point(200, 133),
    new Aspose.Imaging.Point(400, 166),
    new Aspose.Imaging.Point(600, 400));

// Zeichnen Sie ein Rasterbild der angegebenen Größe an der angegebenen Position.
// Das Bild wird so skaliert, dass es in das gewünschte Rechteck passt.
using (Aspose.Imaging.RasterImage imageToDraw = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    graphics.DrawImage(imageToDraw,
        new Aspose.Imaging.Rectangle(400, 200, 100, 50),
        new Aspose.Imaging.Rectangle(0, 0, deviceWidth, deviceHeight),
        Aspose.Imaging.GraphicsUnit.Pixel);
}

// Zeichne eine Textzeichenfolge
graphics.DrawString("Hello World!", new Aspose.Imaging.Font("Arial", 48, Aspose.Imaging.FontStyle.Regular), Aspose.Imaging.Color.DarkRed, 200, 300);

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

// Um SVG zu rastern, müssen wir Rasterisierungsoptionen angeben.
Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();
Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
saveOptions.VectorRasterizationOptions = rasterizationOptions;

// Holen Sie sich das endgültige WMF-Bild, das alle Zeichenbefehle enthält
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = graphics.EndRecording())
{
    emfImage.Save(dir + "test.output.emf");
}
```

### Siehe auch

* class [Pen](../../../aspose.imaging/pen)
* class [MetafileRecorderGraphics2D](../../metafilerecordergraphics2d)
* namensraum [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d)
* Montage [Aspose.Imaging](../../../)

---

## DrawLine(Pen, Point, Point) {#drawline}

Zeichnet die Linie.

```csharp
public void DrawLine(Pen pen, Point pt1, Point pt2)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | Stift, der Farbe, Breite und Stil der Figur bestimmt. |
| pt1 | Point | Der erste Punkt. |
| pt2 | Point | Der zweite Punkt. |

### Siehe auch

* class [Pen](../../../aspose.imaging/pen)
* struct [Point](../../../aspose.imaging/point)
* class [MetafileRecorderGraphics2D](../../metafilerecordergraphics2d)
* namensraum [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
