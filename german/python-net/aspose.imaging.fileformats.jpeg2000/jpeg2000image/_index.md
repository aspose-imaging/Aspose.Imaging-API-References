---
title: "Jpeg2000Image Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/
---

**Summary:** Efficiently manipulate JPEG2000 (JP2) image files with our API, supporting<br/>            a range of bits per pixel depths and seamless processing of XMP metadata<br/>            containing essential image information. With capabilities for lossless compression,<br/>            ensure optimal image quality while maintaining file integrity, empowering you to<br/>            tailor JP2 images to your exact specifications with ease.

**Module:** [aspose.imaging.fileformats.jpeg2000](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/)

**Full Name:** aspose.imaging.fileformats.jpeg2000.Jpeg2000Image

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Jpeg2000Image(image)](#Jpeg2000Image_image_1) | Instanziieren Sie eine neue [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse mit einem Rasterbild. Dieser <br/>            Konstruktor erleichtert die Erstellung eines JPEG2000-Bildes aus einem vorhandenen Raster-<br/>            Bild und bietet nahtlose Integration und Konvertierung zwischen verschiedenen Bildformaten. |
| [Jpeg2000Image(path)](#Jpeg2000Image_path_2) | Beginnen Sie mit der Arbeit an der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse, indem Sie eine neue <br/>            Instanz mit dem Pfad zu dem Bild, das Sie laden möchten, initialisieren. Dieser Konstruktor ermöglicht einen einfachen <br/>            Zugriff auf JPEG2000-Bilder und vereinfacht den Vorgang des Ladens und Handhabens von Bild-<br/>            dateien. Durch Angabe des Dateipfads können Sie schnell mit der Verarbeitung und <br/>            Manipulation von JPEG2000-Bildern in Ihrer Anwendung beginnen. |
| [Jpeg2000Image(path, bits_per_pixel)](#Jpeg2000Image_path_bits_per_pixel_3) | Starten Sie einfach mit der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse, indem Sie eine neue <br/>            Instanz erstellen, die sowohl den Dateipfad als auch den gewünschten Bits‑pro‑Pixel‑Parameter enthält. Dieser <br/>            Konstruktor ermöglicht eine Feinabstimmung des Bildladevorgangs und sorgt für <br/>            Kompatibilität mit verschiedenen Bildformaten und Qualitätseinstellungen. Mit dieser <br/>            Flexibilität können Sie JPEG2000-Bilder effizient verwalten und manipulieren, entsprechend Ihren <br/>            spezifischen Anforderungen. |
| [Jpeg2000Image(raster_image, bits_per_pixel)](#Jpeg2000Image_raster_image_bits_per_pixel_4) | Initialisieren Sie eine neue [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Instanz mit einem Rasterbild und <br/>            Bits‑pro‑Pixel‑Parametern. Dieser Konstruktor ermöglicht eine präzise Kontrolle über die <br/>            Qualität und Größe des resultierenden JPEG2000-Bildes und ist damit ideal für Szenarien, <br/>            in denen Anpassungen entscheidend sind. |
| [Jpeg2000Image(stream)](#Jpeg2000Image_stream_5) | Initialisieren Sie einfach eine neue Instanz der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse, indem Sie <br/>            ein Stream‑Objekt bereitstellen. Dieser Konstruktor vereinfacht das Laden von <br/>            JPEG2000-Bildern direkt aus Streams und bietet Flexibilität sowie Komfort beim <br/>            Umgang mit Bilddaten aus verschiedenen Quellen. |
| [Jpeg2000Image(stream, bits_per_pixel)](#Jpeg2000Image_stream_bits_per_pixel_6) | Initialisieren Sie eine neue Instanz der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse mit einem Stream zum <br/>            Laden des Bildes sowie Bits‑pro‑Pixel‑Parametern. Dieser Konstruktor bietet <br/>            Flexibilität, indem er Ihnen ermöglicht, sowohl die Bilddatenquelle als auch die gewünschten <br/>            Bits pro Pixel anzugeben, wodurch eine feinere Kontrolle über den Bildladevorgang ermöglicht wird. |
| [Jpeg2000Image(width, height)](#Jpeg2000Image_width_height_7) | Erstellen Sie eine neue Instanz der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse und geben Sie die <br/>            Breiten‑ und Höhenparameter an. Dieser Konstruktor ermöglicht es Ihnen, ein JPEG2000-<br/>            Bild mit spezifischen Abmessungen zu initialisieren, was für Szenarien nützlich ist, in denen Sie <br/>            programmgesteuert ein Bild einer bestimmten Größe erzeugen müssen. |
| [Jpeg2000Image(width, height, bits_count)](#Jpeg2000Image_width_height_bits_count_8) | Erstellen Sie eine neue Instanz der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse mit Parametern für <br/>            Breite, Höhe und Bitanzahl. Dieser Konstruktor ermöglicht die Erstellung von JPEG2000-<br/>            Bildern mit spezifischen Abmessungen und Bit‑Tiefen und bietet Flexibilität für verschiedene <br/>            Bildanforderungen. |
| [Jpeg2000Image(width, height, options)](#Jpeg2000Image_width_height_options_9) | Instanziieren Sie ein neues [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Objekt und geben Sie die Breiten‑, Höhen‑ <br/>            und Bildoptionen‑Parameter an. Dieser Konstruktor ermöglicht die Erstellung von JPEG2000-<br/>            Bildern mit spezifischen Abmessungen und zusätzlichen Optionen und bietet Flexibilität bei der <br/>            Bildgenerierung. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die automatische Anpassung der Palette erfolgt. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Liest oder setzt einen Wert für die Hintergrundfarbe. |
| bits_per_pixel | int | r | Diese Eigenschaft gibt die Farbtiefe des Bildes zurück, gemessen in Bits pro Pixel (bpp). Sie <br/>            gibt an, wie viel Farbinformation in jedem Pixel des Bildes gespeichert ist. <br/>            Das Verständnis der Bildtiefe ist entscheidend, um die Farbtreue und <br/>            Qualität des Bildes zu bestimmen. Mit diesen Informationen können Benutzer das Detail‑<br/>            niveau und die Farbreichtum des Bildes einschätzen. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Liest die Objektgrenzen. |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| codec | [Jpeg2000Codec](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000codec/) | r | Diese Eigenschaft ruft den mit dem Bild verbundenen JPEG2000‑Codec ab. Der JPEG2000‑<br/>            Codec ist für das Kodieren und Dekodieren der Bilddaten im JPEG2000‑Format verantwortlich und bietet eine effiziente Kompression bei gleichzeitig hoher Bildqualität. <br/>            Der Zugriff auf diesen Codec kann nützlich sein, um fortgeschrittene Bildverarbeitungs‑<br/>            Vorgänge durchzuführen oder die Kompressionseinstellungen des Bildes an spezifische Anforderungen anzupassen. |
| Kommentare | string[] | r/w | Diese Eigenschaft ermöglicht das Abrufen oder Aktualisieren der mit dem <br/>            Bild verbundenen Kommentare. Kommentare liefern zusätzliche Informationen zum Bildinhalt, wie <br/>            Anmerkungen, Beschreibungen oder Metadaten. Das Ändern dieser Kommentare kann nützlich sein, um <br/>            Bilder zu organisieren und zu kategorisieren sowie wichtige Details an Betrachter oder Benutzer zu übermitteln. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Liest den [Image](/imaging/python-net/aspose.imaging/image/) Container. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Liest den Datenstrom des Objekts. |
| freigegeben | bool | r | Liest einen Wert, der angibt, ob diese Instanz freigegeben ist. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Liest oder setzt die Exif‑Instanz. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Rufen Sie das Format der Bilddatei ab. Diese Eigenschaft liefert Informationen über das <br/>            Dateiformat des Bildes. Verwenden Sie diese Eigenschaft, um das Format der <br/>            Bilddatei programmgesteuert zu bestimmen, was eine angemessene Handhabung und Verarbeitung basierend <br/>            auf dem Dateiformat ermöglicht. |
| has_alpha | bool | r | Gibt einen Wert zurück, der angibt, ob diese Instanz Alpha enthält. |
| has_background_color | bool | r/w | Liest oder setzt einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| has_transparent_color | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) Instanz eine transparente Farbe hat. |
| height | int | r | Diese Eigenschaft gibt die Höhe des Bildes in Pixeln zurück. Sie liefert wesentliche <br/>            Informationen zum vertikalen Umfang des Bildes und unterstützt verschiedene <br/>            Bildbearbeitungsaufgaben wie Skalieren, Zuschneiden und Rendern. Durch den Zugriff auf diese <br/>            Eigenschaft können Benutzer die vertikale Größe des Bildes ermitteln, was ein präzises <br/>            Layout und die Anzeige in Anwendungen ermöglicht. |
| horizontal_resolution | float | r/w | Diese Eigenschaft ermöglicht das Abrufen oder Ändern der horizontalen Auflösung des<br/>            [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/), gemessen in Pixel pro Zoll (PPI). Die Anpassung dieser <br/>            Auflösung kann die Größe und Qualität des Bildes beim Drucken oder Anzeigen beeinflussen. <br/>            Durch Festlegen der horizontalen Auflösung können Benutzer das Bild für bestimmte <br/>            Ausgabegeräte oder Anwendungen optimieren und so die bestmöglichen visuellen Ergebnisse erzielen. |
| image_opacity | float | r | Liest die Opazität dieses Bildes. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Liest oder setzt den Interrupt-Monitor. |
| is_cached | bool | r | Liest einen Wert, der angibt, ob Bilddaten derzeit zwischengespeichert sind. |
| is_raw_data_available | bool | r | Liest einen Wert, der angibt, ob das Laden von Rohdaten unterstützt wird. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Gibt die Metadaten des Bildes zurück. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Liest oder setzt die Farbpalette. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| premultiply_components | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die Bildkomponenten vormultipliziert werden müssen. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | Liest oder setzt den benutzerdefinierten Farbkonverter |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Diese Eigenschaft ruft das Rohdatenformat des Bildes ab. Sie liefert Informationen <br/>            darüber, wie die Pixeldaten im Speicher abgelegt werden. Verwenden Sie diese Eigenschaft, um das <br/>            zugrunde liegende Datenformat des Bildes zu verstehen, was für verschiedene Bild‑<br/>            verarbeitungsoperationen wie Farbkonvertierung, Kompression oder Dekompression entscheidend sein kann. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | Liest die aktuellen Rohdateneinstellungen. Hinweis: Beim Verwenden dieser Einstellungen werden die Daten ohne Konvertierung geladen. |
| raw_fallback_index | int | r/w | Liest oder setzt den Rückfallindex, der verwendet wird, wenn der Palettenindex außerhalb des gültigen Bereichs liegt |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | Liest oder setzt den indizierten Farbkonverter |
| raw_line_size | int | r | Diese Eigenschaft gibt die Größe einer einzelnen Zeile von Rohbilddaten in Bytes zurück. Sie <br/>            gibt an, wie viel Speicher von einer einzelnen Pixelreihe im Rohdatenformat des Bildes belegt wird. Das Verständnis der Zeilengröße ist wichtig für Aufgaben wie <br/>            Speicherzuweisung, Datenmanipulation und Bildverarbeitungsalgorithmen, die auf einzelnen Bildzeilen <br/>            operieren. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Liest die Objektgröße. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Liest die transparente Bildfarbe. |
| update_xmp_data | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die XMP-Metadaten aktualisiert werden sollen. |
| use_palette | bool | r | Liest einen Wert, der angibt, ob die Bildpalette verwendet wird. |
| use_raw_data | bool | r/w | Liest oder setzt einen Wert, der angibt, ob das Laden von Rohdaten verwendet werden soll, wenn das Laden von Rohdaten verfügbar ist. |
| vertical_resolution | float | r/w | Diese Eigenschaft bietet Zugriff auf die vertikale Auflösung des<br/>            [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/), gemessen in Pixel pro Zoll (PPI). Die Änderung dieser <br/>            Auflösung kann die Qualität und Größe des Bildes beim Drucken oder Anzeigen beeinflussen. <br/>            Durch Anpassen der vertikalen Auflösung können Benutzer das Bild für verschiedene <br/>            Ausgabegeräte oder Anwendungen optimieren und so eine optimale visuelle Darstellung gewährleisten. |
| width | int | r | Diese Eigenschaft gibt die Breite des Bildes in Pixeln zurück. Sie liefert eine grundlegende <br/>            Information über die Bildabmessungen, die für verschiedene Bild‑<br/>            verarbeitungsaufgaben wie Skalieren, Zuschneiden und Rendern entscheidend ist. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Liest oder setzt XMP-Daten. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_1) | Anpassung der Helligkeit für das Bild. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_2) | Bildkontrastierung |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_3) | Gamma-Korrektur eines Bildes. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_4) | Gamma-Korrektur eines Bildes. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_5) | Berechnet den prozentualen Ähnlichkeitsgrad zwischen den extrahierten Daten und dem ursprünglichen Passwort. |
| auto_brightness_contrast() | Führt eine automatische adaptive Helligkeits- und Kontrastnormalisierung für das gesamte Bild durch. |
| auto_rotate() | Dreht das Bild automatisch basierend auf den aus den Exif-<br/>            Metadaten extrahierten Orientierungsdaten. Diese Methode stellt sicher, dass Bilder in der korrekten Ausrichtung angezeigt werden, <br/>            verbessert das Benutzererlebnis und eliminiert die Notwendigkeit manueller Anpassungen. Durch <br/>            Analyse der Exif-Informationen wird das Bild entsprechend gedreht, was ein nahtloses <br/>            Anzeigeerlebnis über verschiedene Plattformen und Geräte hinweg ermöglicht. Dieser automatisierte Rotations<br/>            Prozess vereinfacht die Bildverarbeitung und erhöht die Gesamtbenutzerfreundlichkeit, insbesondere bei <br/>            großen Bildmengen mit unterschiedlichen Ausrichtungen. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_6) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild-Schwellenwertbestimmung |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_7) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild-Schwellenwertbestimmung |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_8) | Binarisierung eines Bildes mit vordefiniertem Schwellenwert |
| binarize_otsu() | Binarisierung eines Bildes mit Otsu-Schwellenwertbestimmung |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_9) | Mischt diese Bildinstanz mit dem _overlay_-Bild. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_10) | Mischt diese Bildinstanz mit dem _overlay_-Bild. |
| cache_data() | Zwischenspeichert die Daten und stellt sicher, dass keine zusätzlichen Datenladungen vom zugrunde liegenden [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/) durchgeführt werden. |
| [can_load(file_path)](#can_load_file_path_11) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_12) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann und optional die angegebenen Öffnungsoptionen verwendet. |
| [can_load(stream)](#can_load_stream_13) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann. |
| [can_load(stream, load_options)](#can_load_stream_load_options_14) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann und optional die angegebenen _loadOptions_ verwendet. |
| [can_load_stream(stream)](#can_load_stream_stream_15) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_16) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann und optional die angegebenen _loadOptions_ verwendet. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_17) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann und optional die angegebenen Öffnungsoptionen verwendet. |
| [can_save(options)](#can_save_options_18) | Bestimmt, ob das Bild im angegebenen Dateiformat, das durch die übergebenen Speicheroptionen repräsentiert wird, gespeichert werden kann. |
| [create(files)](#create_files_19) | Erstellt das mehrseitige Bild, das die angegebenen Dateien enthält. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_20) | Erstellt das mehrseitige Bild, das die angegebenen Dateien enthält. |
| [create(image_options, width, height)](#create_image_options_width_height_21) | Erstellt ein neues Bild mit den angegebenen Erstellungsoptionen. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_22) | Erstellt eine [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) Instanz aus dem bereitgestellten Pixelarray.<br/>            <br/>            Validiert, dass die angegebene Breite und Höhe den Abmessungen der Pixeldaten entsprechen.<br/>            Diese Methode kann nur verwendet werden, wenn die Bibliothek im lizenzierten Modus ist. |
| [create(images)](#create_images_23) | Erstellt ein neues Bild, das die angegebenen Bilder als Seiten verwendet |
| [create(images, dispose_images)](#create_images_dispose_images_24) | Erstellt ein neues Bild, wobei die angegebenen Bilder als Seiten verwendet werden. |
| [create(multipage_create_options)](#create_multipage_create_options_25) | Erstellt die angegebenen Mehrseiten‑Erstellungsoptionen. |
| [create_from_file_with_bpp(path, bits_per_pixel)](#create_from_file_with_bpp_path_bits_per_pixel_26) | Initialisiert eine neue Instanz der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse. |
| [create_from_files(files)](#create_from_files_files_27) | Erstellt das Mehrseiten‑Bild, das die angegebenen Dateien als Lazy‑Loading‑Seiten enthält. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_28) | Erstellt das Mehrseiten‑Bild, das die angegebenen Dateien als Lazy‑Loading‑Seiten enthält. |
| [create_from_image(image)](#create_from_image_image_29) | Initialisiert eine neue Instanz der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse. |
| [create_from_image_with_bpp(raster_image, bits_per_pixel)](#create_from_image_with_bpp_raster_image_bits_per_pixel_30) | Initialisiert eine neue Instanz der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse. |
| [create_from_images(images)](#create_from_images_images_31) | Erstellt ein neues Bild, das die angegebenen Bilder als Seiten verwendet |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_32) | Erstellt ein neues Bild, wobei die angegebenen Bilder als Seiten verwendet werden. |
| [create_from_stream(stream)](#create_from_stream_stream_33) | Initialisiert eine neue Instanz der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse. |
| [create_from_stream_with_bpp(stream, bits_per_pixel)](#create_from_stream_with_bpp_stream_bits_per_pixel_34) | Initialisiert eine neue Instanz der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse. |
| [create_with_width_height(width, height)](#create_with_width_height_width_height_35) | Initialisiert eine neue Instanz der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse. |
| [create_with_width_height_bitscount(width, height, bits_count)](#create_with_width_height_bitscount_width_height_bits_count_36) | Initialisiert eine neue Instanz der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse. |
| [create_with_width_height_options(width, height, options)](#create_with_width_height_options_width_height_options_37) | Initialisiert eine neue Instanz der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_38) | Bild mit Verschiebungen zuschneiden. |
| [crop(rectangle)](#crop_rectangle_39) | Zuschneiden des Bildes. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_40) | Führt Dithering auf dem aktuellen Bild aus. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_41) | Führt Dithering auf dem aktuellen Bild aus. |
| [embed_digital_signature(password)](#embed_digital_signature_password_42) | Digitales Siegel basierend auf dem bereitgestellten Passwort in das Bild einbetten mittels Steganographie. |
| [filter(rectangle, options)](#filter_rectangle_options_43) | Filtert das angegebene Rechteck. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_44) | Liefert ein 32‑Bit‑ARGB‑Pixel‑Bild. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_45) | Liefert das Standard‑32‑Bit‑ARGB‑Pixel‑Array. |
| [get_default_options(args)](#get_default_options_args_46) | Liefert die Standardoptionen. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_47) | Liefert das Standard‑Pixel‑Array mittels teilweisem Pixel‑Lader. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_48) | Liefert das Standard‑Rohdaten‑Array mittels teilweisem Pixel‑Lader. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_49) | Liefert das Standard‑Rohdaten‑Array. |
| [get_file_format(file_path)](#get_file_format_file_path_50) | Liefert das Dateiformat. |
| [get_file_format(stream)](#get_file_format_stream_51) | Liefert das Dateiformat. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_52) | Liefert das Dateiformat. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_53) | Liefert das Rechteck, das zum aktuellen Bild passt. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_54) | Liefert das Rechteck, das zum aktuellen Bild passt. |
| [get_modify_date(use_default)](#get_modify_date_use_default_55) | Liefert Datum und Uhrzeit, zu der das Ressourcen‑Bild zuletzt geändert wurde. |
| [get_original_options()](#get_original_options__56) | Rufen Sie die Bildoptionen basierend auf den ursprünglichen Dateieinstellungen ab. Diese Methode ist <br/>            nützlich, um die Bit‑Tiefe und andere Parameter des Originalbildes beizubehalten, wodurch Konsistenz gewährleistet und die Integrität der Bilddaten erhalten bleibt. <br/>            Der Zugriff auf diese Optionen erleichtert die nahtlose Handhabung und Verarbeitung des Bildes, <br/>            während seine ursprünglichen Merkmale erhalten bleiben.<br/>            Beispiel: Wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es anschließend mit der<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) Methode speichern, wird ein PNG‑Ausgabebild mit 8 Bit pro Pixel erzeugt.<br/>            Um dies zu vermeiden und ein PNG‑Bild mit 1‑Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und sie<br/>            an die [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) Methode als zweiten Parameter zu übergeben. |
| [get_pixel(x, y)](#get_pixel_x_y_57) | Liefert ein Bild‑Pixel. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_58) | Liefert eine proportionale Höhe. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_59) | Liefert eine proportionale Breite. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_60) | Konvertiert zu aps. |
| [get_skew_angle()](#get_skew_angle__61) | Liefert den Schrägungswinkel.<br/>            Diese Methode ist auf gescannte Textdokumente anwendbar, um den Schrägungswinkel beim Scannen zu bestimmen. |
| grayscale() | Transformation eines Bildes in seine Graustufen-Darstellung |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_62) | Führt eine schnelle Prüfung durch, um festzustellen, ob das Bild digital signiert ist, wobei das bereitgestellte Passwort und der Schwellenwert verwendet werden. |
| [load(file_path)](#load_file_path_63) | Lädt ein neues Bild vom angegebenen Dateipfad oder URL.<br/>            Wenn _filePath_ ein Dateipfad ist, öffnet die Methode einfach die Datei.<br/>            Wenn _filePath_ eine URL ist, lädt die Methode die Datei herunter, speichert sie temporär und öffnet sie. |
| [load(file_path, load_options)](#load_file_path_load_options_64) | Lädt ein neues Bild vom angegebenen Dateipfad oder URL.<br/>            Wenn _filePath_ ein Dateipfad ist, öffnet die Methode einfach die Datei.<br/>            Wenn _filePath_ eine URL ist, lädt die Methode die Datei herunter, speichert sie temporär und öffnet sie. |
| [load(stream)](#load_stream_65) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load(stream, load_options)](#load_stream_load_options_66) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_67) | Lädt 32‑Bit‑ARGB‑Pixel. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_68) | Lädt 64‑Bit‑ARGB‑Pixel. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_69) | Lädt Pixel im CMYK‑Format. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_70) | Lädt Pixel im CMYK‑Format.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere Methode [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_71) | Lädt 32‑Bit‑ARGB‑Pixel teilweise (nach Blöcken). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_72) | Lädt 64‑Bit‑ARGB‑Pixel teilweise nach Paketen. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_73) | Lädt Pixel teilweise nach Paketen. |
| [load_pixels(rectangle)](#load_pixels_rectangle_74) | Lädt Pixel. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_75) | Lädt Rohdaten. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_76) | Lädt Rohdaten. |
| [load_stream(stream)](#load_stream_stream_77) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_78) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_79) | Lädt ein neues Bild vom angegebenen Dateipfad oder URL.<br/>            Wenn _filePath_ ein Dateipfad ist, öffnet die Methode einfach die Datei.<br/>            Wenn _filePath_ eine URL ist, lädt die Methode die Datei herunter, speichert sie temporär und öffnet sie. |
| normalize_angle() | Normalisiert den Winkel.<br/>            Diese Methode ist auf gescannte Textdokumente anwendbar, um die schiefe Aufnahme zu korrigieren.<br/>            Diese Methode verwendet die Methoden [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) und [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_80) | Normalisiert den Winkel.<br/>            Diese Methode ist auf gescannte Textdokumente anwendbar, um die verzerrte Aufnahme zu korrigieren.<br/>            Diese Methode verwendet die Methoden [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) und [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/). |
| normalize_histogram() | Normalisiert das Bildhistogramm — passt die Pixelwerte an, um den gesamten verfügbaren Bereich zu nutzen. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_81) | Liest die gesamte Scanzeile anhand des angegebenen Scanzeilen‑Index. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_82) | Liest die gesamte Scanzeile anhand des angegebenen Scanzeilen‑Index. |
| remove_metadata() | Entfernt die Metadaten dieser Bildinstanz, indem der Wert von [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) auf **None** gesetzt wird. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_83) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_84) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_85) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_86) | Ersetzt alle nicht-transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.<br/>            Hinweis: Wenn Sie es bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_87) | Ersetzt alle nicht-transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.<br/>            Hinweis: Wenn Sie es bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| [resize(new_width, new_height)](#resize_new_width_new_height_88) | Skaliert das Bild. Der Standardwert [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_89) | Skaliert das Bild. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_90) | Skaliert das Bild. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_91) | Skaliert das Bild. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_92) | Skaliert das Bild. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_93) | Skaliert die Höhe proportional. Der Standard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_94) | Skaliert die Höhe proportional. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_95) | Skaliert die Höhe proportional. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_96) | Skaliert die Höhe proportional. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_97) | Skaliert die Breite proportional. Der Standard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_98) | Skaliert die Breite proportional. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_99) | Skaliert die Breite proportional. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_100) | Skaliert die Breite proportional. |
| [rotate(angle)](#rotate_angle_101) | Bild um das Zentrum drehen. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_102) | Bild um das Zentrum drehen. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_103) | Dreht, spiegelt oder dreht und spiegelt das Bild. |
| save() | Speichert die Bilddaten in den zugrunde liegenden Stream. |
| [save(file_path)](#save_file_path_104) | Speichert das Bild am angegebenen Dateipfad. |
| [save(file_path, options)](#save_file_path_options_105) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_106) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(file_path, over_write)](#save_file_path_over_write_107) | Speichert die Daten des Objekts am angegebenen Speicherort. |
| [save(stream)](#save_stream_108) | Speichert die Daten des Objekts in den angegebenen Stream. |
| [save(stream, options_base)](#save_stream_options_base_109) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_110) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_111) | Speichert die 32‑Bit‑ARGB‑Pixel. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_112) | Speichert die Pixel. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_113) | Speichert die Pixel.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) Methode. |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_114) | Speichert Pixel (formatspezifische Methode). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_115) | Speichert die Rohdaten. |
| [save_to_stream(stream)](#save_to_stream_stream_116) | Speichert die Daten des Objekts in den angegebenen Stream. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_117) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_118) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_119) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_120) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_121) | Setzt ein 32‑Bit‑ARGB‑Pixel des Bildes für die angegebene Position. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_122) | Setzt die Bildpalette. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_123) | Setzt ein Bildpixel für die angegebene Position. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_124) | Setzt die Auflösung für dieses [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_125) | Versucht, eine _metadata_-Instanz zu setzen, falls diese [Image](/imaging/python-net/aspose.imaging/image/)‑Instanz unterstützt und eine [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)‑Instanz implementiert. |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_126) | Schreibt die gesamte Scanzeile in den angegebenen Scanzeilen‑Index. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_127) | Schreibt die gesamte Scanzeile in den angegebenen Scanzeilen‑Index. |


### Constructor: Jpeg2000Image(image) {#Jpeg2000Image_image_1}


```
 Jpeg2000Image(image) 
```

Instanziieren Sie eine neue [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse mit einem Rasterbild. Dieser <br/>            Konstruktor erleichtert die Erstellung eines JPEG2000-Bildes aus einem vorhandenen Raster-<br/>            Bild und bietet nahtlose Integration und Konvertierung zwischen verschiedenen Bildformaten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Bild. |

### Constructor: Jpeg2000Image(path) {#Jpeg2000Image_path_2}


```
 Jpeg2000Image(path) 
```

Beginnen Sie mit der Arbeit an der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse, indem Sie eine neue <br/>            Instanz mit dem Pfad zu dem Bild, das Sie laden möchten, initialisieren. Dieser Konstruktor ermöglicht einen einfachen <br/>            Zugriff auf JPEG2000-Bilder und vereinfacht den Vorgang des Ladens und Handhabens von Bild-<br/>            dateien. Durch Angabe des Dateipfads können Sie schnell mit der Verarbeitung und <br/>            Manipulation von JPEG2000-Bildern in Ihrer Anwendung beginnen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Pfad | string | Der Pfad, von dem das Bild geladen und mit dem Pixel‑ und Palettendaten initialisiert werden soll. |


**See also:**

**[Example # 1](#example_158)**: This example shows how to load a JPEG2000 image from a file and save it to PNG.


### Constructor: Jpeg2000Image(path, bits_per_pixel) {#Jpeg2000Image_path_bits_per_pixel_3}


```
 Jpeg2000Image(path, bits_per_pixel) 
```

Starten Sie einfach mit der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse, indem Sie eine neue <br/>            Instanz erstellen, die sowohl den Dateipfad als auch den gewünschten Bits‑pro‑Pixel‑Parameter enthält. Dieser <br/>            Konstruktor ermöglicht eine Feinabstimmung des Bildladevorgangs und sorgt für <br/>            Kompatibilität mit verschiedenen Bildformaten und Qualitätseinstellungen. Mit dieser <br/>            Flexibilität können Sie JPEG2000-Bilder effizient verwalten und manipulieren, entsprechend Ihren <br/>            spezifischen Anforderungen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Pfad | string | Der Pfad, von dem das Bild geladen und mit dem Pixel‑ und Palettendaten initialisiert werden soll. |
| bits_per_pixel | int | Die Bits pro Pixel. |

### Constructor: Jpeg2000Image(raster_image, bits_per_pixel) {#Jpeg2000Image_raster_image_bits_per_pixel_4}


```
 Jpeg2000Image(raster_image, bits_per_pixel) 
```

Initialisieren Sie eine neue [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Instanz mit einem Rasterbild und <br/>            Bits‑pro‑Pixel‑Parametern. Dieser Konstruktor ermöglicht eine präzise Kontrolle über die <br/>            Qualität und Größe des resultierenden JPEG2000-Bildes und ist damit ideal für Szenarien, <br/>            in denen Anpassungen entscheidend sind.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Bild, mit dem Pixel‑ und Palettendaten initialisiert werden sollen. |
| bits_per_pixel | int | Die Bits pro Pixel. |

### Constructor: Jpeg2000Image(stream) {#Jpeg2000Image_stream_5}


```
 Jpeg2000Image(stream) 
```

Initialisieren Sie einfach eine neue Instanz der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse, indem Sie <br/>            ein Stream‑Objekt bereitstellen. Dieser Konstruktor vereinfacht das Laden von <br/>            JPEG2000-Bildern direkt aus Streams und bietet Flexibilität sowie Komfort beim <br/>            Umgang mit Bilddaten aus verschiedenen Quellen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, von dem das Bild geladen und mit dem Pixel‑ und Palettendaten initialisiert werden soll. |


**See also:**

**[Example # 1](#example_159)**: This example shows how to load a JPEG2000 image from a file stream and save i...


### Constructor: Jpeg2000Image(stream, bits_per_pixel) {#Jpeg2000Image_stream_bits_per_pixel_6}


```
 Jpeg2000Image(stream, bits_per_pixel) 
```

Initialisieren Sie eine neue Instanz der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse mit einem Stream zum <br/>            Laden des Bildes sowie Bits‑pro‑Pixel‑Parametern. Dieser Konstruktor bietet <br/>            Flexibilität, indem er Ihnen ermöglicht, sowohl die Bilddatenquelle als auch die gewünschten <br/>            Bits pro Pixel anzugeben, wodurch eine feinere Kontrolle über den Bildladevorgang ermöglicht wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, von dem das Bild geladen und mit dem Pixel‑ und Palettendaten initialisiert werden soll. |
| bits_per_pixel | int | Die Bits pro Pixel. |

### Constructor: Jpeg2000Image(width, height) {#Jpeg2000Image_width_height_7}


```
 Jpeg2000Image(width, height) 
```

Erstellen Sie eine neue Instanz der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse und geben Sie die <br/>            Breiten‑ und Höhenparameter an. Dieser Konstruktor ermöglicht es Ihnen, ein JPEG2000-<br/>            Bild mit spezifischen Abmessungen zu initialisieren, was für Szenarien nützlich ist, in denen Sie <br/>            programmgesteuert ein Bild einer bestimmten Größe erzeugen müssen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | int | Die Bildbreite |
| height | int | Die Bildhöhe |


**See also:**

**[Example # 1](#example_160)**: This example shows how to create a JPEG2000 image and save it to a file.


### Constructor: Jpeg2000Image(width, height, bits_count) {#Jpeg2000Image_width_height_bits_count_8}


```
 Jpeg2000Image(width, height, bits_count) 
```

Erstellen Sie eine neue Instanz der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse mit Parametern für <br/>            Breite, Höhe und Bitanzahl. Dieser Konstruktor ermöglicht die Erstellung von JPEG2000-<br/>            Bildern mit spezifischen Abmessungen und Bit‑Tiefen und bietet Flexibilität für verschiedene <br/>            Bildanforderungen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | int | Die Bildbreite |
| height | int | Die Bildhöhe |
| bits_count | int | Die Bitanzahl. |

### Constructor: Jpeg2000Image(width, height, options) {#Jpeg2000Image_width_height_options_9}


```
 Jpeg2000Image(width, height, options) 
```

Instanziieren Sie ein neues [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Objekt und geben Sie die Breiten‑, Höhen‑ <br/>            und Bildoptionen‑Parameter an. Dieser Konstruktor ermöglicht die Erstellung von JPEG2000-<br/>            Bildern mit spezifischen Abmessungen und zusätzlichen Optionen und bietet Flexibilität bei der <br/>            Bildgenerierung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | int | Die Bildbreite |
| height | int | Die Bildhöhe |
| options | [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/) | Die Optionen. |


**See also:**

**[Example # 1](#example_161)**: This example shows how to create a JPEG2000 image with the desired options an...

**[Example # 2](#example_163)**: This example shows how to create a PNG image and save it to JPEG2000 with the...


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_1}


```
 adjust_brightness(brightness) 
```

Anpassung der Helligkeit für das Bild.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Helligkeit | int | Helligkeitswert. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_2}


```
 adjust_contrast(contrast) 
```

Bildkontrastierung

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Kontrast | float | Kontrastwert (im Bereich [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_3}


```
 adjust_gamma(gamma) 
```

Gamma-Korrektur eines Bildes.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Gamma | float | Gamma‑Koeffizient für die Rot‑, Grün‑ und Blaukanäle |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_4}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Gamma-Korrektur eines Bildes.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| gamma_red | float | Gamma‑Koeffizient für den Rotkanal |
| gamma_green | float | Gamma‑Koeffizient für den Grünkanal |
| gamma_blue | float | Gamma für den Blaukanal-Koeffizienten |

### Method: analyze_percentage_digital_signature(password) {#analyze_percentage_digital_signature_password_5}


```
 analyze_percentage_digital_signature(password) 
```

Berechnet den prozentualen Ähnlichkeitsgrad zwischen den extrahierten Daten und dem ursprünglichen Passwort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Passwort | string | Das Passwort, das zum Extrahieren der eingebetteten Daten verwendet wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der prozentuale Ähnlichkeitswert. |


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_6}


```
 binarize_bradley(brightness_difference) 
```

Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild-Schwellenwertbestimmung

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brightness_difference | float | Der Helligkeitsunterschied zwischen dem Pixel und dem Durchschnitt eines s × s-Fensters von Pixeln, das um dieses Pixel zentriert ist. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_7}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild-Schwellenwertbestimmung

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brightness_difference | float | Der Helligkeitsunterschied zwischen dem Pixel und dem Durchschnitt eines s × s-Fensters von Pixeln, das um dieses Pixel zentriert ist. |
| window_size | int | Die Größe des s x s Fensters von Pixeln, das um dieses Pixel zentriert ist. |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_8}


```
 binarize_fixed(threshold) 
```

Binarisierung eines Bildes mit vordefiniertem Schwellenwert

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Schwellenwert | System.Byte | Schwellenwert. Wenn der entsprechende Grauwert eines Pixels größer als der Schwellenwert ist, wird ihm der Wert 255 zugewiesen, sonst 0. |

### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_9}


```
 blend(origin, overlay, overlay_alpha) 
```

Mischt diese Bildinstanz mit dem _overlay_-Bild.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Der Ursprung der Hintergrundbildüberblendung. |
| overlay | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Overlay-Bild. |
| overlay_alpha | System.Byte | Der Overlay‑Alpha. |

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_10}


```
 blend(origin, overlay, overlay_area, overlay_alpha) 
```

Mischt diese Bildinstanz mit dem _overlay_-Bild.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Der Ursprung der Hintergrundbildüberblendung. |
| overlay | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Overlay-Bild. |
| overlay_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Overlay‑Bereich. |
| overlay_alpha | System.Byte | Der Overlay‑Alpha. |

### Method: can_load(file_path)  [static] {#can_load_file_path_11}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_12}


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


### Method: can_load(stream)  [static] {#can_load_stream_13}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_14}


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


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_15}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_16}


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


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_17}


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


### Method: can_save(options) {#can_save_options_18}


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


### Method: create(files)  [static] {#create_files_19}


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


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_20}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_21}


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


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_22}


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


### Method: create(images)  [static] {#create_images_23}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_24}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_25}


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


### Method: create_from_file_with_bpp(path, bits_per_pixel)  [static] {#create_from_file_with_bpp_path_bits_per_pixel_26}


```
 create_from_file_with_bpp(path, bits_per_pixel) 
```

Initialisiert eine neue Instanz der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Pfad | string | Der Pfad, von dem das Bild geladen und mit dem Pixel‑ und Palettendaten initialisiert werden soll. |
| bits_per_pixel | int | Die Bits pro Pixel. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) |  |


### Method: create_from_files(files)  [static] {#create_from_files_files_27}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_28}


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


### Method: create_from_image(image)  [static] {#create_from_image_image_29}


```
 create_from_image(image) 
```

Initialisiert eine neue Instanz der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Bild. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) |  |


### Method: create_from_image_with_bpp(raster_image, bits_per_pixel)  [static] {#create_from_image_with_bpp_raster_image_bits_per_pixel_30}


```
 create_from_image_with_bpp(raster_image, bits_per_pixel) 
```

Initialisiert eine neue Instanz der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Bild, mit dem Pixel‑ und Palettendaten initialisiert werden sollen. |
| bits_per_pixel | int | Die Bits pro Pixel. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) |  |


### Method: create_from_images(images)  [static] {#create_from_images_images_31}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_32}


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


### Method: create_from_stream(stream)  [static] {#create_from_stream_stream_33}


```
 create_from_stream(stream) 
```

Initialisiert eine neue Instanz der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, von dem das Bild geladen und mit dem Pixel‑ und Palettendaten initialisiert werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) |  |


### Method: create_from_stream_with_bpp(stream, bits_per_pixel)  [static] {#create_from_stream_with_bpp_stream_bits_per_pixel_34}


```
 create_from_stream_with_bpp(stream, bits_per_pixel) 
```

Initialisiert eine neue Instanz der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, von dem das Bild geladen und mit dem Pixel‑ und Palettendaten initialisiert werden soll. |
| bits_per_pixel | int | Die Bits pro Pixel. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) |  |


### Method: create_with_width_height(width, height)  [static] {#create_with_width_height_width_height_35}


```
 create_with_width_height(width, height) 
```

Initialisiert eine neue Instanz der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | int | Die Bildbreite |
| height | int | Die Bildhöhe |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) |  |


### Method: create_with_width_height_bitscount(width, height, bits_count)  [static] {#create_with_width_height_bitscount_width_height_bits_count_36}


```
 create_with_width_height_bitscount(width, height, bits_count) 
```

Initialisiert eine neue Instanz der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | int | Die Bildbreite |
| height | int | Die Bildhöhe |
| bits_count | int | Die Bitanzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) |  |


### Method: create_with_width_height_options(width, height, options)  [static] {#create_with_width_height_options_width_height_options_37}


```
 create_with_width_height_options(width, height, options) 
```

Initialisiert eine neue Instanz der [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | int | Die Bildbreite |
| height | int | Die Bildhöhe |
| options | [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/) | Die Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_38}


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

### Method: crop(rectangle) {#crop_rectangle_39}


```
 crop(rectangle) 
```

Zuschneiden des Bildes.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_40}


```
 dither(dithering_method, bits_count) 
```

Führt Dithering auf dem aktuellen Bild aus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Die Dithering-Methode. |
| bits_count | int | Die endgültige Bitanzahl für das Dithern. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_41}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Führt Dithering auf dem aktuellen Bild aus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Die Dithering-Methode. |
| bits_count | int | Die endgültige Bitanzahl für das Dithern. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die benutzerdefinierte Palette für das Dithern. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_42}


```
 embed_digital_signature(password) 
```

Digitales Siegel basierend auf dem bereitgestellten Passwort in das Bild einbetten mittels Steganographie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Passwort | string | Das Passwort, das zum Erzeugen digitaler Signaturdaten verwendet wird |

### Method: filter(rectangle, options) {#filter_rectangle_options_43}


```
 filter(rectangle, options) 
```

Filtert das angegebene Rechteck.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Die Optionen. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_44}


```
 get_argb_32_pixel(x, y) 
```

Liefert ein 32‑Bit‑ARGB‑Pixel‑Bild.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Position des Pixels. |
| y | int | Die y-Position des Pixels. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Das 32‑Bit‑ARGB‑Pixel für die angegebene Position. |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_45}


```
 get_default_argb_32_pixels(rectangle) 
```

Liefert das Standard‑32‑Bit‑ARGB‑Pixel‑Array.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, für das die Pixel abgerufen werden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Das Standard‑Pixel‑Array. |


### Method: get_default_options(args) {#get_default_options_args_46}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_47}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Liefert das Standard‑Pixel‑Array mittels teilweisem Pixel‑Lader.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, für das die Pixel abgerufen werden. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Der partielle Pixel‑Lader. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_48}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

Liefert das Standard‑Rohdaten‑Array mittels teilweisem Pixel‑Lader.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, für das die Pixel abgerufen werden. |
| partial_raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Der partielle Rohdaten‑Lader. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Die Rohdaten‑Einstellungen. |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_49}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

Liefert das Standard‑Rohdaten‑Array.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, für das Rohdaten abgerufen werden. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Die Rohdaten‑Einstellungen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Byte | Das Standard‑Rohdaten‑Array. |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_50}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_51}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_52}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_53}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_54}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_55}


```
 get_modify_date(use_default) 
```

Liefert Datum und Uhrzeit, zu der das Ressourcen‑Bild zuletzt geändert wurde.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| use_default | bool | Wenn auf <c>true</c> gesetzt, verwendet die Information aus FileInfo als Standardwert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.DateTime | Das Datum und die Uhrzeit, zu der das Ressourcenbild zuletzt geändert wurde. |


### Method: get_original_options() {#get_original_options__56}


```
 get_original_options() 
```

Rufen Sie die Bildoptionen basierend auf den ursprünglichen Dateieinstellungen ab. Diese Methode ist <br/>            nützlich, um die Bit‑Tiefe und andere Parameter des Originalbildes beizubehalten, wodurch Konsistenz gewährleistet und die Integrität der Bilddaten erhalten bleibt. <br/>            Der Zugriff auf diese Optionen erleichtert die nahtlose Handhabung und Verarbeitung des Bildes, <br/>            während seine ursprünglichen Merkmale erhalten bleiben.<br/>            Beispiel: Wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es anschließend mit der<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) Methode speichern, wird ein PNG‑Ausgabebild mit 8 Bit pro Pixel erzeugt.<br/>            Um dies zu vermeiden und ein PNG‑Bild mit 1‑Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und sie<br/>            an die [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) Methode als zweiten Parameter zu übergeben.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Optionen basierend auf den ursprünglichen Dateieinstellungen. |


### Method: get_pixel(x, y) {#get_pixel_x_y_57}


```
 get_pixel(x, y) 
```

Liefert ein Bild‑Pixel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Position des Pixels. |
| y | int | Die y-Position des Pixels. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Die Pixel‑Farbe für die angegebene Position. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_58}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_59}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_60}


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


### Method: get_skew_angle() {#get_skew_angle__61}


```
 get_skew_angle() 
```

Liefert den Schrägungswinkel.<br/>            Diese Methode ist auf gescannte Textdokumente anwendbar, um den Schrägungswinkel beim Scannen zu bestimmen.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float | Der Schrägwinkel in Grad. |


### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_62}


```
 is_digital_signed(password, percentage_threshold) 
```

Führt eine schnelle Prüfung durch, um festzustellen, ob das Bild digital signiert ist, wobei das bereitgestellte Passwort und der Schwellenwert verwendet werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Passwort | string | Das Passwort zur Überprüfung der Signatur. |
| percentage_threshold | int | Der Schwellenwert (in Prozent)[0-100], der bestimmt, ob das Bild als signiert gilt.<br/>            Wenn nicht angegeben, wird ein Standardschwellenwert (<c>75</c>) verwendet. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Wahr, wenn das Bild signiert ist, sonst falsch. |


### Method: load(file_path)  [static] {#load_file_path_63}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_64}


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


### Method: load(stream)  [static] {#load_stream_65}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_66}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_67}


```
 load_argb_32_pixels(rectangle) 
```

Lädt 32‑Bit‑ARGB‑Pixel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, aus dem Pixel geladen werden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Das geladene 32‑Bit‑ARGB‑Pixel‑Array. |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_68}


```
 load_argb_64_pixels(rectangle) 
```

Lädt 64‑Bit‑ARGB‑Pixel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, aus dem Pixel geladen werden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Das geladene 64-bit ARGB-Pixel-Array. |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_69}


```
 load_cmyk_32_pixels(rectangle) 
```

Lädt Pixel im CMYK‑Format.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, aus dem Pixel geladen werden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Das geladene CMYK-Pixel-Array wird als 32-bit Integer-Werte dargestellt. |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_70}


```
 load_cmyk_pixels(rectangle) 
```

Lädt Pixel im CMYK‑Format.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere Methode [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, aus dem Pixel geladen werden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Das geladene CMYK-Pixel-Array. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_71}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Lädt 32‑Bit‑ARGB‑Pixel teilweise (nach Blöcken).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, aus dem Pixel geladen werden. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Der partielle Pixel‑Lader. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_72}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Lädt 64‑Bit‑ARGB‑Pixel teilweise nach Paketen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das gewünschte Rechteck. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | Der 64-bit ARGB-Pixel-Lader. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_73}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Lädt Pixel teilweise nach Paketen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das gewünschte Rechteck. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Der Pixel-Lader. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_74}


```
 load_pixels(rectangle) 
```

Lädt Pixel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, aus dem Pixel geladen werden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Das geladene Pixel-Array. |


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_75}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

Lädt Rohdaten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, aus dem Rohdaten geladen werden. |
| dest_image_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Die Ziel-Bildgrenzen. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Die Rohdaten-Einstellungen, die für geladene Daten verwendet werden. Hinweis: Wenn Daten nicht im angegebenen Format vorliegen, wird eine Datenkonvertierung durchgeführt. |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Der Rohdaten-Lader. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_76}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Lädt Rohdaten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, aus dem Rohdaten geladen werden. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Die Rohdaten-Einstellungen, die für geladene Daten verwendet werden. Hinweis: Wenn Daten nicht im angegebenen Format vorliegen, wird eine Datenkonvertierung durchgeführt. |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Der Rohdaten-Lader. |

### Method: load_stream(stream)  [static] {#load_stream_stream_77}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_78}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_79}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_80}


```
 normalize_angle(resize_proportionally, background_color) 
```

Normalisiert den Winkel.<br/>            Diese Methode ist auf gescannte Textdokumente anwendbar, um die verzerrte Aufnahme zu korrigieren.<br/>            Diese Methode verwendet die Methoden [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) und [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| resize_proportionally | bool | Wenn auf <c>true</c> gesetzt, wird die Bildgröße gemäß den Projektionen des gedrehten Rechtecks (Eckpunkte) geändert; andernfalls bleiben die Abmessungen unverändert und nur der Bildinhalt wird rotiert. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Farbe des Hintergrunds. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_81}


```
 read_argb_32_scan_line(scan_line_index) 
```

Liest die gesamte Scanzeile anhand des angegebenen Scanzeilen‑Index.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| scan_line_index | int | Nullbasierter Index der Scan-Zeile. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int[] | Das 32-bit ARGB-Farbwert-Array der Scan-Zeile. |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_82}


```
 read_scan_line(scan_line_index) 
```

Liest die gesamte Scanzeile anhand des angegebenen Scanzeilen‑Index.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| scan_line_index | int | Nullbasierter Index der Scan-Zeile. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Das Pixel-Farbwert-Array der Scan-Zeile. |


### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_83}


```
 replace_argb(old_color_argb, old_color_diff, new_color_argb) 
```

Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| old_color_argb | int | Alter ARGB-Farbwert, der ersetzt werden soll. |
| old_color_diff | System.Byte | Erlaubte Differenz im alten Farbwert, um den ersetzten Farbton zu erweitern. |
| new_color_argb | int | Neuer ARGB-Farbwert, um den alten Farbwert zu ersetzen. |

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_84}


```
 replace_color(old_color, old_color_diff, new_color) 
```

Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| old_color | [Color](/imaging/python-net/aspose.imaging/color/) | Alte Farbe, die ersetzt werden soll. |
| old_color_diff | System.Byte | Erlaubte Differenz im alten Farbwert, um den ersetzten Farbton zu erweitern. |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | Neue Farbe, mit der die alte Farbe ersetzt wird. |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_85}


```
 replace_color(old_color_argb, old_color_diff, new_color_argb) 
```

Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| old_color_argb | int | Alter ARGB-Farbwert, der ersetzt werden soll. |
| old_color_diff | System.Byte | Erlaubte Differenz im alten Farbwert, um den ersetzten Farbton zu erweitern. |
| new_color_argb | int | Neuer ARGB-Farbwert, um den alten Farbwert zu ersetzen. |

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_86}


```
 replace_non_transparent_colors(new_color) 
```

Ersetzt alle nicht-transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.<br/>            Hinweis: Wenn Sie es bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | Neue Farbe, mit der nicht-transparente Farben ersetzt werden. |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_87}


```
 replace_non_transparent_colors(new_color_argb) 
```

Ersetzt alle nicht-transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.<br/>            Hinweis: Wenn Sie es bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_color_argb | int | Neuer ARGB-Farbwert, um nicht-transparente Farben zu ersetzen. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_88}


```
 resize(new_width, new_height) 
```

Skaliert das Bild. Der Standardwert [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_89}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_90}


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

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_91}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_92}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_93}


```
 resize_height_proportionally(new_height) 
```

Skaliert die Höhe proportional. Der Standard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_94}


```
 resize_height_proportionally(new_height, resize_type) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ der Skalierung. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_95}


```
 resize_height_proportionally(new_height, settings) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Bildskalierungseinstellungen. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_96}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Bildskalierungseinstellungen. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_97}


```
 resize_width_proportionally(new_width) 
```

Skaliert die Breite proportional. Der Standard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_98}


```
 resize_width_proportionally(new_width, resize_type) 
```

Skaliert die Breite proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ der Skalierung. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_99}


```
 resize_width_proportionally(new_width, settings) 
```

Skaliert die Breite proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Bildskalierungseinstellungen. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_100}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Skaliert die Breite proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Bildskalierungseinstellungen. |

### Method: rotate(angle) {#rotate_angle_101}


```
 rotate(angle) 
```

Bild um das Zentrum drehen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_102}


```
 rotate(angle, resize_proportionally, background_color) 
```

Bild um das Zentrum drehen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |
| resize_proportionally | bool | Wenn auf <c>true</c> gesetzt, wird die Bildgröße gemäß den Projektionen des gedrehten Rechtecks (Eckpunkte) geändert; andernfalls bleiben die Abmessungen unverändert und nur der Bildinhalt wird rotiert. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Farbe des Hintergrunds. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_103}


```
 rotate_flip(rotate_flip_type) 
```

Dreht, spiegelt oder dreht und spiegelt das Bild.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Der Rotations-Flip-Typ. |

### Method: save(file_path) {#save_file_path_104}


```
 save(file_path) 
```

Speichert das Bild am angegebenen Dateipfad.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem das Bild gespeichert wird. |

### Method: save(file_path, options) {#save_file_path_options_105}


```
 save(file_path, options) 
```

Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Optionen. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_106}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_107}


```
 save(file_path, over_write) 
```

Speichert die Daten des Objekts am angegebenen Speicherort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Objektdaten gespeichert werden. |
| over_write | bool | wenn auf <c>true</c> gesetzt, werden die Dateiinhalte überschrieben, andernfalls wird angehängt. |

### Method: save(stream) {#save_stream_108}


```
 save(stream) 
```

Speichert die Daten des Objekts in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in den die Objekt­daten gespeichert werden sollen |

### Method: save(stream, options_base) {#save_stream_options_base_109}


```
 save(stream, options_base) 
```

Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem die Bilddaten gespeichert werden. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Speicheroptionen. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_110}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_111}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Speichert die 32‑Bit‑ARGB‑Pixel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, in dem Pixel gespeichert werden. |
| Pixel | int[] | Das 32‑Bit‑ARGB‑Pixel‑Array. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_112}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Speichert die Pixel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, in dem Pixel gespeichert werden. |
| Pixel | int[] | Die CMYK‑Pixel, dargestellt als 32‑Bit‑Ganzzahlwerte. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_113}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Speichert die Pixel.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) Methode.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, in dem Pixel gespeichert werden. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Das CMYK‑Pixel‑Array. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_114}


```
 save_pixels(rectangle, pixels) 
```

Speichert Pixel (formatspezifische Methode).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, in dem Pixel gespeichert werden. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Das 32‑Bit‑ARGB‑Pixel‑Array. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_115}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

Speichert die Rohdaten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Daten | System.Byte | Die Rohdaten. |
| data_offset | int | Der Anfangs‑Rohdaten‑Offset. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rohdaten‑Rechteck. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Die Rohdaten, in denen sich die Daten befinden. |

### Method: save_to_stream(stream) {#save_to_stream_stream_116}


```
 save_to_stream(stream) 
```

Speichert die Daten des Objekts in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem die Daten des Objekts gespeichert werden sollen. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_117}


```
 save_to_stream_with_options(stream, options_base) 
```

Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem die Bilddaten gespeichert werden. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Speicheroptionen. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_118}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_119}


```
 save_with_options(file_path, options) 
```

Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Optionen. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_120}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_121}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

Setzt ein 32‑Bit‑ARGB‑Pixel des Bildes für die angegebene Position.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Position des Pixels. |
| y | int | Die y-Position des Pixels. |
| argb_32_color | int | Das 32‑Bit‑ARGB‑Pixel für die angegebene Position. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_122}


```
 set_palette(palette, update_colors) 
```

Setzt die Bildpalette.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die zu setzende Palette. |
| update_colors | bool | Wenn auf <c>true</c> gesetzt, werden die Farben gemäß der neuen Palette aktualisiert; andernfalls bleiben die Farbindizes unverändert. Hinweis: Unveränderte Indizes können das Bild beim Laden zum Absturz bringen, wenn einige Indizes keinen entsprechenden Paletteneintrag haben. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_123}


```
 set_pixel(x, y, color) 
```

Setzt ein Bildpixel für die angegebene Position.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Position des Pixels. |
| y | int | Die y-Position des Pixels. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Die Pixel‑Farbe für die angegebene Position. |

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_124}


```
 set_resolution(dpi_x, dpi_y) 
```

Setzt die Auflösung für dieses [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dpi_x | float | Die horizontale Auflösung in Punkten pro Zoll des [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | Die vertikale Auflösung in Punkten pro Zoll des [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_125}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_126}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Schreibt die gesamte Scanzeile in den angegebenen Scanzeilen‑Index.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| scan_line_index | int | Nullbasierter Index der Scan-Zeile. |
| argb_32_pixels | int[] | Das 32‑Bit‑ARGB‑Farben‑Array zum Schreiben. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_127}


```
 write_scan_line(scan_line_index, pixels) 
```

Schreibt die gesamte Scanzeile in den angegebenen Scanzeilen‑Index.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| scan_line_index | int | Nullbasierter Index der Scan-Zeile. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Das Pixel‑Farben‑Array zum Schreiben. |

## **Examples**
### This example shows how to load a JPEG2000 image from a file and save it to PNG. {#example_158}
``` python
import aspose.pycore as aspycore
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Image
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp"
# Lädt ein JPEG2000‑Bild.
with Jpeg2000Image(join(dir_, "sample.jp2")) as jpeg2000_image:
	# Als PNG speichern
	jpeg2000_image.save(join(dir_, "sample.output.png"), PngOptions())


```

### This example shows how to load a JPEG2000 image from a file stream and save it to PNG. {#example_159}
``` python
import aspose.pycore as aspycore
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Image
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp"
# Lädt ein JPEG2000‑Bild aus einem Stream.
with open(join(dir_, "sample.jp2"), "rb") as stream:
	with Jpeg2000Image(stream) as jpeg2000_image:
		# Als PNG speichern
		jpeg2000_image.save(join(dir_, "sample.output.png"), PngOptions())


```

### This example shows how to create a JPEG2000 image and save it to a file. {#example_160}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Image
from aspose.imaging.imageoptions import Jpeg2000Options
from os.path import join

dir_: str = "c:\\temp"
# Erstellt ein JPEG2000‑Bild mit 100 × 100 px.
with Jpeg2000Image(100, 100) as jpeg2000_image:
	graphics = Graphics(jpeg2000_image)
	# Füllen Sie das gesamte Bild mit Rot.
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, jpeg2000_image.bounds)
	# In einer Datei speichern
	jpeg2000_image.save(join(dir_, "sample.output.jp2"), Jpeg2000Options())


```

### This example shows how to create a JPEG2000 image with the desired options and save it to a file. {#example_161}
``` python

from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import Jpeg2000Options
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Codec, Jpeg2000Image
from os.path import join as path_join     


dir_ = "c:\\temp"
create_options = Jpeg2000Options()
# Verwendet die irreversible Diskrete Wavelet‑Transformation 9‑7
create_options.irreversible = True
# JP2 ist das "Container"‑Format für JPEG‑2000‑Codestreams.
# J2K ist Rohdaten, ohne Wrapper.
create_options.codec = Jpeg2000Codec.J2K
# Erstellt ein JPEG2000‑Bild mit 100 × 100 px.
with Jpeg2000Image(100, 100, create_options) as jpeg2000_image:
	graphics = Graphics(jpeg2000_image)
	# Füllen Sie das gesamte Bild mit Rot.
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, jpeg2000_image.bounds)
	# In einer Datei speichern
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
# Erstellen Sie ein PNG-Bild mit 100 × 100 px.
with PngImage(100, 100) as png_image:
	graphics = Graphics(png_image)
	# Füllen Sie das gesamte Bild mit Rot.
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	save_options = Jpeg2000Options()
	# Verwendet die irreversible Diskrete Wavelet‑Transformation 9‑7
	save_options.irreversible = True
	# JP2 ist das "Container"‑Format für JPEG‑2000‑Codestreams.
	# J2K ist Rohdaten, ohne Wrapper.
	save_options.codec = Jpeg2000Codec.J2K
	# In einer Datei speichern
	png_image.save(path_join(dir_, "output.j2k"), save_options)


```

