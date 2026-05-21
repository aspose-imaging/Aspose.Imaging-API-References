---
title: "ConvolutionFilter"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Kernel-Matrix-Provider-Klasse."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.imagefilters.convolution/convolutionfilter/
---
**Inheritance:**
java.lang.Object
```
public final class ConvolutionFilter
```

Die Kernel-Matrix-Provider-Klasse.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSharpen3x3()](#getSharpen3x3--) | Liefert den 3x3-Schärfungs‑Kernel. |
| [getSharpen5x5()](#getSharpen5x5--) | Liefert den 5x5-Schärfungs‑Kernel. |
| [getEmboss3x3()](#getEmboss3x3--) | Liefert den 3x3-Präge‑Kernel. |
| [getEmboss5x5()](#getEmboss5x5--) | Liefert den 5x5-Präge‑Kernel. |
| [getBlurMotion(int size, double angle)](#getBlurMotion-int-double-) | Liefert den Bewegungsunschärfe‑Kernel. |
| [getGaussian(int size, double sigma)](#getGaussian-int-double-) | Liefert den Gauß‑Kernel. |
| [getBlurBox(int size)](#getBlurBox-int-) | Liefert den Box‑Unschärfe‑Kernel. |
| [toComplex(double[][] kernel)](#toComplex-double-----) | Konvertiert `kernel` zu einem [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex)-Kernel. |
### getSharpen3x3() {#getSharpen3x3--}
```
public static double[][] getSharpen3x3()
```


Liefert den 3x3-Schärfungs‑Kernel.

**Returns:**
double[][] - der 3x3-Schärfungs‑Kernel.
### getSharpen5x5() {#getSharpen5x5--}
```
public static double[][] getSharpen5x5()
```


Liefert den 5x5-Schärfungs‑Kernel.

**Returns:**
double[][] - der 5x5-Schärfungs‑Kernel.
### getEmboss3x3() {#getEmboss3x3--}
```
public static double[][] getEmboss3x3()
```


Liefert den 3x3-Präge‑Kernel.

**Returns:**
double[][] - der 3x3-Präge‑Kernel.
### getEmboss5x5() {#getEmboss5x5--}
```
public static double[][] getEmboss5x5()
```


Liefert den 5x5-Präge‑Kernel.

**Returns:**
double[][] - der 5x5-Präge‑Kernel.
### getBlurMotion(int size, double angle) {#getBlurMotion-int-double-}
```
public static double[][] getBlurMotion(int size, double angle)
```


Liefert den Bewegungsunschärfe‑Kernel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Größe | int | Die Kernelgröße. |
| angle | double | Der Bewegungswinkel. |

**Returns:**
double[][] - Der Bewegungsunschärfe‑Kernel.
### getGaussian(int size, double sigma) {#getGaussian-int-double-}
```
public static double[][] getGaussian(int size, double sigma)
```


Liefert den Gauß‑Kernel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Größe | int | Die Kernelgröße. |
| Sigma | double | Der Sigma‑Wert im Bereich (0...]. |

**Returns:**
double[][] - Der Gaußsche Kernel.
### getBlurBox(int size) {#getBlurBox-int-}
```
public static double[][] getBlurBox(int size)
```


Liefert den Box‑Unschärfe‑Kernel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Größe | int | Die Kernelgröße. |

**Returns:**
double[][] - Der Box-Blur-Kernel.
### toComplex(double[][] kernel) {#toComplex-double-----}
```
public static Complex[][] toComplex(double[][] kernel)
```


Konvertiert `kernel` zu einem [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex)-Kernel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Kernel | double[][] | Der Kernel. |

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - Ein [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) Kernel.
