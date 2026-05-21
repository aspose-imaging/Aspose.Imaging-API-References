---
title: "GraphicsPath"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente une série de lignes et de courbes connectées."
type: docs
weight: 52
url: /fr/java/com.aspose.imaging/graphicspath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

Représente une série de lignes et de courbes connectées. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | Initialise une nouvelle instance de la classe `GraphicsPath`. |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.imaging.Figure---) | Initialise une nouvelle instance de la classe `GraphicsPath`. |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.imaging.Figure---int-) | Initialise une nouvelle instance de la classe `GraphicsPath`. |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | Initialise une nouvelle instance de la classe `GraphicsPath`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFillMode()](#getFillMode--) | Obtient une énumération `com.aspose.imaging.FillMode` qui détermine comment les intérieurs des formes dans ce `com.aspose.imaging.GraphicsPath` sont remplis. |
| [setFillMode(int value)](#setFillMode-int-) | Définit une énumération `com.aspose.imaging.FillMode` qui détermine comment les intérieurs des formes de ce `com.aspose.imaging.GraphicsPath` sont remplis. |
| [getFigures()](#getFigures--) | Obtient les figures du chemin. |
| [getBounds()](#getBounds--) | Obtient ou définit les limites de l'objet. |
| [reset()](#reset--) | Vide le chemin graphique et définit le `com.aspose.imaging.FillMode` sur `F:com.aspose.imaging.fillMode.alternate`. |
| [reverse()](#reverse--) | Inverse l'ordre des figures, des formes et des points dans chaque forme de ce `com.aspose.imaging.graphicsPath`. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Indique si le point spécifié est contenu dans ce `com.aspose.imaging.graphicsPath`. |
| [isVisible(PointF point)](#isVisible-com.aspose.imaging.PointF-) | Indique si le point spécifié est contenu dans ce `com.aspose.imaging.graphicsPath`. |
| [isVisible(int x, int y)](#isVisible-int-int-) | Indique si le point spécifié est contenu dans ce `com.aspose.imaging.graphicsPath`. |
| [isVisible(Point point)](#isVisible-com.aspose.imaging.Point-) | Indique si le point spécifié est contenu dans ce `com.aspose.imaging.graphicsPath`. |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.imaging.Graphics-) | Indique si le point spécifié est contenu dans ce `com.aspose.imaging.GraphicsPath` dans la région de découpe visible du `com.aspose.imaging.graphics` spécifié. |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-) | Indique si le point spécifié est contenu dans ce `com.aspose.imaging.graphicsPath`. |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.imaging.Graphics-) | Indique si le point spécifié est contenu dans ce `com.aspose.imaging.GraphicsPath`, en utilisant le `com.aspose.imaging.graphics` spécifié. |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-) | Indique si le point spécifié est contenu dans ce `com.aspose.imaging.graphicsPath`. |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.imaging.Pen-) | Indique si le point spécifié est contenu (sous) le contour de ce `com.aspose.imaging.GraphicsPath` lorsqu'il est dessiné avec le `com.aspose.imaging.pen` spécifié. |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-) | Indique si le point spécifié est contenu (sous) le contour de ce `com.aspose.imaging.GraphicsPath` lorsqu'il est dessiné avec le `com.aspose.imaging.pen` spécifié. |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Indique si le point spécifié est contenu (sous) le contour de ce `com.aspose.imaging.GraphicsPath` lorsqu'il est dessiné avec le `com.aspose.imaging.Pen` spécifié et en utilisant le `com.aspose.imaging.graphics` spécifié. |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Indique si le point spécifié est contenu (sous) le contour de ce `com.aspose.imaging.GraphicsPath` lorsqu'il est dessiné avec le `com.aspose.imaging.Pen` spécifié et en utilisant le `com.aspose.imaging.graphics` spécifié. |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.imaging.Pen-) | Indique si le point spécifié est contenu (sous) le contour de ce `com.aspose.imaging.GraphicsPath` lorsqu'il est dessiné avec le `com.aspose.imaging.pen` spécifié. |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-) | Indique si le point spécifié est contenu (sous) le contour de ce `com.aspose.imaging.GraphicsPath` lorsqu'il est dessiné avec le `com.aspose.imaging.pen` spécifié. |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Indique si le point spécifié est contenu (sous) le contour de ce `com.aspose.imaging.GraphicsPath` lorsqu'il est dessiné avec le `com.aspose.imaging.Pen` spécifié et en utilisant le `com.aspose.imaging.graphics` spécifié. |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Indique si le point spécifié est contenu (sous) le contour de ce `com.aspose.imaging.GraphicsPath` lorsqu'il est dessiné avec le `com.aspose.imaging.Pen` spécifié et en utilisant le `com.aspose.imaging.graphics` spécifié. |
| [flatten()](#flatten--) | Convertit chaque courbe de ce chemin en une séquence de segments de ligne connectés. |
| [flatten(Matrix matrix)](#flatten-com.aspose.imaging.Matrix-) | Applique la transformation spécifiée puis convertit chaque courbe de ce `com.aspose.imaging.GraphicsPath` en une séquence de segments de ligne connectés. |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.imaging.Matrix-float-) | Convertit chaque courbe de ce `com.aspose.imaging.GraphicsPath` en une séquence de segments de ligne connectés. |
| [widen(Pen pen)](#widen-com.aspose.imaging.Pen-) | Ajoute un contour supplémentaire au chemin. |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-) | Ajoute un contour supplémentaire au `com.aspose.imaging.graphicsPath`. |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-float-) | Remplace ce `com.aspose.imaging.GraphicsPath` par des courbes qui entourent la zone remplie lorsque ce chemin est dessiné avec le stylo spécifié. |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-) | Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce `com.aspose.imaging.graphicsPath`. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-) | Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce `com.aspose.imaging.graphicsPath`. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-) | Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce `com.aspose.imaging.graphicsPath`. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-float-) | Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce `com.aspose.imaging.graphicsPath`. |
| [addFigure(Figure figure)](#addFigure-com.aspose.imaging.Figure-) | Ajoute une nouvelle figure. |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.imaging.Figure---) | Ajoute de nouvelles figures. |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.imaging.Figure-) | Supprime une figure. |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.imaging.Figure---) | Supprime des figures. |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.imaging.GraphicsPath-) | Ajoute le `com.aspose.imaging.GraphicsPath` spécifié à ce chemin. |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.imaging.GraphicsPath-boolean-) | Ajoute le `com.aspose.imaging.GraphicsPath` spécifié à ce chemin. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Obtient les limites de l'objet. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Obtient les limites de l'objet. |
| [deepClone()](#deepClone--) | Effectue un clonage profond de ce chemin graphique. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Applique la transformation spécifiée à la forme. |
| [equals(Object o)](#equals-java.lang.Object-) | Vérifie si les objets sont égaux. |
| [hashCode()](#hashCode--) | Obtient le code de hachage de l'objet actuel. |

## Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.
Ces exemples utilisent les classes GraphicsPath et Graphics pour créer et manipuler des Figures sur une surface Image. L'exemple crée une nouvelle Image (de type Tiff) et trace des chemins à l'aide de la classe GraphicsPath. Enfin, la méthode DrawPath exposée par la classe Graphics est appelée pour rendre les chemins sur la surface.
``` java
// Créer une instance de FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.tif", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Créer une instance de TiffOptions et définir ses différentes propriétés
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

    // Définir la source pour l'instance de ImageOptions
    tiffOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Créer une instance de Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(tiffOptions, 500, 500);
    try {
        // Créer et initialiser une instance de la classe Graphics
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Effacer la surface Graphics
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Créer une instance de la classe GraphicsPath
        com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

        // Créer une instance de la classe Figure
        com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();

        // Ajouter des formes à l'objet Figure
        figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300)));
        figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
        figure.addShape(
                new com.aspose.imaging.shapes.PieShape(new com.aspose.imaging.RectangleF(
                        new com.aspose.imaging.PointF(250, 250),
                        new com.aspose.imaging.SizeF(200, 200)),
                        0, 45));

        // Ajouter l'objet Figure à GraphicsPath
        graphicspath.addFigure(figure);

        // Tracer le chemin avec l'objet Pen de couleur noire
        graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

        // Enregistrer toutes les modifications.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


Initialise une nouvelle instance de la classe `GraphicsPath`.

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.imaging.Figure---}
```
public GraphicsPath(Figure[] figures)
```


Initialise une nouvelle instance de la classe `GraphicsPath`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Les figures à initialiser. |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.imaging.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


Initialise une nouvelle instance de la classe `GraphicsPath`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Les figures à initialiser. |
| fillMode | int | Le mode de remplissage. |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


Initialise une nouvelle instance de la classe `GraphicsPath`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fillMode | int | Le mode de remplissage. |

### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


Obtient une énumération `com.aspose.imaging.FillMode` qui détermine comment les intérieurs des formes dans ce `com.aspose.imaging.GraphicsPath` sont remplis.

**Returns:**
int - Le mode de remplissage. Une énumération `com.aspose.imaging.FillMode` qui spécifie comment les intérieurs des formes dans ce `com.aspose.imaging.GraphicsPath` sont remplis.
### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


Définit une énumération `com.aspose.imaging.FillMode` qui détermine comment les intérieurs des formes de ce `com.aspose.imaging.GraphicsPath` sont remplis.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le mode de remplissage. |

### getFigures() {#getFigures--}
```
public Figure[] getFigures()
```


Obtient les figures du chemin.

**Returns:**
com.aspose.imaging.Figure[] - Les figures du chemin.
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Obtient ou définit les limites de l'objet.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### reset() {#reset--}
```
public void reset()
```


Vide le chemin graphique et définit le `com.aspose.imaging.FillMode` sur `F:com.aspose.imaging.fillMode.alternate`.

### reverse() {#reverse--}
```
public void reverse()
```


Inverse l'ordre des figures, des formes et des points dans chaque forme de ce `com.aspose.imaging.graphicsPath`.

### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Indique si le point spécifié est contenu dans ce `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu dans ce `com.aspose.imaging.GraphicsPath` ; sinon, false.
### isVisible(PointF point) {#isVisible-com.aspose.imaging.PointF-}
```
public boolean isVisible(PointF point)
```


Indique si le point spécifié est contenu dans ce `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Un `com.aspose.imaging.PointF` qui représente le point à tester. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu dans ce `com.aspose.imaging.GraphicsPath` ; sinon, false.
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


Indique si le point spécifié est contenu dans ce `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu dans ce `com.aspose.imaging.GraphicsPath` ; sinon, false.
### isVisible(Point point) {#isVisible-com.aspose.imaging.Point-}
```
public boolean isVisible(Point point)
```


Indique si le point spécifié est contenu dans ce `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Un `com.aspose.imaging.Point` qui représente le point à tester. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu dans ce `com.aspose.imaging.GraphicsPath` ; sinon, false.
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


Indique si le point spécifié est contenu dans ce `com.aspose.imaging.GraphicsPath` dans la région de découpe visible du `com.aspose.imaging.graphics` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Le `com.aspose.imaging.Graphics` pour lequel tester la visibilité. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu dans ce `com.aspose.imaging.GraphicsPath` ; sinon, false.
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


Indique si le point spécifié est contenu dans ce `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.imaging/pointf) | Un `com.aspose.imaging.PointF` qui représente le point à tester. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Le `com.aspose.imaging.Graphics` pour lequel tester la visibilité. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu dans cet objet ; sinon, false.
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


Indique si le point spécifié est contenu dans ce `com.aspose.imaging.GraphicsPath`, en utilisant le `com.aspose.imaging.graphics` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Le `com.aspose.imaging.Graphics` pour lequel tester la visibilité. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu dans ce `com.aspose.imaging.GraphicsPath` ; sinon, false.
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


Indique si le point spécifié est contenu dans ce `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pt | [Point](../../com.aspose.imaging/point) | Un `com.aspose.imaging.Point` qui représente le point à tester. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Le `com.aspose.imaging.Graphics` pour lequel tester la visibilité. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu dans ce `com.aspose.imaging.GraphicsPath` ; sinon, false.
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


Indique si le point spécifié est contenu (sous) le contour de ce `com.aspose.imaging.GraphicsPath` lorsqu'il est dessiné avec le `com.aspose.imaging.pen` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |
| pen | [Pen](../../com.aspose.imaging/pen) | Le `com.aspose.imaging.Pen` à tester. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu dans le contour de ce `com.aspose.imaging.GraphicsPath` lorsqu'il est dessiné avec le `com.aspose.imaging.Pen` spécifié ; sinon, false.
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


Indique si le point spécifié est contenu (sous) le contour de ce `com.aspose.imaging.GraphicsPath` lorsqu'il est dessiné avec le `com.aspose.imaging.pen` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Un `com.aspose.imaging.PointF` qui spécifie l'emplacement à tester. |
| pen | [Pen](../../com.aspose.imaging/pen) | Le `com.aspose.imaging.Pen` à tester. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu dans le contour de ce `com.aspose.imaging.GraphicsPath` lorsqu'il est dessiné avec le `com.aspose.imaging.Pen` spécifié ; sinon, false.
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


Indique si le point spécifié est contenu (sous) le contour de ce `com.aspose.imaging.GraphicsPath` lorsqu'il est dessiné avec le `com.aspose.imaging.Pen` spécifié et en utilisant le `com.aspose.imaging.graphics` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |
| pen | [Pen](../../com.aspose.imaging/pen) | Le `com.aspose.imaging.Pen` à tester. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Le `com.aspose.imaging.Graphics` pour lequel tester la visibilité. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu dans (ou sous) le contour de ce `com.aspose.imaging.GraphicsPath` tel que dessiné avec le `com.aspose.imaging.Pen` spécifié ; sinon, false.
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


Indique si le point spécifié est contenu (sous) le contour de ce `com.aspose.imaging.GraphicsPath` lorsqu'il est dessiné avec le `com.aspose.imaging.Pen` spécifié et en utilisant le `com.aspose.imaging.graphics` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.imaging/pointf) | Un `com.aspose.imaging.PointF` qui spécifie l'emplacement à tester. |
| pen | [Pen](../../com.aspose.imaging/pen) | Le `com.aspose.imaging.Pen` à tester. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Le `com.aspose.imaging.Graphics` pour lequel tester la visibilité. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu dans (ou sous) le contour de ce `com.aspose.imaging.GraphicsPath` tel que dessiné avec le `com.aspose.imaging.Pen` spécifié ; sinon, false.
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


Indique si le point spécifié est contenu (sous) le contour de ce `com.aspose.imaging.GraphicsPath` lorsqu'il est dessiné avec le `com.aspose.imaging.pen` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |
| pen | [Pen](../../com.aspose.imaging/pen) | Le `com.aspose.imaging.Pen` à tester. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu dans le contour de ce `com.aspose.imaging.GraphicsPath` lorsqu'il est dessiné avec le `com.aspose.imaging.Pen` spécifié ; sinon, false.
### isOutlineVisible(Point point, Pen pen) {#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(Point point, Pen pen)
```


Indique si le point spécifié est contenu (sous) le contour de ce `com.aspose.imaging.GraphicsPath` lorsqu'il est dessiné avec le `com.aspose.imaging.pen` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Un `com.aspose.imaging.Point` qui spécifie l'emplacement à tester. |
| pen | [Pen](../../com.aspose.imaging/pen) | Le `com.aspose.imaging.Pen` à tester. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu dans le contour de ce `com.aspose.imaging.GraphicsPath` lorsqu'il est dessiné avec le `com.aspose.imaging.Pen` spécifié ; sinon, false.
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


Indique si le point spécifié est contenu (sous) le contour de ce `com.aspose.imaging.GraphicsPath` lorsqu'il est dessiné avec le `com.aspose.imaging.Pen` spécifié et en utilisant le `com.aspose.imaging.graphics` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |
| pen | [Pen](../../com.aspose.imaging/pen) | Le `com.aspose.imaging.Pen` à tester. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Le `com.aspose.imaging.Graphics` pour lequel tester la visibilité. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu dans le contour de ce `com.aspose.imaging.GraphicsPath` tel que dessiné avec le `com.aspose.imaging.Pen` spécifié ; sinon, false.
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


Indique si le point spécifié est contenu (sous) le contour de ce `com.aspose.imaging.GraphicsPath` lorsqu'il est dessiné avec le `com.aspose.imaging.Pen` spécifié et en utilisant le `com.aspose.imaging.graphics` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pt | [Point](../../com.aspose.imaging/point) | Un `com.aspose.imaging.Point` qui spécifie l'emplacement à tester. |
| pen | [Pen](../../com.aspose.imaging/pen) | Le `com.aspose.imaging.Pen` à tester. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Le `com.aspose.imaging.Graphics` pour lequel tester la visibilité. |

**Returns:**
boolean - Cette méthode renvoie true si le point spécifié est contenu dans le contour de ce `com.aspose.imaging.GraphicsPath` tel que dessiné avec le `com.aspose.imaging.Pen` spécifié ; sinon, false.
### flatten() {#flatten--}
```
public void flatten()
```


Convertit chaque courbe de ce chemin en une séquence de segments de ligne connectés.

### flatten(Matrix matrix) {#flatten-com.aspose.imaging.Matrix-}
```
public void flatten(Matrix matrix)
```


Applique la transformation spécifiée puis convertit chaque courbe de ce `com.aspose.imaging.GraphicsPath` en une séquence de segments de ligne connectés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Une `com.aspose.imaging.Matrix` par laquelle transformer ce `com.aspose.imaging.GraphicsPath` avant l'aplatissement. |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.imaging.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


Convertit chaque courbe de ce `com.aspose.imaging.GraphicsPath` en une séquence de segments de ligne connectés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Une `com.aspose.imaging.Matrix` par laquelle transformer ce `com.aspose.imaging.GraphicsPath` avant l'aplatissement. |
| planéité | float | Spécifie l'erreur maximale autorisée entre la courbe et son approximation aplatie. Une valeur de 0,25 est la valeur par défaut. Réduire la valeur de planéité augmentera le nombre de segments de ligne dans l'approximation. |

### widen(Pen pen) {#widen-com.aspose.imaging.Pen-}
```
public void widen(Pen pen)
```


Ajoute un contour supplémentaire au chemin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Un `com.aspose.imaging.Pen` qui spécifie la largeur entre le contour original du chemin et le nouveau contour créé par cette méthode. |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


Ajoute un contour supplémentaire au `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Un `com.aspose.imaging.Pen` qui spécifie la largeur entre le contour original du chemin et le nouveau contour créé par cette méthode. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Une `com.aspose.imaging.Matrix` qui spécifie une transformation à appliquer au chemin avant l'élargissement. |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


Remplace ce `com.aspose.imaging.GraphicsPath` par des courbes qui entourent la zone remplie lorsque ce chemin est dessiné avec le stylo spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Un `com.aspose.imaging.Pen` qui spécifie la largeur entre le contour original du chemin et le nouveau contour créé par cette méthode. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Une `com.aspose.imaging.Matrix` qui spécifie une transformation à appliquer au chemin avant l'élargissement. |
| planéité | float | Une valeur qui spécifie la planéité pour les courbes. |

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Un tableau de structures `com.aspose.imaging.PointF` qui définissent un parallélogramme vers lequel le rectangle défini par `srcRect` est transformé. Le tableau peut contenir trois ou quatre éléments. Si le tableau contient trois éléments, le coin inférieur droit du parallélogramme est implicite à partir des trois premiers points. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | Un `com.aspose.imaging.RectangleF` qui représente le rectangle transformé en parallélogramme défini par `destPoints`. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Un tableau de structures `com.aspose.imaging.PointF` qui définissent un parallélogramme vers lequel le rectangle défini par `srcRect` est transformé. Le tableau peut contenir trois ou quatre éléments. Si le tableau contient trois éléments, le coin inférieur droit du parallélogramme est implicite à partir des trois premiers points. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | Un `com.aspose.imaging.RectangleF` qui représente le rectangle transformé en parallélogramme défini par `destPoints`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Une `com.aspose.imaging.Matrix` qui spécifie une transformation géométrique à appliquer au chemin. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Un tableau de structures `com.aspose.imaging.PointF` qui définit un parallélogramme vers lequel le rectangle défini par `srcRect` est transformé. Le tableau peut contenir trois ou quatre éléments. Si le tableau contient trois éléments, le coin inférieur droit du parallélogramme est implicite à partir des trois premiers points. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | Un `com.aspose.imaging.RectangleF` qui représente le rectangle transformé en parallélogramme défini par `destPoints`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Une `com.aspose.imaging.Matrix` qui spécifie une transformation géométrique à appliquer au chemin. |
| modeDéformation | int | Une énumération `com.aspose.imaging.WarpMode` qui spécifie si cette opération de déformation utilise le mode perspective ou bilinéaire. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Un tableau de structures `com.aspose.imaging.PointF` qui définissent un parallélogramme vers lequel le rectangle défini par `srcRect` est transformé. Le tableau peut contenir trois ou quatre éléments. Si le tableau contient trois éléments, le coin inférieur droit du parallélogramme est implicite à partir des trois premiers points. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | Un `com.aspose.imaging.RectangleF` qui représente le rectangle transformé en parallélogramme défini par `destPoints`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Une `com.aspose.imaging.Matrix` qui spécifie une transformation géométrique à appliquer au chemin. |
| modeDéformation | int | Une énumération `com.aspose.imaging.WarpMode` qui spécifie si cette opération de déformation utilise le mode perspective ou bilinéaire. |
| planéité | float | Une valeur comprise entre 0 et 1 qui spécifie à quel point le chemin résultant est plat. Pour plus d'informations, voir les méthodes `com.aspose.imaging.GraphicsPath.flatten`. |

### addFigure(Figure figure) {#addFigure-com.aspose.imaging.Figure-}
```
public void addFigure(Figure figure)
```


Ajoute une nouvelle figure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.imaging/figure) | La figure à ajouter. |


**Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.**
Ces exemples utilisent les classes GraphicsPath et Graphics pour créer et manipuler des Figures sur une surface Image. L'exemple crée une nouvelle Image (de type Tiff) et trace des chemins à l'aide de la classe GraphicsPath. Enfin, la méthode DrawPath exposée par la classe Graphics est appelée pour rendre les chemins sur la surface.
``` java
// Créer une instance de FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.tif", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Créer une instance de TiffOptions et définir ses différentes propriétés
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

    // Définir la source pour l'instance de ImageOptions
    tiffOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Créer une instance de Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(tiffOptions, 500, 500);
    try {
        // Créer et initialiser une instance de la classe Graphics
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Effacer la surface Graphics
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Créer une instance de la classe GraphicsPath
        com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

        // Créer une instance de la classe Figure
        com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();

        // Ajouter des formes à l'objet Figure
        figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300)));
        figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
        figure.addShape(
                new com.aspose.imaging.shapes.PieShape(new com.aspose.imaging.RectangleF(
                        new com.aspose.imaging.PointF(250, 250),
                        new com.aspose.imaging.SizeF(200, 200)),
                        0, 45));

        // Ajouter l'objet Figure à GraphicsPath
        graphicspath.addFigure(figure);

        // Tracer le chemin avec l'objet Pen de couleur noire
        graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

        // Enregistrer toutes les modifications.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### addFigures(Figure[] figures) {#addFigures-com.aspose.imaging.Figure---}
```
public void addFigures(Figure[] figures)
```


Ajoute de nouvelles figures.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Les figures à ajouter. |


**Example: This example creates a new Image and draws a variety of shapes using Figures and GraphicsPath o...**
Cet exemple crée une nouvelle Image et dessine une variété de formes en utilisant Figures et GraphicsPath sur la surface de l'Image
``` java
//Crée une instance de BmpOptions et définit ses différentes propriétés
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//Créez une instance de FileCreateSource et affectez‑la comme Source pour l'instance de BmpOptions
//Le deuxième paramètre booléen détermine si le fichier à créer est IsTemporal ou non
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\output.bmp", false));

//Créer une instance de Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Créer et initialiser une instance de la classe Graphics
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Effacer la surface Graphics
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Créer une instance de la classe GraphicsPath
    com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

    //Créer une instance de la classe Figure
    com.aspose.imaging.Figure figure1 = new com.aspose.imaging.Figure();

    //Ajouter une forme à l'objet Figure
    figure1.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
    figure1.addShape(new com.aspose.imaging.shapes.PieShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(110, 110),
                    new com.aspose.imaging.SizeF(200, 200)), 0, 90));

    //Créer une instance de la classe Figure
    com.aspose.imaging.Figure figure2 = new com.aspose.imaging.Figure();

    //Ajouter une forme à l'objet Figure
    figure2.addShape(new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.addShape(new com.aspose.imaging.shapes.PolygonShape(
            new com.aspose.imaging.PointF[]
                    {
                            new com.aspose.imaging.PointF(150, 10),
                            new com.aspose.imaging.PointF(150, 200),
                            new com.aspose.imaging.PointF(250, 300),
                            new com.aspose.imaging.PointF(350, 400)}, true));
    figure2.addShape(new com.aspose.imaging.shapes.RectangleShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(250, 250),
                    new com.aspose.imaging.SizeF(200, 200))));

    //Ajouter l'objet Figure à GraphicsPath
    graphicspath.addFigures(new com.aspose.imaging.Figure[]{figure1, figure2});

    //Tracer le chemin avec l'objet Pen de couleur noire
    graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

    // enregistrer toutes les modifications.
    image.save();
} finally {
    image.dispose();
}
```

### removeFigure(Figure figure) {#removeFigure-com.aspose.imaging.Figure-}
```
public void removeFigure(Figure figure)
```


Supprime une figure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.imaging/figure) | La figure à supprimer. |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.imaging.Figure---}
```
public void removeFigures(Figure[] figures)
```


Supprime des figures.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Les figures à supprimer. |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.imaging.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


Ajoute le `com.aspose.imaging.GraphicsPath` spécifié à ce chemin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Le `com.aspose.imaging.GraphicsPath` à ajouter. |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.imaging.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


Ajoute le `com.aspose.imaging.GraphicsPath` spécifié à ce chemin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Le `com.aspose.imaging.GraphicsPath` à ajouter. |
| connecter | boolean | Une valeur booléenne qui indique si la première figure du chemin ajouté fait partie de la dernière figure de ce chemin. Une valeur true indique que la première figure du chemin ajouté fait partie de la dernière figure de ce chemin. Une valeur false indique que la première figure du chemin ajouté est séparée de la dernière figure de ce chemin. |

### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Obtient les limites de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matrice à appliquer avant que les limites ne soient calculées. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Obtient les limites de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matrice à appliquer avant que les limites ne soient calculées. |
| pen | [Pen](../../com.aspose.imaging/pen) | Le stylo à utiliser pour l'objet. Cela peut influencer la taille des limites de l'objet. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


Effectue un clonage profond de ce chemin graphique.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - A deep clone of the graphics path.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Applique la transformation spécifiée à la forme.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | La transformation à appliquer. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Vérifie si les objets sont égaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| o | java.lang.Object | L'autre objet. |

**Returns:**
boolean - Le résultat de la comparaison d'égalité.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtient le code de hachage de l'objet actuel.

**Returns:**
int - Le code de hachage.
