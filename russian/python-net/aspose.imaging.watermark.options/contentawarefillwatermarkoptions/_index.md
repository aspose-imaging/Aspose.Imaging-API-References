---
title: "ContentAwareFillWatermarkOptions Класс"
type: docs
weight: 10
url: /ru/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/
---

**Summary:** The common Content Aware Fill Algorithm options.

**Module:** [aspose.imaging.watermark.options](/imaging/python-net/aspose.imaging.watermark.options/)

**Full Name:** aspose.imaging.watermark.options.ContentAwareFillWatermarkOptions

**Inheritance:** WatermarkOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ContentAwareFillWatermarkOptions(mask)](#ContentAwareFillWatermarkOptions_mask_1) | Инициализирует новый экземпляр класса [ContentAwareFillWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/). |
| [ContentAwareFillWatermarkOptions(mask)](#ContentAwareFillWatermarkOptions_mask_2) | Инициализирует новый экземпляр класса [ContentAwareFillWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| graphics_path_mask | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | Получает или задает маску. |
| interest_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает область для взятия патчей. |
| mask | System.Collections.Generic.IEnumerable`1[[Aspose.Imaging.Point]] | r/w | Получает или задает маску. |
| [max_painting_attempts](#max_painting_attempts1) | int | r/w | Получает или задает максимальное количество попыток рисования.<br/>            Алгоритм выберет лучший вариант. |
| patch_size | System.Byte | r/w | Получает или задает размер патча (должен быть нечетным). |


### Constructor: ContentAwareFillWatermarkOptions(mask) {#ContentAwareFillWatermarkOptions_mask_1}


```
 ContentAwareFillWatermarkOptions(mask) 
```

Инициализирует новый экземпляр класса [ContentAwareFillWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| mask | [Point[]](/imaging/python-net/aspose.imaging/point/) | Маска для неизвестной области. |

### Constructor: ContentAwareFillWatermarkOptions(mask) {#ContentAwareFillWatermarkOptions_mask_2}


```
 ContentAwareFillWatermarkOptions(mask) 
```

Инициализирует новый экземпляр класса [ContentAwareFillWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| mask | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Маска для неизвестной области. |

### Property: max_painting_attempts {#max_painting_attempts1}

Получает или задает максимальное количество попыток рисования.<br/>            Алгоритм выберет лучший вариант.

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

