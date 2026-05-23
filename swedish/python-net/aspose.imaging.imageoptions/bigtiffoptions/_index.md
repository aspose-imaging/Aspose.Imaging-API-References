---
title: "BigTiffOptions klass"
type: docs
weight: 20
url: /sv/python-net/aspose.imaging.imageoptions/bigtiffoptions/
---

**Summary:** The API for BigTIFF raster image format creation is specifically designed<br/>            to serve to the unique requirements of applications utilizing large-scale<br/>            imaging data from scanners. This API facilitates the seamless generation<br/>            of BigTIFF format, which combines multiple TIFF images into a single,<br/>            comprehensive image. It ensures efficient processing of extensive image<br/>            data, providing developers with a powerful tool for creating and<br/>            manipulating high-resolution, multi-image formats.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.BigTiffOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, TiffOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BigTiffOptions(expected_format)](#BigTiffOptions_expected_format_1) | Initierar en ny instans av klassen [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) . Som standard används little endian‑konventionen. |
| [BigTiffOptions(expected_format, byte_order)](#BigTiffOptions_expected_format_byte_order_2) | Initierar en ny instans av klassen [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) . |
| [BigTiffOptions(options)](#BigTiffOptions_options_3) | Initierar en ny instans av klassen [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) . |
| [BigTiffOptions(tags)](#BigTiffOptions_tags_4) | Initierar en ny instans av klassen [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffalphastorage/) | r/w | Hämtar eller anger alfa lagringsalternativet. Alternativ förutom [TiffAlphaStorage.UNSPECIFIED](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffalphastorage/)<br/>            används när det finns mer än 3 [TiffOptions.samples_per_pixel](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) definierade. |
| artist | string | r/w | Hämtar eller anger artisten. |
| bits_per_pixel | int | r | Hämtar bitarna per pixel. |
| bits_per_sample | int[] | r/w | Hämtar eller anger antalet bitar per prov. |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | r/w | Hämtar eller anger ett värde som indikerar tiff-byteordningen. |
| color_map | int[] | r/w | Hämtar eller anger färgkartan. |
| compressed_quality | int | r/w | Hämtar eller anger komprimerad bildkvalitet.<br/>            Används med Jpeg‑komprimering. |
| compression | [TiffCompressions](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffcompressions/) | r/w | Hämtar eller anger komprimeringen. |
| upphovsrätt | string | r/w | Hämtar eller anger upphovsrätten. |
| date_time | string | r/w | Hämtar eller anger datum och tid. |
| default_memory_allocation_limit | int | r/w | Hämtar eller anger standardgränsen för minnesallokering. |
| disable_icc_export | bool | r/w | Hämtar eller anger ett värde som indikerar om ICC‑profilexport är inaktiverad (ICC‑profilen appliceras på källpixlarna i förväg). |
| disposed | bool | r | Hämtar ett värde som indikerar om den här instansen är frigjord. |
| document_name | string | r/w | Hämtar eller anger dokumentets namn. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Hämtar eller anger Exif-data. |
| exif_ifd | [TiffExifIfd](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffexififd/) | r | Hämtar eller anger pekaren till EXIF IFD. |
| extra_samples | int[] | r | Hämtar värdena för extra samples. |
| fax_t4_options | [Group3Options](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/group3options/) | r/w | Hämtar eller anger fax t4‑alternativen. |
| file_standard | [TiffFileStandards](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifffilestandards/) | r/w | Hämtar eller anger TIFF‑filstandard. |
| fill_order | [TiffFillOrders](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifffillorders/) | r/w | Hämtar eller anger fyllningsordningen för byte‑bitar. |
| full_frame | bool | r/w | Hämtar eller anger ett värde som indikerar om [full frame]. |
| half_tone_hints | int[] | r/w | Hämtar eller anger halvtone‑tipsen. |
| image_description | string | r/w | Hämtar eller anger bildbeskrivningen. |
| image_length | int | r/w | Hämtar eller anger bildlängden. |
| image_width | int | r/w | Hämtar eller anger bildbredden. |
| ink_names | string | r/w | Hämtar eller anger bläcknamnen. |
| is_extra_samples_present | bool | r | Hämtar ett värde som indikerar om de extra proverna finns. |
| is_tiled | bool | r | Hämtar ett värde som indikerar om bilden är tiled. |
| is_valid | bool | r | Hämtar ett värde som indikerar om [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) har konfigurerats korrekt. Använd Validate method för att hitta felorsaken. |
| keep_metadata | bool | r/w | Hämtar ett värde som anger om originalmetadata för bilden ska behållas vid export. |
| max_sample_value | int[] | r/w | Hämtar eller anger det maximala provvärdet. |
| min_sample_value | int[] | r/w | Hämtar eller anger det minsta provvärdet. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Flersidiga alternativ |
| orientation | [TiffOrientations](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifforientations/) | r/w | Hämtar eller anger orienteringen. |
| page_name | string | r/w | Hämtar eller anger sidnamnet. |
| page_number | int[] | r/w | Hämtar eller anger sidnummer‑taggen. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Hämtar eller anger färgpaletten. |
| photometric | [TiffPhotometrics](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffphotometrics/) | r/w | Hämtar eller anger photometric. |
| planar_configuration | [TiffPlanarConfigs](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | Hämtar eller anger den plana konfigurationen. |
| predictor | [TiffPredictor](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffpredictor/) | r/w | Hämtar eller anger förutsägaren för LZW-komprimering. |
| premultiply_components | bool | r/w | Hämtar eller anger ett värde som indikerar om komponenterna måste förmultipliceras. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Hämtar eller anger upplösningsinställningarna. |
| resolution_unit | [TiffResolutionUnits](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffresolutionunits/) | r/w | Hämtar eller anger upplösningsenheten. |
| rows_per_strip | int | r/w | Hämtar eller anger rader per strip. |
| sample_format | [TiffSampleFormats[]](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffsampleformats/) | r/w | Hämtar eller anger provformatet. |
| samples_per_pixel | int | r | Hämtar prover per pixel. För att ändra detta egenskapsvärde, använd [TiffOptions.bits_per_sample](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) egenskaps‑setter. |
| scanner_manufacturer | string | r/w | Hämtar eller anger skannertillverkaren. |
| scanner_model | string | r/w | Hämtar eller anger skannermodellen. |
| smax_sample_value | int[] | r/w | Hämtar eller anger det maximala provvärdet. Värdet har en fälttyp som bäst matchar provdata (Byte, Short eller Long type). |
| smin_sample_value | int[] | r/w | Hämtar eller anger det minsta provvärdet. Värdet har en fälttyp som bäst matchar provdata (Byte, Short eller Long type). |
| software_type | string | r/w | Hämtar eller anger programvarutypen. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Hämtar eller anger källan där bilden ska skapas. |
| strip_byte_counts | int[] | r/w | Hämtar eller anger strip-byte-antalet. |
| strip_offsets | int[] | r/w | Hämtar eller anger strip-offsetsen. |
| sub_file_type | [TiffNewSubFileTypes](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | Hämtar eller anger en allmän indikation på vilken typ av data som finns i denna underfil. |
| tag_count | int | r | Hämtar taggantalet. |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Hämtar eller anger taggarna. |
| target_printer | string | r/w | Hämtar eller anger målskrivaren. |
| threshholding | [TiffThresholds](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffthresholds/) | r/w | Hämtar eller anger tröskelvärdet. |
| tile_byte_counts | int[] | r/w | Hämtar eller anger tile-byte-antalet. |
| tile_length | int | r/w | Hämtar eller anger tile-längden. |
| tile_offsets | int[] | r/w | Hämtar eller anger tile-offsetsen. |
| tile_width | int | r/w | Hämtar eller anger tile-bredden. |
| total_pages | int | r | Hämtar det totala antalet sidor. |
| valid_tag_count | int | r | Hämtar det giltiga taggantalet. Detta är inte det totala antalet taggar utan antalet taggar som kan bevaras. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Hämtar eller anger vektorrasteriseringsalternativen. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Hämtar eller anger Xmp-data. |
| xp_author | string | r/w | Hämtar eller anger bildens författare, som används av Windows Explorer. |
| xp_comment | string | r/w | Hämtar eller anger kommentar på bilden, som används av Windows Explorer. |
| xp_keywords | string | r/w | Hämtar eller anger bildens ämne, som används av Windows Explorer. |
| xp_subject | string | r/w | Hämtar eller anger information om bilden, som används av Windows Explorer. |
| xp_title | string | r/w | Hämtar eller anger information om bilden, som används av Windows Explorer. |
| xposition | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger x‑positionen. |
| xresolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger x-upplösningen. |
| y_cb_cr_coefficients | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger YCbCr‑koefficienterna. |
| y_cb_cr_subsampling | int[] | r/w | Hämtar eller anger subsamplingsfaktorerna för YCbCr‑fotometriska data. |
| yposition | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger y‑positionen. |
| yresolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger y-upplösningen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | Lägger till en ny tagg. |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | Lägger till taggarna. |
| [clone()](#clone__3) | Klonar den här instansen. |
| [create_with_format(expected_format)](#create_with_format_expected_format_4) | Initierar en ny instans av klassen [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) . Som standard används little endian‑konventionen. |
| [create_with_options(options)](#create_with_options_options_5) | Initierar en ny instans av klassen [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) . |
| [create_with_tags(tags)](#create_with_tags_tags_6) | Initierar en ny instans av klassen [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) . |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_7) | Hämtar instansen av taggen efter typ. |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_8) | Hämtar antalet giltiga taggar. |
| [is_tag_present(tag)](#is_tag_present_tag_9) | Bestämmer om taggen finns i alternativen eller inte. |
| [remove_tag(tag)](#remove_tag_tag_10) | Tar bort taggen. |
| [remove_tags(tags)](#remove_tags_tags_11) | Tar bort taggarna. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_12) | Försöker sätta en _metadata_-instans, om detta [Image](/imaging/python-net/aspose.imaging/image/)-instans stödjer och implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)-instansen. |
| validate() | Validerar om alternativ har en giltig kombination av taggar |


### Constructor: BigTiffOptions(expected_format) {#BigTiffOptions_expected_format_1}


```
 BigTiffOptions(expected_format) 
```

Initierar en ny instans av klassen [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) . Som standard används little endian‑konventionen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | Det förväntade Tiff-filformatet. |

### Constructor: BigTiffOptions(expected_format, byte_order) {#BigTiffOptions_expected_format_byte_order_2}


```
 BigTiffOptions(expected_format, byte_order) 
```

Initierar en ny instans av klassen [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) .

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | Det förväntade Tiff-filformatet. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | Byteordningen för tiff-filformatet att använda. |

### Constructor: BigTiffOptions(options) {#BigTiffOptions_options_3}


```
 BigTiffOptions(options) 
```

Initierar en ny instans av klassen [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) .

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) | Alternativens källa. |

### Constructor: BigTiffOptions(tags) {#BigTiffOptions_tags_4}


```
 BigTiffOptions(tags) 
```

Initierar en ny instans av klassen [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) .

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Taggarna för alternativens initiering. |

### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

Lägger till en ny tagg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Taggen att lägga till. |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

Lägger till taggarna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Taggarna att lägga till. |

### Method: clone() {#clone__3}


```
 clone() 
```

Klonar den här instansen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Returnerar en djup klon. |


### Method: create_with_format(expected_format)  [static] {#create_with_format_expected_format_4}


```
 create_with_format(expected_format) 
```

Initierar en ny instans av klassen [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) . Som standard används little endian‑konventionen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | Det förväntade Tiff-filformatet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) | Ett nytt BigTiffOptions-objekt. |


### Method: create_with_options(options)  [static] {#create_with_options_options_5}


```
 create_with_options(options) 
```

Initierar en ny instans av klassen [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) .

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) | Alternativens källa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) | En kopia av alternativen. |


### Method: create_with_tags(tags)  [static] {#create_with_tags_tags_6}


```
 create_with_tags(tags) 
```

Initierar en ny instans av klassen [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) .

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Taggarna för alternativens initiering. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) | Ett nytt BigTiffOptions-objekt med taggar. |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_7}


```
 get_tag_by_type(tag_key) 
```

Hämtar instansen av taggen efter typ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tag_key | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Taggnyckeln. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Instans av taggen om den finns, annars null. |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_8}


```
 get_valid_tags_count(tags) 
```

Hämtar antalet giltiga taggar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Taggarna att validera. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Antalet giltiga taggar. |


### Method: is_tag_present(tag) {#is_tag_present_tag_9}


```
 is_tag_present(tag) 
```

Bestämmer om taggen finns i alternativen eller inte.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tag | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Tagg‑id‑et att kontrollera. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om taggen finns; annars <c>false</c>. |


### Method: remove_tag(tag) {#remove_tag_tag_10}


```
 remove_tag(tag) 
```

Tar bort taggen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tag | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Taggen att ta bort. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | true om den har tagits bort framgångsrikt |


### Method: remove_tags(tags) {#remove_tags_tags_11}


```
 remove_tags(tags) 
```

Tar bort taggarna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tags | [TiffTags[]](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Taggarna att ta bort. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | **True** om storleken på tagg‑samlingen har ändrats. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_12}


```
 try_set_metadata(metadata) 
```

Försöker sätta en _metadata_-instans, om detta [Image](/imaging/python-net/aspose.imaging/image/)-instans stödjer och implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)-instansen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | Metadata. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Sant om _metadata_ inte är null och [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/)‑instansen <br/>            stöder och/eller implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)‑instansen; annars falskt. |


