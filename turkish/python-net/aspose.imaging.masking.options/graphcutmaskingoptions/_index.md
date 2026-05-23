---
title: "GraphCutMaskingOptions Sınıfı"
type: docs
weight: 40
url: /tr/python-net/aspose.imaging.masking.options/graphcutmaskingoptions/
---

**Summary:** The GraphCut auto masking options.

**Module:** [aspose.imaging.masking.options](/imaging/python-net/aspose.imaging.masking.options/)

**Full Name:** aspose.imaging.masking.options.GraphCutMaskingOptions

**Inheritance:** MaskingOptions

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [GraphCutMaskingOptions()](#GraphCutMaskingOptions__1) | GraphCutMaskingOptions sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| BACKGROUND_OBJECT_NUMBER [static] | int | r | Arka plan nesnesi numarası |
| args | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | r/w | Segmentasyon algoritması için argümanları alır veya ayarlar. |
| background_replacement_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Arka plan değiştirme rengini alır veya ayarlar. |
| parçala | bool | r/w | Her şeklin maskeden ayrı bir nesne olarak mı yoksa arka plandan ayrılmış birleşik bir nesne olarak mı ayrılması gerektiğini gösteren bir değeri alır veya ayarlar.<br/>             |
| export_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | r/w | Görüntü dışa aktarma seçeneklerini alır veya ayarlar. |
| [feathering_radius](#feathering_radius1) | int | r/w | Tüyleme yarıçapını alır veya ayarlar. |
| masking_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Maskeleme alanını alır veya ayarlar. |
| method | [SegmentationMethod](/imaging/python-net/aspose.imaging.masking.options/segmentationmethod/) | r/w | Segmentasyon yöntemini alır veya ayarlar. |


### Constructor: GraphCutMaskingOptions() {#GraphCutMaskingOptions__1}


```
 GraphCutMaskingOptions() 
```

GraphCutMaskingOptions sınıfının yeni bir örneğini başlatır

### Property: feathering_radius {#feathering_radius1}

Tüyleme yarıçapını alır veya ayarlar.

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
	
# tüm alt görüntüleri serbest bırak
for it in results:
	with it as _:
		pass


```

