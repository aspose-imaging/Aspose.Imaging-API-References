---
title: "الفئة GraphCutMaskingOptions"
type: docs
weight: 40
url: /ar/python-net/aspose.imaging.masking.options/graphcutmaskingoptions/
---

**Summary:** The GraphCut auto masking options.

**Module:** [aspose.imaging.masking.options](/imaging/python-net/aspose.imaging.masking.options/)

**Full Name:** aspose.imaging.masking.options.GraphCutMaskingOptions

**Inheritance:** MaskingOptions

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [GraphCutMaskingOptions()](#GraphCutMaskingOptions__1) | يُنشئ مثيلًا جديدًا من الفئة GraphCutMaskingOptions |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| BACKGROUND_OBJECT_NUMBER [static] | int | r | رقم كائن الخلفية |
| args | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | r/w | يحصل أو يعيّن المعاملات لخوارزمية التجزئة. |
| background_replacement_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | يحصل أو يعيّن لون استبدال الخلفية. |
| تحليل | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان<br/> من غير الضروري فصل كل شكل عن القناع ككائن منفرد أو ككائن موحد من القناع مفصول عن الخلفية. |
| export_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | r/w | يحصل أو يعيّن خيارات تصدير الصورة. |
| [feathering_radius](#feathering_radius1) | int | r/w | يحصل أو يضبط نصف قطر التدرج. |
| masking_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن منطقة القناع. |
| method | [SegmentationMethod](/imaging/python-net/aspose.imaging.masking.options/segmentationmethod/) | r/w | يحصل أو يعيّن طريقة التجزئة. |


### Constructor: GraphCutMaskingOptions() {#GraphCutMaskingOptions__1}


```
 GraphCutMaskingOptions() 
```

يُنشئ مثيلًا جديدًا من الفئة GraphCutMaskingOptions

### Property: feathering_radius {#feathering_radius1}

يحصل أو يضبط نصف قطر التدرج.

**See also:**

**[Example # 1](#example_220)**: Saving Graph Cut image masking result with feathering set to 3. Image masking...


## **Examples**
### Saving Graph Cut image masking result with feathering set to 3. Image masking is performed using specified Point array. {#example_220}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image, Color, RasterImage
from aspose.imaging.masking.options import AutoMaskingArgs, GraphCutMaskingOptions, SegmentationMethod
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.png import PngColorType


with aspycore.as_of(Image.load("input.jpg"), RasterImage) as image:
	obj_init = PngOptions()
	obj_init.color_type = PngColorType.TRUECOLOR_WITH_ALPHA
	obj_init.source = FileCreateSource("tempFile")
	obj_init2 = AutoMaskingArgs()
	obj_init2.objects_points = [[Point(100, 100)]]
	
	options = GraphCutMaskingOptions()
	options.feathering_radius = 3
	options.method = SegmentationMethod.GRAPH_CUT
	options.decompose = False
	options.export_options = obj_init
	options.background_replacement_color = Color.transparent
	options.args = obj_init2
	
	results = ImageMasking(image).decompose(options)

with aspycore.as_of(results[1].get_image(), RasterImage) as result_image:
	obj_init4 = PngOptions()
	obj_init4.color_type = PngColorType.TRUECOLOR_WITH_ALPHA
	result_image.save("output.png", obj_init4)
	
# إصدار جميع الصور الفرعية
for it in results:
	with it as _:
		pass


```

