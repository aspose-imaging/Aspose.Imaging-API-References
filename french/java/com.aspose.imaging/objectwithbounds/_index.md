---
title: "ObjectWithBounds"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet ayant des limites."
type: docs
weight: 77
url: /fr/java/com.aspose.imaging/objectwithbounds/
---
**Inheritance:**
java.lang.Object
```
public abstract class ObjectWithBounds
```

L'objet ayant des limites.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ObjectWithBounds()](#ObjectWithBounds--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Obtient les limites de l'objet. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Obtient les limites de l'objet. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Obtient les limites de l'objet. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Applique la transformation spécifiée à la forme. |
### ObjectWithBounds() {#ObjectWithBounds--}
```
public ObjectWithBounds()
```


### getBounds() {#getBounds--}
```
public abstract RectangleF getBounds()
```


Obtient les limites de l'objet.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public abstract RectangleF getBounds(Matrix matrix)
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
public abstract RectangleF getBounds(Matrix matrix, Pen pen)
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
public abstract void transform(Matrix transform)
```


Applique la transformation spécifiée à la forme.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | La transformation à appliquer. |

