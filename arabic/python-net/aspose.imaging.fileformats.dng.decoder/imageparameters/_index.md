---
title: "فئة ImageParameters"
type: docs
weight: 20
url: /ar/python-net/aspose.imaging.fileformats.dng.decoder/imageparameters/
---

**Summary:** Dng image parameters

**Module:** [aspose.imaging.fileformats.dng.decoder](/imaging/python-net/aspose.imaging.fileformats.dng.decoder/)

**Full Name:** aspose.imaging.fileformats.dng.decoder.ImageParameters

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| [camera_manufacturer](#camera_manufacturer1) | string | r | الحصول على شركة تصنيع الكاميرا. |
| [colors_count](#colors_count2) | int | r | الحصول على الألوان. |
| [description](#description3) | string | r | الحصول على وصف الألوان (RGBG,RGBE,GMCY, أو GBTG). |
| [dng_version](#dng_version4) | int | r | الحصول على نسخة DNG. |
| [filters](#filters5) | int | r | الحصول على قناع البت الذي يصف ترتيب بكسلات اللون في المصفوفة. |
| is_foveon | int | r | الحصول على مصفوفة is foveon. |
| [model](#model6) | string | r | الحصول على طراز الكاميرا. |
| [raw_count](#raw_count7) | int | r | الحصول على عدد صور RAW في الملف (0 يعني أن الملف لم يتم التعرف عليه). |
| [software](#software8) | string | r | الحصول على البرنامج. |
| [translation_cfa_dng](#translation_cfa_dng9) | string[] | r | الحصول على مصفوفة الترجمة لتنسيق CFA mosaic DNG. |
| xmp_data | string | r | يحصل على بيانات XMP. |


### Property: camera_manufacturer {#camera_manufacturer1}

الحصول على شركة تصنيع الكاميرا.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: colors_count {#colors_count2}

الحصول على الألوان.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: description {#description3}

الحصول على وصف الألوان (RGBG,RGBE,GMCY, أو GBTG).

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: dng_version {#dng_version4}

الحصول على نسخة DNG.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: filters {#filters5}

الحصول على قناع البت الذي يصف ترتيب بكسلات اللون في المصفوفة.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: model {#model6}

الحصول على طراز الكاميرا.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: raw_count {#raw_count7}

الحصول على عدد صور RAW في الملف (0 يعني أن الملف لم يتم التعرف عليه).

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: software {#software8}

الحصول على البرنامج.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: translation_cfa_dng {#translation_cfa_dng9}

الحصول على مصفوفة الترجمة لتنسيق CFA mosaic DNG.

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

