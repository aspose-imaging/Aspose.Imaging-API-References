---
title: "CmxImagePage Klasse"
type: docs
weight: 110
url: /de/python-net/aspose.imaging.fileformats.cmx/cmximagepage/
---

**Summary:** The image of CMX page

**Module:** [aspose.imaging.fileformats.cmx](/imaging/python-net/aspose.imaging.fileformats.cmx/)

**Full Name:** aspose.imaging.fileformats.cmx.CmxImagePage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IObjectWithSizeF, ICmxImage, VectorImage

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [CmxImagePage(cmx_page)](#CmxImagePage_cmx_page_1) | Initialisiert eine neue Instanz der [CmxImagePage](/imaging/python-net/aspose.imaging.fileformats.cmx/cmximagepage/) Klasse. |
| [CmxImagePage(cmx_page, container)](#CmxImagePage_cmx_page_container_2) | Initialisiert eine neue Instanz der [CmxImagePage](/imaging/python-net/aspose.imaging.fileformats.cmx/cmximagepage/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die automatische Anpassung der Palette erfolgt. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Liest oder setzt einen Wert für die Hintergrundfarbe. |
| bits_per_pixel | int | r | Liest die Bit‑Pro‑Pixel‑Anzahl des Bildes. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Liest die Objektgrenzen. |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| cmx_page | [CmxPage](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel/cmxpage/) | r | Liefert die CMX‑Seite. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Liest den [Image](/imaging/python-net/aspose.imaging/image/) Container. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Liest den Datenstrom des Objekts. |
| freigegeben | bool | r | Liest einen Wert, der angibt, ob diese Instanz freigegeben ist. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Liest oder setzt die Exif‑Instanz. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Gibt einen Wert des Dateiformats zurück |
| has_background_color | bool | r/w | Liest oder setzt einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| height | int | r | Liest die Bildhöhe. |
| height_f | float | r | Liefert die Objekthöhe in Zoll. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Liest oder setzt den Interrupt-Monitor. |
| is_cached | bool | r | Gibt einen Wert zurück, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Gibt die Metadaten des Bildes zurück. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Liest oder setzt die Farbpalette. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Liest die Objektgröße. |
| size_f | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r | Liefert die Objektgröße in Zoll. |
| use_palette | bool | r | Liest einen Wert, der angibt, ob die Bildpalette verwendet wird. |
| width | int | r | Liest die Bildbreite. |
| width_f | float | r | Liefert die Objektbreite in Zoll. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Liest oder setzt XMP-Daten. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| cache_data() | Cache kann nicht verwendet werden. |
| [can_load(file_path)](#can_load_file_path_1) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann und optional die angegebenen Öffnungsoptionen verwendet. |
| [can_load(stream)](#can_load_stream_3) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann. |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann und optional die angegebenen _loadOptions_ verwendet. |
| [can_load_stream(stream)](#can_load_stream_stream_5) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_6) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann und optional die angegebenen _loadOptions_ verwendet. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_7) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann und optional die angegebenen Öffnungsoptionen verwendet. |
| [can_save(options)](#can_save_options_8) | Bestimmt, ob das Bild im angegebenen Dateiformat, das durch die übergebenen Speicheroptionen repräsentiert wird, gespeichert werden kann. |
| [create(files)](#create_files_9) | Erstellt das mehrseitige Bild, das die angegebenen Dateien enthält. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_10) | Erstellt das mehrseitige Bild, das die angegebenen Dateien enthält. |
| [create(image_options, width, height)](#create_image_options_width_height_11) | Erstellt ein neues Bild mit den angegebenen Erstellungsoptionen. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_12) | Erstellt eine [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) Instanz aus dem bereitgestellten Pixelarray.<br/>            <br/>            Validiert, dass die angegebene Breite und Höhe den Abmessungen der Pixeldaten entsprechen.<br/>            Diese Methode kann nur verwendet werden, wenn die Bibliothek im lizenzierten Modus ist. |
| [create(images)](#create_images_13) | Erstellt ein neues Bild, das die angegebenen Bilder als Seiten verwendet |
| [create(images, dispose_images)](#create_images_dispose_images_14) | Erstellt ein neues Bild, wobei die angegebenen Bilder als Seiten verwendet werden. |
| [create(multipage_create_options)](#create_multipage_create_options_15) | Erstellt die angegebenen Mehrseiten‑Erstellungsoptionen. |
| [create_from_files(files)](#create_from_files_files_16) | Erstellt das Mehrseiten‑Bild, das die angegebenen Dateien als Lazy‑Loading‑Seiten enthält. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_17) | Erstellt das Mehrseiten‑Bild, das die angegebenen Dateien als Lazy‑Loading‑Seiten enthält. |
| [create_from_images(images)](#create_from_images_images_18) | Erstellt ein neues Bild, das die angegebenen Bilder als Seiten verwendet |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_19) | Erstellt ein neues Bild, wobei die angegebenen Bilder als Seiten verwendet werden. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_20) | Bild mit Verschiebungen zuschneiden. |
| [crop(rectangle)](#crop_rectangle_21) | Schneidet das angegebene Rechteck zu. |
| [get_default_options(args)](#get_default_options_args_22) | Liefert die Standardoptionen. |
| [get_embedded_images()](#get_embedded_images__23) | Liefert die eingebetteten Bilder. |
| [get_file_format(file_path)](#get_file_format_file_path_24) | Liefert das Dateiformat. |
| [get_file_format(stream)](#get_file_format_stream_25) | Liefert das Dateiformat. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_26) | Liefert das Dateiformat. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_27) | Liefert das Rechteck, das zum aktuellen Bild passt. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_28) | Liefert das Rechteck, das zum aktuellen Bild passt. |
| [get_original_options()](#get_original_options__29) | Liefert die Optionen basierend auf den ursprünglichen Dateieinstellungen.<br/>            Dies kann hilfreich sein, um die Bit‑Tiefe und andere Parameter des Originalbildes unverändert zu lassen.<br/>            Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es anschließend mit der<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/)‑Methode speichern, wird ein PNG‑Ausgabebild mit 8 Bit pro Pixel erzeugt.<br/>            Um dies zu vermeiden und ein PNG‑Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und übergeben Sie sie<br/>            an die [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/)‑Methode als zweiten Parameter. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_30) | Liefert eine proportionale Höhe. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_31) | Liefert eine proportionale Breite. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_32) | Konvertiert zu aps. |
| [load(file_path)](#load_file_path_33) | Lädt ein neues Bild vom angegebenen Dateipfad oder URL.<br/>            Wenn _filePath_ ein Dateipfad ist, öffnet die Methode einfach die Datei.<br/>            Wenn _filePath_ eine URL ist, lädt die Methode die Datei herunter, speichert sie temporär und öffnet sie. |
| [load(file_path, load_options)](#load_file_path_load_options_34) | Lädt ein neues Bild vom angegebenen Dateipfad oder URL.<br/>            Wenn _filePath_ ein Dateipfad ist, öffnet die Methode einfach die Datei.<br/>            Wenn _filePath_ eine URL ist, lädt die Methode die Datei herunter, speichert sie temporär und öffnet sie. |
| [load(stream)](#load_stream_35) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load(stream, load_options)](#load_stream_load_options_36) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load_stream(stream)](#load_stream_stream_37) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_38) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_39) | Lädt ein neues Bild vom angegebenen Dateipfad oder URL.<br/>            Wenn _filePath_ ein Dateipfad ist, öffnet die Methode einfach die Datei.<br/>            Wenn _filePath_ eine URL ist, lädt die Methode die Datei herunter, speichert sie temporär und öffnet sie. |
| remove_background() | Entfernt den Hintergrund. |
| [remove_background(settings)](#remove_background_settings_40) | Entfernt den Hintergrund. |
| remove_metadata() | Entfernt Metadaten. |
| [resize(new_width, new_height)](#resize_new_width_new_height_41) | Skaliert das Bild. Der Standardwert [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_42) | Ändert die Größe auf die angegebene neue Breite. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_43) | Skaliert das Bild mit erweiterten Optionen. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_44) | Skaliert das Bild. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_45) | Skaliert das Bild. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_46) | Skaliert die Höhe proportional. Der Standard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_47) | Skaliert die Höhe proportional. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_48) | Skaliert die Höhe proportional. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_49) | Skaliert die Höhe proportional. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_50) | Skaliert die Breite proportional. Der Standard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_51) | Skaliert die Breite proportional. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_52) | Skaliert die Breite proportional. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_53) | Skaliert die Breite proportional. |
| [rotate(angle)](#rotate_angle_54) | Bild um das Zentrum drehen. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_55) | Dreht, spiegelt oder dreht und spiegelt das Bild. |
| save() | Speichert die Bilddaten in den zugrunde liegenden Stream. |
| [save(file_path)](#save_file_path_56) | Speichert das Bild am angegebenen Dateipfad. |
| [save(file_path, options)](#save_file_path_options_57) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_58) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(file_path, over_write)](#save_file_path_over_write_59) | Speichert die Daten des Objekts am angegebenen Speicherort. |
| [save(stream)](#save_stream_60) | Speichert die Daten. |
| [save(stream, options_base)](#save_stream_options_base_61) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_62) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_to_stream(stream)](#save_to_stream_stream_63) | Speichert die Daten des Objekts in den angegebenen Stream. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_64) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_65) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_66) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_67) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_68) | Setzt die Bildpalette. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_69) | Versucht, eine _metadata_-Instanz zu setzen, falls diese [Image](/imaging/python-net/aspose.imaging/image/)‑Instanz unterstützt und eine [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)‑Instanz implementiert. |


### Constructor: CmxImagePage(cmx_page) {#CmxImagePage_cmx_page_1}


```
 CmxImagePage(cmx_page) 
```

Initialisiert eine neue Instanz der [CmxImagePage](/imaging/python-net/aspose.imaging.fileformats.cmx/cmximagepage/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmx_page | [CmxPage](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel/cmxpage/) | Die CMX-Seite. |

### Constructor: CmxImagePage(cmx_page, container) {#CmxImagePage_cmx_page_container_2}


```
 CmxImagePage(cmx_page, container) 
```

Initialisiert eine neue Instanz der [CmxImagePage](/imaging/python-net/aspose.imaging.fileformats.cmx/cmximagepage/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmx_page | [CmxPage](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel/cmxpage/) | Die CMX-Seite. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | Der Container. |

### Method: can_load(file_path)  [static] {#can_load_file_path_1}


```
 can_load(file_path) 
```

Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn das Bild aus der angegebenen Datei geladen werden kann; andernfalls <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


```
 can_load(file_path, load_options) 
```

Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann und optional die angegebenen Öffnungsoptionen verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Die Ladeoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn das Bild aus der angegebenen Datei geladen werden kann; andernfalls <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_3}


```
 can_load(stream) 
```

Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, aus dem geladen werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn das Bild aus dem angegebenen Stream geladen werden kann; andernfalls <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


```
 can_load(stream, load_options) 
```

Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann und optional die angegebenen _loadOptions_ verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, aus dem geladen werden soll. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Die Ladeoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn das Bild aus dem angegebenen Stream geladen werden kann; andernfalls <c>false</c>. |


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_5}


```
 can_load_stream(stream) 
```

Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, aus dem geladen werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn das Bild aus dem angegebenen Stream geladen werden kann; andernfalls <c>false</c>. |


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_6}


```
 can_load_stream_with_options(stream, load_options) 
```

Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann und optional die angegebenen _loadOptions_ verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, aus dem geladen werden soll. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Die Ladeoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn das Bild aus dem angegebenen Stream geladen werden kann; andernfalls <c>false</c>. |


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_7}


```
 can_load_with_options(file_path, load_options) 
```

Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann und optional die angegebenen Öffnungsoptionen verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Die Ladeoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn das Bild aus der angegebenen Datei geladen werden kann; andernfalls <c>false</c>. |


### Method: can_save(options) {#can_save_options_8}


```
 can_save(options) 
```

Bestimmt, ob das Bild im angegebenen Dateiformat, das durch die übergebenen Speicheroptionen repräsentiert wird, gespeichert werden kann.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die zu verwendenden Speicheroptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn das Bild im angegebenen Dateiformat, das durch die übergebenen Speicheroptionen dargestellt wird, gespeichert werden kann; andernfalls <c>false</c>. |


### Method: create(files)  [static] {#create_files_9}


```
 create(files) 
```

Erstellt das mehrseitige Bild, das die angegebenen Dateien enthält.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Dateien | string[] | Die Dateien. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Das mehrseitige Bild |


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_10}


```
 create(files, throw_exception_on_load_error) 
```

Erstellt das mehrseitige Bild, das die angegebenen Dateien enthält.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Dateien | string[] | Die Dateien. |
| throw_exception_on_load_error | bool | wenn auf <c>true</c> gesetzt [Ausnahme bei Ladefehler werfen]. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Das mehrseitige Bild |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_11}


```
 create(image_options, width, height) 
```

Erstellt ein neues Bild mit den angegebenen Erstellungsoptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Bildoptionen. |
| width | int | Die Breite. |
| height | int | Die Höhe. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Das neu erstellte Bild. |


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_12}


```
 create(image_options, width, height, pixels) 
```

Erstellt eine [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) Instanz aus dem bereitgestellten Pixelarray.<br/>            <br/>            Validiert, dass die angegebene Breite und Höhe den Abmessungen der Pixeldaten entsprechen.<br/>            Diese Methode kann nur verwendet werden, wenn die Bibliothek im lizenzierten Modus ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Optionen, die zum Erstellen des [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) verwendet werden. |
| width | int | Die Breite des [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| height | int | Die Höhe des [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| Pixel | int[] | Das Array von Pixelwerten, das zum Befüllen des Bildes verwendet wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Ein [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) gefüllt mit den bereitgestellten Pixeldaten. |


### Method: create(images)  [static] {#create_images_13}


```
 create(images) 
```

Erstellt ein neues Bild, das die angegebenen Bilder als Seiten verwendet

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Die Bilder. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild als IMultipageImage |


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_14}


```
 create(images, dispose_images) 
```

Erstellt ein neues Bild, wobei die angegebenen Bilder als Seiten verwendet werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Die Bilder. |
| dispose_images | bool | wenn auf <c>true</c> gesetzt [Bilder freigeben]. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild als IMultipageImage |


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_15}


```
 create(multipage_create_options) 
```

Erstellt die angegebenen Mehrseiten‑Erstellungsoptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| multipage_create_options | [MultipageCreateOptions](/imaging/python-net/aspose.imaging.imageoptions/multipagecreateoptions/) | Die Optionen zum Erstellen von mehrseitigen Bildern. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Das mehrseitige Bild |


### Method: create_from_files(files)  [static] {#create_from_files_files_16}


```
 create_from_files(files) 
```

Erstellt das Mehrseiten‑Bild, das die angegebenen Dateien als Lazy‑Loading‑Seiten enthält.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Dateien | string[] | Die Dateien. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Das mehrseitige Bild |


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_17}


```
 create_from_files(files, throw_exception_on_load_error) 
```

Erstellt das Mehrseiten‑Bild, das die angegebenen Dateien als Lazy‑Loading‑Seiten enthält.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Dateien | string[] | Die Dateien. |
| throw_exception_on_load_error | bool | wenn auf <c>true</c> gesetzt, Ausnahme bei Ladefehler werfen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Das mehrseitige Bild |


### Method: create_from_images(images)  [static] {#create_from_images_images_18}


```
 create_from_images(images) 
```

Erstellt ein neues Bild, das die angegebenen Bilder als Seiten verwendet

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Die Bilder. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild als IMultipageImage |


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_19}


```
 create_from_images(images, dispose_images) 
```

Erstellt ein neues Bild, wobei die angegebenen Bilder als Seiten verwendet werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Die Bilder. |
| dispose_images | bool | wenn auf <c>true</c> gesetzt [Bilder freigeben]. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild als IMultipageImage |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_20}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Bild mit Verschiebungen zuschneiden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| left_shift | int | Die linke Verschiebung. |
| right_shift | int | Die rechte Verschiebung. |
| top_shift | int | Die obere Verschiebung. |
| bottom_shift | int | Die untere Verschiebung. |

### Method: crop(rectangle) {#crop_rectangle_21}


```
 crop(rectangle) 
```

Schneidet das angegebene Rechteck zu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck. |

### Method: get_default_options(args) {#get_default_options_args_22}


```
 get_default_options(args) 
```

Liefert die Standardoptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| args | System.Object | Die Argumente. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Standardoptionen |


### Method: get_embedded_images() {#get_embedded_images__23}


```
 get_embedded_images() 
```

Liefert die eingebetteten Bilder.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [EmbeddedImage[]](/imaging/python-net/aspose.imaging/embeddedimage/) | Array von Bildern |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_24}


```
 get_file_format(file_path) 
```

Liefert das Dateiformat.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Das ermittelte Dateiformat. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_25}


```
 get_file_format(stream) 
```

Liefert das Dateiformat.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Das ermittelte Dateiformat. |


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_26}


```
 get_file_format_of_stream(stream) 
```

Liefert das Dateiformat.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Das ermittelte Dateiformat. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_27}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Liefert das Rechteck, das zum aktuellen Bild passt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, für das ein passendes Rechteck ermittelt werden soll. |
| Pixel | int[] | Die 32‑Bit‑ARGB‑Pixel. |
| width | int | Die Objektbreite. |
| height | int | Die Objekthöhe. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das passende Rechteck oder eine Ausnahme, wenn kein passendes Rechteck gefunden werden kann. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_28}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Liefert das Rechteck, das zum aktuellen Bild passt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, für das ein passendes Rechteck ermittelt werden soll. |
| width | int | Die Objektbreite. |
| height | int | Die Objekthöhe. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das passende Rechteck oder eine Ausnahme, wenn kein passendes Rechteck gefunden werden kann. |


### Method: get_original_options() {#get_original_options__29}


```
 get_original_options() 
```

Liefert die Optionen basierend auf den ursprünglichen Dateieinstellungen.<br/>            Dies kann hilfreich sein, um die Bit‑Tiefe und andere Parameter des Originalbildes unverändert zu lassen.<br/>            Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es anschließend mit der<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/)‑Methode speichern, wird ein PNG‑Ausgabebild mit 8 Bit pro Pixel erzeugt.<br/>            Um dies zu vermeiden und ein PNG‑Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und übergeben Sie sie<br/>            an die [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/)‑Methode als zweiten Parameter.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Optionen basierend auf den ursprünglichen Dateieinstellungen. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_30}


```
 get_proportional_height(width, height, new_width) 
```

Liefert eine proportionale Höhe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | int | Die Breite. |
| height | int | Die Höhe. |
| new_width | int | Die neue Breite. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die proportionale Höhe. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_31}


```
 get_proportional_width(width, height, new_height) 
```

Liefert eine proportionale Breite.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | int | Die Breite. |
| height | int | Die Höhe. |
| new_height | int | Die neue Höhe. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die proportionale Breite. |


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_32}


```
 get_serialized_stream(image_options, clipping_rectangle, page_number) 
```

Konvertiert zu aps.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Bildoptionen. |
| clipping_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Beschneidungsrechteck. |
| page_number | int[] | Die Seitenzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| _io.BufferedRandom | Der serialisierte Stream |


### Method: load(file_path)  [static] {#load_file_path_33}


```
 load(file_path) 
```

Lädt ein neues Bild vom angegebenen Dateipfad oder URL.<br/>            Wenn _filePath_ ein Dateipfad ist, öffnet die Methode einfach die Datei.<br/>            Wenn _filePath_ eine URL ist, lädt die Methode die Datei herunter, speichert sie temporär und öffnet sie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad oder die URL, von der das Bild geladen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Das geladene Bild. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_34}


```
 load(file_path, load_options) 
```

Lädt ein neues Bild vom angegebenen Dateipfad oder URL.<br/>            Wenn _filePath_ ein Dateipfad ist, öffnet die Methode einfach die Datei.<br/>            Wenn _filePath_ eine URL ist, lädt die Methode die Datei herunter, speichert sie temporär und öffnet sie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad oder die URL, von der das Bild geladen wird. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Die Ladeoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Das geladene Bild. |


### Method: load(stream)  [static] {#load_stream_35}


```
 load(stream) 
```

Lädt ein neues Bild aus dem angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, von dem das Bild geladen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Das geladene Bild. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_36}


```
 load(stream, load_options) 
```

Lädt ein neues Bild aus dem angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, von dem das Bild geladen wird. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Die Ladeoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Das geladene Bild. |


### Method: load_stream(stream)  [static] {#load_stream_stream_37}


```
 load_stream(stream) 
```

Lädt ein neues Bild aus dem angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, von dem das Bild geladen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Das geladene Bild. |


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_38}


```
 load_stream_with_options(stream, load_options) 
```

Lädt ein neues Bild aus dem angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, von dem das Bild geladen wird. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Die Ladeoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Das geladene Bild. |


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_39}


```
 load_with_options(file_path, load_options) 
```

Lädt ein neues Bild vom angegebenen Dateipfad oder URL.<br/>            Wenn _filePath_ ein Dateipfad ist, öffnet die Methode einfach die Datei.<br/>            Wenn _filePath_ eine URL ist, lädt die Methode die Datei herunter, speichert sie temporär und öffnet sie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad oder die URL, von der das Bild geladen wird. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Die Ladeoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Das geladene Bild. |


### Method: remove_background(settings) {#remove_background_settings_40}


```
 remove_background(settings) 
```

Entfernt den Hintergrund.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| settings | [RemoveBackgroundSettings](/imaging/python-net/aspose.imaging/removebackgroundsettings/) | Die Einstellungen. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_41}


```
 resize(new_width, new_height) 
```

Skaliert das Bild. Der Standardwert [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_42}


```
 resize(new_width, new_height, resize_type) 
```

Ändert die Größe auf die angegebene neue Breite.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ der Skalierung. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_43}


```
 resize(new_width, new_height, settings) 
```

Skaliert das Bild mit erweiterten Optionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Skalierungseinstellungen. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_44}


```
 resize_by_settings(new_width, new_height, settings) 
```

Skaliert das Bild.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Skalierungseinstellungen. |

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_45}


```
 resize_by_type(new_width, new_height, resize_type) 
```

Skaliert das Bild.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Der Skalierungstyp. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_46}


```
 resize_height_proportionally(new_height) 
```

Skaliert die Höhe proportional. Der Standard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_47}


```
 resize_height_proportionally(new_height, resize_type) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ der Skalierung. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_48}


```
 resize_height_proportionally(new_height, settings) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Bildskalierungseinstellungen. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_49}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Bildskalierungseinstellungen. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_50}


```
 resize_width_proportionally(new_width) 
```

Skaliert die Breite proportional. Der Standard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_51}


```
 resize_width_proportionally(new_width, resize_type) 
```

Skaliert die Breite proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ der Skalierung. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_52}


```
 resize_width_proportionally(new_width, settings) 
```

Skaliert die Breite proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Bildskalierungseinstellungen. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_53}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Skaliert die Breite proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Bildskalierungseinstellungen. |

### Method: rotate(angle) {#rotate_angle_54}


```
 rotate(angle) 
```

Bild um das Zentrum drehen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_55}


```
 rotate_flip(rotate_flip_type) 
```

Dreht, spiegelt oder dreht und spiegelt das Bild.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Typ der Dreh- und Spiegelung. |

### Method: save(file_path) {#save_file_path_56}


```
 save(file_path) 
```

Speichert das Bild am angegebenen Dateipfad.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem das Bild gespeichert wird. |

### Method: save(file_path, options) {#save_file_path_options_57}


```
 save(file_path, options) 
```

Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Optionen. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_58}


```
 save(file_path, options, bounds_rectangle) 
```

Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Optionen. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Zielrechteck der Bildgrenzen. Setzen Sie das leere Rechteck, um Quellgrenzen zu verwenden. |

### Method: save(file_path, over_write) {#save_file_path_over_write_59}


```
 save(file_path, over_write) 
```

Speichert die Daten des Objekts am angegebenen Speicherort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Objektdaten gespeichert werden. |
| over_write | bool | wenn auf <c>true</c> gesetzt, werden die Dateiinhalte überschrieben, andernfalls wird angehängt. |

### Method: save(stream) {#save_stream_60}


```
 save(stream) 
```

Speichert die Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem Daten gespeichert werden. |

### Method: save(stream, options_base) {#save_stream_options_base_61}


```
 save(stream, options_base) 
```

Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem die Bilddaten gespeichert werden. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Speicheroptionen. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_62}


```
 save(stream, options_base, bounds_rectangle) 
```

Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem die Bilddaten gespeichert werden. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Speicheroptionen. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Zielrechteck für die Bildgrenzen. Setzen Sie das leere Rechteck, um die Quellgrenzen zu verwenden. |

### Method: save_to_stream(stream) {#save_to_stream_stream_63}


```
 save_to_stream(stream) 
```

Speichert die Daten des Objekts in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem die Daten des Objekts gespeichert werden sollen. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_64}


```
 save_to_stream_with_options(stream, options_base) 
```

Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem die Bilddaten gespeichert werden. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Speicheroptionen. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_65}


```
 save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) 
```

Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem die Bilddaten gespeichert werden. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Speicheroptionen. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Zielrechteck für die Bildgrenzen. Setzen Sie das leere Rechteck, um die Quellgrenzen zu verwenden. |

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_66}


```
 save_with_options(file_path, options) 
```

Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Optionen. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_67}


```
 save_with_options_rect(file_path, options, bounds_rectangle) 
```

Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Optionen. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Zielrechteck der Bildgrenzen. Setzen Sie das leere Rechteck, um Quellgrenzen zu verwenden. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_68}


```
 set_palette(palette, update_colors) 
```

Setzt die Bildpalette.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die zu setzende Palette. |
| update_colors | bool | Wenn auf <c>true</c> gesetzt, werden die Farben gemäß der neuen Palette aktualisiert; andernfalls bleiben die Farbindizes unverändert. Hinweis: Unveränderte Indizes können das Bild beim Laden zum Absturz bringen, wenn einige Indizes keinen entsprechenden Paletteneintrag haben. |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_69}


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
| bool | Wahr, wenn _metadata_ nicht null ist und die Instanz von [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) <br/>            unterstützt und/oder eine Instanz von [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) implementiert; andernfalls falsch. |


