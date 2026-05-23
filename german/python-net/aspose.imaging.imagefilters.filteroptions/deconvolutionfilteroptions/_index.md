---
title: "DeconvolutionFilterOptions Klasse"
type: docs
weight: 70
url: /de/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/
---

**Summary:** Deconvolution Filter Options, abstract class

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.DeconvolutionFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [DeconvolutionFilterOptions(kernel)](#DeconvolutionFilterOptions_kernel_1) | Initialisiert eine neue Instanz der Klasse [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |
| [DeconvolutionFilterOptions(kernel)](#DeconvolutionFilterOptions_kernel_2) | Initialisiert eine neue Instanz der Klasse [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| Helligkeit | float | r/w | Liest oder setzt die Helligkeit.<br/>            empfohlener Bereich 1 - 1,5<br/>            Standardwert = 1,15 |
| grayscale | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) im Graustufenmodus ist.<br/>            Gibt Graustufenmodus oder RGB-Modus zurück. |
| is_partial_loaded | bool | r | Liest einen Wert, der angibt, ob diese Instanz teilweise geladen ist. |
| kernel_data | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Liest den Kernel. |
| snr | float | r/w | Liest oder setzt das SNR (Signal‑zu‑Rausch‑Verhältnis)<br/>            empfohlener Bereich 0,002 - 0,009, Standardwert = 0,007 |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_with_complex(kernel)](#create_with_complex_kernel_1) | Initialisiert eine neue Instanz der Klasse [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |
| [create_with_double(kernel)](#create_with_double_kernel_2) | Initialisiert eine neue Instanz der Klasse [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |


### Constructor: DeconvolutionFilterOptions(kernel) {#DeconvolutionFilterOptions_kernel_1}


```
 DeconvolutionFilterOptions(kernel) 
```

Initialisiert eine neue Instanz der Klasse [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Kernel | float[] | Der Kernel. |

### Constructor: DeconvolutionFilterOptions(kernel) {#DeconvolutionFilterOptions_kernel_2}


```
 DeconvolutionFilterOptions(kernel) 
```

Initialisiert eine neue Instanz der Klasse [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| kernel | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Der Kernel. |

### Method: create_with_complex(kernel)  [static] {#create_with_complex_kernel_1}


```
 create_with_complex(kernel) 
```

Initialisiert eine neue Instanz der Klasse [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| kernel | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Der Complex[] Kernel. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) |  |


### Method: create_with_double(kernel)  [static] {#create_with_double_kernel_2}


```
 create_with_double(kernel) 
```

Initialisiert eine neue Instanz der Klasse [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Kernel | float[] | Der double[] Kernel. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) |  |


