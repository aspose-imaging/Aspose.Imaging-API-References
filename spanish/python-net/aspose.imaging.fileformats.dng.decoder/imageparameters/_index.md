---
title: "Clase ImageParameters"
type: docs
weight: 20
url: /es/python-net/aspose.imaging.fileformats.dng.decoder/imageparameters/
---

**Summary:** Dng image parameters

**Module:** [aspose.imaging.fileformats.dng.decoder](/imaging/python-net/aspose.imaging.fileformats.dng.decoder/)

**Full Name:** aspose.imaging.fileformats.dng.decoder.ImageParameters

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| [camera_manufacturer](#camera_manufacturer1) | string | r | Obtiene el fabricante de la cámara. |
| [colors_count](#colors_count2) | int | r | Obtiene los colores. |
| [description](#description3) | string | r | Obtiene la descripción de los colores (RGBG, RGBE, GMCY o GBTG). |
| [dng_version](#dng_version4) | int | r | Obtiene la versión DNG. |
| [filters](#filters5) | int | r | Obtiene la máscara de bits que describe el orden de los píxeles de color en la matriz. |
| is_foveon | int | r | Obtiene la matriz is foveon. |
| [model](#model6) | string | r | Obtiene el modelo de la cámara. |
| [raw_count](#raw_count7) | int | r | Obtiene el número de imágenes RAW en el archivo (0 significa que el archivo no ha sido reconocido). |
| [software](#software8) | string | r | Obtiene el software. |
| [translation_cfa_dng](#translation_cfa_dng9) | string[] | r | Obtiene la matriz de traducción para el formato DNG de mosaico CFA. |
| xmp_data | string | r | Obtiene los datos XMP. |


### Property: camera_manufacturer {#camera_manufacturer1}

Obtiene el fabricante de la cámara.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: colors_count {#colors_count2}

Obtiene los colores.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: description {#description3}

Obtiene la descripción de los colores (RGBG, RGBE, GMCY o GBTG).

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: dng_version {#dng_version4}

Obtiene la versión DNG.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: filters {#filters5}

Obtiene la máscara de bits que describe el orden de los píxeles de color en la matriz.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: model {#model6}

Obtiene el modelo de la cámara.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: raw_count {#raw_count7}

Obtiene el número de imágenes RAW en el archivo (0 significa que el archivo no ha sido reconocido).

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: software {#software8}

Obtiene el software.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: translation_cfa_dng {#translation_cfa_dng9}

Obtiene la matriz de traducción para el formato DNG de mosaico CFA.

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

	# Exportar a PNG con opciones predeterminadas.
	dng_image.save(join(dir_, "test.png"), PngOptions())

# El fabricante de la cámara: Leica
# El modelo de la cámara: M8 Digital Camera
# Recuento de colores: 3
# Descripción de colores: RGBG
# Versión DNG: 16777216
# Número de imágenes RAW en el archivo: 1
# El software: 1.107
# Orden de los píxeles de color: 0b10110100101101001011010010110100
# Apertura: 0
# Descripción: 
# Distancia focal: 50
# Sensibilidad ISO: 160
# Número de serie de la imagen: 0
# Velocidad de obturación: 12
# Fecha de disparo: 8/3/2007 3:13:49 AM

```

