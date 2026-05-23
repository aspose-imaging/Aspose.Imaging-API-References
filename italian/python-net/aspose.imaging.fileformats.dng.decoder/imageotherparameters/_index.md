---
title: "Classe ImageOtherParameters"
type: docs
weight: 10
url: /it/python-net/aspose.imaging.fileformats.dng.decoder/imageotherparameters/
---

**Summary:** Other image parameters

**Module:** [aspose.imaging.fileformats.dng.decoder](/imaging/python-net/aspose.imaging.fileformats.dng.decoder/)

**Full Name:** aspose.imaging.fileformats.dng.decoder.ImageOtherParameters

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| [aperture](#aperture1) | float | r | Ottiene l'apertura. |
| artist | string | r | Ottiene l'autore dell'immagine. |
| [description](#description2) | string | r | Ottiene la descrizione dell'immagine. |
| [focal_length](#focal_length3) | float | r | Ottiene la lunghezza della focale. |
| gps_data | int[] | r | Ottiene i dati GPS. |
| [iso_speed](#iso_speed4) | float | r | Ottiene la sensibilità ISO. |
| [shot_order](#shot_order5) | int | r | Ottiene il numero di serie dell'immagine. |
| [shutter_speed](#shutter_speed6) | float | r | Ottiene la velocità dell'otturatore. |
| [timestamp](#timestamp7) | int | r | Ottiene la data di scatto. |


### Property: aperture {#aperture1}

Ottiene l'apertura.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: description {#description2}

Ottiene la descrizione dell'immagine.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: focal_length {#focal_length3}

Ottiene la lunghezza della focale.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: iso_speed {#iso_speed4}

Ottiene la sensibilità ISO.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: shot_order {#shot_order5}

Ottiene il numero di serie dell'immagine.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: shutter_speed {#shutter_speed6}

Ottiene la velocità dell'otturatore.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: timestamp {#timestamp7}

Ottiene la data di scatto.

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

