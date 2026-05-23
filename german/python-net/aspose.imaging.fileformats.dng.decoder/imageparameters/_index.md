---
title: "ImageParameters Klasse"
type: docs
weight: 20
url: /de/python-net/aspose.imaging.fileformats.dng.decoder/imageparameters/
---

**Summary:** Dng image parameters

**Module:** [aspose.imaging.fileformats.dng.decoder](/imaging/python-net/aspose.imaging.fileformats.dng.decoder/)

**Full Name:** aspose.imaging.fileformats.dng.decoder.ImageParameters

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| [camera_manufacturer](#camera_manufacturer1) | string | r | Liest den Kamerahersteller. |
| [colors_count](#colors_count2) | int | r | Liest die Farben. |
| [description](#description3) | string | r | Liest die Beschreibung der Farben (RGBG, RGBE, GMCY oder GBTG). |
| [dng_version](#dng_version4) | int | r | Liest die DNG-Version. |
| [filters](#filters5) | int | r | Liest die Bitmaske, die die Reihenfolge der Farbpixel in der Matrix beschreibt. |
| is_foveon | int | r | Liest die is foveon-Matrix. |
| [model](#model6) | string | r | Liest das Kameramodell. |
| [raw_count](#raw_count7) | int | r | Liest die Anzahl der RAW-Bilder in der Datei (0 bedeutet, dass die Datei nicht erkannt wurde). |
| [software](#software8) | string | r | Liest die Software. |
| [translation_cfa_dng](#translation_cfa_dng9) | string[] | r | Liest das Übersetzungsarray für das CFA-Mosaik-DNG-Format. |
| xmp_data | string | r | Liefert die XMP-Daten. |


### Property: camera_manufacturer {#camera_manufacturer1}

Liest den Kamerahersteller.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: colors_count {#colors_count2}

Liest die Farben.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: description {#description3}

Liest die Beschreibung der Farben (RGBG, RGBE, GMCY oder GBTG).

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: dng_version {#dng_version4}

Liest die DNG-Version.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: filters {#filters5}

Liest die Bitmaske, die die Reihenfolge der Farbpixel in der Matrix beschreibt.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: model {#model6}

Liest das Kameramodell.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: raw_count {#raw_count7}

Liest die Anzahl der RAW-Bilder in der Datei (0 bedeutet, dass die Datei nicht erkannt wurde).

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: software {#software8}

Liest die Software.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: translation_cfa_dng {#translation_cfa_dng9}

Liest das Übersetzungsarray für das CFA-Mosaik-DNG-Format.

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

