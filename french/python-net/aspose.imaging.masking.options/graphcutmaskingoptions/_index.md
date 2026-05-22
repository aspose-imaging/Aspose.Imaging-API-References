---
title: "Classe GraphCutMaskingOptions"
type: docs
weight: 40
url: /fr/python-net/aspose.imaging.masking.options/graphcutmaskingoptions/
---

**Summary:** The GraphCut auto masking options.

**Module:** [aspose.imaging.masking.options](/imaging/python-net/aspose.imaging.masking.options/)

**Full Name:** aspose.imaging.masking.options.GraphCutMaskingOptions

**Inheritance:** MaskingOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GraphCutMaskingOptions()](#GraphCutMaskingOptions__1) | Initialise une nouvelle instance de la classe GraphCutMaskingOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| BACKGROUND_OBJECT_NUMBER [static] | int | r | Le numéro de l'objet d'arrière-plan |
| args | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | r/w | Obtient ou définit les arguments de l'algorithme de segmentation. |
| background_replacement_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtient ou définit la couleur de remplacement de l'arrière-plan. |
| decompose | bool | r/w | Obtient ou définit une valeur indiquant si<br/>            il est inutile de séparer chaque forme du masque en tant qu'objet individuel ou en tant qu'objet uni du masque séparé de l'arrière-plan. |
| export_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | r/w | Obtient ou définit les options d'exportation d'image. |
| [feathering_radius](#feathering_radius1) | int | r/w | Obtient ou définit le rayon d'adoucissement. |
| masking_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit la zone de masquage. |
| method | [SegmentationMethod](/imaging/python-net/aspose.imaging.masking.options/segmentationmethod/) | r/w | Obtient ou définit la méthode de segmentation. |


### Constructor: GraphCutMaskingOptions() {#GraphCutMaskingOptions__1}


```
 GraphCutMaskingOptions() 
```

Initialise une nouvelle instance de la classe GraphCutMaskingOptions

### Property: feathering_radius {#feathering_radius1}

Obtient ou définit le rayon d'adoucissement.

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
	
# libérer toutes les sous-images
for it in results:
	with it as _:
		pass


```

