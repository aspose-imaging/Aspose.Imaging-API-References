---
title: "Brush"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La clase base de pincel."
type: docs
weight: 13
url: /es/java/com.aspose.imaging/brush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public abstract class Brush extends DisposableObject
```

La clase base de pincel.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Brush()](#Brush--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getOpacity()](#getOpacity--) | Obtiene la opacidad del pincel. |
| [setOpacity(float value)](#setOpacity-float-) | Establece la opacidad del pincel. |
| [deepClone()](#deepClone--) | Crea una nueva clonación profunda del `Brush` actual. |
| [equals(Object o)](#equals-java.lang.Object-) | Comprueba si los objetos son iguales. |
| [hashCode()](#hashCode--) | Obtiene el código hash del objeto actual. |
### Brush() {#Brush--}
```
public Brush()
```


### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Obtiene la opacidad del pincel. El valor debe estar entre 0 y 1. Un valor de 0 significa que el pincel es totalmente visible, un valor de 1 significa que el pincel es totalmente opaco.

**Returns:**
float - El valor de opacidad del pincel.
### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Establece la opacidad del pincel. El valor debe estar entre 0 y 1. Un valor de 0 significa que el pincel es totalmente visible, un valor de 1 significa que el pincel es totalmente opaco.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El valor de opacidad del pincel. |

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Crea una nueva clonación profunda del `Brush` actual.

**Returns:**
[Brush](../../com.aspose.imaging/brush) - A new `Brush` which is the deep clone of this `Brush` instance.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Comprueba si los objetos son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| o | java.lang.Object | El otro objeto. |

**Returns:**
boolean - El resultado de la comparación de igualdad.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtiene el código hash del objeto actual.

**Returns:**
int - El código hash.
