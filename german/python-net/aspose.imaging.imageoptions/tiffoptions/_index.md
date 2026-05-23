---
title: "TiffOptions Klasse"
type: docs
weight: 330
url: /de/python-net/aspose.imaging.imageoptions/tiffoptions/
---

**Summary:** The tiff file format options.<br/>                Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly.<br/>                Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.TiffOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [TiffOptions(expected_format)](#TiffOptions_expected_format_1) | Initialisiert eine neue Instanz der [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) Klasse. Standardmäßig wird die Little‑Endian‑Konvention verwendet. |
| [TiffOptions(expected_format, byte_order)](#TiffOptions_expected_format_byte_order_2) | Initialisiert eine neue Instanz der [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) Klasse. |
| [TiffOptions(options)](#TiffOptions_options_3) | Initialisiert eine neue Instanz der [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) Klasse. |
| [TiffOptions(tags)](#TiffOptions_tags_4) | Initialisiert eine neue Instanz der [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffalphastorage/) | r/w | Liest oder legt die Alpha-Speicheroption fest. Optionen außer [TiffAlphaStorage.UNSPECIFIED](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffalphastorage/)<br/>            werden verwendet, wenn mehr als 3 [TiffOptions.samples_per_pixel](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) definiert sind. |
| artist | string | r/w | Liest oder setzt den Künstler. |
| bits_per_pixel | int | r | Liefert die Bits pro Pixel. |
| bits_per_sample | int[] | r/w | Liest oder setzt die Bits pro Sample. |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | r/w | Liest oder legt einen Wert fest, der die TIFF-Byte-Reihenfolge angibt. |
| color_map | int[] | r/w | Liest oder legt die Farbkarte fest. |
| [compressed_quality](#compressed_quality1) | int | r/w | Liest oder legt die komprimierte Bildqualität fest.<br/>            Wird mit der JPEG-Kompression verwendet. |
| compression | [TiffCompressions](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffcompressions/) | r/w | Liest oder setzt die Kompression. |
| Urheberrecht | string | r/w | Liest oder setzt das Urheberrecht. |
| date_time | string | r/w | Liest oder legt Datum und Uhrzeit fest. |
| default_memory_allocation_limit | int | r/w | Liest oder setzt das Standard‑Speicherzuweisungs‑Limit. |
| disable_icc_export | bool | r/w | Liest oder legt einen Wert fest, der angibt, ob der ICC-Profil-Export deaktiviert ist (das ICC-Profil wird vorher auf die Quellpixel angewendet). |
| freigegeben | bool | r | Liest einen Wert, der angibt, ob diese Instanz freigegeben ist. |
| document_name | string | r/w | Liest oder legt den Namen des Dokuments fest. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Liest oder setzt Exif-Daten. |
| exif_ifd | [TiffExifIfd](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffexififd/) | r | Liest oder setzt den Zeiger auf EXIF IFD. |
| extra_samples | int[] | r | Liest die Werte der zusätzlichen Proben. |
| fax_t4_options | [Group3Options](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/group3options/) | r/w | Liest oder legt die Fax‑T4-Optionen fest. |
| file_standard | [TiffFileStandards](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifffilestandards/) | r/w | Liest oder legt den TIFF-Dateistandard fest. |
| fill_order | [TiffFillOrders](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifffillorders/) | r/w | Liest oder legt die Füllreihenfolge der Byte‑Bits fest. |
| full_frame | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [full frame]. |
| half_tone_hints | int[] | r/w | Liest oder legt die Halftone-Hinweise fest. |
| image_description | string | r/w | Liest oder setzt die Bildbeschreibung. |
| image_length | int | r/w | Liest oder setzt die Bildlänge. |
| image_width | int | r/w | Liest oder setzt die Bildbreite. |
| ink_names | string | r/w | Liest oder setzt die Tintenamen. |
| is_extra_samples_present | bool | r | Liest einen Wert, der angibt, ob die zusätzlichen Proben vorhanden sind. |
| is_tiled | bool | r | Liest einen Wert, der angibt, ob das Bild gekachelt ist. |
| is_valid | bool | r | Liest einen Wert, der angibt, ob die [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) korrekt konfiguriert wurden. Verwenden Sie die Validate-Methode, um den Fehlgrund zu finden. |
| keep_metadata | bool | r/w | Liest einen Wert, ob die ursprünglichen Bildmetadaten beim Export beibehalten werden sollen. |
| max_sample_value | int[] | r/w | Liest oder setzt den maximalen Stichprobenwert. |
| min_sample_value | int[] | r/w | Liest oder setzt den minimalen Stichprobenwert. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Die Mehrseiten‑Optionen |
| orientation | [TiffOrientations](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifforientations/) | r/w | Ruft die Ausrichtung ab oder legt sie fest. |
| page_name | string | r/w | Liest oder setzt den Seitennamen. |
| page_number | int[] | r/w | Liest oder setzt das Seitenzahl-Tag. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Liest oder setzt die Farbpalette. |
| photometric | [TiffPhotometrics](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffphotometrics/) | r/w | Liest oder setzt die Photometrie. |
| planar_configuration | [TiffPlanarConfigs](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | Liest oder setzt die planare Konfiguration. |
| predictor | [TiffPredictor](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffpredictor/) | r/w | Liest oder setzt den Prädiktor für die LZW-Kompression. |
| premultiply_components | bool | r/w | Liest oder setzt einen Wert, der angibt, ob Komponenten vormultipliziert werden müssen. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Liest oder setzt die Auflösungseinstellungen. |
| resolution_unit | [TiffResolutionUnits](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffresolutionunits/) | r/w | Liest oder setzt die Auflösungseinheit. |
| rows_per_strip | int | r/w | Liest oder setzt die Zeilen pro Streifen. |
| sample_format | [TiffSampleFormats[]](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffsampleformats/) | r/w | Liest oder setzt das Stichprobenformat. |
| samples_per_pixel | int | r | Liest die Stichproben pro Pixel. Um diesen Eigenschaftswert zu ändern, verwenden Sie den Setter der [TiffOptions.bits_per_sample](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) Eigenschaft. |
| scanner_manufacturer | string | r/w | Liest oder setzt den Scannerhersteller. |
| scanner_model | string | r/w | Liest oder setzt das Scanner-Modell. |
| smax_sample_value | int[] | r/w | Liest oder setzt den maximalen Stichprobenwert. Der Wert hat einen Feldtyp, der am besten zu den Stichprobendaten passt (Byte-, Short- oder Long-Typ). |
| smin_sample_value | int[] | r/w | Liest oder setzt den minimalen Stichprobenwert. Der Wert hat einen Feldtyp, der am besten zu den Stichprobendaten passt (Byte-, Short- oder Long-Typ). |
| software_type | string | r/w | Liest oder setzt den Softwaretyp. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Liest oder setzt die Quelle, in der das Bild erstellt wird. |
| strip_byte_counts | int[] | r/w | Liest oder setzt die Strip-Byte-Anzahlen. |
| strip_offsets | int[] | r/w | Liest oder setzt die Strip-Offsets. |
| sub_file_type | [TiffNewSubFileTypes](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | Liest oder setzt eine allgemeine Angabe zur Art der in dieser Unterdatei enthaltenen Daten. |
| tag_count | int | r | Liest die Tag-Anzahl. |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Liest oder setzt die Tags. |
| target_printer | string | r/w | Liest oder setzt den Ziel-Drucker. |
| threshholding | [TiffThresholds](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffthresholds/) | r/w | Liest oder setzt die Schwellenwertbestimmung. |
| tile_byte_counts | int[] | r/w | Liest oder setzt die Tile-Byte-Anzahlen. |
| tile_length | int | r/w | Liest ot setzt die Tile-Länge. |
| tile_offsets | int[] | r/w | Liest oder setzt die Tile-Offsets. |
| tile_width | int | r/w | Liest ot setzt die Tile-Breite. |
| total_pages | int | r | Ermittelt die Gesamtseitenzahl. |
| valid_tag_count | int | r | Ermittelt die gültige Tag-Anzahl. Dies ist nicht die Gesamtanzahl der Tags, sondern die Anzahl der Tags, die erhalten bleiben können. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Liest oder setzt die Vektor‑Rasterisierungsoptionen. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Liest oder setzt den XMP‑Metadatencontainer. |
| xp_author | string | r/w | Liest oder setzt den Bildautor, der von Windows Explorer verwendet wird. |
| xp_comment | string | r/w | Liest oder setzt den Kommentar zum Bild, der von Windows Explorer verwendet wird. |
| xp_keywords | string | r/w | Liest oder setzt den Betreff des Bildes, der von Windows Explorer verwendet wird. |
| xp_subject | string | r/w | Liest oder setzt Informationen zum Bild, die von Windows Explorer verwendet werden. |
| xp_title | string | r/w | Liest oder setzt Informationen zum Bild, die von Windows Explorer verwendet werden. |
| xposition | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die X-Position. |
| xresolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die X-Auflösung. |
| y_cb_cr_coefficients | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die YCbCr-Koeffizienten. |
| y_cb_cr_subsampling | int[] | r/w | Liest oder setzt die Subsampling-Faktoren für die YCbCr-Photometrie. |
| yposition | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die Y-Position. |
| yresolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die y‑Auflösung. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | Fügt ein neues Tag hinzu. |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | Fügt die Tags hinzu. |
| [clone()](#clone__3) | Klont diese Instanz. |
| [create_with_format(expected_format)](#create_with_format_expected_format_4) | Initialisiert eine neue Instanz der [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) Klasse. Standardmäßig wird die Little‑Endian‑Konvention verwendet. |
| [create_with_options(options)](#create_with_options_options_5) | Initialisiert eine neue Instanz der [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) Klasse. |
| [create_with_tags(tags)](#create_with_tags_tags_6) | Initialisiert eine neue Instanz der [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) Klasse. |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_7) | Ermittelt die Instanz des Tags nach Typ. |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_8) | Ermittelt die Anzahl gültiger Tags. |
| [is_tag_present(tag)](#is_tag_present_tag_9) | Bestimmt, ob das Tag in den Optionen vorhanden ist oder nicht. |
| [remove_tag(tag)](#remove_tag_tag_10) | Entfernt das Tag. |
| [remove_tags(tags)](#remove_tags_tags_11) | Entfernt die Tags. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_12) | Versucht, eine _metadata_-Instanz zu setzen, falls diese [Image](/imaging/python-net/aspose.imaging/image/)‑Instanz unterstützt und eine [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)‑Instanz implementiert. |
| validate() | Validiert, ob Optionen eine gültige Kombination von Tags haben |


### Constructor: TiffOptions(expected_format) {#TiffOptions_expected_format_1}


```
 TiffOptions(expected_format) 
```

Initialisiert eine neue Instanz der [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) Klasse. Standardmäßig wird die Little‑Endian‑Konvention verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | Das erwartete TIFF‑Dateiformat. |

### Constructor: TiffOptions(expected_format, byte_order) {#TiffOptions_expected_format_byte_order_2}


```
 TiffOptions(expected_format, byte_order) 
```

Initialisiert eine neue Instanz der [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | Das erwartete TIFF‑Dateiformat. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | Die Byte-Reihenfolge des Tiff-Dateiformats, die verwendet werden soll. |

### Constructor: TiffOptions(options) {#TiffOptions_options_3}


```
 TiffOptions(options) 
```

Initialisiert eine neue Instanz der [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) | Die Optionen, von denen kopiert werden soll. |

### Constructor: TiffOptions(tags) {#TiffOptions_tags_4}


```
 TiffOptions(tags) 
```

Initialisiert eine neue Instanz der [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Die Tags, mit denen Optionen initialisiert werden. |

### Property: compressed_quality {#compressed_quality1}

Liest oder legt die komprimierte Bildqualität fest.<br/>            Wird mit der JPEG-Kompression verwendet.

**See also:**

**[Example # 1](#example_117)**: This example shows how to create a TIFF image with the Jpeg compression and t...


### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

Fügt ein neues Tag hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Das hinzuzufügende Tag. |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

Fügt die Tags hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Die hinzuzufügenden Tags. |

### Method: clone() {#clone__3}


```
 clone() 
```

Klont diese Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Gibt eine tiefe Kopie zurück. |


### Method: create_with_format(expected_format)  [static] {#create_with_format_expected_format_4}


```
 create_with_format(expected_format) 
```

Initialisiert eine neue Instanz der [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) Klasse. Standardmäßig wird die Little‑Endian‑Konvention verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | Das erwartete TIFF‑Dateiformat. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) |  |


### Method: create_with_options(options)  [static] {#create_with_options_options_5}


```
 create_with_options(options) 
```

Initialisiert eine neue Instanz der [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) | Die Optionen, von denen kopiert werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) |  |


### Method: create_with_tags(tags)  [static] {#create_with_tags_tags_6}


```
 create_with_tags(tags) 
```

Initialisiert eine neue Instanz der [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Die Tags, mit denen Optionen initialisiert werden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) |  |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_7}


```
 get_tag_by_type(tag_key) 
```

Ermittelt die Instanz des Tags nach Typ.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tag_key | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Der Tag‑Schlüssel. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Instanz des Tags, falls vorhanden, sonst null. |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_8}


```
 get_valid_tags_count(tags) 
```

Ermittelt die Anzahl gültiger Tags.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Die zu validierenden Tags. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die Anzahl gültiger Tags. |


### Method: is_tag_present(tag) {#is_tag_present_tag_9}


```
 is_tag_present(tag) 
```

Bestimmt, ob das Tag in den Optionen vorhanden ist oder nicht.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tag | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Die zu prüfende Tag-ID. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn das Tag vorhanden ist; andernfalls <c>false</c>. |


### Method: remove_tag(tag) {#remove_tag_tag_10}


```
 remove_tag(tag) 
```

Entfernt das Tag.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tag | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Das zu entfernende Tag. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | true, wenn erfolgreich entfernt |


### Method: remove_tags(tags) {#remove_tags_tags_11}


```
 remove_tags(tags) 
```

Entfernt die Tags.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tags | [TiffTags[]](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Die zu entfernenden Tags. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | **True** wenn die Größe der Tag-Sammlung geändert wurde. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_12}


```
 try_set_metadata(metadata) 
```

Versucht, eine _metadata_-Instanz zu setzen, falls diese [Image](/imaging/python-net/aspose.imaging/image/)‑Instanz unterstützt und eine [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)‑Instanz implementiert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | Die Metadaten. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | True, wenn die [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) Instanz unterstützt und/oder das [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) implementiert; andernfalls false. |


## **Examples**
### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# Erstelle eine Instanz eines Dateistreams
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# Erstellen Sie eine Instanz von TiffOptions und setzen Sie deren verschiedene Eigenschaften
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Legen Sie die Quelle für die Instanz von ImageOptions fest
	tiffOptions.source = StreamSource(stream)
	# Erstellen Sie eine Instanz von Image
	with Image.create(tiffOptions, 500, 500) as image:
		# Erstelle und initialisiere eine Instanz der Graphics Klasse.
		graphics = Graphics(image)
		# Lösche die Graphics-Oberfläche.
		graphics.clear(Color.wheat);
		# Erstellen Sie eine Instanz der Klasse GraphicsPath
		graphics_path = GraphicsPath()
		# Erstellen Sie eine Instanz der Klasse Figure
		figure = Figure()
		# Fügen Sie dem Figure-Objekt Formen hinzu
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Fügen Sie das Figure-Objekt zu GraphicsPath hinzu
		graphics_path.add_figure(figure)
		# Zeichnen Sie den Pfad mit dem Pen-Objekt in der Farbe Schwarz
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# Alle Änderungen speichern.
		image.save()


```

### This example demonstrates the use of different classes from `imageoptions` package for export purposes. A gif image is loaded as an instance of Image and then exported out to several formats. {#example_15}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions, JpegOptions, PngOptions, TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from os.path import join as path_join

directory = "c:\\temp\\"
#Lade ein vorhandenes GIF-Bild als Instanz der Image‑Klasse
with Image.load(path_join(directory, "sample.gif")) as image:
	# Exportiere in das BMP-Dateiformat unter Verwendung der Standardoptionen
	image.save(path_join(directory, "output.bmp"), BmpOptions())
	# Exportiere in das JPEG-Dateiformat unter Verwendung der Standardoptionen
	image.save(path_join(directory, "output.jpg"), JpegOptions())
	# Exportiere in das PNG-Dateiformat unter Verwendung der Standardoptionen
	image.save(path_join(directory, "output.png"), PngOptions())
	# Exportiere in das TIFF-Dateiformat unter Verwendung der Standardoptionen
	image.save(path_join(directory, "output.tif"), TiffOptions(TiffExpectedFormat.DEFAULT))


```

### This example shows how to create a TIFF image with the Jpeg compression and the specified compressed image quality. {#example_117}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.imageoptions import TiffOptions   
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat, TiffPhotometrics, TiffCompressions

with aspycore.as_of(Image.load("zeebra.tif"), TiffImage) as image:
	tiff_options = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Setzt das RGB‑Farbmodell.
	tiff_options.photometric = TiffPhotometrics.RGB
	# Setzt die JPEG‑Kompression.
	tiff_options.compression = TiffCompressions.JPEG
	tiff_options.compressed_quality = 50
	# Setzt 8 Bits für jede Farbkomponente.
	tiff_options.bits_per_sample = [8, 8, 8]
	image.save("zeebra.tif-50.tiff", tiff_options)


```

