---
title: "ImageParameters Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.imaging.fileformats.dng.decoder/imageparameters/
---

**Summary:** Dng image parameters

**Module:** [aspose.imaging.fileformats.dng.decoder](/imaging/python-net/aspose.imaging.fileformats.dng.decoder/)

**Full Name:** aspose.imaging.fileformats.dng.decoder.ImageParameters

## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| [camera_manufacturer](#camera_manufacturer1) | string | r | Kamera üreticisini alır. |
| [colors_count](#colors_count2) | int | r | Renkleri alır. |
| [description](#description3) | string | r | Renklerin açıklamasını alır (RGBG,RGBE,GMCY veya GBTG). |
| [dng_version](#dng_version4) | int | r | DNG sürümünü alır. |
| [filters](#filters5) | int | r | Matristeki renk piksel sırasını tanımlayan bit maskesini alır. |
| is_foveon | int | r | Foveon matrisini alır. |
| [model](#model6) | string | r | Kamera modelini alır. |
| [raw_count](#raw_count7) | int | r | Dosyadaki RAW görüntü sayısını alır (0, dosyanın tanınmadığını gösterir). |
| [software](#software8) | string | r | Yazılımı alır. |
| [translation_cfa_dng](#translation_cfa_dng9) | string[] | r | CFA mozaik DNG formatı için çeviri dizisini alır. |
| xmp_data | string | r | XMP verilerini alır. |


### Property: camera_manufacturer {#camera_manufacturer1}

Kamera üreticisini alır.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: colors_count {#colors_count2}

Renkleri alır.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: description {#description3}

Renklerin açıklamasını alır (RGBG,RGBE,GMCY veya GBTG).

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: dng_version {#dng_version4}

DNG sürümünü alır.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: filters {#filters5}

Matristeki renk piksel sırasını tanımlayan bit maskesini alır.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: model {#model6}

Kamera modelini alır.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: raw_count {#raw_count7}

Dosyadaki RAW görüntü sayısını alır (0, dosyanın tanınmadığını gösterir).

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: software {#software8}

Yazılımı alır.

**See also:**

**[Example # 1](#example_169)**: This example shows how to load a DNG image from a file, print its properties ...


### Property: translation_cfa_dng {#translation_cfa_dng9}

CFA mozaik DNG formatı için çeviri dizisini alır.

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

	# Varsayılan seçeneklerle PNG olarak dışa aktar.
	dng_image.save(join(dir_, "test.png"), PngOptions())

# Kamera üreticisi:              Leica
# Kamera modeli:                     M8 Digital Camera
# Renk sayısı:                     3
# Renk açıklaması:               RGBG
# DNG sürümü:                      16777216
# Dosyadaki RAW görüntü sayısı: 1
# Yazılım:                         1.107
# Renk piksellerinin sırası:        0b10110100101101001011010010110100
# Diyafram:                         0
# Açıklama:                      
# Odak uzaklığı:                     50
# ISO duyarlılığı:                  160
# Görüntünün seri numarası:       0
# Enstantane hızı:                    12
# Çekim tarihi:                 8/3/2007 3:13:49 AM

```

