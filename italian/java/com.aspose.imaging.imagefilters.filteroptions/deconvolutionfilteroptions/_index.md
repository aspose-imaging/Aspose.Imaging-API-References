---
title: "DeconvolutionFilterOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Classe astratta Deconvolution Filter Options"
type: docs
weight: 16
url: /it/java/com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.IComplexConvolutionKernel
```
public class DeconvolutionFilterOptions extends FilterOptionsBase implements IComplexConvolutionKernel
```

Opzioni del filtro di deconvoluzione, classe astratta
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DeconvolutionFilterOptions(double[][] kernel)](#DeconvolutionFilterOptions-double-----) | Inizializza una nuova istanza della classe [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions). |
| [DeconvolutionFilterOptions(Complex[][] kernel)](#DeconvolutionFilterOptions-com.aspose.imaging.imagefilters.complexutils.Complex-----) | Inizializza una nuova istanza della classe [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getKernel()](#getKernel--) | Ottiene il kernel. |
| [getSnr()](#getSnr--) | Ottiene o imposta il SNR (rapporto segnale-rumore) intervallo consigliato 0.002 - 0.009, valore predefinito = 0.007 |
| [setSnr(double value)](#setSnr-double-) | Ottiene o imposta il SNR (rapporto segnale-rumore) intervallo consigliato 0.002 - 0.009, valore predefinito = 0.007 |
| [getBrightness()](#getBrightness--) | Ottiene o imposta la luminosità. |
| [setBrightness(double value)](#setBrightness-double-) | Ottiene o imposta la luminosità. |
| [getGrayscale()](#getGrayscale--) | Ottiene o imposta un valore che indica se questo `DeconvolutionFilterOptions` è in scala di grigi. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Ottiene o imposta un valore che indica se questo `DeconvolutionFilterOptions` è in scala di grigi. |
| [isPartialLoaded()](#isPartialLoaded--) | Ottiene un valore che indica se questa istanza è parzialmente caricata. |
### DeconvolutionFilterOptions(double[][] kernel) {#DeconvolutionFilterOptions-double-----}
```
public DeconvolutionFilterOptions(double[][] kernel)
```


Inizializza una nuova istanza della classe [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| kernel | double[][] | Il kernel. |

### DeconvolutionFilterOptions(Complex[][] kernel) {#DeconvolutionFilterOptions-com.aspose.imaging.imagefilters.complexutils.Complex-----}
```
public DeconvolutionFilterOptions(Complex[][] kernel)
```


Inizializza una nuova istanza della classe [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| kernel | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Il kernel. |

### getKernel() {#getKernel--}
```
public Complex[][] getKernel()
```


Ottiene il kernel.

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - il kernel.
### getSnr() {#getSnr--}
```
public double getSnr()
```


Ottiene o imposta il SNR (rapporto segnale-rumore) intervallo consigliato 0.002 - 0.009, valore predefinito = 0.007

Valore: L'SNR.

**Returns:**
double
### setSnr(double value) {#setSnr-double-}
```
public void setSnr(double value)
```


Ottiene o imposta il SNR (rapporto segnale-rumore) intervallo consigliato 0.002 - 0.009, valore predefinito = 0.007

Valore: L'SNR.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### getBrightness() {#getBrightness--}
```
public double getBrightness()
```


Ottiene o imposta la luminosità. intervallo consigliato 1 - 1.5 valore predefinito = 1.15

Valore: La luminosità.

**Returns:**
double
### setBrightness(double value) {#setBrightness-double-}
```
public void setBrightness(double value)
```


Ottiene o imposta la luminosità. intervallo consigliato 1 - 1.5 valore predefinito = 1.15

Valore: La luminosità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### getGrayscale() {#getGrayscale--}
```
public boolean getGrayscale()
```


Ottiene o imposta un valore che indica se questo `DeconvolutionFilterOptions` è in scala di grigi. Restituisce la modalità scala di grigi o la modalità RGB.

Valore: `true` se scala di grigi; altrimenti, `false`.

**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public void setGrayscale(boolean value)
```


Ottiene o imposta un valore che indica se questo `DeconvolutionFilterOptions` è in scala di grigi. Restituisce la modalità scala di grigi o la modalità RGB.

Valore: `true` se scala di grigi; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### isPartialLoaded() {#isPartialLoaded--}
```
public boolean isPartialLoaded()
```


Ottiene un valore che indica se questa istanza è parzialmente caricata.

Valore: `true` se questa istanza è parzialmente caricata; altrimenti, `false`.

**Returns:**
boolean
