---
title: AutoMaskingGraphCutOptions Class
type: docs
weight: 30
url: /python-net/aspose.imaging.masking.options/automaskinggraphcutoptions/
---

**Summary:** The GraphCut auto masking options.

**Module:** [aspose.imaging.masking.options](/imaging/python-net/aspose.imaging.masking.options/)

**Full Name:** aspose.imaging.masking.options.AutoMaskingGraphCutOptions

**Inheritance:** GraphCutMaskingOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [AutoMaskingGraphCutOptions()](#AutoMaskingGraphCutOptions__1) | Initializes a new instance of the [AutoMaskingGraphCutOptions](/imaging/python-net/aspose.imaging.masking.options/automaskinggraphcutoptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| BACKGROUND_OBJECT_NUMBER [static] | int | r | The background object number |
| args | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | r/w | Gets or sets the arguments for segmentation algorithm. |
| assumed_objects | System.Collections.Generic.List`1[[Aspose.Imaging.Masking.Options.AssumedObjectData]] | r/w | Gets or sets the assumed objects. |
| background_replacement_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Gets or sets the background replacement color. |
| [calculate_default_strokes](#calculate_default_strokes1) | bool | r/w | Gets or sets a value indicating whether default strokes should be calculated. |
| decompose | bool | r/w | Gets or sets a value indicating whether<br/>            needless to separate each Shape from mask as individual object or as united object from mask separated from background. |
| default_background_strokes | [Point[]](/imaging/python-net/aspose.imaging/point/) | r | Gets the default background strokes. |
| default_foreground_strokes | [Point[]](/imaging/python-net/aspose.imaging/point/) | r | Gets the pre-calculated default foreground strokes. |
| default_objects_rectangles | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | r | Gets the default objects rectangles. |
| export_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | r/w | Gets or sets the image export options. |
| feathering_radius | int | r/w | Gets or sets the feathering radius. |
| masking_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Gets or sets the masking area. |
| method | [SegmentationMethod](/imaging/python-net/aspose.imaging.masking.options/segmentationmethod/) | r/w | Gets or sets the segmentation method. |


### Constructor: AutoMaskingGraphCutOptions() {#AutoMaskingGraphCutOptions__1}


```
 AutoMaskingGraphCutOptions() 
```

Initializes a new instance of the [AutoMaskingGraphCutOptions](/imaging/python-net/aspose.imaging.masking.options/automaskinggraphcutoptions/) class.

### Property: calculate_default_strokes {#calculate_default_strokes1}

Gets or sets a value indicating whether default strokes should be calculated.

**See also:**

**[Example # 1](#example_232)**: Saving image masking result with feathering based on image size. Image maskin...


## **Examples**
### Saving image masking result with feathering based on image size. Image masking is performed using auto calculated default strokes. The Args property of AutoMaskingGraphCutOptions can be omitted since default strokes are placed there in the end. {#example_232}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.fileformats.png import PngColorType
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.masking.options import AutoMaskingGraphCutOptions, SegmentationMethod
from aspose.imaging.masking import ImageMasking

results = None
with aspycore.as_of(Image.load("input.jpg"), RasterImage) as image:
	obj_init = PngOptions()
	obj_init.color_type = PngColorType.TRUECOLOR_WITH_ALPHA
	obj_init.source = FileCreateSource("tempFile")
	options = AutoMaskingGraphCutOptions()
	options.calculate_default_strokes = True
	options.feathering_radius = (max(image.width, image.height) // 500) + 1
	options.method = SegmentationMethod.GRAPH_CUT
	options.decompose = False
	options.export_options = obj_init
	options.background_replacement_color = Color.transparent

	results = ImageMasking(image).decompose(options)

with aspycore.as_of(results[1].get_image(), RasterImage) as result_image:
	obj_init3 = PngOptions()
	obj_init3.color_type = PngColorType.TRUECOLOR_WITH_ALPHA
	result_image.save("output.png", obj_init3)
	
# disposing
for it in results:
	with it as _:
		pass


```

