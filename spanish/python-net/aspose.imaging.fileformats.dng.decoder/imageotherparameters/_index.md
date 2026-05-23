---
title: "Clase ImageOtherParameters"
type: docs
weight: 10
url: /es/python-net/aspose.imaging.fileformats.dng.decoder/imageotherparameters/
---

**Summary:** Other image parameters

**Module:** [aspose.imaging.fileformats.dng.decoder](/imaging/python-net/aspose.imaging.fileformats.dng.decoder/)

**Full Name:** aspose.imaging.fileformats.dng.decoder.ImageOtherParameters

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| [aperture](#aperture1) | float | r | Obtiene la apertura. |
| artist | string | r | Obtiene el autor de la imagen. |
| [description](#description2) | string | r | Obtiene la descripción de la imagen. |
| [focal_length](#focal_length3) | float | r | Obtiene la longitud focal. |
| gps_data | int[] | r | Obtiene los datos GPS. |
| [iso_speed](#iso_speed4) | float | r | Obtiene la sensibilidad ISO. |
| [shot_order](#shot_order5) | int | r | Obtiene el número de serie de la imagen. |
| [shutter_speed](#shutter_speed6) | float | r | Obtiene la velocidad de obturación. |
| [timestamp](#timestamp7) | int | r | Obtiene la fecha de captura. |


### Property: aperture {#aperture1}

Obtiene la apertura.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: description {#description2}

Obtiene la descripción de la imagen.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: focal_length {#focal_length3}

Obtiene la longitud focal.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: iso_speed {#iso_speed4}

Obtiene la sensibilidad ISO.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: shot_order {#shot_order5}

Obtiene el número de serie de la imagen.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: shutter_speed {#shutter_speed6}

Obtiene la velocidad de obturación.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: timestamp {#timestamp7}

Obtiene la fecha de captura.

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

