---
title: "ConvolutionFilterOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les options du filtre de convolution."
type: docs
weight: 15
url: /fr/java/com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.IConvolutionKernel
```
public class ConvolutionFilterOptions extends FilterOptionsBase implements IConvolutionKernel
```

Les options du filtre de convolution.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ConvolutionFilterOptions(double[][] kernel)](#ConvolutionFilterOptions-double-----) | Initialise une nouvelle instance de la classe [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) avec factor == 1 et bias == 0. |
| [ConvolutionFilterOptions(double[][] kernel, double factor)](#ConvolutionFilterOptions-double-----double-) | Initialise une nouvelle instance de la classe [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) avec bias == 0. |
| [ConvolutionFilterOptions(double[][] kernel, double factor, int bias)](#ConvolutionFilterOptions-double-----double-int-) | Initialise une nouvelle instance de la classe [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getKernel()](#getKernel--) | Obtient le noyau. |
| [getFactor()](#getFactor--) | Obtient le facteur. |
| [setFactor(double value)](#setFactor-double-) | Définit le facteur. |
| [getBias()](#getBias--) | Obtient le biais. |
| [setBias(int value)](#setBias-int-) | Définit le biais. |
| [getIgnoreAlpha()](#getIgnoreAlpha--) | Obtient une valeur indiquant si [ignore alpha]. |
| [setIgnoreAlpha(boolean value)](#setIgnoreAlpha-boolean-) | Définit une valeur indiquant si [ignore alpha]. |
| [getBordersProcessing()](#getBordersProcessing--) | Obtient une valeur indiquant si [borders processing]. |
| [setBordersProcessing(boolean value)](#setBordersProcessing-boolean-) | Définit une valeur indiquant si [borders processing]. |
### ConvolutionFilterOptions(double[][] kernel) {#ConvolutionFilterOptions-double-----}
```
public ConvolutionFilterOptions(double[][] kernel)
```


Initialise une nouvelle instance de la classe [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) avec factor == 1 et bias == 0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| noyau | double[][] | Le noyau de convolution pour la direction de l'axe X. |

### ConvolutionFilterOptions(double[][] kernel, double factor) {#ConvolutionFilterOptions-double-----double-}
```
public ConvolutionFilterOptions(double[][] kernel, double factor)
```


Initialise une nouvelle instance de la classe [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) avec bias == 0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| noyau | double[][] | Le noyau de convolution pour la direction de l'axe X. |
| facteur | double | Le facteur. |

### ConvolutionFilterOptions(double[][] kernel, double factor, int bias) {#ConvolutionFilterOptions-double-----double-int-}
```
public ConvolutionFilterOptions(double[][] kernel, double factor, int bias)
```


Initialise une nouvelle instance de la classe [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| noyau | double[][] | Le noyau de convolution pour la direction de l'axe X. |
| facteur | double | Le facteur. |
| biais | int | La valeur du biais. |

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


Obtient le noyau.

**Returns:**
double[][] - le noyau.
### getFactor() {#getFactor--}
```
public final double getFactor()
```


Obtient le facteur.

**Returns:**
double - le facteur.
### setFactor(double value) {#setFactor-double-}
```
public final void setFactor(double value)
```


Définit le facteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | le facteur. |

### getBias() {#getBias--}
```
public final int getBias()
```


Obtient le biais.

Valeur: le biais.

**Returns:**
int - le biais.
### setBias(int value) {#setBias-int-}
```
public final void setBias(int value)
```


Définit le biais.

Valeur: le biais.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le biais. |

### getIgnoreAlpha() {#getIgnoreAlpha--}
```
public final boolean getIgnoreAlpha()
```


Obtient une valeur indiquant si [ignore alpha].

Valeur: `true` si [ignore alpha]; sinon, `false`.

**Returns:**
boolean - une valeur indiquant si [ignore alpha].
### setIgnoreAlpha(boolean value) {#setIgnoreAlpha-boolean-}
```
public final void setIgnoreAlpha(boolean value)
```


Définit une valeur indiquant si [ignore alpha].

Valeur: `true` si [ignore alpha]; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si [ignore alpha]. |

### getBordersProcessing() {#getBordersProcessing--}
```
public final boolean getBordersProcessing()
```


Obtient une valeur indiquant si [borders processing].

Valeur: `true` si [borders processing]; sinon, `false`.

**Returns:**
boolean - une valeur indiquant si [borders processing].
### setBordersProcessing(boolean value) {#setBordersProcessing-boolean-}
```
public final void setBordersProcessing(boolean value)
```


Définit une valeur indiquant si [borders processing].

Valeur: `true` si [borders processing]; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si [borders processing]. |

