---
title: DrawString
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Disegna la stringa di testo.
type: docs
weight: 80
url: /it/net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/drawstring/
---
## SvgGraphics2D.DrawString method

Disegna la stringa di testo.

```csharp
public void DrawString(Font font, string text, Point origin, Color textColor)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| font | Font | Il carattere utilizzato per il rendering del testo. |
| text | String | La stringa di testo unicode. |
| origin | Point | L'angolo in alto a sinistra del testo viene eseguito. |
| textColor | Color | Il colore del testo. |

### Esempi

Questo esempio mostra come creare un'immagine SVG della dimensione specificata e disegnarvi forme diverse usando SvgGraphics2D.

```csharp
[C#]

string dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;
int dpi = 96;

Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D graphics = new Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D(imageWidth, imageHeight, dpi);

// Disegna un rettangolo nero lungo i bordi dell'immagine usando una penna nera larga 1 pixel.
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, imageWidth, imageHeight);

// Riempi un rettangolo con il colore bianco-fumo.
graphics.FillRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.WhiteSmoke, 1), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), 10, 10, 580, 380);

// Disegna due linee diagonali usando una penna verde scuro larga 1 pixel.
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, imageWidth, imageHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, imageHeight, imageWidth, 0);

// Disegna un arco all'interno del rettangolo {0, 0, 200, 200} usando una penna blu larga 2 pixel.
graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Riempi un arco
graphics.FillArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.LightCoral, 10), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.LightSkyBlue), new Aspose.Imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Disegna un bezier cubico usando una penna rossa larga 2 pixel.
graphics.DrawCubicBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2),
    new Aspose.Imaging.PointF(0, 0),
    new Aspose.Imaging.PointF(200, 133),
    new Aspose.Imaging.PointF(400, 166),
    new Aspose.Imaging.PointF(600, 400));

// Disegna un'immagine raster della dimensione specificata nella posizione specificata.
// L'immagine viene ridimensionata per adattarsi al rettangolo desiderato.
using (Aspose.Imaging.RasterImage imageToDraw = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    graphics.DrawImage(imageToDraw, new Aspose.Imaging.Point(400, 200), new Aspose.Imaging.Size(100, 50));
}

// Disegna una stringa di testo
graphics.DrawString(new Aspose.Imaging.Font("Arial", 48, Aspose.Imaging.FontStyle.Regular), "Hello World!", new Aspose.Imaging.Point(200, 300), Aspose.Imaging.Color.DarkRed);

// Crea un percorso da riempire
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

// Riempi il percorso usando un pennello giallo e una penna verde per disegnare il contorno
graphics.FillPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Yellow), pathToFill);

// Crea un percorso da disegnare
Aspose.Imaging.GraphicsPath pathToDraw = new Aspose.Imaging.GraphicsPath();
Aspose.Imaging.Figure figureToDraw = new Aspose.Imaging.Figure();
pathToDraw.AddFigure(figureToDraw);

figureToDraw.AddShapes(new Aspose.Imaging.Shape[]
    {
        new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(200, 200, 200, 200), 0, 360),
    });

// Disegna il percorso usando una penna arancione larga 5 pixel.
graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 5), pathToDraw);

// Ottieni l'immagine SVG finale che include tutti i comandi di disegno
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = graphics.EndRecording())
{
    svgImage.Save(dir + "test.output.svg");
}
```

### Guarda anche

* class [Font](../../../aspose.imaging/font)
* struct [Point](../../../aspose.imaging/point)
* struct [Color](../../../aspose.imaging/color)
* class [SvgGraphics2D](../../svggraphics2d)
* spazio dei nomi [Aspose.Imaging.FileFormats.Svg.Graphics](../../svggraphics2d)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
