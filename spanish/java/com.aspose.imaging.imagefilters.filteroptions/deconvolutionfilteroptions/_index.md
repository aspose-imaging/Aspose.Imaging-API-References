---
title: "DeconvolutionFilterOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Clase abstracta Deconvolution Filter Options"
type: docs
weight: 16
url: /es/java/com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.IComplexConvolutionKernel
```
public class DeconvolutionFilterOptions extends FilterOptionsBase implements IComplexConvolutionKernel
```

Opciones del filtro de deconvolución, clase abstracta
## Constructores

| Constructor | Descripción |
| --- | --- |
| [DeconvolutionFilterOptions(double[][] kernel)](#DeconvolutionFilterOptions-double-----) | Inicializa una nueva instancia de la clase [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions). |
| [DeconvolutionFilterOptions(Complex[][] kernel)](#DeconvolutionFilterOptions-com.aspose.imaging.imagefilters.complexutils.Complex-----) | Inicializa una nueva instancia de la clase [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getKernel()](#getKernel--) | Obtiene el kernel. |
| [getSnr()](#getSnr--) | Obtiene o establece la relación señal-ruido (SNR) rango recomendado 0.002 - 0.009, valor predeterminado = 0.007 |
| [setSnr(double value)](#setSnr-double-) | Obtiene o establece la relación señal-ruido (SNR) rango recomendado 0.002 - 0.009, valor predeterminado = 0.007 |
| [getBrightness()](#getBrightness--) | Obtiene o establece el brillo. |
| [setBrightness(double value)](#setBrightness-double-) | Obtiene o establece el brillo. |
| [getGrayscale()](#getGrayscale--) | Obtiene o establece un valor que indica si este `DeconvolutionFilterOptions` está en escala de grises. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Obtiene o establece un valor que indica si este `DeconvolutionFilterOptions` está en escala de grises. |
| [isPartialLoaded()](#isPartialLoaded--) | Obtiene un valor que indica si esta instancia está parcialmente cargada. |
### DeconvolutionFilterOptions(double[][] kernel) {#DeconvolutionFilterOptions-double-----}
```
public DeconvolutionFilterOptions(double[][] kernel)
```


Inicializa una nueva instancia de la clase [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| núcleo | double[][] | El núcleo. |

### DeconvolutionFilterOptions(Complex[][] kernel) {#DeconvolutionFilterOptions-com.aspose.imaging.imagefilters.complexutils.Complex-----}
```
public DeconvolutionFilterOptions(Complex[][] kernel)
```


Inicializa una nueva instancia de la clase [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| kernel | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | El núcleo. |

### getKernel() {#getKernel--}
```
public Complex[][] getKernel()
```


Obtiene el kernel.

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - el kernel.
### getSnr() {#getSnr--}
```
public double getSnr()
```


Obtiene o establece la relación señal-ruido (SNR) rango recomendado 0.002 - 0.009, valor predeterminado = 0.007

Valor: La SNR.

**Returns:**
double
### setSnr(double value) {#setSnr-double-}
```
public void setSnr(double value)
```


Obtiene o establece la relación señal-ruido (SNR) rango recomendado 0.002 - 0.009, valor predeterminado = 0.007

Valor: La SNR.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### getBrightness() {#getBrightness--}
```
public double getBrightness()
```


Obtiene o establece el brillo. rango recomendado 1 - 1.5 valor predeterminado = 1.15

Valor: El brillo.

**Returns:**
double
### setBrightness(double value) {#setBrightness-double-}
```
public void setBrightness(double value)
```


Obtiene o establece el brillo. rango recomendado 1 - 1.5 valor predeterminado = 1.15

Valor: El brillo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### getGrayscale() {#getGrayscale--}
```
public boolean getGrayscale()
```


Obtiene o establece un valor que indica si este `DeconvolutionFilterOptions` está en escala de grises. Devuelve modo de escala de grises o modo RGB.

Valor: `true` si es escala de grises; de lo contrario, `false`.

**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public void setGrayscale(boolean value)
```


Obtiene o establece un valor que indica si este `DeconvolutionFilterOptions` está en escala de grises. Devuelve modo de escala de grises o modo RGB.

Valor: `true` si es escala de grises; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### isPartialLoaded() {#isPartialLoaded--}
```
public boolean isPartialLoaded()
```


Obtiene un valor que indica si esta instancia está parcialmente cargada.

Valor: `true` si esta instancia está parcialmente cargada; de lo contrario, `false`.

**Returns:**
boolean
