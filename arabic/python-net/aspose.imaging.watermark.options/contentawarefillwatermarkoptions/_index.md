---
title: "فئة ContentAwareFillWatermarkOptions"
type: docs
weight: 10
url: /ar/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/
---

**Summary:** The common Content Aware Fill Algorithm options.

**Module:** [aspose.imaging.watermark.options](/imaging/python-net/aspose.imaging.watermark.options/)

**Full Name:** aspose.imaging.watermark.options.ContentAwareFillWatermarkOptions

**Inheritance:** WatermarkOptions

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [ContentAwareFillWatermarkOptions(mask)](#ContentAwareFillWatermarkOptions_mask_1) | يُنشئ مثيلًا جديدًا من الفئة [ContentAwareFillWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/) |
| [ContentAwareFillWatermarkOptions(mask)](#ContentAwareFillWatermarkOptions_mask_2) | يُنشئ مثيلًا جديدًا من الفئة [ContentAwareFillWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| graphics_path_mask | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | يحصل أو يضبط القناع. |
| interest_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يضبط المنطقة لأخذ الرقع. |
| mask | System.Collections.Generic.IEnumerable`1[[Aspose.Imaging.Point]] | r/w | يحصل أو يضبط القناع. |
| [max_painting_attempts](#max_painting_attempts1) | int | r/w | يحصل أو يضبط الحد الأقصى لعدد محاولات الرسم.<br/>            سيختار الخوارزمية أفضل خيار. |
| patch_size | System.Byte | r/w | يحصل أو يضبط حجم الرقعة (يجب أن يكون فرديًا). |


### Constructor: ContentAwareFillWatermarkOptions(mask) {#ContentAwareFillWatermarkOptions_mask_1}


```
 ContentAwareFillWatermarkOptions(mask) 
```

يُنشئ مثيلًا جديدًا من الفئة [ContentAwareFillWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| mask | [Point[]](/imaging/python-net/aspose.imaging/point/) | القناع للمنطقة غير المعروفة. |

### Constructor: ContentAwareFillWatermarkOptions(mask) {#ContentAwareFillWatermarkOptions_mask_2}


```
 ContentAwareFillWatermarkOptions(mask) 
```

يُنشئ مثيلًا جديدًا من الفئة [ContentAwareFillWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| mask | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | القناع للمنطقة غير المعروفة. |

### Property: max_painting_attempts {#max_painting_attempts1}

يحصل أو يضبط الحد الأقصى لعدد محاولات الرسم.<br/>            سيختار الخوارزمية أفضل خيار.

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

