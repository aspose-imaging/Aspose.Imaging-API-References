---
title: "SvgGraphics2D"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Fournit des commandes de dessin pour composer une image Svg."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.svg.graphics/svggraphics2d/
---
**Inheritance:**
java.lang.Object
```
public class SvgGraphics2D
```

Fournit des commandes de dessin pour composer une image Svg.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SvgGraphics2D(int width, int height, int dpi)](#SvgGraphics2D-int-int-int-) | Initialise une nouvelle instance de la classe [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d). |
| [SvgGraphics2D(SvgImage image)](#SvgGraphics2D-com.aspose.imaging.fileformats.svg.SvgImage-) | Initialise une nouvelle instance de la classe [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [drawImage(RasterImage image, Point origin)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-) | Dessine l'image spécifiée à l'emplacement spécifié. |
| [drawImage(RasterImage image, Point origin, Size size)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Dessine l'image spécifiée de la taille spécifiée à l'emplacement spécifié. |
| [drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image)](#drawImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RasterImage-) | Dessine la portion spécifiée de l'image spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)](#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Dessine un arc représentant une partie d'une ellipse spécifiée par une structure Rectangle. |
| [fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle)](#fillArc-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-) | Remplit un arc représentant une portion d'une ellipse spécifiée par une structure Rectangle. |
| [drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Dessine le Bézier cubique. |
| [drawString(Font font, String text, Point origin, Color textColor)](#drawString-com.aspose.imaging.Font-java.lang.String-com.aspose.imaging.Point-com.aspose.imaging.Color-) | Dessine la chaîne de texte. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.imaging.Pen-int-int-int-int-) | Dessine la ligne. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-) | Dessine le chemin. |
| [fillPath(Pen pen, Brush brush, GraphicsPath path)](#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-) | Remplit le chemin. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-) | Dessine le rectangle. |
| [fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Brush-int-int-int-int-) | Remplit le rectangle. |
| [endRecording()](#endRecording--) | Obtient l'image Svg finale qui inclut toutes les commandes de dessin effectuées via l'objet [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d). |

## Example: This example shows how to create an SVG image of the specified size and draw different shapes on it using SvgGraphics2D.

``` java
String dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;
int dpi = 96;

com.aspose.imaging.fileformats.svg.graphics.SvgGraphics2D graphics = new com.aspose.imaging.fileformats.svg.graphics.SvgGraphics2D(imageWidth, imageHeight, dpi);

// Dessinez un rectangle noir le long des bordures de l'image en utilisant un stylo noir d'une largeur de 1 pixel.
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, imageWidth, imageHeight);

// Remplissez un rectangle avec la couleur white-smoke.
graphics.fillRectangle(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getWhiteSmoke(), 1),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()), 10, 10, 580, 380);

// Dessinez deux lignes diagonales en utilisant un stylo darkgreen d'une largeur de 1 pixel.
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, imageWidth, imageHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, imageHeight, imageWidth, 0);

// Dessinez un arc à l'intérieur du rectangle {0, 0, 200, 200} en utilisant un stylo bleu d'une largeur de 2 pixels.
graphics.drawArc(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
        new com.aspose.imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Remplissez un arc
graphics.fillArc(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getLightCoral(), 10),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getLightSkyBlue()),
        new com.aspose.imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Dessinez un Bézier cubique en utilisant un stylo rouge d'une largeur de 2 pixels.
graphics.drawCubicBezier(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
        new com.aspose.imaging.PointF(0, 0),
        new com.aspose.imaging.PointF(200, 133),
        new com.aspose.imaging.PointF(400, 166),
        new com.aspose.imaging.PointF(600, 400));

// Dessinez une image raster de la taille spécifiée à l'emplacement spécifié.
// L'image est mise à l'échelle pour s'adapter au rectangle souhaité.
com.aspose.imaging.RasterImage imageToDraw = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    graphics.drawImage(imageToDraw, new com.aspose.imaging.Point(400, 200), new com.aspose.imaging.Size(100, 50));
} finally {
    imageToDraw.dispose();
}

// Dessinez une chaîne de texte
graphics.drawString(
        new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular),
        "Hello World!",
        new com.aspose.imaging.Point(200, 300),
        com.aspose.imaging.Color.getDarkRed());

// Créez un chemin à remplir
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

// Remplissez le chemin en utilisant un pinceau jaune et un stylo vert pour tracer le contour
graphics.fillPath(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getYellow()), pathToFill);

// Créez un chemin à dessiner
com.aspose.imaging.GraphicsPath pathToDraw = new com.aspose.imaging.GraphicsPath();
com.aspose.imaging.Figure figureToDraw = new com.aspose.imaging.Figure();
pathToDraw.addFigure(figureToDraw);

figureToDraw.addShapes(new com.aspose.imaging.Shape[]
        {
                new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(200, 200, 200, 200), 0, 360),
        });

// Dessinez le chemin en utilisant un stylo orange d'une largeur de 5 pixels.
graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 5), pathToDraw);

// Obtenez l'image SVG finale qui inclut toutes les commandes de dessin
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


Initialise une nouvelle instance de la classe [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur de l'image Svg de sortie. |
| height | int | La largeur de l'image Svg de sortie. |
| dpi | int | La résolution de l'appareil, p. ex. 96 points par pouce. |

### SvgGraphics2D(SvgImage image) {#SvgGraphics2D-com.aspose.imaging.fileformats.svg.SvgImage-}
```
public SvgGraphics2D(SvgImage image)
```


Initialise une nouvelle instance de la classe [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) | L'image sur laquelle effectuer les opérations de dessin. |

### drawImage(RasterImage image, Point origin) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-}
```
public final void drawImage(RasterImage image, Point origin)
```


Dessine l'image spécifiée à l'emplacement spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image dessinée. |
| origin | [Point](../../com.aspose.imaging/point) | L'emplacement de l'image dessinée. |

### drawImage(RasterImage image, Point origin, Size size) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public final void drawImage(RasterImage image, Point origin, Size size)
```


Dessine l'image spécifiée de la taille spécifiée à l'emplacement spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image dessinée. |
| origin | [Point](../../com.aspose.imaging/point) | L'emplacement de l'image dessinée. |
| size | [Size](../../com.aspose.imaging/size) | La taille souhaitée de l'image dessinée. |

### drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image) {#drawImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RasterImage-}
```
public final void drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image)
```


Dessine la portion spécifiée de l'image spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| srcRect | [Rectangle](../../com.aspose.imaging/rectangle) | La portion de l'objet image à dessiner. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | L'emplacement et la taille de l'image dessinée. L'image est mise à l'échelle pour s'adapter au rectangle. |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image à dessiner. |

### drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle) {#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public final void drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)
```


Dessine un arc représentant une partie d'une ellipse spécifiée par une structure Rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Le crayon pour dessiner le contour de la figure. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Les limites de l'ellipse. |
| startAngle | float | L'angle en degrés mesuré dans le sens des aiguilles d'une montre depuis l'axe x jusqu'au point de départ de l'arc. |
| arcAngle | float | L'angle en degrés mesuré dans le sens des aiguilles d'une montre depuis le paramètre startAngle jusqu'au point final de l'arc. |

### fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle) {#fillArc-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-}
```
public final void fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle)
```


Remplit un arc représentant une portion d'une ellipse spécifiée par une structure Rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Le crayon pour dessiner le contour de la figure. |
| brush | [Brush](../../com.aspose.imaging/brush) | Le pinceau pour remplir l'intérieur de la figure. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Les limites de l'ellipse. |
| startAngle | float | L'angle en degrés mesuré dans le sens des aiguilles d'une montre depuis l'axe x jusqu'au point de départ de l'arc. |
| arcAngle | float | L'angle en degrés mesuré dans le sens des aiguilles d'une montre depuis le paramètre startAngle jusqu'au point final de l'arc. |

### drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public final void drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


Dessine le Bézier cubique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Le crayon qui détermine la couleur, la largeur et le style de la figure. |
| pt1 | [PointF](../../com.aspose.imaging/pointf) | Le point de départ de la courbe. |
| pt2 | [PointF](../../com.aspose.imaging/pointf) | Le premier point de contrôle de la courbe. |
| pt3 | [PointF](../../com.aspose.imaging/pointf) | Le deuxième point de contrôle de la courbe. |
| pt4 | [PointF](../../com.aspose.imaging/pointf) | Le point final de la courbe. |

### drawString(Font font, String text, Point origin, Color textColor) {#drawString-com.aspose.imaging.Font-java.lang.String-com.aspose.imaging.Point-com.aspose.imaging.Color-}
```
public final void drawString(Font font, String text, Point origin, Color textColor)
```


Dessine la chaîne de texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| font | [Font](../../com.aspose.imaging/font) | La police utilisée pour rendre le texte. |
| text | java.lang.String | La chaîne de texte Unicode. |
| origin | [Point](../../com.aspose.imaging/point) | Le coin supérieur gauche du bloc de texte. |
| textColor | [Color](../../com.aspose.imaging/color) | La couleur du texte. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.imaging.Pen-int-int-int-int-}
```
public final void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Dessine la ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Le crayon qui détermine la couleur, la largeur et le style de la figure. |
| x1 | int | La coordonnée x du premier point. |
| y1 | int | La coordonnée y du premier point. |
| x2 | int | La coordonnée x du deuxième point. |
| y2 | int | La coordonnée y du deuxième point. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-}
```
public final void drawPath(Pen pen, GraphicsPath path)
```


Dessine le chemin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Le crayon pour dessiner le contour de la figure. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Le chemin à tracer. |

### fillPath(Pen pen, Brush brush, GraphicsPath path) {#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-}
```
public final void fillPath(Pen pen, Brush brush, GraphicsPath path)
```


Remplit le chemin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Le crayon pour dessiner le contour de la figure. |
| brush | [Brush](../../com.aspose.imaging/brush) | Le pinceau pour remplir l'intérieur de la figure. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Le chemin à tracer. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-}
```
public final void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Dessine le rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Le crayon pour dessiner le contour de la figure. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à tracer. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à tracer. |
| width | int | La largeur du rectangle à tracer. |
| height | int | La hauteur du rectangle à tracer. |

### fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Brush-int-int-int-int-}
```
public final void fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height)
```


Remplit le rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Le crayon pour dessiner le contour de la figure. |
| brush | [Brush](../../com.aspose.imaging/brush) | Le pinceau pour remplir l'intérieur de la figure. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à tracer. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à tracer. |
| width | int | La largeur du rectangle à tracer. |
| height | int | La hauteur du rectangle à tracer. |

### endRecording() {#endRecording--}
```
public final SvgImage endRecording()
```


Obtient l'image Svg finale qui inclut toutes les commandes de dessin effectuées via l'objet [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d).

**Returns:**
[SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) - The final Svg image.
