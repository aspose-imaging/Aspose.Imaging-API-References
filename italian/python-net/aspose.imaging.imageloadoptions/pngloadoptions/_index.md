---
title: "Classe PngLoadOptions"
type: docs
weight: 70
url: /it/python-net/aspose.imaging.imageloadoptions/pngloadoptions/
---

**Summary:** The png load options.

**Module:** [aspose.imaging.imageloadoptions](/imaging/python-net/aspose.imaging.imageloadoptions/)

**Full Name:** aspose.imaging.imageloadoptions.PngLoadOptions

**Inheritance:** LoadOptions

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [PngLoadOptions()](#PngLoadOptions__1) | Inizializza una nuova istanza della classe [PngLoadOptions](/imaging/python-net/aspose.imaging.imageloadoptions/pngloadoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Ottiene o imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| concurrent_image_processing | bool | r/w | Ottiene o imposta un valore che indica se [concurrent image processing]. |
| data_background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Ottiene o imposta il colore di sfondo dell'[Image] [Color]. |
| data_recovery_mode | [DataRecoveryMode](/imaging/python-net/aspose.imaging/datarecoverymode/) | r/w | Ottiene o imposta la modalità di recupero dati. |
| [strict_mode](#strict_mode1) | bool | r/w | Ottiene o imposta un valore che indica se [strict mode]. |
| use_icc_profile_conversion | bool | r/w | Ottiene o imposta un valore che indica se la conversione del profilo ICC deve essere applicata. |


### Constructor: PngLoadOptions() {#PngLoadOptions__1}


```
 PngLoadOptions() 
```

Inizializza una nuova istanza della classe [PngLoadOptions](/imaging/python-net/aspose.imaging.imageloadoptions/pngloadoptions/).

### Property: strict_mode {#strict_mode1}

Ottiene o imposta un valore che indica se [strict mode].

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
# Modalità predefinita (non rigorosa) - lettura riuscita.
with Image.load(input_file_name) as image:
	image.save(output_file_name, PngOptions())

# Modalità rigorosa - ImageLoadException: fine inaspettata del file.
obj_init = PngLoadOptions()
obj_init.strict_mode = True
with Image.load(input_file_name, obj_init) as image:
	image.save(output_file_name, PngOptions())


```

