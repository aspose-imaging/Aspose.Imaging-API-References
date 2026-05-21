---
title: "ConvolutionFilterOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Las opciones del filtro de convolución."
type: docs
weight: 15
url: /es/java/com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.IConvolutionKernel
```
public class ConvolutionFilterOptions extends FilterOptionsBase implements IConvolutionKernel
```

Las opciones del filtro de convolución.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ConvolutionFilterOptions(double[][] kernel)](#ConvolutionFilterOptions-double-----) | Inicializa una nueva instancia de la clase [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) con factor == 1 y sesgo == 0. |
| [ConvolutionFilterOptions(double[][] kernel, double factor)](#ConvolutionFilterOptions-double-----double-) | Inicializa una nueva instancia de la clase [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) con sesgo == 0. |
| [ConvolutionFilterOptions(double[][] kernel, double factor, int bias)](#ConvolutionFilterOptions-double-----double-int-) | Inicializa una nueva instancia de la clase [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getKernel()](#getKernel--) | Obtiene el kernel. |
| [getFactor()](#getFactor--) | Obtiene el factor. |
| [setFactor(double value)](#setFactor-double-) | Establece el factor. |
| [getBias()](#getBias--) | Obtiene el sesgo. |
| [setBias(int value)](#setBias-int-) | Establece el sesgo. |
| [getIgnoreAlpha()](#getIgnoreAlpha--) | Obtiene un valor que indica si [ignore alpha]. |
| [setIgnoreAlpha(boolean value)](#setIgnoreAlpha-boolean-) | Establece un valor que indica si [ignore alpha]. |
| [getBordersProcessing()](#getBordersProcessing--) | Obtiene un valor que indica si [borders processing]. |
| [setBordersProcessing(boolean value)](#setBordersProcessing-boolean-) | Establece un valor que indica si [borders processing]. |
### ConvolutionFilterOptions(double[][] kernel) {#ConvolutionFilterOptions-double-----}
```
public ConvolutionFilterOptions(double[][] kernel)
```


Inicializa una nueva instancia de la clase [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) con factor == 1 y sesgo == 0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| núcleo | double[][] | El núcleo de convolución para la dirección del eje X. |

### ConvolutionFilterOptions(double[][] kernel, double factor) {#ConvolutionFilterOptions-double-----double-}
```
public ConvolutionFilterOptions(double[][] kernel, double factor)
```


Inicializa una nueva instancia de la clase [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) con sesgo == 0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| núcleo | double[][] | El núcleo de convolución para la dirección del eje X. |
| factor | double | El factor. |

### ConvolutionFilterOptions(double[][] kernel, double factor, int bias) {#ConvolutionFilterOptions-double-----double-int-}
```
public ConvolutionFilterOptions(double[][] kernel, double factor, int bias)
```


Inicializa una nueva instancia de la clase [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| núcleo | double[][] | El núcleo de convolución para la dirección del eje X. |
| factor | double | El factor. |
| sesgo | int | El valor del sesgo. |

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


Obtiene el kernel.

**Returns:**
double[][] - el núcleo.
### getFactor() {#getFactor--}
```
public final double getFactor()
```


Obtiene el factor.

**Returns:**
double - el factor.
### setFactor(double value) {#setFactor-double-}
```
public final void setFactor(double value)
```


Establece el factor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | el factor. |

### getBias() {#getBias--}
```
public final int getBias()
```


Obtiene el sesgo.

Valor: El sesgo.

**Returns:**
int - el sesgo.
### setBias(int value) {#setBias-int-}
```
public final void setBias(int value)
```


Establece el sesgo.

Valor: El sesgo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el sesgo. |

### getIgnoreAlpha() {#getIgnoreAlpha--}
```
public final boolean getIgnoreAlpha()
```


Obtiene un valor que indica si [ignore alpha].

Valor: `true` si [ignore alpha]; de lo contrario, `false`.

**Returns:**
boolean - un valor que indica si [ignore alpha].
### setIgnoreAlpha(boolean value) {#setIgnoreAlpha-boolean-}
```
public final void setIgnoreAlpha(boolean value)
```


Establece un valor que indica si [ignore alpha].

Valor: `true` si [ignore alpha]; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si [ignore alpha]. |

### getBordersProcessing() {#getBordersProcessing--}
```
public final boolean getBordersProcessing()
```


Obtiene un valor que indica si [borders processing].

Valor: `true` si [borders processing]; de lo contrario, `false`.

**Returns:**
boolean - un valor que indica si [borders processing].
### setBordersProcessing(boolean value) {#setBordersProcessing-boolean-}
```
public final void setBordersProcessing(boolean value)
```


Establece un valor que indica si [borders processing].

Valor: `true` si [borders processing]; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si [borders processing]. |

