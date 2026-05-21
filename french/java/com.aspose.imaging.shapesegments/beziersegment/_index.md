---
title: "BezierSegment"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le segment de Bézier allant d'un point au point suivant en utilisant deux points de contrôle."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.shapesegments/beziersegment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ShapeSegment](../../com.aspose.imaging/shapesegment), [com.aspose.imaging.shapesegments.LineSegment](../../com.aspose.imaging.shapesegments/linesegment)
```
public final class BezierSegment extends LineSegment
```

Le segment de Bézier allant d'un point au point suivant en utilisant deux points de contrôle.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)](#BezierSegment-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Initialise une nouvelle instance de la classe `BezierSegment`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFirstControlPoint()](#getFirstControlPoint--) | Obtient le premier point de contrôle d'une courbe de Bézier. |
| [getSecondControlPoint()](#getSecondControlPoint--) | Obtient le deuxième point de contrôle d'une courbe de Bézier. |
| [equals(Object obj)](#equals-java.lang.Object-) | Vérifie si les objets sont égaux. |
| [hashCode()](#hashCode--) | Obtient le code de hachage de l'objet actuel. |
### BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint) {#BezierSegment-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)
```


Initialise une nouvelle instance de la classe `BezierSegment`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startPoint | [PointF](../../com.aspose.imaging/pointf) | Le point de départ. |
| firstControlPoint | [PointF](../../com.aspose.imaging/pointf) | Le premier point de contrôle. |
| secondControlPoint | [PointF](../../com.aspose.imaging/pointf) | Le deuxième point de contrôle. |
| endPoint | [PointF](../../com.aspose.imaging/pointf) | Le point d'arrivée. |

### getFirstControlPoint() {#getFirstControlPoint--}
```
public PointF getFirstControlPoint()
```


Obtient le premier point de contrôle d'une courbe de Bézier.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The first control point.
### getSecondControlPoint() {#getSecondControlPoint--}
```
public PointF getSecondControlPoint()
```


Obtient le deuxième point de contrôle d'une courbe de Bézier.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The second control point.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Vérifie si les objets sont égaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'autre objet. |

**Returns:**
boolean - Le résultat de la comparaison d'égalité.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtient le code de hachage de l'objet actuel.

**Returns:**
int - Le code de hachage.
