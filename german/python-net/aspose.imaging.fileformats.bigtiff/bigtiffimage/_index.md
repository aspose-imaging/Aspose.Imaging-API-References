---
title: "BigTiffImage Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/
---

**Summary:** With the [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) class you can effortlessly manipulate<br/>            BigTiff image format files. Our API offering seamless handling and customization<br/>            options, ensuring optimal processing of large-scale image data with versatile features<br/>            tailored to your specific requirements.

**Module:** [aspose.imaging.fileformats.bigtiff](/imaging/python-net/aspose.imaging.fileformats.bigtiff/)

**Full Name:** aspose.imaging.fileformats.bigtiff.BigTiffImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IMultipageImage, IMultipageImageExt, TiffImage

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [BigTiffImage(frame)](#BigTiffImage_frame_1) | Erstellen Sie eine neue Instanz der [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) Klasse, indem Sie sie mit einem TiffFrame-Parameter initialisieren<br/>            . Ideal für Entwickler, die eine bequeme<br/>            Möglichkeit suchen, mit BigTiffImage-Objekten zu arbeiten, und dabei Flexibilität und einfache Integration<br/>            in ihre Projekte gewährleisten. |
| [BigTiffImage(frames)](#BigTiffImage_frames_2) | Beginnen Sie mit der nahtlosen Nutzung der [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) Klasse, indem Sie<br/>            eine neue Instanz mit einer Liste von TiffFrames-Parameter initialisieren.<br/>            Perfekt für Entwickler, die eine unkomplizierte Methode suchen, um mit<br/>            BigTiffImage-Objekten zu arbeiten, die mehrere Frames enthalten, und dabei die Effizienz ihrer Projekte sicherstellen. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| active_frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | r/w | Verwalten Sie den aktiven Frame nahtlos und ermöglichen dabei dynamische Navigation und <br/>            Manipulation im vorgesehenen Kontext. Ermöglichen Sie Ihrer Anwendung, effizient mit Multimedia-Inhalten zu interagieren, und steigern Sie das Nutzerengagement sowie die Produktivität. |
| auto_adjust_palette | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die automatische Anpassung der Palette erfolgt. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Liest oder setzt einen Wert für die Hintergrundfarbe. |
| bits_per_pixel | int | r | Liest die Bit‑Pro‑Pixel‑Anzahl des Bildes. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Liest die Objektgrenzen. |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | r/w | Schalten Sie die Byte-Reihenfolge für TIFF-Dateien nahtlos um und gewährleisten dabei eine präzise Kontrolle über <br/>            die Dateninterpretation. Rüsten Sie Ihre Anwendungen mit der Flexibilität aus, sich an <br/>            verschiedene Dateispezifikationen anzupassen, und verbessern Sie die Kompatibilität sowie die Effizienz bei der Datenverarbeitung. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Liest den [Image](/imaging/python-net/aspose.imaging/image/) Container. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Liest den Datenstrom des Objekts. |
| freigegeben | bool | r | Liest einen Wert, der angibt, ob diese Instanz freigegeben ist. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Liest oder setzt die Exif‑Instanz. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Ermittelt das Dateiformat dieser [Image](/imaging/python-net/aspose.imaging/image/) Instanz. |
| frames | [TiffFrame[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | r | Rufen Sie ein Array von [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) Instanzen ab, das umfassenden <br/>            Zugriff und Manipulation einzelner Frames innerhalb des TIFF-Bildes ermöglicht. Nutzen Sie die <br/>            Leistungsfähigkeit dieses Arrays, um Bildverarbeitungs‑Workflows zu optimieren, und gewährleisten Sie präzise <br/>            Kontrolle sowie Optimierung visueller Inhalte. |
| has_alpha | bool | r | Bestimmen Sie, ob das Bild einen Alpha-Kanal besitzt, und liefern damit entscheidende Informationen <br/>            für Rendering- und Compositing‑Operationen. Integrieren Sie diese Funktion, um visuelle Verarbeitungs‑Workflows zu optimieren, und gewährleisten Sie eine genaue Darstellung sowie Manipulation transparenter Elemente. |
| has_background_color | bool | r/w | Liest oder setzt einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| has_transparent_color | bool | r/w | Liest einen Wert, der angibt, ob das Bild eine transparente Farbe hat. |
| height | int | r | Liefert die Objekt­höhe. |
| horizontal_resolution | float | r/w | Rufen Sie die horizontale Auflösung des angegebenen [Image](/imaging/python-net/aspose.imaging/image/) in Pixeln <br/>            pro Zoll ab, um präzise Anpassungen und Rendering‑Fähigkeiten zu ermöglichen. Greifen Sie mühelos auf wichtige Bild‑Metadaten zu und unterstützen Sie optimierte Bildverarbeitungs‑Workflows für verbesserte Benutzererlebnisse. |
| image_opacity | float | r | Liest die Opazität dieses Bildes. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Liest oder setzt den Interrupt-Monitor. |
| is_cached | bool | r | Liest einen Wert, der angibt, ob Bilddaten derzeit zwischengespeichert sind. |
| is_raw_data_available | bool | r | Liest einen Wert, der angibt, ob das Laden von Rohdaten unterstützt wird. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Liest oder setzt XMP-Daten aus dem Frame. |
| page_count | int | r | Ermitteln Sie die Gesamtzahl der Seiten im angegebenen Dokument, um <br/>            eine effiziente Navigation und Verwaltung von mehrseitigem Inhalt zu ermöglichen. Integrieren Sie diese <br/>            Funktion, um die Benutzererfahrung zu verbessern und einen nahtlosen Zugriff auf <br/>            umfassende Dokumentstrukturen zu ermöglichen. |
| pages | [Image[]](/imaging/python-net/aspose.imaging/image/) | r | Greifen Sie nahtlos auf die Seiten des Dokuments zu und ermöglichen dabei dynamische Navigation und <br/>            Manipulation innerhalb der Inhaltsstruktur. Statten Sie Ihre Anwendung mit effizientem <br/>            Zugriff auf einzelne Seiten aus, um die Dokumentenverarbeitung zu optimieren und die Benutzerinteraktion zu verbessern. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Liest oder setzt die Farbpalette. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| premultiply_components | bool | r/w | Geben Sie an, ob Komponenten eine Premultiplikation benötigen, um eine effiziente Handhabung <br/>            visueller Elemente zu gewährleisten. Verbessern Sie Rendering‑Prozesse, indem Sie diese Eigenschaft umschalten, und optimieren Sie Grafik‑Workflows für eine verbesserte Leistung. |
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
| vertical_resolution | float | r/w | Greifen Sie auf die vertikale Auflösung des angegebenen [Image](/imaging/python-net/aspose.imaging/image/) in Pixel pro <br/>            Zoll zu, um präzise Anpassungen und Rendering‑Optimierungen zu ermöglichen. Nutzen Sie wichtige <br/>            Bilddaten mühelos, um Bildverarbeitungs‑Workflows zu optimieren und dabei eine überlegene Qualität sowie Leistung in Ihren Anwendungen sicherzustellen. |
| width | int | r | Liefert die Objekt­breite. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Liest oder setzt XMP-Daten. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add(image)](#add_image_1) | Fügen Sie die Frames des angegebenen Bildes nahtlos in den aktuellen Frame ein, <br/>            konsolidieren deren Inhalt und erhöhen die Flexibilität der Komposition. Integrieren Sie <br/>            diese Methode, um die Frame‑Verwaltung und -Manipulation in Ihrer <br/>            Anwendung zu optimieren und eine effiziente Handhabung von Multi‑Frame‑Bildern zu ermöglichen. |
| [add_frame(frame)](#add_frame_frame_2) | Integrieren Sie den angegebenen Frame nahtlos in das Bild und erweitern dessen Inhalt <br/>            sowie Vielseitigkeit. Nutzen Sie diese Methode, um die Bildkomposition und -verwaltung zu verbessern und eine effiziente Handhabung von Multi‑Frame‑Bildern in Ihrer Anwendung zu ermöglichen. |
| [add_frames(frames)](#add_frames_frames_3) | Integrieren Sie das Frame‑Array nahtlos in das Bild und bereichern dessen Inhalt und <br/>            Vielseitigkeit. Nutzen Sie diese Methode, um die Bildkomposition und -verwaltung zu verbessern und eine effiziente Handhabung von Multi‑Frame‑Bildern in Ihrer Anwendung zu ermöglichen. |
| [add_page(page)](#add_page_page_4) | Erweitern Sie Ihr BigTiff‑Bild mühelos, indem Sie mit dieser intuitiven Methode eine neue Seite hinzufügen.<br/>            Perfekt für Entwickler, die den Inhalt ihrer mehrseitigen Bilder dynamisch erweitern möchten. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_5) | Implementieren Sie die _Helligkeit_‑Anpassung für das Bild, um die <br/>            Modifikation der Gesamthelligkeitswerte zu ermöglichen. Integrieren Sie diese Methode in Ihren Bild‑<br/>            Verarbeitungs‑Workflow, um die Sichtbarkeit zu erhöhen und die visuelle Qualität von <br/>            Bildern in Ihrer Anwendung zu verbessern. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_6) | Verbessern Sie den Kontrast der [Image](/imaging/python-net/aspose.imaging/image/) Instanz, <br/>            indem Sie die Unterschiede zwischen hellen und dunklen Bereichen verstärken. Integrieren Sie diese <br/>            Funktion, um die visuelle Klarheit und die Gesamtqualität des Bildes <br/>            in Ihrer Anwendung zu erhöhen. |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_7) | Wenden Sie eine Gammakorrektur auf das Bild an, passen Sie die Pixelintensitäten an, um das gewünschte Farbgleichgewicht zu erreichen <br/>            . Integrieren Sie diese Methode in Ihren Bildverarbeitungs <br/>            Workflow, um die visuelle Qualität zu verbessern und die Genauigkeit nachfolgender <br/>            Analyse‑ oder Anzeigeaufgaben in Ihrer Anwendung zu erhöhen. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_8) | Führen Sie eine Gammakorrektur am Bild unter Verwendung individueller Koeffizienten für die Rot‑, <br/>            Grün‑ und Blaukanäle durch, um feine Anpassungen des Farbgleichgewichts <br/>            und des Kontrasts zu ermöglichen. Integrieren Sie diese Methode in Ihre Bildverarbeitungspipeline, um <br/>            präzise Kontrolle über die Farbdarstellung zu erreichen und die visuelle Treue in Ihrer <br/>            Anwendung zu erhöhen. |
| align_resolutions() | Implementieren Sie die Hilfsmethode AlignResolutions, um horizontale und <br/>            vertikale Auflösungen zu synchronisieren und damit eine einheitliche Bildgröße zu gewährleisten. Diese Funktionalität <br/>            erleichtert optimierte Bildverarbeitungs‑Workflows, indem Auflösungsparameter <br/>            harmonisiert werden, was die visuelle Qualität und Konsistenz über verschiedene Plattformen und <br/>            Geräte hinweg optimiert. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_9) | Berechnet den prozentualen Ähnlichkeitsgrad zwischen den extrahierten Daten und dem ursprünglichen Passwort. |
| auto_brightness_contrast() | Führt eine automatische adaptive Helligkeits- und Kontrastnormalisierung für das gesamte Bild durch. |
| auto_rotate() | Dreht das Bild automatisch basierend auf den aus den Exif-<br/>            Metadaten extrahierten Orientierungsdaten. Diese Methode stellt sicher, dass Bilder in der korrekten Ausrichtung angezeigt werden, <br/>            verbessert das Benutzererlebnis und eliminiert die Notwendigkeit manueller Anpassungen. Durch <br/>            Analyse der Exif-Informationen wird das Bild entsprechend gedreht, was ein nahtloses <br/>            Anzeigeerlebnis über verschiedene Plattformen und Geräte hinweg ermöglicht. Dieser automatisierte Rotations<br/>            Prozess vereinfacht die Bildverarbeitung und erhöht die Gesamtbenutzerfreundlichkeit, insbesondere bei <br/>            großen Bildmengen mit unterschiedlichen Ausrichtungen. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_10) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild-Schwellenwertbestimmung |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_11) | Implementieren Sie die Binarisierung des Bildes mittels Bradleys adaptivem Schwellenwert‑Algorithmus <br/>            mit Integral‑Bild‑Schwellwertbestimmung. Dieser Ansatz berechnet dynamisch <br/>            lokale Schwellenwerte basierend auf der Nachbarschaft des Bildes, verbessert die Anpassungsfähigkeit an <br/>            unterschiedliche Lichtverhältnisse und sorgt für eine robuste Segmentierung für nachfolgende <br/>            Verarbeitungsschritte in Ihrer Anwendung. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_12) | Wenden Sie die Binarisierung auf das Bild mit einem vordefinierten Schwellenwert an und konvertieren Sie es in <br/>            ein Binärbild mit klaren Vorder‑ und Hintergrundbereichen. Integrieren Sie diese <br/>            Methode in Ihren Bildverarbeitungs‑Workflow, um Segmentierungs‑ und Feature‑Extraktionsaufgaben zu erleichtern und die Genauigkeit sowie Effizienz der Bildanalyse in Ihrer <br/>            Anwendung zu steigern. |
| binarize_otsu() | Verwenden Sie die Otsu‑Schwellwertbestimmung, um das Bild zu binarisieren, wobei automatisch <br/>            der optimale Schwellenwert basierend auf dem Histogramm des Bildes ermittelt wird. Integrieren <br/>            Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um eine effektive Segmentierung <br/>            und Feature‑Extraktion zu erreichen und die Genauigkeit sowie Zuverlässigkeit der Bildanalyse <br/>            Aufgaben in Ihrer Anwendung zu verbessern. |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_13) | Mischt diese Bildinstanz mit dem _overlay_-Bild. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_14) | Mischt diese Bildinstanz mit dem _overlay_-Bild. |
| cache_data() | Zwischenspeichert die Daten privat. |
| [can_load(file_path)](#can_load_file_path_15) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_16) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann und optional die angegebenen Öffnungsoptionen verwendet. |
| [can_load(stream)](#can_load_stream_17) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann. |
| [can_load(stream, load_options)](#can_load_stream_load_options_18) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann und optional die angegebenen _loadOptions_ verwendet. |
| [can_load_stream(stream)](#can_load_stream_stream_19) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_20) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann und optional die angegebenen _loadOptions_ verwendet. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_21) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann und optional die angegebenen Öffnungsoptionen verwendet. |
| [can_save(options)](#can_save_options_22) | Bestimmt, ob das Bild im angegebenen Dateiformat, das durch die übergebenen Speicheroptionen repräsentiert wird, gespeichert werden kann. |
| [create(files)](#create_files_23) | Erstellt das mehrseitige Bild, das die angegebenen Dateien enthält. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_24) | Erstellt das mehrseitige Bild, das die angegebenen Dateien enthält. |
| [create(image_options, width, height)](#create_image_options_width_height_25) | Erstellt ein neues Bild mit den angegebenen Erstellungsoptionen. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_26) | Erstellt eine [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) Instanz aus dem bereitgestellten Pixelarray.<br/>            <br/>            Validiert, dass die angegebene Breite und Höhe den Abmessungen der Pixeldaten entsprechen.<br/>            Diese Methode kann nur verwendet werden, wenn die Bibliothek im lizenzierten Modus ist. |
| [create(images)](#create_images_27) | Erstellt ein neues Bild, das die angegebenen Bilder als Seiten verwendet |
| [create(images, dispose_images)](#create_images_dispose_images_28) | Erstellt ein neues Bild, wobei die angegebenen Bilder als Seiten verwendet werden. |
| [create(multipage_create_options)](#create_multipage_create_options_29) | Erstellt die angegebenen Mehrseiten‑Erstellungsoptionen. |
| [create_from_files(files)](#create_from_files_files_30) | Erstellt das Mehrseiten‑Bild, das die angegebenen Dateien als Lazy‑Loading‑Seiten enthält. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_31) | Erstellt das Mehrseiten‑Bild, das die angegebenen Dateien als Lazy‑Loading‑Seiten enthält. |
| [create_from_images(images)](#create_from_images_images_32) | Erstellt ein neues Bild, das die angegebenen Bilder als Seiten verwendet |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_33) | Erstellt ein neues Bild, wobei die angegebenen Bilder als Seiten verwendet werden. |
| [create_with_frame(frame)](#create_with_frame_frame_34) | Initialisiert eine neue Instanz der Klasse [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/). |
| [create_with_frames(frames)](#create_with_frames_frames_35) | Initialisiert eine neue Instanz der Klasse [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/). |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_36) | Führen Sie einen Bildausschnitt durch, indem Sie Verschiebungen nach links, rechts, oben und <br/>            unten angeben. Diese Methode ermöglicht eine präzise Auswahl des gewünschten Bildausschnitts, <br/>            erleichtert das effiziente Entfernen unerwünschter Bereiche und fokussiert auf <br/>            wesentliche Inhalte. Integrieren Sie diese Funktionalität in Ihre Bildverarbeitungspipeline, um bei Bedarf Klarheit und Komposition in Ihrer Anwendung zu verbessern. |
| [crop(rectangle)](#crop_rectangle_37) | Schneiden Sie das Bild mit einem angegebenen rechteckigen Bereich zu, um den gewünschten Inhalt präzise auszuwählen. Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um <br/>            unerwünschte Bereiche effizient zu entfernen und sich auf wesentliche Details zu konzentrieren, wodurch die <br/>            Gesamtklarheit und Komposition des Bildes verbessert wird. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_38) | Führt Dithering auf dem aktuellen Bild aus. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_39) | Führen Sie ein Dithering des aktuellen Bildes durch, um die visuelle Qualität zu erhöhen und <br/>            Farbbänderungsartefakte zu reduzieren. Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, <br/>            um sanftere Farbübergänge zu gewährleisten, was zu einem verbesserten Gesamterscheinungsbild und Klarheit des Bildes führt. |
| [embed_digital_signature(password)](#embed_digital_signature_password_40) | Betten Sie eine digitale Signatur, basierend auf dem angegebenen Passwort, in jede Seite des Bildes ein. |
| [filter(rectangle, options)](#filter_rectangle_options_41) | Filtern Sie den Inhalt innerhalb des angegebenen Rechtecks und wenden Sie einen festgelegten Bild‑<br/>            Verarbeitungsfilter an, um den ausgewählten Bereich zu verbessern oder zu verändern. Integrieren Sie diese Methode <br/>            in Ihren Bildbearbeitungs‑Workflow, um gezielte Verbesserungen oder <br/>            Transformationen in Ihrer Anwendung zu erreichen. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_42) | Liefert ein 32‑Bit‑ARGB‑Pixel‑Bild. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_43) | Liefert das Standard‑32‑Bit‑ARGB‑Pixel‑Array. |
| [get_default_options(args)](#get_default_options_args_44) | Liefert die Standardoptionen. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_45) | Liefert das Standard‑Pixel‑Array mittels teilweisem Pixel‑Lader. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_46) | Liefert das Standard‑Rohdaten‑Array mittels teilweisem Pixel‑Lader. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_47) | Liefert das Standard‑Rohdaten‑Array. |
| [get_file_format(file_path)](#get_file_format_file_path_48) | Liefert das Dateiformat. |
| [get_file_format(stream)](#get_file_format_stream_49) | Liefert das Dateiformat. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_50) | Liefert das Dateiformat. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_51) | Liefert das Rechteck, das zum aktuellen Bild passt. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_52) | Liefert das Rechteck, das zum aktuellen Bild passt. |
| [get_modify_date(use_default)](#get_modify_date_use_default_53) | Liefert Datum und Uhrzeit, zu der das Ressourcen‑Bild zuletzt geändert wurde. |
| [get_original_options()](#get_original_options__54) | Rufen Sie Optionen ab, die aus den ursprünglichen Dateieinstellungen abgeleitet sind, um eine nahtlose <br/>            Bewahrung wichtiger Parameter wie Bit‑Tiefe und anderer wesentlicher Attribute des <br/>            Originalbildes zu ermöglichen. Nutzen Sie diese Methode, um Treue und Konsistenz bei <br/>            Bildverarbeitungsaufgaben zu wahren und optimale Ergebnisse ohne unnötige Änderungen zu sichern.<br/>            Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es anschließend mit der<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) Methode speichern, wird ein PNG‑Bild mit 8 Bit pro Pixel erzeugt.<br/>            Um dies zu vermeiden und ein PNG‑Bild mit 1‑Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und sie<br/>            an die [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) Methode als zweiten Parameter zu übergeben. |
| [get_pixel(x, y)](#get_pixel_x_y_55) | Liefert ein Bild‑Pixel. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_56) | Liefert eine proportionale Höhe. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_57) | Liefert eine proportionale Breite. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_58) | Konvertiert zu aps. |
| [get_skew_angle()](#get_skew_angle__59) | Liefert den Schrägungswinkel.<br/>            Diese Methode ist auf gescannte Textdokumente anwendbar, um den Schrägungswinkel beim Scannen zu bestimmen. |
| grayscale() | Konvertieren Sie das Bild in seine Graustufen‑Darstellung, indem Sie es in ein <br/>            einkanaliges Bild umwandeln, bei dem jeder Pixel die Intensität repräsentiert. Integrieren Sie diese Methode <br/>            in Ihre Bildverarbeitungspipeline, um die Analyse zu vereinfachen und die <br/>            Kompatibilität mit graustufenbasierten Algorithmen zu erhöhen, was verschiedene Computer‑<br/>            Vision‑ und Bildanalyse‑Aufgaben in Ihrer Anwendung erleichtert. |
| [insert_frame(index, frame)](#insert_frame_index_frame_60) | Fügen Sie den neuen Frame an der angegebenen Position in die Frame‑Sequenz ein, um <br/>            präzise Kontrolle über die Anordnung der Frames zu gewährleisten. Nutzen Sie diese Methode, um Frame‑<br/>            Sequenzen effektiv zu verwalten, dynamische Manipulation und Organisation von Bild‑<br/>            Inhalten in Ihrer Anwendung zu ermöglichen. |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_61) | Führt eine schnelle Prüfung durch, um festzustellen, ob das Bild digital signiert ist, wobei das bereitgestellte Passwort und der Schwellenwert verwendet werden. |
| [load(file_path)](#load_file_path_62) | Lädt ein neues Bild vom angegebenen Dateipfad oder URL.<br/>            Wenn _filePath_ ein Dateipfad ist, öffnet die Methode einfach die Datei.<br/>            Wenn _filePath_ eine URL ist, lädt die Methode die Datei herunter, speichert sie temporär und öffnet sie. |
| [load(file_path, load_options)](#load_file_path_load_options_63) | Lädt ein neues Bild vom angegebenen Dateipfad oder URL.<br/>            Wenn _filePath_ ein Dateipfad ist, öffnet die Methode einfach die Datei.<br/>            Wenn _filePath_ eine URL ist, lädt die Methode die Datei herunter, speichert sie temporär und öffnet sie. |
| [load(stream)](#load_stream_64) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load(stream, load_options)](#load_stream_load_options_65) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_66) | Lädt 32‑Bit‑ARGB‑Pixel. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_67) | Lädt 64‑Bit‑ARGB‑Pixel. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_68) | Lädt Pixel im CMYK‑Format. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_69) | Lädt Pixel im CMYK‑Format.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere Methode [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_70) | Lädt 32‑Bit‑ARGB‑Pixel teilweise (nach Blöcken). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_71) | Lädt 64‑Bit‑ARGB‑Pixel teilweise nach Paketen. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_72) | Lädt Pixel teilweise nach Paketen. |
| [load_pixels(rectangle)](#load_pixels_rectangle_73) | Lädt Pixel. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_74) | Lädt Rohdaten. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_75) | Lädt Rohdaten. |
| [load_stream(stream)](#load_stream_stream_76) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_77) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_78) | Lädt ein neues Bild vom angegebenen Dateipfad oder URL.<br/>            Wenn _filePath_ ein Dateipfad ist, öffnet die Methode einfach die Datei.<br/>            Wenn _filePath_ eine URL ist, lädt die Methode die Datei herunter, speichert sie temporär und öffnet sie. |
| normalize_angle() | Normalisiert den Winkel.<br/>            Diese Methode ist auf gescannte Textdokumente anwendbar, um die schiefe Aufnahme zu korrigieren.<br/>            Diese Methode verwendet die Methoden [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) und [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_79) | Verwenden Sie die Methode NormalizeAngle, die speziell für gescannte Textdokumente entwickelt wurde, <br/>            um schiefe Scans zu korrigieren und eine genaue Ausrichtung sicherzustellen. Integrieren Sie diese Funktionalität nahtlos in Ihre Textverarbeitungs‑Workflows, um die <br/>            Lesbarkeit und Qualität von Dokumenten zu verbessern und die Gesamteffizienz bei Texterkennung <br/>            und Analyseaufgaben zu steigern.<br/>            Diese Methode verwendet [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) und [TiffImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) Methoden. |
| normalize_histogram() | Normalisiert das Bildhistogramm — passt die Pixelwerte an, um den gesamten verfügbaren Bereich zu nutzen. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_80) | Liest die gesamte Scanzeile anhand des angegebenen Scanzeilen‑Index. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_81) | Liest die gesamte Scanzeile anhand des angegebenen Scanzeilen‑Index. |
| [remove_frame(frame)](#remove_frame_frame_82) | Entfernen Sie effizient den angegebenen Frame aus der Bildsequenz, um <br/>            ein schlankes Frame‑Management in Ihrer Anwendung zu ermöglichen. Integrieren Sie diese Funktionalität <br/>            zur Verbesserung von Präzision und Flexibilität bei der Frame‑Manipulation, um eine nahtlose <br/>            Organisation und Darstellung von Bildinhalten zu gewährleisten. |
| [remove_frame(index)](#remove_frame_index_83) | Entfernt den Frame anhand seines Index. |
| [remove_frame_by_index(index)](#remove_frame_by_index_index_84) | Entfernt den Frame anhand seines Index. |
| remove_metadata() | Entfernt die Metadaten dieser Bildinstanz, indem die Werte von [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) und [IHasExifData.exif_data](/imaging/python-net/aspose.imaging.exif/ihasexifdata/) auf **None** gesetzt werden. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_85) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_86) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_87) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [replace_frame(index, new_frame)](#replace_frame_index_new_frame_88) | Ersetzen Sie den Frame an der angegebenen Position durch einen anderen Frame nahtlos, <br/>            um ein dynamisches Frame‑Management innerhalb der Bildsequenz zu ermöglichen. Integrieren Sie diese <br/>            Methode, um Flexibilität und Präzision bei der Frame‑Manipulation zu erhöhen und eine <br/>            optimale Organisation und Darstellung von Bildinhalten in Ihrer Anwendung sicherzustellen. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_89) | Ersetzt alle nicht‑transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.<br/>                Hinweis: Wenn Sie dies bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_90) | Ersetzt alle nicht‑transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.<br/>                Hinweis: Wenn Sie dies bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| [resize(new_width, new_height)](#resize_new_width_new_height_91) | Skaliert das Bild. Der Standardwert [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_92) | Führen Sie eine proportionale Größenänderung des Bildes durch, wobei das Seitenverhältnis beibehalten wird, <br/>            während die Abmessungen angepasst werden. Nutzen Sie diese Methode, um Bilder in Ihrer Anwendung dynamisch zu skalieren und eine konsistente visuelle Darstellung des Inhalts <br/>            zu gewährleisten.<br/>            Die proportionale Größenänderung passt jeden Frame gemäß dem Verhältnis von _newWidth_/width und _newHeight_/height an. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_93) | Passen Sie die Größe des Bildes anhand der angegebenen Einstellungen an, um präzise <br/>            Kontrolle über Abmessungen, Seitenverhältnis und Skalierungsverhalten zu ermöglichen. Integrieren Sie diese <br/>            Methode in Ihren Bildverarbeitungs‑Workflow, um maßgeschneiderte Größenänderungen <br/>            durchzuführen, die den spezifischen Anforderungen Ihrer Anwendung entsprechen. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_94) | Skaliert das Bild. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_95) | Skaliert das Bild. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_96) | Skaliert die Höhe proportional. Der Standard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_97) | Führen Sie eine proportionale Anpassung der Bildhöhe durch, wobei das Seitenverhältnis beibehalten wird, um eine konsistente visuelle Integrität zu gewährleisten. Nutzen Sie diese Methode, um Bilder in Ihrer Anwendung dynamisch zu skalieren und eine optimale Darstellung über verschiedene Plattformen <br/>            und Geräte hinweg sicherzustellen, ohne die Inhaltsqualität zu beeinträchtigen. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_98) | Skaliert die Höhe proportional. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_99) | Skaliert die Höhe proportional. |
| [resize_proportional(new_width, new_height, resize_type)](#resize_proportional_new_width_new_height_resize_type_100) | Führen Sie eine proportionale Größenänderung des Bildes durch, wobei das Seitenverhältnis beibehalten wird, <br/>            während die Abmessungen angepasst werden. Nutzen Sie diese Methode, um Bilder in Ihrer Anwendung dynamisch zu skalieren und eine konsistente visuelle Darstellung des Inhalts <br/>            zu gewährleisten.<br/>            Die proportionale Größenänderung passt jeden Frame gemäß dem Verhältnis von _newWidth_/width und _newHeight_/height an. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_101) | Skaliert die Breite proportional. Der Standard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_102) | Passen Sie die Breite des Bildes an, während das Seitenverhältnis erhalten bleibt, um eine proportionale Größenänderung für optimale visuelle Darstellung zu gewährleisten. Verwenden Sie diese Methode, um <br/>            Bilder in Ihrer Anwendung dynamisch zu skalieren und eine konsistente sowie <br/>            ästhetisch ansprechende Darstellung über verschiedene Anzeige‑Kontexte hinweg zu ermöglichen. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_103) | Skaliert die Breite proportional. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_104) | Skaliert die Breite proportional. |
| [rotate(angle)](#rotate_angle_105) | Bild um das Zentrum drehen. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_106) | Rotieren Sie das Bild um seinen Mittelpunkt um einen angegebenen Winkel, um präzise <br/>            Ausrichtungsanpassungen zu ermöglichen. Integrieren Sie diese Funktionalität in Ihre Bildverarbeitungspipeline, um genaue Transformationen zu erleichtern und eine optimale Ausrichtung sowie <br/>            Darstellung von visuellen Inhalten in Ihrer Anwendung sicherzustellen. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_107) | Führen Sie Rotation, Spiegelung oder eine Kombination beider Operationen ausschließlich am <br/>            aktiven Frame durch. Diese Methode ermöglicht eine präzise Manipulation einzelner Frames innerhalb <br/>            der Bildsequenz und erhöht die Flexibilität bei Bildbearbeitung und -komposition in Ihrer Anwendung. |
| [rotate_flip_all(rotate_flip)](#rotate_flip_all_rotate_flip_108) | Dreht das gesamte Flip. |
| save() | Speichert die Bilddaten in den zugrunde liegenden Stream. |
| [save(file_path)](#save_file_path_109) | Speichert das Bild am angegebenen Dateipfad. |
| [save(file_path, options)](#save_file_path_options_110) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_111) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(file_path, over_write)](#save_file_path_over_write_112) | Speichert die Daten des Objekts am angegebenen Speicherort. |
| [save(stream)](#save_stream_113) | Speichert die Daten des Objekts in den angegebenen Stream. |
| [save(stream, options_base)](#save_stream_options_base_114) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_115) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_116) | Speichert die 32‑Bit‑ARGB‑Pixel. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_117) | Speichert die Pixel. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_118) | Speichert die Pixel.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) Methode. |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_119) | Speichert die Pixel intern im Hauptspeicher. |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_120) | Speichert die Rohdaten. |
| [save_to_stream(stream)](#save_to_stream_stream_121) | Speichert das Bild in einen Stream |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_122) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_123) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_124) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_125) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_126) | Setzt ein 32‑Bit‑ARGB‑Pixel des Bildes für die angegebene Position. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_127) | Setzt die Bildpalette. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_128) | Setzt ein Bildpixel für die angegebene Position. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_129) | Legt die Auflösung für das angegebene [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) fest, wodurch <br/>            eine präzise Kontrolle über die Bilddarstellung und Anzeigeeigenschaften ermöglicht wird. Integrieren Sie diese <br/>            Funktionalität, um die visuelle Ausgabe zu optimieren und die Kompatibilität mit verschiedenen <br/>            Ausgabegeräten und Plattformen sicherzustellen, wodurch das Gesamterlebnis des Benutzers verbessert wird. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_130) | Versucht, eine _metadata_-Instanz zu setzen, falls diese [Image](/imaging/python-net/aspose.imaging/image/)‑Instanz unterstützt und eine [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)‑Instanz implementiert. |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_131) | Schreibt die gesamte Scanzeile in den angegebenen Scanzeilen‑Index. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_132) | Schreibt die gesamte Scanzeile in den angegebenen Scanzeilen‑Index. |


### Constructor: BigTiffImage(frame) {#BigTiffImage_frame_1}


```
 BigTiffImage(frame) 
```

Erstellen Sie eine neue Instanz der [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) Klasse, indem Sie sie mit einem TiffFrame-Parameter initialisieren<br/>            . Ideal für Entwickler, die eine bequeme<br/>            Möglichkeit suchen, mit BigTiffImage-Objekten zu arbeiten, und dabei Flexibilität und einfache Integration<br/>            in ihre Projekte gewährleisten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Der TIFF-Frame, mit dem das Bild initialisiert wird. |

### Constructor: BigTiffImage(frames) {#BigTiffImage_frames_2}


```
 BigTiffImage(frames) 
```

Beginnen Sie mit der nahtlosen Nutzung der [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) Klasse, indem Sie<br/>            eine neue Instanz mit einer Liste von TiffFrames-Parameter initialisieren.<br/>            Perfekt für Entwickler, die eine unkomplizierte Methode suchen, um mit<br/>            BigTiffImage-Objekten zu arbeiten, die mehrere Frames enthalten, und dabei die Effizienz ihrer Projekte sicherstellen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| frames | [TiffFrame[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Die Frames. |

### Method: add(image) {#add_image_1}


```
 add(image) 
```

Fügen Sie die Frames des angegebenen Bildes nahtlos in den aktuellen Frame ein, <br/>            konsolidieren deren Inhalt und erhöhen die Flexibilität der Komposition. Integrieren Sie <br/>            diese Methode, um die Frame‑Verwaltung und -Manipulation in Ihrer <br/>            Anwendung zu optimieren und eine effiziente Handhabung von Multi‑Frame‑Bildern zu ermöglichen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) | Das Quellbild. |

### Method: add_frame(frame) {#add_frame_frame_2}


```
 add_frame(frame) 
```

Integrieren Sie den angegebenen Frame nahtlos in das Bild und erweitern dessen Inhalt <br/>            sowie Vielseitigkeit. Nutzen Sie diese Methode, um die Bildkomposition und -verwaltung zu verbessern und eine effiziente Handhabung von Multi‑Frame‑Bildern in Ihrer Anwendung zu ermöglichen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Der hinzuzufügende Frame. |

### Method: add_frames(frames) {#add_frames_frames_3}


```
 add_frames(frames) 
```

Integrieren Sie das Frame‑Array nahtlos in das Bild und bereichern dessen Inhalt und <br/>            Vielseitigkeit. Nutzen Sie diese Methode, um die Bildkomposition und -verwaltung zu verbessern und eine effiziente Handhabung von Multi‑Frame‑Bildern in Ihrer Anwendung zu ermöglichen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| frames | [TiffFrame[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Das Frame-Array, das hinzugefügt werden soll |

### Method: add_page(page) {#add_page_page_4}


```
 add_page(page) 
```

Erweitern Sie Ihr BigTiff‑Bild mühelos, indem Sie mit dieser intuitiven Methode eine neue Seite hinzufügen.<br/>            Perfekt für Entwickler, die den Inhalt ihrer mehrseitigen Bilder dynamisch erweitern möchten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Die hinzuzufügende Seite. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_5}


```
 adjust_brightness(brightness) 
```

Implementieren Sie die _Helligkeit_‑Anpassung für das Bild, um die <br/>            Modifikation der Gesamthelligkeitswerte zu ermöglichen. Integrieren Sie diese Methode in Ihren Bild‑<br/>            Verarbeitungs‑Workflow, um die Sichtbarkeit zu erhöhen und die visuelle Qualität von <br/>            Bildern in Ihrer Anwendung zu verbessern.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Helligkeit | int | Helligkeitswert. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_6}


```
 adjust_contrast(contrast) 
```

Verbessern Sie den Kontrast der [Image](/imaging/python-net/aspose.imaging/image/) Instanz, <br/>            indem Sie die Unterschiede zwischen hellen und dunklen Bereichen verstärken. Integrieren Sie diese <br/>            Funktion, um die visuelle Klarheit und die Gesamtqualität des Bildes <br/>            in Ihrer Anwendung zu erhöhen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Kontrast | float | Kontrastwert (im Bereich [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_7}


```
 adjust_gamma(gamma) 
```

Wenden Sie eine Gammakorrektur auf das Bild an, passen Sie die Pixelintensitäten an, um das gewünschte Farbgleichgewicht zu erreichen <br/>            . Integrieren Sie diese Methode in Ihren Bildverarbeitungs <br/>            Workflow, um die visuelle Qualität zu verbessern und die Genauigkeit nachfolgender <br/>            Analyse‑ oder Anzeigeaufgaben in Ihrer Anwendung zu erhöhen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Gamma | float | Gamma‑Koeffizient für die Rot‑, Grün‑ und Blaukanäle |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_8}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Führen Sie eine Gammakorrektur am Bild unter Verwendung individueller Koeffizienten für die Rot‑, <br/>            Grün‑ und Blaukanäle durch, um feine Anpassungen des Farbgleichgewichts <br/>            und des Kontrasts zu ermöglichen. Integrieren Sie diese Methode in Ihre Bildverarbeitungspipeline, um <br/>            präzise Kontrolle über die Farbdarstellung zu erreichen und die visuelle Treue in Ihrer <br/>            Anwendung zu erhöhen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| gamma_red | float | Gamma‑Koeffizient für den Rotkanal |
| gamma_green | float | Gamma‑Koeffizient für den Grünkanal |
| gamma_blue | float | Gamma für den Blaukanal-Koeffizienten |

### Method: analyze_percentage_digital_signature(password) {#analyze_percentage_digital_signature_password_9}


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


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_10}


```
 binarize_bradley(brightness_difference) 
```

Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild-Schwellenwertbestimmung

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brightness_difference | float | Der Helligkeitsunterschied zwischen dem Pixel und dem Durchschnitt eines s x s Fensters von Pixeln<br/>                das um dieses Pixel zentriert ist. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_11}


```
 binarize_bradley(brightness_difference, window_size) 
```

Implementieren Sie die Binarisierung des Bildes mittels Bradleys adaptivem Schwellenwert‑Algorithmus <br/>            mit Integral‑Bild‑Schwellwertbestimmung. Dieser Ansatz berechnet dynamisch <br/>            lokale Schwellenwerte basierend auf der Nachbarschaft des Bildes, verbessert die Anpassungsfähigkeit an <br/>            unterschiedliche Lichtverhältnisse und sorgt für eine robuste Segmentierung für nachfolgende <br/>            Verarbeitungsschritte in Ihrer Anwendung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brightness_difference | float | Der Helligkeitsunterschied zwischen dem Pixel und dem Durchschnitt eines s x s Fensters von Pixeln<br/>            das um dieses Pixel zentriert ist. |
| window_size | int | Die Größe des s x s Fensters von Pixeln, das um dieses Pixel zentriert ist. |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_12}


```
 binarize_fixed(threshold) 
```

Wenden Sie die Binarisierung auf das Bild mit einem vordefinierten Schwellenwert an und konvertieren Sie es in <br/>            ein Binärbild mit klaren Vorder‑ und Hintergrundbereichen. Integrieren Sie diese <br/>            Methode in Ihren Bildverarbeitungs‑Workflow, um Segmentierungs‑ und Feature‑Extraktionsaufgaben zu erleichtern und die Genauigkeit sowie Effizienz der Bildanalyse in Ihrer <br/>            Anwendung zu steigern.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Schwellenwert | System.Byte | Schwellenwert. Wenn der entsprechende Grauwert eines Pixels größer als der Schwellenwert ist, wird ihm ein Wert von<br/>            255 zugewiesen, sonst 0. |

### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_13}


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

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_14}


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

### Method: can_load(file_path)  [static] {#can_load_file_path_15}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_16}


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


### Method: can_load(stream)  [static] {#can_load_stream_17}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_18}


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


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_19}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_20}


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


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_21}


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


### Method: can_save(options) {#can_save_options_22}


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


### Method: create(files)  [static] {#create_files_23}


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


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_24}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_25}


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


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_26}


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


### Method: create(images)  [static] {#create_images_27}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_28}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_29}


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


### Method: create_from_files(files)  [static] {#create_from_files_files_30}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_31}


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


### Method: create_from_images(images)  [static] {#create_from_images_images_32}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_33}


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


### Method: create_with_frame(frame)  [static] {#create_with_frame_frame_34}


```
 create_with_frame(frame) 
```

Initialisiert eine neue Instanz der Klasse [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Der TIFF-Frame, mit dem das Bild initialisiert wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) | Ein neues BigTiffImage-Bild, das den Frame enthält. |


### Method: create_with_frames(frames)  [static] {#create_with_frames_frames_35}


```
 create_with_frames(frames) 
```

Initialisiert eine neue Instanz der Klasse [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| frames | [TiffFrame[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Die Frames. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_36}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Führen Sie einen Bildausschnitt durch, indem Sie Verschiebungen nach links, rechts, oben und <br/>            unten angeben. Diese Methode ermöglicht eine präzise Auswahl des gewünschten Bildausschnitts, <br/>            erleichtert das effiziente Entfernen unerwünschter Bereiche und fokussiert auf <br/>            wesentliche Inhalte. Integrieren Sie diese Funktionalität in Ihre Bildverarbeitungspipeline, um bei Bedarf Klarheit und Komposition in Ihrer Anwendung zu verbessern.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| left_shift | int | Die linke Verschiebung. |
| right_shift | int | Die rechte Verschiebung. |
| top_shift | int | Die obere Verschiebung. |
| bottom_shift | int | Die untere Verschiebung. |

### Method: crop(rectangle) {#crop_rectangle_37}


```
 crop(rectangle) 
```

Schneiden Sie das Bild mit einem angegebenen rechteckigen Bereich zu, um den gewünschten Inhalt präzise auszuwählen. Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um <br/>            unerwünschte Bereiche effizient zu entfernen und sich auf wesentliche Details zu konzentrieren, wodurch die <br/>            Gesamtklarheit und Komposition des Bildes verbessert wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_38}


```
 dither(dithering_method, bits_count) 
```

Führt Dithering auf dem aktuellen Bild aus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Die Dithering-Methode. |
| bits_count | int | Die endgültige Bitanzahl für das Dithern. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_39}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Führen Sie ein Dithering des aktuellen Bildes durch, um die visuelle Qualität zu erhöhen und <br/>            Farbbänderungsartefakte zu reduzieren. Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, <br/>            um sanftere Farbübergänge zu gewährleisten, was zu einem verbesserten Gesamterscheinungsbild und Klarheit des Bildes führt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Die Dithering-Methode. |
| bits_count | int | Die endgültige Bitanzahl für das Dithern. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die benutzerdefinierte Palette für das Dithern. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_40}


```
 embed_digital_signature(password) 
```

Betten Sie eine digitale Signatur, basierend auf dem angegebenen Passwort, in jede Seite des Bildes ein.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Passwort | string | Das Passwort, das zum Erzeugen digitaler Signaturdaten verwendet wird |

### Method: filter(rectangle, options) {#filter_rectangle_options_41}


```
 filter(rectangle, options) 
```

Filtern Sie den Inhalt innerhalb des angegebenen Rechtecks und wenden Sie einen festgelegten Bild‑<br/>            Verarbeitungsfilter an, um den ausgewählten Bereich zu verbessern oder zu verändern. Integrieren Sie diese Methode <br/>            in Ihren Bildbearbeitungs‑Workflow, um gezielte Verbesserungen oder <br/>            Transformationen in Ihrer Anwendung zu erreichen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Die Optionen. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_42}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_43}


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


### Method: get_default_options(args) {#get_default_options_args_44}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_45}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Liefert das Standard‑Pixel‑Array mittels teilweisem Pixel‑Lader.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, für das die Pixel abgerufen werden. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Der partielle Pixel‑Lader. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_46}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_47}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_48}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_49}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_50}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_51}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_52}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_53}


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


### Method: get_original_options() {#get_original_options__54}


```
 get_original_options() 
```

Rufen Sie Optionen ab, die aus den ursprünglichen Dateieinstellungen abgeleitet sind, um eine nahtlose <br/>            Bewahrung wichtiger Parameter wie Bit‑Tiefe und anderer wesentlicher Attribute des <br/>            Originalbildes zu ermöglichen. Nutzen Sie diese Methode, um Treue und Konsistenz bei <br/>            Bildverarbeitungsaufgaben zu wahren und optimale Ergebnisse ohne unnötige Änderungen zu sichern.<br/>            Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es anschließend mit der<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) Methode speichern, wird ein PNG‑Bild mit 8 Bit pro Pixel erzeugt.<br/>            Um dies zu vermeiden und ein PNG‑Bild mit 1‑Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und sie<br/>            an die [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) Methode als zweiten Parameter zu übergeben.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Optionen basierend auf den ursprünglichen Dateieinstellungen. |


### Method: get_pixel(x, y) {#get_pixel_x_y_55}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_56}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_57}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_58}


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


### Method: get_skew_angle() {#get_skew_angle__59}


```
 get_skew_angle() 
```

Liefert den Schrägungswinkel.<br/>            Diese Methode ist auf gescannte Textdokumente anwendbar, um den Schrägungswinkel beim Scannen zu bestimmen.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float | Der Schrägwinkel in Grad. |


### Method: insert_frame(index, frame) {#insert_frame_index_frame_60}


```
 insert_frame(index, frame) 
```

Fügen Sie den neuen Frame an der angegebenen Position in die Frame‑Sequenz ein, um <br/>            präzise Kontrolle über die Anordnung der Frames zu gewährleisten. Nutzen Sie diese Methode, um Frame‑<br/>            Sequenzen effektiv zu verwalten, dynamische Manipulation und Organisation von Bild‑<br/>            Inhalten in Ihrer Anwendung zu ermöglichen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Der Index von _frame_. |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Der Frame für die Einfügung. |

### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_61}


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


### Method: load(file_path)  [static] {#load_file_path_62}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_63}


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


### Method: load(stream)  [static] {#load_stream_64}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_65}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_66}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_67}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_68}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_69}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_70}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Lädt 32‑Bit‑ARGB‑Pixel teilweise (nach Blöcken).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, aus dem Pixel geladen werden. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Der partielle Pixel‑Lader. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_71}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Lädt 64‑Bit‑ARGB‑Pixel teilweise nach Paketen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das gewünschte Rechteck. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | Der 64-bit ARGB-Pixel-Lader. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_72}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Lädt Pixel teilweise nach Paketen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das gewünschte Rechteck. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Der Pixel-Lader. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_73}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_74}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_75}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_76}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_77}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_78}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_79}


```
 normalize_angle(resize_proportionally, background_color) 
```

Verwenden Sie die Methode NormalizeAngle, die speziell für gescannte Textdokumente entwickelt wurde, <br/>            um schiefe Scans zu korrigieren und eine genaue Ausrichtung sicherzustellen. Integrieren Sie diese Funktionalität nahtlos in Ihre Textverarbeitungs‑Workflows, um die <br/>            Lesbarkeit und Qualität von Dokumenten zu verbessern und die Gesamteffizienz bei Texterkennung <br/>            und Analyseaufgaben zu steigern.<br/>            Diese Methode verwendet [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) und [TiffImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) Methoden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| resize_proportionally | bool | Wenn auf <c>true</c> gesetzt, wird die Bildgröße gemäß den Projektionen des gedrehten Rechtecks (Eckpunkte) geändert; andernfalls bleiben die Abmessungen unverändert und nur der Bildinhalt wird rotiert. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Farbe des Hintergrunds. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_80}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_81}


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


### Method: remove_frame(frame) {#remove_frame_frame_82}


```
 remove_frame(frame) 
```

Entfernen Sie effizient den angegebenen Frame aus der Bildsequenz, um <br/>            ein schlankes Frame‑Management in Ihrer Anwendung zu ermöglichen. Integrieren Sie diese Funktionalität <br/>            zur Verbesserung von Präzision und Flexibilität bei der Frame‑Manipulation, um eine nahtlose <br/>            Organisation und Darstellung von Bildinhalten zu gewährleisten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Der zu entfernende Frame. |

### Method: remove_frame(index) {#remove_frame_index_83}


```
 remove_frame(index) 
```

Entfernt den Frame anhand seines Index.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Index des zu entfernenden Frames. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Der entfernte Frame. |


### Method: remove_frame_by_index(index) {#remove_frame_by_index_index_84}


```
 remove_frame_by_index(index) 
```

Entfernt den Frame anhand seines Index.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Index des zu entfernenden Frames. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Der entfernte Frame. |


### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_85}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_86}


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

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_87}


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

### Method: replace_frame(index, new_frame) {#replace_frame_index_new_frame_88}


```
 replace_frame(index, new_frame) 
```

Ersetzen Sie den Frame an der angegebenen Position durch einen anderen Frame nahtlos, <br/>            um ein dynamisches Frame‑Management innerhalb der Bildsequenz zu ermöglichen. Integrieren Sie diese <br/>            Methode, um Flexibilität und Präzision bei der Frame‑Manipulation zu erhöhen und eine <br/>            optimale Organisation und Darstellung von Bildinhalten in Ihrer Anwendung sicherzustellen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Die nullbasierte Frame-Position. |
| new_frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Der Frame, der den bei angegebenem _index_ befindlichen ersetzen soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Der entfernte Frame. |


### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_89}


```
 replace_non_transparent_colors(new_color) 
```

Ersetzt alle nicht‑transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.<br/>                Hinweis: Wenn Sie dies bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_90}


```
 replace_non_transparent_colors(new_color_argb) 
```

Ersetzt alle nicht‑transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.<br/>                Hinweis: Wenn Sie dies bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_color_argb | int | Neuer ARGB-Farbwert, um nicht-transparente Farben zu ersetzen. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_91}


```
 resize(new_width, new_height) 
```

Skaliert das Bild. Der Standardwert [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_92}


```
 resize(new_width, new_height, resize_type) 
```

Führen Sie eine proportionale Größenänderung des Bildes durch, wobei das Seitenverhältnis beibehalten wird, <br/>            während die Abmessungen angepasst werden. Nutzen Sie diese Methode, um Bilder in Ihrer Anwendung dynamisch zu skalieren und eine konsistente visuelle Darstellung des Inhalts <br/>            zu gewährleisten.<br/>            Die proportionale Größenänderung passt jeden Frame gemäß dem Verhältnis von _newWidth_/width und _newHeight_/height an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Der Skalierungstyp. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_93}


```
 resize(new_width, new_height, settings) 
```

Passen Sie die Größe des Bildes anhand der angegebenen Einstellungen an, um präzise <br/>            Kontrolle über Abmessungen, Seitenverhältnis und Skalierungsverhalten zu ermöglichen. Integrieren Sie diese <br/>            Methode in Ihren Bildverarbeitungs‑Workflow, um maßgeschneiderte Größenänderungen <br/>            durchzuführen, die den spezifischen Anforderungen Ihrer Anwendung entsprechen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Skalierungseinstellungen. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_94}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_95}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_96}


```
 resize_height_proportionally(new_height) 
```

Skaliert die Höhe proportional. Der Standard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_97}


```
 resize_height_proportionally(new_height, resize_type) 
```

Führen Sie eine proportionale Anpassung der Bildhöhe durch, wobei das Seitenverhältnis beibehalten wird, um eine konsistente visuelle Integrität zu gewährleisten. Nutzen Sie diese Methode, um Bilder in Ihrer Anwendung dynamisch zu skalieren und eine optimale Darstellung über verschiedene Plattformen <br/>            und Geräte hinweg sicherzustellen, ohne die Inhaltsqualität zu beeinträchtigen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ der Skalierung. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_98}


```
 resize_height_proportionally(new_height, settings) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Bildskalierungseinstellungen. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_99}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Bildskalierungseinstellungen. |

### Method: resize_proportional(new_width, new_height, resize_type) {#resize_proportional_new_width_new_height_resize_type_100}


```
 resize_proportional(new_width, new_height, resize_type) 
```

Führen Sie eine proportionale Größenänderung des Bildes durch, wobei das Seitenverhältnis beibehalten wird, <br/>            während die Abmessungen angepasst werden. Nutzen Sie diese Methode, um Bilder in Ihrer Anwendung dynamisch zu skalieren und eine konsistente visuelle Darstellung des Inhalts <br/>            zu gewährleisten.<br/>            Die proportionale Größenänderung passt jeden Frame gemäß dem Verhältnis von _newWidth_/width und _newHeight_/height an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Der Skalierungstyp. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_101}


```
 resize_width_proportionally(new_width) 
```

Skaliert die Breite proportional. Der Standard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_102}


```
 resize_width_proportionally(new_width, resize_type) 
```

Passen Sie die Breite des Bildes an, während das Seitenverhältnis erhalten bleibt, um eine proportionale Größenänderung für optimale visuelle Darstellung zu gewährleisten. Verwenden Sie diese Methode, um <br/>            Bilder in Ihrer Anwendung dynamisch zu skalieren und eine konsistente sowie <br/>            ästhetisch ansprechende Darstellung über verschiedene Anzeige‑Kontexte hinweg zu ermöglichen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ der Skalierung. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_103}


```
 resize_width_proportionally(new_width, settings) 
```

Skaliert die Breite proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Bildskalierungseinstellungen. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_104}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Skaliert die Breite proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Bildskalierungseinstellungen. |

### Method: rotate(angle) {#rotate_angle_105}


```
 rotate(angle) 
```

Bild um das Zentrum drehen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_106}


```
 rotate(angle, resize_proportionally, background_color) 
```

Rotieren Sie das Bild um seinen Mittelpunkt um einen angegebenen Winkel, um präzise <br/>            Ausrichtungsanpassungen zu ermöglichen. Integrieren Sie diese Funktionalität in Ihre Bildverarbeitungspipeline, um genaue Transformationen zu erleichtern und eine optimale Ausrichtung sowie <br/>            Darstellung von visuellen Inhalten in Ihrer Anwendung sicherzustellen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |
| resize_proportionally | bool | Wenn auf <c>true</c> gesetzt, wird die Bildgröße gemäß den Projektionen des gedrehten Rechtecks (Eckpunkte) geändert; andernfalls bleiben die Abmessungen unverändert und nur der Bildinhalt wird rotiert. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Farbe des Hintergrunds. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_107}


```
 rotate_flip(rotate_flip_type) 
```

Führen Sie Rotation, Spiegelung oder eine Kombination beider Operationen ausschließlich am <br/>            aktiven Frame durch. Diese Methode ermöglicht eine präzise Manipulation einzelner Frames innerhalb <br/>            der Bildsequenz und erhöht die Flexibilität bei Bildbearbeitung und -komposition in Ihrer Anwendung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Der Rotations-Flip-Typ. |

### Method: rotate_flip_all(rotate_flip) {#rotate_flip_all_rotate_flip_108}


```
 rotate_flip_all(rotate_flip) 
```

Dreht das gesamte Flip.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rotate_flip | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Der Rotations-Flip. |

### Method: save(file_path) {#save_file_path_109}


```
 save(file_path) 
```

Speichert das Bild am angegebenen Dateipfad.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem das Bild gespeichert wird. |

### Method: save(file_path, options) {#save_file_path_options_110}


```
 save(file_path, options) 
```

Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Optionen. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_111}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_112}


```
 save(file_path, over_write) 
```

Speichert die Daten des Objekts am angegebenen Speicherort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Objektdaten gespeichert werden. |
| over_write | bool | wenn auf <c>true</c> gesetzt, werden die Dateiinhalte überschrieben, andernfalls wird angehängt. |

### Method: save(stream) {#save_stream_113}


```
 save(stream) 
```

Speichert die Daten des Objekts in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem die Daten des Objekts gespeichert werden sollen. |

### Method: save(stream, options_base) {#save_stream_options_base_114}


```
 save(stream, options_base) 
```

Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem die Bilddaten gespeichert werden. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Speicheroptionen. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_115}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_116}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Speichert die 32‑Bit‑ARGB‑Pixel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, in dem Pixel gespeichert werden. |
| Pixel | int[] | Das 32‑Bit‑ARGB‑Pixel‑Array. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_117}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Speichert die Pixel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, in dem Pixel gespeichert werden. |
| Pixel | int[] | Die CMYK‑Pixel, dargestellt als 32‑Bit‑Ganzzahlwerte. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_118}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Speichert die Pixel.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) Methode.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, in dem Pixel gespeichert werden. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Das CMYK‑Pixel‑Array. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_119}


```
 save_pixels(rectangle, pixels) 
```

Speichert die Pixel intern im Hauptspeicher.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Die Pixel. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_120}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_121}


```
 save_to_stream(stream) 
```

Speichert das Bild in einen Stream

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom |  |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_122}


```
 save_to_stream_with_options(stream, options_base) 
```

Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem die Bilddaten gespeichert werden. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Speicheroptionen. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_123}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_124}


```
 save_with_options(file_path, options) 
```

Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Optionen. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_125}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_126}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_127}


```
 set_palette(palette, update_colors) 
```

Setzt die Bildpalette.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die zu setzende Palette. |
| update_colors | bool | Wenn auf <c>true</c> gesetzt, werden die Farben gemäß der neuen Palette aktualisiert; andernfalls bleiben die Farbindizes unverändert. Hinweis: Unveränderte Indizes können das Bild beim Laden zum Absturz bringen, wenn einige Indizes keinen entsprechenden Paletteneintrag haben. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_128}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_129}


```
 set_resolution(dpi_x, dpi_y) 
```

Legt die Auflösung für das angegebene [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) fest, wodurch <br/>            eine präzise Kontrolle über die Bilddarstellung und Anzeigeeigenschaften ermöglicht wird. Integrieren Sie diese <br/>            Funktionalität, um die visuelle Ausgabe zu optimieren und die Kompatibilität mit verschiedenen <br/>            Ausgabegeräten und Plattformen sicherzustellen, wodurch das Gesamterlebnis des Benutzers verbessert wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dpi_x | float | Die horizontale Auflösung in Punkten pro Zoll des [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | Die vertikale Auflösung in Punkten pro Zoll des [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_130}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_131}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Schreibt die gesamte Scanzeile in den angegebenen Scanzeilen‑Index.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| scan_line_index | int | Nullbasierter Index der Scan-Zeile. |
| argb_32_pixels | int[] | Das 32‑Bit‑ARGB‑Farben‑Array zum Schreiben. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_132}


```
 write_scan_line(scan_line_index, pixels) 
```

Schreibt die gesamte Scanzeile in den angegebenen Scanzeilen‑Index.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| scan_line_index | int | Nullbasierter Index der Scan-Zeile. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Das Pixel‑Farben‑Array zum Schreiben. |

