---
title: "TeleaWatermarkOptions Clase"
type: docs
weight: 20
url: /es/python-net/aspose.imaging.watermark.options/teleawatermarkoptions/
---

**Summary:** The common Telea Algorithm options.

**Module:** [aspose.imaging.watermark.options](/imaging/python-net/aspose.imaging.watermark.options/)

**Full Name:** aspose.imaging.watermark.options.TeleaWatermarkOptions

**Inheritance:** WatermarkOptions

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [TeleaWatermarkOptions(mask)](#TeleaWatermarkOptions_mask_1) | Inicializa una nueva instancia de la clase [TeleaWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/teleawatermarkoptions/). |
| [TeleaWatermarkOptions(mask)](#TeleaWatermarkOptions_mask_2) | Inicializa una nueva instancia de la clase [TeleaWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/teleawatermarkoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| graphics_path_mask | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | Obtiene o establece la máscara. |
| half_patch_size | int | r/w | Obtiene o establece el tamaño medio del parche. |
| mask | System.Collections.Generic.IEnumerable`1[[Aspose.Imaging.Point]] | r/w | Obtiene o establece la máscara. |


### Constructor: TeleaWatermarkOptions(mask) {#TeleaWatermarkOptions_mask_1}


```
 TeleaWatermarkOptions(mask) 
```

Inicializa una nueva instancia de la clase [TeleaWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/teleawatermarkoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| mask | [Point[]](/imaging/python-net/aspose.imaging/point/) | La máscara para el área desconocida. |

### Constructor: TeleaWatermarkOptions(mask) {#TeleaWatermarkOptions_mask_2}


```
 TeleaWatermarkOptions(mask) 
```

Inicializa una nueva instancia de la clase [TeleaWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/teleawatermarkoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| mask | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | La máscara para el área desconocida. |

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

