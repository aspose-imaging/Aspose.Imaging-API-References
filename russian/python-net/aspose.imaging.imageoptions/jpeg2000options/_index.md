---
title: "Класс Jpeg2000Options"
type: docs
weight: 150
url: /ru/python-net/aspose.imaging.imageoptions/jpeg2000options/
---

**Summary:** Create JPEG2000 (JP2) image files with our API, utilizing advanced wavelet technology<br/>            for coding lossless content. Benefit from support for various codecs, including<br/>            irreversible and lossless compression, as well as XMP metadata containers, ensuring<br/>            versatility and high-quality image creation tailored to your needs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.Jpeg2000Options

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Jpeg2000Options()](#Jpeg2000Options__1) | Инициализирует новый экземпляр класса [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/). |
| [Jpeg2000Options(jpeg_2000_options)](#Jpeg2000Options_jpeg_2000_options_2) | Инициализирует новый экземпляр класса [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Получает или задает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [codec](#codec1) | [Jpeg2000Codec](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000codec/) | r/w | Получает или задает кодек JPEG2000 |
| комментарии | string[] | r/w | Получает или задает маркеры комментариев Jpeg. |
| compression_ratios | int[] | r/w | Получает или задает массив коэффициентов сжатия.<br/>            Разные коэффициенты сжатия для последовательных слоёв.<br/>            Указанная для каждого уровня качества величина является желаемым<br/>            коэффициентом сжатия.<br/>            Требуются уменьшающиеся коэффициенты. |
| disposed | bool | r | Получает значение, указывающее, удалён ли этот экземпляр. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Получает или задает данные Exif. |
| full_frame | bool | r/w | Получает или задает значение, указывающее, включен ли [full frame]. |
| [irreversible](#irreversible2) | bool | r/w | Получает или задает значение, указывающее, использовать ли необратимый DWT 9-7 (true) или без потерь DWT 5-3 (по умолчанию). |
| keep_metadata | bool | r/w | Получает значение, указывающее, сохранять ли оригинальные метаданные изображения при экспорте. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Параметры multipage |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Получает или задает цветовую палитру. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Получает или задает параметры разрешения. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Получает или задает источник, в котором создаётся изображение. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Получает или задает параметры растеризации вектора. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Получает или задает контейнер метаданных XMP. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Создаёт поверхностную копию этого экземпляра. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Пытается установить экземпляр _metadata_, если этот экземпляр [Image](/imaging/python-net/aspose.imaging/image/) поддерживает и реализует экземпляр [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: Jpeg2000Options() {#Jpeg2000Options__1}


```
 Jpeg2000Options() 
```

Инициализирует новый экземпляр класса [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/).

### Constructor: Jpeg2000Options(jpeg_2000_options) {#Jpeg2000Options_jpeg_2000_options_2}


```
 Jpeg2000Options(jpeg_2000_options) 
```

Инициализирует новый экземпляр класса [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| jpeg_2000_options | [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/) | Параметры формата файла Jpeg2000, из которых копировать настройки. |

### Property: codec {#codec1}

Получает или задает кодек JPEG2000

**See also:**

**[Example # 1](#example_161)**: This example shows how to create a JPEG2000 image with the desired options an...

**[Example # 2](#example_163)**: This example shows how to create a PNG image and save it to JPEG2000 with the...


### Property: irreversible {#irreversible2}

Получает или задает значение, указывающее, использовать ли необратимый DWT 9-7 (true) или без потерь DWT 5-3 (по умолчанию).

**See also:**

**[Example # 1](#example_161)**: This example shows how to create a JPEG2000 image with the desired options an...

**[Example # 2](#example_163)**: This example shows how to create a PNG image and save it to JPEG2000 with the...


### Method: clone() {#clone__1}


```
 clone() 
```

Создаёт поверхностную копию этого экземпляра.

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Поверхностная копия этого экземпляра. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_2}


```
 try_set_metadata(metadata) 
```

Пытается установить экземпляр _metadata_, если этот экземпляр [Image](/imaging/python-net/aspose.imaging/image/) поддерживает и реализует экземпляр [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | Метаданные. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | True, если экземпляр [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) поддерживает и/или реализует экземпляр [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/); иначе — false. |


## **Examples**
### This example shows how to create a JPEG2000 image with the desired options and save it to a file. {#example_161}
``` python

from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import Jpeg2000Options
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Codec, Jpeg2000Image
from os.path import join as path_join     


dir_ = "c:\\temp"
create_options = Jpeg2000Options()
# Использовать необратимое дискретное вейвлет-преобразование 9-7
create_options.irreversible = True
# JP2 — это формат «контейнер» для кодовых потоков JPEG 2000.
# J2K — это необработанные сжатые данные без оболочки.
create_options.codec = Jpeg2000Codec.J2K
# Создать изображение JPEG2000 размером 100×100 пикселей.
with Jpeg2000Image(100, 100, create_options) as jpeg2000_image:
	graphics = Graphics(jpeg2000_image)
	# Заполнить всё изображение красным.
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, jpeg2000_image.bounds)
	# Сохранить в файл
	jpeg2000_image.save(path_join(dir_, "sample.output.j2k"))


```

### This example shows how to create a PNG image and save it to JPEG2000 with the desired options. {#example_163}
``` python

from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import Jpeg2000Options
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Codec
from aspose.imaging.fileformats.png import PngImage
from os.path import join as path_join


dir_ = "c:\\temp"
# Создать PNG‑изображение размером 100 × 100 px.
with PngImage(100, 100) as png_image:
	graphics = Graphics(png_image)
	# Заполнить всё изображение красным.
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	save_options = Jpeg2000Options()
	# Использовать необратимое дискретное вейвлет-преобразование 9-7
	save_options.irreversible = True
	# JP2 — это формат «контейнер» для кодовых потоков JPEG 2000.
	# J2K — это необработанные сжатые данные без оболочки.
	save_options.codec = Jpeg2000Codec.J2K
	# Сохранить в файл
	png_image.save(path_join(dir_, "output.j2k"), save_options)


```

