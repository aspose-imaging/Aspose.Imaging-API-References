---
title: "ImageParameters-klass"
type: docs
weight: 20
url: /sv/python-net/aspose.imaging.fileformats.dng.decoder/imageparameters/
---

**Summary:** Dng image parameters

**Module:** [aspose.imaging.fileformats.dng.decoder](/imaging/python-net/aspose.imaging.fileformats.dng.decoder/)

**Full Name:** aspose.imaging.fileformats.dng.decoder.ImageParameters

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [camera_manufacturer](#camera_manufacturer1) | string | r | Hämtar kameratillverkaren. |
| [colors_count](#colors_count2) | int | r | Hämtar färgerna. |
| [description](#description3) | string | r | Hämtar beskrivningen av färger (RGBG, RGBE, GMCY eller GBTG). |
| [dng_version](#dng_version4) | int | r | Hämtar DNG-versionen. |
| [filters](#filters5) | int | r | Hämtar bitmasken som beskriver ordningen på färgpixlar i matrisen. |
| is_foveon | int | r | Hämtar is_foveon-matrisen. |
| [model](#model6) | string | r | Hämtar kameramodellen. |
| [raw_count](#raw_count7) | int | r | Hämtar antalet RAW-bilder i filen (0 betyder att filen inte har identifierats). |
| [software](#software8) | string | r | Hämtar programvaran. |
| [translation_cfa_dng](#translation_cfa_dng9) | string[] | r | Hämtar översättningsarrayen för CFA-mosaik DNG-format. |
| xmp_data | string | r | Hämtar XMP‑data. |


### Property: camera_manufacturer {#camera_manufacturer1}

Hämtar kameratillverkaren.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: colors_count {#colors_count2}

Hämtar färgerna.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: description {#description3}

Hämtar beskrivningen av färger (RGBG, RGBE, GMCY eller GBTG).

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: dng_version {#dng_version4}

Hämtar DNG-versionen.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: filters {#filters5}

Hämtar bitmasken som beskriver ordningen på färgpixlar i matrisen.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: model {#model6}

Hämtar kameramodellen.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: raw_count {#raw_count7}

Hämtar antalet RAW-bilder i filen (0 betyder att filen inte har identifierats).

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: software {#software8}

Hämtar programvaran.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: translation_cfa_dng {#translation_cfa_dng9}

Hämtar översättningsarrayen för CFA-mosaik DNG-format.

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

	# Exportera till PNG med standardalternativ.
	dng_image.save(join(dir_, "test.png"), PngOptions())

# Kameratillverkaren:              Leica
# Kameramodellen:                     M8 Digital Camera
# Antalet färger:                     3
# Färgbeskrivning:               RGBG
# DNG-versionen:                      16777216
# Antalet RAW-bilder i filen: 1
# Mjukvaran:                         1.107
# Färgpixelordning:        0b10110100101101001011010010110100
# Bländaren:                         0
# Beskrivning:                      
# Brännvidd:                     50
# ISO-känsligheten:                  160
# Bildens serienummer:       0
# Slutartid:                    12
# Fotodatum:                 8/3/2007 3:13:49 AM

```

