---
title: "DeconvolutionFilterOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Deconvolution Filter Options abstrakte Klasse"
type: docs
weight: 16
url: /de/java/com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.IComplexConvolutionKernel
```
public class DeconvolutionFilterOptions extends FilterOptionsBase implements IComplexConvolutionKernel
```

Deconvolution-Filteroptionen, abstrakte Klasse
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DeconvolutionFilterOptions(double[][] kernel)](#DeconvolutionFilterOptions-double-----) | Initialisiert eine neue Instanz der [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions)-Klasse. |
| [DeconvolutionFilterOptions(Complex[][] kernel)](#DeconvolutionFilterOptions-com.aspose.imaging.imagefilters.complexutils.Complex-----) | Initialisiert eine neue Instanz der [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions)-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getKernel()](#getKernel--) | Ruft den Kernel ab. |
| [getSnr()](#getSnr--) | Liest oder setzt das SNR (Signal‑zu‑Rausch‑Verhältnis) empfohlener Bereich 0,002 - 0,009, Standardwert = 0,007 |
| [setSnr(double value)](#setSnr-double-) | Liest oder setzt das SNR (Signal‑zu‑Rausch‑Verhältnis) empfohlener Bereich 0,002 - 0,009, Standardwert = 0,007 |
| [getBrightness()](#getBrightness--) | Liest oder setzt die Helligkeit. |
| [setBrightness(double value)](#setBrightness-double-) | Liest oder setzt die Helligkeit. |
| [getGrayscale()](#getGrayscale--) | Liest oder setzt einen Wert, der angibt, ob diese `DeconvolutionFilterOptions` Graustufen ist. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese `DeconvolutionFilterOptions` Graustufen ist. |
| [isPartialLoaded()](#isPartialLoaded--) | Liest einen Wert, der angibt, ob diese Instanz teilweise geladen ist. |
### DeconvolutionFilterOptions(double[][] kernel) {#DeconvolutionFilterOptions-double-----}
```
public DeconvolutionFilterOptions(double[][] kernel)
```


Initialisiert eine neue Instanz der [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions)-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Kernel | double[][] | Der Kernel. |

### DeconvolutionFilterOptions(Complex[][] kernel) {#DeconvolutionFilterOptions-com.aspose.imaging.imagefilters.complexutils.Complex-----}
```
public DeconvolutionFilterOptions(Complex[][] kernel)
```


Initialisiert eine neue Instanz der [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions)-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| kernel | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Der Kernel. |

### getKernel() {#getKernel--}
```
public Complex[][] getKernel()
```


Ruft den Kernel ab.

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - der Kernel.
### getSnr() {#getSnr--}
```
public double getSnr()
```


Liest oder setzt das SNR (Signal‑zu‑Rausch‑Verhältnis) empfohlener Bereich 0,002 - 0,009, Standardwert = 0,007

Wert: Der SNR.

**Returns:**
double
### setSnr(double value) {#setSnr-double-}
```
public void setSnr(double value)
```


Liest oder setzt das SNR (Signal‑zu‑Rausch‑Verhältnis) empfohlener Bereich 0,002 - 0,009, Standardwert = 0,007

Wert: Der SNR.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getBrightness() {#getBrightness--}
```
public double getBrightness()
```


Liest oder setzt die Helligkeit. empfohlener Bereich 1 - 1,5 Standardwert = 1,15

Wert: Die Helligkeit.

**Returns:**
double
### setBrightness(double value) {#setBrightness-double-}
```
public void setBrightness(double value)
```


Liest oder setzt die Helligkeit. empfohlener Bereich 1 - 1,5 Standardwert = 1,15

Wert: Die Helligkeit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getGrayscale() {#getGrayscale--}
```
public boolean getGrayscale()
```


Liest oder setzt einen Wert, der angibt, ob diese `DeconvolutionFilterOptions` Graustufen ist. Gibt den Graustufenmodus oder den RGB‑Modus zurück.

Wert: `true`, wenn Graustufen; andernfalls `false`.

**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public void setGrayscale(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese `DeconvolutionFilterOptions` Graustufen ist. Gibt den Graustufenmodus oder den RGB‑Modus zurück.

Wert: `true`, wenn Graustufen; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### isPartialLoaded() {#isPartialLoaded--}
```
public boolean isPartialLoaded()
```


Liest einen Wert, der angibt, ob diese Instanz teilweise geladen ist.

Wert: `true`, wenn diese Instanz teilweise geladen ist; andernfalls `false`.

**Returns:**
boolean
