---
title: "Класс PngOptions"
type: docs
weight: 250
url: /ru/python-net/aspose.imaging.imageoptions/pngoptions/
---

**Summary:** Create high-quality Portable Network Graphics (PNG) raster images effortlessly<br/>            with our API, offering customizable options for compression levels,<br/>            bits per pixel depths, and alpha bits. Seamlessly process XMP metadata containers,<br/>            ensuring comprehensive image metadata management, and empowering you to tailor<br/>            PNG images to your exact specifications with ease.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PngOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PngOptions()](#PngOptions__1) | Создаёт новый экземпляр класса [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/). |
| [PngOptions(png_options)](#PngOptions_png_options_2) | Создаёт новый экземпляр класса [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| DEFAULT_COMPRESSION_LEVEL [static] | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r | Уровень сжатия по умолчанию. |
| bit_depth | System.Byte | r/w | Получает или задаёт значения глубины цвета в диапазоне 1, 2, 4, 8, 16.<br/>            <br/><br/>            Учтите следующие ограничения:<br/>            <br/><br/>[PngColorType.INDEXED_COLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) поддерживает глубину цвета 1, 2, 4, 8.<br/>            <br/><br/>[PngColorType.GRAYSCALE](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.GRAYSCALE_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) поддерживают глубину цвета 8.<br/>            <br/><br/>[PngColorType.TRUECOLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.TRUECOLOR_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) поддерживают глубину цвета 8, 16.<br/>            <br/> |
| buffer_size_hint | int | r/w | Получает или задает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [color_type](#color_type1) | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | r/w | Получает или задает тип цвета. |
| [compression_level](#compression_level2) | int | r/w | Получает или задаёт уровень сжатия [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| disposed | bool | r | Получает значение, указывающее, удалён ли этот экземпляр. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Получает или задает данные Exif. |
| filter_type | [PngFilterType](/imaging/python-net/aspose.imaging.fileformats.png/pngfiltertype/) | r/w | Получает или задаёт тип фильтра, используемый при сохранении PNG‑файла. |
| full_frame | bool | r/w | Получает или задает значение, указывающее, включен ли [full frame]. |
| keep_metadata | bool | r/w | Получает значение, указывающее, сохранять ли оригинальные метаданные изображения при экспорте. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Параметры multipage |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Получает или задает цветовую палитру. |
| png_compression_level | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r/w | Получает или задаёт уровень сжатия [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| [progressive](#progressive3) | bool | r/w | Получает или задаёт значение, указывающее, является ли [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) прогрессивным. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Получает или задает параметры разрешения. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Получает или задает источник, в котором создаётся изображение. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Получает или задает параметры растеризации вектора. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Получает или задает контейнер метаданных XMP. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Создаёт поверхностную копию этого экземпляра. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Пытается установить экземпляр _metadata_, если этот экземпляр [Image](/imaging/python-net/aspose.imaging/image/) поддерживает и реализует экземпляр [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: PngOptions() {#PngOptions__1}


```
 PngOptions() 
```

Создаёт новый экземпляр класса [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/).

### Constructor: PngOptions(png_options) {#PngOptions_png_options_2}


```
 PngOptions(png_options) 
```

Создаёт новый экземпляр класса [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| png_options | [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) | Параметры PNG. |

### Property: color_type {#color_type1}

Получает или задает тип цвета.

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Property: compression_level {#compression_level2}

Получает или задаёт уровень сжатия [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/).

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Property: progressive {#progressive3}

Получает или задаёт значение, указывающее, является ли [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) прогрессивным.

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


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
### This example uses Graphics class to create primitive shapes on the Image surface. To demonstrate the operation, the example creates a new Image in PNG format and draw primitive shapes on Image surface using Draw methods exposed by Graphics class {#example_12}
``` python

from aspose.imaging import Image, RotateFlipType, Graphics, Color, Pen, Rectangle, Point, Size,\
	Font, PointF
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.psd import CompressionMethod, ColorModes
from aspose.imaging.sources import StreamSource

from os.path import join as path_join

#Создает экземпляр файлового потока.
with open(r"C:\temp\output.png", "w+b") as stream:
	#Создайте экземпляр PngOptions и задайте его различные свойства.
	pngOptions = PngOptions()
	#Установите источник для PngOptions.
	pngOptions.source = StreamSource(stream)
	#Создайте экземпляр Image
	with Image.create(pngOptions, 500, 500) as image:
		#Создайте и инициализируйте экземпляр класса Graphics.
		graphics = Graphics(image)
		#Очистить поверхность Graphics.
		graphics.clear(Color.wheat);
		#Нарисуйте дугу, указав объект Pen с черным цветом, 
		#прямоугольник, окружающий дугу, начальный угол и угол разворота
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Нарисуйте кривую Безье, указав объект Pen с синим цветом и координатные точки.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Нарисуйте кривую, указав объект Pen, имеющий зелёный цвет, и массив точек
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Нарисуйте эллипс, используя объект Pen и окружающий прямоугольник
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Нарисуйте линию 
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Нарисуйте сегмент пирога
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Нарисуйте многоугольник, указав объект Pen, имеющий красный цвет, и массив точек
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Нарисуйте прямоугольник
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#Создайте объект SolidBrush и задайте его различные свойства
		brush = SolidBrush()
		brush.color = Color.purple
		#Нарисуйте строку, используя объект SolidBrush и Font, в конкретной точке
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# Сохраните все изменения.
		image.save();

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

### The following example shows how to compress a PNG image, using indexed color with best fit palette {#example_21}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, ColorPaletteHelper, RasterImage, PaletteMiningMethod
from aspose.imaging.fileformats.png import PngColorType

# Загружает PNG‑изображение
sourceFilePath = "OriginalRings.png"
outputFilePath = "OriginalRingsOutput.png"
with Image.load(sourceFilePath) as image:
	png_options = PngOptions()
	png_options.progressive = True
	# Использовать индексный тип цвета
	png_options.color_type = PngColorType.INDEXED_COLOR
	# Использовать максимальное сжатие
	png_options.compression_level = 9
	# Получите ближайшую 8‑битную цветовую палитру, покрывающую как можно больше пикселей, так чтобы изображение
	# с палитрой было почти визуально неотличимо от изображения без палитры.
	png_options.palette = ColorPaletteHelper.get_close_image_palette(
						as_of(image, RasterImage), 256, 
						PaletteMiningMethod.HISTOGRAM)
		 
	image.save(outputFilePath, png_options);
}
# Размер выходного файла должен значительно уменьшиться

```

