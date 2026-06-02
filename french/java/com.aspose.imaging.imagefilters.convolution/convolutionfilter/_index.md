---
title: "ConvolutionFilter"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "La classe du fournisseur de matrice du noyau."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.imagefilters.convolution/convolutionfilter/
---
**Inheritance:**
java.lang.Object
```
public final class ConvolutionFilter
```

La classe du fournisseur de matrice du noyau.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSharpen3x3()](#getSharpen3x3--) | Obtient le noyau de netteté 3x3. |
| [getSharpen5x5()](#getSharpen5x5--) | Obtient le noyau de netteté 5x5. |
| [getEmboss3x3()](#getEmboss3x3--) | Obtient le noyau de gaufrage 3x3. |
| [getEmboss5x5()](#getEmboss5x5--) | Obtient le noyau de gaufrage 5x5. |
| [getBlurMotion(int size, double angle)](#getBlurMotion-int-double-) | Obtient le noyau de flou de mouvement. |
| [getGaussian(int size, double sigma)](#getGaussian-int-double-) | Obtient le noyau gaussien. |
| [getBlurBox(int size)](#getBlurBox-int-) | Obtient le noyau de flou boîte. |
| [toComplex(double[][] kernel)](#toComplex-double-----) | Convertit `kernel` en un noyau [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
### getSharpen3x3() {#getSharpen3x3--}
```
public static double[][] getSharpen3x3()
```


Obtient le noyau de netteté 3x3.

**Returns:**
double[][] - le noyau de netteté 3x3.
### getSharpen5x5() {#getSharpen5x5--}
```
public static double[][] getSharpen5x5()
```


Obtient le noyau de netteté 5x5.

**Returns:**
double[][] - le noyau de netteté 5x5.
### getEmboss3x3() {#getEmboss3x3--}
```
public static double[][] getEmboss3x3()
```


Obtient le noyau de gaufrage 3x3.

**Returns:**
double[][] - le noyau de gaufrage 3x3.
### getEmboss5x5() {#getEmboss5x5--}
```
public static double[][] getEmboss5x5()
```


Obtient le noyau de gaufrage 5x5.

**Returns:**
double[][] - le noyau de gaufrage 5x5.
### getBlurMotion(int size, double angle) {#getBlurMotion-int-double-}
```
public static double[][] getBlurMotion(int size, double angle)
```


Obtient le noyau de flou de mouvement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| taille | int | La taille du noyau. |
| angle | double | L'angle de mouvement. |

**Returns:**
double[][] - le noyau de flou de mouvement.
### getGaussian(int size, double sigma) {#getGaussian-int-double-}
```
public static double[][] getGaussian(int size, double sigma)
```


Obtient le noyau gaussien.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| taille | int | La taille du noyau. |
| sigma | double | La valeur sigma dans la plage (0...]. |

**Returns:**
double[][] - Le noyau gaussien.
### getBlurBox(int size) {#getBlurBox-int-}
```
public static double[][] getBlurBox(int size)
```


Obtient le noyau de flou boîte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| taille | int | La taille du noyau. |

**Returns:**
double[][] - Le noyau de flou de boîte.
### toComplex(double[][] kernel) {#toComplex-double-----}
```
public static Complex[][] toComplex(double[][] kernel)
```


Convertit `kernel` en un noyau [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| noyau | double[][] | Le noyau. |

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - Un noyau [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).
