---
title: "ContentAwareFillWatermarkOptions Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/
---

**Summary:** The common Content Aware Fill Algorithm options.

**Module:** [aspose.imaging.watermark.options](/imaging/python-net/aspose.imaging.watermark.options/)

**Full Name:** aspose.imaging.watermark.options.ContentAwareFillWatermarkOptions

**Inheritance:** WatermarkOptions

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [ContentAwareFillWatermarkOptions(mask)](#ContentAwareFillWatermarkOptions_mask_1) | Yeni bir [ContentAwareFillWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/) sınıfının örneğini başlatır. |
| [ContentAwareFillWatermarkOptions(mask)](#ContentAwareFillWatermarkOptions_mask_2) | Yeni bir [ContentAwareFillWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| graphics_path_mask | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | Maskeyi alır veya ayarlar. |
| interest_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Yamaları alacağı alanı alır veya ayarlar. |
| mask | System.Collections.Generic.IEnumerable`1[[Aspose.Imaging.Point]] | r/w | Maskeyi alır veya ayarlar. |
| [max_painting_attempts](#max_painting_attempts1) | int | r/w | Maksimum boyama deneme sayısını alır veya ayarlar.<br/>            Algoritma en iyi varyantı seçecektir. |
| patch_size | System.Byte | r/w | Yama boyutunu alır veya ayarlar (tek sayı olmalıdır). |


### Constructor: ContentAwareFillWatermarkOptions(mask) {#ContentAwareFillWatermarkOptions_mask_1}


```
 ContentAwareFillWatermarkOptions(mask) 
```

Yeni bir [ContentAwareFillWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| mask | [Point[]](/imaging/python-net/aspose.imaging/point/) | Bilinmeyen alan için maske. |

### Constructor: ContentAwareFillWatermarkOptions(mask) {#ContentAwareFillWatermarkOptions_mask_2}


```
 ContentAwareFillWatermarkOptions(mask) 
```

Yeni bir [ContentAwareFillWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| mask | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Bilinmeyen alan için maske. |

### Property: max_painting_attempts {#max_painting_attempts1}

Maksimum boyama deneme sayısını alır veya ayarlar.<br/>            Algoritma en iyi varyantı seçecektir.

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

