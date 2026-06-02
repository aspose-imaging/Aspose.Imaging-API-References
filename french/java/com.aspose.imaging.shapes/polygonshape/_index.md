---
title: "PolygonShape"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente une forme de polygone."
type: docs
weight: 15
url: /fr/java/com.aspose.imaging.shapes/polygonshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape)

**All Implemented Interfaces:**
[com.aspose.imaging.IOrderedShape](../../com.aspose.imaging/iorderedshape)
```
public class PolygonShape extends Shape implements IOrderedShape
```

Représente une forme de polygone.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PolygonShape()](#PolygonShape--) | Initialise une nouvelle instance de la classe `PolygonShape`. |
| [PolygonShape(PointF[] points)](#PolygonShape-com.aspose.imaging.PointF---) | Initialise une nouvelle instance de la classe `PolygonShape`. |
| [PolygonShape(PointF[] points, boolean isClosed)](#PolygonShape-com.aspose.imaging.PointF---boolean-) | Initialise une nouvelle instance de la classe `PolygonShape`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPoints()](#getPoints--) | Obtient ou définit les points de la courbe. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.imaging.PointF---) | Obtient ou définit les points de la courbe. |
| [isClosed()](#isClosed--) | Obtient ou définit une valeur indiquant si la forme est fermée. |
| [setClosed(boolean value)](#setClosed-boolean-) | Obtient ou définit une valeur indiquant si la forme est fermée. |
| [getBounds()](#getBounds--) | Obtient les limites de l'objet. |
| [getCenter()](#getCenter--) | Obtient le centre de la forme. |
| [getSegments()](#getSegments--) | Obtient les segments de la forme. |
| [hasSegments()](#hasSegments--) | Obtient une valeur indiquant si la forme possède des segments. |
| [getStartPoint()](#getStartPoint--) | Obtient le point de départ de la forme. |
| [getEndPoint()](#getEndPoint--) | Obtient le point d'arrivée de la forme. |
| [reverse()](#reverse--) | Inverse l'ordre des points pour cette forme. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Obtient les limites de l'objet. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Obtient les limites de l'objet. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Applique la transformation spécifiée à la forme. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si l'objet spécifié est égal à l'objet actuel. |
| [hashCode()](#hashCode--) | Servir de fonction de hachage par défaut. |

## Example: This example creates a new Image and draws a variety of shapes using Figures and GraphicsPath o...
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

### PolygonShape() {#PolygonShape--}
```
public PolygonShape()
```


Initialise une nouvelle instance de la classe `PolygonShape`.

### PolygonShape(PointF[] points) {#PolygonShape-com.aspose.imaging.PointF---}
```
public PolygonShape(PointF[] points)
```


Initialise une nouvelle instance de la classe `PolygonShape`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Le tableau de points. |

### PolygonShape(PointF[] points, boolean isClosed) {#PolygonShape-com.aspose.imaging.PointF---boolean-}
```
public PolygonShape(PointF[] points, boolean isClosed)
```


Initialise une nouvelle instance de la classe `PolygonShape`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Le tableau de points. |
| isClosed | boolean | Si la valeur est `true`, le polygone est fermé. |

### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


Obtient ou définit les points de la courbe.

Valeur : les points de la courbe.

**Returns:**
com.aspose.imaging.PointF[]
### setPoints(PointF[] value) {#setPoints-com.aspose.imaging.PointF---}
```
public void setPoints(PointF[] value)
```


Obtient ou définit les points de la courbe.

Valeur : les points de la courbe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Obtient ou définit une valeur indiquant si la forme est fermée.

Valeur : `true` si la forme est fermée ; sinon, `false`.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Obtient ou définit une valeur indiquant si la forme est fermée.

Valeur : `true` si la forme est fermée ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Obtient les limites de l'objet.

Valeur: les limites de l'objet.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Obtient le centre de la forme.

Valeur: le centre de la forme.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Obtient les segments de la forme.

Valeur : les segments de la forme.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Obtient une valeur indiquant si la forme possède des segments.

Valeur: `True` si la forme possède des segments ; sinon, `false`.

**Returns:**
boolean
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Obtient le point de départ de la forme.

Valeur : le point de départ de la forme.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


Obtient le point d'arrivée de la forme.

Valeur : le point d'arrivée de la forme.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### reverse() {#reverse--}
```
public void reverse()
```


Inverse l'ordre des points pour cette forme.

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
