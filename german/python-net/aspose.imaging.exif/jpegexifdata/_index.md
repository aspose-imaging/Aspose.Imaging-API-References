---
title: "JpegExifData‑Klasse"
type: docs
weight: 40
url: /de/python-net/aspose.imaging.exif/jpegexifdata/
---

**Summary:** EXIF data container for jpeg files.

**Module:** [aspose.imaging.exif](/imaging/python-net/aspose.imaging.exif/)

**Full Name:** aspose.imaging.exif.JpegExifData

**Inheritance:** IImageMetadataFormat, ExifData

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [JpegExifData()](#JpegExifData__1) | Initialisiert eine neue Instanz der [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) Klasse. |
| [JpegExifData(common_tags, exif_tags, gps_tags)](#JpegExifData_common_tags_exif_tags_gps_tags_2) | Initialisiert eine neue Instanz der [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) Klasse mit Daten aus dem Array. |
| [JpegExifData(exifdata)](#JpegExifData_exifdata_3) | Initialisiert eine neue Instanz der [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) Klasse mit Daten aus dem Array. |
| [JpegExifData(exifdata)](#JpegExifData_exifdata_4) | Initialisiert eine neue Instanz der [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) Klasse mit Daten aus dem Array. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| MAX_EXIF_SEGMENT_SIZE [static] | int | r | Die maximal zulässige EXIF‑Segmentgröße in Bytes. |
| aperture_value | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt den Blendenwert. |
| artist | string | r/w | Liest oder setzt den Künstler. |
| bits_per_sample | int[] | r/w | Liest oder setzt die Bits pro Sample. |
| body_serial_number | string | r/w | Liest oder setzt die Seriennummer des Kameragehäuses. |
| brightness_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | Liest oder setzt den Helligkeitswert. |
| camera_owner_name | string | r/w | Liest oder setzt den Namen des Kamerabesitzers. |
| cfa_pattern | System.Byte | r/w | Liest oder setzt das CFA-Muster. |
| color_space | [ExifColorSpace](/imaging/python-net/aspose.imaging.exif.enums/exifcolorspace/) | r/w | Liest oder setzt den Farbraum. |
| common_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Liest oder setzt Tags, die zum gemeinsamen Abschnitt gehören. Dies gilt nur für JPEG-Bilder; im TIFF-Format werden stattdessen tiffOptions verwendet. |
| components_configuration | System.Byte | r/w | Liest oder setzt die Komponenten-Konfiguration. |
| compressed_bits_per_pixel | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die komprimierten Bits pro Pixel. |
| Kompression | int | r/w | Liest oder setzt die Kompression. |
| contrast | [ExifContrast](/imaging/python-net/aspose.imaging.exif.enums/exifcontrast/) | r/w | Liest oder setzt den Kontrast. |
| Urheberrecht | string | r/w | Liest oder setzt das Urheberrecht. |
| custom_rendered | [ExifCustomRendered](/imaging/python-net/aspose.imaging.exif.enums/exifcustomrendered/) | r/w | Liest oder setzt die benutzerdefinierte Darstellung. |
| date_time | string | r/w | Liest oder setzt das Datum und die Uhrzeit. |
| date_time_digitized | string | r/w | Liest oder setzt das digitalisierte Datum und die Uhrzeit. |
| date_time_original | string | r/w | Liest oder setzt das ursprüngliche Datum und die Uhrzeit. |
| device_setting_description | System.Byte | r/w | Liest oder setzt die Beschreibung der Geräteeinstellungen. |
| digital_zoom_ratio | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt das digitale Zoomverhältnis. |
| exif_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Liest oder setzt Tags, die nur zum EXIF-Abschnitt gehören. |
| exif_version | System.Byte | r/w | Liest oder setzt die EXIF-Version. |
| exposure_bias_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | Liest oder setzt den Belichtungskorrekturwert. |
| exposure_index | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt den Belichtungsindex. |
| exposure_mode | [ExifExposureMode](/imaging/python-net/aspose.imaging.exif.enums/exifexposuremode/) | r/w | Liest oder setzt den Belichtungsmodus. |
| exposure_program | [ExifExposureProgram](/imaging/python-net/aspose.imaging.exif.enums/exifexposureprogram/) | r/w | Liest oder setzt das Belichtungsprogramm. |
| exposure_time | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die Belichtungszeit. |
| f_number | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die Blendenzahl. |
| file_source | [ExifFileSource](/imaging/python-net/aspose.imaging.exif.enums/exiffilesource/) | r/w | Liest oder setzt den Dateiquelltyp. |
| flash | [ExifFlash](/imaging/python-net/aspose.imaging.exif.enums/exifflash/) | r/w | Liest oder setzt den Blitz. |
| flash_energy | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die Blitzenergie. |
| flashpix_version | System.Byte | r/w | Liest oder setzt die Flash-Pix-Version. |
| focal_length | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die Brennweite. |
| focal_length_in_35_mm_film | int | r/w | Liest oder setzt die Brennweite in 35‑mm-Film. |
| focal_plane_resolution_unit | [ExifUnit](/imaging/python-net/aspose.imaging.exif.enums/exifunit/) | r/w | Liest oder setzt die Auflösungseinheit der Bildebene. |
| focal_plane_x_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die X-Auflösung der Bildebene. |
| focal_plane_y_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die Y-Auflösung der Bildebene. |
| gain_control | [ExifGainControl](/imaging/python-net/aspose.imaging.exif.enums/exifgaincontrol/) | r/w | Liest oder setzt den Grad der Gesamtsignalverstärkungsanpassung des Bildes. |
| gamma | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt das Gamma. |
| gps_altitude | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die GPS-Höhe. |
| gps_altitude_ref | [ExifGPSAltitudeRef](/imaging/python-net/aspose.imaging.exif.enums/exifgpsaltituderef/) | r/w | Liest oder setzt die GPS-Höhe, die als Referenzhöhe verwendet wird. |
| gps_area_information | System.Byte | r/w | Ruft die GPS-Bereichsinformation ab oder legt sie fest. |
| gps_date_stamp | string | r/w | Ruft die GPS-Zeichenkette mit Datum- und Zeitinformationen relativ zu UTC (Koordinierte Weltzeit) ab oder legt sie fest. |
| gps_dest_bearing | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ruft die GPS-Richtung zum Zielpunkt ab oder legt sie fest. |
| gps_dest_bearing_ref | string | r/w | Ruft die GPS-Referenz ab, die zur Angabe der Richtung zum Zielpunkt verwendet wird, oder legt sie fest. |
| gps_dest_distance | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ruft die GPS-Entfernung zum Zielpunkt ab oder legt sie fest. |
| gps_dest_distance_ref | string | r/w | Ruft die GPS-Einheit ab, die zur Angabe der Entfernung zum Zielpunkt verwendet wird, oder legt sie fest. |
| gps_dest_latitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ruft den GPS-Breitengrad des Zielpunkts ab oder legt ihn fest. |
| gps_dest_latitude_ref | string | r/w | Ruft den GPS-Wert ab, der angibt, ob der Breitengrad des Zielpunkts nördlich oder südlich ist, oder legt ihn fest. |
| gps_dest_longitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ruft den GPS-Längengrad des Zielpunkts ab oder legt ihn fest. |
| gps_dest_longitude_ref | string | r/w | Ruft den GPS-Wert ab, der angibt, ob der Längengrad des Zielpunkts östlich oder westlich ist, oder legt ihn fest. |
| gps_differential | int | r/w | Ruft einen GPS-Wert ab, der angibt, ob eine differentielle Korrektur auf den GPS-Empfänger angewendet wird, oder legt ihn fest. |
| gps_img_direction | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ruft die GPS-Richtung des Bildes zum Zeitpunkt der Aufnahme ab oder legt sie fest. |
| gps_img_direction_ref | string | r/w | Ruft die GPS-Referenz ab, die zur Angabe der Bildrichtung bei der Aufnahme verwendet wird, oder legt sie fest. |
| gps_latitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ruft den GPS-Breitengrad ab oder legt ihn fest. |
| gps_latitude_ref | string | r/w | Ruft ab oder legt fest, ob der GPS-Breitengrad nördlich oder südlich ist. |
| gps_longitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ruft den GPS-Längengrad ab oder legt ihn fest. |
| gps_longitude_ref | string | r/w | Ruft ab oder legt fest, ob der GPS-Längengrad östlich oder westlich ist. |
| gps_map_datum | string | r/w | Ruft ab oder legt fest, die vom GPS-Empfänger verwendeten geodätischen Vermessungsdaten. |
| gps_measure_mode | string | r/w | Ruft ab oder legt fest, den GPS-Messmodus. |
| gps_processing_method | System.Byte | r/w | Ruft ab oder legt fest, die GPS-Zeichenkette, die den Namen der für die Standortbestimmung verwendeten Methode enthält. |
| gps_satellites | string | r/w | Ruft ab oder legt fest, die für Messungen verwendeten GPS-Satelliten. |
| gps_speed | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ruft ab oder legt fest, die Geschwindigkeit der GPS-Empfängerbewegung. |
| gps_speed_ref | string | r/w | Ruft ab oder legt fest, die Einheit, die zur Angabe der Geschwindigkeit der GPS-Empfängerbewegung verwendet wird. |
| gps_status | string | r/w | Ruft ab oder legt fest, den Status des GPS-Empfängers, wenn das Bild aufgenommen wird. |
| gps_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Ruft ab oder legt fest, Tags, die ausschließlich zum GPS-Abschnitt gehören. |
| gps_timestamp | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ruft ab oder legt fest, die GPS-Zeit als UTC (Koordinierte Weltzeit). |
| gps_track | string | r/w | Ruft ab oder legt fest, die Richtung der GPS-Empfängerbewegung. |
| gps_track_ref | string | r/w | Ruft ab oder legt fest, die Referenz zur Angabe der Richtung der GPS-Empfängerbewegung. |
| gps_version_id | System.Byte | r/w | Ruft ab oder legt fest, den GPS-Versionsidentifikator. |
| gpsdop | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ruft ab oder legt fest, den GPS-DOP (Datengrad der Präzision). |
| image_description | string | r/w | Liest oder setzt die Bildbeschreibung. |
| image_length | int | r/w | Liest oder setzt die Bildlänge. |
| image_unique_id | string | r/w | Ruft ab oder legt fest, die eindeutige Bildkennung. |
| image_width | int | r/w | Liest oder setzt die Bildbreite. |
| is_big_endian | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die aus dem Stream erstellten EXIF-Daten im Big-Endian-Format vorliegen. |
| iso_speed | int | r/w | Liest oder setzt die ISO-Geschwindigkeit |
| iso_speed_latitude_yyy | int | r/w | Liest oder setzt den ISO-Geschwindigkeits-Latituden-yyy-Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist. |
| iso_speed_latitude_zzz | int | r/w | Liest oder setzt den ISO-Geschwindigkeits-Latituden-zzz-Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist. |
| iso_speed_value | int | r/w | Liest oder setzt den ISO-Geschwindigkeitswert. |
| lens_make | string | r/w | Liest oder setzt den Hersteller des Objektivs. |
| lens_model | string | r/w | Liest oder setzt das Objektivmodell. |
| lens_serial_number | string | r/w | Liest oder setzt die Seriennummer des Objektivs. |
| lens_specification | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die Objektivspezifikation |
| light_source | [ExifLightSource](/imaging/python-net/aspose.imaging.exif.enums/exiflightsource/) | r/w | Liest oder setzt die Lichtquelle. |
| make | string | r/w | Liest oder setzt den Hersteller der Aufzeichnungsgeräte. |
| maker_note_data | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r | Liest die Hersteller-Notizdaten. |
| maker_note_raw_data | System.Byte | r/w | Liest oder setzt die rohen Hersteller-Notizdaten. |
| maker_notes | [MakerNote[]](/imaging/python-net/aspose.imaging.exif/makernote/) | r | Liest die Hersteller-Notizen. |
| max_aperture_value | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt den maximalen Blendenwert. |
| metering_mode | [ExifMeteringMode](/imaging/python-net/aspose.imaging.exif.enums/exifmeteringmode/) | r/w | Ruft den Messmodus ab oder legt ihn fest. |
| model | string | r/w | Liest oder setzt das Modell. |
| oecf | System.Byte | r/w | Ruft die Opto-elektrische Umwandlungsfunktion (OECF) gemäß ISO 14524 ab oder legt sie fest. |
| orientation | [ExifOrientation](/imaging/python-net/aspose.imaging.exif.enums/exiforientation/) | r/w | Ruft die Ausrichtung ab oder legt sie fest. |
| photographic_sensitivity | int | r/w | Ruft die fotografische Empfindlichkeit ab oder legt sie fest. |
| photometric_interpretation | int | r/w | Liest oder setzt die photometrische Interpretation. |
| pixel_x_dimension | int | r/w | Ruft die Pixel-X-Dimension ab oder legt sie fest. |
| pixel_y_dimension | int | r/w | Ruft die Pixel-Y-Dimension ab oder legt sie fest. |
| planar_configuration | int | r/w | Liest oder setzt die planare Konfiguration. |
| primary_chromaticities | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die Chromatik der drei Primärfarben des Bildes. |
| properties | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Ruft alle EXIF-Tags (einschließlich gängiger und GPS-Tags) ab oder legt sie fest. |
| recommended_exposure_index | int | r/w | Ruft den empfohlenen Belichtungsindex ab oder legt ihn fest. |
| reference_black_white | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt das Referenz‑Schwarz‑Weiß. |
| related_sound_file | string | r/w | Ruft die zugehörige Audiodatei ab oder legt sie fest. |
| resolution_unit | [ExifUnit](/imaging/python-net/aspose.imaging.exif.enums/exifunit/) | r/w | Liest oder setzt die Auflösungseinheit. |
| samples_per_pixel | int | r/w | Liest oder setzt die Stichproben pro Pixel. |
| saturation | [ExifSaturation](/imaging/python-net/aspose.imaging.exif.enums/exifsaturation/) | r/w | Ruft die Sättigung ab oder legt sie fest. |
| scene_capture_type | [ExifSceneCaptureType](/imaging/python-net/aspose.imaging.exif.enums/exifscenecapturetype/) | r/w | Ruft den Aufnahmetyp der Szene ab oder legt ihn fest. |
| scene_type | System.Byte | r/w | Ruft den Szenentyp ab oder legt ihn fest. |
| sensing_method | [ExifSensingMethod](/imaging/python-net/aspose.imaging.exif.enums/exifsensingmethod/) | r/w | Ruft die Erfassungsmethode ab oder legt sie fest. |
| sensitivity_type | int | r/w | Ruft den Empfindlichkeitstyp ab oder legt ihn fest. |
| sharpness | int | r/w | Ruft die Schärfe ab oder legt sie fest. |
| shutter_speed_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | Ruft den Verschlusszeitwert ab oder legt ihn fest. |
| Software | string | r/w | Liest oder setzt die Software. |
| spatial_frequency_response | System.Byte | r/w | Liest oder setzt die räumliche Frequenzantwort. |
| spectral_sensitivity | string | r/w | Liest oder setzt die spektrale Empfindlichkeit. |
| standard_output_sensitivity | int | r/w | Liest oder setzt die Standardausgabeempfindlichkeit |
| subject_area | int[] | r/w | Liest oder setzt den Betreffbereich. |
| subject_distance | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt den Abstand zum Motiv. |
| subject_distance_range | [ExifSubjectDistanceRange](/imaging/python-net/aspose.imaging.exif.enums/exifsubjectdistancerange/) | r/w | Liest oder setzt den Abstandbereich zum Motiv. |
| subject_location | int[] | r/w | Liest oder setzt den Ort des Motivs. |
| subsec_time | string | r/w | Liest oder setzt die Sekundenbruchteile für das DateTime-Tag. |
| subsec_time_digitized | string | r/w | Liest oder setzt die Sekundenbruchteile für das DateTimeDigitized-Tag. |
| subsec_time_original | string | r/w | Liest oder setzt die Sekundenbruchteile für das DateTimeOriginal-Tag. |
| thumbnail | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | r/w | Liest oder setzt das Vorschaubild. |
| transfer_function | int[] | r/w | Liest oder setzt die Transferfunktion. |
| user_comment | string | r/w | Liest oder setzt den Benutzerkommentar. |
| white_balance | [ExifWhiteBalance](/imaging/python-net/aspose.imaging.exif.enums/exifwhitebalance/) | r/w | Liest oder setzt den Weißabgleich. |
| white_point | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die Chromatik des Weißpunkts des Bildes. |
| x_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die X-Auflösung. |
| y_cb_cr_coefficients | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die Matrixkoeffizienten für die Umwandlung von RGB- in YCbCr-Bilddaten. |
| y_cb_cr_positioning | [ExifYCbCrPositioning](/imaging/python-net/aspose.imaging.exif.enums/exifycbcrpositioning/) | r/w | Liest oder setzt die Position der Chrominanzkomponenten in Relation zur Luminanzkomponente. |
| y_cb_cr_sub_sampling | int[] | r/w | Liest oder setzt das Abtastverhältnis der Chrominanzkomponenten in Relation zur Luminanzkomponente. |
| y_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die y‑Auflösung. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_tag_value(key)](#get_tag_value_key_1) | Liest den Tagwert. |
| [load_from_bytes(binary_data)](#load_from_bytes_binary_data_2) | Erstellt eine neue Instanz der [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) Klasse, indem sie aus dem Byte‑Array geladen wird. |
| [remove_tag(tag)](#remove_tag_tag_3) | Tag aus dem Container entfernen |
| [remove_tag(tag_id)](#remove_tag_tag_id_4) | Tag aus dem Container entfernen |
| [remove_tag_id(tag_id)](#remove_tag_id_tag_id_5) | Tag aus dem Container entfernen |
| [serialize_exif_data()](#serialize_exif_data__6) | Serialisiert die EXIF-Daten. Schreibt die Tag-Werte und Inhalte. Das am stärksten einflussnehmende Größentag ist der Thumbnail-Tag-Inhalt. |


### Constructor: JpegExifData() {#JpegExifData__1}


```
 JpegExifData() 
```

Initialisiert eine neue Instanz der [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) Klasse.

### Constructor: JpegExifData(common_tags, exif_tags, gps_tags) {#JpegExifData_common_tags_exif_tags_gps_tags_2}


```
 JpegExifData(common_tags, exif_tags, gps_tags) 
```

Initialisiert eine neue Instanz der [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) Klasse mit Daten aus dem Array.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Die gängigen Tags. |
| exif_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Die EXIF‑Tags. |
| gps_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Die GPS‑Tags. |

### Constructor: JpegExifData(exifdata) {#JpegExifData_exifdata_3}


```
 JpegExifData(exifdata) 
```

Initialisiert eine neue Instanz der [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) Klasse mit Daten aus dem Array.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Array von EXIF‑Tags zusammen mit gängigen und GPS‑Tags. |

### Constructor: JpegExifData(exifdata) {#JpegExifData_exifdata_4}


```
 JpegExifData(exifdata) 
```

Initialisiert eine neue Instanz der [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) Klasse mit Daten aus dem Array.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| exifdata | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | Array von EXIF‑Tags zusammen mit gängigen und GPS‑Tags. |

### Method: get_tag_value(key) {#get_tag_value_key_1}


```
 get_tag_value(key) 
```

Liest den Tagwert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | [ExifProperties](/imaging/python-net/aspose.imaging.exif/exifproperties/) | Der Tag‑Schlüssel. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Der TiffDataType |


### Method: load_from_bytes(binary_data)  [static] {#load_from_bytes_binary_data_2}


```
 load_from_bytes(binary_data) 
```

Erstellt eine neue Instanz der [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) Klasse, indem sie aus dem Byte‑Array geladen wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| binary_data | System.Byte | Die Binärdaten. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | Die geladene ExifData‑Instanz. |


### Method: remove_tag(tag) {#remove_tag_tag_3}


```
 remove_tag(tag) 
```

Tag aus dem Container entfernen

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tag | [ExifProperties](/imaging/python-net/aspose.imaging.exif/exifproperties/) | Der zu entfernende Tag |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_4}


```
 remove_tag(tag_id) 
```

Tag aus dem Container entfernen

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tag_id | int | Der zu entfernende Tag‑Bezeichner. |

### Method: remove_tag_id(tag_id) {#remove_tag_id_tag_id_5}


```
 remove_tag_id(tag_id) 
```

Tag aus dem Container entfernen

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tag_id | int | Der zu entfernende Tag‑Bezeichner. |

### Method: serialize_exif_data() {#serialize_exif_data__6}


```
 serialize_exif_data() 
```

Serialisiert die EXIF-Daten. Schreibt die Tag-Werte und Inhalte. Das am stärksten einflussnehmende Größentag ist der Thumbnail-Tag-Inhalt.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Byte | Die serialisierten EXIF-Daten. |


