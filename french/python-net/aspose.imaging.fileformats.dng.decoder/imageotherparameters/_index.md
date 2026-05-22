---
title: "Classe ImageOtherParameters"
type: docs
weight: 10
url: /fr/python-net/aspose.imaging.fileformats.dng.decoder/imageotherparameters/
---

**Summary:** Other image parameters

**Module:** [aspose.imaging.fileformats.dng.decoder](/imaging/python-net/aspose.imaging.fileformats.dng.decoder/)

**Full Name:** aspose.imaging.fileformats.dng.decoder.ImageOtherParameters

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [aperture](#aperture1) | float | r | Obtient l'ouverture. |
| artist | string | r | Obtient l'auteur de l'image. |
| [description](#description2) | string | r | Obtient la description de l'image. |
| [focal_length](#focal_length3) | float | r | Obtient la longueur focale. |
| gps_data | int[] | r | Obtient les données GPS. |
| [iso_speed](#iso_speed4) | float | r | Obtient la sensibilité ISO. |
| [shot_order](#shot_order5) | int | r | Obtient le numéro de série de l'image. |
| [shutter_speed](#shutter_speed6) | float | r | Obtient la vitesse d'obturation. |
| [timestamp](#timestamp7) | int | r | Obtient la date de prise de vue. |


### Property: aperture {#aperture1}

Obtient l'ouverture.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: description {#description2}

Obtient la description de l'image.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: focal_length {#focal_length3}

Obtient la longueur focale.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: iso_speed {#iso_speed4}

Obtient la sensibilité ISO.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: shot_order {#shot_order5}

Obtient le numéro de série de l'image.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: shutter_speed {#shutter_speed6}

Obtient la vitesse d'obturation.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: timestamp {#timestamp7}

Obtient la date de prise de vue.

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

	# Exportez en PNG avec les options par défaut.
	dng_image.save(join(dir_, "test.png"), PngOptions())

# Le fabricant de l'appareil photo :              Leica
# Le modèle de l'appareil photo :                     M8 Digital Camera
# Le nombre de couleurs :                     3
# La description des couleurs :               RGBG
# La version DNG :                      16777216
# Le nombre d'images RAW dans le fichier : 1
# Le logiciel :                         1.107
# L'ordre des pixels de couleur :        0b10110100101101001011010010110100
# L'ouverture :                         0
# La description :                      
# La distance focale :                     50
# La sensibilité ISO :                  160
# Le numéro de série de l'image :       0
# La vitesse d'obturation :                    12
# La date de prise de vue :                 8/3/2007 3:13:49 AM

```

