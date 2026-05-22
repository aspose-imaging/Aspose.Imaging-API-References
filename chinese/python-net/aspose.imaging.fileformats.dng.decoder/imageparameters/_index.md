---
title: "ImageParameters 类"
type: docs
weight: 20
url: /zh/python-net/aspose.imaging.fileformats.dng.decoder/imageparameters/
---

**Summary:** Dng image parameters

**Module:** [aspose.imaging.fileformats.dng.decoder](/imaging/python-net/aspose.imaging.fileformats.dng.decoder/)

**Full Name:** aspose.imaging.fileformats.dng.decoder.ImageParameters

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| [camera_manufacturer](#camera_manufacturer1) | string | r | 获取相机制造商。 |
| [colors_count](#colors_count2) | int | r | 获取颜色。 |
| [description](#description3) | string | r | 获取颜色的描述（RGBG、RGBE、GMCY 或 GBTG）。 |
| [dng_version](#dng_version4) | int | r | 获取 DNG 版本。 |
| [filters](#filters5) | int | r | 获取描述矩阵中颜色像素顺序的位掩码。 |
| is_foveon | int | r | 获取 is_foveon 矩阵。 |
| [model](#model6) | string | r | 获取相机型号。 |
| [raw_count](#raw_count7) | int | r | 获取文件中 RAW 图像的数量（0 表示文件未被识别）。 |
| [software](#software8) | string | r | 获取软件。 |
| [translation_cfa_dng](#translation_cfa_dng9) | string[] | r | 获取 CFA 马赛克 DNG 格式的转换数组。 |
| xmp_data | string | r | 获取 XMP 数据。 |


### Property: camera_manufacturer {#camera_manufacturer1}

获取相机制造商。

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: colors_count {#colors_count2}

获取颜色。

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: description {#description3}

获取颜色的描述（RGBG、RGBE、GMCY 或 GBTG）。

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: dng_version {#dng_version4}

获取 DNG 版本。

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: filters {#filters5}

获取描述矩阵中颜色像素顺序的位掩码。

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: model {#model6}

获取相机型号。

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: raw_count {#raw_count7}

获取文件中 RAW 图像的数量（0 表示文件未被识别）。

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: software {#software8}

获取软件。

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: translation_cfa_dng {#translation_cfa_dng9}

获取 CFA 马赛克 DNG 格式的转换数组。

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

