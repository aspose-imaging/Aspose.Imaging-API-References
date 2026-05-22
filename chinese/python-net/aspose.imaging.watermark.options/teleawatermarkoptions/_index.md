---
title: "TeleaWatermarkOptions 类"
type: docs
weight: 20
url: /zh/python-net/aspose.imaging.watermark.options/teleawatermarkoptions/
---

**Summary:** The common Telea Algorithm options.

**Module:** [aspose.imaging.watermark.options](/imaging/python-net/aspose.imaging.watermark.options/)

**Full Name:** aspose.imaging.watermark.options.TeleaWatermarkOptions

**Inheritance:** WatermarkOptions

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [TeleaWatermarkOptions(mask)](#TeleaWatermarkOptions_mask_1) | 初始化 [TeleaWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/teleawatermarkoptions/) 类的新实例。 |
| [TeleaWatermarkOptions(mask)](#TeleaWatermarkOptions_mask_2) | 初始化 [TeleaWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/teleawatermarkoptions/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| graphics_path_mask | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | 获取或设置掩码。 |
| half_patch_size | int | r/w | 获取或设置半补丁大小。 |
| mask | System.Collections.Generic.IEnumerable`1[[Aspose.Imaging.Point]] | r/w | 获取或设置掩码。 |


### Constructor: TeleaWatermarkOptions(mask) {#TeleaWatermarkOptions_mask_1}


```
 TeleaWatermarkOptions(mask) 
```

初始化 [TeleaWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/teleawatermarkoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| mask | [Point[]](/imaging/python-net/aspose.imaging/point/) | 未知区域的掩码。 |

### Constructor: TeleaWatermarkOptions(mask) {#TeleaWatermarkOptions_mask_2}


```
 TeleaWatermarkOptions(mask) 
```

初始化 [TeleaWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/teleawatermarkoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| mask | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 未知区域的掩码。 |

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

