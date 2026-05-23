---
title: "Класс ImageOtherParameters"
type: docs
weight: 10
url: /ru/python-net/aspose.imaging.fileformats.dng.decoder/imageotherparameters/
---

**Summary:** Other image parameters

**Module:** [aspose.imaging.fileformats.dng.decoder](/imaging/python-net/aspose.imaging.fileformats.dng.decoder/)

**Full Name:** aspose.imaging.fileformats.dng.decoder.ImageOtherParameters

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [aperture](#aperture1) | float | r | Получает диафрагму. |
| artist | string | r | Получает автора изображения. |
| [description](#description2) | string | r | Получает описание изображения. |
| [focal_length](#focal_length3) | float | r | Получает длину фокусного расстояния. |
| gps_data | int[] | r | Получает данные GPS. |
| [iso_speed](#iso_speed4) | float | r | Получает чувствительность ISO. |
| [shot_order](#shot_order5) | int | r | Получает серийный номер изображения. |
| [shutter_speed](#shutter_speed6) | float | r | Получает выдержку. |
| [timestamp](#timestamp7) | int | r | Получает дату съёмки. |


### Property: aperture {#aperture1}

Получает диафрагму.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: description {#description2}

Получает описание изображения.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: focal_length {#focal_length3}

Получает длину фокусного расстояния.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: iso_speed {#iso_speed4}

Получает чувствительность ISO.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: shot_order {#shot_order5}

Получает серийный номер изображения.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: shutter_speed {#shutter_speed6}

Получает выдержку.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: timestamp {#timestamp7}

Получает дату съёмки.

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

	# Экспорт в PNG с настройками по умолчанию.
	dng_image.save(join(dir_, "test.png"), PngOptions())

# Производитель камеры:              Leica
# Модель камеры:                     M8 Digital Camera
# Количество цветов:                     3
# Описание цветов:               RGBG
# Версия DNG:                      16777216
# Количество RAW‑изображений в файле: 1
# Программное обеспечение:                         1.107
# Порядок цветовых пикселей:        0b10110100101101001011010010110100
# Диафрагма:                         0
# Описание:                      
# Фокусное расстояние:                     50
# Чувствительность ISO:                  160
# Серийный номер изображения:       0
# Скорость затвора:                    12
# Дата съёмки:                 8/3/2007 3:13:49 AM

```

