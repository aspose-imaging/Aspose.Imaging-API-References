---
title: "ObjectWithBounds"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto que tiene límites."
type: docs
weight: 77
url: /es/java/com.aspose.imaging/objectwithbounds/
---
**Inheritance:**
java.lang.Object
```
public abstract class ObjectWithBounds
```

El objeto que tiene límites.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ObjectWithBounds()](#ObjectWithBounds--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBounds()](#getBounds--) | Obtiene los límites del objeto. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Obtiene los límites del objeto. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Obtiene los límites del objeto. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Aplica la transformación especificada a la forma. |
### ObjectWithBounds() {#ObjectWithBounds--}
```
public ObjectWithBounds()
```


### getBounds() {#getBounds--}
```
public abstract RectangleF getBounds()
```


Obtiene los límites del objeto.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public abstract RectangleF getBounds(Matrix matrix)
```


Obtiene los límites del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matriz a aplicar antes de que se calculen los límites. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public abstract RectangleF getBounds(Matrix matrix, Pen pen)
```


Obtiene los límites del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matriz a aplicar antes de que se calculen los límites. |
| pen | [Pen](../../com.aspose.imaging/pen) | El lápiz a usar para el objeto. Esto puede influir en el tamaño de los límites del objeto. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public abstract void transform(Matrix transform)
```


Aplica la transformación especificada a la forma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | La transformación a aplicar. |

