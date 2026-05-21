---
title: "CurveShape"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente une forme de spline courbée."
type: docs
weight: 12
url: /fr/java/com.aspose.imaging.shapes/curveshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.PolygonShape](../../com.aspose.imaging.shapes/polygonshape)
```
public final class CurveShape extends PolygonShape
```

Représente une forme de spline courbée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CurveShape()](#CurveShape--) | Initialise une nouvelle instance de la classe `CurveShape`. |
| [CurveShape(PointF[] points)](#CurveShape-com.aspose.imaging.PointF---) | Initialise une nouvelle instance de la classe `CurveShape`. |
| [CurveShape(PointF[] points, boolean isClosed)](#CurveShape-com.aspose.imaging.PointF---boolean-) | Initialise une nouvelle instance de la classe `CurveShape`. |
| [CurveShape(PointF[] points, float tension)](#CurveShape-com.aspose.imaging.PointF---float-) | Initialise une nouvelle instance de la classe `CurveShape`. |
| [CurveShape(PointF[] points, float tension, boolean isClosed)](#CurveShape-com.aspose.imaging.PointF---float-boolean-) | Initialise une nouvelle instance de la classe `CurveShape`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTension()](#getTension--) | Obtient ou définit la tension de la courbe. |
| [setTension(float value)](#setTension-float-) | Obtient ou définit la tension de la courbe. |
| [getBounds()](#getBounds--) | Obtient les limites de l'objet. |
| [getCenter()](#getCenter--) | Obtient le centre de la forme. |
| [getSegments()](#getSegments--) | Obtient les segments de la forme. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Obtient les limites de l'objet. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Obtient les limites de l'objet. |
| [equals(Object o)](#equals-java.lang.Object-) | Vérifie si les objets sont égaux. |
| [hashCode()](#hashCode--) | Obtient le code de hachage de l'objet actuel. |
### CurveShape() {#CurveShape--}
```
public CurveShape()
```


Initialise une nouvelle instance de la classe `CurveShape`.

### CurveShape(PointF[] points) {#CurveShape-com.aspose.imaging.PointF---}
```
public CurveShape(PointF[] points)
```


Initialise une nouvelle instance de la classe `CurveShape`. La tension par défaut de 0.5 est utilisée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Le tableau de points. |

### CurveShape(PointF[] points, boolean isClosed) {#CurveShape-com.aspose.imaging.PointF---boolean-}
```
public CurveShape(PointF[] points, boolean isClosed)
```


Initialise une nouvelle instance de la classe `CurveShape`. La tension par défaut de 0.5 est utilisée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Le tableau de points. |
| isClosed | boolean |  |

### CurveShape(PointF[] points, float tension) {#CurveShape-com.aspose.imaging.PointF---float-}
```
public CurveShape(PointF[] points, float tension)
```


Initialise une nouvelle instance de la classe `CurveShape`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Le tableau de points. |
| tension | float | La tension de la courbe. |

### CurveShape(PointF[] points, float tension, boolean isClosed) {#CurveShape-com.aspose.imaging.PointF---float-boolean-}
```
public CurveShape(PointF[] points, float tension, boolean isClosed)
```


Initialise une nouvelle instance de la classe `CurveShape`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Le tableau de points. |
| tension | float | La tension de la courbe. |
| isClosed | boolean | si la valeur est `true`, la courbe est fermée. |

### getTension() {#getTension--}
```
public float getTension()
```


Obtient ou définit la tension de la courbe.

Valeur : la tension de la courbe.

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Obtient ou définit la tension de la courbe.

Valeur : la tension de la courbe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

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
