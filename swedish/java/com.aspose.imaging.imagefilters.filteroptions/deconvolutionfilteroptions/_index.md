---
title: "DeconvolutionFilterOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Abstrakt klass för Deconvolution Filter Options"
type: docs
weight: 16
url: /sv/java/com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.IComplexConvolutionKernel
```
public class DeconvolutionFilterOptions extends FilterOptionsBase implements IComplexConvolutionKernel
```

Deconvolution Filter Options, abstrakt klass
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [DeconvolutionFilterOptions(double[][] kernel)](#DeconvolutionFilterOptions-double-----) | Initierar en ny instans av klassen [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions). |
| [DeconvolutionFilterOptions(Complex[][] kernel)](#DeconvolutionFilterOptions-com.aspose.imaging.imagefilters.complexutils.Complex-----) | Initierar en ny instans av klassen [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getKernel()](#getKernel--) | Hämtar kärnan. |
| [getSnr()](#getSnr--) | Hämtar eller anger SNR (signal‑till‑brus‑förhållande) rekommenderat intervall 0,002 - 0,009, standardvärde = 0,007 |
| [setSnr(double value)](#setSnr-double-) | Hämtar eller anger SNR (signal‑till‑brus‑förhållande) rekommenderat intervall 0,002 - 0,009, standardvärde = 0,007 |
| [getBrightness()](#getBrightness--) | Hämtar eller anger ljusstyrkan. |
| [setBrightness(double value)](#setBrightness-double-) | Hämtar eller anger ljusstyrkan. |
| [getGrayscale()](#getGrayscale--) | Hämtar eller anger ett värde som indikerar om detta `DeconvolutionFilterOptions` är i gråskala. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Hämtar eller anger ett värde som indikerar om detta `DeconvolutionFilterOptions` är i gråskala. |
| [isPartialLoaded()](#isPartialLoaded--) | Hämtar ett värde som indikerar om denna instans är delvis inläst. |
### DeconvolutionFilterOptions(double[][] kernel) {#DeconvolutionFilterOptions-double-----}
```
public DeconvolutionFilterOptions(double[][] kernel)
```


Initierar en ny instans av klassen [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| kärna | double[][] | Kärnan. |

### DeconvolutionFilterOptions(Complex[][] kernel) {#DeconvolutionFilterOptions-com.aspose.imaging.imagefilters.complexutils.Complex-----}
```
public DeconvolutionFilterOptions(Complex[][] kernel)
```


Initierar en ny instans av klassen [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| kernel | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Kärnan. |

### getKernel() {#getKernel--}
```
public Complex[][] getKernel()
```


Hämtar kärnan.

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - kärnan.
### getSnr() {#getSnr--}
```
public double getSnr()
```


Hämtar eller anger SNR (signal‑till‑brus‑förhållande) rekommenderat intervall 0,002 - 0,009, standardvärde = 0,007

Värde: SNR.

**Returns:**
double
### setSnr(double value) {#setSnr-double-}
```
public void setSnr(double value)
```


Hämtar eller anger SNR (signal‑till‑brus‑förhållande) rekommenderat intervall 0,002 - 0,009, standardvärde = 0,007

Värde: SNR.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### getBrightness() {#getBrightness--}
```
public double getBrightness()
```


Hämtar eller anger ljusstyrkan. rekommenderat intervall 1 - 1.5 standardvärde = 1.15

Värde: ljusstyrkan.

**Returns:**
double
### setBrightness(double value) {#setBrightness-double-}
```
public void setBrightness(double value)
```


Hämtar eller anger ljusstyrkan. rekommenderat intervall 1 - 1.5 standardvärde = 1.15

Värde: ljusstyrkan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### getGrayscale() {#getGrayscale--}
```
public boolean getGrayscale()
```


Hämtar eller anger ett värde som indikerar om detta `DeconvolutionFilterOptions` är gråskala. Returnerar gråskalaläge eller RGB-läge.

Värde: `true` om gråskala; annars `false`.

**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public void setGrayscale(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta `DeconvolutionFilterOptions` är gråskala. Returnerar gråskalaläge eller RGB-läge.

Värde: `true` om gråskala; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### isPartialLoaded() {#isPartialLoaded--}
```
public boolean isPartialLoaded()
```


Hämtar ett värde som indikerar om denna instans är delvis inläst.

Värde: `true` om detta objekt är delvis inläst; annars `false`.

**Returns:**
boolean
