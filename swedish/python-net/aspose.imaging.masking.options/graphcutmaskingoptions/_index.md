---
title: "GraphCutMaskingOptions‑klass"
type: docs
weight: 40
url: /sv/python-net/aspose.imaging.masking.options/graphcutmaskingoptions/
---

**Summary:** The GraphCut auto masking options.

**Module:** [aspose.imaging.masking.options](/imaging/python-net/aspose.imaging.masking.options/)

**Full Name:** aspose.imaging.masking.options.GraphCutMaskingOptions

**Inheritance:** MaskingOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GraphCutMaskingOptions()](#GraphCutMaskingOptions__1) | Initierar en ny instans av klassen GraphCutMaskingOptions. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| BACKGROUND_OBJECT_NUMBER [static] | int | r | Bakgrundsobjektets nummer |
| args | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | r/w | Hämtar eller anger argumenten för segmenteringsalgoritmen. |
| background_replacement_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Hämtar eller anger bakgrundens ersättningsfärg. |
| dekomponera | bool | r/w | Hämtar eller anger ett värde som indikerar om<br/>            det är onödigt att separera varje Shape från masken som ett enskilt objekt eller som ett förenat objekt från masken separerat från bakgrunden. |
| export_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | r/w | Hämtar eller anger bildexportalternativen. |
| [feathering_radius](#feathering_radius1) | int | r/w | Hämtar eller anger fjädringsradien. |
| masking_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger maskningsområdet. |
| method | [SegmentationMethod](/imaging/python-net/aspose.imaging.masking.options/segmentationmethod/) | r/w | Hämtar eller anger segmenteringsmetoden. |


### Constructor: GraphCutMaskingOptions() {#GraphCutMaskingOptions__1}


```
 GraphCutMaskingOptions() 
```

Initierar en ny instans av klassen GraphCutMaskingOptions.

### Property: feathering_radius {#feathering_radius1}

Hämtar eller anger fjädringsradien.

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
	
# släpp alla delbilder
for it in results:
	with it as _:
		pass


```

