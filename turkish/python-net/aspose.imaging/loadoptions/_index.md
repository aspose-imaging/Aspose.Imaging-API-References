---
title: "LoadOptions Sınıfı"
type: docs
weight: 6000
url: /tr/python-net/aspose.imaging/loadoptions/
---

**Summary:** Represents the loading options.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.LoadOptions

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [LoadOptions()](#LoadOptions__1) | Yeni bir [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| [buffer_size_hint](#buffer_size_hint1) | int | r/w | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| concurrent_image_processing | bool | r/w | Eşzamanlı [concurrent image processing] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| data_background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | [Image](/imaging/python-net/aspose.imaging/image/) arka plan [Color](/imaging/python-net/aspose.imaging/color/) alır veya ayarlar. |
| data_recovery_mode | [DataRecoveryMode](/imaging/python-net/aspose.imaging/datarecoverymode/) | r/w | Veri kurtarma modunu alır veya ayarlar. |
| use_icc_profile_conversion | bool | r/w | ICC profil dönüşümünün uygulanıp uygulanmayacağını gösteren bir değeri alır veya ayarlar. |


### Constructor: LoadOptions() {#LoadOptions__1}


```
 LoadOptions() 
```

Yeni bir [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) örneği başlatır.

### Property: buffer_size_hint {#buffer_size_hint1}

Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar.

**See also:**

**[Example # 1](#example_179)**: The following example shows how to set a memory limit when loading a CMX imag...


## **Examples**
### The following example shows how to set a memory limit when loading a CMX image. The memory limit is the maximum allowed size (in megabytes) for all internal buffers. {#example_179}
``` python
from aspose.imaging import Image, TextRenderingHint, SmoothingMode, PositioningTypes, LoadOptions
from aspose.imaging.imageoptions import PngOptions, CmxRasterizationOptions
import os

directory = "c:\\aspose.imaging\\issues\\net\\3419\\"
	
# Hedef yüklenen görüntü için 10 megabayt bellek sınırı ayarlanıyor.
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

