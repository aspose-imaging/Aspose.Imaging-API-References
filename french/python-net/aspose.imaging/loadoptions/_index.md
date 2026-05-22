---
title: "Classe LoadOptions"
type: docs
weight: 6000
url: /fr/python-net/aspose.imaging/loadoptions/
---

**Summary:** Represents the loading options.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.LoadOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LoadOptions()](#LoadOptions__1) | Initialise une nouvelle instance de la [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [buffer_size_hint](#buffer_size_hint1) | int | r/w | Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| concurrent_image_processing | bool | r/w | Obtient ou définit une valeur indiquant si [concurrent image processing]. |
| data_background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtient ou définit le [Image](/imaging/python-net/aspose.imaging/image/) d'arrière-plan [Color](/imaging/python-net/aspose.imaging/color/). |
| data_recovery_mode | [DataRecoveryMode](/imaging/python-net/aspose.imaging/datarecoverymode/) | r/w | Obtient ou définit le mode de récupération des données. |
| use_icc_profile_conversion | bool | r/w | Obtient ou définit une valeur indiquant si la conversion de profil ICC doit être appliquée. |


### Constructor: LoadOptions() {#LoadOptions__1}


```
 LoadOptions() 
```

Initialise une nouvelle instance de la [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/).

### Property: buffer_size_hint {#buffer_size_hint1}

Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes.

**See also:**

**[Example # 1](#example_179)**: The following example shows how to set a memory limit when loading a CMX imag...


## **Examples**
### The following example shows how to set a memory limit when loading a CMX image. The memory limit is the maximum allowed size (in megabytes) for all internal buffers. {#example_179}
``` python
from aspose.imaging import Image, TextRenderingHint, SmoothingMode, PositioningTypes, LoadOptions
from aspose.imaging.imageoptions import PngOptions, CmxRasterizationOptions
import os

directory = "c:\\aspose.imaging\\issues\\net\\3419\\"
	
# Définir une limite de mémoire de 10 mégaoctets pour l'image chargée cible.
load_options = LoadOptions()
load_options.buffer_size_hint = 10
with Image.load(os.path.join(directory, "example.cmx"), load_options) as image:
	png_options = PngOptions()
	cmx_spec = CmxRasterizationOptions()
	cmx_spec.text_renderingHint = TextRenderingHint.SINGLE_BIT_PER_PIXEL
	cmx_spec.smoothing_mode = SmoothingMode.ANTI_ALIAS
	cmx_spec.positioning = PositioningTypes.DEFINED_BY_DOCUMENT
	png_options.vector_rasterization_options = cmx_spec
	image.save(os.path.join(directory, "output.png"), png_options)


```

