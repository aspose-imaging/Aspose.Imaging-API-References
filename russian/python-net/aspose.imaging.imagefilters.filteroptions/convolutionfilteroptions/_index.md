---
title: "Класс ConvolutionFilterOptions"
type: docs
weight: 60
url: /ru/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/
---

**Summary:** The convolution filter options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.ConvolutionFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ConvolutionFilterOptions(kernel)](#ConvolutionFilterOptions_kernel_1) | Создает новый экземпляр класса [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) с factor = 1 и bias = 0. |
| [ConvolutionFilterOptions(kernel, factor)](#ConvolutionFilterOptions_kernel_factor_2) | Создает новый экземпляр класса [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) с bias = 0. |
| [ConvolutionFilterOptions(kernel, factor, bias)](#ConvolutionFilterOptions_kernel_factor_bias_3) | Создает новый экземпляр класса [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bias | int | r/w | Получает или задает bias. |
| borders_processing | bool | r/w | Получает или задает значение, указывающее, включена ли [borders processing]. |
| factor | float | r/w | Получает или задает factor. |
| ignore_alpha | bool | r/w | Получает или задает значение, указывающее, включено ли [ignore alpha]. |
| kernel_data | float[] | r | Получает ядро. |


### Constructor: ConvolutionFilterOptions(kernel) {#ConvolutionFilterOptions_kernel_1}


```
 ConvolutionFilterOptions(kernel) 
```

Создает новый экземпляр класса [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) с factor = 1 и bias = 0.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| ядро | float[] | Сверточное ядро для направления по оси X. |

### Constructor: ConvolutionFilterOptions(kernel, factor) {#ConvolutionFilterOptions_kernel_factor_2}


```
 ConvolutionFilterOptions(kernel, factor) 
```

Создает новый экземпляр класса [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) с bias = 0.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| ядро | float[] | Сверточное ядро для направления по оси X. |
| factor | float | Фактор. |

### Constructor: ConvolutionFilterOptions(kernel, factor, bias) {#ConvolutionFilterOptions_kernel_factor_bias_3}


```
 ConvolutionFilterOptions(kernel, factor, bias) 
```

Создает новый экземпляр класса [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| ядро | float[] | Сверточное ядро для направления по оси X. |
| factor | float | Фактор. |
| bias | int | Значение bias. |

