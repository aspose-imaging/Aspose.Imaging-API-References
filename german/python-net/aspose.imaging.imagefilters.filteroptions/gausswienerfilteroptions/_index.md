---
title: "GaussWienerFilterOptions Klasse"
type: docs
weight: 90
url: /de/python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/
---

**Summary:** Gauss Wiener filter options for image debluring.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions

**Inheritance:** GaussianDeconvolutionFilterOptions

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions__1) | Initialisiert eine neue Instanz der [GaussWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/) Klasse. |
| [GaussWienerFilterOptions(size, sigma)](#GaussWienerFilterOptions_size_sigma_2) | Initialisiert eine neue Instanz der [GaussWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/) Klasse. |
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


### Constructor: GaussWienerFilterOptions() {#GaussWienerFilterOptions__1}


```
 GaussWienerFilterOptions() 
```

Initialisiert eine neue Instanz der [GaussWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/) Klasse.

### Constructor: GaussWienerFilterOptions(size, sigma) {#GaussWienerFilterOptions_size_sigma_2}


```
 GaussWienerFilterOptions(size, sigma) 
```

Initialisiert eine neue Instanz der [GaussWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size | int | Die Größe des Gauß‑Kernels. |
| Sigma | float | Das Sigma des Gauß‑Kernels. |

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


## **Examples**
### The following example applies various types of filters to a raster image. {#example_59}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from aspose.imaging.imagefilters.filteroptions import *
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Wenden Sie einen Medianfilter mit einer Rechteckgröße von 5 auf das gesamte Bild an.
	rasterImage.filter(rasterImage.bounds, MedianFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.MedianFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Wenden Sie einen bilateralen Glättungsfilter mit einer Kernelgröße von 5 auf das gesamte Bild an.
	rasterImage.filter(rasterImage.bounds, BilateralSmoothingFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.BilateralSmoothingFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Wenden Sie einen Gaußschen Unschärfefilter mit einem Radius von 5 und einem Sigma‑Wert von 4,0 auf das gesamte Bild an.
	rasterImage.filter(rasterImage.bounds, GaussianBlurFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussianBlurFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Wenden Sie einen Gauss‑Wiener‑Filter mit einem Radius von 5 und einem Glättungswert von 4,0 auf das gesamte Bild an.
	rasterImage.filter(rasterImage.bounds, GaussWienerFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussWienerFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Wenden Sie einen Bewegungs‑Wiener‑Filter mit einer Länge von 5, einem Glättungswert von 4,0 und einem Winkel von 90,0 Grad auf das gesamte Bild an.
	rasterImage.filter(rasterImage.bounds, MotionWienerFilterOptions(10, 1.0, 90.0))
	rasterImage.save(join_path(directory, "sample.MotionWienerFilter.png"))
}

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Wenden Sie einen Schärfungsfilter mit einer Kernelgröße von 5 und einem Sigma‑Wert von 4,0 auf das gesamte Bild an.
	rasterImage.filter(rasterImage.bounds, SharpenFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.SharpenFilter.png"))


```

