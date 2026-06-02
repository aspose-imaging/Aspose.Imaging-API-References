---
title: "ContentAwareFillWatermarkOptions Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/
---

**Summary:** The common Content Aware Fill Algorithm options.

**Module:** [aspose.imaging.watermark.options](/imaging/python-net/aspose.imaging.watermark.options/)

**Full Name:** aspose.imaging.watermark.options.ContentAwareFillWatermarkOptions

**Inheritance:** WatermarkOptions

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [ContentAwareFillWatermarkOptions(mask)](#ContentAwareFillWatermarkOptions_mask_1) | Initialisiert eine neue Instanz der [ContentAwareFillWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/) Klasse. |
| [ContentAwareFillWatermarkOptions(mask)](#ContentAwareFillWatermarkOptions_mask_2) | Initialisiert eine neue Instanz der [ContentAwareFillWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| graphics_path_mask | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | Liest oder setzt die Maske. |
| interest_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Liest oder setzt den Bereich, aus dem Patches entnommen werden. |
| mask | System.Collections.Generic.IEnumerable`1[[Aspose.Imaging.Point]] | r/w | Liest oder setzt die Maske. |
| [max_painting_attempts](#max_painting_attempts1) | int | r/w | Liest oder setzt die maximale Anzahl von Malversuchen.<br/>            Der Algorithmus wählt die beste Variante. |
| patch_size | System.Byte | r/w | Liest oder setzt die Patch-Größe (sollte ungerade sein). |


### Constructor: ContentAwareFillWatermarkOptions(mask) {#ContentAwareFillWatermarkOptions_mask_1}


```
 ContentAwareFillWatermarkOptions(mask) 
```

Initialisiert eine neue Instanz der [ContentAwareFillWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| mask | [Point[]](/imaging/python-net/aspose.imaging/point/) | Die Maske für den unbekannten Bereich. |

### Constructor: ContentAwareFillWatermarkOptions(mask) {#ContentAwareFillWatermarkOptions_mask_2}


```
 ContentAwareFillWatermarkOptions(mask) 
```

Initialisiert eine neue Instanz der [ContentAwareFillWatermarkOptions](/imaging/python-net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| mask | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Die Maske für den unbekannten Bereich. |

### Property: max_painting_attempts {#max_painting_attempts1}

Liest oder setzt die maximale Anzahl von Malversuchen.<br/>            Der Algorithmus wählt die beste Variante.

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

