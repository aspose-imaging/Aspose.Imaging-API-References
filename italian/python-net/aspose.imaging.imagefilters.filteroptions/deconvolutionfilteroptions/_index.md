---
title: "Classe DeconvolutionFilterOptions"
type: docs
weight: 70
url: /it/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/
---

**Summary:** Deconvolution Filter Options, abstract class

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.DeconvolutionFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [DeconvolutionFilterOptions(kernel)](#DeconvolutionFilterOptions_kernel_1) | Inizializza una nuova istanza della classe [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |
| [DeconvolutionFilterOptions(kernel)](#DeconvolutionFilterOptions_kernel_2) | Inizializza una nuova istanza della classe [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| luminosità | float | r/w | Restituisce o imposta la luminosità.<br/>            intervallo consigliato 1 - 1.5<br/>            valore predefinito = 1.15 |
| grayscale | bool | r/w | Restituisce o imposta un valore che indica se questo [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) è in scala di grigi.<br/>            Restituisce modalità scala di grigi o modalità RGB. |
| is_partial_loaded | bool | r | Restituisce un valore che indica se questa istanza è parzialmente caricata. |
| kernel_data | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Restituisce il kernel. |
| snr | float | r/w | Restituisce o imposta il SNR (rapporto segnale-rumore)<br/>            intervallo consigliato 0.002 - 0.009, valore predefinito = 0.007 |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_with_complex(kernel)](#create_with_complex_kernel_1) | Inizializza una nuova istanza della classe [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |
| [create_with_double(kernel)](#create_with_double_kernel_2) | Inizializza una nuova istanza della classe [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |


### Constructor: DeconvolutionFilterOptions(kernel) {#DeconvolutionFilterOptions_kernel_1}


```
 DeconvolutionFilterOptions(kernel) 
```

Inizializza una nuova istanza della classe [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| kernel | float[] | Il kernel. |

### Constructor: DeconvolutionFilterOptions(kernel) {#DeconvolutionFilterOptions_kernel_2}


```
 DeconvolutionFilterOptions(kernel) 
```

Inizializza una nuova istanza della classe [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| kernel | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il kernel. |

### Method: create_with_complex(kernel)  [static] {#create_with_complex_kernel_1}


```
 create_with_complex(kernel) 
```

Inizializza una nuova istanza della classe [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| kernel | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il kernel Complex[]. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) |  |


### Method: create_with_double(kernel)  [static] {#create_with_double_kernel_2}


```
 create_with_double(kernel) 
```

Inizializza una nuova istanza della classe [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| kernel | float[] | Il kernel double[]. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) |  |


