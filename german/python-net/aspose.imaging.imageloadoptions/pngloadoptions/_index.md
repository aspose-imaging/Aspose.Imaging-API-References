---
title: "PngLoadOptions Klasse"
type: docs
weight: 70
url: /de/python-net/aspose.imaging.imageloadoptions/pngloadoptions/
---

**Summary:** The png load options.

**Module:** [aspose.imaging.imageloadoptions](/imaging/python-net/aspose.imaging.imageloadoptions/)

**Full Name:** aspose.imaging.imageloadoptions.PngLoadOptions

**Inheritance:** LoadOptions

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [PngLoadOptions()](#PngLoadOptions__1) | Initialisiert eine neue Instanz der [PngLoadOptions](/imaging/python-net/aspose.imaging.imageloadoptions/pngloadoptions/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| concurrent_image_processing | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [concurrent image processing]. |
| data_background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Liest oder setzt das Hintergrund-[Color](/imaging/python-net/aspose.imaging/color/) des [Image](/imaging/python-net/aspose.imaging/image/). |
| data_recovery_mode | [DataRecoveryMode](/imaging/python-net/aspose.imaging/datarecoverymode/) | r/w | Liest oder setzt den Datenwiederherstellungsmodus. |
| [strict_mode](#strict_mode1) | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [strict mode]. |
| use_icc_profile_conversion | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die ICC-Profilkonvertierung angewendet werden soll. |


### Constructor: PngLoadOptions() {#PngLoadOptions__1}


```
 PngLoadOptions() 
```

Initialisiert eine neue Instanz der [PngLoadOptions](/imaging/python-net/aspose.imaging.imageloadoptions/pngloadoptions/) Klasse.

### Property: strict_mode {#strict_mode1}

Liest oder setzt einen Wert, der angibt, ob [strict mode].

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
# Standardmodus (nicht strikt) – erfolgreiches Lesen.
with Image.load(input_file_name) as image:
	image.save(output_file_name, PngOptions())

# Strikter Modus – ImageLoadException: Unerwartetes Dateiende.
obj_init = PngLoadOptions()
obj_init.strict_mode = True
with Image.load(input_file_name, obj_init) as image:
	image.save(output_file_name, PngOptions())


```

