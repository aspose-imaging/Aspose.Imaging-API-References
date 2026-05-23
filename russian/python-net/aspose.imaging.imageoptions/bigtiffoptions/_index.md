---
title: "Класс BigTiffOptions"
type: docs
weight: 20
url: /ru/python-net/aspose.imaging.imageoptions/bigtiffoptions/
---

**Summary:** The API for BigTIFF raster image format creation is specifically designed<br/>            to serve to the unique requirements of applications utilizing large-scale<br/>            imaging data from scanners. This API facilitates the seamless generation<br/>            of BigTIFF format, which combines multiple TIFF images into a single,<br/>            comprehensive image. It ensures efficient processing of extensive image<br/>            data, providing developers with a powerful tool for creating and<br/>            manipulating high-resolution, multi-image formats.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.BigTiffOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, TiffOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BigTiffOptions(expected_format)](#BigTiffOptions_expected_format_1) | Создаёт новый экземпляр класса [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/). По умолчанию используется порядок байтов little endian. |
| [BigTiffOptions(expected_format, byte_order)](#BigTiffOptions_expected_format_byte_order_2) | Создаёт новый экземпляр класса [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/). |
| [BigTiffOptions(options)](#BigTiffOptions_options_3) | Создаёт новый экземпляр класса [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/). |
| [BigTiffOptions(tags)](#BigTiffOptions_tags_4) | Создаёт новый экземпляр класса [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffalphastorage/) | r/w | Получает или задает параметр хранения альфа-канала. Параметры, отличные от [TiffAlphaStorage.UNSPECIFIED](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffalphastorage/)<br/>            используются, когда определено более 3 [TiffOptions.samples_per_pixel](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). |
| artist | string | r/w | Получает или задает исполнителя. |
| bits_per_pixel | int | r | Получает количество бит на пиксель. |
| bits_per_sample | int[] | r/w | Получает или задает количество бит на образец. |
| buffer_size_hint | int | r/w | Получает или задает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | r/w | Получает или задает значение, указывающее порядок байтов TIFF. |
| color_map | int[] | r/w | Получает или задает карту цветов. |
| compressed_quality | int | r/w | Получает или задает качество сжатого изображения.<br/>            Используется с компрессией JPEG. |
| compression | [TiffCompressions](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffcompressions/) | r/w | Получает или задает сжатие. |
| авторские права | string | r/w | Получает или задает авторские права. |
| дата_время | string | r/w | Получает или задает дату и время. |
| default_memory_allocation_limit | int | r/w | Получает или задает предельный объём памяти по умолчанию. |
| disable_icc_export | bool | r/w | Получает или задает значение, указывающее, отключён ли экспорт ICC‑профиля (ICC‑профиль применяется к исходным пикселям заранее). |
| disposed | bool | r | Получает значение, указывающее, удалён ли этот экземпляр. |
| document_name | string | r/w | Получает или задает имя документа. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Получает или задает данные Exif. |
| exif_ifd | [TiffExifIfd](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffexififd/) | r | Получает или задает указатель на EXIF IFD. |
| extra_samples | int[] | r | Получает значения дополнительных образцов. |
| fax_t4_options | [Group3Options](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/group3options/) | r/w | Получает или задает параметры fax t4. |
| file_standard | [TiffFileStandards](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifffilestandards/) | r/w | Получает или задает стандарт файла TIFF. |
| fill_order | [TiffFillOrders](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifffillorders/) | r/w | Получает или задает порядок заполнения битов байта. |
| full_frame | bool | r/w | Получает или задает значение, указывающее, включен ли [full frame]. |
| half_tone_hints | int[] | r/w | Получает или задает подсказки полутонов. |
| описание_изображения | string | r/w | Получает или задает описание изображения. |
| длина_изображения | int | r/w | Получает или задает длину изображения. |
| ширина_изображения | int | r/w | Получает или задает ширину изображения. |
| ink_names | string | r/w | Получает или задает названия чернил. |
| is_extra_samples_present | bool | r | Получает значение, указывающее, присутствуют ли дополнительные образцы. |
| is_tiled | bool | r | Получает значение, указывающее, разбито ли изображение на плитки. |
| is_valid | bool | r | Получает значение, указывающее, правильно ли настроены [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). Используйте метод Validate, чтобы найти причину ошибки. |
| keep_metadata | bool | r/w | Получает значение, указывающее, сохранять ли оригинальные метаданные изображения при экспорте. |
| max_sample_value | int[] | r/w | Получает или задает максимальное значение образца. |
| min_sample_value | int[] | r/w | Получает или задает минимальное значение образца. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Параметры multipage |
| orientation | [TiffOrientations](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifforientations/) | r/w | Получает или задает ориентацию. |
| page_name | string | r/w | Получает или задает имя страницы. |
| page_number | int[] | r/w | Получает или задает тег номера страницы. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Получает или задает цветовую палитру. |
| photometric | [TiffPhotometrics](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffphotometrics/) | r/w | Получает или задает фотометрический параметр. |
| planar_configuration | [TiffPlanarConfigs](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | Получает или задает планарную конфигурацию. |
| predictor | [TiffPredictor](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffpredictor/) | r/w | Получает или задает предсказатель для сжатия LZW. |
| premultiply_components | bool | r/w | Получает или задает значение, указывающее, должны ли компоненты быть предварительно умножены. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Получает или задает параметры разрешения. |
| resolution_unit | [TiffResolutionUnits](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffresolutionunits/) | r/w | Получает или задает единицу разрешения. |
| rows_per_strip | int | r/w | Получает или задает количество строк в полосе. |
| sample_format | [TiffSampleFormats[]](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffsampleformats/) | r/w | Получает или задает формат образца. |
| samples_per_pixel | int | r | Получает количество образцов на пиксель. Чтобы изменить значение этого свойства, используйте сеттер свойства [TiffOptions.bits_per_sample](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). |
| scanner_manufacturer | string | r/w | Получает или задает производителя сканера. |
| scanner_model | string | r/w | Получает или задает модель сканера. |
| smax_sample_value | int[] | r/w | Получает или задает максимальное значение образца. Значение имеет тип поля, который лучше всего соответствует данным образца (тип Byte, Short или Long). |
| smin_sample_value | int[] | r/w | Получает или задает минимальное значение образца. Значение имеет тип поля, который лучше всего соответствует данным образца (тип Byte, Short или Long). |
| software_type | string | r/w | Получает или задает тип программного обеспечения. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Получает или задает источник, в котором создаётся изображение. |
| strip_byte_counts | int[] | r/w | Получает или задает количество байтов в полосе. |
| strip_offsets | int[] | r/w | Получает или задает смещения полос. |
| sub_file_type | [TiffNewSubFileTypes](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | Получает или задает общее указание типа данных, содержащихся в этом подпфайле. |
| tag_count | int | r | Получает количество тегов. |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Получает или задает теги. |
| target_printer | string | r/w | Получает или задает целевой принтер. |
| threshholding | [TiffThresholds](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffthresholds/) | r/w | Получает или задает пороговое значение. |
| tile_byte_counts | int[] | r/w | Получает или задает количество байтов в плитке. |
| tile_length | int | r/w | Получает или задает длину плитки. |
| tile_offsets | int[] | r/w | Получает или задает смещения плитки. |
| tile_width | int | r/w | Получает или задает ширину плитки. |
| total_pages | int | r | Получает общее количество страниц. |
| valid_tag_count | int | r | Получает количество действительных тегов. Это не общее количество тегов, а число тегов, которые могут быть сохранены. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Получает или задает параметры растеризации вектора. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Получает или задает данные Xmp. |
| xp_author | string | r/w | Получает или задает автора изображения, который используется в Windows Explorer. |
| xp_comment | string | r/w | Получает или задает комментарий к изображению, который используется в Windows Explorer. |
| xp_keywords | string | r/w | Получает или задает тему изображения, которая используется в Windows Explorer. |
| xp_subject | string | r/w | Получает или задает информацию об изображении, которая используется в Windows Explorer. |
| xp_title | string | r/w | Получает или задает информацию об изображении, которая используется в Windows Explorer. |
| xposition | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает позицию по оси X. |
| xresolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает разрешение по оси X. |
| y_cb_cr_coefficients | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает коэффициенты YCbCr. |
| y_cb_cr_subsampling | int[] | r/w | Получает или задает коэффициенты субдискретизации для фотометрии YCbCr. |
| yposition | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает позицию по оси Y. |
| yresolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает разрешение по оси y. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | Добавляет новый тег. |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | Добавляет теги. |
| [clone()](#clone__3) | Создаёт клон этого экземпляра. |
| [create_with_format(expected_format)](#create_with_format_expected_format_4) | Создаёт новый экземпляр класса [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/). По умолчанию используется порядок байтов little endian. |
| [create_with_options(options)](#create_with_options_options_5) | Создаёт новый экземпляр класса [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/). |
| [create_with_tags(tags)](#create_with_tags_tags_6) | Создаёт новый экземпляр класса [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/). |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_7) | Получает экземпляр тега по типу. |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_8) | Получает количество действительных тегов. |
| [is_tag_present(tag)](#is_tag_present_tag_9) | Определяет, присутствует ли тег в параметрах или нет. |
| [remove_tag(tag)](#remove_tag_tag_10) | Удаляет тег. |
| [remove_tags(tags)](#remove_tags_tags_11) | Удаляет теги. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_12) | Пытается установить экземпляр _metadata_, если этот экземпляр [Image](/imaging/python-net/aspose.imaging/image/) поддерживает и реализует экземпляр [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |
| validate() | Проверяет, имеет ли параметры допустимую комбинацию тегов |


### Constructor: BigTiffOptions(expected_format) {#BigTiffOptions_expected_format_1}


```
 BigTiffOptions(expected_format) 
```

Создаёт новый экземпляр класса [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/). По умолчанию используется порядок байтов little endian.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | Ожидаемый формат файла Tiff. |

### Constructor: BigTiffOptions(expected_format, byte_order) {#BigTiffOptions_expected_format_byte_order_2}


```
 BigTiffOptions(expected_format, byte_order) 
```

Создаёт новый экземпляр класса [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | Ожидаемый формат файла Tiff. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | Порядок байтов формата файла tiff, который следует использовать. |

### Constructor: BigTiffOptions(options) {#BigTiffOptions_options_3}


```
 BigTiffOptions(options) 
```

Создаёт новый экземпляр класса [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) | Источник параметров. |

### Constructor: BigTiffOptions(tags) {#BigTiffOptions_tags_4}


```
 BigTiffOptions(tags) 
```

Создаёт новый экземпляр класса [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Теги для инициализации параметров. |

### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

Добавляет новый тег.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Тег для добавления. |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

Добавляет теги.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Теги для добавления. |

### Method: clone() {#clone__3}


```
 clone() 
```

Создаёт клон этого экземпляра.

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Возвращает глубокую копию. |


### Method: create_with_format(expected_format)  [static] {#create_with_format_expected_format_4}


```
 create_with_format(expected_format) 
```

Создаёт новый экземпляр класса [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/). По умолчанию используется порядок байтов little endian.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | Ожидаемый формат файла Tiff. |

**Returns**

| Тип | Описание |
| :- | :- |
| [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) | Новый объект BigTiffOptions. |


### Method: create_with_options(options)  [static] {#create_with_options_options_5}


```
 create_with_options(options) 
```

Создаёт новый экземпляр класса [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) | Источник параметров. |

**Returns**

| Тип | Описание |
| :- | :- |
| [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) | Копия параметров. |


### Method: create_with_tags(tags)  [static] {#create_with_tags_tags_6}


```
 create_with_tags(tags) 
```

Создаёт новый экземпляр класса [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Теги для инициализации параметров. |

**Returns**

| Тип | Описание |
| :- | :- |
| [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) | Новый объект BigTiffOptions с тегами. |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_7}


```
 get_tag_by_type(tag_key) 
```

Получает экземпляр тега по типу.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tag_key | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Ключ тега. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Экземпляр тега, если он существует, иначе null. |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_8}


```
 get_valid_tags_count(tags) 
```

Получает количество действительных тегов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Теги для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Количество допустимых тегов. |


### Method: is_tag_present(tag) {#is_tag_present_tag_9}


```
 is_tag_present(tag) 
```

Определяет, присутствует ли тег в параметрах или нет.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tag | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Идентификатор тега для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если тег присутствует; иначе <c>false</c>. |


### Method: remove_tag(tag) {#remove_tag_tag_10}


```
 remove_tag(tag) 
```

Удаляет тег.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tag | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Тег для удаления. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true если успешно удалён |


### Method: remove_tags(tags) {#remove_tags_tags_11}


```
 remove_tags(tags) 
```

Удаляет теги.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tags | [TiffTags[]](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Теги для удаления. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | **True** если размер коллекции тегов изменился. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_12}


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
| bool | Истина, если _metadata_ не равно null и экземпляр [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) <br/> поддерживает и/или реализует экземпляр [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/); в противном случае — ложь. |


