---
title: "MetafileRecorderGraphics2D"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les graphiques d'enregistrement des métafichiers"
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/
---
**Inheritance:**
java.lang.Object
```
public abstract class MetafileRecorderGraphics2D
```

Les graphiques d'enregistrement des métafichiers
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MetafileRecorderGraphics2D()](#MetafileRecorderGraphics2D--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getClip()](#getClip--) | Obtient ou définit une Région qui limite la zone de dessin de cet objet Graphics |
| [setClip(Region value)](#setClip-com.aspose.imaging.Region-) | Obtient ou définit une Région qui limite la zone de dessin de cet objet Graphics |
| [getClipBounds()](#getClipBounds--) | Obtient les limites du clip. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtient la couleur de l'arrière-plan. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Définit la couleur de l'arrière-plan. |
| [clear()](#clear--) | Efface l'état de l'objet graphique |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)](#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Dessine un arc représentant une partie d'une ellipse spécifiée par une structure Rectangle. |
| [drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Dessine le Bézier cubique. |
| [drawPolyCubicBezier(Pen pen, Point[] points)](#drawPolyCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Dessine le Bézier cubique poly. |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-) | Dessine l'ellipse. |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-) | Remplit l'ellipse. |
| [drawImage(RasterImage image, Point location)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-) | Dessine l'Image spécifiée, en utilisant sa taille physique d'origine, à l'emplacement spécifié. |
| [drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit)](#drawImage-byte---com.aspose.imaging.Rectangle-int-) | Dessine l'image. |
| [drawImage(InputStream stream, Rectangle destRect, int srcUnit)](#drawImage-java.io.InputStream-com.aspose.imaging.Rectangle-int-) | Dessine l'image. |
| [drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-int-) | Dessine la partie spécifiée de l'Image spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.imaging.Pen-int-int-int-int-) | Dessine la ligne. |
| [drawLine(Pen pen, Point pt1, Point pt2)](#drawLine-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Dessine la ligne. |
| [drawPolyline(Pen pen, Point[] points)](#drawPolyline-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Dessine la polyligne. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-) | Dessine le chemin. |
| [fillPath(Pen pen, Brush brush, GraphicsPath path)](#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-) | Remplit le chemin. |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Dessine le secteur. |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-) | Remplit le secteur. |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Dessine le polygone. |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---) | Remplit le polygone. |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-) | Remplit le polygone. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-) | Dessine le rectangle. |
| [drawRectangle(Pen pen, Rectangle rectangle)](#drawRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-) | Dessine le rectangle. |
| [fillRectangle(Brush brush, Rectangle rectangle)](#fillRectangle-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-) | Remplit le rectangle. |
| [drawString(String string, Font font, Color color, int x, int y)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-) | Dessine la chaîne. |
| [drawString(String string, Font font, Color color, int x, int y, float angle)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-float-) | Dessine la chaîne. |
| [excludeClip(Rectangle rect)](#excludeClip-com.aspose.imaging.Rectangle-) | Met à jour la région de découpage de cet objet Graphics pour exclure la zone spécifiée par une structure Rectangle. |
| [excludeClip(Region region)](#excludeClip-com.aspose.imaging.Region-) | Met à jour la région de découpage de cet objet Graphics pour exclure la zone spécifiée par une Région. |
| [intersectClip(RectangleF rect)](#intersectClip-com.aspose.imaging.RectangleF-) | Met à jour la région de découpage de cet objet Graphics à l'intersection de la région de découpage actuelle et de la structure Rectangle spécifiée. |
| [intersectClip(Region region)](#intersectClip-com.aspose.imaging.Region-) | Met à jour la région de découpage de cet objet Graphics à l'intersection de la région de découpage actuelle et de la Région spécifiée. |
| [resetClip()](#resetClip--) | Réinitialise le découpage. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | Multiplie la transformation du monde de cet objet Graphics par la matrice spécifiée. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | Multiplie la transformation du monde de cet objet Graphics par la matrice spécifiée dans l'ordre indiqué. |
| [translateTransform(float x, float y)](#translateTransform-float-float-) | Modifie l'origine du système de coordonnées en préfixant la translation spécifiée à la matrice de transformation de cet objet Graphics. |
| [translateTransform(float x, float y, int order)](#translateTransform-float-float-int-) | Modifie l'origine du système de coordonnées en appliquant la translation spécifiée à la matrice de transformation de cet objet Graphics dans l'ordre indiqué. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Applique la rotation spécifiée à la matrice de transformation de cet objet Graphics. |
| [rotateTransform(float angle, PointF center, int order)](#rotateTransform-float-com.aspose.imaging.PointF-int-) | Applique la rotation spécifiée à la matrice de transformation de cet objet Graphics dans l'ordre indiqué. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Applique l'opération de mise à l'échelle spécifiée à la matrice de transformation de cet objet Graphics en la préfixant à la matrice de transformation de l'objet. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Applique l'opération de mise à l'échelle spécifiée à la matrice de transformation de cet objet Graphics dans l'ordre indiqué. |
| [getTransform()](#getTransform--) | Obtient la transformation du monde. |
| [setTransform(Matrix transform)](#setTransform-com.aspose.imaging.Matrix-) | Définit la transformation. |

## Example: This example shows how to create a EMF image and draw some geometric shapes on it using EmfRecorderGraphics2D.

``` java
String dir = "c:\\temp\\";

// La taille de l'image en pixels
int deviceWidth = 600;
int deviceHeight = 400;

// La taille de l'image en millimètres
int deviceWidthMm = (int) (deviceWidth / 100f);
int deviceHeightMm = (int) (deviceHeight / 100f);

com.aspose.imaging.Rectangle frame = new com.aspose.imaging.Rectangle(0, 0, deviceWidth, deviceHeight);

// Crée une image EMF.
com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
        new com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D(
                frame,
                new com.aspose.imaging.Size(deviceWidth, deviceHeight),
                new com.aspose.imaging.Size(deviceWidthMm, deviceHeightMm));

// Dessinez un rectangle noir le long des bordures de l'image en utilisant un stylo noir d'une largeur de 1 pixel.
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, deviceWidth, deviceHeight);

// Remplissez un rectangle avec la couleur white-smoke.
graphics.fillRectangle(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()),
        new com.aspose.imaging.Rectangle(10, 10, 580, 380));

// Dessinez deux lignes diagonales en utilisant un stylo darkgreen d'une largeur de 1 pixel.
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, deviceWidth, deviceHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, deviceHeight, deviceWidth, 0);

// Dessinez un arc à l'intérieur du rectangle {0, 0, 200, 200} en utilisant un stylo bleu d'une largeur de 2 pixels.
graphics.drawArc(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2), new com.aspose.imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Remplissez un arc
graphics.fillPie(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getLightSkyBlue()),
        new com.aspose.imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Dessinez un Bézier cubique en utilisant un stylo rouge d'une largeur de 2 pixels.
graphics.drawCubicBezier(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(200, 133),
        new com.aspose.imaging.Point(400, 166),
        new com.aspose.imaging.Point(600, 400));

// Dessinez une image raster de la taille spécifiée à l'emplacement spécifié.
// L'image est mise à l'échelle pour s'adapter au rectangle souhaité.
com.aspose.imaging.RasterImage imageToDraw = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    graphics.drawImage(imageToDraw,
            new com.aspose.imaging.Rectangle(400, 200, 100, 50),
            new com.aspose.imaging.Rectangle(0, 0, deviceWidth, deviceHeight),
            com.aspose.imaging.GraphicsUnit.Pixel);
} finally {
    imageToDraw.dispose();
}

// Dessinez une chaîne de texte
graphics.drawString("Hello World!",
        new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular),
        com.aspose.imaging.Color.getDarkRed(), 200, 300);

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
                new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(0, 100, 200, 200)),
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

// Pour rasteriser le SVG, nous devons spécifier les options de rasterisation.
com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
saveOptions.setVectorRasterizationOptions(rasterizationOptions);

// Obtenez l'image WMF finale qui inclut toutes les commandes de dessin
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


Obtient ou définit une Région qui limite la zone de dessin de cet objet Graphics

**Returns:**
[Region](../../com.aspose.imaging/region) - The clip region.
### setClip(Region value) {#setClip-com.aspose.imaging.Region-}
```
public void setClip(Region value)
```


Obtient ou définit une Région qui limite la zone de dessin de cet objet Graphics

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Region](../../com.aspose.imaging/region) | La région de découpage. |

### getClipBounds() {#getClipBounds--}
```
public RectangleF getClipBounds()
```


Obtient les limites du clip.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The clip bounds.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtient la couleur de l'arrière-plan.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of the background.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Définit la couleur de l'arrière-plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | La couleur de l'arrière-plan. |

### clear() {#clear--}
```
public void clear()
```


Efface l'état de l'objet graphique

### drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle) {#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)
```


Dessine un arc représentant une partie d'une ellipse spécifiée par une structure Rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Les limites de l'ellipse. |
| startAngle | float | Angle en degrés mesuré dans le sens horaire depuis l'axe des x jusqu'au point de départ de l'arc. |
| arcAngle | float | Angle en degrés mesuré dans le sens des aiguilles d'une montre depuis le paramètre startAngle jusqu'au point final de l'arc. |

### drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public void drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


Dessine le Bézier cubique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| pt1 | [Point](../../com.aspose.imaging/point) | Le point de départ de la courbe. |
| pt2 | [Point](../../com.aspose.imaging/point) | Le premier point de contrôle de la courbe. |
| pt3 | [Point](../../com.aspose.imaging/point) | Le deuxième point de contrôle de la courbe. |
| pt4 | [Point](../../com.aspose.imaging/point) | Le point final de la courbe. |

### drawPolyCubicBezier(Pen pen, Point[] points) {#drawPolyCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolyCubicBezier(Pen pen, Point[] points)
```


Dessine le Bézier cubique poly.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Les points. |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


Dessine l'ellipse.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Les limites de l'ellipse. |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


Remplit l'ellipse.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pinceau qui détermine les caractéristiques du remplissage. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Les limites de l'ellipse. |

### drawImage(RasterImage image, Point location) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-}
```
public void drawImage(RasterImage image, Point location)
```


Dessine l'Image spécifiée, en utilisant sa taille physique d'origine, à l'emplacement spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image à dessiner. |
| location | [Point](../../com.aspose.imaging/point) | L'emplacement du coin supérieur gauche de l'image dessinée. |

### drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit) {#drawImage-byte---com.aspose.imaging.Rectangle-int-}
```
public final void drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit)
```


Dessine l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageBytes | byte[] | Les octets de l'image. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle de destination. |
| srcUnit | int | L'unité source. |

### drawImage(InputStream stream, Rectangle destRect, int srcUnit) {#drawImage-java.io.InputStream-com.aspose.imaging.Rectangle-int-}
```
public final void drawImage(InputStream stream, Rectangle destRect, int srcUnit)
```


Dessine l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle de destination. |
| srcUnit | int | L'unité source. |

### drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-int-}
```
public void drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit)
```


Dessine la partie spécifiée de l'Image spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image à dessiner. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | Structure Rectangle qui spécifie l'emplacement et la taille de l'image dessinée. L'image est redimensionnée pour s'adapter au rectangle. |
| srcRect | [Rectangle](../../com.aspose.imaging/rectangle) | Structure Rectangle qui spécifie la portion de l'objet image à dessiner. |
| srcUnit | int | Les unités de mesure utilisées par le paramètre srcRect. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.imaging.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Dessine la ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| x1 | int | La coordonnée x du premier point. |
| y1 | int | La coordonnée y du premier point. |
| x2 | int | La coordonnée x du deuxième point. |
| y2 | int | La coordonnée y du deuxième point. |

### drawLine(Pen pen, Point pt1, Point pt2) {#drawLine-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public void drawLine(Pen pen, Point pt1, Point pt2)
```


Dessine la ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| pt1 | [Point](../../com.aspose.imaging/point) | Le premier point. |
| pt2 | [Point](../../com.aspose.imaging/point) | Le deuxième point. |

### drawPolyline(Pen pen, Point[] points) {#drawPolyline-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolyline(Pen pen, Point[] points)
```


Dessine la polyligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Les points. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


Dessine le chemin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Le chemin à tracer. |

### fillPath(Pen pen, Brush brush, GraphicsPath path) {#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-}
```
public void fillPath(Pen pen, Brush brush, GraphicsPath path)
```


Remplit le chemin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| brush | [Brush](../../com.aspose.imaging/brush) | Pinceau qui détermine les caractéristiques du remplissage. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Le chemin à remplir. |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Dessine le secteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Les limites de l'ellipse. |
| startAngle | float | Angle en degrés mesuré dans le sens horaire depuis l'axe des x jusqu'au point de départ de l'arc. |
| sweepAngle | float | Angle en degrés mesuré dans le sens des aiguilles d'une montre depuis le paramètre startAngle jusqu'au point final de l'arc. |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


Remplit le secteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pinceau qui détermine les caractéristiques du remplissage. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Les limites de l'ellipse. |
| startAngle | float | Angle en degrés mesuré dans le sens horaire depuis l'axe des x jusqu'au point de départ de l'arc. |
| sweepAngle | float | Angle en degrés mesuré dans le sens des aiguilles d'une montre depuis le paramètre startAngle jusqu'au point final de l'arc. |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


Dessine le polygone.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Les points. |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


Remplit le polygone.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pinceau qui détermine les caractéristiques du remplissage. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Les points. |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


Remplit le polygone.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pinceau qui détermine les caractéristiques du remplissage. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Les points. |
| fillMode | int | Le mode de remplissage. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Dessine le rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à tracer. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à tracer. |
| width | int | La largeur du rectangle à tracer. |
| height | int | La hauteur du rectangle à tracer. |

### drawRectangle(Pen pen, Rectangle rectangle) {#drawRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rectangle)
```


Dessine le rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle à tracer. |

### fillRectangle(Brush brush, Rectangle rectangle) {#fillRectangle-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rectangle)
```


Remplit le rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pinceau qui détermine les caractéristiques du remplissage. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle à remplir. |

### drawString(String string, Font font, Color color, int x, int y) {#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-}
```
public void drawString(String string, Font font, Color color, int x, int y)
```


Dessine la chaîne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chaîne | java.lang.String | La chaîne. |
| font | [Font](../../com.aspose.imaging/font) | Police qui définit le format du texte de la chaîne. |
| color | [Color](../../com.aspose.imaging/color) | La couleur du texte. |
| x | int | La coordonnée x du coin supérieur gauche du texte dessiné. |
| y | int | La coordonnée y du coin supérieur gauche du texte dessiné. |


**Example: This example shows how to load a EMF image from a file and draw a text string over it.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
            com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D.fromEmfImage(emfImage);

    // Tout d'abord, obtenez la taille de l'image
    int width = emfImage.getWidth();
    int height = emfImage.getHeight();

    // Deuxièmement, calculez une transformation pour placer une chaîne de texte le long de la diagonale principale de l'image -
    // du coin supérieur gauche au coin inférieur droit.
    float emFontSize = 96f;
    float d = (float) java.lang.Math.sqrt(width * width + height * height);
    float scaleFactor = d / (emFontSize * 5f);

    float tan = ((float) height) / width;
    double radians = java.lang.Math.atan(tan);
    double degrees = (180 * radians) / java.lang.Math.PI;

    com.aspose.imaging.Matrix transform = new com.aspose.imaging.Matrix();
    transform.rotate((float) degrees);
    transform.scale(scaleFactor, scaleFactor);

    // Ensuite, définissez la transformation.
    graphics.setTransform(transform);

    // Enfin, placez un filigrane (chaîne de texte de couleur rose) le long de la diagonale principale.
    graphics.drawString("WATERMARK", new com.aspose.imaging.Font(
                    "Courier New", emFontSize),
            com.aspose.imaging.Color.getLightPink(), 0, 0/*, (float)degrees*/);

    // Enregistrez l'image avec le filigrane dans un autre fichier EMF.
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


Dessine la chaîne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chaîne | java.lang.String | La chaîne. |
| font | [Font](../../com.aspose.imaging/font) | Police qui définit le format du texte de la chaîne. |
| color | [Color](../../com.aspose.imaging/color) | La couleur du texte. |
| x | int | La coordonnée x du coin supérieur gauche du texte dessiné. |
| y | int | La coordonnée y du coin supérieur gauche du texte dessiné. |
| angle | float | L'angle en degrés, entre le vecteur d'échappement et l'axe x de l'appareil. Le vecteur d'échappement est parallèle à la ligne de base d'une rangée de texte. |

### excludeClip(Rectangle rect) {#excludeClip-com.aspose.imaging.Rectangle-}
```
public void excludeClip(Rectangle rect)
```


Met à jour la région de découpage de cet objet Graphics pour exclure la zone spécifiée par une structure Rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Structure de rectangle qui spécifie le rectangle à exclure de la région de découpe. |

### excludeClip(Region region) {#excludeClip-com.aspose.imaging.Region-}
```
public void excludeClip(Region region)
```


Met à jour la région de découpage de cet objet Graphics pour exclure la zone spécifiée par une Région.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Région qui spécifie la région à exclure de la région de découpe. |

### intersectClip(RectangleF rect) {#intersectClip-com.aspose.imaging.RectangleF-}
```
public void intersectClip(RectangleF rect)
```


Met à jour la région de découpage de cet objet Graphics à l'intersection de la région de découpage actuelle et de la structure Rectangle spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Structure de rectangle à intersecter avec la région de découpe actuelle. |

### intersectClip(Region region) {#intersectClip-com.aspose.imaging.Region-}
```
public void intersectClip(Region region)
```


Met à jour la région de découpage de cet objet Graphics à l'intersection de la région de découpage actuelle et de la Région spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Région à intersecter avec la région actuelle. |

### resetClip() {#resetClip--}
```
public void resetClip()
```


Réinitialise le découpage.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplie la transformation du monde de cet objet Graphics par la matrice spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matrice qui multiplie la transformation du monde. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplie la transformation du monde de cet objet Graphics par la matrice spécifiée dans l'ordre indiqué.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matrice qui multiplie la transformation du monde. |
| ordre | int | L'ordre de la multiplication. |

### translateTransform(float x, float y) {#translateTransform-float-float-}
```
public void translateTransform(float x, float y)
```


Modifie l'origine du système de coordonnées en préfixant la translation spécifiée à la matrice de transformation de cet objet Graphics.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x de la translation. |
| y | float | La coordonnée y de la translation. |

### translateTransform(float x, float y, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float x, float y, int order)
```


Modifie l'origine du système de coordonnées en appliquant la translation spécifiée à la matrice de transformation de cet objet Graphics dans l'ordre indiqué.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x de la translation. |
| y | float | La coordonnée y de la translation. |
| ordre | int | Spécifie si la translation est préfixée ou suffixée à la matrice de transformation. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Applique la rotation spécifiée à la matrice de transformation de cet objet Graphics.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | Angle de rotation en degrés. |

### rotateTransform(float angle, PointF center, int order) {#rotateTransform-float-com.aspose.imaging.PointF-int-}
```
public void rotateTransform(float angle, PointF center, int order)
```


Applique la rotation spécifiée à la matrice de transformation de cet objet Graphics dans l'ordre indiqué.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | Angle de rotation en degrés. |
| center | [PointF](../../com.aspose.imaging/pointf) | Le centre de rotation. |
| ordre | int | Spécifie si la rotation est ajoutée ou préfixée à la transformation de la matrice. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Applique l'opération de mise à l'échelle spécifiée à la matrice de transformation de cet objet Graphics en la préfixant à la matrice de transformation de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sx | float | Facteur d'échelle dans la direction x. |
| sy | float | Facteur d'échelle dans la direction y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Applique l'opération de mise à l'échelle spécifiée à la matrice de transformation de cet objet Graphics dans l'ordre indiqué.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sx | float | Facteur d'échelle dans la direction x. |
| sy | float | Facteur d'échelle dans la direction y. |
| ordre | int | Spécifie si l'opération de mise à l'échelle est préfixée ou ajoutée à la matrice de transformation. |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Obtient la transformation du monde.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - The transform matrix.
### setTransform(Matrix transform) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix transform)
```


Définit la transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | La nouvelle matrice de transformation. |


**Example: This example shows how to load a EMF image from a file and draw a text string over it.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
            com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D.fromEmfImage(emfImage);

    // Tout d'abord, obtenez la taille de l'image
    int width = emfImage.getWidth();
    int height = emfImage.getHeight();

    // Deuxièmement, calculez une transformation pour placer une chaîne de texte le long de la diagonale principale de l'image -
    // du coin supérieur gauche au coin inférieur droit.
    float emFontSize = 96f;
    float d = (float) java.lang.Math.sqrt(width * width + height * height);
    float scaleFactor = d / (emFontSize * 5f);

    float tan = ((float) height) / width;
    double radians = java.lang.Math.atan(tan);
    double degrees = (180 * radians) / java.lang.Math.PI;

    com.aspose.imaging.Matrix transform = new com.aspose.imaging.Matrix();
    transform.rotate((float) degrees);
    transform.scale(scaleFactor, scaleFactor);

    // Ensuite, définissez la transformation.
    graphics.setTransform(transform);

    // Enfin, placez un filigrane (chaîne de texte de couleur rose) le long de la diagonale principale.
    graphics.drawString("WATERMARK", new com.aspose.imaging.Font(
                    "Courier New", emFontSize),
            com.aspose.imaging.Color.getLightPink(), 0, 0/*, (float)degrees*/);

    // Enregistrez l'image avec le filigrane dans un autre fichier EMF.
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

