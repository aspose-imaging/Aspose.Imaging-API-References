---
title: "Classe BilateralSmoothingFilterOptions"
type: docs
weight: 40
url: /it/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/
---

**Summary:** The Bilateral Smoothing Filter Options.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [BilateralSmoothingFilterOptions()](#BilateralSmoothingFilterOptions__1) | Inizializza una nuova istanza della classe [BilateralSmoothingFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/). |
| [BilateralSmoothingFilterOptions(size)](#BilateralSmoothingFilterOptions_size_2) | Inizializza una nuova istanza della classe [BilateralSmoothingFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| color_factor | float | r/w | Ottiene o imposta il fattore di colore. |
| color_power | float | r/w | Ottiene o imposta la potenza del colore. |
| dimensione | int | r/w | Ottiene o imposta la dimensione del kernel. |
| spatial_factor | float | r/w | Ottiene o imposta il fattore spaziale. |
| spatial_power | float | r/w | Ottiene o imposta la potenza spaziale. |


### Constructor: BilateralSmoothingFilterOptions() {#BilateralSmoothingFilterOptions__1}


```
 BilateralSmoothingFilterOptions() 
```

Inizializza una nuova istanza della classe [BilateralSmoothingFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/).

### Constructor: BilateralSmoothingFilterOptions(size) {#BilateralSmoothingFilterOptions_size_2}


```
 BilateralSmoothingFilterOptions(size) 
```

Inizializza una nuova istanza della classe [BilateralSmoothingFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dimensione | int | Dimensione del kernal. |

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
	# Applica un filtro mediano con una dimensione del rettangolo pari a 5 all'intera immagine.
	rasterImage.filter(rasterImage.bounds, MedianFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.MedianFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Applica un filtro di levigatura bilaterale con una dimensione del kernel pari a 5 all'intera immagine.
	rasterImage.filter(rasterImage.bounds, BilateralSmoothingFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.BilateralSmoothingFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Applica un filtro di sfocatura gaussiana con un raggio di 5 e un valore sigma di 4.0 all'intera immagine.
	rasterImage.filter(rasterImage.bounds, GaussianBlurFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussianBlurFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Applica un filtro Gauss-Wiener con un raggio di 5 e un valore di levigatura di 4.0 all'intera immagine.
	rasterImage.filter(rasterImage.bounds, GaussWienerFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussWienerFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Applica un filtro motion Wiener con una lunghezza di 5, un valore di levigatura di 4.0 e un angolo di 90,0 gradi all'intera immagine.
	rasterImage.filter(rasterImage.bounds, MotionWienerFilterOptions(10, 1.0, 90.0))
	rasterImage.save(join_path(directory, "sample.MotionWienerFilter.png"))
}

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Applica un filtro di nitidezza con una dimensione del kernel pari a 5 e un valore sigma di 4.0 all'intera immagine.
	rasterImage.filter(rasterImage.bounds, SharpenFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.SharpenFilter.png"))


```

