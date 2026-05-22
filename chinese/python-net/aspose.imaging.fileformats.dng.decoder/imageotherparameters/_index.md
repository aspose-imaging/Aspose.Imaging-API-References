---
title: "ImageOtherParameters 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.fileformats.dng.decoder/imageotherparameters/
---

**Summary:** Other image parameters

**Module:** [aspose.imaging.fileformats.dng.decoder](/imaging/python-net/aspose.imaging.fileformats.dng.decoder/)

**Full Name:** aspose.imaging.fileformats.dng.decoder.ImageOtherParameters

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| [aperture](#aperture1) | float | r | 获取光圈。 |
| artist | string | r | 获取图像的作者。 |
| [description](#description2) | string | r | 获取图像描述。 |
| [focal_length](#focal_length3) | float | r | 获取焦距的长度。 |
| gps_data | int[] | r | 获取 GPS 数据。 |
| [iso_speed](#iso_speed4) | float | r | 获取 ISO 感光度。 |
| [shot_order](#shot_order5) | int | r | 获取图像的序列号。 |
| [shutter_speed](#shutter_speed6) | float | r | 获取快门速度。 |
| [timestamp](#timestamp7) | int | r | 获取拍摄日期。 |


### Property: aperture {#aperture1}

获取光圈。

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: description {#description2}

获取图像描述。

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: focal_length {#focal_length3}

获取焦距的长度。

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: iso_speed {#iso_speed4}

获取 ISO 感光度。

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: shot_order {#shot_order5}

获取图像的序列号。

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: shutter_speed {#shutter_speed6}

获取快门速度。

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: timestamp {#timestamp7}

获取拍摄日期。

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

	# 使用默认选项导出为 PNG。
	dng_image.save(join(dir_, "test.png"), PngOptions())

# 相机制造商：              Leica
# 相机型号：                     M8 Digital Camera
# 颜色数量：                     3
# 颜色描述：               RGBG
# DNG 版本：                      16777216
# 文件中 RAW 图像的数量： 1
# 软件版本：                         1.107
# 颜色像素的顺序：        0b10110100101101001011010010110100
# 光圈：                         0
# 描述：                      
# 焦距：                     50
# ISO 感光度：                  160
# 图像序列号：       0
# 快门速度：                    12
# 拍摄日期：                 8/3/2007 3:13:49 AM

```

