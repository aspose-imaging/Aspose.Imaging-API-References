---
title: "Класс BmpOptions"
type: docs
weight: 30
url: /ru/python-net/aspose.imaging.imageoptions/bmpoptions/
---

**Summary:** The API for BMP and DIB raster image format creation options provides developers<br/>            with a versatile toolset for generating custom Bitmap (BMP) and Device<br/>            Independent Bitmap (DIB) images. With this API, you can precisely define<br/>            image characteristics such as bits per pixel, compression level and compression<br/>            type, tailoring the output to meet specific requirements. This feature-rich<br/>            API empowers developers to create high-quality, customized raster images<br/>            with ease and flexibility for diverse applications.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.BmpOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BmpOptions()](#BmpOptions__1) | Инициализирует новый экземпляр класса [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/). |
| [BmpOptions(bmp_options)](#BmpOptions_bmp_options_2) | Инициализирует новый экземпляр класса [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [bits_per_pixel](#bits_per_pixel1) | int | r/w | Получает или задает количество бит на пиксель изображения. |
| buffer_size_hint | int | r/w | Получает или задает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [compression](#compression2) | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | r/w | Получает или задает тип сжатия. Тип сжатия по умолчанию — [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/), который позволяет сохранять [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) с прозрачностью. |
| disposed | bool | r | Получает значение, указывающее, удалён ли этот экземпляр. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Получает или задает данные Exif. |
| full_frame | bool | r/w | Получает или задает значение, указывающее, включен ли [full frame]. |
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


### Constructor: BmpOptions() {#BmpOptions__1}


```
 BmpOptions() 
```

Инициализирует новый экземпляр класса [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/).


**See also:**

**[Example # 1](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 2](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...


### Constructor: BmpOptions(bmp_options) {#BmpOptions_bmp_options_2}


```
 BmpOptions(bmp_options) 
```

Инициализирует новый экземпляр класса [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| bmp_options | [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) | Параметры BMP. |

### Property: bits_per_pixel {#bits_per_pixel1}

Получает или задает количество бит на пиксель изображения.

**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 3](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...


### Property: compression {#compression2}

Получает или задает тип сжатия. Тип сжатия по умолчанию — [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/), который позволяет сохранять [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) с прозрачностью.

**See also:**

**[Example # 1](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 2](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...

**[Example # 3](#example_208)**: Decompress BMP image which was previously compressed using DXT1 compression a...

**[Example # 4](#example_225)**: The example shows how to export a BMP from a PNG file while keeping the alpha...

**[Example # 5](#example_226)**: The example shows how to export a BMP with the RGB compression type.


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
### This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case. {#example_4}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#Создайте экземпляр `BmpOptions` и задайте его различные свойства.
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24

	#Создайте экземпляр `FileCreateSource` и назначьте его в качестве `source` для экземпляра `BmpOptions`.
	#Второй параметр типа `Boolean` определяет, является ли создаваемый файл временным (is_temporal) или нет.
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp", False)

	#Создайте экземпляр Image и инициализируйте его экземпляром BmpOptions, вызвав метод Create.
	with Image.create(bmp_options, 500, 500) as image:
		#выполнить обработку изображения.
		# сохранить все изменения.
		image.save()


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

### The following example shows how to set a palette to a BMP image to reduce its output size. {#example_20}
``` python

from aspose.pycore import as_of
from aspose.imaging import Point, Color, Graphics, ColorPaletteHelper
from aspose.imaging.brushes import LinearGradientBrush
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.imageoptions import BmpOptions
from os.path import join as path_join

# Создайте BMP‑изображение размером 100 × 100 px.
with BmpImage(100, 100) as bmpImage:
	# Линейный градиент от левого верхнего до правого нижнего угла изображения.
	brush = LinearGradientBrush(Point(0, 0), Point(bmpImage.width, bmpImage.height),
								Color.red,
								Color.green)
	# Заполните всё изображение кистью линейного градиента.
	gr = Graphics(bmpImage)
	gr.fill_rectangle(brush, bmpImage.bounds)
	# Получите ближайшую 8‑битную цветовую палитру, покрывающую как можно больше пикселей, так чтобы палитризированное изображение
	# было почти визуально неотличимо от BMP без палитры
	palette = ColorPaletteHelper.get_close_image_palette(bmpImage, 256)
	# 8‑битная палитра содержит не более 256 цветов.
	saveOptions = BmpOptions()
	saveOptions.palette = palette
	saveOptions.bits_per_pixel = 8
	
	with stream_ext.create_memory_stream() as stream:
		bmpImage.save(stream, saveOptions)
		print(f"The size of image with palette is {stream.tell()} bytes.")
		stream.seek(0)
		bmpImage.save(stream)
		print(f"The size of image without palette is {stream.tell()} bytes.")

# Вывод выглядит так:
# Размер изображения с палитрой составляет 11078 байт.
# Размер изображения без палитры составляет 40054 байт.

```

### The following example loads a BMP image and saves it back to BMP using various save options. {#example_91}
``` python
from aspose.imaging import Image, RasterImage, ColorPaletteHelper, ResolutionSetting
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.fileformats.bmp import BitmapCompression
import os
import aspose.pycore as aspycore

directory = "c:\\temp\\"

with Image.load(os.path.join(directory, "sample.bmp")) as image:
	
	rasterImage = aspycore.as_of(image, RasterImage)

	# Создайте BmpOptions
	saveOptions = BmpOptions()

	# Используйте 8 бит на пиксель, чтобы уменьшить размер выходного изображения.
	saveOptions.bits_per_pixel = 8

	# Установите ближайшую 8‑битную цветовую палитру, покрывающую максимальное количество пикселей изображения, так чтобы палитризированное изображение
	# почти визуально не отличим от непалетизированного.
	saveOptions.palette = ColorPaletteHelper.get_close_image_palette(rasterImage, 256)

	# Сохранить без сжатия.
	# Вы также можете использовать сжатие RLE-8, чтобы уменьшить размер выходного изображения.
	saveOptions.compression = BitmapCompression.RGB

	# Установите горизонтальное и вертикальное разрешение в 96 dpi.
	saveOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

	image.save(os.path.join(directory, "sample.bmpoptions.bmp"), saveOptions)


```

### The following example creates a palettized grayscale BMP image and then saves it to a file. {#example_92}
``` python

from os.path import join as path_join
from aspose.imaging import Image, ColorPaletteHelper, ResolutionSetting, Graphics, Point, Color
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.fileformats.bmp import BitmapCompression
from aspose.imaging.brushes import LinearGradientBrush

directory = "c:\\temp\\"
createOptions = BmpOptions()

# Сохранить в файл
createOptions.source = FileCreateSource(path_join(directory, "output.palette8bit.bmp"), False)
	
# Используйте 8 бит на пиксель, чтобы уменьшить размер выходного изображения.
createOptions.bits_per_pixel = 8

# Установите стандартную 8‑битную градационную палитру, охватывающую все оттенки серого.
# Если обработанное изображение содержит только оттенки серого, то его палетизированная версия
# визуально не отличима от непалетизированного.
createOptions.palette = ColorPaletteHelper.create_8_bit_grayscale(False)

# Сохранить без сжатия.
# Вы также можете использовать сжатие RLE-8, чтобы уменьшить размер выходного изображения.
createOptions.compression = BitmapCompression.RGB

# Установите горизонтальное и вертикальное разрешение в 96 dpi.
createOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

# Создайте BMP‑изображение размером 100 × 100 px и сохраните его в файл.
with Image.create(createOptions, 100, 100) as image:
	graphics = Graphics(image)
	gradientBrush = LinearGradientBrush(Point(0, 0), Point(image.width, image.height), Color.black, Color.white)
	# Заполните изображение градиентом серого
	graphics.fill_rectangle(gradientBrush, image.bounds)
	image.save()


```

### Decompress BMP image which was previously compressed using DXT1 compression algorithm. {#example_208}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions

with Image.load("CompressedTiger.bmp") as image:
	image.save("DecompressedTiger.bmp", BmpOptions())


```

### The example shows how to export a BMP from a PNG file while keeping the alpha channel, save a BMP file with transparency. {#example_225}
``` python
from aspose.imaging import Image
from aspose.imaging.fileformats.png import BmpOptions

source_path = "input.png"
output_path_def = "result_def.bmp"
output_path_def_2 = "result_def-2.bmp"
output_path_bitfields = "result_bitfields.bmp"
# Загрузить PNG‑изображение из файла.
with Image.load(source_path) as pngImage:
	# Изображение BMP сохраняется с поддержкой прозрачности по умолчанию.
	# Если вы хотите явно указать такой режим, свойство `compression` объекта BmpOptions должно быть установлено в BitmapCompression.BITFIELDS.
	# Метод сжатия BitmapCompression.BITFIELDS является методом сжатия по умолчанию в BmpOptions.
	# Таким образом, тот же результат экспорта BMP‑изображения с прозрачностью можно достичь любым из следующих способов.
	# С неявными параметрами по умолчанию:
	pngImage.save(output_path_def)
	# С явными параметрами по умолчанию:
	pngImage.save(output_path_def_2, BmpOptions())
	# Указание метода сжатия BitmapCompression.BITFIELDS:
	bmp_options = BmpOptions()
	bmp_options.compression = BitmapCompression.BITFIELDS
	pngImage.save(output_path_bitfields, bmp_options)


```

### The example shows how to export a BMP with the RGB compression type. {#example_226}
``` python

from aspose.imaging import Image
from aspose.imaging.fileformats.bmp import BitmapCompression
from aspose.imaging.imageoptions import BmpOptions

source_path = "input.png"
output_path = "output.png"
# Загрузить PNG‑изображение из файла.
with Image.load(source_path) as pngImage:
	# Изображение BMP сохраняется с поддержкой прозрачности по умолчанию, что достигается использованием метода сжатия BitmapCompression.BITFIELDS.
	# Чтобы сохранить BMP‑изображение с методом сжатия RGB, необходимо указать BmpOptions со свойством `compression`, установленным в BitmapCompression.RGB.
	bmp_options = BmpOptions()
	bmp_options.compression = BitmapCompression.RGB
	pngImage.save(output_path, bmp_options)


```

