---
title: DrawImage
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Disegna limmagine specificata utilizzando la sua dimensione fisica originale nella posizione specificata.
type: docs
weight: 80
url: /it/aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage/
---
## DrawImage(RasterImage, Point) {#drawimage}

Disegna l'immagine specificata, utilizzando la sua dimensione fisica originale, nella posizione specificata.

```csharp
public void DrawImage(RasterImage image, Point location)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | RasterImage | L'immagine da disegnare. |
| location | Point | La posizione dell'angolo superiore sinistro dell'immagine disegnata. |

### Guarda anche

* class [RasterImage](../../../aspose.imaging/rasterimage)
* struct [Point](../../../aspose.imaging/point)
* class [MetafileRecorderGraphics2D](../../metafilerecordergraphics2d)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d)
* assemblea [Aspose.Imaging](../../../)

---

## DrawImage(RasterImage, Rectangle, Rectangle, GraphicsUnit) {#drawimage_1}

Disegna la parte specificata dell'immagine specificata nella posizione specificata e con la dimensione specificata.

```csharp
public void DrawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, 
    GraphicsUnit srcUnit)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | RasterImage | L'immagine da disegnare. |
| destRect | Rectangle | Struttura rettangolare che specifica la posizione e la dimensione dell'immagine disegnata. L'immagine viene ridimensionata per adattarsi al rettangolo. |
| srcRect | Rectangle | Struttura rettangolare che specifica la parte dell'oggetto immagine da disegnare. |
| srcUnit | GraphicsUnit | Le unità di misura utilizzate dal parametro srcRect. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | srcUnit; Supporta solo l'unità Pixel |

### Esempi

Questo esempio mostra come creare un'immagine WMF e disegnare alcune forme geometriche usando WmfRecorderGraphics2D.

```csharp
[C#]

string dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;

// Questa è la risoluzione dello schermo predefinita.
int dpi = 96;

Aspose.Imaging.Rectangle frame = new Aspose.Imaging.Rectangle(0, 0, imageWidth, imageHeight);

// Crea un'immagine WMF.
Aspose.Imaging.FileFormats.Wmf.Graphics.WmfRecorderGraphics2D graphics =
    new Aspose.Imaging.FileFormats.Wmf.Graphics.WmfRecorderGraphics2D(frame, dpi);

// Disegna un rettangolo nero lungo i bordi dell'immagine usando una penna nera larga 1 pixel.
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, imageWidth, imageHeight);

// Riempi un rettangolo con il colore bianco-fumo.
graphics.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), new Aspose.Imaging.Rectangle(10, 10, 580, 380));

// Disegna due linee diagonali usando una penna verde scuro larga 1 pixel.
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, imageWidth, imageHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, imageHeight, imageWidth, 0);

// Disegna un arco all'interno del rettangolo {0, 0, 200, 200} usando una penna blu larga 2 pixel.
graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Riempi un arco
graphics.FillPie(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.LightSkyBlue), new Aspose.Imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Disegna un bezier cubico usando una penna rossa larga 2 pixel.
graphics.DrawCubicBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2),
    new Aspose.Imaging.Point(0, 0),
    new Aspose.Imaging.Point(200, 133),
    new Aspose.Imaging.Point(400, 166),
    new Aspose.Imaging.Point(600, 400));

// Disegna un'immagine raster della dimensione specificata nella posizione specificata.
// L'immagine viene ridimensionata per adattarsi al rettangolo desiderato.
using (Aspose.Imaging.RasterImage imageToDraw = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    graphics.DrawImage(imageToDraw,
        new Aspose.Imaging.Rectangle(400, 200, 100, 50),
        new Aspose.Imaging.Rectangle(0, 0, imageWidth, imageHeight),
        Aspose.Imaging.GraphicsUnit.Pixel);
}

// Disegna una stringa di testo
graphics.DrawString("Hello World!", new Aspose.Imaging.Font("Arial", 48, Aspose.Imaging.FontStyle.Regular), Aspose.Imaging.Color.DarkRed, 200, 300);

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

// Per rasterizzare SVG dobbiamo specificare le opzioni di rasterizzazione.
Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();
Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
saveOptions.VectorRasterizationOptions = rasterizationOptions;

// Ottieni l'immagine WMF finale che include tutti i comandi di disegno
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = graphics.EndRecording())
{
    wmfImage.Save(dir + "test.output.wmf");
}
```

Questo esempio mostra come creare un'immagine EMF e disegnarvi alcune forme geometriche utilizzando EmfRecorderGraphics2D.

```csharp
[C#]

string dir = "c:\\temp\\";

// La dimensione dell'immagine in pixel
int deviceWidth = 600;
int deviceHeight = 400;

// La dimensione dell'immagine in millimetri
int deviceWidthMm = (int)(deviceWidth / 100f);
int deviceHeightMm = (int)(deviceHeight / 100f);

Aspose.Imaging.Rectangle frame = new Aspose.Imaging.Rectangle(0, 0, deviceWidth, deviceHeight);

// Crea un'immagine EMF.
Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D graphics =
    new Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D(
        frame,
        new Aspose.Imaging.Size(deviceWidth, deviceHeight),
        new Aspose.Imaging.Size(deviceWidthMm, deviceHeightMm));

// Disegna un rettangolo nero lungo i bordi dell'immagine usando una penna nera larga 1 pixel.
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, deviceWidth, deviceHeight);

// Riempi un rettangolo con il colore bianco-fumo.
graphics.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), new Aspose.Imaging.Rectangle(10, 10, 580, 380));

// Disegna due linee diagonali usando una penna verde scuro larga 1 pixel.
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, deviceWidth, deviceHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, deviceHeight, deviceWidth, 0);

// Disegna un arco all'interno del rettangolo {0, 0, 200, 200} usando una penna blu larga 2 pixel.
graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Riempi un arco
graphics.FillPie(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.LightSkyBlue), new Aspose.Imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Disegna un bezier cubico usando una penna rossa larga 2 pixel.
graphics.DrawCubicBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2),
    new Aspose.Imaging.Point(0, 0),
    new Aspose.Imaging.Point(200, 133),
    new Aspose.Imaging.Point(400, 166),
    new Aspose.Imaging.Point(600, 400));

// Disegna un'immagine raster della dimensione specificata nella posizione specificata.
// L'immagine viene ridimensionata per adattarsi al rettangolo desiderato.
using (Aspose.Imaging.RasterImage imageToDraw = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    graphics.DrawImage(imageToDraw,
        new Aspose.Imaging.Rectangle(400, 200, 100, 50),
        new Aspose.Imaging.Rectangle(0, 0, deviceWidth, deviceHeight),
        Aspose.Imaging.GraphicsUnit.Pixel);
}

// Disegna una stringa di testo
graphics.DrawString("Hello World!", new Aspose.Imaging.Font("Arial", 48, Aspose.Imaging.FontStyle.Regular), Aspose.Imaging.Color.DarkRed, 200, 300);

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

// Per rasterizzare SVG dobbiamo specificare le opzioni di rasterizzazione.
Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();
Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
saveOptions.VectorRasterizationOptions = rasterizationOptions;

// Ottieni l'immagine WMF finale che include tutti i comandi di disegno
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = graphics.EndRecording())
{
    emfImage.Save(dir + "test.output.emf");
}
```

### Guarda anche

* class [RasterImage](../../../aspose.imaging/rasterimage)
* struct [Rectangle](../../../aspose.imaging/rectangle)
* enum [GraphicsUnit](../../../aspose.imaging/graphicsunit)
* class [MetafileRecorderGraphics2D](../../metafilerecordergraphics2d)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d)
* assemblea [Aspose.Imaging](../../../)

---

## DrawImage(byte[], Rectangle, GraphicsUnit) {#drawimage_2}

Disegna l'immagine.

```csharp
public void DrawImage(byte[] imageBytes, Rectangle destRect, GraphicsUnit srcUnit)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageBytes | Byte[] | I byte dell'immagine. |
| destRect | Rectangle | Il dest retto. |
| srcUnit | GraphicsUnit | L'unità sorgente. |

### Guarda anche

* struct [Rectangle](../../../aspose.imaging/rectangle)
* enum [GraphicsUnit](../../../aspose.imaging/graphicsunit)
* class [MetafileRecorderGraphics2D](../../metafilerecordergraphics2d)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d)
* assemblea [Aspose.Imaging](../../../)

---

## DrawImage(Stream, Rectangle, GraphicsUnit) {#drawimage_3}

Disegna l'immagine.

```csharp
public void DrawImage(Stream stream, Rectangle destRect, GraphicsUnit srcUnit)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso. |
| destRect | Rectangle | Il dest retto. |
| srcUnit | GraphicsUnit | L'unità sorgente. |

### Guarda anche

* struct [Rectangle](../../../aspose.imaging/rectangle)
* enum [GraphicsUnit](../../../aspose.imaging/graphicsunit)
* class [MetafileRecorderGraphics2D](../../metafilerecordergraphics2d)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
