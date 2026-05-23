---
title: "PngLoadOptions Sınıfı"
type: docs
weight: 70
url: /tr/python-net/aspose.imaging.imageloadoptions/pngloadoptions/
---

**Summary:** The png load options.

**Module:** [aspose.imaging.imageloadoptions](/imaging/python-net/aspose.imaging.imageloadoptions/)

**Full Name:** aspose.imaging.imageloadoptions.PngLoadOptions

**Inheritance:** LoadOptions

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [PngLoadOptions()](#PngLoadOptions__1) | Yeni bir [PngLoadOptions](/imaging/python-net/aspose.imaging.imageloadoptions/pngloadoptions/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| concurrent_image_processing | bool | r/w | Eşzamanlı [concurrent image processing] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| data_background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | [Image](/imaging/python-net/aspose.imaging/image/) arka plan [Color](/imaging/python-net/aspose.imaging/color/) alır veya ayarlar. |
| data_recovery_mode | [DataRecoveryMode](/imaging/python-net/aspose.imaging/datarecoverymode/) | r/w | Veri kurtarma modunu alır veya ayarlar. |
| [strict_mode](#strict_mode1) | bool | r/w | Bir değerin [strict mode] olup olmadığını alır veya ayarlar. |
| use_icc_profile_conversion | bool | r/w | ICC profil dönüşümünün uygulanıp uygulanmayacağını gösteren bir değeri alır veya ayarlar. |


### Constructor: PngLoadOptions() {#PngLoadOptions__1}


```
 PngLoadOptions() 
```

Yeni bir [PngLoadOptions](/imaging/python-net/aspose.imaging.imageloadoptions/pngloadoptions/) sınıfı örneği başlatır.

### Property: strict_mode {#strict_mode1}

Bir değerin [strict mode] olup olmadığını alır veya ayarlar.

**See also:**

**[Example # 1](#example_186)**: The following example shows how to read PNG file in a strict mode. The strict...


## **Examples**
### The following example shows how to read PNG file in a strict mode. The strict mode allows to find potential problems in PNG images, e.g. unrecognized data blocks, unexpected end of file. Such files still can be opened in default (non-strict) mode by `aspose.imaging` and by common viewers as well. However any attempts to open them in the strict mode cause a corresponding exception. {#example_186}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.imageloadoptions import PngLoadOptions
from os.path import join as path_join


dir_ = "c:\\testdata"
input_file_name = path_join(dir_, "FC5F1998104EB92469CB14070628073616BB28F9.png")
output_file_name = input_file_name + ".png"
# Varsayılan mod (katı olmayan) - başarılı okuma.
with Image.load(input_file_name) as image:
	image.save(output_file_name, PngOptions())

# Katı mod - ImageLoadException : Beklenmeyen dosya sonu.
obj_init = PngLoadOptions()
obj_init.strict_mode = True
with Image.load(input_file_name, obj_init) as image:
	image.save(output_file_name, PngOptions())


```

