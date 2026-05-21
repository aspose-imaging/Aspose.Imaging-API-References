---
title: "ConvolutionFilter"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "La classe provider della matrice kernel."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.imagefilters.convolution/convolutionfilter/
---
**Inheritance:**
java.lang.Object
```
public final class ConvolutionFilter
```

La classe provider della matrice kernel.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSharpen3x3()](#getSharpen3x3--) | Ottiene il kernel di nitidezza 3x3. |
| [getSharpen5x5()](#getSharpen5x5--) | Ottiene il kernel di nitidezza 5x5. |
| [getEmboss3x3()](#getEmboss3x3--) | Ottiene il kernel di emboss 3x3. |
| [getEmboss5x5()](#getEmboss5x5--) | Ottiene il kernel di emboss 5x5. |
| [getBlurMotion(int size, double angle)](#getBlurMotion-int-double-) | Ottiene il kernel di sfocatura di movimento. |
| [getGaussian(int size, double sigma)](#getGaussian-int-double-) | Ottiene il kernel gaussiano. |
| [getBlurBox(int size)](#getBlurBox-int-) | Ottiene il kernel di sfocatura a scatola. |
| [toComplex(double[][] kernel)](#toComplex-double-----) | Converte `kernel` in un kernel [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
### getSharpen3x3() {#getSharpen3x3--}
```
public static double[][] getSharpen3x3()
```


Ottiene il kernel di nitidezza 3x3.

**Returns:**
double[][] - il kernel di nitidezza 3x3.
### getSharpen5x5() {#getSharpen5x5--}
```
public static double[][] getSharpen5x5()
```


Ottiene il kernel di nitidezza 5x5.

**Returns:**
double[][] - il kernel di nitidezza 5x5.
### getEmboss3x3() {#getEmboss3x3--}
```
public static double[][] getEmboss3x3()
```


Ottiene il kernel di emboss 3x3.

**Returns:**
double[][] - il kernel di emboss 3x3.
### getEmboss5x5() {#getEmboss5x5--}
```
public static double[][] getEmboss5x5()
```


Ottiene il kernel di emboss 5x5.

**Returns:**
double[][] - il kernel di emboss 5x5.
### getBlurMotion(int size, double angle) {#getBlurMotion-int-double-}
```
public static double[][] getBlurMotion(int size, double angle)
```


Ottiene il kernel di sfocatura di movimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dimensione | int | La dimensione del kernel. |
| angle | double | L'angolo di movimento. |

**Returns:**
double[][] - Il kernel di sfocatura di movimento.
### getGaussian(int size, double sigma) {#getGaussian-int-double-}
```
public static double[][] getGaussian(int size, double sigma)
```


Ottiene il kernel gaussiano.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dimensione | int | La dimensione del kernel. |
| sigma | double | Il valore sigma nell'intervallo (0...]. |

**Returns:**
double[][] - Il kernel gaussiano.
### getBlurBox(int size) {#getBlurBox-int-}
```
public static double[][] getBlurBox(int size)
```


Ottiene il kernel di sfocatura a scatola.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dimensione | int | La dimensione del kernel. |

**Returns:**
double[][] - Il kernel di sfocatura a scatola.
### toComplex(double[][] kernel) {#toComplex-double-----}
```
public static Complex[][] toComplex(double[][] kernel)
```


Converte `kernel` in un kernel [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| kernel | double[][] | Il kernel. |

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - Un kernel [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).
