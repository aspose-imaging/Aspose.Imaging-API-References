---
title: "WebPImage Klasse"
type: docs
weight: 30
url: /de/python-net/aspose.imaging.fileformats.webp/webpimage/
---

**Summary:** Manipulate WebP raster images with our API, using its modern features for both<br/>            lossless and lossy compression, ensuring optimal image quality with reduced file sizes.<br/>            Seamlessly handle extended file formats, animations, and alpha channels, while easily<br/>            updating dimensions, resizing proportionally, cropping, rotating, applying filters,<br/>            adjusting image parameters, and converting to other image formats for versatile<br/>            web image optimization.

**Module:** [aspose.imaging.fileformats.webp](/imaging/python-net/aspose.imaging.fileformats.webp/)

**Full Name:** aspose.imaging.fileformats.webp.WebPImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IMultipageImage, IMultipageImageExt, RasterCachedMultipageImage

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [WebPImage(path)](#WebPImage_path_1) | Instanziieren Sie eine neue Instanz der Klasse [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/), initialisiert <br/>            aus einer bereitgestellten Dateiquelle. Verwenden Sie diesen Konstruktor, um WebP-<br/>            Bildobjekte direkt aus Dateien nahtlos zu erstellen und den Ladevorgang sowie die<br/>            Manipulation von WebP-Bilddaten in Ihrer Anwendung zu optimieren. |
| [WebPImage(path, load_options)](#WebPImage_path_load_options_2) | Erstellen Sie eine neue Instanz der Klasse [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) mithilfe einer Datei und <br/>            angegebenen Ladeoptionen, um eine flexible Handhabung von WebP-Bilddaten zu ermöglichen. Verwenden Sie <br/>            diesen Konstruktor, um WebP-Bildobjekte nahtlos aus Dateien zu initialisieren und dabei <br/>            die Ladevorgänge gemäß den Anforderungen Ihrer Anwendung anzupassen. |
| [WebPImage(raster_image)](#WebPImage_raster_image_3) | Instanziieren Sie eine neue Instanz der Klasse [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/), initialisiert <br/>            aus einem bereitgestellten rasterImage-Objekt. Dieser Konstruktor ermöglicht eine nahtlose <br/>            Konvertierung von Rasterbildern in das WebP-Format und unterstützt eine effiziente Handhabung sowie <br/>            Manipulation von Bilddaten in Ihrer Anwendung. |
| [WebPImage(raster_image, load_options)](#WebPImage_raster_image_load_options_4) | Erstellen Sie eine neue Instanz der Klasse [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) mithilfe eines rasterImage-Objekts und <br/>            angegebenen Ladeoptionen, um eine flexible Handhabung von Bilddaten zu ermöglichen. Verwenden Sie diesen <br/>            Konstruktor, um WebP-Bildobjekte nahtlos aus Rasterbildern zu initialisieren und dabei <br/>            die Ladevorgänge gemäß den Anforderungen Ihrer Anwendung anzupassen. |
| [WebPImage(stream)](#WebPImage_stream_5) | Instanziieren Sie eine neue Instanz der [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) Klasse, initialisiert <br/>            aus einer bereitgestellten Stream-Quelle. Verwenden Sie diesen Konstruktor, um nahtlos WebP <br/>            Bildobjekte direkt aus Streams zu erstellen, wodurch eine effiziente Handhabung und Manipulation <br/>            von WebP-Bilddaten in Ihrer Anwendung ermöglicht wird. |
| [WebPImage(stream, load_options)](#WebPImage_stream_load_options_6) | Erstellen Sie eine neue Instanz der [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) Klasse aus einem Stream,  <br/>            unter Einbeziehung der angegebenen Ladeoptionen und Speicherverwaltungseinstellungen. Dieser <br/>            Konstruktor bietet Flexibilität beim Laden von WebP-Bildern aus Streams, während er <br/>            Speicherressourcen effizient verwaltet und so optimale Leistung und Ressourcennutzung <br/>            in Ihrer Anwendung sicherstellt. |
| [WebPImage(width, height, options)](#WebPImage_width_height_options_7) | Instanziieren Sie eine neue Instanz der [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) Klasse mit einem leeren <br/>            Bild mit angegebenen Breiten- und Höhenmaßen. Dieser Konstruktor ermöglicht die <br/>            Erstellung leerer WebP-Bilder und bietet eine Grundlage für nachfolgende Bild-<br/>            Manipulationen und Inhaltserzeugung in Ihrer Anwendung. |
| [WebPImage(width, height, options, load_options)](#WebPImage_width_height_options_load_options_8) | Erstellen Sie eine neue Instanz der [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) Klasse mit einem leeren Bild und angegebenen <br/>            Ladeoptionen. Dieser Konstruktor ermöglicht die Initialisierung von WebP-Bildern mit <br/>            anpassbaren Ladeparametern und bietet Flexibilität bei der Bild­erstellung und <br/>            -manipulation in Ihrer Anwendung. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die automatische Anpassung der Palette erfolgt. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Liest oder setzt einen Wert für die Hintergrundfarbe. |
| bits_per_pixel | int | r | Liest die Bit‑Pro‑Pixel‑Anzahl des Bildes. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Liest die Objektgrenzen. |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Liest den [Image](/imaging/python-net/aspose.imaging/image/) Container. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Liest den Datenstrom des Objekts. |
| freigegeben | bool | r | Liest einen Wert, der angibt, ob diese Instanz freigegeben ist. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Liest oder setzt die Exif‑Instanz. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Greifen Sie auf den Dateiformatwert zu, der dem Bild zugeordnet ist, und erhalten Sie Informationen <br/>            über das Format, in dem das Bild gespeichert ist. Verwenden Sie diese Eigenschaft, um das <br/>            Dateiformat des Bildes zu bestimmen, was Kompatibilitätsprüfungen und <br/>            formatbezogene Verarbeitung in Ihrer Anwendung erleichtert. |
| [has_alpha](#has_alpha1) | bool | r | Ermitteln Sie, ob das Bild einen Alpha-Kanal enthält, was auf das Vorhandensein von <br/>            Transparenzinformationen hinweist. Verwenden Sie diese Eigenschaft, um festzustellen, ob das Bild <br/>            Transparenz enthält, und ermöglichen Sie eine geeignete Handhabung und Verarbeitung von <br/>            Alpha-bezogenen Vorgängen in Ihrer Anwendung. |
| has_background_color | bool | r/w | Liest oder setzt einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| has_transparent_color | bool | r/w | Liest einen Wert, der angibt, ob das Bild eine transparente Farbe hat. |
| height | int | r | Liest die Bildhöhe. |
| horizontal_resolution | float | r/w | Liest oder setzt die horizontale Auflösung in Pixel pro Zoll dieses [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| image_opacity | float | r | Liest die Opazität dieses Bildes. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Liest oder setzt den Interrupt-Monitor. |
| is_cached | bool | r | Liest einen Wert, der angibt, ob Bilddaten derzeit zwischengespeichert sind. |
| is_raw_data_available | bool | r | Liest einen Wert, der angibt, ob das Laden von Rohdaten unterstützt wird. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Liest oder setzt XMP-Daten aus dem Frame. |
| options | [WebPOptions](/imaging/python-net/aspose.imaging.imageoptions/webpoptions/) | r | Rufen Sie die mit der angegebenen Eigenschaft verbundenen Optionen ab oder ändern Sie sie, um <br/>            eine fein abgestimmte Anpassung von Verhalten und Einstellungen zu ermöglichen. Verwenden Sie diese Eigenschaft, um <br/>            konfigurierbare Parameter nahtlos zuzugreifen und zu manipulieren, was eine vielseitige <br/>            Steuerung und Optimierung der Funktionalität Ihrer Anwendung ermöglicht. |
| page_count | int | r | Ermitteln Sie die Gesamtzahl der Seiten im angegebenen Dokument, um <br/>            eine effiziente Navigation und Verwaltung von mehrseitigem Inhalt zu ermöglichen. Integrieren Sie diese <br/>            Funktion, um die Benutzererfahrung zu verbessern und einen nahtlosen Zugriff auf <br/>            umfassende Dokumentstrukturen zu ermöglichen. |
| pages | [Image[]](/imaging/python-net/aspose.imaging/image/) | r | Greifen Sie auf die WebP-Blöcke im Bild zu, um eine detaillierte Untersuchung oder <br/>            Manipulation der zugrunde liegenden Blockstruktur zu ermöglichen. Verwenden Sie diese Eigenschaft, um <br/>            einzelne Blöcke innerhalb der WebP-Bilddaten zu analysieren oder zu ändern, was fortgeschrittene <br/>            Bildverarbeitungstechniken in Ihrer Anwendung unterstützt. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Liest oder setzt die Farbpalette. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| premultiply_components | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die Bildkomponenten vormultipliziert werden müssen. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | Liest oder setzt den benutzerdefinierten Farbkonverter |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Liest das Rohdatenformat. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | Liest die aktuellen Rohdateneinstellungen. Hinweis: Beim Verwenden dieser Einstellungen werden die Daten ohne Konvertierung geladen. |
| raw_fallback_index | int | r/w | Liest oder setzt den Rückfallindex, der verwendet wird, wenn der Palettenindex außerhalb des gültigen Bereichs liegt |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | Liest oder setzt den indizierten Farbkonverter |
| raw_line_size | int | r | Liest die Rohzeilengröße in Bytes. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Liest die Objektgröße. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Liest die transparente Bildfarbe. |
| update_xmp_data | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die XMP-Metadaten aktualisiert werden sollen. |
| use_palette | bool | r | Liest einen Wert, der angibt, ob die Bildpalette verwendet wird. |
| use_raw_data | bool | r/w | Liest oder setzt einen Wert, der angibt, ob das Laden von Rohdaten verwendet werden soll, wenn das Laden von Rohdaten verfügbar ist. |
| vertical_resolution | float | r/w | Liest oder setzt die vertikale Auflösung in Pixel pro Zoll dieses [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | r | Liest die Bildbreite. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Liest oder setzt XMP-Daten. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_block(block)](#add_block_block_1) | Fügen Sie dem Bild einen neuen WebP-Block hinzu, um dessen Inhalt zu erweitern und <br/>            fortgeschrittene Bildmanipulation zu ermöglichen. Integrieren Sie diese Methode, um dynamisch <br/>            die Struktur und Komplexität der WebP-Bilddaten in Ihrer <br/>            Anwendung zu verbessern, wodurch eine präzise Steuerung und Optimierung der Bilddarstellung ermöglicht wird. |
| [add_page(page)](#add_page_page_2) | Fügen Sie dem Bild eine neue Seite hinzu, um dessen Inhalt zu erweitern und zusätzliche <br/>            visuelle Elemente zu integrieren. Integrieren Sie diese Methode, um die dynamische Seitenverwaltung <br/>            in Ihrer Anwendung zu erleichtern, wodurch die nahtlose Erstellung und Erweiterung von mehrseitigen <br/>            Dokumenten oder Bildern ermöglicht wird. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_3) | Implementieren Sie die _Helligkeits_‑Anpassung für das Bild, um die <br/>            Gesamthelligkeitswerte zu verändern. Integrieren Sie diese Methode in Ihren Bild‑<br/>            Verarbeitung‑Workflow, um die Sichtbarkeit zu erhöhen und die visuelle Qualität von Bildern <br/>            in Ihrer Anwendung zu verbessern. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_4) | Verbessern Sie den Kontrast des [Image](/imaging/python-net/aspose.imaging/image/), indem Sie die <br/>            Unterschiede zwischen hellen und dunklen Bereichen verstärken. Integrieren Sie diese Methode in Ihren Bild‑<br/>            Verarbeitung‑Workflow, um die visuelle Klarheit und die Gesamtbildqualität in Ihrer <br/>            Anwendung zu erhöhen. |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_5) | Wenden Sie eine Gammakorrektur auf das Bild an, um die Pixelintensitäten anzupassen und die gewünschte Helligkeit sowie Farbbalance zu erreichen. Integrieren Sie diese Methode in Ihren Bild‑<br/>            Verarbeitung‑Workflow, um die visuelle Qualität zu verbessern und die Genauigkeit von <br/>            nachfolgenden Analyse‑ oder Anzeigeaufgaben in Ihrer Anwendung zu erhöhen. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_6) | Führen Sie eine Gammakorrektur am Bild durch, indem Sie einzelne Koeffizienten für die roten, <br/>            grünen und blauen Kanäle verwenden, um fein abgestimmte Anpassungen von Farbbalance und <br/>            Kontrast zu ermöglichen. Integrieren Sie diese Methode in Ihre Bildverarbeitungspipeline, um <br/>            eine präzise Kontrolle über die Farbdarstellung zu erreichen und die visuelle Treue in Ihrer <br/>            Anwendung zu verbessern. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_7) | Berechnet den prozentualen Ähnlichkeitsgrad zwischen den extrahierten Daten und dem ursprünglichen Passwort. |
| auto_brightness_contrast() | Führt eine automatische adaptive Helligkeits- und Kontrastnormalisierung für das gesamte Bild durch. |
| auto_rotate() | Dreht das Bild automatisch basierend auf den aus den Exif-<br/>            Metadaten extrahierten Orientierungsdaten. Diese Methode stellt sicher, dass Bilder in der korrekten Ausrichtung angezeigt werden, <br/>            verbessert das Benutzererlebnis und eliminiert die Notwendigkeit manueller Anpassungen. Durch <br/>            Analyse der Exif-Informationen wird das Bild entsprechend gedreht, was ein nahtloses <br/>            Anzeigeerlebnis über verschiedene Plattformen und Geräte hinweg ermöglicht. Dieser automatisierte Rotations<br/>            Prozess vereinfacht die Bildverarbeitung und erhöht die Gesamtbenutzerfreundlichkeit, insbesondere bei <br/>            großen Bildmengen mit unterschiedlichen Ausrichtungen. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_8) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild-Schwellenwertbestimmung |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_9) | Wenden Sie die Binarisierung auf das Bild an, indem Sie Bradleys adaptiven Schwellenwertalgorithmus <br/>            mit Integralbild‑Schwellwertbildung verwenden. Diese Methode berechnet dynamisch lokale <br/>            Schwellenwerte basierend auf der Nachbarschaft des Bildes, verbessert die Anpassungsfähigkeit an unterschiedliche <br/>            Lichtverhältnisse und sorgt für eine robuste Segmentierung für nachfolgende Verarbeitungs‑<br/>            aufgaben in Ihrer Anwendung. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_10) | Führen Sie die Binarisierung des Bildes mit einem vordefinierten Schwellenwert durch, indem Sie es in ein binäres Bild umwandeln, bei dem Pixel basierend auf ihrer Intensität relativ zum Schwellenwert als Vorder‑ oder Hintergrund klassifiziert werden. Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um Segmentierungs‑ und Merkmalextraktions‑aufgaben zu erleichtern und die Genauigkeit sowie Effizienz nachfolgender Analysen in Ihrer <br/>            Anwendung zu steigern. |
| binarize_otsu() | Führen Sie die Binarisierung des Bildes mit Otsus Schwellenwertmethode durch, die automatisch <br/>            den optimalen Schwellenwert basierend auf dem Histogramm des Bildes bestimmt. Integrieren <br/>            Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um eine effektive Segmentierung <br/>            und Merkmalextraktion zu erreichen und die Genauigkeit sowie Zuverlässigkeit von Bildanalyse‑<br/>            aufgaben in Ihrer Anwendung zu verbessern. |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_11) | Mischt diese Bildinstanz mit dem _overlay_-Bild. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_12) | Mischt diese Bildinstanz mit dem _overlay_-Bild. |
| cache_data() | Zwischenspeichert die Daten privat. |
| [can_load(file_path)](#can_load_file_path_13) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_14) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann und optional die angegebenen Öffnungsoptionen verwendet. |
| [can_load(stream)](#can_load_stream_15) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann. |
| [can_load(stream, load_options)](#can_load_stream_load_options_16) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann und optional die angegebenen _loadOptions_ verwendet. |
| [can_load_stream(stream)](#can_load_stream_stream_17) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_18) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann und optional die angegebenen _loadOptions_ verwendet. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_19) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann und optional die angegebenen Öffnungsoptionen verwendet. |
| [can_save(options)](#can_save_options_20) | Bestimmt, ob das Bild im angegebenen Dateiformat, das durch die übergebenen Speicheroptionen repräsentiert wird, gespeichert werden kann. |
| clear_blocks() | Löschen Sie alle vorhandenen WebP‑Blöcke aus dem Bild, um eine saubere Basis für <br/>            nachfolgende Änderungen oder Ergänzungen zu schaffen. Verwenden Sie diese Methode, um die <br/>            Blockstruktur der WebP‑Bilddaten effektiv zurückzusetzen und eine optimale Verwaltung sowie <br/>            Organisation des Bildinhalts in Ihrer Anwendung sicherzustellen. |
| [create(files)](#create_files_21) | Erstellt das mehrseitige Bild, das die angegebenen Dateien enthält. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_22) | Erstellt das mehrseitige Bild, das die angegebenen Dateien enthält. |
| [create(image_options, width, height)](#create_image_options_width_height_23) | Erstellt ein neues Bild mit den angegebenen Erstellungsoptionen. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_24) | Erstellt eine [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) Instanz aus dem bereitgestellten Pixelarray.<br/>            <br/>            Validiert, dass die angegebene Breite und Höhe den Abmessungen der Pixeldaten entsprechen.<br/>            Diese Methode kann nur verwendet werden, wenn die Bibliothek im lizenzierten Modus ist. |
| [create(images)](#create_images_25) | Erstellt ein neues Bild, das die angegebenen Bilder als Seiten verwendet |
| [create(images, dispose_images)](#create_images_dispose_images_26) | Erstellt ein neues Bild, wobei die angegebenen Bilder als Seiten verwendet werden. |
| [create(multipage_create_options)](#create_multipage_create_options_27) | Erstellt die angegebenen Mehrseiten‑Erstellungsoptionen. |
| [create_from_file_with_options(path, load_options)](#create_from_file_with_options_path_load_options_28) | Initialisiert eine neue Instanz der [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) Klasse aus einer Datei. |
| [create_from_files(files)](#create_from_files_files_29) | Erstellt das Mehrseiten‑Bild, das die angegebenen Dateien als Lazy‑Loading‑Seiten enthält. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_30) | Erstellt das Mehrseiten‑Bild, das die angegebenen Dateien als Lazy‑Loading‑Seiten enthält. |
| [create_from_image(raster_image)](#create_from_image_raster_image_31) | Initialisiert eine neue Instanz der [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) Klasse aus rasterImage. |
| [create_from_image_with_options(raster_image, load_options)](#create_from_image_with_options_raster_image_load_options_32) | Initialisiert eine neue Instanz der [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) Klasse aus rasterImage. |
| [create_from_images(images)](#create_from_images_images_33) | Erstellt ein neues Bild, das die angegebenen Bilder als Seiten verwendet |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_34) | Erstellt ein neues Bild, wobei die angegebenen Bilder als Seiten verwendet werden. |
| [create_from_stream(stream)](#create_from_stream_stream_35) | Initialisiert eine neue Instanz der [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) Klasse<br/>                aus einem Stream. |
| [create_from_stream_with_options(stream, load_options)](#create_from_stream_with_options_stream_load_options_36) | Initialisiert eine neue Instanz der [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) Klasse aus einem Stream. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_37) | Beschneiden Sie das Bild, indem Sie linke, rechte, obere und untere Verschiebungen anwenden und so <br/>            effektiv einen Interessensbereich im Bild auswählen. Verwenden Sie diese Methode, um <br/>            gewünschte Bildbereiche dynamisch zu extrahieren und gleichzeitig die Zusammensetzung <br/>            und den Fokus gemäß den Anforderungen Ihrer Anwendung anzupassen. |
| [crop(rectangle)](#crop_rectangle_38) | Beschneiden Sie das Bild mithilfe eines angegebenen Rechteckbereichs und entfernen Sie unerwünschte Teile <br/>            bei gleichzeitiger Beibehaltung des gewünschten Inhalts. Integrieren Sie diese Methode in Ihren Bild‑<br/>            Verarbeitung‑Workflow, um gezielt bestimmte Interessensbereiche im Bild zu extrahieren und zu fokussieren, wodurch Klarheit und Zusammensetzung für verschiedene Anwendungen verbessert werden. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_39) | Führt Dithering auf dem aktuellen Bild aus. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_40) | Führen Sie Dithering auf dem aktuellen Bild durch, um Farbbänderungen zu reduzieren und die visuelle <br/>            Qualität zu verbessern. Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um <br/>            sanftere Übergänge zwischen den Farben zu erzielen und das Gesamterscheinungsbild des <br/>            Bildes in Ihrer Anwendung zu verbessern. |
| [embed_digital_signature(password)](#embed_digital_signature_password_41) | Betten Sie eine digitale Signatur, basierend auf dem angegebenen Passwort, in jede Seite des Bildes ein. |
| [filter(rectangle, options)](#filter_rectangle_options_42) | Filtern Sie den Inhalt innerhalb des angegebenen Rechtecks und wenden Sie einen festgelegten Bild‑<br/>            Verarbeitungsfilter an, um den ausgewählten Bereich zu verbessern oder zu verändern. Integrieren Sie diese Methode <br/>            in Ihren Bildbearbeitungs‑Workflow, um gezielte Verbesserungen oder <br/>            Transformationen in Ihrer Anwendung zu erreichen. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_43) | Liefert ein 32‑Bit‑ARGB‑Pixel‑Bild. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_44) | Liefert das Standard‑32‑Bit‑ARGB‑Pixel‑Array. |
| [get_default_options(args)](#get_default_options_args_45) | Liefert die Standardoptionen. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_46) | Liefert das Standard‑Pixel‑Array mittels teilweisem Pixel‑Lader. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_47) | Liefert das Standard‑Rohdaten‑Array mittels teilweisem Pixel‑Lader. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_48) | Liefert das Standard‑Rohdaten‑Array. |
| [get_file_format(file_path)](#get_file_format_file_path_49) | Liefert das Dateiformat. |
| [get_file_format(stream)](#get_file_format_stream_50) | Liefert das Dateiformat. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_51) | Liefert das Dateiformat. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_52) | Liefert das Rechteck, das zum aktuellen Bild passt. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_53) | Liefert das Rechteck, das zum aktuellen Bild passt. |
| [get_modify_date(use_default)](#get_modify_date_use_default_54) | Liefert Datum und Uhrzeit, zu der das Ressourcen‑Bild zuletzt geändert wurde. |
| [get_original_options()](#get_original_options__55) | Liefert die Optionen basierend auf den ursprünglichen Dateieinstellungen.<br/>            Dies kann hilfreich sein, um die Bit‑Tiefe und andere Parameter des Originalbildes unverändert zu lassen.<br/>            Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es anschließend mit der<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/)‑Methode speichern, wird ein PNG‑Ausgabebild mit 8 Bit pro Pixel erzeugt.<br/>            Um dies zu vermeiden und ein PNG‑Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und übergeben Sie sie<br/>            an die [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/)‑Methode als zweiten Parameter. |
| [get_pixel(x, y)](#get_pixel_x_y_56) | Liefert ein Bild‑Pixel. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_57) | Liefert eine proportionale Höhe. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_58) | Liefert eine proportionale Breite. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_59) | Konvertiert zu aps. |
| [get_skew_angle()](#get_skew_angle__60) | Liefert den Schrägungswinkel.<br/>            Diese Methode ist auf gescannte Textdokumente anwendbar, um den Schrägungswinkel beim Scannen zu bestimmen. |
| grayscale() | Konvertieren Sie das Bild in seine Graustufen‑Darstellung, indem Sie es in ein <br/>            einkanaliges Bild umwandeln, bei dem jeder Pixel die Intensität oder Helligkeit repräsentiert. Integrieren <br/>            Sie diese Methode in Ihre Bildverarbeitungspipeline, um die Analyse zu vereinfachen und die <br/>            Kompatibilität mit Graustufen‑basierten Algorithmen zu erhöhen, was verschiedene Computer‑<br/>            Vision‑ und Bildanalyseaufgaben in Ihrer Anwendung erleichtert. |
| [insert_block(index, block)](#insert_block_index_block_61) | Fügen Sie einen neuen WebP‑Block an dem angegebenen Index im Bild ein, um eine präzise <br/>            Kontrolle über die Blocksequenz zu ermöglichen. Integrieren Sie diese Methode, um nahtlos <br/>            zusätzliche WebP‑Blöcke in die Bilddatenstruktur einzufügen, was fortgeschrittene Bild‑<br/>            Verarbeitung und Optimierung in Ihrer Anwendung erleichtert. |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_62) | Führt eine schnelle Prüfung durch, um festzustellen, ob das Bild digital signiert ist, wobei das bereitgestellte Passwort und der Schwellenwert verwendet werden. |
| [load(file_path)](#load_file_path_63) | Lädt ein neues Bild vom angegebenen Dateipfad oder URL.<br/>            Wenn _filePath_ ein Dateipfad ist, öffnet die Methode einfach die Datei.<br/>            Wenn _filePath_ eine URL ist, lädt die Methode die Datei herunter, speichert sie temporär und öffnet sie. |
| [load(file_path, load_options)](#load_file_path_load_options_64) | Lädt ein neues Bild vom angegebenen Dateipfad oder URL.<br/>            Wenn _filePath_ ein Dateipfad ist, öffnet die Methode einfach die Datei.<br/>            Wenn _filePath_ eine URL ist, lädt die Methode die Datei herunter, speichert sie temporär und öffnet sie. |
| [load(stream)](#load_stream_65) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load(stream, load_options)](#load_stream_load_options_66) | Lädt die Daten aus dem Stream. |
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
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_80) | Normalisiert den Winkel.<br/>            Diese Methode ist auf gescannte Textdokumente anwendbar, um die schiefe Aufnahme zu korrigieren.<br/>            Diese Methode verwendet die Methoden [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) und [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/). |
| normalize_histogram() | Normalisiert das Bildhistogramm — passt die Pixelwerte an, um den gesamten verfügbaren Bereich zu nutzen. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_81) | Liest die gesamte Scanzeile anhand des angegebenen Scanzeilen‑Index. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_82) | Liest die gesamte Scanzeile anhand des angegebenen Scanzeilen‑Index. |
| [remove_block(block)](#remove_block_block_83) | Entfernt den angegebenen WebP‑Block aus dem Bild und erleichtert so die effiziente Verwaltung <br/>            der Bilddatenstruktur. Verwenden Sie diese Methode, um Bildverarbeitungs‑Workflows zu optimieren, <br/>            indem Sie unnötige Blöcke oder Komponenten in Ihrer Anwendung entfernen. |
| remove_metadata() | Entfernt die Metadaten dieser Bildinstanz, indem der Wert von [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) auf **None** gesetzt wird. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_84) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_85) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_86) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_87) | Ersetzt alle nicht‑transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.<br/>                Hinweis: Wenn Sie dies bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_88) | Ersetzt alle nicht‑transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.<br/>                Hinweis: Wenn Sie dies bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| [resize(new_width, new_height)](#resize_new_width_new_height_89) | Skaliert das Bild. Der Standardwert [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_90) | Skaliert das Bild, wobei die Abmessungen angepasst und das Seitenverhältnis beibehalten werden. <br/>            Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um Bilder dynamisch zu skalieren, <br/>            sodass sie verschiedenen Anzeige‑ oder Speicheranforderungen in Ihrer Anwendung entsprechen. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_91) | Skaliert das Bild gemäß den angegebenen Einstellungen und ermöglicht eine präzise Kontrolle über <br/>            Abmessungen, Seitenverhältnis und Skalierungsverhalten. Integrieren Sie diese Methode in Ihren <br/>            Bildverarbeitungs‑Workflow, um benutzerdefinierte Skalierungsoperationen zu realisieren, die auf die <br/>            spezifischen Anforderungen Ihrer Anwendung zugeschnitten sind. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_92) | Skaliert das Bild. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_93) | Skaliert das Bild. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_94) | Skaliert die Höhe proportional. Der Standard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_95) | Passen Sie die Höhe des Bildes proportional an, während das Seitenverhältnis für ein konsistentes Skalieren beibehalten wird. <br/>            Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um Bilder dynamisch mit einheitlichen Proportionen zu skalieren und so eine optimale Anzeige oder <br/>            Speicherung in Ihrer Anwendung sicherzustellen. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_96) | Skaliert die Höhe proportional. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_97) | Skaliert die Höhe proportional. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_98) | Skaliert die Breite proportional. Der Standard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_99) | Passen Sie die Breite des Bildes proportional an und behalten Sie dabei das Seitenverhältnis bei. <br/>            Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um Bilder dynamisch mit konsistenten Proportionen zu skalieren und so eine optimale Anzeige oder Speicherung in <br/>            Ihrer Anwendung zu gewährleisten. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_100) | Skaliert die Breite proportional. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_101) | Skaliert die Breite proportional. |
| [rotate(angle)](#rotate_angle_102) | Bild um das Zentrum drehen. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_103) | Drehen Sie das Bild um sein Zentrum um einen angegebenen Winkel, während Sie es proportional <br/>            skalieren und die angegebenen Hintergrundfarbparameter anwenden. Integrieren Sie diese <br/>            Methode in Ihren Bildverarbeitungs‑Workflow, um präzise Transformationen mit <br/>            anpassbaren Hintergrundfarben zu erzielen und so eine optimale visuelle Darstellung in Ihrer <br/>            Anwendung sicherzustellen. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_104) | Wenden Sie Rotation, Spiegelung oder beide Operationen ausschließlich auf den aktiven Frame <br/>            im Bild an. Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um <br/>            eine präzise Manipulation einzelner Frames zu ermöglichen, die Flexibilität und <br/>            Kontrolle über Frame‑Transformationen in Ihrer Anwendung zu erhöhen. |
| [rotate_flip_all(rotate_flip)](#rotate_flip_all_rotate_flip_105) | Dreht das gesamte Flip. |
| save() | Speichert die Bilddaten in den zugrunde liegenden Stream. |
| [save(file_path)](#save_file_path_106) | Speichert das Bild am angegebenen Dateipfad. |
| [save(file_path, options)](#save_file_path_options_107) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_108) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(file_path, over_write)](#save_file_path_over_write_109) | Speichert die Daten des Objekts am angegebenen Speicherort. |
| [save(stream)](#save_stream_110) | Speichert die Daten. |
| [save(stream, options_base)](#save_stream_options_base_111) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_112) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_113) | Speichert die 32‑Bit‑ARGB‑Pixel. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_114) | Speichert die Pixel. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_115) | Speichert die Pixel.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) Methode. |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_116) | Speichert die Pixel intern im Hauptspeicher. |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_117) | Speichert die Rohdaten. |
| [save_to_stream(stream)](#save_to_stream_stream_118) | Speichert die Daten des Objekts in den angegebenen Stream. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_119) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_120) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_121) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_122) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_123) | Setzt ein 32‑Bit‑ARGB‑Pixel des Bildes für die angegebene Position. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_124) | Setzt die Bildpalette. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_125) | Setzt ein Bildpixel für die angegebene Position. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_126) | Setzt die Auflösung für dieses [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_127) | Versucht, eine _metadata_-Instanz zu setzen, falls diese [Image](/imaging/python-net/aspose.imaging/image/)‑Instanz unterstützt und eine [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)‑Instanz implementiert. |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_128) | Schreibt die gesamte Scanzeile in den angegebenen Scanzeilen‑Index. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_129) | Schreibt die gesamte Scanzeile in den angegebenen Scanzeilen‑Index. |


### Constructor: WebPImage(path) {#WebPImage_path_1}


```
 WebPImage(path) 
```

Instanziieren Sie eine neue Instanz der Klasse [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/), initialisiert <br/>            aus einer bereitgestellten Dateiquelle. Verwenden Sie diesen Konstruktor, um WebP-<br/>            Bildobjekte direkt aus Dateien nahtlos zu erstellen und den Ladevorgang sowie die<br/>            Manipulation von WebP-Bilddaten in Ihrer Anwendung zu optimieren.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Pfad | string | Der Pfad zur WebP‑Bilddatei |


**See also:**

**[Example # 1](#example_164)**: This example shows how to load a WebP image from a file and save it to PNG.


### Constructor: WebPImage(path, load_options) {#WebPImage_path_load_options_2}


```
 WebPImage(path, load_options) 
```

Erstellen Sie eine neue Instanz der Klasse [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) mithilfe einer Datei und <br/>            angegebenen Ladeoptionen, um eine flexible Handhabung von WebP-Bilddaten zu ermöglichen. Verwenden Sie <br/>            diesen Konstruktor, um WebP-Bildobjekte nahtlos aus Dateien zu initialisieren und dabei <br/>            die Ladevorgänge gemäß den Anforderungen Ihrer Anwendung anzupassen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Pfad | string | Der Pfad zur WebP‑Bilddatei |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Die Ladeoptionen. |

### Constructor: WebPImage(raster_image) {#WebPImage_raster_image_3}


```
 WebPImage(raster_image) 
```

Instanziieren Sie eine neue Instanz der Klasse [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/), initialisiert <br/>            aus einem bereitgestellten rasterImage-Objekt. Dieser Konstruktor ermöglicht eine nahtlose <br/>            Konvertierung von Rasterbildern in das WebP-Format und unterstützt eine effiziente Handhabung sowie <br/>            Manipulation von Bilddaten in Ihrer Anwendung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Rasterbild. |


**See also:**

**[Example # 1](#example_166)**: This example shows how to create a WebP image from another raster image.


### Constructor: WebPImage(raster_image, load_options) {#WebPImage_raster_image_load_options_4}


```
 WebPImage(raster_image, load_options) 
```

Erstellen Sie eine neue Instanz der Klasse [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) mithilfe eines rasterImage-Objekts und <br/>            angegebenen Ladeoptionen, um eine flexible Handhabung von Bilddaten zu ermöglichen. Verwenden Sie diesen <br/>            Konstruktor, um WebP-Bildobjekte nahtlos aus Rasterbildern zu initialisieren und dabei <br/>            die Ladevorgänge gemäß den Anforderungen Ihrer Anwendung anzupassen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Rasterbild. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Die Ladeoptionen. |

### Constructor: WebPImage(stream) {#WebPImage_stream_5}


```
 WebPImage(stream) 
```

Instanziieren Sie eine neue Instanz der [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) Klasse, initialisiert <br/>            aus einer bereitgestellten Stream-Quelle. Verwenden Sie diesen Konstruktor, um nahtlos WebP <br/>            Bildobjekte direkt aus Streams zu erstellen, wodurch eine effiziente Handhabung und Manipulation <br/>            von WebP-Bilddaten in Ihrer Anwendung ermöglicht wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der WebP‑Bild‑Stream. |


**See also:**

**[Example # 1](#example_165)**: This example shows how to load a WebP image from a file stream and save it to...


### Constructor: WebPImage(stream, load_options) {#WebPImage_stream_load_options_6}


```
 WebPImage(stream, load_options) 
```

Erstellen Sie eine neue Instanz der [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) Klasse aus einem Stream,  <br/>            unter Einbeziehung der angegebenen Ladeoptionen und Speicherverwaltungseinstellungen. Dieser <br/>            Konstruktor bietet Flexibilität beim Laden von WebP-Bildern aus Streams, während er <br/>            Speicherressourcen effizient verwaltet und so optimale Leistung und Ressourcennutzung <br/>            in Ihrer Anwendung sicherstellt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der WebP‑Bild‑Stream. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Die Ladeoptionen. |

### Constructor: WebPImage(width, height, options) {#WebPImage_width_height_options_7}


```
 WebPImage(width, height, options) 
```

Instanziieren Sie eine neue Instanz der [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) Klasse mit einem leeren <br/>            Bild mit angegebenen Breiten- und Höhenmaßen. Dieser Konstruktor ermöglicht die <br/>            Erstellung leerer WebP-Bilder und bietet eine Grundlage für nachfolgende Bild-<br/>            Manipulationen und Inhaltserzeugung in Ihrer Anwendung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | int | Die Bildbreite |
| height | int | Die Bildhöhe. |
| options | [WebPOptions](/imaging/python-net/aspose.imaging.imageoptions/webpoptions/) | Die Optionen. |


**See also:**

**[Example # 1](#example_167)**: This example shows how to create a WebP image with the specified options from...


### Constructor: WebPImage(width, height, options, load_options) {#WebPImage_width_height_options_load_options_8}


```
 WebPImage(width, height, options, load_options) 
```

Erstellen Sie eine neue Instanz der [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) Klasse mit einem leeren Bild und angegebenen <br/>            Ladeoptionen. Dieser Konstruktor ermöglicht die Initialisierung von WebP-Bildern mit <br/>            anpassbaren Ladeparametern und bietet Flexibilität bei der Bild­erstellung und <br/>            -manipulation in Ihrer Anwendung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | int | Die Bildbreite |
| height | int | Die Bildhöhe. |
| options | [WebPOptions](/imaging/python-net/aspose.imaging.imageoptions/webpoptions/) | Die Optionen. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Die Ladeoptionen. |

### Property: has_alpha {#has_alpha1}

Ermitteln Sie, ob das Bild einen Alpha-Kanal enthält, was auf das Vorhandensein von <br/>            Transparenzinformationen hinweist. Verwenden Sie diese Eigenschaft, um festzustellen, ob das Bild <br/>            Transparenz enthält, und ermöglichen Sie eine geeignete Handhabung und Verarbeitung von <br/>            Alpha-bezogenen Vorgängen in Ihrer Anwendung.

**See also:**

**[Example # 1](#example_168)**: The following example loads a WEBP image and prints information about raw dat...


### Method: add_block(block) {#add_block_block_1}


```
 add_block(block) 
```

Fügen Sie dem Bild einen neuen WebP-Block hinzu, um dessen Inhalt zu erweitern und <br/>            fortgeschrittene Bildmanipulation zu ermöglichen. Integrieren Sie diese Methode, um dynamisch <br/>            die Struktur und Komplexität der WebP-Bilddaten in Ihrer <br/>            Anwendung zu verbessern, wodurch eine präzise Steuerung und Optimierung der Bilddarstellung ermöglicht wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| block | [IFrame](/imaging/python-net/aspose.imaging.fileformats.webp/iframe/) | Der hinzuzufügende WebP‑Block. |

### Method: add_page(page) {#add_page_page_2}


```
 add_page(page) 
```

Fügen Sie dem Bild eine neue Seite hinzu, um dessen Inhalt zu erweitern und zusätzliche <br/>            visuelle Elemente zu integrieren. Integrieren Sie diese Methode, um die dynamische Seitenverwaltung <br/>            in Ihrer Anwendung zu erleichtern, wodurch die nahtlose Erstellung und Erweiterung von mehrseitigen <br/>            Dokumenten oder Bildern ermöglicht wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Die hinzuzufügende Seite. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_3}


```
 adjust_brightness(brightness) 
```

Implementieren Sie die _Helligkeits_‑Anpassung für das Bild, um die <br/>            Gesamthelligkeitswerte zu verändern. Integrieren Sie diese Methode in Ihren Bild‑<br/>            Verarbeitung‑Workflow, um die Sichtbarkeit zu erhöhen und die visuelle Qualität von Bildern <br/>            in Ihrer Anwendung zu verbessern.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Helligkeit | int | Helligkeitswert. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_4}


```
 adjust_contrast(contrast) 
```

Verbessern Sie den Kontrast des [Image](/imaging/python-net/aspose.imaging/image/), indem Sie die <br/>            Unterschiede zwischen hellen und dunklen Bereichen verstärken. Integrieren Sie diese Methode in Ihren Bild‑<br/>            Verarbeitung‑Workflow, um die visuelle Klarheit und die Gesamtbildqualität in Ihrer <br/>            Anwendung zu erhöhen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Kontrast | float | Kontrastwert (im Bereich [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_5}


```
 adjust_gamma(gamma) 
```

Wenden Sie eine Gammakorrektur auf das Bild an, um die Pixelintensitäten anzupassen und die gewünschte Helligkeit sowie Farbbalance zu erreichen. Integrieren Sie diese Methode in Ihren Bild‑<br/>            Verarbeitung‑Workflow, um die visuelle Qualität zu verbessern und die Genauigkeit von <br/>            nachfolgenden Analyse‑ oder Anzeigeaufgaben in Ihrer Anwendung zu erhöhen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Gamma | float | Gamma‑Koeffizient für die Rot‑, Grün‑ und Blaukanäle |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_6}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Führen Sie eine Gammakorrektur am Bild durch, indem Sie einzelne Koeffizienten für die roten, <br/>            grünen und blauen Kanäle verwenden, um fein abgestimmte Anpassungen von Farbbalance und <br/>            Kontrast zu ermöglichen. Integrieren Sie diese Methode in Ihre Bildverarbeitungspipeline, um <br/>            eine präzise Kontrolle über die Farbdarstellung zu erreichen und die visuelle Treue in Ihrer <br/>            Anwendung zu verbessern.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| gamma_red | float | Gamma‑Koeffizient für den Rotkanal |
| gamma_green | float | Gamma‑Koeffizient für den Grünkanal |
| gamma_blue | float | Gamma für den Blaukanal-Koeffizienten |

### Method: analyze_percentage_digital_signature(password) {#analyze_percentage_digital_signature_password_7}


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


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_8}


```
 binarize_bradley(brightness_difference) 
```

Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild-Schwellenwertbestimmung

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brightness_difference | float | Der Helligkeitsunterschied zwischen dem Pixel und dem Durchschnitt eines s x s Fensters von Pixeln<br/>                das um dieses Pixel zentriert ist. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_9}


```
 binarize_bradley(brightness_difference, window_size) 
```

Wenden Sie die Binarisierung auf das Bild an, indem Sie Bradleys adaptiven Schwellenwertalgorithmus <br/>            mit Integralbild‑Schwellwertbildung verwenden. Diese Methode berechnet dynamisch lokale <br/>            Schwellenwerte basierend auf der Nachbarschaft des Bildes, verbessert die Anpassungsfähigkeit an unterschiedliche <br/>            Lichtverhältnisse und sorgt für eine robuste Segmentierung für nachfolgende Verarbeitungs‑<br/>            aufgaben in Ihrer Anwendung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brightness_difference | float | Der Helligkeitsunterschied zwischen dem Pixel und dem Durchschnitt eines s x s Fensters von Pixeln<br/>            das um dieses Pixel zentriert ist. |
| window_size | int | Die Größe des s x s Fensters von Pixeln, das um dieses Pixel zentriert ist. |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_10}


```
 binarize_fixed(threshold) 
```

Führen Sie die Binarisierung des Bildes mit einem vordefinierten Schwellenwert durch, indem Sie es in ein binäres Bild umwandeln, bei dem Pixel basierend auf ihrer Intensität relativ zum Schwellenwert als Vorder‑ oder Hintergrund klassifiziert werden. Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um Segmentierungs‑ und Merkmalextraktions‑aufgaben zu erleichtern und die Genauigkeit sowie Effizienz nachfolgender Analysen in Ihrer <br/>            Anwendung zu steigern.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Schwellenwert | System.Byte | Schwellenwert. Wenn der entsprechende Grauwert eines Pixels größer als der Schwellenwert ist, wird ihm ein Wert von<br/>            255 zugewiesen, sonst 0. |

### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_11}


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

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_12}


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

### Method: can_load(file_path)  [static] {#can_load_file_path_13}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_14}


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


### Method: can_load(stream)  [static] {#can_load_stream_15}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_16}


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


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_17}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_18}


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


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_19}


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


### Method: can_save(options) {#can_save_options_20}


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


### Method: create(files)  [static] {#create_files_21}


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


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_22}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_23}


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


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_24}


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


### Method: create(images)  [static] {#create_images_25}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_26}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_27}


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


### Method: create_from_file_with_options(path, load_options)  [static] {#create_from_file_with_options_path_load_options_28}


```
 create_from_file_with_options(path, load_options) 
```

Initialisiert eine neue Instanz der [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) Klasse aus einer Datei.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Pfad | string | Der Pfad zur WebP‑Bilddatei |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Die Ladeoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: create_from_files(files)  [static] {#create_from_files_files_29}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_30}


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


### Method: create_from_image(raster_image)  [static] {#create_from_image_raster_image_31}


```
 create_from_image(raster_image) 
```

Initialisiert eine neue Instanz der [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) Klasse aus rasterImage.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Rasterbild. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: create_from_image_with_options(raster_image, load_options)  [static] {#create_from_image_with_options_raster_image_load_options_32}


```
 create_from_image_with_options(raster_image, load_options) 
```

Initialisiert eine neue Instanz der [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) Klasse aus rasterImage.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Rasterbild. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Die Ladeoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: create_from_images(images)  [static] {#create_from_images_images_33}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_34}


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


### Method: create_from_stream(stream)  [static] {#create_from_stream_stream_35}


```
 create_from_stream(stream) 
```

Initialisiert eine neue Instanz der [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) Klasse<br/>                aus einem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der WebP‑Bild‑Stream. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: create_from_stream_with_options(stream, load_options)  [static] {#create_from_stream_with_options_stream_load_options_36}


```
 create_from_stream_with_options(stream, load_options) 
```

Initialisiert eine neue Instanz der [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) Klasse aus einem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der WebP‑Bild‑Stream. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Die Ladeoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_37}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Beschneiden Sie das Bild, indem Sie linke, rechte, obere und untere Verschiebungen anwenden und so <br/>            effektiv einen Interessensbereich im Bild auswählen. Verwenden Sie diese Methode, um <br/>            gewünschte Bildbereiche dynamisch zu extrahieren und gleichzeitig die Zusammensetzung <br/>            und den Fokus gemäß den Anforderungen Ihrer Anwendung anzupassen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| left_shift | int | Die linke Verschiebung. |
| right_shift | int | Die rechte Verschiebung. |
| top_shift | int | Die obere Verschiebung. |
| bottom_shift | int | Die untere Verschiebung. |

### Method: crop(rectangle) {#crop_rectangle_38}


```
 crop(rectangle) 
```

Beschneiden Sie das Bild mithilfe eines angegebenen Rechteckbereichs und entfernen Sie unerwünschte Teile <br/>            bei gleichzeitiger Beibehaltung des gewünschten Inhalts. Integrieren Sie diese Methode in Ihren Bild‑<br/>            Verarbeitung‑Workflow, um gezielt bestimmte Interessensbereiche im Bild zu extrahieren und zu fokussieren, wodurch Klarheit und Zusammensetzung für verschiedene Anwendungen verbessert werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_39}


```
 dither(dithering_method, bits_count) 
```

Führt Dithering auf dem aktuellen Bild aus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Die Dithering-Methode. |
| bits_count | int | Die endgültige Bitanzahl für das Dithern. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_40}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Führen Sie Dithering auf dem aktuellen Bild durch, um Farbbänderungen zu reduzieren und die visuelle <br/>            Qualität zu verbessern. Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um <br/>            sanftere Übergänge zwischen den Farben zu erzielen und das Gesamterscheinungsbild des <br/>            Bildes in Ihrer Anwendung zu verbessern.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Die Dithering-Methode. |
| bits_count | int | Die endgültige Bitanzahl für das Dithern. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die benutzerdefinierte Palette für das Dithern. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_41}


```
 embed_digital_signature(password) 
```

Betten Sie eine digitale Signatur, basierend auf dem angegebenen Passwort, in jede Seite des Bildes ein.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Passwort | string | Das Passwort, das zum Erzeugen digitaler Signaturdaten verwendet wird |

### Method: filter(rectangle, options) {#filter_rectangle_options_42}


```
 filter(rectangle, options) 
```

Filtern Sie den Inhalt innerhalb des angegebenen Rechtecks und wenden Sie einen festgelegten Bild‑<br/>            Verarbeitungsfilter an, um den ausgewählten Bereich zu verbessern oder zu verändern. Integrieren Sie diese Methode <br/>            in Ihren Bildbearbeitungs‑Workflow, um gezielte Verbesserungen oder <br/>            Transformationen in Ihrer Anwendung zu erreichen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Die Optionen. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_43}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_44}


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


### Method: get_default_options(args) {#get_default_options_args_45}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_46}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Liefert das Standard‑Pixel‑Array mittels teilweisem Pixel‑Lader.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, für das die Pixel abgerufen werden. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Der partielle Pixel‑Lader. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_47}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_48}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_49}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_50}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_51}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_52}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_53}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_54}


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


### Method: get_original_options() {#get_original_options__55}


```
 get_original_options() 
```

Liefert die Optionen basierend auf den ursprünglichen Dateieinstellungen.<br/>            Dies kann hilfreich sein, um die Bit‑Tiefe und andere Parameter des Originalbildes unverändert zu lassen.<br/>            Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es anschließend mit der<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/)‑Methode speichern, wird ein PNG‑Ausgabebild mit 8 Bit pro Pixel erzeugt.<br/>            Um dies zu vermeiden und ein PNG‑Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und übergeben Sie sie<br/>            an die [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/)‑Methode als zweiten Parameter.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Optionen basierend auf den ursprünglichen Dateieinstellungen. |


### Method: get_pixel(x, y) {#get_pixel_x_y_56}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_57}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_58}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_59}


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


### Method: get_skew_angle() {#get_skew_angle__60}


```
 get_skew_angle() 
```

Liefert den Schrägungswinkel.<br/>            Diese Methode ist auf gescannte Textdokumente anwendbar, um den Schrägungswinkel beim Scannen zu bestimmen.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float | Der Schrägwinkel in Grad. |


### Method: insert_block(index, block) {#insert_block_index_block_61}


```
 insert_block(index, block) 
```

Fügen Sie einen neuen WebP‑Block an dem angegebenen Index im Bild ein, um eine präzise <br/>            Kontrolle über die Blocksequenz zu ermöglichen. Integrieren Sie diese Methode, um nahtlos <br/>            zusätzliche WebP‑Blöcke in die Bilddatenstruktur einzufügen, was fortgeschrittene Bild‑<br/>            Verarbeitung und Optimierung in Ihrer Anwendung erleichtert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Das nullbasierte Element, an dem _block_ eingefügt wird<br/>                . |
| block | [IFrame](/imaging/python-net/aspose.imaging.fileformats.webp/iframe/) | Der hinzuzufügende WebP‑Block. |

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

Lädt die Daten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der WebP‑Bild‑Stream. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Die Ladeoptionen |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) |  |


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

Normalisiert den Winkel.<br/>            Diese Methode ist auf gescannte Textdokumente anwendbar, um die schiefe Aufnahme zu korrigieren.<br/>            Diese Methode verwendet die Methoden [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) und [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/).

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


### Method: remove_block(block) {#remove_block_block_83}


```
 remove_block(block) 
```

Entfernt den angegebenen WebP‑Block aus dem Bild und erleichtert so die effiziente Verwaltung <br/>            der Bilddatenstruktur. Verwenden Sie diese Methode, um Bildverarbeitungs‑Workflows zu optimieren, <br/>            indem Sie unnötige Blöcke oder Komponenten in Ihrer Anwendung entfernen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| block | [IFrame](/imaging/python-net/aspose.imaging.fileformats.webp/iframe/) | Der Block zum Entfernen. |

### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_84}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_85}


```
 replace_color(old_color, old_color_diff, new_color) 
```

Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| old_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |
| old_color_diff | System.Byte | Erlaubte Differenz im alten Farbwert, um den ersetzten Farbton zu erweitern. |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_86}


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

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_87}


```
 replace_non_transparent_colors(new_color) 
```

Ersetzt alle nicht‑transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.<br/>                Hinweis: Wenn Sie dies bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_88}


```
 replace_non_transparent_colors(new_color_argb) 
```

Ersetzt alle nicht‑transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.<br/>                Hinweis: Wenn Sie dies bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_color_argb | int | Neuer ARGB-Farbwert, um nicht-transparente Farben zu ersetzen. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_89}


```
 resize(new_width, new_height) 
```

Skaliert das Bild. Der Standardwert [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_90}


```
 resize(new_width, new_height, resize_type) 
```

Skaliert das Bild, wobei die Abmessungen angepasst und das Seitenverhältnis beibehalten werden. <br/>            Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um Bilder dynamisch zu skalieren, <br/>            sodass sie verschiedenen Anzeige‑ oder Speicheranforderungen in Ihrer Anwendung entsprechen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Der Skalierungstyp. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_91}


```
 resize(new_width, new_height, settings) 
```

Skaliert das Bild gemäß den angegebenen Einstellungen und ermöglicht eine präzise Kontrolle über <br/>            Abmessungen, Seitenverhältnis und Skalierungsverhalten. Integrieren Sie diese Methode in Ihren <br/>            Bildverarbeitungs‑Workflow, um benutzerdefinierte Skalierungsoperationen zu realisieren, die auf die <br/>            spezifischen Anforderungen Ihrer Anwendung zugeschnitten sind.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Skalierungseinstellungen. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_92}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_93}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_94}


```
 resize_height_proportionally(new_height) 
```

Skaliert die Höhe proportional. Der Standard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_95}


```
 resize_height_proportionally(new_height, resize_type) 
```

Passen Sie die Höhe des Bildes proportional an, während das Seitenverhältnis für ein konsistentes Skalieren beibehalten wird. <br/>            Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um Bilder dynamisch mit einheitlichen Proportionen zu skalieren und so eine optimale Anzeige oder <br/>            Speicherung in Ihrer Anwendung sicherzustellen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ der Skalierung. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_96}


```
 resize_height_proportionally(new_height, settings) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Bildskalierungseinstellungen. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_97}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Bildskalierungseinstellungen. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_98}


```
 resize_width_proportionally(new_width) 
```

Skaliert die Breite proportional. Der Standard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_99}


```
 resize_width_proportionally(new_width, resize_type) 
```

Passen Sie die Breite des Bildes proportional an und behalten Sie dabei das Seitenverhältnis bei. <br/>            Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um Bilder dynamisch mit konsistenten Proportionen zu skalieren und so eine optimale Anzeige oder Speicherung in <br/>            Ihrer Anwendung zu gewährleisten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ der Skalierung. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_100}


```
 resize_width_proportionally(new_width, settings) 
```

Skaliert die Breite proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Bildskalierungseinstellungen. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_101}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Skaliert die Breite proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Bildskalierungseinstellungen. |

### Method: rotate(angle) {#rotate_angle_102}


```
 rotate(angle) 
```

Bild um das Zentrum drehen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_103}


```
 rotate(angle, resize_proportionally, background_color) 
```

Drehen Sie das Bild um sein Zentrum um einen angegebenen Winkel, während Sie es proportional <br/>            skalieren und die angegebenen Hintergrundfarbparameter anwenden. Integrieren Sie diese <br/>            Methode in Ihren Bildverarbeitungs‑Workflow, um präzise Transformationen mit <br/>            anpassbaren Hintergrundfarben zu erzielen und so eine optimale visuelle Darstellung in Ihrer <br/>            Anwendung sicherzustellen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |
| resize_proportionally | bool | wenn auf <c>true</c> gesetzt, wird die Bildgröße geändert<br/>            entsprechend den Projektionen des gedrehten Rechtecks (Eckpunkte) im anderen<br/>            Fall bleiben die Abmessungen unverändert und nur<br/>            __internal__ Bildinhalte werden gedreht. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Farbe des Hintergrunds. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_104}


```
 rotate_flip(rotate_flip_type) 
```

Wenden Sie Rotation, Spiegelung oder beide Operationen ausschließlich auf den aktiven Frame <br/>            im Bild an. Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um <br/>            eine präzise Manipulation einzelner Frames zu ermöglichen, die Flexibilität und <br/>            Kontrolle über Frame‑Transformationen in Ihrer Anwendung zu erhöhen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Der Rotations-Flip-Typ. |

### Method: rotate_flip_all(rotate_flip) {#rotate_flip_all_rotate_flip_105}


```
 rotate_flip_all(rotate_flip) 
```

Dreht das gesamte Flip.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rotate_flip | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Der Rotations-Flip. |

### Method: save(file_path) {#save_file_path_106}


```
 save(file_path) 
```

Speichert das Bild am angegebenen Dateipfad.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem das Bild gespeichert wird. |

### Method: save(file_path, options) {#save_file_path_options_107}


```
 save(file_path, options) 
```

Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Optionen. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_108}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_109}


```
 save(file_path, over_write) 
```

Speichert die Daten des Objekts am angegebenen Speicherort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Objektdaten gespeichert werden. |
| over_write | bool | wenn auf <c>true</c> gesetzt, werden die Dateiinhalte überschrieben, andernfalls wird angehängt. |

### Method: save(stream) {#save_stream_110}


```
 save(stream) 
```

Speichert die Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in den Bilddaten gespeichert werden. |

### Method: save(stream, options_base) {#save_stream_options_base_111}


```
 save(stream, options_base) 
```

Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem die Bilddaten gespeichert werden. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Speicheroptionen. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_112}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_113}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Speichert die 32‑Bit‑ARGB‑Pixel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, in dem Pixel gespeichert werden. |
| Pixel | int[] | Das 32‑Bit‑ARGB‑Pixel‑Array. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_114}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Speichert die Pixel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, in dem Pixel gespeichert werden. |
| Pixel | int[] | Die CMYK‑Pixel, dargestellt als 32‑Bit‑Ganzzahlwerte. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_115}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Speichert die Pixel.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) Methode.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, in dem Pixel gespeichert werden. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Das CMYK‑Pixel‑Array. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_116}


```
 save_pixels(rectangle, pixels) 
```

Speichert die Pixel intern im Hauptspeicher.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Die Pixel. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_117}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_118}


```
 save_to_stream(stream) 
```

Speichert die Daten des Objekts in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem die Daten des Objekts gespeichert werden sollen. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_119}


```
 save_to_stream_with_options(stream, options_base) 
```

Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem die Bilddaten gespeichert werden. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Speicheroptionen. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_120}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_121}


```
 save_with_options(file_path, options) 
```

Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Optionen. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_122}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_123}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_124}


```
 set_palette(palette, update_colors) 
```

Setzt die Bildpalette.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die zu setzende Palette. |
| update_colors | bool | Wenn auf <c>true</c> gesetzt, werden die Farben gemäß der neuen Palette aktualisiert; andernfalls bleiben die Farbindizes unverändert. Hinweis: Unveränderte Indizes können das Bild beim Laden zum Absturz bringen, wenn einige Indizes keinen entsprechenden Paletteneintrag haben. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_125}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_126}


```
 set_resolution(dpi_x, dpi_y) 
```

Setzt die Auflösung für dieses [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dpi_x | float | Die horizontale Auflösung in Punkten pro Zoll des [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | Die vertikale Auflösung in Punkten pro Zoll des [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_127}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_128}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Schreibt die gesamte Scanzeile in den angegebenen Scanzeilen‑Index.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| scan_line_index | int | Nullbasierter Index der Scan-Zeile. |
| argb_32_pixels | int[] | Das 32‑Bit‑ARGB‑Farben‑Array zum Schreiben. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_129}


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
### This example shows how to load a WebP image from a file and save it to PNG. {#example_164}
``` python

import aspose.pycore as aspycore
from aspose.imaging.fileformats.webp import WebPImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
# Laden Sie ein WebP‑Bild aus einer Datei.
with WebPImage(join(dir_, "test.webp")) as web_pimage:
	# Als PNG speichern
	# Beachten Sie, dass nur der aktive Frame als PNG gespeichert wird, da PNG kein Mehrseitenformat ist.
	web_pimage.save(join(dir_, "test.output.png"), PngOptions())


```

### This example shows how to load a WebP image from a file stream and save it to PNG. {#example_165}
``` python

import aspose.pycore as aspycore
from aspose.imaging.fileformats.webp import WebPImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp"
# Laden Sie ein WebP‑Bild aus einem Dateistream.
with open(join(dir_, "test.webp"), "w+b") as stream:
	with WebPImage(stream) as web_pimage:
		# Als PNG speichern
		# Beachten Sie, dass nur der aktive Frame als PNG gespeichert wird, da PNG kein Mehrseitenformat ist.
		web_pimage.save(join(dir_, "test.output.png"), PngOptions())


```

### This example shows how to create a WebP image from another raster image. {#example_166}
``` python
from os.path import join
from aspose.imaging import Graphics, Color
from aspose.imaging.fileformats.png import PngImage
from aspose.imaging.fileformats.webp import WebPImage
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import WebPOptions      

dir_: str = "c:\\temp"
# Laden Sie ein PNG‑Bild mit 100 × 100 px.
with PngImage(100, 100) as png_image:
	graphics = Graphics(png_image)
	# Füllen Sie das gesamte Bild mit Rot.
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	# Erstellen Sie ein WebP‑Bild basierend auf dem PNG‑Bild.
	with WebPImage(png_image) as web_pimage:
		# Speichern in einer WebP-Datei mit Standardoptionen
		web_pimage.save(join(dir_, "output.webp"), WebPOptions())


```

### This example shows how to create a WebP image with the specified options from scratch. {#example_167}
``` python
from aspose.imaging.fileformats.webp import WebPImage
from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import WebPOptions
from os.path import join


dir_: str = "c:\\temp"
create_options = WebPOptions()
create_options.lossless = True
create_options.quality = 100.0

# Ein WebP-Bild mit 100x100 px erstellen.
with WebPImage(100, 100, create_options) as web_pimage:
	graphics = Graphics(web_pimage)
	# Füllen Sie das gesamte Bild mit Rot.
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, web_pimage.bounds)
	# In einer WebP-Datei speichern
	web_pimage.save(join(dir_, "output.webp"))


```

### The following example loads a WEBP image and prints information about raw data format and alpha channel. {#example_168}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.webp import WebPImage, WebPFrameBlock

dir_ = "c:\\temp"
file_name = dir_ + "sample.webp"
with Image.load(file_name) as image:
	webp_image = aspycore.as_of(image, WebPImage)
	# Wenn der aktive TIFF-Frame einen Alpha-Kanal hat, wird das gesamte TIFF-Bild als Alpha-Kanal enthaltend betrachtet.
	print(f"ImageFile={file_name}, FileFormat={webp_image.raw_data_format}, HasAlpha={webp_image.has_alpha}")
	i: int = 0
	for frame in webp_image.blocks:
		if aspycore.is_assignable(frame, WebPFrameBlock):
			frame_block = aspycore.as_of(frame, WebPFrameBlock)
			print(f"Frame={i}, FileFormat={frame_block.raw_data_format}, HasAlpha={frame_block.has_alpha}")
			i += 1

# Die Ausgabe könnte folgendermaßen aussehen:
# ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, verwendete Kanäle: 1, HasAlpha=False
# Frame=0, FileFormat=RgbIndexed1Bpp, verwendete Kanäle: 1, HasAlpha=False


```

