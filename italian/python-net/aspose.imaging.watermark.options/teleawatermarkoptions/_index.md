---
title: "TeleaWatermarkOptions Classe"
type: docs
weight: 20
url: /it/python-net/aspose.imaging.watermark.options/teleawatermarkoptions/
---

**Summary:** The common Telea Algorithm options.

**Module:** [aspose.imaging.watermark.options](/imaging/python-net/aspose.imaging.watermark.options/)

**Full Name:** aspose.imaging.watermark.options.TeleaWatermarkOptions

**Inheritance:** WatermarkOptions

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [TeleaWatermarkOptions(mask)](#TeleaWatermarkOptions_mask_1) | Inizializza una nuova istanza della classe [TeleaWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/teleawatermarkoptions/). |
| [TeleaWatermarkOptions(mask)](#TeleaWatermarkOptions_mask_2) | Inizializza una nuova istanza della classe [TeleaWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/teleawatermarkoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| graphics_path_mask | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | Ottiene o imposta la maschera. |
| half_patch_size | int | r/w | Ottiene o imposta il half patch size. |
| mask | System.Collections.Generic.IEnumerable`1[[Aspose.Imaging.Point]] | r/w | Ottiene o imposta la maschera. |


### Constructor: TeleaWatermarkOptions(mask) {#TeleaWatermarkOptions_mask_1}


```
 TeleaWatermarkOptions(mask) 
```

Inizializza una nuova istanza della classe [TeleaWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/teleawatermarkoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| mask | [Point[]](/imaging/python-net/aspose.imaging/point/) | La maschera per l'area sconosciuta. |

### Constructor: TeleaWatermarkOptions(mask) {#TeleaWatermarkOptions_mask_2}


```
 TeleaWatermarkOptions(mask) 
```

Inizializza una nuova istanza della classe [TeleaWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/teleawatermarkoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| mask | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | La maschera per l'area sconosciuta. |

## **Examples**
### The example shows how to remove any object from the image using Graphics Path with Telea algorithm. {#example_228}
``` python
from aspose.imaging import Image, Figure, GraphicsPath, RectangleF
from aspose.imaging.shapes import EllipseShape
from aspose.imaging.watermark import WatermarkRemover
from aspose.imaging.watermark.options import TeleaWatermarkOptions
from aspose.imaging.fileformats.png import PngImage
import aspose.pycore import as_of

image_file_path = "ball.png"; 
with Image.load(image_file_path) as image:
	pngImage = as_of(image, PngImage)
	mask = GraphicsPath()
	firstFigure = Figure()
	firstFigure.add_shape(EllipseShape(RectangleF(350, 170, 570 - 350, 400 - 170)))
	mask.add_figure(firstFigure);
	options = TeleaWatermarkOptions(mask)
	with WatermarkRemover.paint_over(pngImage, options) as result:
		result.save(outputPath)


```

