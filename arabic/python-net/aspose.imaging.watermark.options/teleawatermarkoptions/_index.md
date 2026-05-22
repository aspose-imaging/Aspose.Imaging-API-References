---
title: "فئة TeleaWatermarkOptions"
type: docs
weight: 20
url: /ar/python-net/aspose.imaging.watermark.options/teleawatermarkoptions/
---

**Summary:** The common Telea Algorithm options.

**Module:** [aspose.imaging.watermark.options](/imaging/python-net/aspose.imaging.watermark.options/)

**Full Name:** aspose.imaging.watermark.options.TeleaWatermarkOptions

**Inheritance:** WatermarkOptions

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [TeleaWatermarkOptions(mask)](#TeleaWatermarkOptions_mask_1) | يُنشئ مثيلًا جديدًا من الفئة [TeleaWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/teleawatermarkoptions/) |
| [TeleaWatermarkOptions(mask)](#TeleaWatermarkOptions_mask_2) | يُنشئ مثيلًا جديدًا من الفئة [TeleaWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/teleawatermarkoptions/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| graphics_path_mask | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | يحصل أو يضبط القناع. |
| half_patch_size | int | r/w | يحصل أو يضبط حجم نصف الرقعة. |
| mask | System.Collections.Generic.IEnumerable`1[[Aspose.Imaging.Point]] | r/w | يحصل أو يضبط القناع. |


### Constructor: TeleaWatermarkOptions(mask) {#TeleaWatermarkOptions_mask_1}


```
 TeleaWatermarkOptions(mask) 
```

يُنشئ مثيلًا جديدًا من الفئة [TeleaWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/teleawatermarkoptions/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| mask | [Point[]](/imaging/python-net/aspose.imaging/point/) | القناع للمنطقة غير المعروفة. |

### Constructor: TeleaWatermarkOptions(mask) {#TeleaWatermarkOptions_mask_2}


```
 TeleaWatermarkOptions(mask) 
```

يُنشئ مثيلًا جديدًا من الفئة [TeleaWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/teleawatermarkoptions/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| mask | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | القناع للمنطقة غير المعروفة. |

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

