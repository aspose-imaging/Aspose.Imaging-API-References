---
title: "ConvolutionFilterOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Le opzioni del filtro di convoluzione."
type: docs
weight: 15
url: /it/java/com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.IConvolutionKernel
```
public class ConvolutionFilterOptions extends FilterOptionsBase implements IConvolutionKernel
```

Le opzioni del filtro di convoluzione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ConvolutionFilterOptions(double[][] kernel)](#ConvolutionFilterOptions-double-----) | Inizializza una nuova istanza della classe [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) con factor == 1 e bias == 0. |
| [ConvolutionFilterOptions(double[][] kernel, double factor)](#ConvolutionFilterOptions-double-----double-) | Inizializza una nuova istanza della classe [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) con bias == 0. |
| [ConvolutionFilterOptions(double[][] kernel, double factor, int bias)](#ConvolutionFilterOptions-double-----double-int-) | Inizializza una nuova istanza della classe [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getKernel()](#getKernel--) | Ottiene il kernel. |
| [getFactor()](#getFactor--) | Ottiene il fattore. |
| [setFactor(double value)](#setFactor-double-) | Imposta il fattore. |
| [getBias()](#getBias--) | Ottiene il bias. |
| [setBias(int value)](#setBias-int-) | Imposta il bias. |
| [getIgnoreAlpha()](#getIgnoreAlpha--) | Ottiene un valore che indica se [ignore alpha]. |
| [setIgnoreAlpha(boolean value)](#setIgnoreAlpha-boolean-) | Imposta un valore che indica se [ignore alpha]. |
| [getBordersProcessing()](#getBordersProcessing--) | Ottiene un valore che indica se [borders processing]. |
| [setBordersProcessing(boolean value)](#setBordersProcessing-boolean-) | Imposta un valore che indica se [borders processing]. |
### ConvolutionFilterOptions(double[][] kernel) {#ConvolutionFilterOptions-double-----}
```
public ConvolutionFilterOptions(double[][] kernel)
```


Inizializza una nuova istanza della classe [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) con factor == 1 e bias == 0.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| kernel | double[][] | Il kernel di convoluzione per la direzione dell'asse X. |

### ConvolutionFilterOptions(double[][] kernel, double factor) {#ConvolutionFilterOptions-double-----double-}
```
public ConvolutionFilterOptions(double[][] kernel, double factor)
```


Inizializza una nuova istanza della classe [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) con bias == 0.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| kernel | double[][] | Il kernel di convoluzione per la direzione dell'asse X. |
| fattore | double | Il fattore. |

### ConvolutionFilterOptions(double[][] kernel, double factor, int bias) {#ConvolutionFilterOptions-double-----double-int-}
```
public ConvolutionFilterOptions(double[][] kernel, double factor, int bias)
```


Inizializza una nuova istanza della classe [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| kernel | double[][] | Il kernel di convoluzione per la direzione dell'asse X. |
| fattore | double | Il fattore. |
| bias | int | Il valore del bias. |

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


Ottiene il kernel.

**Returns:**
double[][] - il kernel.
### getFactor() {#getFactor--}
```
public final double getFactor()
```


Ottiene il fattore.

**Returns:**
double - il fattore.
### setFactor(double value) {#setFactor-double-}
```
public final void setFactor(double value)
```


Imposta il fattore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | il fattore. |

### getBias() {#getBias--}
```
public final int getBias()
```


Ottiene il bias.

Valore: Il bias.

**Returns:**
int - il bias.
### setBias(int value) {#setBias-int-}
```
public final void setBias(int value)
```


Imposta il bias.

Valore: Il bias.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il bias. |

### getIgnoreAlpha() {#getIgnoreAlpha--}
```
public final boolean getIgnoreAlpha()
```


Ottiene un valore che indica se [ignore alpha].

Valore: `true` se [ignore alpha]; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se [ignore alpha].
### setIgnoreAlpha(boolean value) {#setIgnoreAlpha-boolean-}
```
public final void setIgnoreAlpha(boolean value)
```


Imposta un valore che indica se [ignore alpha].

Valore: `true` se [ignore alpha]; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se [ignore alpha]. |

### getBordersProcessing() {#getBordersProcessing--}
```
public final boolean getBordersProcessing()
```


Ottiene un valore che indica se [borders processing].

Valore: `true` se [borders processing]; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se [borders processing].
### setBordersProcessing(boolean value) {#setBordersProcessing-boolean-}
```
public final void setBordersProcessing(boolean value)
```


Imposta un valore che indica se [borders processing].

Valore: `true` se [borders processing]; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se [borders processing]. |

