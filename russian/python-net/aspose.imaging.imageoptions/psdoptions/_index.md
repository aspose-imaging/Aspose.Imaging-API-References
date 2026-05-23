---
title: "Класс PsdOptions"
type: docs
weight: 260
url: /ru/python-net/aspose.imaging.imageoptions/psdoptions/
---

**Summary:** Create Photoshop Document (PSD) images with our API, offering versatile options<br/>            with different format versions, compression methods, color modes, and<br/>            bits counts per color channel. Seamlessly handle XMP metadata containers,<br/>            ensuring comprehensive image processing with the power of PSD format features<br/>            like image layers, layer masks, and file information for customization<br/>            and creativity in your designs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PsdOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | Инициализирует новый экземпляр класса [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/). |
| [PsdOptions(options)](#PsdOptions_options_2) | Инициализирует новый экземпляр класса [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Получает или задает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| channel_bits_count | int | r/w | Получает или задает количество битов на цветовой канал. |
| channels_count | int | r/w | Получает или задает количество цветовых каналов. |
| [color_mode](#color_mode1) | [ColorModes](/imaging/python-net/aspose.imaging.fileformats.psd/colormodes/) | r/w | Получает или задает цветовой режим PSD. |
| [compression_method](#compression_method2) | [CompressionMethod](/imaging/python-net/aspose.imaging.fileformats.psd/compressionmethod/) | r/w | Получает или задает метод сжатия PSD. |
| disposed | bool | r | Получает значение, указывающее, удалён ли этот экземпляр. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Получает или задает данные Exif. |
| full_frame | bool | r/w | Получает или задает значение, указывающее, включен ли [full frame]. |
| keep_metadata | bool | r/w | Получает значение, указывающее, сохранять ли оригинальные метаданные изображения при экспорте. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Параметры multipage |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Получает или задает цветовую палитру. |
| psd_version | [PsdVersion](/imaging/python-net/aspose.imaging.fileformats.psd/psdversion/) | r/w | Получает или задает версию формата файла. Это может быть PSD или PSB. |
| refresh_image_preview_data | bool | r/w | Получает или задает значение, указывающее, следует ли [refresh image preview data] - параметр, используемый для повышения совместимости с другими просмотрщиками PSD‑изображений.<br/>            Обратите внимание, что отрисовка текстовых слоёв в окончательном макете не поддерживается на платформе Compact Framework. |
| remove_global_text_engine_resource | bool | r/w | Получает или задает значение, указывающее, следует ли - удалить глобальный ресурс текстового движка - используется для некоторых PSD‑файлов с текстовыми слоями, только в случае, когда после обработки их нельзя открыть в Adobe Photoshop (в основном из‑за отсутствующих шрифтов в текстовых слоях).<br/>            После использования этой опции пользователь должен выполнить следующее в открытом в Photoshop файле: Меню "Text" -> "Process absent fonts". После этой операции весь текст появится снова.<br/>            Обратите внимание, что эта операция может вызвать некоторые изменения окончательного макета. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Получает или задает параметры разрешения. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Получает или задает источник, в котором создаётся изображение. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Получает или задает параметры растеризации вектора. |
| vectorization_options | [PsdVectorizationOptions](/imaging/python-net/aspose.imaging.imageoptions/psdvectorizationoptions/) | r/w | Получает или задает параметры векторизации PSD. |
| version | int | r/w | Получает или задает версию файла PSD. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Получить или задать контейнер данных XMP |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Создаёт поверхностную копию этого экземпляра. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Пытается установить экземпляр _metadata_, если этот экземпляр [Image](/imaging/python-net/aspose.imaging/image/) поддерживает и реализует экземпляр [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

Инициализирует новый экземпляр класса [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/).

### Constructor: PsdOptions(options) {#PsdOptions_options_2}


```
 PsdOptions(options) 
```

Инициализирует новый экземпляр класса [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) | Параметры. |

### Property: color_mode {#color_mode1}

Получает или задает цветовой режим PSD.

**See also:**

**[Example # 1](#example_11)**: This example demonstrates the use of `aspose.imaging` API to convert Images t...


### Property: compression_method {#compression_method2}

Получает или задает метод сжатия PSD.

**See also:**

**[Example # 1](#example_11)**: This example demonstrates the use of `aspose.imaging` API to convert Images t...


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
### This example demonstrates the use of `aspose.imaging` API to convert Images to PSD format. To achieve this goal this example loads an existing image and then saves it back to PSD format. {#example_11}
``` python

from aspose.imaging import Image, RotateFlipType
from aspose.imaging.imageoptions import PsdOptions
from aspose.imaging.fileformats.psd import CompressionMethod, ColorModes
from os.path import join as path_join

directory = "c:\\temp\\"

#Создаёт экземпляр класса изображения и инициализирует его существующим файлом по пути к файлу
with Image.load(path_join(directory, "sample.bmp")) as image:
	#Создайте экземпляр класса PsdOptions
	psdOptions = PsdOptions()
	#Установите CompressionMethod как RLE
	#Примечание: Другой поддерживаемый CompressionMethod — CompressionMethod.RAW [Без сжатия]
	psdOptions.compression_method = CompressionMethod.RLE
	#Установите ColorMode в GRAYSCALE
	#Примечание: Другие поддерживаемые ColorModes — ColorModes.BITMAP и ColorModes.RGB
	psdOptions.color_mode = ColorModes.GRAYSCALE
	#Сохраните изображение в указанное место на диске с заданными настройками PsdOptions
	image.save(path_join(directory, "output.psd"), psdOptions)
}

```

