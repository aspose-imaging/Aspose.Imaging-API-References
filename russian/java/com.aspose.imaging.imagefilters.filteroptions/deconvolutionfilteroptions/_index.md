---
title: "DeconvolutionFilterOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Абстрактный класс Deconvolution Filter Options"
type: docs
weight: 16
url: /ru/java/com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.IComplexConvolutionKernel
```
public class DeconvolutionFilterOptions extends FilterOptionsBase implements IComplexConvolutionKernel
```

Параметры фильтра деконволюции, абстрактный класс
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DeconvolutionFilterOptions(double[][] kernel)](#DeconvolutionFilterOptions-double-----) | Инициализирует новый экземпляр класса [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions). |
| [DeconvolutionFilterOptions(Complex[][] kernel)](#DeconvolutionFilterOptions-com.aspose.imaging.imagefilters.complexutils.Complex-----) | Инициализирует новый экземпляр класса [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getKernel()](#getKernel--) | Возвращает ядро. |
| [getSnr()](#getSnr--) | Получает или задает SNR (отношение сигнал/шум) рекомендуемый диапазон 0.002 - 0.009, значение по умолчанию = 0.007 |
| [setSnr(double value)](#setSnr-double-) | Получает или задает SNR (отношение сигнал/шум) рекомендуемый диапазон 0.002 - 0.009, значение по умолчанию = 0.007 |
| [getBrightness()](#getBrightness--) | Получает или задает яркость. |
| [setBrightness(double value)](#setBrightness-double-) | Получает или задает яркость. |
| [getGrayscale()](#getGrayscale--) | Получает или задает значение, указывающее, является ли этот `DeconvolutionFilterOptions` в градациях серого. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Получает или задает значение, указывающее, является ли этот `DeconvolutionFilterOptions` в градациях серого. |
| [isPartialLoaded()](#isPartialLoaded--) | Получает значение, указывающее, загружен ли этот экземпляр частично. |
### DeconvolutionFilterOptions(double[][] kernel) {#DeconvolutionFilterOptions-double-----}
```
public DeconvolutionFilterOptions(double[][] kernel)
```


Инициализирует новый экземпляр класса [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ядро | double[][] | Ядро. |

### DeconvolutionFilterOptions(Complex[][] kernel) {#DeconvolutionFilterOptions-com.aspose.imaging.imagefilters.complexutils.Complex-----}
```
public DeconvolutionFilterOptions(Complex[][] kernel)
```


Инициализирует новый экземпляр класса [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| kernel | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Ядро. |

### getKernel() {#getKernel--}
```
public Complex[][] getKernel()
```


Возвращает ядро.

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - ядро.
### getSnr() {#getSnr--}
```
public double getSnr()
```


Получает или задает SNR (отношение сигнал/шум) рекомендуемый диапазон 0.002 - 0.009, значение по умолчанию = 0.007

Значение: SNR.

**Returns:**
double
### setSnr(double value) {#setSnr-double-}
```
public void setSnr(double value)
```


Получает или задает SNR (отношение сигнал/шум) рекомендуемый диапазон 0.002 - 0.009, значение по умолчанию = 0.007

Значение: SNR.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getBrightness() {#getBrightness--}
```
public double getBrightness()
```


Получает или задает яркость. рекомендуемый диапазон 1 - 1.5 значение по умолчанию = 1.15

Значение: яркость.

**Returns:**
double
### setBrightness(double value) {#setBrightness-double-}
```
public void setBrightness(double value)
```


Получает или задает яркость. рекомендуемый диапазон 1 - 1.5 значение по умолчанию = 1.15

Значение: яркость.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getGrayscale() {#getGrayscale--}
```
public boolean getGrayscale()
```


Получает или задает значение, указывающее, является ли этот `DeconvolutionFilterOptions` градацией серого. Возвращает режим градации серого или режим RGB.

Значение: `true`, если градация серого; иначе `false`.

**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public void setGrayscale(boolean value)
```


Получает или задает значение, указывающее, является ли этот `DeconvolutionFilterOptions` градацией серого. Возвращает режим градации серого или режим RGB.

Значение: `true`, если градация серого; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### isPartialLoaded() {#isPartialLoaded--}
```
public boolean isPartialLoaded()
```


Получает значение, указывающее, загружен ли этот экземпляр частично.

Значение: `true`, если этот экземпляр частично загружен; иначе `false`.

**Returns:**
boolean
