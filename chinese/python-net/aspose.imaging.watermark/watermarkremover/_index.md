---
title: "WatermarkRemover 类"
type: docs
weight: 40
url: /zh/python-net/aspose.imaging.watermark/watermarkremover/
---

**Summary:** The class intended for manipulation the watermark.

**Module:** [aspose.imaging.watermark](/imaging/python-net/aspose.imaging.watermark/)

**Full Name:** aspose.imaging.watermark.WatermarkRemover

## **Methods**
| **Name** | **描述** |
| :- | :- |
| [paint_over(source, options)](#paint_over_source_options_1) | 从光栅图像中移除水印。 |


### Method: paint_over(source, options)  [static] {#paint_over_source_options_1}


```
 paint_over(source, options) 
```

从光栅图像中移除水印。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 源光栅图像。 |
| options | [WatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/watermarkoptions/) | 水印选项。 |

**Returns**

| Type | Description |
| :- | :- |
| [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 生成的图像。 |


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

