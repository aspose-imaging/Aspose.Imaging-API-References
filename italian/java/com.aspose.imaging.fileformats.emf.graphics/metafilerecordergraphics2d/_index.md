---
title: "MetafileRecorderGraphics2D"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "La grafica del registratore di metafile"
type: docs
weight: 11
url: /it/java/com.aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/
---
**Inheritance:**
java.lang.Object
```
public abstract class MetafileRecorderGraphics2D
```

La grafica del registratore di metafile
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MetafileRecorderGraphics2D()](#MetafileRecorderGraphics2D--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getClip()](#getClip--) | Ottiene o imposta una Region che limita l'area di disegno di questo Graphics |
| [setClip(Region value)](#setClip-com.aspose.imaging.Region-) | Ottiene o imposta una Region che limita l'area di disegno di questo Graphics |
| [getClipBounds()](#getClipBounds--) | Ottiene i limiti di clip. |
| [getBackgroundColor()](#getBackgroundColor--) | Ottiene il colore dello sfondo. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Imposta il colore dello sfondo. |
| [clear()](#clear--) | Cancella lo stato dell'oggetto graphics |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)](#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura Rectangle. |
| [drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Disegna il bezier cubico. |
| [drawPolyCubicBezier(Pen pen, Point[] points)](#drawPolyCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Disegna il poly cubic bezier. |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-) | Disegna l'ellisse. |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-) | Riempie l'ellisse. |
| [drawImage(RasterImage image, Point location)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-) | Disegna l'Image specificata, usando la sua dimensione fisica originale, nella posizione specificata. |
| [drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit)](#drawImage-byte---com.aspose.imaging.Rectangle-int-) | Disegna l'immagine. |
| [drawImage(InputStream stream, Rectangle destRect, int srcUnit)](#drawImage-java.io.InputStream-com.aspose.imaging.Rectangle-int-) | Disegna l'immagine. |
| [drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-int-) | Disegna la porzione specificata dell'Image specificata nella posizione specificata e con la dimensione specificata. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.imaging.Pen-int-int-int-int-) | Disegna la linea. |
| [drawLine(Pen pen, Point pt1, Point pt2)](#drawLine-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Disegna la linea. |
| [drawPolyline(Pen pen, Point[] points)](#drawPolyline-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Disegna la polilinea. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-) | Disegna il percorso. |
| [fillPath(Pen pen, Brush brush, GraphicsPath path)](#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-) | Riempie il percorso. |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Disegna la torta. |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-) | Riempie la torta. |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Disegna il poligono. |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---) | Riempie il poligono. |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-) | Riempie il poligono. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-) | Disegna il rettangolo. |
| [drawRectangle(Pen pen, Rectangle rectangle)](#drawRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-) | Disegna il rettangolo. |
| [fillRectangle(Brush brush, Rectangle rectangle)](#fillRectangle-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-) | Riempie il rettangolo. |
| [drawString(String string, Font font, Color color, int x, int y)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-) | Disegna la stringa. |
| [drawString(String string, Font font, Color color, int x, int y, float angle)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-float-) | Disegna la stringa. |
| [excludeClip(Rectangle rect)](#excludeClip-com.aspose.imaging.Rectangle-) | Aggiorna la regione di ritaglio di questo Graphics per escludere l'area specificata da una struttura Rectangle. |
| [excludeClip(Region region)](#excludeClip-com.aspose.imaging.Region-) | Aggiorna la regione di ritaglio di questo Graphics per escludere l'area specificata da una Region. |
| [intersectClip(RectangleF rect)](#intersectClip-com.aspose.imaging.RectangleF-) | Aggiorna la regione di ritaglio di questo Graphics all'intersezione della regione di ritaglio corrente e della struttura Rectangle specificata. |
| [intersectClip(Region region)](#intersectClip-com.aspose.imaging.Region-) | Aggiorna la regione di ritaglio di questo Graphics all'intersezione della regione di ritaglio corrente e della Region specificata. |
| [resetClip()](#resetClip--) | Reimposta il ritaglio. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | Moltiplica la trasformazione globale di questo Graphics per la Matrix specificata. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | Moltiplica la trasformazione globale di questo Graphics per la Matrix specificata nell'ordine specificato. |
| [translateTransform(float x, float y)](#translateTransform-float-float-) | Modifica l'origine del sistema di coordinate anteponendo la traduzione specificata alla matrice di trasformazione di questo Graphics. |
| [translateTransform(float x, float y, int order)](#translateTransform-float-float-int-) | Modifica l'origine del sistema di coordinate applicando la traduzione specificata alla matrice di trasformazione di questo Graphics nell'ordine specificato. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Applica la rotazione specificata alla matrice di trasformazione di questo Graphics. |
| [rotateTransform(float angle, PointF center, int order)](#rotateTransform-float-com.aspose.imaging.PointF-int-) | Applica la rotazione specificata alla matrice di trasformazione di questo Graphics nell'ordine specificato. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Applica l'operazione di scaling specificata alla matrice di trasformazione di questo Graphics anteponendola alla matrice di trasformazione dell'oggetto. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Applica l'operazione di scaling specificata alla matrice di trasformazione di questo Graphics nell'ordine specificato. |
| [getTransform()](#getTransform--) | Ottiene la trasformazione globale. |
| [setTransform(Matrix transform)](#setTransform-com.aspose.imaging.Matrix-) | Imposta la trasformazione. |

## Example: This example shows how to create a EMF image and draw some geometric shapes on it using EmfRecorderGraphics2D.

``` java
String dir = "c:\\temp\\";

// La dimensione dell'immagine in pixel
int deviceWidth = 600;
int deviceHeight = 400;

// La dimensione dell'immagine in millimetri
int deviceWidthMm = (int) (deviceWidth / 100f);
int deviceHeightMm = (int) (deviceHeight / 100f);

com.aspose.imaging.Rectangle frame = new com.aspose.imaging.Rectangle(0, 0, deviceWidth, deviceHeight);

// Crea un'immagine EMF.
com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
        new com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D(
                frame,
                new com.aspose.imaging.Size(deviceWidth, deviceHeight),
                new com.aspose.imaging.Size(deviceWidthMm, deviceHeightMm));

// Disegna un rettangolo nero lungo i bordi dell'immagine usando una penna nera larga 1 pixel.
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, deviceWidth, deviceHeight);

// Riempi un rettangolo con il colore white-smoke.
graphics.fillRectangle(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()),
        new com.aspose.imaging.Rectangle(10, 10, 580, 380));

// Disegna due linee diagonali usando una penna darkgreen larga 1 pixel.
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, deviceWidth, deviceHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, deviceHeight, deviceWidth, 0);

// Disegna un arco all'interno del rettangolo {0, 0, 200, 200} usando una penna blu larga 2 pixel.
graphics.drawArc(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2), new com.aspose.imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Riempi un arco
graphics.fillPie(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getLightSkyBlue()),
        new com.aspose.imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Disegna un bezier cubico usando una penna rossa larga 2 pixel.
graphics.drawCubicBezier(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(200, 133),
        new com.aspose.imaging.Point(400, 166),
        new com.aspose.imaging.Point(600, 400));

// Disegna un'immagine raster della dimensione specificata nella posizione specificata.
// L'immagine è scalata per adattarsi al rettangolo desiderato.
com.aspose.imaging.RasterImage imageToDraw = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    graphics.drawImage(imageToDraw,
            new com.aspose.imaging.Rectangle(400, 200, 100, 50),
            new com.aspose.imaging.Rectangle(0, 0, deviceWidth, deviceHeight),
            com.aspose.imaging.GraphicsUnit.Pixel);
} finally {
    imageToDraw.dispose();
}

// Disegna una stringa di testo
graphics.drawString("Hello World!",
        new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular),
        com.aspose.imaging.Color.getDarkRed(), 200, 300);

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
                new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(0, 100, 200, 200)),
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

// Per rasterizzare SVG è necessario specificare le opzioni di rasterizzazione.
com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
saveOptions.setVectorRasterizationOptions(rasterizationOptions);

// Ottieni l'immagine WMF finale che include tutti i comandi di disegno
com.aspose.imaging.fileformats.emf.EmfImage emfImage = graphics.endRecording();
try {
    emfImage.save(dir + "test.output.emf");
} finally {
    emfImage.dispose();
}
```

### MetafileRecorderGraphics2D() {#MetafileRecorderGraphics2D--}
```
public MetafileRecorderGraphics2D()
```


### getClip() {#getClip--}
```
public Region getClip()
```


Ottiene o imposta una Region che limita l'area di disegno di questo Graphics

**Returns:**
[Region](../../com.aspose.imaging/region) - The clip region.
### setClip(Region value) {#setClip-com.aspose.imaging.Region-}
```
public void setClip(Region value)
```


Ottiene o imposta una Region che limita l'area di disegno di questo Graphics

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Region](../../com.aspose.imaging/region) | La regione di ritaglio. |

### getClipBounds() {#getClipBounds--}
```
public RectangleF getClipBounds()
```


Ottiene i limiti di clip.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The clip bounds.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Ottiene il colore dello sfondo.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of the background.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Imposta il colore dello sfondo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Il colore dello sfondo. |

### clear() {#clear--}
```
public void clear()
```


Cancella lo stato dell'oggetto graphics

### drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle) {#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)
```


Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura Rectangle.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna che determina il colore, la larghezza e lo stile della figura. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | I confini dell'ellisse. |
| startAngle | float | Angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| arcAngle | float | Angolo in gradi misurato in senso orario dal parametro startAngle al punto finale dell'arco. |

### drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public void drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


Disegna il bezier cubico.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna che determina il colore, la larghezza e lo stile della figura. |
| pt1 | [Point](../../com.aspose.imaging/point) | Il punto di partenza della curva. |
| pt2 | [Point](../../com.aspose.imaging/point) | Il primo punto di controllo per la curva. |
| pt3 | [Point](../../com.aspose.imaging/point) | Il secondo punto di controllo per la curva. |
| pt4 | [Point](../../com.aspose.imaging/point) | Il punto finale della curva. |

### drawPolyCubicBezier(Pen pen, Point[] points) {#drawPolyCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolyCubicBezier(Pen pen, Point[] points)
```


Disegna il poly cubic bezier.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna che determina il colore, la larghezza e lo stile della figura. |
| points | [Point\[\]](../../com.aspose.imaging/point) | I punti. |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


Disegna l'ellisse.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna che determina il colore, la larghezza e lo stile della figura. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | I confini dell'ellisse. |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


Riempie l'ellisse.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pennello che determina le caratteristiche del riempimento. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | I confini dell'ellisse. |

### drawImage(RasterImage image, Point location) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-}
```
public void drawImage(RasterImage image, Point location)
```


Disegna l'Image specificata, usando la sua dimensione fisica originale, nella posizione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine da disegnare. |
| location | [Point](../../com.aspose.imaging/point) | La posizione dell'angolo superiore sinistro dell'immagine disegnata. |

### drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit) {#drawImage-byte---com.aspose.imaging.Rectangle-int-}
```
public final void drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit)
```


Disegna l'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageBytes | byte[] | I byte dell'immagine. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo di destinazione. |
| srcUnit | int | L'unità di origine. |

### drawImage(InputStream stream, Rectangle destRect, int srcUnit) {#drawImage-java.io.InputStream-com.aspose.imaging.Rectangle-int-}
```
public final void drawImage(InputStream stream, Rectangle destRect, int srcUnit)
```


Disegna l'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo di destinazione. |
| srcUnit | int | L'unità di origine. |

### drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-int-}
```
public void drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit)
```


Disegna la porzione specificata dell'Image specificata nella posizione specificata e con la dimensione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine da disegnare. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | Struttura Rectangle che specifica la posizione e le dimensioni dell'immagine disegnata. L'immagine è scalata per adattarsi al rettangolo. |
| srcRect | [Rectangle](../../com.aspose.imaging/rectangle) | Struttura Rectangle che specifica la porzione dell'oggetto immagine da disegnare. |
| srcUnit | int | Le unità di misura utilizzate dal parametro srcRect. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.imaging.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Disegna la linea.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna che determina il colore, la larghezza e lo stile della figura. |
| x1 | int | La coordinata x del primo punto. |
| y1 | int | La coordinata y del primo punto. |
| x2 | int | La coordinata x del secondo punto. |
| y2 | int | La coordinata y del secondo punto. |

### drawLine(Pen pen, Point pt1, Point pt2) {#drawLine-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public void drawLine(Pen pen, Point pt1, Point pt2)
```


Disegna la linea.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna che determina il colore, la larghezza e lo stile della figura. |
| pt1 | [Point](../../com.aspose.imaging/point) | Il primo punto. |
| pt2 | [Point](../../com.aspose.imaging/point) | Il secondo punto. |

### drawPolyline(Pen pen, Point[] points) {#drawPolyline-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolyline(Pen pen, Point[] points)
```


Disegna la polilinea.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna che determina il colore, la larghezza e lo stile della figura. |
| points | [Point\[\]](../../com.aspose.imaging/point) | I punti. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


Disegna il percorso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna che determina il colore, la larghezza e lo stile della figura. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Il percorso da disegnare. |

### fillPath(Pen pen, Brush brush, GraphicsPath path) {#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-}
```
public void fillPath(Pen pen, Brush brush, GraphicsPath path)
```


Riempie il percorso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna che determina il colore, la larghezza e lo stile della figura. |
| brush | [Brush](../../com.aspose.imaging/brush) | Pennello che determina le caratteristiche del riempimento. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Il percorso da riempire. |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Disegna la torta.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna che determina il colore, la larghezza e lo stile della figura. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | I confini dell'ellisse. |
| startAngle | float | Angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| sweepAngle | float | Angolo in gradi misurato in senso orario dal parametro startAngle al punto finale dell'arco. |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


Riempie la torta.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pennello che determina le caratteristiche del riempimento. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | I confini dell'ellisse. |
| startAngle | float | Angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| sweepAngle | float | Angolo in gradi misurato in senso orario dal parametro startAngle al punto finale dell'arco. |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


Disegna il poligono.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna che determina il colore, la larghezza e lo stile della figura. |
| points | [Point\[\]](../../com.aspose.imaging/point) | I punti. |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


Riempie il poligono.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pennello che determina le caratteristiche del riempimento. |
| points | [Point\[\]](../../com.aspose.imaging/point) | I punti. |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


Riempie il poligono.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pennello che determina le caratteristiche del riempimento. |
| points | [Point\[\]](../../com.aspose.imaging/point) | I punti. |
| fillMode | int | La modalità di riempimento. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Disegna il rettangolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna che determina il colore, la larghezza e lo stile della figura. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo da disegnare. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo da disegnare. |
| width | int | La larghezza del rettangolo da disegnare. |
| height | int | L'altezza del rettangolo da disegnare. |

### drawRectangle(Pen pen, Rectangle rectangle) {#drawRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rectangle)
```


Disegna il rettangolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna che determina il colore, la larghezza e lo stile della figura. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo da disegnare. |

### fillRectangle(Brush brush, Rectangle rectangle) {#fillRectangle-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rectangle)
```


Riempie il rettangolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pennello che determina le caratteristiche del riempimento. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo da riempire. |

### drawString(String string, Font font, Color color, int x, int y) {#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-}
```
public void drawString(String string, Font font, Color color, int x, int y)
```


Disegna la stringa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stringa | java.lang.String | La stringa. |
| font | [Font](../../com.aspose.imaging/font) | Font che definisce il formato del testo della stringa. |
| color | [Color](../../com.aspose.imaging/color) | Il colore del testo. |
| x | int | La coordinata x dell'angolo in alto a sinistra del testo disegnato. |
| y | int | La coordinata y dell'angolo in alto a sinistra del testo disegnato. |


**Example: This example shows how to load a EMF image from a file and draw a text string over it.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
            com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D.fromEmfImage(emfImage);

    // Prima, ottieni le dimensioni dell'immagine
    int width = emfImage.getWidth();
    int height = emfImage.getHeight();

    // Secondo, calcola una trasformazione per posizionare una stringa di testo lungo la diagonale principale dell'immagine -
    // dall'angolo in alto a sinistra all'angolo in basso a destra.
    float emFontSize = 96f;
    float d = (float) java.lang.Math.sqrt(width * width + height * height);
    float scaleFactor = d / (emFontSize * 5f);

    float tan = ((float) height) / width;
    double radians = java.lang.Math.atan(tan);
    double degrees = (180 * radians) / java.lang.Math.PI;

    com.aspose.imaging.Matrix transform = new com.aspose.imaging.Matrix();
    transform.rotate((float) degrees);
    transform.scale(scaleFactor, scaleFactor);

    // Quindi, imposta la trasformazione.
    graphics.setTransform(transform);

    // Infine, inserisci una filigrana (stringa di testo di colore rosa) lungo la diagonale principale.
    graphics.drawString("WATERMARK", new com.aspose.imaging.Font(
                    "Courier New", emFontSize),
            com.aspose.imaging.Color.getLightPink(), 0, 0/*, (float)degrees*/);

    // Salva l'immagine con filigrana in un altro file EMF.
    com.aspose.imaging.fileformats.emf.EmfImage scaledEmfImage = graphics.endRecording();
    try {
        scaledEmfImage.save(dir + "test.scaled.emf");
    } finally {
        scaledEmfImage.dispose();
    }
} finally {
    emfImage.dispose();
}
```

### drawString(String string, Font font, Color color, int x, int y, float angle) {#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-float-}
```
public void drawString(String string, Font font, Color color, int x, int y, float angle)
```


Disegna la stringa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stringa | java.lang.String | La stringa. |
| font | [Font](../../com.aspose.imaging/font) | Font che definisce il formato del testo della stringa. |
| color | [Color](../../com.aspose.imaging/color) | Il colore del testo. |
| x | int | La coordinata x dell'angolo in alto a sinistra del testo disegnato. |
| y | int | La coordinata y dell'angolo in alto a sinistra del testo disegnato. |
| angle | float | L'angolo in gradi, tra il vettore di escapement e l'asse x del dispositivo. Il vettore di escapement è parallelo alla linea di base di una riga di testo. |

### excludeClip(Rectangle rect) {#excludeClip-com.aspose.imaging.Rectangle-}
```
public void excludeClip(Rectangle rect)
```


Aggiorna la regione di ritaglio di questo Graphics per escludere l'area specificata da una struttura Rectangle.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Struttura rettangolo che specifica il rettangolo da escludere dalla regione di clip. |

### excludeClip(Region region) {#excludeClip-com.aspose.imaging.Region-}
```
public void excludeClip(Region region)
```


Aggiorna la regione di ritaglio di questo Graphics per escludere l'area specificata da una Region.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Regione che specifica la regione da escludere dalla regione di clip. |

### intersectClip(RectangleF rect) {#intersectClip-com.aspose.imaging.RectangleF-}
```
public void intersectClip(RectangleF rect)
```


Aggiorna la regione di ritaglio di questo Graphics all'intersezione della regione di ritaglio corrente e della struttura Rectangle specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Struttura rettangolo da intersecare con la regione di clip corrente. |

### intersectClip(Region region) {#intersectClip-com.aspose.imaging.Region-}
```
public void intersectClip(Region region)
```


Aggiorna la regione di ritaglio di questo Graphics all'intersezione della regione di ritaglio corrente e della Region specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Regione da intersecare con la regione corrente. |

### resetClip() {#resetClip--}
```
public void resetClip()
```


Reimposta il ritaglio.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Moltiplica la trasformazione globale di questo Graphics per la Matrix specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matrice che moltiplica la trasformazione del mondo. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Moltiplica la trasformazione globale di questo Graphics per la Matrix specificata nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matrice che moltiplica la trasformazione del mondo. |
| order | int | L'ordine della moltiplicazione. |

### translateTransform(float x, float y) {#translateTransform-float-float-}
```
public void translateTransform(float x, float y)
```


Modifica l'origine del sistema di coordinate anteponendo la traduzione specificata alla matrice di trasformazione di questo Graphics.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x della traslazione. |
| y | float | La coordinata y della traslazione. |

### translateTransform(float x, float y, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float x, float y, int order)
```


Modifica l'origine del sistema di coordinate applicando la traduzione specificata alla matrice di trasformazione di questo Graphics nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x della traslazione. |
| y | float | La coordinata y della traslazione. |
| order | int | Specifica se la traslazione è anteposta o aggiunta alla matrice di trasformazione. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Applica la rotazione specificata alla matrice di trasformazione di questo Graphics.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | Angolo di rotazione in gradi. |

### rotateTransform(float angle, PointF center, int order) {#rotateTransform-float-com.aspose.imaging.PointF-int-}
```
public void rotateTransform(float angle, PointF center, int order)
```


Applica la rotazione specificata alla matrice di trasformazione di questo Graphics nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | Angolo di rotazione in gradi. |
| center | [PointF](../../com.aspose.imaging/pointf) | Il centro di rotazione. |
| order | int | Specifica se la rotazione è aggiunta o anteposta alla trasformazione della matrice. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Applica l'operazione di scaling specificata alla matrice di trasformazione di questo Graphics anteponendola alla matrice di trasformazione dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sx | float | Fattore di scala nella direzione x. |
| sy | float | Fattore di scala nella direzione y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Applica l'operazione di scaling specificata alla matrice di trasformazione di questo Graphics nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sx | float | Fattore di scala nella direzione x. |
| sy | float | Fattore di scala nella direzione y. |
| order | int | Specifica se l'operazione di scalatura è anteposta o aggiunta alla matrice di trasformazione. |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Ottiene la trasformazione globale.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - The transform matrix.
### setTransform(Matrix transform) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix transform)
```


Imposta la trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | La nuova matrice di trasformazione. |


**Example: This example shows how to load a EMF image from a file and draw a text string over it.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
            com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D.fromEmfImage(emfImage);

    // Prima, ottieni le dimensioni dell'immagine
    int width = emfImage.getWidth();
    int height = emfImage.getHeight();

    // Secondo, calcola una trasformazione per posizionare una stringa di testo lungo la diagonale principale dell'immagine -
    // dall'angolo in alto a sinistra all'angolo in basso a destra.
    float emFontSize = 96f;
    float d = (float) java.lang.Math.sqrt(width * width + height * height);
    float scaleFactor = d / (emFontSize * 5f);

    float tan = ((float) height) / width;
    double radians = java.lang.Math.atan(tan);
    double degrees = (180 * radians) / java.lang.Math.PI;

    com.aspose.imaging.Matrix transform = new com.aspose.imaging.Matrix();
    transform.rotate((float) degrees);
    transform.scale(scaleFactor, scaleFactor);

    // Quindi, imposta la trasformazione.
    graphics.setTransform(transform);

    // Infine, inserisci una filigrana (stringa di testo di colore rosa) lungo la diagonale principale.
    graphics.drawString("WATERMARK", new com.aspose.imaging.Font(
                    "Courier New", emFontSize),
            com.aspose.imaging.Color.getLightPink(), 0, 0/*, (float)degrees*/);

    // Salva l'immagine con filigrana in un altro file EMF.
    com.aspose.imaging.fileformats.emf.EmfImage scaledEmfImage = graphics.endRecording();
    try {
        scaledEmfImage.save(dir + "test.scaled.emf");
    } finally {
        scaledEmfImage.dispose();
    }
} finally {
    emfImage.dispose();
}
```

