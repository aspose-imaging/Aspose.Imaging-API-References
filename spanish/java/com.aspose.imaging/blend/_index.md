---
title: "Blend"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Define un patrón de mezcla."
type: docs
weight: 12
url: /es/java/com.aspose.imaging/blend/
---
**Inheritance:**
java.lang.Object
```
public final class Blend
```

Define un patrón de mezcla. Esta clase no puede heredarse.

El uso típico de la clase Blend consiste en definir un patrón de mezcla para el pincel. Por lo tanto, las propiedades de mezcla deben inicializarse con cuidado. No se permiten matrices nulas. El pincel lanzará la excepción correspondiente si las matrices de factores de mezcla o de posiciones están vacías o su longitud no es la misma. Si hay dos o más elementos en la matriz de posiciones, el primer elemento debe ser 0 y el último debe ser 1.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Blend()](#Blend--) | Inicializa una nueva instancia de la clase `Blend`. |
| [Blend(int count)](#Blend-int-) | Inicializa una nueva instancia de la clase `Blend` con el número especificado de factores y posiciones. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFactors()](#getFactors--) | Obtiene la matriz de factores de mezcla para el degradado. |
| [setFactors(float[] value)](#setFactors-float---) | Establece la matriz de factores de mezcla para el degradado. |
| [getPositions()](#getPositions--) | Obtiene la matriz de posiciones de mezcla para el degradado. |
| [setPositions(float[] value)](#setPositions-float---) | Establece la matriz de posiciones de mezcla para el degradado. |
| [equals(Object obj)](#equals-java.lang.Object-) | Comprueba si el objeto especificado es una clase `com.aspose.imaging.Blend` y es equivalente a esta clase `com.aspose.imaging.Blend`. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia. |
### Blend() {#Blend--}
```
public Blend()
```


Inicializa una nueva instancia de la clase `Blend`. El número de elementos en los arreglos de factor y mezcla será igual a 1.

### Blend(int count) {#Blend-int-}
```
public Blend(int count)
```


Inicializa una nueva instancia de la clase `Blend` con el número especificado de factores y posiciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| count | int | El número de elementos en los arreglos de factor y posición. |

### getFactors() {#getFactors--}
```
public float[] getFactors()
```


Obtiene la matriz de factores de mezcla para el degradado.

**Returns:**
float[] - El arreglo de factores de mezcla que especifica los porcentajes del color inicial y del color final que se usarán en la posición correspondiente.
### setFactors(float[] value) {#setFactors-float---}
```
public void setFactors(float[] value)
```


Establece la matriz de factores de mezcla para el degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float[] | El arreglo de factores de mezcla que especifica los porcentajes del color inicial y del color final que se usarán en la posición correspondiente. |

### getPositions() {#getPositions--}
```
public float[] getPositions()
```


Obtiene la matriz de posiciones de mezcla para el degradado.

**Returns:**
float[] - El arreglo de posiciones de mezcla que especifica los porcentajes de distancia a lo largo de la línea de degradado.
### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```


Establece la matriz de posiciones de mezcla para el degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float[] | El arreglo de posiciones de mezcla que especifica los porcentajes de distancia a lo largo de la línea de degradado. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Comprueba si el objeto especificado es una clase `com.aspose.imaging.Blend` y es equivalente a esta clase `com.aspose.imaging.Blend`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El objeto a probar. |

**Returns:**
boolean - Verdadero si `obj` es una clase `com.aspose.imaging.Blend` equivalente a esta clase `com.aspose.imaging.Blend`; de lo contrario, falso.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta instancia.

**Returns:**
int - Un código hash para esta instancia, adecuado para su uso en algoritmos de hash y estructuras de datos como una tabla hash.
