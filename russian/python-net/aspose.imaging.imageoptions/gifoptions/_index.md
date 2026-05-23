---
title: "Класс GifOptions"
type: docs
weight: 120
url: /ru/python-net/aspose.imaging.imageoptions/gifoptions/
---

**Summary:** The API for Graphical Interchange Format (GIF) raster image file creation offers<br/>            developers comprehensive options for generating GIF images with precise<br/>            control. With features to set background color, color palette, resolution,<br/>            interlaced type, transparent color, XMP metadata container, and image<br/>            compression, this API ensures flexibility and efficiency in creating optimized<br/>            and visually appealing GIFs tailored to specific application requirements.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.GifOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | Инициализирует новый экземпляр класса [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/). |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | Инициализирует новый экземпляр класса [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Получает или задаёт цвет фона. |
| background_color_index | System.Byte | r/w | Получает или задаёт индекс цвета фона GIF. |
| buffer_size_hint | int | r/w | Получает или задает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| color_resolution | System.Byte | r/w | Получает или задаёт разрешение цвета GIF. |
| disposed | bool | r | Получает значение, указывающее, удалён ли этот экземпляр. |
| do_palette_correction | bool | r/w | Получает или задаёт значение, указывающее, применяется ли коррекция палитры. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Получает или задает данные Exif. |
| full_frame | bool | r/w | Получает или задает значение, указывающее, включен ли [full frame]. |
| has_trailer | bool | r/w | Получает или задаёт значение, указывающее, имеет ли GIF трейлер. |
| has_transparent_color | System.Nullable`1[[System.Boolean]] | r/w | Получает или задаёт значение, указывающее, имеет ли изображение GIF прозрачный цвет. <br/>            Если возвращаемое значение **None**, это свойство переопределяется контекстом исходного изображения. |
| interlaced | bool | r/w | True, если изображение должно быть чересстрочным. |
| is_palette_sorted | bool | r/w | Получает или задаёт значение, указывающее, отсортированы ли элементы палитры. |
| keep_metadata | bool | r/w | Получает значение, указывающее, сохранять ли оригинальные метаданные изображения при экспорте. |
| loops_count | int | r/w | Получает или задаёт количество циклов (по умолчанию 1 цикл) |
| max_diff | int | r/w | Получает или задаёт максимальную допустимую разницу пикселей. Если значение больше нуля, будет использовано сжатие с потерями.<br/>            Рекомендуемое значение для оптимального сжатия с потерями — 80. 30 соответствует очень лёгкому сжатию, 200 — сильному.<br/>            Наилучший результат достигается при небольших потерях, а из‑за ограничений алгоритма сжатия очень высокие уровни потерь не дают значительного выигрыша.<br/>            Диапазон допустимых значений: [0, 1000]. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Параметры multipage |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Получает или задает цветовую палитру. |
| pixel_aspect_ratio | System.Byte | r/w | Получает или задаёт соотношение сторон пикселя GIF. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Получает или задает параметры разрешения. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Получает или задает источник, в котором создаётся изображение. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Получает или задает параметры растеризации вектора. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Получает или задает контейнер метаданных XMP. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Создаёт поверхностную копию этого экземпляра. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Пытается установить экземпляр _metadata_, если этот экземпляр [Image](/imaging/python-net/aspose.imaging/image/) поддерживает и реализует экземпляр [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

Инициализирует новый экземпляр класса [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/).

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

Инициализирует новый экземпляр класса [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| gif_options | [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) | Опции GIF. |

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
### This example shows how to load a pixels information in an array of Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in GIF format) using MemoryStream object. {#example_7}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.externsions import StreamExtensions as strm_ext
from aspose.imaging.imageoptions import GifOptions
from aspose.imaging.sources import StreamSource

# Создать экземпляр MemoryStream
with strm_ext.create_memory_stream() as stream:
	#Создайте экземпляр GifOptions и задайте его различные свойства, включая свойство Source
	with GifOptions() as gifOptions:
		gifOptions.source = StreamSource(stream)

		# Создайте экземпляр Image
		with as_of(Image.create(gifOptions, 500, 500), RasterImage) as image:
			# Получите пиксели изображения, указав область как границу изображения
			pixels = image.load_pixels(image.bounds)

			yellow_color = Color.yellow
			blue_color = Color.blue
			#Пройдитесь по массиву и задайте цвет альтернативных индексированных пикселей
			for index in range(pixel.length):
				if index % 2 == 0:
					#Установите цвет индексированного пикселя в желтый
					pixels[index] = yellow_color
				else:
					#Установите цвет индексированного пикселя в синий
					pixels[index] = blue_color

			#Примените изменения пикселей к изображению
			image.save_pixels(image.bounds, pixels)

			# Сохраните все изменения.
			image.save()

	# Запишите MemoryStream в файл
	stream.seek(0)
	with open(r"C:\temp\output.gif", "wb") as fileStream:
		fileStream.write(stream.read())
}

```

### This example demonstrates the use of different classes from `imageoptions` package for export purposes. A gif image is loaded as an instance of Image and then exported out to several formats. {#example_15}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions, JpegOptions, PngOptions, TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from os.path import join as path_join

directory = "c:\\temp\\"
#Загрузить существующее GIF‑изображение как экземпляр класса Image.
with Image.load(path_join(directory, "sample.gif")) as image:
	# Экспортировать в формат BMP, используя параметры по умолчанию.
	image.save(path_join(directory, "output.bmp"), BmpOptions())
	# Экспортировать в формат JPEG, используя параметры по умолчанию.
	image.save(path_join(directory, "output.jpg"), JpegOptions())
	# Экспортировать в формат PNG, используя параметры по умолчанию.
	image.save(path_join(directory, "output.png"), PngOptions())
	# Экспортировать в формат TIFF, используя параметры по умолчанию.
	image.save(path_join(directory, "output.tif"), TiffOptions(TiffExpectedFormat.DEFAULT))


```

