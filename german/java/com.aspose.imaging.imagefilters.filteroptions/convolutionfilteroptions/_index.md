---
title: "ConvolutionFilterOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Convolution-Filteroptionen."
type: docs
weight: 15
url: /de/java/com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.IConvolutionKernel
```
public class ConvolutionFilterOptions extends FilterOptionsBase implements IConvolutionKernel
```

Die Convolution-Filteroptionen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ConvolutionFilterOptions(double[][] kernel)](#ConvolutionFilterOptions-double-----) | Initialisiert eine neue Instanz der [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) Klasse mit factor == 1 und bias == 0. |
| [ConvolutionFilterOptions(double[][] kernel, double factor)](#ConvolutionFilterOptions-double-----double-) | Initialisiert eine neue Instanz der [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) Klasse mit bias == 0. |
| [ConvolutionFilterOptions(double[][] kernel, double factor, int bias)](#ConvolutionFilterOptions-double-----double-int-) | Initialisiert eine neue Instanz der [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getKernel()](#getKernel--) | Ruft den Kernel ab. |
| [getFactor()](#getFactor--) | Ruft den Faktor ab. |
| [setFactor(double value)](#setFactor-double-) | Legt den Faktor fest. |
| [getBias()](#getBias--) | Ruft den Bias ab. |
| [setBias(int value)](#setBias-int-) | Legt den Bias fest. |
| [getIgnoreAlpha()](#getIgnoreAlpha--) | Ruft einen Wert ab, der angibt, ob [ignore alpha]. |
| [setIgnoreAlpha(boolean value)](#setIgnoreAlpha-boolean-) | Legt einen Wert fest, der angibt, ob [ignore alpha]. |
| [getBordersProcessing()](#getBordersProcessing--) | Ruft einen Wert ab, der angibt, ob [borders processing]. |
| [setBordersProcessing(boolean value)](#setBordersProcessing-boolean-) | Legt einen Wert fest, der angibt, ob [borders processing]. |
### ConvolutionFilterOptions(double[][] kernel) {#ConvolutionFilterOptions-double-----}
```
public ConvolutionFilterOptions(double[][] kernel)
```


Initialisiert eine neue Instanz der [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) Klasse mit factor == 1 und bias == 0.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Kernel | double[][] | Der Faltungskernel für die X‑Achsen‑Richtung. |

### ConvolutionFilterOptions(double[][] kernel, double factor) {#ConvolutionFilterOptions-double-----double-}
```
public ConvolutionFilterOptions(double[][] kernel, double factor)
```


Initialisiert eine neue Instanz der [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) Klasse mit bias == 0.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Kernel | double[][] | Der Faltungskernel für die X‑Achsen‑Richtung. |
| Faktor | double | Der Faktor. |

### ConvolutionFilterOptions(double[][] kernel, double factor, int bias) {#ConvolutionFilterOptions-double-----double-int-}
```
public ConvolutionFilterOptions(double[][] kernel, double factor, int bias)
```


Initialisiert eine neue Instanz der [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Kernel | double[][] | Der Faltungskernel für die X‑Achsen‑Richtung. |
| Faktor | double | Der Faktor. |
| Bias | int | Der Biaswert. |

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


Ruft den Kernel ab.

**Returns:**
double[][] – der Kernel.
### getFactor() {#getFactor--}
```
public final double getFactor()
```


Ruft den Faktor ab.

**Returns:**
double – der Faktor.
### setFactor(double value) {#setFactor-double-}
```
public final void setFactor(double value)
```


Legt den Faktor fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double | der Faktor. |

### getBias() {#getBias--}
```
public final int getBias()
```


Ruft den Bias ab.

Wert: Der Bias.

**Returns:**
int – der Bias.
### setBias(int value) {#setBias-int-}
```
public final void setBias(int value)
```


Legt den Bias fest.

Wert: Der Bias.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | der Bias. |

### getIgnoreAlpha() {#getIgnoreAlpha--}
```
public final boolean getIgnoreAlpha()
```


Ruft einen Wert ab, der angibt, ob [ignore alpha].

Wert: `true`, wenn [ignore alpha]; andernfalls `false`.

**Returns:**
boolean – ein Wert, der angibt, ob [ignore alpha].
### setIgnoreAlpha(boolean value) {#setIgnoreAlpha-boolean-}
```
public final void setIgnoreAlpha(boolean value)
```


Legt einen Wert fest, der angibt, ob [ignore alpha].

Wert: `true`, wenn [ignore alpha]; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob [ignore alpha]. |

### getBordersProcessing() {#getBordersProcessing--}
```
public final boolean getBordersProcessing()
```


Ruft einen Wert ab, der angibt, ob [borders processing].

Wert: `true`, wenn [borders processing]; andernfalls `false`.

**Returns:**
boolean – ein Wert, der angibt, ob [borders processing].
### setBordersProcessing(boolean value) {#setBordersProcessing-boolean-}
```
public final void setBordersProcessing(boolean value)
```


Legt einen Wert fest, der angibt, ob [borders processing].

Wert: `true`, wenn [borders processing]; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob [borders processing]. |

