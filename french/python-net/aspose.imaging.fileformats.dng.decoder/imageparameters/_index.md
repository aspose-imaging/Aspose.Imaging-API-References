---
title: "Classe ImageParameters"
type: docs
weight: 20
url: /fr/python-net/aspose.imaging.fileformats.dng.decoder/imageparameters/
---

**Summary:** Dng image parameters

**Module:** [aspose.imaging.fileformats.dng.decoder](/imaging/python-net/aspose.imaging.fileformats.dng.decoder/)

**Full Name:** aspose.imaging.fileformats.dng.decoder.ImageParameters

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [camera_manufacturer](#camera_manufacturer1) | string | r | Obtient le fabricant de l'appareil photo. |
| [colors_count](#colors_count2) | int | r | Obtient les couleurs. |
| [description](#description3) | string | r | Obtient la description des couleurs (RGBG, RGBE, GMCY ou GBTG). |
| [dng_version](#dng_version4) | int | r | Obtient la version DNG. |
| [filters](#filters5) | int | r | Obtient le masque de bits décrivant l'ordre des pixels de couleur dans la matrice. |
| is_foveon | int | r | Obtient la matrice is foveon. |
| [model](#model6) | string | r | Obtient le modèle de l'appareil photo. |
| [raw_count](#raw_count7) | int | r | Obtient le nombre d'images RAW dans le fichier (0 signifie que le fichier n'a pas été reconnu). |
| [software](#software8) | string | r | Obtient le logiciel. |
| [translation_cfa_dng](#translation_cfa_dng9) | string[] | r | Obtient le tableau de traduction pour le format DNG en mosaïque CFA. |
| xmp_data | string | r | Obtient les données XMP. |


### Property: camera_manufacturer {#camera_manufacturer1}

Obtient le fabricant de l'appareil photo.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: colors_count {#colors_count2}

Obtient les couleurs.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: description {#description3}

Obtient la description des couleurs (RGBG, RGBE, GMCY ou GBTG).

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: dng_version {#dng_version4}

Obtient la version DNG.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: filters {#filters5}

Obtient le masque de bits décrivant l'ordre des pixels de couleur dans la matrice.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: model {#model6}

Obtient le modèle de l'appareil photo.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: raw_count {#raw_count7}

Obtient le nombre d'images RAW dans le fichier (0 signifie que le fichier n'a pas été reconnu).

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: software {#software8}

Obtient le logiciel.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: translation_cfa_dng {#translation_cfa_dng9}

Obtient le tableau de traduction pour le format DNG en mosaïque CFA.

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

