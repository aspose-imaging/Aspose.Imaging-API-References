---
title: "DicomImage-Klasse"
type: docs
weight: 20
url: /de/python-net/aspose.imaging.fileformats.dicom/dicomimage/
---

**Summary:** This Class implements Digital Imaging and Communications in Medicine<br/>            (DICOM) raster image format support and offers a comprehensive solution for<br/>            processing DICOM images with precision and flexibility. You can seamlessly<br/>            manipulate image pages, including operations to get, add, or remove pages, and<br/>            control the default and active pages. With capabilities to work with alpha channels,<br/>            embed XMP metadata, resize, rotate, crop, binarize, adjust, apply filters,<br/>            and convert to other raster formats. This API empowers developers to handle<br/>            DICOM images effectively while meeting diverse application requirements in<br/>            medical imaging contexts.

**Module:** [aspose.imaging.fileformats.dicom](/imaging/python-net/aspose.imaging.fileformats.dicom/)

**Full Name:** aspose.imaging.fileformats.dicom.DicomImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IMultipageImage, IMultipageImageExt, RasterCachedMultipageImage

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [DicomImage(dicom_options, width, height)](#DicomImage_dicom_options_width_height_1) | Initialisieren Sie mühelos eine neue Instanz der DicomImage-Klasse mit diesem<br/>            Konstruktor, wobei die dicomOptions-Parameter verwendet werden. Perfekt für Entwickler, die nach<br/>            einer schnellen und effizienten Einarbeitung in [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) Objekte in ihren Projekten suchen. |
| [DicomImage(stream)](#DicomImage_stream_2) | Erstellen Sie eine neue Instanz der DicomImage-Klasse, indem Sie einen Stream‑Parameter<br/>            in diesem Konstruktor verwenden. Perfekt für Entwickler, die nach einer schlanken Methode suchen, um [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) Objekte aus bestehenden Datenströmen in ihren Projekten zu initialisieren. |
| [DicomImage(stream, load_options)](#DicomImage_stream_load_options_3) | Starten Sie eine neue Instanz der DicomImage-Klasse reibungslos, indem Sie einen Stream‑ und<br/>            loadOptions‑Parameter in diesem Konstruktor einsetzen. Ideal für Entwickler, die eifrig sind, um schnell und effektiv mit [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) Objekten in ihren Projekten zu arbeiten. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| active_page | [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/) | r/w | Verwalten Sie die aktive Seite des Bildes mit dieser intuitiven Eigenschaft. Ideal für Entwickler,<br/>            die dynamisch zwischen Seiten in mehrseitigen Bildern wechseln möchten und dabei eine effiziente<br/>            Navigation und Verarbeitung sicherstellen. |
| active_page_index | int | r | Rufen Sie den Index der aktiven Seite mühelos mit dieser intuitiven Eigenschaft ab.<br/>            Ideal für Entwickler, die schnellen Zugriff auf den aktuellen Seitenindex in mehrseitigen<br/>            Bildern benötigen und dabei eine effiziente Navigation und Verarbeitung sicherstellen. |
| auto_adjust_palette | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die automatische Anpassung der Palette erfolgt. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Liest oder setzt einen Wert für die Hintergrundfarbe. |
| bits_per_pixel | int | r | Liest die Bit‑Pro‑Pixel‑Anzahl des Bildes. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Liest die Objektgrenzen. |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Liest den [Image](/imaging/python-net/aspose.imaging/image/) Container. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Liest den Datenstrom des Objekts. |
| dicom_pages | [DicomPage[]](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/) | r | Greifen Sie mit dieser intuitiven Eigenschaft auf die Seiten des Bildes zu. Ideal für Entwickler<br/>            die mit einzelnen Seiten des Bildes interagieren möchten und dabei nahtlose<br/>            Navigation und Manipulation gewährleisten. |
| freigegeben | bool | r | Liest einen Wert, der angibt, ob diese Instanz freigegeben ist. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Liest oder setzt die Exif‑Instanz. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Rufen Sie den Dateiformatwert mühelos mit dieser intuitiven Eigenschaft ab. Ideal für<br/>            Entwickler, die schnellen Zugriff auf das Format der Bilddatei benötigen und dabei eine effiziente<br/>            Handhabung und Verarbeitung basierend auf dem Dateityp gewährleisten. |
| file_info | [DicomImageInfo](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimageinfo/) | r | Rufen Sie wertvolle Header-Informationen aus der DICOM-Datei mühelos mit dieser<br/>            intuitiven Eigenschaft ab. Ideal für Entwickler, die schnellen Zugriff auf wesentliche Details<br/>            innerhalb der DICOM-Datei benötigen und dabei eine effiziente Datenextraktion und Analyse gewährleisten. |
| has_alpha | bool | r | Ermitteln Sie mühelos, ob das Bild einen Alpha-Kanal besitzt, mit dieser intuitiven<br/>            Eigenschaft. Ideal für Entwickler, die feststellen möchten, ob das Bild Transparenzinformationen enthält, und dabei eine präzise Handhabung von Alpha-Kanal-Daten in Bildverarbeitungsaufgaben gewährleisten. |
| has_background_color | bool | r/w | Liest oder setzt einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| has_transparent_color | bool | r/w | Liest einen Wert, der angibt, ob das Bild eine transparente Farbe hat. |
| height | int | r | Liest die Bildhöhe. |
| horizontal_resolution | float | r/w | Liest oder setzt die horizontale Auflösung in Pixel pro Zoll dieses [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| image_opacity | float | r | Liest die Opazität dieses Bildes. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Liest oder setzt den Interrupt-Monitor. |
| is_cached | bool | r | Liest einen Wert, der angibt, ob Bilddaten derzeit zwischengespeichert sind. |
| is_raw_data_available | bool | r | Liest einen Wert, der angibt, ob das Laden von Rohdaten unterstützt wird. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Liest oder setzt XMP-Daten aus dem Frame. |
| page_count | int | r | Rufen Sie die Gesamtseitenzahl des Bildes mit dieser intuitiven Eigenschaft ab. Ideal für<br/>            Entwickler, die schnellen Zugriff auf die Anzahl der Seiten in einem Bild benötigen und dabei eine effiziente Navigation und Verwaltung gewährleisten. |
| pages | [Image[]](/imaging/python-net/aspose.imaging/image/) | r | Greifen Sie mit dieser intuitiven Eigenschaft auf die Seiten des Bildes zu. Ideal für Entwickler<br/>            die mit einzelnen Seiten des Bildes interagieren möchten und dabei nahtlose Navigation<br/>            und Manipulation gewährleisten. |
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
| [add_page()](#add_page__1) | Fügen Sie mit dieser einfachen Methode eine neue Seite am Ende der Seitenliste des Bildes hinzu.<br/>            Ideal für Entwickler, die mehrseitige Bilder dynamisch erweitern möchten, um eine nahtlose<br/>            Integration und Organisation des Bildinhalts zu gewährleisten. |
| [add_page(page)](#add_page_page_2) | Erweitern Sie Ihre Bildsammlung, indem Sie mit dieser intuitiven Methode eine neue Seite hinzufügen.<br/>            Ideal für Entwickler, die mehrseitige Bilder dynamisch ergänzen möchten,<br/>            um eine nahtlose Erweiterung und Organisation des Bildinhalts zu gewährleisten. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_3) | Verbessern Sie die Bildluminanz durch die Anpassung der _Helligkeit_, einer<br/>            parametrisierten Methode, die Entwicklern ermöglicht, die Leuchtkraft von Bildern fein abzustimmen.<br/>            Diese benutzerfreundliche Funktion befähigt Entwickler, die Bild<br/>            Helligkeit nahtlos zu manipulieren und bietet Flexibilität sowie Kontrolle über die visuelle Ästhetik. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_4) | Verbessern Sie den Kontrast von [Image](/imaging/python-net/aspose.imaging/image/) mit dieser benutzerfreundlichen Methode,<br/>            die die Unterschiede zwischen hellen und dunklen Bereichen anpasst. Verbessern Sie die visuelle Klarheit und<br/>            Definition mühelos und bieten Entwicklern eine intuitive Kontrolle über<br/>            den Bildkontrast für eine optimale Darstellung. |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_5) | Verbessern Sie die Bildqualität und passen Sie sie mit Gamma-Korrektur an, einer leistungsstarken Technik<br/>            zur Feinabstimmung des visuellen Erscheinungsbildes. Perfekt für Entwickler, die die Bild<br/>            Darstellung optimieren, den Farbton ausgleichen und eine konsistente Wiedergabe über verschiedene<br/>            Geräte und Umgebungen hinweg sicherstellen möchten. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_6) | Erreichen Sie präzise Farbkorrekturen, indem Sie Gamma-Korrektur unabhängig<br/>            von den roten, grünen und blauen Komponenten eines Bildes anwenden. Diese Methode gewährleistet eine genaue<br/>            Farbbalance und optimale visuelle Ausgabe und richtet sich an Entwickler, die eine feinkörnige<br/>            Kontrolle über die Bilddarstellung und Farbgenauigkeit wünschen. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_7) | Berechnet den prozentualen Ähnlichkeitsgrad zwischen den extrahierten Daten und dem ursprünglichen Passwort. |
| auto_brightness_contrast() | Führt eine automatische adaptive Helligkeits- und Kontrastnormalisierung für das gesamte Bild durch. |
| auto_rotate() | Dreht das Bild automatisch basierend auf den aus den Exif-<br/>            Metadaten extrahierten Orientierungsdaten. Diese Methode stellt sicher, dass Bilder in der korrekten Ausrichtung angezeigt werden, <br/>            verbessert das Benutzererlebnis und eliminiert die Notwendigkeit manueller Anpassungen. Durch <br/>            Analyse der Exif-Informationen wird das Bild entsprechend gedreht, was ein nahtloses <br/>            Anzeigeerlebnis über verschiedene Plattformen und Geräte hinweg ermöglicht. Dieser automatisierte Rotations<br/>            Prozess vereinfacht die Bildverarbeitung und erhöht die Gesamtbenutzerfreundlichkeit, insbesondere bei <br/>            großen Bildmengen mit unterschiedlichen Ausrichtungen. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_8) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild-Schwellenwertbestimmung |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_9) | Binarisieren Sie Bilder mit Bradleys adaptivem Schwellenwertalgorithmus und nutzen Sie dabei die Integralbild-<br/>            Schwellenwertbestimmung für verbesserte Leistung. Ideal für Entwickler, die<br/>            Bilder automatisch anhand lokaler Helligkeitsvariationen segmentieren möchten, um<br/>            eine genaue Objekterkennung und -extraktion bei unterschiedlichen Lichtbedingungen sicherzustellen. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_10) | Konvertieren Sie das Bild einfach in ein Binärformat mithilfe eines vordefinierten Schwellenwerts<br/>            mit dieser unkomplizierten Methode. Ideal für Entwickler, die Bildverarbeitungsaufgaben vereinfachen möchten, indem sie das Bild anhand festgelegter Intensitätsstufen in Vorder- und Hintergrundkomponenten<br/>            segmentieren. |
| binarize_otsu() | Wenden Sie die Otsu-Schwellenwertbestimmung an, um das Bild zu binarisieren, wobei der optimale<br/>            Schwellenwert automatisch basierend auf dem Histogramm des Bildes ermittelt wird. Perfekt für Entwickler, die<br/>            eine zuverlässige Methode suchen, um Bilder in Vorder- und Hintergrundbereiche zu segmentieren, mit<br/>            minimalem manuellem Eingriff. |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_11) | Mischt diese Bildinstanz mit dem _overlay_-Bild. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_12) | Mischt diese Bildinstanz mit dem _overlay_-Bild. |
| cache_data() | Diese Methode cached Daten effizient, optimiert die Leistung und gewährleistet schnellen Zugriff<br/>            bei Bedarf. Ideal für Entwickler, die die Geschwindigkeit und Effizienz ihrer<br/>            Anwendungen durch intelligentes Datenmanagement verbessern möchten. |
| [can_load(file_path)](#can_load_file_path_13) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_14) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann und optional die angegebenen Öffnungsoptionen verwendet. |
| [can_load(stream)](#can_load_stream_15) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann. |
| [can_load(stream, load_options)](#can_load_stream_load_options_16) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann und optional die angegebenen _loadOptions_ verwendet. |
| [can_load_stream(stream)](#can_load_stream_stream_17) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_18) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann und optional die angegebenen _loadOptions_ verwendet. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_19) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann und optional die angegebenen Öffnungsoptionen verwendet. |
| [can_save(options)](#can_save_options_20) | Bestimmt, ob das Bild im angegebenen Dateiformat, das durch die übergebenen Speicheroptionen repräsentiert wird, gespeichert werden kann. |
| [create(files)](#create_files_21) | Erstellt das mehrseitige Bild, das die angegebenen Dateien enthält. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_22) | Erstellt das mehrseitige Bild, das die angegebenen Dateien enthält. |
| [create(image_options, width, height)](#create_image_options_width_height_23) | Erstellt ein neues Bild mit den angegebenen Erstellungsoptionen. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_24) | Erstellt eine [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) Instanz aus dem bereitgestellten Pixelarray.<br/>            <br/>            Validiert, dass die angegebene Breite und Höhe den Abmessungen der Pixeldaten entsprechen.<br/>            Diese Methode kann nur verwendet werden, wenn die Bibliothek im lizenzierten Modus ist. |
| [create(images)](#create_images_25) | Erstellt ein neues Bild, das die angegebenen Bilder als Seiten verwendet |
| [create(images, dispose_images)](#create_images_dispose_images_26) | Erstellt ein neues Bild, wobei die angegebenen Bilder als Seiten verwendet werden. |
| [create(multipage_create_options)](#create_multipage_create_options_27) | Erstellt die angegebenen Mehrseiten‑Erstellungsoptionen. |
| [create_from_files(files)](#create_from_files_files_28) | Erstellt das Mehrseiten‑Bild, das die angegebenen Dateien als Lazy‑Loading‑Seiten enthält. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_29) | Erstellt das Mehrseiten‑Bild, das die angegebenen Dateien als Lazy‑Loading‑Seiten enthält. |
| [create_from_images(images)](#create_from_images_images_30) | Erstellt ein neues Bild, das die angegebenen Bilder als Seiten verwendet |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_31) | Erstellt ein neues Bild, wobei die angegebenen Bilder als Seiten verwendet werden. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_32) | Passen Sie den Beschnittbereich des Bildes an, indem Sie Verschiebungen mit dieser vielseitigen Methode anwenden.<br/>            Perfekt für Entwickler, die eine präzise Kontrolle über den Beschnittvorgang benötigen, um sicherzustellen,<br/>            dass wichtige Details erhalten bleiben, während unnötige Elemente entfernt werden. |
| [crop(rectangle)](#crop_rectangle_33) | Beschneiden Sie das Bild, um unerwünschte Bereiche zu entfernen und sich auf wesentliche Inhalte zu konzentrieren, mit dieser<br/>            einfachen Methode. Ideal für Entwickler, die die visuelle Zusammensetzung von<br/>            Bildern anpassen möchten, um sicherzustellen, dass sie die gewünschte Botschaft effektiv vermitteln. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_34) | Führt Dithering auf dem aktuellen Bild aus. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_35) | Verbessern Sie das aktuelle Bild, indem Sie Dithering‑Effekte mit dieser unkomplizierten<br/>            Methode anwenden. Perfekt für Entwickler, die Textur und Tiefe zu Bildern hinzufügen möchten,<br/>            um deren visuelle Qualität und Gesamteindruck zu verbessern. |
| [embed_digital_signature(password)](#embed_digital_signature_password_36) | Betten Sie eine digitale Signatur, basierend auf dem angegebenen Passwort, in jede Seite des Bildes ein. |
| [filter(rectangle, options)](#filter_rectangle_options_37) | Verbessern Sie mühelos bestimmte Bereiche Ihres Bildes, indem Sie Filter auf festgelegte<br/>            Rechtecke anwenden. Diese Methode bietet Entwicklern eine präzise Kontrolle über<br/>            die Bildmanipulation, sodass zielgerichtete Anpassungen vorgenommen werden können, um gewünschte<br/>            visuelle Effekte mit Leichtigkeit zu erzielen. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_38) | Liefert ein 32‑Bit‑ARGB‑Pixel‑Bild. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_39) | Liefert das Standard‑32‑Bit‑ARGB‑Pixel‑Array. |
| [get_default_options(args)](#get_default_options_args_40) | Liefert die Standardoptionen. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_41) | Liefert das Standard‑Pixel‑Array mittels teilweisem Pixel‑Lader. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_42) | Liefert das Standard‑Rohdaten‑Array mittels teilweisem Pixel‑Lader. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_43) | Liefert das Standard‑Rohdaten‑Array. |
| [get_file_format(file_path)](#get_file_format_file_path_44) | Liefert das Dateiformat. |
| [get_file_format(stream)](#get_file_format_stream_45) | Liefert das Dateiformat. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_46) | Liefert das Dateiformat. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_47) | Liefert das Rechteck, das zum aktuellen Bild passt. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_48) | Liefert das Rechteck, das zum aktuellen Bild passt. |
| [get_modify_date(use_default)](#get_modify_date_use_default_49) | Liefert Datum und Uhrzeit, zu der das Ressourcen‑Bild zuletzt geändert wurde. |
| [get_original_options()](#get_original_options__50) | Liefert die Optionen basierend auf den ursprünglichen Dateieinstellungen.<br/>            Dies kann hilfreich sein, um die Bit‑Tiefe und andere Parameter des Originalbildes unverändert zu lassen.<br/>            Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es anschließend mit der<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/)‑Methode speichern, wird ein PNG‑Ausgabebild mit 8 Bit pro Pixel erzeugt.<br/>            Um dies zu vermeiden und ein PNG‑Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und übergeben Sie sie<br/>            an die [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/)‑Methode als zweiten Parameter. |
| [get_pixel(x, y)](#get_pixel_x_y_51) | Liefert ein Bild‑Pixel. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_52) | Liefert eine proportionale Höhe. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_53) | Liefert eine proportionale Breite. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_54) | Konvertiert zu aps. |
| [get_skew_angle()](#get_skew_angle__55) | Liefert den Schrägungswinkel.<br/>            Diese Methode ist auf gescannte Textdokumente anwendbar, um den Schrägungswinkel beim Scannen zu bestimmen. |
| grayscale() | Transformieren Sie Bilder mühelos in ihre Graustufen‑Darstellung, wodurch die visuelle<br/>            Analyse und Verarbeitung vereinfacht wird. Perfekt für Entwickler, die die Bildklarheit verbessern,<br/>            die Komplexität reduzieren und effiziente graustufenbasierte Algorithmen<br/>            für vielfältige Anwendungen ermöglichen. |
| [insert_page(page_index)](#insert_page_page_index_56) | Fügen Sie mit dieser intuitiven<br/>            Methode eine neue Seite in die Seitenliste des Bildes an einem angegebenen Index ein. Ideal für Entwickler, die eine präzise Kontrolle über die Anordnung der Seiten in<br/>            Mehrseitenbildern benötigen, um eine nahtlose Organisation und Anpassung des Bildinhalts zu gewährleisten. |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_57) | Führt eine schnelle Prüfung durch, um festzustellen, ob das Bild digital signiert ist, wobei das bereitgestellte Passwort und der Schwellenwert verwendet werden. |
| [load(file_path)](#load_file_path_58) | Lädt ein neues Bild vom angegebenen Dateipfad oder URL.<br/>            Wenn _filePath_ ein Dateipfad ist, öffnet die Methode einfach die Datei.<br/>            Wenn _filePath_ eine URL ist, lädt die Methode die Datei herunter, speichert sie temporär und öffnet sie. |
| [load(file_path, load_options)](#load_file_path_load_options_59) | Lädt ein neues Bild vom angegebenen Dateipfad oder URL.<br/>            Wenn _filePath_ ein Dateipfad ist, öffnet die Methode einfach die Datei.<br/>            Wenn _filePath_ eine URL ist, lädt die Methode die Datei herunter, speichert sie temporär und öffnet sie. |
| [load(stream)](#load_stream_60) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load(stream, load_options)](#load_stream_load_options_61) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_62) | Lädt 32‑Bit‑ARGB‑Pixel. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_63) | Lädt 64‑Bit‑ARGB‑Pixel. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_64) | Lädt Pixel im CMYK‑Format. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_65) | Lädt Pixel im CMYK‑Format.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere Methode [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_66) | Lädt 32‑Bit‑ARGB‑Pixel teilweise (nach Blöcken). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_67) | Lädt 64‑Bit‑ARGB‑Pixel teilweise nach Paketen. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_68) | Lädt Pixel teilweise nach Paketen. |
| [load_pixels(rectangle)](#load_pixels_rectangle_69) | Lädt Pixel. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_70) | Lädt Rohdaten. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_71) | Lädt Rohdaten. |
| [load_stream(stream)](#load_stream_stream_72) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_73) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_74) | Lädt ein neues Bild vom angegebenen Dateipfad oder URL.<br/>            Wenn _filePath_ ein Dateipfad ist, öffnet die Methode einfach die Datei.<br/>            Wenn _filePath_ eine URL ist, lädt die Methode die Datei herunter, speichert sie temporär und öffnet sie. |
| normalize_angle() | Normalisiert den Winkel.<br/>            Diese Methode ist auf gescannte Textdokumente anwendbar, um die schiefe Aufnahme zu korrigieren.<br/>            Diese Methode verwendet die Methoden [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) und [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_75) | Normalisiert den Winkel.<br/>            Diese Methode ist auf gescannte Textdokumente anwendbar, um die schiefe Aufnahme zu korrigieren.<br/>            Diese Methode verwendet die Methoden [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) und [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/). |
| normalize_histogram() | Normalisiert das Bildhistogramm — passt die Pixelwerte an, um den gesamten verfügbaren Bereich zu nutzen. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_76) | Liest die gesamte Scanzeile anhand des angegebenen Scanzeilen‑Index. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_77) | Liest die gesamte Scanzeile anhand des angegebenen Scanzeilen‑Index. |
| remove_metadata() | Entfernt die Metadaten dieser Bildinstanz, indem der Wert von [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) auf **None** gesetzt wird. |
| [remove_page(page_index)](#remove_page_page_index_78) | Entfernen Sie die Seite am angegebenen Index aus der Seitenliste mit dieser praktischen Methode.<br/>            Ideal für Entwickler, die eine präzise Kontrolle über die Verwaltung von Mehrseitenbildern benötigen,<br/>            um eine nahtlose Organisation und Anpassung des Bildinhalts zu gewährleisten. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_79) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_80) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_81) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_82) | Ersetzt alle nicht‑transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.<br/>                Hinweis: Wenn Sie dies bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_83) | Ersetzt alle nicht‑transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.<br/>                Hinweis: Wenn Sie dies bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| [resize(new_width, new_height)](#resize_new_width_new_height_84) | Skaliert das Bild. Der Standardwert [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_85) | Skaliert das Bild unter Beibehaltung des Seitenverhältnisses mit dieser praktischen Methode. Ideal<br/>            für Entwickler, die die Bildabmessungen proportional anpassen möchten, um<br/>            Konsistenz zu gewährleisten und die Proportionen des Originalinhalts zu erhalten.<br/>            Die proportionale Skalierung ändert jedes Frame gemäß dem Verhältnis von _newWidth_/width und _newHeight_/height. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_86) | Passen Sie die Größe Ihres Bildes mit dieser einfachen Skalierungsmethode an. Egal, ob Sie<br/>            verkleinern oder vergrößern müssen, diese Funktion stellt sicher, dass Ihre Skalierungsanforderungen effizient und genau erfüllt werden, was sie perfekt für Entwickler macht, die schnelle und einfache Bildgrößenanpassungen suchen. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_87) | Skaliert das Bild. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_88) | Skaliert das Bild. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_89) | Skaliert die Höhe proportional. Der Standard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_90) | Passen Sie die Höhe des Bildes an, während Sie das Seitenverhältnis beibehalten, mit dieser<br/>            benutzerfreundlichen Methode. Perfekt für Entwickler, die Bilder dynamisch skalieren möchten<br/>            und dabei ihre Proportionen erhalten, um optimale Anzeige und Benutzerfreundlichkeit<br/>            in ihren Anwendungen sicherzustellen. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_91) | Skaliert die Höhe proportional. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_92) | Skaliert die Höhe proportional. |
| [resize_proportional(new_width, new_height, resize_type)](#resize_proportional_new_width_new_height_resize_type_93) | Skaliert das Bild unter Beibehaltung des Seitenverhältnisses mit dieser praktischen Methode. Ideal<br/>            für Entwickler, die die Bildabmessungen proportional anpassen möchten, um<br/>            Konsistenz zu gewährleisten und die Proportionen des Originalinhalts zu erhalten.<br/>            Die proportionale Skalierung ändert jedes Frame gemäß dem Verhältnis von _newWidth_/width und _newHeight_/height. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_94) | Skaliert die Breite proportional. Der Standard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_95) | Passen Sie die Breite des Bildes an, während Sie das Seitenverhältnis beibehalten, mit dieser praktischen<br/>            Methode. Ideal für Entwickler, die Bilder proportional skalieren möchten, um<br/>            konsistente und optisch ansprechende Ergebnisse über verschiedene Anzeigeumgebungen hinweg sicherzustellen. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_96) | Skaliert die Breite proportional. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_97) | Skaliert die Breite proportional. |
| [rotate(angle)](#rotate_angle_98) | Bild um das Zentrum drehen. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_99) | Drehen Sie das Bild um sein Zentrum mit dieser praktischen Methode. Ideal für Entwickler<br/>            die Bildausrichtung dynamisch anpassen möchten, um optimale Darstellung und<br/>            Ausrichtung in ihren Anwendungen sicherzustellen. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_100) | Manipulieren Sie einfach den aktiven Frame, indem Sie ihn drehen, spiegeln oder beide Aktionen<br/>            gleichzeitig mit dieser unkomplizierten Methode ausführen. Ideal für Entwickler, die<br/>            die Ausrichtung bestimmter Frames innerhalb ihrer Bildsequenzen dynamisch anpassen müssen,<br/>            um optimale Darstellung und Ausrichtung sicherzustellen. |
| [rotate_flip_all(rotate_flip)](#rotate_flip_all_rotate_flip_101) | Dreht das gesamte Flip. |
| save() | Speichert die Bilddaten in den zugrunde liegenden Stream. |
| [save(file_path)](#save_file_path_102) | Speichert das Bild am angegebenen Dateipfad. |
| [save(file_path, options)](#save_file_path_options_103) | Bewahren Sie die Daten des Objekts, indem Sie sie in die festgelegte Datei (Indexer + Dateiname)<br/>            speichern, zusammen mit dem angegebenen Dateiformat und Optionen. Ideal für Entwickler, die<br/>            Daten sicher in verschiedenen Formaten speichern möchten, während sie Flexibilität und Kontrolle über<br/>            die Speicherparameter beibehalten. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_104) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(file_path, over_write)](#save_file_path_over_write_105) | Speichert die Daten des Objekts am angegebenen Speicherort. |
| [save(stream)](#save_stream_106) | Speichert die Daten. |
| [save(stream, options_base)](#save_stream_options_base_107) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_108) | Speichern Sie Ihre Bilddaten einfach in einen angegebenen Stream im gewünschten Dateiformat<br/>            mit dieser praktischen Methode. Egal, ob Sie mit JPEG, PNG oder einem anderen Format arbeiten,<br/>            stellt diese Funktion sicher, dass Ihre Bilddaten effizient und genau gespeichert werden,<br/>            was sie ideal für Entwickler macht, die ihre Dateispeicherungsprozesse optimieren möchten. |
| [save_all(file_path, options)](#save_all_file_path_options_109) | Bewahren Sie die Daten des Objekts, indem Sie sie in die festgelegte Datei (Indexer + Dateiname)<br/>            speichern, zusammen mit dem angegebenen Dateiformat und Optionen. Ideal für Entwickler, die<br/>            Daten sicher in verschiedenen Formaten speichern möchten, während sie Flexibilität und Kontrolle über<br/>            die Speicherparameter beibehalten. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_110) | Speichert die 32‑Bit‑ARGB‑Pixel. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_111) | Speichert die Pixel. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_112) | Speichert die Pixel.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) Methode. |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_113) | Speichert Pixel (formatspezifische Methode). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_114) | Speichert die Rohdaten. |
| [save_to_stream(stream)](#save_to_stream_stream_115) | Speichert die Daten des Objekts in den angegebenen Stream. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_116) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_117) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_118) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_119) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_120) | Setzt ein 32‑Bit‑ARGB‑Pixel des Bildes für die angegebene Position. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_121) | Setzt die Bildpalette. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_122) | Setzt ein Bildpixel für die angegebene Position. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_123) | Passen Sie die Auflösung dieses [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) präzise mit dieser<br/>            unkomplizierten Methode an. Ideal für Entwickler, die die Bildauflösung an<br/>            spezifische Anforderungen anpassen möchten, um optimale Anzeigequalität und Dateigrößenverwaltung zu gewährleisten. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_124) | Versucht, eine _metadata_-Instanz zu setzen, falls diese [Image](/imaging/python-net/aspose.imaging/image/)‑Instanz unterstützt und eine [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)‑Instanz implementiert. |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_125) | Schreibt die gesamte Scanzeile in den angegebenen Scanzeilen‑Index. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_126) | Schreibt die gesamte Scanzeile in den angegebenen Scanzeilen‑Index. |


### Constructor: DicomImage(dicom_options, width, height) {#DicomImage_dicom_options_width_height_1}


```
 DicomImage(dicom_options, width, height) 
```

Initialisieren Sie mühelos eine neue Instanz der DicomImage-Klasse mit diesem<br/>            Konstruktor, wobei die dicomOptions-Parameter verwendet werden. Perfekt für Entwickler, die nach<br/>            einer schnellen und effizienten Einarbeitung in [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) Objekte in ihren Projekten suchen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dicom_options | [DicomOptions](/imaging/python-net/aspose.imaging.imageoptions/dicomoptions/) | Die DICOM‑Optionen. |
| width | int | Die Breite. |
| height | int | Die Höhe. |

### Constructor: DicomImage(stream) {#DicomImage_stream_2}


```
 DicomImage(stream) 
```

Erstellen Sie eine neue Instanz der DicomImage-Klasse, indem Sie einen Stream‑Parameter<br/>            in diesem Konstruktor verwenden. Perfekt für Entwickler, die nach einer schlanken Methode suchen, um [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) Objekte aus bestehenden Datenströmen in ihren Projekten zu initialisieren.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream. |


**See also:**

**[Example # 1](#example_130)**: This example shows how to load a DICOM image from a file stream.


### Constructor: DicomImage(stream, load_options) {#DicomImage_stream_load_options_3}


```
 DicomImage(stream, load_options) 
```

Starten Sie eine neue Instanz der DicomImage-Klasse reibungslos, indem Sie einen Stream‑ und<br/>            loadOptions‑Parameter in diesem Konstruktor einsetzen. Ideal für Entwickler, die eifrig sind, um schnell und effektiv mit [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) Objekten in ihren Projekten zu arbeiten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Die Ladeoptionen. |


**See also:**

**[Example # 1](#example_131)**: This example shows how to load a DICOM image from a file stream to stay withi...


### Method: add_page() {#add_page__1}


```
 add_page() 
```

Fügen Sie mit dieser einfachen Methode eine neue Seite am Ende der Seitenliste des Bildes hinzu.<br/>            Ideal für Entwickler, die mehrseitige Bilder dynamisch erweitern möchten, um eine nahtlose<br/>            Integration und Organisation des Bildinhalts zu gewährleisten.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/) | Die neu erstellte [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/). |


### Method: add_page(page) {#add_page_page_2}


```
 add_page(page) 
```

Erweitern Sie Ihre Bildsammlung, indem Sie mit dieser intuitiven Methode eine neue Seite hinzufügen.<br/>            Ideal für Entwickler, die mehrseitige Bilder dynamisch ergänzen möchten,<br/>            um eine nahtlose Erweiterung und Organisation des Bildinhalts zu gewährleisten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Die hinzuzufügende Seite. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_3}


```
 adjust_brightness(brightness) 
```

Verbessern Sie die Bildluminanz durch die Anpassung der _Helligkeit_, einer<br/>            parametrisierten Methode, die Entwicklern ermöglicht, die Leuchtkraft von Bildern fein abzustimmen.<br/>            Diese benutzerfreundliche Funktion befähigt Entwickler, die Bild<br/>            Helligkeit nahtlos zu manipulieren und bietet Flexibilität sowie Kontrolle über die visuelle Ästhetik.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Helligkeit | int | Helligkeitswert. |


**See also:**

**[Example # 1](#example_143)**: The following example performs brightness correction of a DICOM image.


### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_4}


```
 adjust_contrast(contrast) 
```

Verbessern Sie den Kontrast von [Image](/imaging/python-net/aspose.imaging/image/) mit dieser benutzerfreundlichen Methode,<br/>            die die Unterschiede zwischen hellen und dunklen Bereichen anpasst. Verbessern Sie die visuelle Klarheit und<br/>            Definition mühelos und bieten Entwicklern eine intuitive Kontrolle über<br/>            den Bildkontrast für eine optimale Darstellung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Kontrast | float | Kontrastwert (im Bereich [-100; 100]) |


**See also:**

**[Example # 1](#example_144)**: The following example performs contrast correction of a DICOM image.


### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_5}


```
 adjust_gamma(gamma) 
```

Verbessern Sie die Bildqualität und passen Sie sie mit Gamma-Korrektur an, einer leistungsstarken Technik<br/>            zur Feinabstimmung des visuellen Erscheinungsbildes. Perfekt für Entwickler, die die Bild<br/>            Darstellung optimieren, den Farbton ausgleichen und eine konsistente Wiedergabe über verschiedene<br/>            Geräte und Umgebungen hinweg sicherstellen möchten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Gamma | float | Gamma‑Koeffizient für die Rot‑, Grün‑ und Blaukanäle |


**See also:**

**[Example # 1](#example_141)**: The following example performs gamma-correction of a DICOM image.


### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_6}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Erreichen Sie präzise Farbkorrekturen, indem Sie Gamma-Korrektur unabhängig<br/>            von den roten, grünen und blauen Komponenten eines Bildes anwenden. Diese Methode gewährleistet eine genaue<br/>            Farbbalance und optimale visuelle Ausgabe und richtet sich an Entwickler, die eine feinkörnige<br/>            Kontrolle über die Bilddarstellung und Farbgenauigkeit wünschen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| gamma_red | float | Gamma‑Koeffizient für den Rotkanal |
| gamma_green | float | Gamma‑Koeffizient für den Grünkanal |
| gamma_blue | float | Gamma für den Blaukanal-Koeffizienten |


**See also:**

**[Example # 1](#example_142)**: The following example performs gamma-correction of a DICOM image applying dif...


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

Binarisieren Sie Bilder mit Bradleys adaptivem Schwellenwertalgorithmus und nutzen Sie dabei die Integralbild-<br/>            Schwellenwertbestimmung für verbesserte Leistung. Ideal für Entwickler, die<br/>            Bilder automatisch anhand lokaler Helligkeitsvariationen segmentieren möchten, um<br/>            eine genaue Objekterkennung und -extraktion bei unterschiedlichen Lichtbedingungen sicherzustellen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brightness_difference | float | Der Helligkeitsunterschied zwischen dem Pixel und dem Durchschnitt eines s x s Fensters von Pixeln<br/>            das um dieses Pixel zentriert ist. |
| window_size | int | Die Größe des s x s Fensters von Pixeln, das um dieses Pixel zentriert ist. |


**See also:**

**[Example # 1](#example_139)**: The following example binarizes a DICOM image with Bradley's adaptive thresho...


### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_10}


```
 binarize_fixed(threshold) 
```

Konvertieren Sie das Bild einfach in ein Binärformat mithilfe eines vordefinierten Schwellenwerts<br/>            mit dieser unkomplizierten Methode. Ideal für Entwickler, die Bildverarbeitungsaufgaben vereinfachen möchten, indem sie das Bild anhand festgelegter Intensitätsstufen in Vorder- und Hintergrundkomponenten<br/>            segmentieren.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Schwellenwert | System.Byte | Schwellenwert. Wenn der entsprechende Grauwert eines Pixels größer als der Schwellenwert ist, wird ihm ein Wert von<br/>            255 zugewiesen, sonst 0. |


**See also:**

**[Example # 1](#example_137)**: The following example binarizes a DICOM image with the predefined threshold. ...


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


### Method: create_from_files(files)  [static] {#create_from_files_files_28}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_29}


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


### Method: create_from_images(images)  [static] {#create_from_images_images_30}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_31}


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


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_32}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Passen Sie den Beschnittbereich des Bildes an, indem Sie Verschiebungen mit dieser vielseitigen Methode anwenden.<br/>            Perfekt für Entwickler, die eine präzise Kontrolle über den Beschnittvorgang benötigen, um sicherzustellen,<br/>            dass wichtige Details erhalten bleiben, während unnötige Elemente entfernt werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| left_shift | int | Die linke Verschiebung. |
| right_shift | int | Die rechte Verschiebung. |
| top_shift | int | Die obere Verschiebung. |
| bottom_shift | int | Die untere Verschiebung. |


**See also:**

**[Example # 1](#example_136)**: The following example crops a DICOM image. The cropping area is specified via...


### Method: crop(rectangle) {#crop_rectangle_33}


```
 crop(rectangle) 
```

Beschneiden Sie das Bild, um unerwünschte Bereiche zu entfernen und sich auf wesentliche Inhalte zu konzentrieren, mit dieser<br/>            einfachen Methode. Ideal für Entwickler, die die visuelle Zusammensetzung von<br/>            Bildern anpassen möchten, um sicherzustellen, dass sie die gewünschte Botschaft effektiv vermitteln.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck. |


**See also:**

**[Example # 1](#example_135)**: The following example crops a DICOM image. The cropping area is be specified ...


### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_34}


```
 dither(dithering_method, bits_count) 
```

Führt Dithering auf dem aktuellen Bild aus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Die Dithering-Methode. |
| bits_count | int | Die endgültige Bitanzahl für das Dithern. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_35}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Verbessern Sie das aktuelle Bild, indem Sie Dithering‑Effekte mit dieser unkomplizierten<br/>            Methode anwenden. Perfekt für Entwickler, die Textur und Tiefe zu Bildern hinzufügen möchten,<br/>            um deren visuelle Qualität und Gesamteindruck zu verbessern.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Die Dithering-Methode. |
| bits_count | int | Die endgültige Bitanzahl für das Dithern. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die benutzerdefinierte Palette für das Dithern. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_36}


```
 embed_digital_signature(password) 
```

Betten Sie eine digitale Signatur, basierend auf dem angegebenen Passwort, in jede Seite des Bildes ein.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Passwort | string | Das Passwort, das zum Erzeugen digitaler Signaturdaten verwendet wird |

### Method: filter(rectangle, options) {#filter_rectangle_options_37}


```
 filter(rectangle, options) 
```

Verbessern Sie mühelos bestimmte Bereiche Ihres Bildes, indem Sie Filter auf festgelegte<br/>            Rechtecke anwenden. Diese Methode bietet Entwicklern eine präzise Kontrolle über<br/>            die Bildmanipulation, sodass zielgerichtete Anpassungen vorgenommen werden können, um gewünschte<br/>            visuelle Effekte mit Leichtigkeit zu erzielen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Die Optionen. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_38}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_39}


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


### Method: get_default_options(args) {#get_default_options_args_40}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_41}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Liefert das Standard‑Pixel‑Array mittels teilweisem Pixel‑Lader.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, für das die Pixel abgerufen werden. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Der partielle Pixel‑Lader. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_42}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_43}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_44}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_45}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_46}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_47}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_48}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_49}


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


### Method: get_original_options() {#get_original_options__50}


```
 get_original_options() 
```

Liefert die Optionen basierend auf den ursprünglichen Dateieinstellungen.<br/>            Dies kann hilfreich sein, um die Bit‑Tiefe und andere Parameter des Originalbildes unverändert zu lassen.<br/>            Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es anschließend mit der<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/)‑Methode speichern, wird ein PNG‑Ausgabebild mit 8 Bit pro Pixel erzeugt.<br/>            Um dies zu vermeiden und ein PNG‑Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und übergeben Sie sie<br/>            an die [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/)‑Methode als zweiten Parameter.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Optionen basierend auf den ursprünglichen Dateieinstellungen. |


### Method: get_pixel(x, y) {#get_pixel_x_y_51}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_52}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_53}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_54}


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


### Method: get_skew_angle() {#get_skew_angle__55}


```
 get_skew_angle() 
```

Liefert den Schrägungswinkel.<br/>            Diese Methode ist auf gescannte Textdokumente anwendbar, um den Schrägungswinkel beim Scannen zu bestimmen.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float | Der Schrägwinkel in Grad. |


### Method: insert_page(page_index) {#insert_page_page_index_56}


```
 insert_page(page_index) 
```

Fügen Sie mit dieser intuitiven<br/>            Methode eine neue Seite in die Seitenliste des Bildes an einem angegebenen Index ein. Ideal für Entwickler, die eine präzise Kontrolle über die Anordnung der Seiten in<br/>            Mehrseitenbildern benötigen, um eine nahtlose Organisation und Anpassung des Bildinhalts zu gewährleisten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page_index | int | Index der Seite. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/) | Die neu erstellte [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/). |


### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_57}


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


### Method: load(file_path)  [static] {#load_file_path_58}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_59}


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


### Method: load(stream)  [static] {#load_stream_60}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_61}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_62}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_63}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_64}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_65}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_66}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Lädt 32‑Bit‑ARGB‑Pixel teilweise (nach Blöcken).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, aus dem Pixel geladen werden. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Der partielle Pixel‑Lader. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_67}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Lädt 64‑Bit‑ARGB‑Pixel teilweise nach Paketen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das gewünschte Rechteck. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | Der 64-bit ARGB-Pixel-Lader. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_68}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Lädt Pixel teilweise nach Paketen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das gewünschte Rechteck. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Der Pixel-Lader. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_69}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_70}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_71}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_72}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_73}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_74}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_75}


```
 normalize_angle(resize_proportionally, background_color) 
```

Normalisiert den Winkel.<br/>            Diese Methode ist auf gescannte Textdokumente anwendbar, um die schiefe Aufnahme zu korrigieren.<br/>            Diese Methode verwendet die Methoden [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) und [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| resize_proportionally | bool | Wenn auf <c>true</c> gesetzt, wird die Bildgröße gemäß den Projektionen des gedrehten Rechtecks (Eckpunkte) geändert; andernfalls bleiben die Abmessungen unverändert und nur der Bildinhalt wird rotiert. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Farbe des Hintergrunds. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_76}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_77}


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


### Method: remove_page(page_index) {#remove_page_page_index_78}


```
 remove_page(page_index) 
```

Entfernen Sie die Seite am angegebenen Index aus der Seitenliste mit dieser praktischen Methode.<br/>            Ideal für Entwickler, die eine präzise Kontrolle über die Verwaltung von Mehrseitenbildern benötigen,<br/>            um eine nahtlose Organisation und Anpassung des Bildinhalts zu gewährleisten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page_index | int | Index der Seite. |

### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_79}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_80}


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

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_81}


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

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_82}


```
 replace_non_transparent_colors(new_color) 
```

Ersetzt alle nicht‑transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.<br/>                Hinweis: Wenn Sie dies bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_83}


```
 replace_non_transparent_colors(new_color_argb) 
```

Ersetzt alle nicht‑transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.<br/>                Hinweis: Wenn Sie dies bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_color_argb | int | Neuer ARGB-Farbwert, um nicht-transparente Farben zu ersetzen. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_84}


```
 resize(new_width, new_height) 
```

Skaliert das Bild. Der Standardwert [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_85}


```
 resize(new_width, new_height, resize_type) 
```

Skaliert das Bild unter Beibehaltung des Seitenverhältnisses mit dieser praktischen Methode. Ideal<br/>            für Entwickler, die die Bildabmessungen proportional anpassen möchten, um<br/>            Konsistenz zu gewährleisten und die Proportionen des Originalinhalts zu erhalten.<br/>            Die proportionale Skalierung ändert jedes Frame gemäß dem Verhältnis von _newWidth_/width und _newHeight_/height.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Der Skalierungstyp. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_86}


```
 resize(new_width, new_height, settings) 
```

Passen Sie die Größe Ihres Bildes mit dieser einfachen Skalierungsmethode an. Egal, ob Sie<br/>            verkleinern oder vergrößern müssen, diese Funktion stellt sicher, dass Ihre Skalierungsanforderungen effizient und genau erfüllt werden, was sie perfekt für Entwickler macht, die schnelle und einfache Bildgrößenanpassungen suchen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Skalierungseinstellungen. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_87}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_88}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_89}


```
 resize_height_proportionally(new_height) 
```

Skaliert die Höhe proportional. Der Standard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_90}


```
 resize_height_proportionally(new_height, resize_type) 
```

Passen Sie die Höhe des Bildes an, während Sie das Seitenverhältnis beibehalten, mit dieser<br/>            benutzerfreundlichen Methode. Perfekt für Entwickler, die Bilder dynamisch skalieren möchten<br/>            und dabei ihre Proportionen erhalten, um optimale Anzeige und Benutzerfreundlichkeit<br/>            in ihren Anwendungen sicherzustellen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ der Skalierung. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_91}


```
 resize_height_proportionally(new_height, settings) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Bildskalierungseinstellungen. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_92}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Bildskalierungseinstellungen. |

### Method: resize_proportional(new_width, new_height, resize_type) {#resize_proportional_new_width_new_height_resize_type_93}


```
 resize_proportional(new_width, new_height, resize_type) 
```

Skaliert das Bild unter Beibehaltung des Seitenverhältnisses mit dieser praktischen Methode. Ideal<br/>            für Entwickler, die die Bildabmessungen proportional anpassen möchten, um<br/>            Konsistenz zu gewährleisten und die Proportionen des Originalinhalts zu erhalten.<br/>            Die proportionale Skalierung ändert jedes Frame gemäß dem Verhältnis von _newWidth_/width und _newHeight_/height.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Der Skalierungstyp. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_94}


```
 resize_width_proportionally(new_width) 
```

Skaliert die Breite proportional. Der Standard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_95}


```
 resize_width_proportionally(new_width, resize_type) 
```

Passen Sie die Breite des Bildes an, während Sie das Seitenverhältnis beibehalten, mit dieser praktischen<br/>            Methode. Ideal für Entwickler, die Bilder proportional skalieren möchten, um<br/>            konsistente und optisch ansprechende Ergebnisse über verschiedene Anzeigeumgebungen hinweg sicherzustellen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ der Skalierung. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_96}


```
 resize_width_proportionally(new_width, settings) 
```

Skaliert die Breite proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Bildskalierungseinstellungen. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_97}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Skaliert die Breite proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Die Bildskalierungseinstellungen. |

### Method: rotate(angle) {#rotate_angle_98}


```
 rotate(angle) 
```

Bild um das Zentrum drehen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_99}


```
 rotate(angle, resize_proportionally, background_color) 
```

Drehen Sie das Bild um sein Zentrum mit dieser praktischen Methode. Ideal für Entwickler<br/>            die Bildausrichtung dynamisch anpassen möchten, um optimale Darstellung und<br/>            Ausrichtung in ihren Anwendungen sicherzustellen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |
| resize_proportionally | bool | wenn auf <c>true</c> gesetzt, wird die Bildgröße geändert<br/>            entsprechend den Projektionen des gedrehten Rechtecks (Eckpunkte) im anderen<br/>            Fall bleiben die Abmessungen unverändert und nur<br/>            __internal__ Bildinhalte werden gedreht. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Farbe des Hintergrunds. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_100}


```
 rotate_flip(rotate_flip_type) 
```

Manipulieren Sie einfach den aktiven Frame, indem Sie ihn drehen, spiegeln oder beide Aktionen<br/>            gleichzeitig mit dieser unkomplizierten Methode ausführen. Ideal für Entwickler, die<br/>            die Ausrichtung bestimmter Frames innerhalb ihrer Bildsequenzen dynamisch anpassen müssen,<br/>            um optimale Darstellung und Ausrichtung sicherzustellen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Der Rotations-Flip-Typ. |


**See also:**

**[Example # 1](#example_132)**: This example loads a DICOM image, rotates it by 90 degrees clockwise and opti...


### Method: rotate_flip_all(rotate_flip) {#rotate_flip_all_rotate_flip_101}


```
 rotate_flip_all(rotate_flip) 
```

Dreht das gesamte Flip.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rotate_flip | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Der Rotations-Flip. |

### Method: save(file_path) {#save_file_path_102}


```
 save(file_path) 
```

Speichert das Bild am angegebenen Dateipfad.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem das Bild gespeichert wird. |

### Method: save(file_path, options) {#save_file_path_options_103}


```
 save(file_path, options) 
```

Bewahren Sie die Daten des Objekts, indem Sie sie in die festgelegte Datei (Indexer + Dateiname)<br/>            speichern, zusammen mit dem angegebenen Dateiformat und Optionen. Ideal für Entwickler, die<br/>            Daten sicher in verschiedenen Formaten speichern möchten, während sie Flexibilität und Kontrolle über<br/>            die Speicherparameter beibehalten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Optionen. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_104}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_105}


```
 save(file_path, over_write) 
```

Speichert die Daten des Objekts am angegebenen Speicherort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Objektdaten gespeichert werden. |
| over_write | bool | wenn auf <c>true</c> gesetzt, werden die Dateiinhalte überschrieben, andernfalls wird angehängt. |

### Method: save(stream) {#save_stream_106}


```
 save(stream) 
```

Speichert die Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem Daten gespeichert werden. |

### Method: save(stream, options_base) {#save_stream_options_base_107}


```
 save(stream, options_base) 
```

Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem die Bilddaten gespeichert werden. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Speicheroptionen. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_108}


```
 save(stream, options_base, bounds_rectangle) 
```

Speichern Sie Ihre Bilddaten einfach in einen angegebenen Stream im gewünschten Dateiformat<br/>            mit dieser praktischen Methode. Egal, ob Sie mit JPEG, PNG oder einem anderen Format arbeiten,<br/>            stellt diese Funktion sicher, dass Ihre Bilddaten effizient und genau gespeichert werden,<br/>            was sie ideal für Entwickler macht, die ihre Dateispeicherungsprozesse optimieren möchten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem die Bilddaten gespeichert werden. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Speicheroptionen. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Zielrechteck der Bildgrenzen. Setzen Sie das leere Rechteck, um Quellgrenzen zu verwenden. |


**See also:**

**[Example # 1](#example_133)**: The following example loads a DICOM image from a file, then saves the image t...


### Method: save_all(file_path, options) {#save_all_file_path_options_109}


```
 save_all(file_path, options) 
```

Bewahren Sie die Daten des Objekts, indem Sie sie in die festgelegte Datei (Indexer + Dateiname)<br/>            speichern, zusammen mit dem angegebenen Dateiformat und Optionen. Ideal für Entwickler, die<br/>            Daten sicher in verschiedenen Formaten speichern möchten, während sie Flexibilität und Kontrolle über<br/>            die Speicherparameter beibehalten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Optionen. |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_110}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Speichert die 32‑Bit‑ARGB‑Pixel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, in dem Pixel gespeichert werden. |
| Pixel | int[] | Das 32‑Bit‑ARGB‑Pixel‑Array. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_111}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Speichert die Pixel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, in dem Pixel gespeichert werden. |
| Pixel | int[] | Die CMYK‑Pixel, dargestellt als 32‑Bit‑Ganzzahlwerte. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_112}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Speichert die Pixel.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) Methode.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, in dem Pixel gespeichert werden. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Das CMYK‑Pixel‑Array. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_113}


```
 save_pixels(rectangle, pixels) 
```

Speichert Pixel (formatspezifische Methode).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck, in dem Pixel gespeichert werden. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Das Pixel‑Array. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_114}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_115}


```
 save_to_stream(stream) 
```

Speichert die Daten des Objekts in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem die Daten des Objekts gespeichert werden sollen. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_116}


```
 save_to_stream_with_options(stream, options_base) 
```

Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem die Bilddaten gespeichert werden. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Speicheroptionen. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_117}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_118}


```
 save_with_options(file_path, options) 
```

Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Optionen. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_119}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_120}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_121}


```
 set_palette(palette, update_colors) 
```

Setzt die Bildpalette.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die zu setzende Palette. |
| update_colors | bool | Wenn auf <c>true</c> gesetzt, werden die Farben gemäß der neuen Palette aktualisiert; andernfalls bleiben die Farbindizes unverändert. Hinweis: Unveränderte Indizes können das Bild beim Laden zum Absturz bringen, wenn einige Indizes keinen entsprechenden Paletteneintrag haben. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_122}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_123}


```
 set_resolution(dpi_x, dpi_y) 
```

Passen Sie die Auflösung dieses [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) präzise mit dieser<br/>            unkomplizierten Methode an. Ideal für Entwickler, die die Bildauflösung an<br/>            spezifische Anforderungen anpassen möchten, um optimale Anzeigequalität und Dateigrößenverwaltung zu gewährleisten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dpi_x | float | Die horizontale Auflösung in Punkten pro Zoll des [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | Die vertikale Auflösung in Punkten pro Zoll des [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_124}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_125}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Schreibt die gesamte Scanzeile in den angegebenen Scanzeilen‑Index.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| scan_line_index | int | Nullbasierter Index der Scan-Zeile. |
| argb_32_pixels | int[] | Das 32‑Bit‑ARGB‑Farben‑Array zum Schreiben. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_126}


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
### This example shows how to load a DICOM image from a file stream. {#example_130}
``` python
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp"
# Laden Sie ein DICOM‑Bild aus einem Dateistream.
with open(join(dir_, "sample.dicom"), "rb") as stream:
	with DicomImage(stream) as dicom_image:
		# Speichern Sie jede Seite als einzelnes PNG‑Bild.
		for dicom_page in dicom_image.dicom_pages:
			# Generieren Sie einen Dateinamen basierend auf dem Seitenindex.
			file_name = "sample.{0}.png".format(dicom_page.index)
			# Eine DICOM‑Seite ist ein Rasterbild, daher sind alle zulässigen Operationen mit einem Rasterbild auf eine DICOM‑Seite anwendbar.
			dicom_page.save(join(dir_, file_name), PngOptions())


```

### This example shows how to load a DICOM image from a file stream to stay within the specified memory limit. {#example_131}
``` python
from aspose.imaging import LoadOptions, Image
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.dicom import DicomImage
from os.path import join as path_join


dir_: str = "c:\\temp"
# Laden Sie ein DICOM‑Bild aus einem Dateistream.
with open(path_join(dir_, "multiframe.dicom"), "rb") as stream:
	# Die maximal zulässige Größe für alle internen Puffer beträgt 256 KB.
	load_options = LoadOptions()
	load_options.buffer_size_hint = 256 * 1024
	with DicomImage(stream, load_options) as dicom_image:
		# Speichern Sie jede Seite als einzelnes PNG‑Bild.
		for dicom_page in dicom_image.dicom_pages:
			# Generieren Sie einen Dateinamen basierend auf dem Seitenindex.
			file_name = "multiframe.{0}.png".format(dicom_page.index)
			# Eine DICOM‑Seite ist ein Rasterbild, daher sind alle zulässigen Operationen mit einem Rasterbild auf eine DICOM‑Seite anwendbar.
			dicom_page.save(path_join(dir_, file_name), PngOptions())


```

### This example loads a DICOM image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically. {#example_132}
``` python

from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image, RotateFlipType
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = "c:\\temp"
rotate_flip_types = [RotateFlipType.ROTATE_90_FLIP_NONE, RotateFlipType.ROTATE_90_FLIP_X, RotateFlipType.ROTATE_90_FLIP_XY, RotateFlipType.ROTATE_90_FLIP_Y]
for rotate_flip_type in rotate_flip_types:
	# Drehen, spiegeln und in die Ausgabedatei speichern.
	with aspycore.as_of(Image.load(join(dir_, "sample.dicom")), DicomImage) as image:
		image.rotate_flip(rotate_flip_type)
		image.save(join(dir_, "sample." + rotate_flip_type + ".png"), PngOptions())


```

### The following example loads a DICOM image from a file, then saves the image to a PNG file stream. {#example_133}
``` python

from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image, Rectangle
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions     

dir_: str = "c:\\temp"
with aspycore.as_of(Image.load(join(dir_, "sample.dicom")), DicomImage) as image:
	save_options = PngOptions()
	bounds = Rectangle(0, 0, image.width // 2, image.height // 2)
	with open(join(dir_, "output.png"), "wb") as output_stream:
		# Speichern Sie das obere linke Viertel des Bildes in einen Dateistream.
		image.save(output_stream, save_options, bounds)


```

### The following example crops a DICOM image. The cropping area is be specified via aspose.imaging.Rectangle. {#example_135}
``` python

from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image, Rectangle
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions    


dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# Beschneiden Sie das Bild. Der Beschneidungsbereich ist der rechteckige zentrale Bereich des Bildes.
	area = Rectangle(dicom_image.width // 4, dicom_image.height // 4, dicom_image.width // 2, dicom_image.height // 2)
	dicom_image.crop(area)
	# Speichern Sie das beschnittene Bild als PNG
	dicom_image.save(join(dir_, "sample.Crop.png"), PngOptions())


```

### The following example crops a DICOM image. The cropping area is specified via Left, Top, Right, Bottom margins. {#example_136}
``` python
from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = r"c:\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# Erneut zuschneiden. Setzen Sie einen Rand von 10 % der Bildgröße.
	horizontal_margin = dicom_image.width // 10
	vertical_margin = dicom_image.height // 10
	dicom_image.crop(horizontal_margin, horizontal_margin, vertical_margin, vertical_margin)
	# Speichern Sie das zugeschnittene Bild als PNG.
	dicom_image.save(join(dir_, "sample.Crop.png"), PngOptions())


```

### The following example binarizes a DICOM image with the predefined threshold. Binarized images contain only 2 colors - black and white. {#example_137}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.dicom import DicomImage
from os.path import join

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# Binarisieren Sie das Bild mit einem Schwellenwert von 127.
	# Wenn ein entsprechender Grauwert eines Pixels größer als 127 ist, wird ihm der Wert 255 zugewiesen, sonst 0.
	dicom_image.binarize_fixed(127)
	dicom_image.save(join(dir_, "sample.BinarizeFixed.png"), PngOptions())


```

### The following example binarizes a DICOM image with Bradley's adaptive thresholding algorithm with the specified window size. Binarized images contain only 2 colors - black and white. {#example_139}
``` python

from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# Binarisieren Sie das Bild mit einem Helligkeitsunterschied von 5. Die Helligkeit ist die Differenz zwischen einem Pixel und dem Durchschnitt eines 10 × 10‑Fensters von Pixeln, das um diesen Pixel zentriert ist.
	dicom_image.binarize_bradley(5, 10)
	dicom_image.save(join(dir_, "sample.BinarizeBradley5_10x10.png"), PngOptions())


```

### The following example performs gamma-correction of a DICOM image. {#example_141}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join


dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# Setzen Sie den Gamma‑Koeffizienten für die Rot‑, Grün‑ und Blau‑Kanäle.
	dicom_image.adjust_gamma(2.5)
	dicom_image.save(join(dir_, "sample.AdjustGamma.png"), PngOptions())


```

### The following example performs gamma-correction of a DICOM image applying different coefficients for color components. {#example_142}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# Setzen Sie individuelle Gamma‑Koeffizienten für die Rot‑, Grün‑ und Blau‑Kanäle.
	dicom_image.adjust_gamma(1.5, 2.5, 3.5)
	dicom_image.save(join(dir_, "sample.AdjustGamma.png"), PngOptions())


```

### The following example performs brightness correction of a DICOM image. {#example_143}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# Setzen Sie den Helligkeitswert. Die zulässigen Helligkeitswerte liegen im Bereich [-255, 255].
	dicom_image.adjust_brightness(50)
	dicom_image.save(join(dir_, "sample.AdjustBrightness.png"), PngOptions())


```

### The following example performs contrast correction of a DICOM image. {#example_144}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# Setzen Sie den Kontrastwert. Die zulässigen Kontrastwerte liegen im Bereich [-100f, 100f].
	dicom_image.adjust_contrast(50.0)
	dicom_image.save(join(dir_, "sample.AdjustContrast.png"), PngOptions())


```

### Use JPEG compression in DICOM image. {#example_211}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.imageoptions import JpegOptions, DicomOptions
from aspose.imaging.fileformats.jpeg import JpegCompressionMode, SampleRoundingMode
from aspose.imaging.imageoptions import DicomOptions
from aspose.imaging.fileformats.dicom import Compression, ColorType, CompressionType

with Image.load("original.jpg") as input_image:
	obj_init = JpegOptions()
	obj_init.compression_type = JpegCompressionMode.BASELINE
	obj_init.sample_rounding_mode = SampleRoundingMode.TRUNCATE
	obj_init.quality = 50
	obj_init2 = Compression()
	obj_init2.type = CompressionType.JPEG
	obj_init2.jpeg = obj_init
	options = DicomOptions()
	options.color_type = ColorType.RGB_24_BIT
	options.compression = obj_init2
	input_image.save("original_JPEG.dcm", options)


```

### Use JPEG 2000 compression in DICOM image. {#example_212}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.imageoptions import Jpeg2000Options, DicomOptions
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Codec, Compression, CompressionType, ColorType

with Image.load("original.jpg") as input_image:
	obj_init = Jpeg2000Options()
	obj_init.codec = Jpeg2000Codec.JP2
	obj_init.irreversible = False
	obj_init2 = Compression()
	obj_init2.type_ = CompressionType.JPEG2000
	obj_init2.jpeg2000 = obj_init
	options = DicomOptions()
	options.color_type = ColorType.RGB_24_BIT
	options.compression = obj_init2
	input_image.save("original_JPEG2000.dcm", options)


```

### Use RLE compression in DICOM image. {#example_213}
``` python

from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import Compression, CompressionType, ColorType
from aspose.imaging.imageoptions import DicomOptions

with Image.load("original.jpg") as input_image:
	compr = Compression()
	compr.type_ = CompressionType.RLE
	options = DicomOptions()
	options.color_type = ColorType.RGB_24_BIT
	options.compression = compr
	input_image.save("original_RLE.dcm", options)


```

### Change the color type in DICOM compression. {#example_214}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import DicomOptions
from aspose.imaging.fileformats.dicom import ColorType

with Image.load("original.jpg") as inputImage:
	options = DicomOptions()
	options.color_type = ColorType.GRAYSCALE_8_BIT
	inputImage.save("original_8Bit.dcm", options)


```

