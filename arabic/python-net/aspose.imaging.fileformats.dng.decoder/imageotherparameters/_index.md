---
title: "فئة ImageOtherParameters"
type: docs
weight: 10
url: /ar/python-net/aspose.imaging.fileformats.dng.decoder/imageotherparameters/
---

**Summary:** Other image parameters

**Module:** [aspose.imaging.fileformats.dng.decoder](/imaging/python-net/aspose.imaging.fileformats.dng.decoder/)

**Full Name:** aspose.imaging.fileformats.dng.decoder.ImageOtherParameters

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| [aperture](#aperture1) | float | r | يحصل على الفتحة. |
| artist | string | r | يحصل على مؤلف الصورة. |
| [description](#description2) | string | r | يحصل على وصف الصورة. |
| [focal_length](#focal_length3) | float | r | يحصل على طول البؤرة. |
| gps_data | int[] | r | يحصل على بيانات GPS. |
| [iso_speed](#iso_speed4) | float | r | يحصل على حساسية ISO. |
| [shot_order](#shot_order5) | int | r | يحصل على الرقم التسلسلي للصورة. |
| [shutter_speed](#shutter_speed6) | float | r | يحصل على سرعة الغالق. |
| [timestamp](#timestamp7) | int | r | يحصل على تاريخ التصوير. |


### Property: aperture {#aperture1}

يحصل على الفتحة.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: description {#description2}

يحصل على وصف الصورة.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: focal_length {#focal_length3}

يحصل على طول البؤرة.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: iso_speed {#iso_speed4}

يحصل على حساسية ISO.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: shot_order {#shot_order5}

يحصل على الرقم التسلسلي للصورة.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: shutter_speed {#shutter_speed6}

يحصل على سرعة الغالق.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: timestamp {#timestamp7}

يحصل على تاريخ التصوير.

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

	# تصدير إلى PNG باستخدام الخيارات الافتراضية.
	dng_image.save(join(dir_, "test.png"), PngOptions())

# مصنّع الكاميرا:              Leica
# طراز الكاميرا:                     M8 Digital Camera
# عدد الألوان:                     3
# وصف الألوان:               RGBG
# إصدار DNG:                      16777216
# عدد صور RAW في الملف: 1
# البرنامج:                         1.107
# ترتيب بكسلات اللون:        0b10110100101101001011010010110100
# فتحة العدسة:                         0
# الوصف:                      
# البعد البؤري:                     50
# حساسية ISO:                  160
# الرقم التسلسلي للصورة:       0
# سرعة الغالق:                    12
# تاريخ التصوير:                 8/3/2007 3:13:49 AM

```

