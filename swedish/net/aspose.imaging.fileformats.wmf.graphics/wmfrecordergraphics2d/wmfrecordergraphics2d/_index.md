---
title: WmfRecorderGraphics2D
second_title: Aspose.Imaging för .NET API-referens
description: Initierar en ny instans avWmfRecorderGraphics2Daspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d class.
type: docs
weight: 10
url: /sv/net/aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d/wmfrecordergraphics2d/
---
## WmfRecorderGraphics2D constructor

Initierar en ny instans av[`WmfRecorderGraphics2D`](../../wmfrecordergraphics2d) class.

```csharp
public WmfRecorderGraphics2D(Rectangle frame, int inch)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| frame | Rectangle | Destinationsrektangel, mätt i twips, för att visa metafilen. |
| inch | Int32 | Antalet pixlar per tum. |

### Exempel

Det här exemplet visar hur man skapar en WMF-bild och ritar några geometriska former med WmfRecorderGraphics2D.

```csharp
[C#]

string dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;

// Detta är standardskärmupplösningen.
int dpi = 96;

Aspose.Imaging.Rectangle frame = new Aspose.Imaging.Rectangle(0, 0, imageWidth, imageHeight);

// Skapa en WMF-bild.
Aspose.Imaging.FileFormats.Wmf.Graphics.WmfRecorderGraphics2D graphics =
    new Aspose.Imaging.FileFormats.Wmf.Graphics.WmfRecorderGraphics2D(frame, dpi);

// Rita en svart rektangel längs bildkanterna med en 1-pixel bred svart penna.
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, imageWidth, imageHeight);

// Fyll en rektangel med färgen på vit rök.
graphics.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), new Aspose.Imaging.Rectangle(10, 10, 580, 380));

// Rita två diagonala linjer med en 1-pixel bred mörkgrön penna.
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, imageWidth, imageHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, imageHeight, imageWidth, 0);

// Rita en båge inom rektangeln {0, 0, 200, 200} med en 2-pixel bred blå penna.
graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Fyll en båge
graphics.FillPie(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.LightSkyBlue), new Aspose.Imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Rita en kubisk bezier med en 2-pixel bred röd penna.
graphics.DrawCubicBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2),
    new Aspose.Imaging.Point(0, 0),
    new Aspose.Imaging.Point(200, 133),
    new Aspose.Imaging.Point(400, 166),
    new Aspose.Imaging.Point(600, 400));

// Rita en rasterbild av den angivna storleken på den angivna platsen.
// Bilden skalas för att passa den önskade rektangeln.
using (Aspose.Imaging.RasterImage imageToDraw = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    graphics.DrawImage(imageToDraw,
        new Aspose.Imaging.Rectangle(400, 200, 100, 50),
        new Aspose.Imaging.Rectangle(0, 0, imageWidth, imageHeight),
        Aspose.Imaging.GraphicsUnit.Pixel);
}

// Rita en textsträng
graphics.DrawString("Hello World!", new Aspose.Imaging.Font("Arial", 48, Aspose.Imaging.FontStyle.Regular), Aspose.Imaging.Color.DarkRed, 200, 300);

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

// För att rastrera SVG måste vi ange rastreringsalternativ.
Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();
Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
saveOptions.VectorRasterizationOptions = rasterizationOptions;

// Hämta den slutliga WMF-bilden som innehåller alla ritkommandon
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = graphics.EndRecording())
{
    wmfImage.Save(dir + "test.output.wmf");
}
```

### Se även

* struct [Rectangle](../../../aspose.imaging/rectangle)
* class [WmfRecorderGraphics2D](../../wmfrecordergraphics2d)
* namnutrymme [Aspose.Imaging.FileFormats.Wmf.Graphics](../../wmfrecordergraphics2d)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
