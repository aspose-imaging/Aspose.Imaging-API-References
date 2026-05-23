---
title: "Image-Klasse"
type: docs
weight: 5650
url: /de/python-net/aspose.imaging/image/
---

**Summary:** The image is the base class for all type of images.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Image

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, DataStreamSupporter

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die automatische Anpassung der Palette erfolgt. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Liest oder setzt einen Wert für die Hintergrundfarbe. |
| bits_per_pixel | int | r | Liest die Bit‑Pro‑Pixel‑Anzahl des Bildes. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Liest die Bildgrenzen. |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Liest den [Image](/imaging/python-net/aspose.imaging/image/) Container. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Liest den Datenstrom des Objekts. |
| freigegeben | bool | r | Liest einen Wert, der angibt, ob diese Instanz freigegeben ist. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Liest oder setzt die Exif-Daten. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Gibt einen Wert des Dateiformats zurück |
| has_background_color | bool | r/w | Liest oder setzt einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| height | int | r | Liest die Bildhöhe. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Liest oder setzt den Interrupt-Monitor. |
| is_cached | bool | r | Gibt einen Wert zurück, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Gibt die Metadaten des Bildes zurück. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Liest oder setzt die Farbpalette. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Liest die Bildgröße. |
| [use_palette](#use_palette1) | bool | r | Liest einen Wert, der angibt, ob die Bildpalette verwendet wird. |
| width | int | r | Liest die Bildbreite. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Liest oder setzt die Xmp-Daten. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| cache_data() | Zwischenspeichert die Daten und stellt sicher, dass keine zusätzlichen Datenladungen vom zugrunde liegenden [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/) durchgeführt werden. |
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
| [get_file_format(file_path)](#get_file_format_file_path_23) | Liefert das Dateiformat. |
| [get_file_format(stream)](#get_file_format_stream_24) | Liefert das Dateiformat. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_25) | Liefert das Dateiformat. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_26) | Liefert das Rechteck, das zum aktuellen Bild passt. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_27) | Liefert das Rechteck, das zum aktuellen Bild passt. |
| [get_original_options()](#get_original_options__28) | Liefert die Optionen basierend auf den ursprünglichen Dateieinstellungen.<br/>            Dies kann hilfreich sein, um die Bit‑Tiefe und andere Parameter des Originalbildes unverändert zu lassen.<br/>            Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es anschließend mit der<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/)‑Methode speichern, wird ein PNG‑Ausgabebild mit 8 Bit pro Pixel erzeugt.<br/>            Um dies zu vermeiden und ein PNG‑Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und übergeben Sie sie<br/>            an die [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/)‑Methode als zweiten Parameter. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_29) | Liefert eine proportionale Höhe. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_30) | Liefert eine proportionale Breite. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_31) | Konvertiert zu aps. |
| [load(file_path)](#load_file_path_32) | Lädt ein neues Bild vom angegebenen Dateipfad oder URL.<br/>            Wenn _filePath_ ein Dateipfad ist, öffnet die Methode einfach die Datei.<br/>            Wenn _filePath_ eine URL ist, lädt die Methode die Datei herunter, speichert sie temporär und öffnet sie. |
| [load(file_path, load_options)](#load_file_path_load_options_33) | Lädt ein neues Bild vom angegebenen Dateipfad oder URL.<br/>            Wenn _filePath_ ein Dateipfad ist, öffnet die Methode einfach die Datei.<br/>            Wenn _filePath_ eine URL ist, lädt die Methode die Datei herunter, speichert sie temporär und öffnet sie. |
| [load(stream)](#load_stream_34) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load(stream, load_options)](#load_stream_load_options_35) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load_stream(stream)](#load_stream_stream_36) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_37) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_38) | Lädt ein neues Bild vom angegebenen Dateipfad oder URL.<br/>            Wenn _filePath_ ein Dateipfad ist, öffnet die Methode einfach die Datei.<br/>            Wenn _filePath_ eine URL ist, lädt die Methode die Datei herunter, speichert sie temporär und öffnet sie. |
| remove_metadata() | Entfernt Metadaten. |
| [resize(new_width, new_height)](#resize_new_width_new_height_39) | Skaliert das Bild. Der Standardwert [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_40) | Skaliert das Bild. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_41) | Skaliert das Bild. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_42) | Skaliert das Bild. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_43) | Skaliert das Bild. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_44) | Skaliert die Höhe proportional. Der Standard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_45) | Skaliert die Höhe proportional. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_46) | Skaliert die Höhe proportional. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_47) | Skaliert die Höhe proportional. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_48) | Skaliert die Breite proportional. Der Standard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_49) | Skaliert die Breite proportional. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_50) | Skaliert die Breite proportional. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_51) | Skaliert die Breite proportional. |
| [rotate(angle)](#rotate_angle_52) | Bild um das Zentrum drehen. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_53) | Dreht, spiegelt oder dreht und spiegelt das Bild. |
| save() | Speichert die Bilddaten in den zugrunde liegenden Stream. |
| [save(file_path)](#save_file_path_54) | Speichert das Bild am angegebenen Dateipfad. |
| [save(file_path, options)](#save_file_path_options_55) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_56) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(file_path, over_write)](#save_file_path_over_write_57) | Speichert die Daten des Objekts am angegebenen Speicherort. |
| [save(stream)](#save_stream_58) | Speichert die Daten des Objekts in den angegebenen Stream. |
| [save(stream, options_base)](#save_stream_options_base_59) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_60) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_to_stream(stream)](#save_to_stream_stream_61) | Speichert die Daten des Objekts in den angegebenen Stream. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_62) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_63) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_64) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_65) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_66) | Setzt die Bildpalette. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_67) | Versucht, eine _metadata_-Instanz zu setzen, falls diese [Image](/imaging/python-net/aspose.imaging/image/) Instanz den Typ [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) unterstützt und implementiert. |


### Property: use_palette {#use_palette1}

Liest einen Wert, der angibt, ob die Bildpalette verwendet wird.

**See also:**

**[Example # 1](#example_221)**: Determine if the palette is used by the image.


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



**See also:**

**[Example # 1](#example_22)**: This example determines whether image can be loaded from a file.


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



**See also:**

**[Example # 1](#example_23)**: This example determines whether image can be loaded from a file stream.


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



**See also:**

**[Example # 1](#example_26)**: This example shows how to determine whether image can be saved to the specifi...


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



**See also:**

**[Example # 1](#example_4)**: This example creates a new Image file at some disk location as specified by S...


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_23}


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



**See also:**

**[Example # 1](#example_24)**: This example shows how to determine the image format without loading the enti...


### Method: get_file_format(stream)  [static] {#get_file_format_stream_24}


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



**See also:**

**[Example # 1](#example_25)**: This example shows how to determine the image format without loading the enti...


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_25}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_26}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_27}


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


### Method: get_original_options() {#get_original_options__28}


```
 get_original_options() 
```

Liefert die Optionen basierend auf den ursprünglichen Dateieinstellungen.<br/>            Dies kann hilfreich sein, um die Bit‑Tiefe und andere Parameter des Originalbildes unverändert zu lassen.<br/>            Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es anschließend mit der<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/)‑Methode speichern, wird ein PNG‑Ausgabebild mit 8 Bit pro Pixel erzeugt.<br/>            Um dies zu vermeiden und ein PNG‑Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und übergeben Sie sie<br/>            an die [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/)‑Methode als zweiten Parameter.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Optionen basierend auf den ursprünglichen Dateieinstellungen. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_29}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_30}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_31}


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


### Method: load(file_path)  [static] {#load_file_path_32}


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



**See also:**

**[Example # 1](#example_1)**: This example demonstrates the loading of an existing Image file into an insta...


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_33}


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


### Method: load(stream)  [static] {#load_stream_34}


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



**See also:**

**[Example # 1](#example_6)**: This example demonstrates the use of a file stream objects to load an existin...


### Method: load(stream, load_options)  [static] {#load_stream_load_options_35}


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


### Method: load_stream(stream)  [static] {#load_stream_stream_36}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_37}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_38}


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


### Method: resize(new_width, new_height) {#resize_new_width_new_height_39}


```
 resize(new_width, new_height) 
```

Skaliert das Bild. Der Standardwert [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |


**See also:**

**[Example # 1](#example_182)**: The following example shows how to resize a metafile (WMF and EMF).

**[Example # 2](#example_185)**: The following example shows how to resize SVG image and save it to PNG.


### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_40}


```
 resize(new_width, new_height, resize_type) 
```

Skaliert das Bild.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Der Skalierungstyp. |


**See also:**

**[Example # 1](#example_209)**: Resize image using specific Resize Type.


### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_41}


```
 resize(new_width, new_height, settings) 
```

Skaliert das Bild.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Skalierungseinstellungen. |


**See also:**

**[Example # 1](#example_28)**: This example loads an image and resizes it using various resizing settings.

**[Example # 2](#example_209)**: Resize image using specific Resize Type.


### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_42}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_43}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_44}


```
 resize_height_proportionally(new_height) 
```

Skaliert die Höhe proportional. Der Standard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_45}


```
 resize_height_proportionally(new_height, resize_type) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ der Skalierung. |


**See also:**

**[Example # 1](#example_30)**: This example loads an image and resizes it proportionally using various resiz...


### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_46}


```
 resize_height_proportionally(new_height, settings) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Bildskalierungseinstellungen. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_47}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Bildskalierungseinstellungen. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_48}


```
 resize_width_proportionally(new_width) 
```

Skaliert die Breite proportional. Der Standard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_49}


```
 resize_width_proportionally(new_width, resize_type) 
```

Skaliert die Breite proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ der Skalierung. |


**See also:**

**[Example # 1](#example_29)**: This example loads an image and resizes it proportionally using various resiz...


### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_50}


```
 resize_width_proportionally(new_width, settings) 
```

Skaliert die Breite proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Bildskalierungseinstellungen. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_51}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Skaliert die Breite proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Bildskalierungseinstellungen. |

### Method: rotate(angle) {#rotate_angle_52}


```
 rotate(angle) 
```

Bild um das Zentrum drehen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_53}


```
 rotate_flip(rotate_flip_type) 
```

Dreht, spiegelt oder dreht und spiegelt das Bild.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Typ der Dreh- und Spiegelung. |


**See also:**

**[Example # 1](#example_8)**: This example demonstrates the use of Rotate operation on an image. Example lo...

**[Example # 2](#example_31)**: This example loads an image, rotates it by 90 degrees clockwise and optionall...


### Method: save(file_path) {#save_file_path_54}


```
 save(file_path) 
```

Speichert das Bild am angegebenen Dateipfad.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem das Bild gespeichert wird. |

### Method: save(file_path, options) {#save_file_path_options_55}


```
 save(file_path, options) 
```

Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Optionen. |


**See also:**

**[Example # 1](#example_9)**: This example shows the simple steps to save an Image. To demonstrate this ope...

**[Example # 2](#example_32)**: The following example loads a BMP image from a file, then saves the image to ...

**[Example # 3](#example_90)**: The following example shows how to save an entire BMP image or part of it to ...


### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_56}


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


**See also:**

**[Example # 1](#example_33)**: The following example loads a BMP image from a file, then saves a rectangular...

**[Example # 2](#example_90)**: The following example shows how to save an entire BMP image or part of it to ...


### Method: save(file_path, over_write) {#save_file_path_over_write_57}


```
 save(file_path, over_write) 
```

Speichert die Daten des Objekts am angegebenen Speicherort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Objektdaten gespeichert werden. |
| over_write | bool | wenn auf <c>true</c> gesetzt, werden die Dateiinhalte überschrieben, andernfalls wird angehängt. |

### Method: save(stream) {#save_stream_58}


```
 save(stream) 
```

Speichert die Daten des Objekts in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem die Daten des Objekts gespeichert werden sollen. |

### Method: save(stream, options_base) {#save_stream_options_base_59}


```
 save(stream, options_base) 
```

Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem die Bilddaten gespeichert werden. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Speicheroptionen. |


**See also:**

**[Example # 1](#example_10)**: This example shows the process of saving an Image to MemoryStream. To demonst...

**[Example # 2](#example_34)**: The following example loads an image from a file, then saves the image to a P...

**[Example # 3](#example_90)**: The following example shows how to save an entire BMP image or part of it to ...


### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_60}


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


**See also:**

**[Example # 1](#example_35)**: The following example loads an image from a file, then saves a rectangular pa...

**[Example # 2](#example_90)**: The following example shows how to save an entire BMP image or part of it to ...


### Method: save_to_stream(stream) {#save_to_stream_stream_61}


```
 save_to_stream(stream) 
```

Speichert die Daten des Objekts in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem die Daten des Objekts gespeichert werden sollen. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_62}


```
 save_to_stream_with_options(stream, options_base) 
```

Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem die Bilddaten gespeichert werden. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Speicheroptionen. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_63}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_64}


```
 save_with_options(file_path, options) 
```

Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Optionen. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_65}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_66}


```
 set_palette(palette, update_colors) 
```

Setzt die Bildpalette.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die zu setzende Palette. |
| update_colors | bool | Wenn auf <c>true</c> gesetzt, werden die Farben gemäß der neuen Palette aktualisiert; andernfalls bleiben die Farbindizes unverändert. Hinweis: Unveränderte Indizes können das Bild beim Laden zum Absturz bringen, wenn einige Indizes keinen entsprechenden Paletteneintrag haben. |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_67}


```
 try_set_metadata(metadata) 
```

Versucht, eine _metadata_-Instanz zu setzen, falls diese [Image](/imaging/python-net/aspose.imaging/image/) Instanz den Typ [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) unterstützt und implementiert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | Die Metadaten. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | True, wenn die [Image](/imaging/python-net/aspose.imaging/image/) Instanz den Typ [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) unterstützt und implementiert; andernfalls false. |


## **Examples**
### This example demonstrates the loading of an existing Image file into an instance of aspose.imaging.Image using file path specified {#example_1}
``` python

from aspose.imaging import Image
# Erstelle Image-Instanz und initialisiere sie mit einer vorhandenen Bilddatei vom Speicherort
with Image.load(r"C:\temp\sample.bmp") as image:
	# Führe einige Bildverarbeitungen durch
	pass


```

### This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case. {#example_4}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#Erstelle eine Instanz von `BmpOptions` und setze ihre verschiedenen Eigenschaften
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24

	#Erstelle eine Instanz von `FileCreateSource` und weise sie als `source` für die Instanz von `BmpOptions` zu
	#Der zweite `Boolean`-Parameter bestimmt, ob die zu erstellende Datei temporär ist oder nicht
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp", False)

	#Erstelle eine Instanz von Image und initialisiere sie mit einer Instanz von BmpOptions, indem du die Create-Methode aufrufst
	with Image.create(bmp_options, 500, 500) as image:
		#Führe einige Bildverarbeitungen durch
		# Speichere alle Änderungen
		image.save()


```

### This example demonstrates the use of a file stream objects to load an existing Image file {#example_6}
``` python

from aspose.imaging import Image

# Erstelle eine Instanz von FileStream
with open(r"C:\temp\sample.bmp", "rb"):
	#Erstelle eine Instanz der Image-Klasse und lade eine vorhandene Datei über das FileStream-Objekt, indem du die Load-Methode aufrufst
	with Image.load(stream) as image:
		#einige Bildverarbeitungen durchführen.
		pass

```

### This example demonstrates the use of Rotate operation on an image. Example loads an existing image file from some disk location and performs the `Rotate` operation on the image according to the value of enumeration `aspose.imaging.RotateFlipType` {#example_8}
``` python

from aspose.imaging import Image, RotateFlipType
#Erstellen Sie eine Instanz der Bildklasse und initialisieren Sie sie mit einer vorhandenen Bilddatei über den Dateipfad
with Image.load(r"C:\temp\sample.bmp") as image:
	# Drehen Sie das Bild um 180 Grad um die X-Achse.
	image.rotate_flip(RotateFlipType.ROTATE_180_FLIP_X)
	# Alle Änderungen speichern.
	image.save()


```

### This example shows the simple steps to save an Image. To demonstrate this operation, we load an existing file from some disk location, performs `rotate` operation on the image and save the image in PSD format using file path {#example_9}
``` python

from aspose.imaging import Image, RotateFlipType
from aspose.imaging.imageoptions import PsdOptions
from os.path import join as path_join

directory = "c:\\temp"

#Erstellen Sie eine Instanz der Bildklasse und initialisieren Sie sie mit einer vorhandenen Datei über den Dateipfad.
with Image.load(path_join(directory, "sample.bmp")) as image:
	#Drehen Sie das Bild um 180 Grad um die X-Achse.
	image.rotate_flip(RotateFlipType.ROTATE_180_FLIP_X)
	#Speichern Sie das Image als PSD zum File Path mit den Standard PsdOptions Einstellungen.
	image.save(path_join(directory, "output.psd"), PsdOptions())


```

### This example shows the process of saving an Image to MemoryStream. To demonstrate this operation, example loads an existing file from some disk location, performs `rotate` operation on the image and save the image in PSD format {#example_10}
``` python
from aspose.imaging import Image, RotateFlipType
from aspose.imaging.imageoptions import PsdOptions
from aspose.imaging.extensions import StreamExtensions as stream_ext

#Erstellen Sie eine Instanz von MemoryStream.
with stream_ext.create_memory_stream() as stream:
	#Erstellen Sie eine Instanz der Bildklasse und initialisieren Sie sie mit einer vorhandenen Datei über den Dateipfad.
	with Image.load(r"C:\temp\sample.bmp") as image:
		#Drehen Sie das Bild um 180 Grad um die X-Achse.
		image.rotate_flip(RotateFlipType.ROTATE_180_FLIP_X)
		#Speichern Sie das Image als PSD in MemoryStream mit den Standard PsdOptions Einstellungen.
		image.save(stream, PsdOptions())


```

### This example determines whether image can be loaded from a file. {#example_22}
``` python

from aspose.imaging import Image

# Verwenden Sie einen absoluten Pfad zur Datei.
can_load: bool = Image.can_load(r"c:\temp\sample.gif")


```

### This example determines whether image can be loaded from a file stream. {#example_23}
``` python

from aspose.imaging import Image
from aspose.imaging.extensions import StreamExtensions as strm_ext
import os.path import join

directory = r"c:\temp"

canLoad = False

# Verwenden Sie einen Dateistream.
with open(join(directory, "sample.bmp"), "rb"):
	canLoad = Image.can_load(stream)

print(f"Can load the file: {canLoad}")

# Die folgenden Daten sind kein gültiger Bildstrom, daher gibt CanLoad false zurück.
imageData = [0, 0, 0, 0, 0, 0, 0, 0]
with strm_ext.create_memory_stream_from_bytes(imageData) as stream:
	canLoad = Image.can_load(stream)

print(f"Can load the byte buffer: {canLoad}")


```

### This example shows how to determine the image format without loading the entire image from a file. {#example_24}
``` python

from aspose.imaging import Image
from os.path import join as path_join

directory = "c:\\temp\\"

# Verwenden Sie einen absoluten Pfad zur Datei.
file_format = Image.get_file_format(path_join(directory, "sample.gif"))
print(f"The file format is {file_format}")


```

### This example shows how to determine the image format without loading the entire image from a file stream. {#example_25}
``` python

from aspose.imaging import Image
from aspose.imaging.extensions import StreamExtensions as strm_ex
from os.path import join as path_join

directory = "c:\\temp\\"

# Verwenden Sie einen Dateistream.
with open(path_join(directory, "sample.bmp"), "rb") as stream:
	file_format = Image.get_file_format(stream)
	print(f"The file format is {file_format}")

# Die folgenden Daten sind kein gültiger Bildstrom, daher gibt get_file_format FileFormat.UNKNOWN zurück.
imageData = bytearray([0, 0, 0, 0, 0, 0, 0, 0])
with strm_ex.create_memory_stream_from_bytes(imageData) as stream:
	file_format = Image.get_file_format(stream)
	print(f"The file format is {file_format}")


```

### This example shows how to determine whether image can be saved to the specified file format represented by the passed save options. {#example_26}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import JpegOptions
from os.path import join as path_join

directory = "c:\\temp\\"

with Image.load(path_join(directory, "sample.gif")) as image:
	saveOptions = JpegOptions()
	saveOptions.quality = 50
	# Bestimmen Sie, ob das Bild als JPEG gespeichert werden kann.
	canSave: bool = image.can_save(saveOptions)
	print(canSave)


```

### This example loads an image and resizes it using various resizing settings. {#example_28}
``` python
from aspose.imaging import Image, ImageResizeSettings, ResizeType, ImageFilterType,\
	ColorQuantizationMethod
from os.path import join as path_join

directory = "c:\\temp\\"

resizeSettings = ImageResizeSettings()

# Der adaptive Algorithmus, basierend auf gewichteten und gemischten rationalen Funktionen sowie Lanczos‑3‑Interpolation.
resizeSettings.mode = ResizeType.ADAPTIVE_RESAMPLE
# Der kleine rechteckige Filter
resizeSettings.filter_type = ImageFilterType.SMALL_RECTANGULAR
# Die Anzahl der Farben in der Palette.
resizeSettings.entries_count = 256
# Die Farbkodierung wird nicht verwendet
resizeSettings.color_quantization_method = ColorQuantizationMethod.NONE

# Die euklidische Methode.
resizeSettings.ColorCompareMethod = ColorCompareMethod.Euclidian;

with Image.load(path_join(directory, "sample.gif")) as image:
	# Verkleinert das Bild um das 2‑fache mittels adaptiver Neuberechnung.
	image.resize(image.width // 2, image.height // 2, resizeSettings)
	image.save(path_join(directory, "downsample.adaptive.gif"))


```

### This example loads an image and resizes it proportionally using various resizing methods. Only the width is specified, the height is calculated automatically. {#example_29}
``` python
from aspose.imaging import Image, ResizeType
from os.path import join as path_join

directory = "c:\\temp\\"

with Image.load(path_join(directory, "sample.gif")) as image:
	# Vergrößert das Bild um das 2‑fache mittels Nearest‑Neighbour‑Neuberechnung.
	image.resize_width_proportionally(image.width * 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE)
	image.save(path_join(directory, "upsample.nearestneighbour.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# Verkleinert das Bild um das 2‑fache mittels Nearest‑Neighbour‑Neuberechnung.
	image.resize_width_proportionally(image.width // 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE)
	image.save(path_join(directory, "downsample.nearestneighbour.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# Vergrößert das Bild um das 2‑fache mittels bilinearer Neuberechnung.
	image.resize_width_proportionally(image.width * 2, ResizeType.BILINEAR_RESAMPLE)
	image.save(path_join(directory, "upsample.bilinear.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# Verkleinert das Bild um das 2‑fache mittels bilinearer Neuberechnung.
	image.resize_width_proportionally(image.width // 2, ResizeType.BILINEAR_RESAMPLE);
	image.save(path_join(directory, "downsample.bilinear.gif"))


```

### This example loads an image and resizes it proportionally using various resizing methods. Only the height is specified, the width is calculated automatically. {#example_30}
``` python

from aspose.imaging import Image, ResizeType
from os.path import join as path_join

directory = "c:\\temp\\"

with Image.load(path_join(directory, "sample.gif")) as image:
	# Vergrößert das Bild um das 2‑fache mittels Nearest‑Neighbour‑Neuberechnung.
	image.resize_height_proportionally(image.height * 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE)
	image.save(path_join(directory, "upsample.nearestneighbour.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# Verkleinert das Bild um das 2‑fache mittels Nearest‑Neighbour‑Neuberechnung.
	image.resize_height_proportionally(image.height // 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE)
	image.save(path_join(directory, "downsample.nearestneighbour.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# Vergrößert das Bild um das 2‑fache mittels bilinearer Neuberechnung.
	image.resize_height_proportionally(image.height * 2, ResizeType.BILINEAR_RESAMPLE)
	image.save(path_join(directory, "upsample.bilinear.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# Verkleinert das Bild um das 2‑fache mittels bilinearer Neuberechnung.
	image.resize_height_proportionally(image.height // 2, ResizeType.BILINEAR_RESAMPLE)
	image.save(path_join(directory, "downsample.bilinear.gif"))


```

### This example loads an image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically. {#example_31}
``` python

from aspose.imaging import Image, RotateFlipType
from os.path import join as path_join

directory = "c:\\temp\\"

rotateFlipTypes = [RotateFlipType.ROTATE_90_FLIP_NONE, RotateFlipType.ROTATE_90_FLIP_X,
				   RotateFlipType.ROTATE_90_FLIP_XY, RotateFlipType.ROTATE_90_FLIP_Y]

for rotateFlipType in rotateFlipTypes:
	# Drehen, spiegeln und in die Ausgabedatei speichern.
	with Image.Load(path_join(directory, "sample.bmp")) as image:
		image.rotate_flip(rotateFlipType)
		image.save(path_join(directory, f"sample.{rotateFlipType}.bmp"))


```

### The following example loads a BMP image from a file, then saves the image to a PNG file. {#example_32}
``` python
from aspose.imaging import Image
from aspose.imaging.imageoptions import PngOptions
from os.path import join as path_join

directory = r"c:\temp"

with Image.load(path_join(dir, "sample.bmp")) as image:
	# Speichern Sie das gesamte Bild in einer PNG-Datei.
	save_options = PngOptions()
	image.save(path_join(dir, "output.png"), save_options)

```

### The following example loads a BMP image from a file, then saves a rectangular part of the image to a PNG file. {#example_33}
``` python
from aspose.imaging import Image, Rectangle
from aspose.imaging.imageoptions import PngOptions
from os.path import join as path_join

directory = r"c:\temp"

with Image.load(path_join(dir, "sample.bmp")) as image:
	# Speichern Sie die obere Bildhälfte in einer PNG-Datei.
	save_options = PngOptions()
	bounds = Rectangle(0, 0, image.width, image.height // 2)
	image.save(path_join(dir, "output.png"), save_options, bounds)

```

### The following example loads an image from a file, then saves the image to a PNG file stream. {#example_34}
``` python
from aspose.imaging import Image, Rectangle
from aspose.imaging.imageoptions import PngOptions
from os.path import join as path_join

directory = r"c:\temp"

with Image.load(path_join(dir, "sample.bmp")) as image:
	save_options = PngOptions()
	with open(path_join(dir, "output.png"), "w+b") as output_stream:
		# Speichern Sie das gesamte Bild in einen Dateistream.
		image.save(output_stream, save_options)

```

### The following example loads an image from a file, then saves a rectangular part of the image to a PNG file stream. {#example_35}
``` python
from aspose.imaging import Image, Rectangle
from aspose.imaging.imageoptions import PngOptions
from os.path import join as path_join

directory = r"c:\temp"

with Image.load(path_join(dir, "sample.bmp")) as image:
	save_options = PngOptions()
	bounds = Rectangle(0, 0, image.width, image.height // 2)
	with open(path_join(dir, "output.png"), "w+b") as output_stream:
		# Speichern Sie die obere Bildhälfte in einen Dateistream.
		image.save(output_stream, save_options, bounds)


```

### The following example shows how to save an entire BMP image or part of it to a file or stream. {#example_90}
``` python

from os.path import join as path_join
from aspose.pycore import as_of
from aspose.imaging import Image, ColorPaletteHelper
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.extensions import StreamExtensions as strm_ext

directory = "c:\\temp\\"
with Image.load(path_join(directory, "sample.bmp")) as image:
	bmpImage = as_of(image, BmpImage)
		
	# In ein Schwarz-Weiß-Bild konvertieren.
	bmpImage.binarize_otsu()

	# Am selben Ort mit den Standardoptionen speichern.
	image.save()

	saveOptions = BmpOptions()

	# Eine Palette enthält in diesem Fall nur zwei Farben: Schwarz und Weiß.
	saveOptions.palette = ColorPaletteHelper.create_monochrome()

	# Für alle monochromen Bilder (einschließlich Schwarz-Weiß-Bilder) reicht es, 1 Bit pro Pixel zuzuweisen.
	saveOptions.bits_per_pixel = 1

	# An einem anderen Ort mit den angegebenen Optionen speichern.
	image.save(path_join(directory, "sample.bw.palettized.bmp"), saveOptions)

	# Nur den zentralen Teil des Bildes speichern.
	bounds = Rectangle(image.width // 4, image.height // 4, image.width // 2, image.height // 2)
	image.save(path_join(directory, "sample.bw.palettized.part.bmp"), saveOptions, bounds)

	# Speichern Sie das gesamte Bild in einen MemoryStream.
	with strm_ext.create_memory_stream() as stream:
		image.save(stream, saveOptions);
		print("The size of the whole image in bytes:", stream.tell())

	# Speichern Sie den zentralen Teil des Bildes in einen Memory-Stream
	with strm_ext.create_memory_stream() as stream:
		image.save(stream, saveOptions, bounds)
		print("The size of the central part of the image in bytes: ", stream.tell())

#Die Ausgabe könnte folgendermaßen aussehen:
#Die Größe des gesamten Bildes in Bytes: 24062
#Die Größe des zentralen Teils des Bildes in Bytes: 6046

```

### The following example shows how to resize a metafile (WMF and EMF). {#example_182}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.emf import MetaImage
from os.path import join

dir_ = "c:\\temp"
file_names = ["image3.emf", "image4.wmf"]
for file_name in file_names:
	input_file_path = join(dir_, file_name)
	output_file_path = join(dir_, "Downscale_" + file_name)
	with aspycore.as_of(Image.load(input_file_path), MetaImage) as image:
		image.resize(image.width // 4, image.height // 4)
		image.save(output_file_path)


```

### The following example shows how to resize SVG image and save it to PNG. {#example_185}
``` python

from aspose.imaging import PointF, Image
from aspose.imaging.imageoptions import PngOptions
from os import path

dir_ = "c:\\aspose.imaging\\net\\issues\\3549"
file_names = ["Logotype.svg", "sample_car.svg", "rg1024_green_grapes.svg", "MidMarkerFigure.svg", "embeddedFonts.svg"]
scales = [PointF(0.5, 0.5), PointF(1.0, 1.0), PointF(2.0, 2.0), PointF(3.5, 9.2)]
for input_file in file_names:
	for scale in scales:
		output_file = "{0}_{1}_{2}.png".format(input_file, str(scale.x), str(scale.y))
		with Image.load(path.join(dir_, input_file)) as image:
			image.resize(int(image.width * scale.x), int(image.height * scale.y))
			image.save(path.join(dir_, output_file), PngOptions())


```

### Resize image using specific Resize Type. {#example_209}
``` python
from aspose.imaging import Image, ResizeType, ImageResizeSettings, ImageFilterType

with Image.load("Photo.jpg") as image:
	image.resize(640, 480, ResizeType.CATMULL_ROM)
	image.save("ResizedPhoto.jpg")
	image.resize(1024, 768, ResizeType.CUBIC_CONVOLUTION)
	image.save("ResizedPhoto2.jpg")
	resize_settings = ImageResizeSettings()
	resize_settings.mode = ResizeType.CUBIC_BSPLINE
	resize_settings.filter_type = ImageFilterType.SMALL_RECTANGULAR
	image.resize(800, 800, resize_settings)
	image.save("ResizedPhoto3.jpg")


```

### Determine if the palette is used by the image. {#example_221}
``` python

from aspose.imaging import Image

with Image.load("Sample.bmp") as image:
	if image.use_palette:
		print("The palette is used by the image")

```

