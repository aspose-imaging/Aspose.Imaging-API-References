---
title: "ConvolutionFilterOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Konvolutionsfilteralternativen."
type: docs
weight: 15
url: /sv/java/com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.IConvolutionKernel
```
public class ConvolutionFilterOptions extends FilterOptionsBase implements IConvolutionKernel
```

Konvolutionsfilteralternativen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ConvolutionFilterOptions(double[][] kernel)](#ConvolutionFilterOptions-double-----) | Initierar en ny instans av klassen [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) klass med faktor == 1 och bias == 0. |
| [ConvolutionFilterOptions(double[][] kernel, double factor)](#ConvolutionFilterOptions-double-----double-) | Initierar en ny instans av klassen [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) klass med bias == 0. |
| [ConvolutionFilterOptions(double[][] kernel, double factor, int bias)](#ConvolutionFilterOptions-double-----double-int-) | Initierar en ny instans av klassen [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) klass. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getKernel()](#getKernel--) | Hämtar kärnan. |
| [getFactor()](#getFactor--) | Hämtar faktorn. |
| [setFactor(double value)](#setFactor-double-) | Ställer in faktorn. |
| [getBias()](#getBias--) | Hämtar bias. |
| [setBias(int value)](#setBias-int-) | Ställer in bias. |
| [getIgnoreAlpha()](#getIgnoreAlpha--) | Hämtar ett värde som indikerar om [ignore alpha]. |
| [setIgnoreAlpha(boolean value)](#setIgnoreAlpha-boolean-) | Ställer in ett värde som indikerar om [ignore alpha]. |
| [getBordersProcessing()](#getBordersProcessing--) | Hämtar ett värde som indikerar om [borders processing]. |
| [setBordersProcessing(boolean value)](#setBordersProcessing-boolean-) | Ställer in ett värde som indikerar om [borders processing]. |
### ConvolutionFilterOptions(double[][] kernel) {#ConvolutionFilterOptions-double-----}
```
public ConvolutionFilterOptions(double[][] kernel)
```


Initierar en ny instans av klassen [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) klass med faktor == 1 och bias == 0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| kärna | double[][] | Konvolutionskärnan för X‑axelns riktning. |

### ConvolutionFilterOptions(double[][] kernel, double factor) {#ConvolutionFilterOptions-double-----double-}
```
public ConvolutionFilterOptions(double[][] kernel, double factor)
```


Initierar en ny instans av klassen [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) klass med bias == 0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| kärna | double[][] | Konvolutionskärnan för X‑axelns riktning. |
| faktor | double | Faktorn. |

### ConvolutionFilterOptions(double[][] kernel, double factor, int bias) {#ConvolutionFilterOptions-double-----double-int-}
```
public ConvolutionFilterOptions(double[][] kernel, double factor, int bias)
```


Initierar en ny instans av klassen [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) klass.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| kärna | double[][] | Konvolutionskärnan för X‑axelns riktning. |
| faktor | double | Faktorn. |
| bias | int | Biasvärdet. |

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


Hämtar kärnan.

**Returns:**
double[][] - kärnan.
### getFactor() {#getFactor--}
```
public final double getFactor()
```


Hämtar faktorn.

**Returns:**
double - faktorn.
### setFactor(double value) {#setFactor-double-}
```
public final void setFactor(double value)
```


Ställer in faktorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | faktorn. |

### getBias() {#getBias--}
```
public final int getBias()
```


Hämtar bias.

Värde: Biasen.

**Returns:**
int - biasen.
### setBias(int value) {#setBias-int-}
```
public final void setBias(int value)
```


Ställer in bias.

Värde: Biasen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | biasen. |

### getIgnoreAlpha() {#getIgnoreAlpha--}
```
public final boolean getIgnoreAlpha()
```


Hämtar ett värde som indikerar om [ignore alpha].

Värde: `true` om [ignore alpha]; annars, `false`.

**Returns:**
boolean - ett värde som indikerar om [ignore alpha].
### setIgnoreAlpha(boolean value) {#setIgnoreAlpha-boolean-}
```
public final void setIgnoreAlpha(boolean value)
```


Ställer in ett värde som indikerar om [ignore alpha].

Värde: `true` om [ignore alpha]; annars, `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om [ignore alpha]. |

### getBordersProcessing() {#getBordersProcessing--}
```
public final boolean getBordersProcessing()
```


Hämtar ett värde som indikerar om [borders processing].

Värde: `true` om [borders processing]; annars, `false`.

**Returns:**
boolean - ett värde som indikerar om [borders processing].
### setBordersProcessing(boolean value) {#setBordersProcessing-boolean-}
```
public final void setBordersProcessing(boolean value)
```


Ställer in ett värde som indikerar om [borders processing].

Värde: `true` om [borders processing]; annars, `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om [borders processing]. |

