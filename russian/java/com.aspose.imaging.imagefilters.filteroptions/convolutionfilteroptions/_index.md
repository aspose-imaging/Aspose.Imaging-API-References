---
title: "ConvolutionFilterOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Параметры свёрточного фильтра."
type: docs
weight: 15
url: /ru/java/com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.IConvolutionKernel
```
public class ConvolutionFilterOptions extends FilterOptionsBase implements IConvolutionKernel
```

Параметры свёрточного фильтра.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ConvolutionFilterOptions(double[][] kernel)](#ConvolutionFilterOptions-double-----) | Инициализирует новый экземпляр класса [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) с factor == 1 и bias == 0. |
| [ConvolutionFilterOptions(double[][] kernel, double factor)](#ConvolutionFilterOptions-double-----double-) | Инициализирует новый экземпляр класса [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) с bias == 0. |
| [ConvolutionFilterOptions(double[][] kernel, double factor, int bias)](#ConvolutionFilterOptions-double-----double-int-) | Инициализирует новый экземпляр класса [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getKernel()](#getKernel--) | Возвращает ядро. |
| [getFactor()](#getFactor--) | Возвращает фактор. |
| [setFactor(double value)](#setFactor-double-) | Устанавливает фактор. |
| [getBias()](#getBias--) | Возвращает bias. |
| [setBias(int value)](#setBias-int-) | Устанавливает bias. |
| [getIgnoreAlpha()](#getIgnoreAlpha--) | Возвращает значение, указывающее, [ignore alpha]. |
| [setIgnoreAlpha(boolean value)](#setIgnoreAlpha-boolean-) | Устанавливает значение, указывающее, [ignore alpha]. |
| [getBordersProcessing()](#getBordersProcessing--) | Возвращает значение, указывающее, [borders processing]. |
| [setBordersProcessing(boolean value)](#setBordersProcessing-boolean-) | Устанавливает значение, указывающее, [borders processing]. |
### ConvolutionFilterOptions(double[][] kernel) {#ConvolutionFilterOptions-double-----}
```
public ConvolutionFilterOptions(double[][] kernel)
```


Инициализирует новый экземпляр класса [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) с factor == 1 и bias == 0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ядро | double[][] | Сверточное ядро для направления по оси X. |

### ConvolutionFilterOptions(double[][] kernel, double factor) {#ConvolutionFilterOptions-double-----double-}
```
public ConvolutionFilterOptions(double[][] kernel, double factor)
```


Инициализирует новый экземпляр класса [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) с bias == 0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ядро | double[][] | Сверточное ядро для направления по оси X. |
| коэффициент | double | Коэффициент. |

### ConvolutionFilterOptions(double[][] kernel, double factor, int bias) {#ConvolutionFilterOptions-double-----double-int-}
```
public ConvolutionFilterOptions(double[][] kernel, double factor, int bias)
```


Инициализирует новый экземпляр класса [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ядро | double[][] | Сверточное ядро для направления по оси X. |
| коэффициент | double | Коэффициент. |
| смещение | int | Значение смещения. |

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


Возвращает ядро.

**Returns:**
double[][] - ядро.
### getFactor() {#getFactor--}
```
public final double getFactor()
```


Возвращает фактор.

**Returns:**
double - коэффициент.
### setFactor(double value) {#setFactor-double-}
```
public final void setFactor(double value)
```


Устанавливает фактор.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | коэффициент. |

### getBias() {#getBias--}
```
public final int getBias()
```


Возвращает bias.

Значение: Смещение.

**Returns:**
int - смещение.
### setBias(int value) {#setBias-int-}
```
public final void setBias(int value)
```


Устанавливает bias.

Значение: Смещение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | смещение. |

### getIgnoreAlpha() {#getIgnoreAlpha--}
```
public final boolean getIgnoreAlpha()
```


Возвращает значение, указывающее, [ignore alpha].

Значение: `true`, если [ignore alpha]; иначе `false`.

**Returns:**
boolean - значение, указывающее, включено ли [ignore alpha].
### setIgnoreAlpha(boolean value) {#setIgnoreAlpha-boolean-}
```
public final void setIgnoreAlpha(boolean value)
```


Устанавливает значение, указывающее, [ignore alpha].

Значение: `true`, если [ignore alpha]; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, включено ли [ignore alpha]. |

### getBordersProcessing() {#getBordersProcessing--}
```
public final boolean getBordersProcessing()
```


Возвращает значение, указывающее, [borders processing].

Значение: `true`, если [borders processing]; иначе `false`.

**Returns:**
boolean - значение, указывающее, включено ли [borders processing].
### setBordersProcessing(boolean value) {#setBordersProcessing-boolean-}
```
public final void setBordersProcessing(boolean value)
```


Устанавливает значение, указывающее, [borders processing].

Значение: `true`, если [borders processing]; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, включено ли [borders processing]. |

