---
title: "ConvolutionFilter"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La clase proveedora de la matriz del kernel."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.imagefilters.convolution/convolutionfilter/
---
**Inheritance:**
java.lang.Object
```
public final class ConvolutionFilter
```

La clase proveedora de la matriz del kernel.
## Métodos

| Método | Descripción |
| --- | --- |
| [getSharpen3x3()](#getSharpen3x3--) | Obtiene el kernel de afilado 3x3. |
| [getSharpen5x5()](#getSharpen5x5--) | Obtiene el kernel de afilado 5x5. |
| [getEmboss3x3()](#getEmboss3x3--) | Obtiene el kernel de relieve 3x3. |
| [getEmboss5x5()](#getEmboss5x5--) | Obtiene el kernel de relieve 5x5. |
| [getBlurMotion(int size, double angle)](#getBlurMotion-int-double-) | Obtiene el kernel de desenfoque de movimiento. |
| [getGaussian(int size, double sigma)](#getGaussian-int-double-) | Obtiene el kernel gaussiano. |
| [getBlurBox(int size)](#getBlurBox-int-) | Obtiene el kernel de desenfoque de caja. |
| [toComplex(double[][] kernel)](#toComplex-double-----) | Convierte `kernel` a un kernel [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
### getSharpen3x3() {#getSharpen3x3--}
```
public static double[][] getSharpen3x3()
```


Obtiene el kernel de afilado 3x3.

**Returns:**
double[][] - el kernel de afilado 3x3.
### getSharpen5x5() {#getSharpen5x5--}
```
public static double[][] getSharpen5x5()
```


Obtiene el kernel de afilado 5x5.

**Returns:**
double[][] - el kernel de afilado 5x5.
### getEmboss3x3() {#getEmboss3x3--}
```
public static double[][] getEmboss3x3()
```


Obtiene el kernel de relieve 3x3.

**Returns:**
double[][] - el kernel de relieve 3x3.
### getEmboss5x5() {#getEmboss5x5--}
```
public static double[][] getEmboss5x5()
```


Obtiene el kernel de relieve 5x5.

**Returns:**
double[][] - el kernel de relieve 5x5.
### getBlurMotion(int size, double angle) {#getBlurMotion-int-double-}
```
public static double[][] getBlurMotion(int size, double angle)
```


Obtiene el kernel de desenfoque de movimiento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | int | El tamaño del kernel. |
| angle | double | El ángulo de movimiento. |

**Returns:**
double[][] - El kernel de desenfoque de movimiento.
### getGaussian(int size, double sigma) {#getGaussian-int-double-}
```
public static double[][] getGaussian(int size, double sigma)
```


Obtiene el kernel gaussiano.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | int | El tamaño del kernel. |
| sigma | double | El valor sigma en el rango (0...]. |

**Returns:**
double[][] - El kernel gaussiano.
### getBlurBox(int size) {#getBlurBox-int-}
```
public static double[][] getBlurBox(int size)
```


Obtiene el kernel de desenfoque de caja.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | int | El tamaño del kernel. |

**Returns:**
double[][] - El kernel de desenfoque de caja.
### toComplex(double[][] kernel) {#toComplex-double-----}
```
public static Complex[][] toComplex(double[][] kernel)
```


Convierte `kernel` a un kernel [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| núcleo | double[][] | El núcleo. |

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - Un [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) kernel.
