---
title: "DeconvolutionFilterOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Classe abstraite Deconvolution Filter Options"
type: docs
weight: 16
url: /fr/java/com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.IComplexConvolutionKernel
```
public class DeconvolutionFilterOptions extends FilterOptionsBase implements IComplexConvolutionKernel
```

Options du filtre de déconvolution, classe abstraite
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DeconvolutionFilterOptions(double[][] kernel)](#DeconvolutionFilterOptions-double-----) | Initialise une nouvelle instance de la classe [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions). |
| [DeconvolutionFilterOptions(Complex[][] kernel)](#DeconvolutionFilterOptions-com.aspose.imaging.imagefilters.complexutils.Complex-----) | Initialise une nouvelle instance de la classe [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getKernel()](#getKernel--) | Obtient le noyau. |
| [getSnr()](#getSnr--) | Obtient ou définit le SNR(signal-to-noise ratio) plage recommandée 0.002 - 0.009, valeur par défaut = 0.007 |
| [setSnr(double value)](#setSnr-double-) | Obtient ou définit le SNR(signal-to-noise ratio) plage recommandée 0.002 - 0.009, valeur par défaut = 0.007 |
| [getBrightness()](#getBrightness--) | Obtient ou définit la luminosité. |
| [setBrightness(double value)](#setBrightness-double-) | Obtient ou définit la luminosité. |
| [getGrayscale()](#getGrayscale--) | Obtient ou définit une valeur indiquant si ce `DeconvolutionFilterOptions` est en niveaux de gris. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Obtient ou définit une valeur indiquant si ce `DeconvolutionFilterOptions` est en niveaux de gris. |
| [isPartialLoaded()](#isPartialLoaded--) | Obtient une valeur indiquant si cette instance est partiellement chargée. |
### DeconvolutionFilterOptions(double[][] kernel) {#DeconvolutionFilterOptions-double-----}
```
public DeconvolutionFilterOptions(double[][] kernel)
```


Initialise une nouvelle instance de la classe [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| noyau | double[][] | Le noyau. |

### DeconvolutionFilterOptions(Complex[][] kernel) {#DeconvolutionFilterOptions-com.aspose.imaging.imagefilters.complexutils.Complex-----}
```
public DeconvolutionFilterOptions(Complex[][] kernel)
```


Initialise une nouvelle instance de la classe [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| kernel | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Le noyau. |

### getKernel() {#getKernel--}
```
public Complex[][] getKernel()
```


Obtient le noyau.

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - le noyau.
### getSnr() {#getSnr--}
```
public double getSnr()
```


Obtient ou définit le SNR(signal-to-noise ratio) plage recommandée 0.002 - 0.009, valeur par défaut = 0.007

Valeur: le SNR.

**Returns:**
double
### setSnr(double value) {#setSnr-double-}
```
public void setSnr(double value)
```


Obtient ou définit le SNR(signal-to-noise ratio) plage recommandée 0.002 - 0.009, valeur par défaut = 0.007

Valeur: le SNR.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### getBrightness() {#getBrightness--}
```
public double getBrightness()
```


Obtient ou définit la luminosité. plage recommandée 1 - 1,5 valeur par défaut = 1,15.

Valeur: la luminosité.

**Returns:**
double
### setBrightness(double value) {#setBrightness-double-}
```
public void setBrightness(double value)
```


Obtient ou définit la luminosité. plage recommandée 1 - 1,5 valeur par défaut = 1,15.

Valeur: la luminosité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### getGrayscale() {#getGrayscale--}
```
public boolean getGrayscale()
```


Obtient ou définit une valeur indiquant si ce `DeconvolutionFilterOptions` est en niveaux de gris. Retourne le mode niveaux de gris ou le mode RVB.

Valeur: `true` si niveaux de gris; sinon, `false`.

**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public void setGrayscale(boolean value)
```


Obtient ou définit une valeur indiquant si ce `DeconvolutionFilterOptions` est en niveaux de gris. Retourne le mode niveaux de gris ou le mode RVB.

Valeur: `true` si niveaux de gris; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### isPartialLoaded() {#isPartialLoaded--}
```
public boolean isPartialLoaded()
```


Obtient une valeur indiquant si cette instance est partiellement chargée.

Valeur: `true` si cette instance est partiellement chargée; sinon, `false`.

**Returns:**
boolean
