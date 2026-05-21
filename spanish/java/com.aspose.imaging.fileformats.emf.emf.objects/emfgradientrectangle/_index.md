---
title: "EmfGradientRectangle"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto GradientRectangle define un rectángulo usando objetos TriVertex sección 2.2.26 en un registro EMR_GRADIENTFILL sección 2.3.5.12."
type: docs
weight: 16
url: /es/java/com.aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfGradientRectangle extends EmfObject
```

El objeto GradientRectangle define un rectángulo usando objetos TriVertex (sección 2.2.26) en un registro EMR\_GRADIENTFILL (sección 2.3.5.12).
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfGradientRectangle()](#EmfGradientRectangle--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getUpperLeft()](#getUpperLeft--) | Obtiene o establece un índice en una matriz de objetos TriVertex que especifica el vértice superior izquierdo de un rectángulo. |
| [setUpperLeft(int value)](#setUpperLeft-int-) | Obtiene o establece un índice en una matriz de objetos TriVertex que especifica el vértice superior izquierdo de un rectángulo. |
| [getLowerRight()](#getLowerRight--) | Obtiene o establece un índice en una matriz de objetos TriVertex que especifica el vértice inferior derecho de un rectángulo. |
| [setLowerRight(int value)](#setLowerRight-int-) | Obtiene o establece un índice en una matriz de objetos TriVertex que especifica el vértice inferior derecho de un rectángulo. |
### EmfGradientRectangle() {#EmfGradientRectangle--}
```
public EmfGradientRectangle()
```


### getUpperLeft() {#getUpperLeft--}
```
public int getUpperLeft()
```


Obtiene o establece un índice en una matriz de objetos TriVertex que especifica el vértice superior izquierdo de un rectángulo. El índice DEBE ser menor que el tamaño de la matriz, según lo definido por el campo nVer del registro EMR\_GRADIENTFILL.

**Returns:**
int
### setUpperLeft(int value) {#setUpperLeft-int-}
```
public void setUpperLeft(int value)
```


Obtiene o establece un índice en una matriz de objetos TriVertex que especifica el vértice superior izquierdo de un rectángulo. El índice DEBE ser menor que el tamaño de la matriz, según lo definido por el campo nVer del registro EMR\_GRADIENTFILL.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getLowerRight() {#getLowerRight--}
```
public int getLowerRight()
```


Obtiene o establece un índice en una matriz de objetos TriVertex que especifica el vértice inferior derecho de un rectángulo. El índice DEBE ser menor que el tamaño de la matriz, según lo definido por el campo nVer del registro EMR\_GRADIENTFILL.

**Returns:**
int
### setLowerRight(int value) {#setLowerRight-int-}
```
public void setLowerRight(int value)
```


Obtiene o establece un índice en una matriz de objetos TriVertex que especifica el vértice inferior derecho de un rectángulo. El índice DEBE ser menor que el tamaño de la matriz, según lo definido por el campo nVer del registro EMR\_GRADIENTFILL.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

