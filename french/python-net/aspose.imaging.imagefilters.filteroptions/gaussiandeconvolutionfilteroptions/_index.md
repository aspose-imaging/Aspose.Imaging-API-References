---
title: "Classe GaussianDeconvolutionFilterOptions"
type: docs
weight: 110
url: /fr/python-net/aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/
---

**Summary:** The deconvolution filter options using Gaussian bluring.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.GaussianDeconvolutionFilterOptions

**Inheritance:** DeconvolutionFilterOptions

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| luminosité | float | r/w | Obtient ou définit la luminosité.<br/>            plage recommandée 1 - 1.5<br/>            valeur par défaut = 1.15 |
| grayscale | bool | r/w | Obtient ou définit une valeur indiquant si ce [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) est en niveaux de gris.<br/>            Retourne le mode niveaux de gris ou le mode RGB. |
| is_partial_loaded | bool | r | Obtient une valeur indiquant si cette instance est partiellement chargée. |
| kernel_data | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Obtient le noyau. |
| radius | int | r/w | Obtient le rayon du [ISquareConvolutionKernel](/imaging/python-net/aspose.imaging.imagefilters.convolution/isquareconvolutionkernel/) gaussien. |
| sigma | float | r/w | Obtient le sigma du noyau gaussien (lissage). Doit être une valeur positive non nulle. |
| size | int | r/w | Obtient la taille du noyau gaussien. Doit être une valeur impaire positive non nulle. |
| snr | float | r/w | Obtient ou définit le SNR (rapport signal/bruit)<br/>            plage recommandée 0.002 - 0.009, valeur par défaut = 0.007 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_complex(kernel)](#create_with_complex_kernel_1) | Initialise une nouvelle instance de la classe [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |
| [create_with_double(kernel)](#create_with_double_kernel_2) | Initialise une nouvelle instance de la classe [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |


### Method: create_with_complex(kernel)  [static] {#create_with_complex_kernel_1}


```
 create_with_complex(kernel) 
```

Initialise une nouvelle instance de la classe [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| kernel | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le noyau Complex[]. |

**Returns**

| Type | Description |
| :- | :- |
| [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) |  |


### Method: create_with_double(kernel)  [static] {#create_with_double_kernel_2}


```
 create_with_double(kernel) 
```

Initialise une nouvelle instance de la classe [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| noyau | float[] | Le noyau double[]. |

**Returns**

| Type | Description |
| :- | :- |
| [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) |  |


