---
title: TeleaWatermarkOptions Class
type: docs
weight: 20
url: /python-net/aspose.imaging.watermark.options/teleawatermarkoptions/
---

**Summary:** 

**Module:** [aspose.imaging.watermark.options](/imaging/python-net/aspose.imaging.watermark.options/)

**Full Name:** aspose.imaging.watermark.options.TeleaWatermarkOptions

**Inheritance:** WatermarkOptions

**Aspose.Imaging Version:** 23.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TeleaWatermarkOptions(mask)](#TeleaWatermarkOptions_mask_1) | Initializes a new instance of the TeleaWatermarkOptions class |
| [TeleaWatermarkOptions(mask)](#TeleaWatermarkOptions_mask_2) | Initializes a new instance of the TeleaWatermarkOptions class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| graphics_path_mask | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath) | r/w |    |
| half_patch_size | int | r/w |    |
| mask | iter[Point] | r/w |    |


### Constructor: TeleaWatermarkOptions(mask) {#TeleaWatermarkOptions_mask_1}


```
 TeleaWatermarkOptions(mask) 
```

Initializes a new instance of the TeleaWatermarkOptions class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| mask | [Point[]](/imaging/python-net/aspose.imaging/point) |  |

### Constructor: TeleaWatermarkOptions(mask) {#TeleaWatermarkOptions_mask_2}


```
 TeleaWatermarkOptions(mask) 
```

Initializes a new instance of the TeleaWatermarkOptions class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| mask | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath) |  |

## **Examples**
### The example shows how to remove any object from the image using Graphics Path with Telea algorithm. {#example_68}
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

