---
title: "ConvolutionFilterOptions klass"
type: docs
weight: 60
url: /sv/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/
---

**Summary:** The convolution filter options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.ConvolutionFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ConvolutionFilterOptions(kernel)](#ConvolutionFilterOptions_kernel_1) | Initierar en ny instans av klassen [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) med factor = 1, och bias = 0. |
| [ConvolutionFilterOptions(kernel, factor)](#ConvolutionFilterOptions_kernel_factor_2) | Initierar en ny instans av klassen [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) med bias = 0. |
| [ConvolutionFilterOptions(kernel, factor, bias)](#ConvolutionFilterOptions_kernel_factor_bias_3) | Initierar en ny instans av klassen [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bias | int | r/w | Hämtar eller anger bias. |
| borders_processing | bool | r/w | Hämtar eller anger ett värde som indikerar om [borders processing]. |
| factor | float | r/w | Hämtar eller anger faktorn. |
| ignore_alpha | bool | r/w | Hämtar eller anger ett värde som indikerar om [ignore alpha]. |
| kernel_data | float[] | r | Hämtar kärnan. |


### Constructor: ConvolutionFilterOptions(kernel) {#ConvolutionFilterOptions_kernel_1}


```
 ConvolutionFilterOptions(kernel) 
```

Initierar en ny instans av klassen [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) med factor = 1, och bias = 0.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| kärna | float[] | Den konvolutionella kärnan för X-axelns riktning. |

### Constructor: ConvolutionFilterOptions(kernel, factor) {#ConvolutionFilterOptions_kernel_factor_2}


```
 ConvolutionFilterOptions(kernel, factor) 
```

Initierar en ny instans av klassen [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/) med bias = 0.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| kärna | float[] | Den konvolutionella kärnan för X-axelns riktning. |
| factor | float | Faktorn. |

### Constructor: ConvolutionFilterOptions(kernel, factor, bias) {#ConvolutionFilterOptions_kernel_factor_bias_3}


```
 ConvolutionFilterOptions(kernel, factor, bias) 
```

Initierar en ny instans av klassen [ConvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| kärna | float[] | Den konvolutionella kärnan för X-axelns riktning. |
| factor | float | Faktorn. |
| bias | int | Biasvärdet. |

