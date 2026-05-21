---
title: "Figure"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "La figure."
type: docs
weight: 44
url: /fr/java/com.aspose.imaging/figure/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

La figure. Un conteneur pour les formes.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Figure()](#Figure--) | Initialise une nouvelle instance de [Figure](../../com.aspose.imaging/figure). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getShapes()](#getShapes--) | Obtient les formes de la figure. |
| [getBounds()](#getBounds--) | Obtient ou définit les limites de l'objet. |
| [isClosed()](#isClosed--) | Obtient une valeur indiquant si cette figure est fermée. |
| [setClosed(boolean value)](#setClosed-boolean-) | Définit une valeur indiquant si cette figure est fermée. |
| [getSegments()](#getSegments--) | Obtient l'ensemble des segments de la figure. |
| [addShape(Shape shape)](#addShape-com.aspose.imaging.Shape-) | Ajoute une forme à la figure. |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.imaging.Shape---) | Ajoute une plage de formes à la figure. |
| [removeShape(Shape shape)](#removeShape-com.aspose.imaging.Shape-) | Supprime une forme de la figure. |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.imaging.Shape---) | Supprime une plage de formes de la figure. |
| [reverse()](#reverse--) | Inverse l'ordre des formes de cette figure ainsi que l'ordre des points des formes. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Obtient les limites de l'objet. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Obtient les limites de l'objet. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Applique la transformation spécifiée à la forme. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si l'objet spécifié est égal à l'objet actuel. |
| [hashCode()](#hashCode--) | Servir de fonction de hachage par défaut. |

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

### Figure() {#Figure--}
```
public Figure()
```


Initialise une nouvelle instance de [Figure](../../com.aspose.imaging/figure). Un constructeur requis pour une désérialisation JSON.

### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


Obtient les formes de la figure.

**Returns:**
com.aspose.imaging.Shape[] - Les formes de la figure.
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Obtient ou définit les limites de l'objet.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Obtient une valeur indiquant si cette figure est fermée. Une figure fermée ne fera une différence que dans le cas où les formes de la première et de la dernière figure sont continues. Dans ce cas, le premier point de la première forme sera relié par une ligne droite au dernier point de la dernière forme.

**Returns:**
booléen - `True` si cette figure est fermée ; sinon, `false`.
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Définit une valeur indiquant si cette figure est fermée. Une figure fermée ne fera une différence que dans le cas où les formes de la première et de la dernière figure sont continues. Dans ce cas, le premier point de la première forme sera relié par une ligne droite au dernier point de la dernière forme.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | `True` si cette figure est fermée ; sinon, `false`. |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Obtient l'ensemble des segments de la figure.

**Returns:**
com.aspose.imaging.ShapeSegment[] - Les segments de la figure.
### addShape(Shape shape) {#addShape-com.aspose.imaging.Shape-}
```
public void addShape(Shape shape)
```


Ajoute une forme à la figure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.imaging/shape) | La forme à ajouter. |


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

### addShapes(Shape[] shapes) {#addShapes-com.aspose.imaging.Shape---}
```
public void addShapes(Shape[] shapes)
```


Ajoute une plage de formes à la figure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.imaging/shape) | Les formes à ajouter. |

### removeShape(Shape shape) {#removeShape-com.aspose.imaging.Shape-}
```
public void removeShape(Shape shape)
```


Supprime une forme de la figure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.imaging/shape) | La forme à supprimer. |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.imaging.Shape---}
```
public void removeShapes(Shape[] shapes)
```


Supprime une plage de formes de la figure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.imaging/shape) | La plage de formes à supprimer. |

### reverse() {#reverse--}
```
public void reverse()
```


Inverse l'ordre des formes de cette figure ainsi que l'ordre des points des formes.

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
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Applique la transformation spécifiée à la forme.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | La transformation à appliquer. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si l'objet spécifié est égal à l'objet actuel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'objet comparé. |

**Returns:**
booléen - Le résultat de equals
### hashCode() {#hashCode--}
```
public int hashCode()
```


Servir de fonction de hachage par défaut.

**Returns:**
int - Un code de hachage pour l'objet actuel.
