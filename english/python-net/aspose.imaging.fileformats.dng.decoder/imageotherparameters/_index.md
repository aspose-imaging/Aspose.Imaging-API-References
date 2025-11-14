---
title: ImageOtherParameters Class
type: docs
weight: 10
url: /python-net/aspose.imaging.fileformats.dng.decoder/imageotherparameters/
---

**Summary:** Other image parameters

**Module:** [aspose.imaging.fileformats.dng.decoder](/imaging/python-net/aspose.imaging.fileformats.dng.decoder/)

**Full Name:** aspose.imaging.fileformats.dng.decoder.ImageOtherParameters

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [aperture](#aperture1) | float | r | Gets the aperture. |
| artist | string | r | Gets the author of image. |
| [description](#description2) | string | r | Gets the image description. |
| [focal_length](#focal_length3) | float | r | Gets the length of the focal. |
| gps_data | int[] | r | Gets the GPS data. |
| [iso_speed](#iso_speed4) | float | r | Gets the ISO sensitivity. |
| [shot_order](#shot_order5) | int | r | Gets serial number of image. |
| [shutter_speed](#shutter_speed6) | float | r | Gets the shutter speed. |
| [timestamp](#timestamp7) | int | r | Gets the date of shooting. |


### Property: aperture {#aperture1}

Gets the aperture.

**See also:**

**[Example # 1](#example_156)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: description {#description2}

Gets the image description.

**See also:**

**[Example # 1](#example_156)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: focal_length {#focal_length3}

Gets the length of the focal.

**See also:**

**[Example # 1](#example_156)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: iso_speed {#iso_speed4}

Gets the ISO sensitivity.

**See also:**

**[Example # 1](#example_156)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: shot_order {#shot_order5}

Gets serial number of image.

**See also:**

**[Example # 1](#example_156)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: shutter_speed {#shutter_speed6}

Gets the shutter speed.

**See also:**

**[Example # 1](#example_156)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: timestamp {#timestamp7}

Gets the date of shooting.

**See also:**

**[Example # 1](#example_156)**: This example shows how to load a DNG image from a file, print its properties ...


## **Examples**
### This example shows how to load a DNG image from a file, print its properties and save it to PNG. {#example_156}
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

