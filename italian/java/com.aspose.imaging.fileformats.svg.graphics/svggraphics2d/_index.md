---
title: "SvgGraphics2D"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Fornisce comandi di disegno per comporre un'immagine Svg."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.svg.graphics/svggraphics2d/
---
**Inheritance:**
java.lang.Object
```
public class SvgGraphics2D
```

Fornisce comandi di disegno per comporre un'immagine Svg.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SvgGraphics2D(int width, int height, int dpi)](#SvgGraphics2D-int-int-int-) | Inizializza una nuova istanza della classe [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d). |
| [SvgGraphics2D(SvgImage image)](#SvgGraphics2D-com.aspose.imaging.fileformats.svg.SvgImage-) | Inizializza una nuova istanza della classe [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [drawImage(RasterImage image, Point origin)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-) | Disegna l'immagine specificata nella posizione specificata. |
| [drawImage(RasterImage image, Point origin, Size size)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Disegna l'immagine specificata della dimensione specificata nella posizione specificata. |
| [drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image)](#drawImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RasterImage-) | Disegna la porzione specificata dell'immagine specificata nella posizione specificata e con la dimensione specificata. |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)](#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura Rectangle. |
| [fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle)](#fillArc-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-) | Riempie un arco che rappresenta una porzione di un'ellisse specificata da una struttura Rectangle. |
| [drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Disegna il bezier cubico. |
| [drawString(Font font, String text, Point origin, Color textColor)](#drawString-com.aspose.imaging.Font-java.lang.String-com.aspose.imaging.Point-com.aspose.imaging.Color-) | Disegna la stringa di testo. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.imaging.Pen-int-int-int-int-) | Disegna la linea. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-) | Disegna il percorso. |
| [fillPath(Pen pen, Brush brush, GraphicsPath path)](#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-) | Riempie il percorso. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-) | Disegna il rettangolo. |
| [fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Brush-int-int-int-int-) | Riempie il rettangolo. |
| [endRecording()](#endRecording--) | Ottiene l'immagine Svg finale che include tutti i comandi di disegno eseguiti tramite l'oggetto [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d). |

## Example: This example shows how to create an SVG image of the specified size and draw different shapes on it using SvgGraphics2D.

``` java
String dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;
int dpi = 96;

com.aspose.imaging.fileformats.svg.graphics.SvgGraphics2D graphics = new com.aspose.imaging.fileformats.svg.graphics.SvgGraphics2D(imageWidth, imageHeight, dpi);

// Disegna un rettangolo nero lungo i bordi dell'immagine usando una penna nera larga 1 pixel.
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, imageWidth, imageHeight);

// Riempi un rettangolo con il colore white-smoke.
graphics.fillRectangle(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getWhiteSmoke(), 1),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()), 10, 10, 580, 380);

// Disegna due linee diagonali usando una penna darkgreen larga 1 pixel.
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, imageWidth, imageHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, imageHeight, imageWidth, 0);

// Disegna un arco all'interno del rettangolo {0, 0, 200, 200} usando una penna blu larga 2 pixel.
graphics.drawArc(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
        new com.aspose.imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Riempi un arco
graphics.fillArc(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getLightCoral(), 10),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getLightSkyBlue()),
        new com.aspose.imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Disegna un bezier cubico usando una penna rossa larga 2 pixel.
graphics.drawCubicBezier(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
        new com.aspose.imaging.PointF(0, 0),
        new com.aspose.imaging.PointF(200, 133),
        new com.aspose.imaging.PointF(400, 166),
        new com.aspose.imaging.PointF(600, 400));

// Disegna un'immagine raster della dimensione specificata nella posizione specificata.
// L'immagine è scalata per adattarsi al rettangolo desiderato.
com.aspose.imaging.RasterImage imageToDraw = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    graphics.drawImage(imageToDraw, new com.aspose.imaging.Point(400, 200), new com.aspose.imaging.Size(100, 50));
} finally {
    imageToDraw.dispose();
}

// Disegna una stringa di testo
graphics.drawString(
        new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular),
        "Hello World!",
        new com.aspose.imaging.Point(200, 300),
        com.aspose.imaging.Color.getDarkRed());

// Crea un percorso da riempire
com.aspose.imaging.Figure figureToFill = new com.aspose.imaging.Figure();
figureToFill.setClosed(true);

com.aspose.imaging.GraphicsPath pathToFill = new com.aspose.imaging.GraphicsPath();
pathToFill.addFigure(figureToFill);

figureToFill.addShapes(new com.aspose.imaging.Shape[]
        {
                new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(400, 0, 200, 100), 45, 300),
                new com.aspose.imaging.shapes.BezierShape(
                        new com.aspose.imaging.PointF[]
                                {
                                        new com.aspose.imaging.PointF(300, 200),
                                        new com.aspose.imaging.PointF(400, 200),
                                        new com.aspose.imaging.PointF(500, 100),
                                        new com.aspose.imaging.PointF(600, 200),
                                }),
                new com.aspose.imaging.shapes.PolygonShape(
                        new com.aspose.imaging.PointF[]
                                {
                                        new com.aspose.imaging.PointF(300, 100),
                                }),
                new com.aspose.imaging.shapes.RectangleShape(
                        new com.aspose.imaging.RectangleF(0, 100, 200, 200)),
        });

// Riempi il percorso usando un pennello giallo e una penna verde per disegnare il contorno
graphics.fillPath(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getYellow()), pathToFill);

// Crea un percorso da disegnare
com.aspose.imaging.GraphicsPath pathToDraw = new com.aspose.imaging.GraphicsPath();
com.aspose.imaging.Figure figureToDraw = new com.aspose.imaging.Figure();
pathToDraw.addFigure(figureToDraw);

figureToDraw.addShapes(new com.aspose.imaging.Shape[]
        {
                new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(200, 200, 200, 200), 0, 360),
        });

// Disegna il percorso usando una penna arancione larga 5 pixel.
graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 5), pathToDraw);

// Ottieni l'immagine SVG finale che include tutti i comandi di disegno
com.aspose.imaging.fileformats.svg.SvgImage svgImage = graphics.endRecording();
try {
    svgImage.save(dir + "test.output.svg");
} finally {
    svgImage.dispose();
}
```

### SvgGraphics2D(int width, int height, int dpi) {#SvgGraphics2D-int-int-int-}
```
public SvgGraphics2D(int width, int height, int dpi)
```


Inizializza una nuova istanza della classe [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza dell'immagine Svg di output. |
| height | int | La larghezza dell'immagine Svg di output. |
| dpi | int | La risoluzione del dispositivo, ad es. 96 punti per pollice. |

### SvgGraphics2D(SvgImage image) {#SvgGraphics2D-com.aspose.imaging.fileformats.svg.SvgImage-}
```
public SvgGraphics2D(SvgImage image)
```


Inizializza una nuova istanza della classe [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) | L'immagine su cui eseguire le operazioni di disegno. |

### drawImage(RasterImage image, Point origin) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-}
```
public final void drawImage(RasterImage image, Point origin)
```


Disegna l'immagine specificata nella posizione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine disegnata. |
| origin | [Point](../../com.aspose.imaging/point) | La posizione dell'immagine disegnata. |

### drawImage(RasterImage image, Point origin, Size size) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public final void drawImage(RasterImage image, Point origin, Size size)
```


Disegna l'immagine specificata della dimensione specificata nella posizione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine disegnata. |
| origin | [Point](../../com.aspose.imaging/point) | La posizione dell'immagine disegnata. |
| size | [Size](../../com.aspose.imaging/size) | La dimensione desiderata dell'immagine disegnata. |

### drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image) {#drawImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RasterImage-}
```
public final void drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image)
```


Disegna la porzione specificata dell'immagine specificata nella posizione specificata e con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcRect | [Rectangle](../../com.aspose.imaging/rectangle) | La porzione dell'oggetto immagine da disegnare. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | La posizione e la dimensione dell'immagine disegnata. L'immagine è scalata per adattarsi al rettangolo. |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine da disegnare. |

### drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle) {#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public final void drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)
```


Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura Rectangle.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | La penna per disegnare il contorno della figura. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | I confini dell'ellisse. |
| startAngle | float | L'angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| arcAngle | float | L'angolo in gradi misurato in senso orario dal parametro startAngle al punto finale dell'arco. |

### fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle) {#fillArc-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-}
```
public final void fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle)
```


Riempie un arco che rappresenta una porzione di un'ellisse specificata da una struttura Rectangle.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | La penna per disegnare il contorno della figura. |
| brush | [Brush](../../com.aspose.imaging/brush) | Il pennello per riempire l'interno della figura. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | I confini dell'ellisse. |
| startAngle | float | L'angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| arcAngle | float | L'angolo in gradi misurato in senso orario dal parametro startAngle al punto finale dell'arco. |

### drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public final void drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


Disegna il bezier cubico.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | La penna che determina il colore, la larghezza e lo stile della figura. |
| pt1 | [PointF](../../com.aspose.imaging/pointf) | Il punto di partenza della curva. |
| pt2 | [PointF](../../com.aspose.imaging/pointf) | Il primo punto di controllo per la curva. |
| pt3 | [PointF](../../com.aspose.imaging/pointf) | Il secondo punto di controllo per la curva. |
| pt4 | [PointF](../../com.aspose.imaging/pointf) | Il punto finale della curva. |

### drawString(Font font, String text, Point origin, Color textColor) {#drawString-com.aspose.imaging.Font-java.lang.String-com.aspose.imaging.Point-com.aspose.imaging.Color-}
```
public final void drawString(Font font, String text, Point origin, Color textColor)
```


Disegna la stringa di testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| font | [Font](../../com.aspose.imaging/font) | Il carattere usato per visualizzare il testo. |
| testo | java.lang.String | La stringa di testo Unicode. |
| origin | [Point](../../com.aspose.imaging/point) | L'angolo in alto a sinistra dell'esecuzione del testo. |
| textColor | [Color](../../com.aspose.imaging/color) | Il colore del testo. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.imaging.Pen-int-int-int-int-}
```
public final void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Disegna la linea.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | La penna che determina il colore, la larghezza e lo stile della figura. |
| x1 | int | La coordinata x del primo punto. |
| y1 | int | La coordinata y del primo punto. |
| x2 | int | La coordinata x del secondo punto. |
| y2 | int | La coordinata y del secondo punto. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-}
```
public final void drawPath(Pen pen, GraphicsPath path)
```


Disegna il percorso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | La penna per disegnare il contorno della figura. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Il percorso da disegnare. |

### fillPath(Pen pen, Brush brush, GraphicsPath path) {#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-}
```
public final void fillPath(Pen pen, Brush brush, GraphicsPath path)
```


Riempie il percorso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | La penna per disegnare il contorno della figura. |
| brush | [Brush](../../com.aspose.imaging/brush) | Il pennello per riempire l'interno della figura. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Il percorso da disegnare. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-}
```
public final void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Disegna il rettangolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | La penna per disegnare il contorno della figura. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo da disegnare. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo da disegnare. |
| width | int | La larghezza del rettangolo da disegnare. |
| height | int | L'altezza del rettangolo da disegnare. |

### fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Brush-int-int-int-int-}
```
public final void fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height)
```


Riempie il rettangolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | La penna per disegnare il contorno della figura. |
| brush | [Brush](../../com.aspose.imaging/brush) | Il pennello per riempire l'interno della figura. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo da disegnare. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo da disegnare. |
| width | int | La larghezza del rettangolo da disegnare. |
| height | int | L'altezza del rettangolo da disegnare. |

### endRecording() {#endRecording--}
```
public final SvgImage endRecording()
```


Ottiene l'immagine Svg finale che include tutti i comandi di disegno eseguiti tramite l'oggetto [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d).

**Returns:**
[SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) - The final Svg image.
