---
title: "Classe PngLoadOptions"
type: docs
weight: 70
url: /fr/python-net/aspose.imaging.imageloadoptions/pngloadoptions/
---

**Summary:** The png load options.

**Module:** [aspose.imaging.imageloadoptions](/imaging/python-net/aspose.imaging.imageloadoptions/)

**Full Name:** aspose.imaging.imageloadoptions.PngLoadOptions

**Inheritance:** LoadOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PngLoadOptions()](#PngLoadOptions__1) | Initialise une nouvelle instance de la classe [PngLoadOptions](/imaging/python-net/aspose.imaging.imageloadoptions/pngloadoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| concurrent_image_processing | bool | r/w | Obtient ou définit une valeur indiquant si [concurrent image processing]. |
| data_background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtient ou définit le [Image](/imaging/python-net/aspose.imaging/image/) d'arrière-plan [Color](/imaging/python-net/aspose.imaging/color/). |
| data_recovery_mode | [DataRecoveryMode](/imaging/python-net/aspose.imaging/datarecoverymode/) | r/w | Obtient ou définit le mode de récupération des données. |
| [strict_mode](#strict_mode1) | bool | r/w | Obtient ou définit une valeur indiquant si [strict mode]. |
| use_icc_profile_conversion | bool | r/w | Obtient ou définit une valeur indiquant si la conversion de profil ICC doit être appliquée. |


### Constructor: PngLoadOptions() {#PngLoadOptions__1}


```
 PngLoadOptions() 
```

Initialise une nouvelle instance de la classe [PngLoadOptions](/imaging/python-net/aspose.imaging.imageloadoptions/pngloadoptions/).

### Property: strict_mode {#strict_mode1}

Obtient ou définit une valeur indiquant si [strict mode].

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
# Mode par défaut (non strict) - lecture réussie.
with Image.load(input_file_name) as image:
	image.save(output_file_name, PngOptions())

# Mode strict - ImageLoadException : Fin de fichier inattendue.
obj_init = PngLoadOptions()
obj_init.strict_mode = True
with Image.load(input_file_name, obj_init) as image:
	image.save(output_file_name, PngOptions())


```

