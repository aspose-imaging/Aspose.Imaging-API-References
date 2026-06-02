---
title: "Clase LoadOptions"
type: docs
weight: 6000
url: /es/python-net/aspose.imaging/loadoptions/
---

**Summary:** Represents the loading options.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.LoadOptions

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [LoadOptions()](#LoadOptions__1) | Inicializa una nueva instancia de [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| [buffer_size_hint](#buffer_size_hint1) | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| concurrent_image_processing | bool | r/w | Obtiene o establece un valor que indica si [concurrent image processing]. |
| data_background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtiene o establece el fondo del [Image](/imaging/python-net/aspose.imaging/image/) [Color](/imaging/python-net/aspose.imaging/color/). |
| data_recovery_mode | [DataRecoveryMode](/imaging/python-net/aspose.imaging/datarecoverymode/) | r/w | Obtiene o establece el modo de recuperación de datos. |
| use_icc_profile_conversion | bool | r/w | Obtiene o establece un valor que indica si se debe aplicar la conversión de perfil ICC. |


### Constructor: LoadOptions() {#LoadOptions__1}


```
 LoadOptions() 
```

Inicializa una nueva instancia de [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/).

### Property: buffer_size_hint {#buffer_size_hint1}

Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos.

**See also:**

**[Example # 1](#example_179)**: The following example shows how to set a memory limit when loading a CMX imag...


## **Examples**
### The following example shows how to set a memory limit when loading a CMX image. The memory limit is the maximum allowed size (in megabytes) for all internal buffers. {#example_179}
``` python
from aspose.imaging import Image, TextRenderingHint, SmoothingMode, PositioningTypes, LoadOptions
from aspose.imaging.imageoptions import PngOptions, CmxRasterizationOptions
import os

directory = "c:\\aspose.imaging\\issues\\net\\3419\\"
	
# Estableciendo un límite de memoria de 10 megabytes para una imagen cargada objetivo.
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

