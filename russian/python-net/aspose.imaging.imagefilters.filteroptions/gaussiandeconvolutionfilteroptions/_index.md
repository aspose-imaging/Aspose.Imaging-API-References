---
title: "Класс GaussianDeconvolutionFilterOptions"
type: docs
weight: 110
url: /ru/python-net/aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/
---

**Summary:** The deconvolution filter options using Gaussian bluring.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.GaussianDeconvolutionFilterOptions

**Inheritance:** DeconvolutionFilterOptions

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| яркость | float | r/w | Получает или задает яркость.<br/>            рекомендуемый диапазон 1 - 1.5<br/>            значение по умолчанию = 1.15 |
| grayscale | bool | r/w | Получает или задает значение, указывающее, является ли этот [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) градациями серого.<br/>            Возвращает режим градаций серого или режим RGB. |
| is_partial_loaded | bool | r | Получает значение, указывающее, частично ли загружен этот экземпляр. |
| kernel_data | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Получает ядро. |
| radius | int | r/w | Получает радиус гауссовского [ISquareConvolutionKernel](/imaging/python-net/aspose.imaging.imagefilters.convolution/isquareconvolutionkernel/). |
| сигма | float | r/w | Получает сигму гауссовского ядра (сглаживание). Должно быть положительным ненулевым значением. |
| size | int | r/w | Получает размер гауссовского ядра. Должно быть положительным ненулевым нечетным значением. |
| snr | float | r/w | Получает или задает SNR (отношение сигнал/шум)<br/>            рекомендуемый диапазон 0.002 - 0.009, значение по умолчанию = 0.007 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_complex(kernel)](#create_with_complex_kernel_1) | Инициализирует новый экземпляр класса [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |
| [create_with_double(kernel)](#create_with_double_kernel_2) | Инициализирует новый экземпляр класса [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |


### Method: create_with_complex(kernel)  [static] {#create_with_complex_kernel_1}


```
 create_with_complex(kernel) 
```

Инициализирует новый экземпляр класса [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| kernel | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Ядро Complex[]. |

**Returns**

| Тип | Описание |
| :- | :- |
| [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) |  |


### Method: create_with_double(kernel)  [static] {#create_with_double_kernel_2}


```
 create_with_double(kernel) 
```

Инициализирует новый экземпляр класса [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| ядро | float[] | Ядро double[]. |

**Returns**

| Тип | Описание |
| :- | :- |
| [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) |  |


