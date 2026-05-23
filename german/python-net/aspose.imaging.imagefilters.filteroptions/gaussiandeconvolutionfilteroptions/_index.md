---
title: "GaussianDeconvolutionFilterOptions Klasse"
type: docs
weight: 110
url: /de/python-net/aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/
---

**Summary:** The deconvolution filter options using Gaussian bluring.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.GaussianDeconvolutionFilterOptions

**Inheritance:** DeconvolutionFilterOptions

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| Helligkeit | float | r/w | Liest oder setzt die Helligkeit.<br/>            empfohlener Bereich 1 - 1,5<br/>            Standardwert = 1,15 |
| grayscale | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) im Graustufenmodus ist.<br/>            Gibt Graustufenmodus oder RGB-Modus zurück. |
| is_partial_loaded | bool | r | Liest einen Wert, der angibt, ob diese Instanz teilweise geladen ist. |
| kernel_data | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Liest den Kernel. |
| radius | int | r/w | Liest den Radius des gaußschen [ISquareConvolutionKernel](/imaging/python-net/aspose.imaging.imagefilters.convolution/isquareconvolutionkernel/). |
| Sigma | float | r/w | Liest das Sigma des Gauß‑Kernels (Glättung). Muss ein positiver, von Null verschiedener Wert sein. |
| size | int | r/w | Liest die Größe des Gauß‑Kernels. Muss ein positiver, von Null verschiedener, ungerader Wert sein. |
| snr | float | r/w | Liest oder setzt das SNR (Signal‑zu‑Rausch‑Verhältnis)<br/>            empfohlener Bereich 0,002 - 0,009, Standardwert = 0,007 |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_with_complex(kernel)](#create_with_complex_kernel_1) | Initialisiert eine neue Instanz der Klasse [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |
| [create_with_double(kernel)](#create_with_double_kernel_2) | Initialisiert eine neue Instanz der Klasse [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |


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


