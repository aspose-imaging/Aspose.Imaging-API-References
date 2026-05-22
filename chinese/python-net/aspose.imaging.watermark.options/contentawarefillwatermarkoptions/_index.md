---
title: "ContentAwareFillWatermarkOptions 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/
---

**Summary:** The common Content Aware Fill Algorithm options.

**Module:** [aspose.imaging.watermark.options](/imaging/python-net/aspose.imaging.watermark.options/)

**Full Name:** aspose.imaging.watermark.options.ContentAwareFillWatermarkOptions

**Inheritance:** WatermarkOptions

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [ContentAwareFillWatermarkOptions(mask)](#ContentAwareFillWatermarkOptions_mask_1) | 初始化 [ContentAwareFillWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/) 类的新实例。 |
| [ContentAwareFillWatermarkOptions(mask)](#ContentAwareFillWatermarkOptions_mask_2) | 初始化 [ContentAwareFillWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| graphics_path_mask | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | 获取或设置掩码。 |
| interest_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置用于获取补丁的区域。 |
| mask | System.Collections.Generic.IEnumerable`1[[Aspose.Imaging.Point]] | r/w | 获取或设置掩码。 |
| [max_painting_attempts](#max_painting_attempts1) | int | r/w | 获取或设置最大绘画尝试次数。<br/>            算法将选择最佳方案。 |
| patch_size | System.Byte | r/w | 获取或设置补丁大小（应为奇数）。 |


### Constructor: ContentAwareFillWatermarkOptions(mask) {#ContentAwareFillWatermarkOptions_mask_1}


```
 ContentAwareFillWatermarkOptions(mask) 
```

初始化 [ContentAwareFillWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| mask | [Point[]](/imaging/python-net/aspose.imaging/point/) | 未知区域的掩码。 |

### Constructor: ContentAwareFillWatermarkOptions(mask) {#ContentAwareFillWatermarkOptions_mask_2}


```
 ContentAwareFillWatermarkOptions(mask) 
```

初始化 [ContentAwareFillWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| mask | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 未知区域的掩码。 |

### Property: max_painting_attempts {#max_painting_attempts1}

获取或设置最大绘画尝试次数。<br/>            算法将选择最佳方案。

**See also:**

**[Example # 1](#example_227)**: The example shows how to remove any object from the image using Graphics Path...


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

