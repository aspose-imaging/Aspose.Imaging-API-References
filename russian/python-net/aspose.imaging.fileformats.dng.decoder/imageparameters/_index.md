---
title: "ImageParameters Класс"
type: docs
weight: 20
url: /ru/python-net/aspose.imaging.fileformats.dng.decoder/imageparameters/
---

**Summary:** Dng image parameters

**Module:** [aspose.imaging.fileformats.dng.decoder](/imaging/python-net/aspose.imaging.fileformats.dng.decoder/)

**Full Name:** aspose.imaging.fileformats.dng.decoder.ImageParameters

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [camera_manufacturer](#camera_manufacturer1) | string | r | Получает производителя камеры. |
| [colors_count](#colors_count2) | int | r | Получает цвета. |
| [description](#description3) | string | r | Получает описание цветов (RGBG, RGBE, GMCY или GBTG). |
| [dng_version](#dng_version4) | int | r | Получает версию DNG. |
| [filters](#filters5) | int | r | Получает битовую маску, описывающую порядок цветовых пикселей в матрице. |
| is_foveon | int | r | Получает матрицу is foveon. |
| [model](#model6) | string | r | Получает модель камеры. |
| [raw_count](#raw_count7) | int | r | Получает количество RAW-изображений в файле (0 означает, что файл не распознан). |
| [software](#software8) | string | r | Получает программное обеспечение. |
| [translation_cfa_dng](#translation_cfa_dng9) | string[] | r | Получает массив преобразования для формата CFA-мозаики DNG. |
| xmp_data | string | r | Получает данные XMP. |


### Property: camera_manufacturer {#camera_manufacturer1}

Получает производителя камеры.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: colors_count {#colors_count2}

Получает цвета.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: description {#description3}

Получает описание цветов (RGBG, RGBE, GMCY или GBTG).

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: dng_version {#dng_version4}

Получает версию DNG.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: filters {#filters5}

Получает битовую маску, описывающую порядок цветовых пикселей в матрице.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: model {#model6}

Получает модель камеры.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: raw_count {#raw_count7}

Получает количество RAW-изображений в файле (0 означает, что файл не распознан).

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: software {#software8}

Получает программное обеспечение.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: translation_cfa_dng {#translation_cfa_dng9}

Получает массив преобразования для формата CFA-мозаики DNG.

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

