---
title: "GaussianDeconvolutionFilterOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Параметры фильтра деконволюции с использованием гауссового размытия."
type: docs
weight: 20
url: /ru/java/com.aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.gaussianblur.IGaussianBlurOptions
```
public abstract class GaussianDeconvolutionFilterOptions extends DeconvolutionFilterOptions implements IGaussianBlurOptions
```

Параметры фильтра деконволюции с использованием гауссового размытия.
## Методы

| Метод | Описание |
| --- | --- |
| [getSize()](#getSize--) | Получает размер гауссовского ядра. |
| [setSize(int value)](#setSize-int-) | Размер ядра Гаусса. |
| [getSigma()](#getSigma--) | Получает сигму (сглаживание) гауссовского ядра. |
| [setSigma(double value)](#setSigma-double-) | Сигма гауссовского ядра (сглаживание). |
| [getRadius()](#getRadius--) | Получает радиус Gausseian ISquareConvolutionKernel. |
| [setRadius(int value)](#setRadius-int-) | Радиус Gausseian ISquareConvolutionKernel. |
### getSize() {#getSize--}
```
public final int getSize()
```


Получает размер гауссовского ядра. Должно быть положительным не нулевым нечётным значением.

**Returns:**
int - размер гауссовского ядра.
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Размер гауссовского ядра. Должно быть положительным не нулевым нечётным значением.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | размер гауссовского ядра. |

### getSigma() {#getSigma--}
```
public final double getSigma()
```


Получает сигму гауссовского ядра (сглаживание). Должно быть положительным не нулевым значением.

**Returns:**
double - сигма гауссовского ядра (сглаживание).
### setSigma(double value) {#setSigma-double-}
```
public final void setSigma(double value)
```


Сигма гауссовского ядра (сглаживание). Должно быть положительным не нулевым значением.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | сигма гауссовского ядра (сглаживание). |

### getRadius() {#getRadius--}
```
public final int getRadius()
```


Получает радиус Gausseian ISquareConvolutionKernel.

**Returns:**
int — радиус Gausseian ISquareConvolutionKernel.
### setRadius(int value) {#setRadius-int-}
```
public final void setRadius(int value)
```


Радиус Gausseian ISquareConvolutionKernel.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | радиус Gausseian ISquareConvolutionKernel. |

