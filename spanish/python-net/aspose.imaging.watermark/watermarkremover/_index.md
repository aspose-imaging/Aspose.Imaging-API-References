---
title: "Clase WatermarkRemover"
type: docs
weight: 40
url: /es/python-net/aspose.imaging.watermark/watermarkremover/
---

**Summary:** The class intended for manipulation the watermark.

**Module:** [aspose.imaging.watermark](/imaging/python-net/aspose.imaging.watermark/)

**Full Name:** aspose.imaging.watermark.WatermarkRemover

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [paint_over(source, options)](#paint_over_source_options_1) | Elimina la marca de agua de la imagen raster. |


### Method: paint_over(source, options)  [static] {#paint_over_source_options_1}


```
 paint_over(source, options) 
```

Elimina la marca de agua de la imagen raster.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen raster de origen. |
| options | [WatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/watermarkoptions/) | Las opciones de marca de agua. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen resultante. |


## **Examples**
### The example shows how to remove any object from the image using Graphics Path with Content Aware fill algorithm. {#example_227}
``` python
from aspose.imaging import Image, Figure, GraphicsPath, RectangleF
from aspose.imaging.shapes import EllipseShape
from aspose.imaging.watermark import WatermarkRemover
from aspose.imaging.watermark.options import ContentAwareFillWatermarkOptions
from aspose.imaging.fileformats.png import PngImage
import aspose.pycore import as_of

image_file_path = "ball.png"; 
with Image.load(image_file_path) as image:
	pngImage = as_of(image, PngImage)
	mask = GraphicsPath()
	firstFigure = Figure()
	firstFigure.add_shape(EllipseShape(RectangleF(350, 170, 570 - 350, 400 - 170)))
	mask.add_figure(firstFigure)

	options = ContentAwareFillWatermarkOptions(mask)
	options.max_painting_attempts = 4
	with WatermarkRemover.paint_over(pngImage, options) as result:
		result.save(outputPath)


```

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

