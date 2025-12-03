---
title: ImageParameters Class
type: docs
weight: 20
url: /python-net/aspose.imaging.fileformats.dng.decoder/imageparameters/
---

**Summary:** Dng image parameters

**Module:** [aspose.imaging.fileformats.dng.decoder](/imaging/python-net/aspose.imaging.fileformats.dng.decoder/)

**Full Name:** aspose.imaging.fileformats.dng.decoder.ImageParameters

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [camera_manufacturer](#camera_manufacturer1) | string | r | Gets the camera manufacturer. |
| [colors_count](#colors_count2) | int | r | Gets the colors. |
| [description](#description3) | string | r | Gets the description of colors (RGBG,RGBE,GMCY, or GBTG). |
| [dng_version](#dng_version4) | int | r | Gets the DNG version. |
| [filters](#filters5) | int | r | Gets the Bit mask describing the order of color pixels in the matrix. |
| is_foveon | int | r | Gets the is foveon matrix. |
| [model](#model6) | string | r | Gets the camera model. |
| [raw_count](#raw_count7) | int | r | Gets the number of RAW images in file (0 means that the file has not been recognized). |
| [software](#software8) | string | r | Gets the software. |
| [translation_cfa_dng](#translation_cfa_dng9) | string[] | r | Gets the translation array for CFA mosaic DNG format. |
| xmp_data | string | r | Gets the XMP data. |


### Property: camera_manufacturer {#camera_manufacturer1}

Gets the camera manufacturer.

**See also:**

**[Example # 1](#example_168)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: colors_count {#colors_count2}

Gets the colors.

**See also:**

**[Example # 1](#example_168)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: description {#description3}

Gets the description of colors (RGBG,RGBE,GMCY, or GBTG).

**See also:**

**[Example # 1](#example_168)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: dng_version {#dng_version4}

Gets the DNG version.

**See also:**

**[Example # 1](#example_168)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: filters {#filters5}

Gets the Bit mask describing the order of color pixels in the matrix.

**See also:**

**[Example # 1](#example_168)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: model {#model6}

Gets the camera model.

**See also:**

**[Example # 1](#example_168)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: raw_count {#raw_count7}

Gets the number of RAW images in file (0 means that the file has not been recognized).

**See also:**

**[Example # 1](#example_168)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: software {#software8}

Gets the software.

**See also:**

**[Example # 1](#example_168)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: translation_cfa_dng {#translation_cfa_dng9}

Gets the translation array for CFA mosaic DNG format.

**See also:**

**[Example # 1](#example_168)**: This example shows how to load a DNG image from a file, print its properties ...


## **Examples**
### This example shows how to load a DNG image from a file, print its properties and save it to PNG. {#example_168}
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

	# Export to PNG with default options.
	dng_image.save(join(dir_, "test.png"), PngOptions())

# The camera manufacturer:              Leica
# The camera model:                     M8 Digital Camera
# The colors count:                     3
# The colors description:               RGBG
# The DNG version:                      16777216
# The number of RAW images in the file: 1
# The software:                         1.107
# The order of the color pixels:        0b10110100101101001011010010110100
# The aperture:                         0
# The description:                      
# The focal length:                     50
# The ISO sensitivity:                  160
# The serial number of the image:       0
# The shutter speed:                    12
# The date of shooting:                 8/3/2007 3:13:49 AM

```

