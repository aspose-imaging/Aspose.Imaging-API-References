---
title: "ImageOtherParameters Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.imaging.fileformats.dng.decoder/imageotherparameters/
---

**Summary:** Other image parameters

**Module:** [aspose.imaging.fileformats.dng.decoder](/imaging/python-net/aspose.imaging.fileformats.dng.decoder/)

**Full Name:** aspose.imaging.fileformats.dng.decoder.ImageOtherParameters

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| [aperture](#aperture1) | float | r | Liefert die Blende. |
| artist | string | r | Liefert den Autor des Bildes. |
| [description](#description2) | string | r | Liefert die Bildbeschreibung. |
| [focal_length](#focal_length3) | float | r | Liefert die Brennweite. |
| gps_data | int[] | r | Liefert die GPS-Daten. |
| [iso_speed](#iso_speed4) | float | r | Liefert die ISO-Empfindlichkeit. |
| [shot_order](#shot_order5) | int | r | Liefert die Seriennummer des Bildes. |
| [shutter_speed](#shutter_speed6) | float | r | Liefert die Verschlusszeit. |
| [timestamp](#timestamp7) | int | r | Liefert das Aufnahmedatum. |


### Property: aperture {#aperture1}

Liefert die Blende.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: description {#description2}

Liefert die Bildbeschreibung.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: focal_length {#focal_length3}

Liefert die Brennweite.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: iso_speed {#iso_speed4}

Liefert die ISO-Empfindlichkeit.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: shot_order {#shot_order5}

Liefert die Seriennummer des Bildes.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: shutter_speed {#shutter_speed6}

Liefert die Verschlusszeit.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: timestamp {#timestamp7}

Liefert das Aufnahmedatum.

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

	# Exportieren Sie nach PNG mit den Standardeinstellungen.
	dng_image.save(join(dir_, "test.png"), PngOptions())

# Der Kamerahersteller:              Leica
# Das Kameramodell:                     M8 Digital Camera
# Die Farbanzahl:                     3
# Die Farbbeschreibung:               RGBG
# Die DNG-Version:                      16777216
# Die Anzahl der RAW-Bilder in der Datei: 1
# Die Software:                         1.107
# Die Reihenfolge der Farbpixel:        0b10110100101101001011010010110100
# Die Blende:                         0
# Die Beschreibung:                      
# Die Brennweite:                     50
# Die ISO-Empfindlichkeit:                  160
# Die Seriennummer des Bildes:       0
# Die Verschlusszeit:                    12
# Das Aufnahmedatum:                 8/3/2007 3:13:49 AM

```

