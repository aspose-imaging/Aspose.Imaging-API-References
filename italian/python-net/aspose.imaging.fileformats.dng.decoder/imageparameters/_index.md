---
title: "ImageParameters Classe"
type: docs
weight: 20
url: /it/python-net/aspose.imaging.fileformats.dng.decoder/imageparameters/
---

**Summary:** Dng image parameters

**Module:** [aspose.imaging.fileformats.dng.decoder](/imaging/python-net/aspose.imaging.fileformats.dng.decoder/)

**Full Name:** aspose.imaging.fileformats.dng.decoder.ImageParameters

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| [camera_manufacturer](#camera_manufacturer1) | string | r | Ottiene il produttore della fotocamera. |
| [colors_count](#colors_count2) | int | r | Ottiene i colori. |
| [description](#description3) | string | r | Ottiene la descrizione dei colori (RGBG,RGBE,GMCY o GBTG). |
| [dng_version](#dng_version4) | int | r | Ottiene la versione DNG. |
| [filters](#filters5) | int | r | Ottiene la maschera di bit che descrive l'ordine dei pixel di colore nella matrice. |
| is_foveon | int | r | Ottiene la matrice is foveon. |
| [model](#model6) | string | r | Ottiene il modello della fotocamera. |
| [raw_count](#raw_count7) | int | r | Ottiene il numero di immagini RAW nel file (0 indica che il file non è stato riconosciuto). |
| [software](#software8) | string | r | Ottiene il software. |
| [translation_cfa_dng](#translation_cfa_dng9) | string[] | r | Ottiene l'array di traduzione per il formato DNG a mosaico CFA. |
| xmp_data | string | r | Ottiene i dati XMP. |


### Property: camera_manufacturer {#camera_manufacturer1}

Ottiene il produttore della fotocamera.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: colors_count {#colors_count2}

Ottiene i colori.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: description {#description3}

Ottiene la descrizione dei colori (RGBG,RGBE,GMCY o GBTG).

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: dng_version {#dng_version4}

Ottiene la versione DNG.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: filters {#filters5}

Ottiene la maschera di bit che descrive l'ordine dei pixel di colore nella matrice.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: model {#model6}

Ottiene il modello della fotocamera.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: raw_count {#raw_count7}

Ottiene il numero di immagini RAW nel file (0 indica che il file non è stato riconosciuto).

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: software {#software8}

Ottiene il software.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: translation_cfa_dng {#translation_cfa_dng9}

Ottiene l'array di traduzione per il formato DNG a mosaico CFA.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


## **Examples**
### This example shows how to load a DNG image from a file, print its properties and save it to PNG. {#example_169}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dng import DngImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join


dir_: str = "c:\\temp"
with Image.load(join(dir_, "test.dng")) as image:
	dng_image = aspycore.as_of(image, DngImage)
	raw_data = dng_image.img_data
	parameters = raw_data.image_data_parameters
	if parameters is not None:
		print("The camera manufacturer:              ", str(parameters.camera_manufacturer))
		print("The camera model:                     ", str(parameters.model))
		print("The colors count:                     ", str(parameters.colors_count))
		print("The colors description:               ", str(parameters.description))
		print("The DNG version:                      ", str(parameters.dng_version))
		print("The number of RAW images in the file: ", str(parameters.raw_count))
		print("The software:                         ", str(parameters.software))
		print("The order of the color pixels:        ", bin(parameters.filters))
		translation_cfa_dng = parameters.translation_cfa_dng
		if translation_cfa_dng is not None:
			print("The translation array for CFA mosaic :", translation_cfa_dng.length)
			for s in translation_cfa_dng:
				print("- ", s)

	other_parameters = raw_data.image_other_parameters
	if other_parameters is not None:
		print("The aperture:                         ", other_parameters.aperture)
		print("The description:                      ", other_parameters.description)
		print("The focal length:                     ", other_parameters.focal_length)
		print("The ISO sensitivity:                  ", other_parameters.iso_speed)
		print("The serial number of the image:       ", other_parameters.shot_order)
		print("The shutter speed:                    ", other_parameters.shutter_speed)
		print("The date of shooting:                 ", System.DateTime.from_file_time(other_parameters.timestamp))

	# Esporta in PNG con le opzioni predefinite.
	dng_image.save(join(dir_, "test.png"), PngOptions())

# Il produttore della fotocamera:              Leica
# Il modello della fotocamera:                     M8 Digital Camera
# Il conteggio dei colori:                     3
# La descrizione dei colori:               RGBG
# La versione DNG:                      16777216
# Il numero di immagini RAW nel file: 1
# Il software:                         1.107
# L'ordine dei pixel di colore:        0b10110100101101001011010010110100
# L'apertura:                         0
# La descrizione:                      
# La lunghezza focale:                     50
# La sensibilità ISO:                  160
# Il numero di serie dell'immagine:       0
# La velocità dell'otturatore:                    12
# La data di scatto:                 8/3/2007 3:13:49 AM

```

