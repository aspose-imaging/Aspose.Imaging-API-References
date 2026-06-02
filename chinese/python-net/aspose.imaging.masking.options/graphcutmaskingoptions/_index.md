---
title: "GraphCutMaskingOptions 类"
type: docs
weight: 40
url: /zh/python-net/aspose.imaging.masking.options/graphcutmaskingoptions/
---

**Summary:** The GraphCut auto masking options.

**Module:** [aspose.imaging.masking.options](/imaging/python-net/aspose.imaging.masking.options/)

**Full Name:** aspose.imaging.masking.options.GraphCutMaskingOptions

**Inheritance:** MaskingOptions

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [GraphCutMaskingOptions()](#GraphCutMaskingOptions__1) | 初始化 GraphCutMaskingOptions 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| BACKGROUND_OBJECT_NUMBER [static] | int | r | 背景对象编号 |
| args | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | r/w | 获取或设置分割算法的参数。 |
| background_replacement_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | 获取或设置背景替换颜色。 |
| 分解 | bool | r/w | 获取或设置一个值，指示是否<br/>            不需要将遮罩中的每个形状分离为单独的对象，或将其作为从遮罩中分离的与背景分开的统一对象。 |
| export_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | r/w | 获取或设置图像导出选项。 |
| [feathering_radius](#feathering_radius1) | int | r/w | 获取或设置羽化半径。 |
| masking_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置遮罩区域。 |
| method | [SegmentationMethod](/imaging/python-net/aspose.imaging.masking.options/segmentationmethod/) | r/w | 获取或设置分割方法。 |


### Constructor: GraphCutMaskingOptions() {#GraphCutMaskingOptions__1}


```
 GraphCutMaskingOptions() 
```

初始化 GraphCutMaskingOptions 类的新实例

### Property: feathering_radius {#feathering_radius1}

获取或设置羽化半径。

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
	
# 释放所有子图像
for it in results:
	with it as _:
		pass


```

