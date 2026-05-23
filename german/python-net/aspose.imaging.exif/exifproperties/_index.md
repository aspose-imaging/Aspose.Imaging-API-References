---
title: "ExifProperties-Aufzählung"
type: docs
weight: 190
url: /de/python-net/aspose.imaging.exif/exifproperties/
---

Exif‑Tags‑Liste

**Module:** [aspose.imaging.exif](/imaging/python-net/aspose.imaging.exif/)

**Full Name:** aspose.imaging.exif.ExifProperties

## **Members**
| **Member name** | **Beschreibung** |
| :- | :- |
| APERTURE_VALUE | Der Blendenwert des Objektivs. |
| ARTIST | Dieser Tag zeichnet den Namen des Kamerabesitzers, Fotografen oder Bild-Erstellers auf. Das genaue Format ist nicht festgelegt, aber es wird empfohlen, die Informationen wie im untenstehenden Beispiel für eine bessere Interoperabilität zu schreiben. Wenn das Feld leer gelassen wird, gilt es als unbekannt. Beispiel: "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James" |
| BITS_PER_SAMPLE | Die Anzahl der Bits pro Bildkomponente. In diesem Standard hat jede Komponente des Bildes 8 Bits, daher ist der Wert für dieses Tag 8. |
| BODY_SERIAL_NUMBER | Enthält die Seriennummer des Kameragehäuses |
| BRIGHTNESS_VALUE | Der Helligkeitswert. |
| CAMERA_OWNER_NAME | Enthält den Namen des Kamerabesitzers |
| CFA_PATTERN | Gibt das geometrische Muster des Farbfilter-Arrays (CFA) des Bildsensors an, wenn ein Ein-Chip-Farbflächen-Sensor verwendet wird. Es gilt nicht für alle Erfassungsmethoden. |
| COLOR_SPACE | Das Farbraum-Informations-Tag (ColorSpace) wird immer als Farbraumspezifikator aufgezeichnet. |
| COMPONENTS_CONFIGURATION | Die Konfiguration der Komponenten. |
| COMPRESSED_BITS_PER_PIXEL | Spezifisch für komprimierte Daten; gibt die komprimierten Bits pro Pixel an. |
| COMPRESSION | Das Komprimierungsschema, das für die Bilddaten verwendet wird. Wenn ein primäres Bild JPEG-komprimiert ist, ist diese Bezeichnung nicht erforderlich und wird weggelassen. |
| CONTRAST | Dieses Tag gibt die Richtung der vom Kamerasystem angewendeten Kontrastverarbeitung an, die beim Aufnehmen des Bildes verwendet wurde. |
| COPYRIGHT | Copyright‑Informationen. In diesem Standard wird das Tag verwendet, um<br/>                sowohl die Urheberrechte des Fotografen als auch des Editors anzugeben. Es ist<br/>                der Urheberrechtshinweis der Person oder Organisation, die<br/>                Rechte an dem Bild beansprucht. Die Interoperabilitäts‑Urheberrechtserklärung<br/>                einschließlich Datum und Rechte sollte in diesem<br/>                Feld geschrieben werden; z. B. \"Copyright, John Smith, 19xx. Alle Rechte<br/>                vorbehalten.\". In diesem Standard erfasst das Feld sowohl die<br/>                Urheberrechte des Fotografen als auch des Editors, wobei jedes in einem<br/>                separaten Teil der Erklärung aufgezeichnet wird. Wenn eine klare Unterscheidung<br/>                zwischen den Urheberrechten des Fotografen und des Editors besteht, sind diese<br/>                in der Reihenfolge Fotograf gefolgt vom Editor‑Urheberrecht zu schreiben,<br/>                getrennt durch NULL (in diesem Fall, da die Erklärung ebenfalls mit<br/>                einem NULL endet, gibt es zwei NULL‑Codes). Wenn nur das Urheberrecht des Fotografen<br/>                angegeben ist, wird es durch einen NULL‑Code beendet. Wenn nur das Urheberrecht des Editors<br/>                angegeben ist, besteht der Fotografen‑Urheberrechtsteil aus einem Leerzeichen, gefolgt von einem abschließenden NULL‑Code, dann wird das Editor‑Urheberrecht angegeben. Wenn das Feld leer gelassen wird, gilt es als unbekannt. |
| CUSTOM_RENDERED | Dieses Tag weist auf die Verwendung einer speziellen Verarbeitung der Bilddaten hin, z. B. auf die Ausgabe‑orientierte Darstellung. Wenn eine spezielle Verarbeitung durchgeführt wird, sollte der Leser weitere Verarbeitungen deaktivieren oder minimieren. |
| DATE_TIME | Datum und Uhrzeit der Bildanlage. Im Exif‑Standard ist dies das Datum und die Uhrzeit, zu der die Datei geändert wurde. |
| DATE_TIME_DIGITIZED | Das digitalisierte Datum und die Uhrzeit. |
| DATE_TIME_ORIGINAL | Datum und Uhrzeit, zu der die ursprünglichen Bilddaten erzeugt wurden. |
| DEVICE_SETTING_DESCRIPTION | Dieses Tag gibt Informationen zu den Aufnahmebedingungen eines bestimmten Kameramodells an. Das Tag wird nur verwendet, um die Aufnahmebedingungen im Reader anzuzeigen. |
| DIGITAL_ZOOM_RATIO | Dieses Tag gibt das digitale Zoom‑Verhältnis an, das beim Aufnehmen des Bildes verwendet wurde. Wenn der Zähler des aufgezeichneten Werts 0 ist, bedeutet dies, dass kein digitaler Zoom verwendet wurde. |
| EXIF_IFD_POINTER | Ein Zeiger auf das Exif‑IFD. Interoperabilität, das Exif‑IFD hat dieselbe Struktur wie das in TIFF spezifizierte IFD. gewöhnlich enthält es jedoch keine Bilddaten, wie im Fall von TIFF. |
| EXIF_VERSION | Die Exif‑Version. |
| EXPOSURE_BIAS_VALUE | Der Belichtungswert. |
| EXPOSURE_INDEX | Gibt den bei der Aufnahme des Bildes ausgewählten Belichtungsindex der Kamera oder des Eingabegeräts an. |
| EXPOSURE_MODE | Dieses Tag gibt den beim Aufnehmen des Bildes eingestellten Belichtungsmodus an. Im Auto‑Bracketing‑Modus nimmt die Kamera eine Reihe von Aufnahmen derselben Szene mit unterschiedlichen Belichtungseinstellungen auf. |
| EXPOSURE_PROGRAM | Die Klasse des Programms, das von der Kamera verwendet wird, um die Belichtung beim Aufnehmen des Bildes einzustellen. |
| EXPOSURE_TIME | Belichtungszeit, angegeben in Sekunden. |
| FILE_SOURCE | Die Dateiquelle. |
| FLASH | Gibt den Blitzstatus zum Zeitpunkt der Aufnahme des Bildes an. |
| FLASHPIX_VERSION | Die von einer FPXR-Datei unterstützte Flashpix-Formatversion. |
| FLASH_ENERGY | Gibt die Blitzenergie zum Zeitpunkt der Aufnahme des Bildes an, gemessen in Beam Candle Power Seconds (BCPS). |
| FOCAL_LENGTH | Die tatsächliche Brennweite des Objektivs in mm. |
| FOCAL_LENGTH_IN_35_MM_FILM | Dieses Tag gibt die äquivalente Brennweite an, angenommen eine 35‑mm-Filmkamera, in mm. Ein Wert von 0 bedeutet, dass die Brennweite unbekannt ist. Hinweis: Dieses Tag unterscheidet sich vom Tag FocalLength. |
| FOCAL_PLANE_RESOLUTION_UNIT | Gibt die Einheit für die Messung von FocalPlaneXResolution und FocalPlaneYResolution an. Dieser Wert entspricht dem ResolutionUnit. |
| FOCAL_PLANE_X_RESOLUTION | Gibt die Anzahl der Pixel in Bildbreite (X) pro FocalPlaneResolutionUnit auf der Kamera‑Bildebene an. |
| FOCAL_PLANE_Y_RESOLUTION | Gibt die Anzahl der Pixel in Bildhöhe (Y) pro FocalPlaneResolutionUnit auf der Kamera‑Bildebene an. |
| F_NUMBER | Die F-Nummer. |
| GAIN_CONTROL | Dieses Tag gibt den Grad der gesamten Bildverstärkungsanpassung an. |
| GAMMA | Gamma-Wert |
| GPSDOP | Gibt den GPS-DOP (Datenpräzisionsgrad) an. Ein HDOP-Wert wird bei zweidimensionaler Messung geschrieben,<br/>                und ein PDOP bei dreidimensionaler Messung. |
| GPS_ALTITUDE | Gibt die Höhe basierend auf dem Verweis in GPSAltitudeRef an. Die Höhe wird als ein RATIONAL-Wert ausgedrückt.<br/>                Die Referenzeinheit ist Meter. |
| GPS_ALTITUDE_REF | Gibt die als Referenzhöhe verwendete Höhe an. Wenn die Referenz Meereshöhe ist und die Höhe über dem Meeresspiegel liegt,<br/>                wird 0 angegeben. Liegt die Höhe unter dem Meeresspiegel, wird der Wert 1 angegeben und die Höhe wird als absoluter Wert im<br/>                GPSAltitude-Tag angegeben. |
| GPS_AREA_INFORMATION | Eine Zeichenkette, die den Namen des GPS-Gebiets aufzeichnet. Das erste Byte gibt<br/>                den verwendeten Zeichencode an, gefolgt vom Namen des GPS-Gebiets. |
| GPS_DATE_STAMP | Eine Zeichenkette, die Datums- und Zeitinformationen relativ zu UTC<br/>                (Koordinierte Weltzeit). Das Format ist JJJJ:MM:TT. |
| GPS_DEST_BEARING | Gibt die Peilung zum Zielpunkt an. Der Wertebereich liegt zwischen 0,00 und 359,99. |
| GPS_DEST_BEARING_REF | Gibt die Referenz an, die für die Angabe der Peilung zum Zielpunkt verwendet wird. 'T' steht für wahre Richtung und 'M' für<br/>                magnetische Richtung. |
| GPS_DEST_DISTANCE | Gibt die Entfernung zum Zielpunkt an. |
| GPS_DEST_DISTANCE_REF | Gibt die Einheit an, die zur Angabe der Entfernung zum Zielpunkt verwendet wird. 'K', 'M' und 'N' stehen für Kilometer, Meilen<br/>                und Knoten. |
| GPS_DEST_LATITUDE | Gibt die Breite des Zielpunkts an. Die Breite wird als drei RATIONAL-Werte angegeben, die jeweils Grad, Minuten und Sekunden darstellen.<br/>                Wenn die Breite als Grad, Minuten und Sekunden angegeben wird, wäre ein typisches Format dd/1,mm/1,ss/1. Werden Grad und Minuten verwendet und beispielsweise Bruchteile von Minuten bis zu zwei Dezimalstellen angegeben, wäre das Format dd/1,mmmm/100,0/1. |
| GPS_DEST_LATITUDE_REF | Gibt an, ob die Breite des Zielpunkts nördliche oder südliche Breite ist. Der ASCII-Wert 'N' steht für nördliche<br/>                Breite, und 'S' für südliche Breite. |
| GPS_DEST_LONGITUDE | Gibt die Länge des Zielpunkts an. Die Länge wird als drei RATIONAL-Werte angegeben, die jeweils Grad, Minuten und Sekunden darstellen.<br/>                Wenn die Länge als Grad, Minuten und Sekunden angegeben wird, wäre ein typisches Format ddd/1,mm/1,ss/1. Werden Grad und Minuten verwendet und beispielsweise Bruchteile von Minuten bis zu zwei Dezimalstellen angegeben, wäre das Format ddd/1,mmmm/100,0/1. |
| GPS_DEST_LONGITUDE_REF | Gibt an, ob die Länge des Zielpunkts östliche oder westliche Länge ist. ASCII 'E' steht für östliche Länge,<br/>                und 'W' für westliche Länge. |
| GPS_DIFFERENTIAL | Gibt an, ob eine differentielle Korrektur auf den GPS-Empfänger angewendet wird. |
| GPS_IFD_POINTER | Der gps ifd pointer. |
| GPS_IMG_DIRECTION | Gibt die Richtung des Bildes an, als es aufgenommen wurde. Der Wertebereich liegt zwischen 0,00 und 359,99. |
| GPS_IMG_DIRECTION_REF | Gibt die Referenz für die Angabe der Bildrichtung bei der Aufnahme an. 'T' steht für wahre Richtung und 'M' für<br/>                magnetische Richtung. |
| GPS_LATITUDE | Gibt die Breite an. Die Breite wird als drei RATIONAL-Werte angegeben, die jeweils Grad, Minuten und Sekunden darstellen.<br/>                Wenn die Breite als Grad, Minuten und Sekunden angegeben wird, wäre ein typisches Format dd/1,mm/1,ss/1. Werden Grad und Minuten verwendet und beispielsweise Bruchteile von Minuten bis zu zwei Dezimalstellen angegeben, wäre das Format dd/1,mmmm/100,0/1. |
| GPS_LATITUDE_REF | Gibt an, ob die Breite nördliche oder südliche Breite ist. |
| GPS_LONGITUDE | Gibt die Länge an. Die Länge wird als drei RATIONAL-Werte angegeben, die jeweils Grad, Minuten und Sekunden darstellen.<br/>                Wenn die Länge als Grad, Minuten und Sekunden angegeben wird, wäre ein typisches Format ddd/1,mm/1,ss/1. Werden Grad und Minuten verwendet und beispielsweise Bruchteile von Minuten bis zu zwei Dezimalstellen angegeben, wäre das Format ddd/1,mmmm/100,0/1. |
| GPS_LONGITUDE_REF | Gibt an, ob die Länge östliche oder westliche Länge ist. |
| GPS_MAP_DATUM | Gibt die vom GPS-Empfänger verwendeten geodätischen Vermessungsdaten an. |
| GPS_MEASURE_MODE | Gibt den GPS-Messmodus an. - 2- oder 3- dimensional. |
| GPS_PROCESSING_METHOD | Eine Zeichenkette, die den Namen der für die Positionsbestimmung verwendeten Methode aufzeichnet.<br/>                Das erste Byte gibt den verwendeten Zeichencode an, gefolgt vom Namen<br/>                der Methode. |
| GPS_SATELLITES | Gibt die für Messungen verwendeten GPS‑Satelliten an. Dieses Tag kann verwendet werden, um die Anzahl der Satelliten,<br/>                deren ID‑Nummer, Elevationswinkel, Azimut, SNR und weitere Informationen in ASCII‑Notation zu beschreiben. Das Format ist nicht<br/>                spezifiziert. Wenn der GPS‑Empfänger keine Messungen durchführen kann, muss der Wert des Tags auf NULL gesetzt werden. |
| GPS_SPEED | Gibt die Geschwindigkeit der GPS‑Empfängerbewegung an. |
| GPS_SPEED_REF | Gibt die Einheit an, die zur Angabe der Geschwindigkeit der GPS‑Empfängerbewegung verwendet wird. 'K', 'M' und 'N' stehen für Kilometer pro<br/>                Stunde, Meilen pro Stunde und Knoten. |
| GPS_STATUS | Gibt den Status des GPS‑Empfängers zum Zeitpunkt der Bildaufnahme an. |
| GPS_TIMESTAMP | Gibt die Zeit als UTC (Coordinated Universal Time) an. Der Zeitstempel wird als drei RATIONAL‑Werte ausgedrückt<br/>                für Stunde, Minute und Sekunde. |
| GPS_TRACK | Gibt die Richtung der GPS‑Empfängerbewegung an. Der Wertebereich liegt zwischen 0,00 und 359,99. |
| GPS_TRACK_REF | Gibt die Referenz für die Angabe der Richtung der GPS‑Empfängerbewegung an. 'T' steht für wahre Richtung und 'M' für<br/>                magnetische Richtung. |
| GPS_VERSION_ID | Gibt die Version von GPSInfoIFD an. |
| IMAGE_DESCRIPTION | Eine Zeichenkette, die den Titel des Bildes angibt. Es kann ein Kommentar sein, z. B. "1988 Firmenpicknick" oder Ähnliches. |
| IMAGE_LENGTH | Die Anzahl der Zeilen der Bilddaten. |
| IMAGE_UNIQUE_ID | Die eindeutige Bild-ID. |
| IMAGE_WIDTH | Die Anzahl der Spalten der Bilddaten, gleich der Anzahl der Pixel pro Zeile. |
| ISO_SPEED | Informationen zum ISO-Geschwindigkeitswert wie in ISO 12232 definiert |
| ISO_SPEED_LATITUDE_YYY | Dieses Tag gibt den ISO-Geschwindigkeitsbreitenwert yyy an, wie in ISO 12232 definiert |
| ISO_SPEED_LATITUDE_ZZZ | Dieses Tag gibt den ISO-Geschwindigkeitsbreitenwert zzz an, wie in ISO 12232 definiert |
| JPEG_INTERCHANGE_FORMAT | Der Offset zum Startbyte (SOI) der JPEG-komprimierten Vorschaudaten. Dies wird nicht für die primären JPEG-Bilddaten verwendet. |
| JPEG_INTERCHANGE_FORMAT_LENGTH | Die Anzahl der Bytes der JPEG-komprimierten Vorschaudaten. Dies wird nicht für die primären JPEG-Bilddaten verwendet. JPEG-Vorschaubilder werden nicht aufgeteilt, sondern als durchgehender JPEG-Bitstream von SOI bis EOI aufgezeichnet. Appn- und COM-Markierungen sollten nicht aufgezeichnet werden. Komprimierte Vorschaubilder dürfen nicht mehr als 64 KB umfassen, einschließlich aller anderen in APP1 aufzuzeichnenden Daten. |
| LENS_MAKE | Dieses Tag zeichnet den Linsenhersteller auf |
| LENS_MODEL | Dieses Tag zeichnet den Modellnamen und die Modellnummer des Objektivs auf |
| LENS_SERIAL_NUMBER | Dieses Tag zeichnet die Seriennummer des austauschbaren Objektivs auf |
| LENS_SPECIFICATION | Dieses Tag gibt die minimale Brennweite, maximale Brennweite, die minimale Blendenzahl bei der minimalen Brennweite und die minimale Blendenzahl bei der maximalen Brennweite an |
| LIGHT_SOURCE | Die Art der Lichtquelle. |
| MAKE | Der Hersteller der Aufzeichnungsgeräte. Dies ist der Hersteller der DSC, des Scanners, des Video-Digitalisierers oder anderer Geräte, die das Bild erzeugt haben. Wenn das Feld leer bleibt, wird es als unbekannt behandelt. |
| MAKER_NOTE | Ein Tag für Hersteller von Exif-Schreibern, um beliebige gewünschte Informationen zu speichern. Der Inhalt liegt im Ermessen des Herstellers, aber dieses Tag sollte nicht für andere Zwecke als den beabsichtigten verwendet werden. |
| MAX_APERTURE_VALUE | Der maximale Blendenwert. |
| METERING_MODE | Der Messmodus. |
| MODEL | Der Modellname oder die Modellnummer der Ausrüstung. Dies ist der Modellname oder die Nummer der DSC, des Scanners, des Video-Digitalisierers oder anderer Geräte, die das Bild erzeugt haben. Wenn das Feld leer bleibt, wird es als unbekannt behandelt. |
| OECF | Gibt die Opto‑Elektrische Umwandlungsfunktion (OECF) an, die in ISO 14524 spezifiziert ist. |
| ORIENTATION | Die Bildorientierung, dargestellt in Zeilen und Spalten. |
| PHOTOGRAPHIC_SENSITIVITY | Gibt die ISO‑Geschwindigkeit und ISO‑Latitude der Kamera oder des Eingabegeräts an, wie in ISO 12232 festgelegt. |
| PHOTOMETRIC_INTERPRETATION | Die Pixelzusammensetzung. |
| PIXEL_X_DIMENSION | Informationsspezifisch für komprimierte Daten. Wenn eine komprimierte Datei aufgezeichnet wird, muss die gültige Breite des bedeutungsvollen Bildes in diesem Tag gespeichert werden, unabhängig davon, ob Pad‑Daten oder ein Neustart‑Marker vorhanden sind. |
| PIXEL_Y_DIMENSION | Informationsspezifisch für komprimierte Daten. Wenn eine komprimierte Datei aufgezeichnet wird, muss die gültige Höhe des bedeutungsvollen Bildes in diesem Tag gespeichert werden. |
| PLANAR_CONFIGURATION | Gibt an, ob Pixelkomponenten in einem chunky‑ oder planar‑Format gespeichert werden. Wenn dieses Feld nicht existiert, wird der TIFF‑Standardwert 1 (chunky) angenommen. |
| PRIMARY_CHROMATICITIES | Die Chromatik der drei Primärfarben des Bildes. Normalerweise ist dieses Tag nicht erforderlich, da der Farbraum im Farbrauminformations‑Tag ColorSpace angegeben wird. |
| RECOMMENDED_EXPOSURE_INDEX | Gibt den empfohlenen Belichtungsindex an |
| REFERENCE_BLACK_WHITE | Der Referenzschwarzpunktwert und der Referenzweißpunktwert<br/>                Wert. In TIFF werden keine Vorgaben bereitgestellt, aber die untenstehenden Werte werden hier als Vorgaben angegeben.<br/>                Der Farbraum wird<br/>                in einem Farbrauminformations-Tag deklariert, wobei die Vorgabe<br/>                der Wert ist, der die optimalen Bildeigenschaften<br/>                Interoperabilität unter diesen Bedingungen liefert |
| RELATED_SOUND_FILE | Die zugehörige Audiodatei. |
| RESOLUTION_UNIT | Die Einheit zur Messung von XResolution und YResolution. Die gleiche Einheit wird für sowohl XResolution als auch YResolution verwendet. Wenn die Bildauflösung unbekannt ist, wird 2 (Zoll) angegeben. |
| ROWS_PER_STRIP | Die Anzahl der Zeilen pro Streifen. Dies ist die Zeilenanzahl im Bild eines Streifens, wenn ein Bild in Streifen aufgeteilt wird. |
| SAMPLES_PER_PIXEL | Die Anzahl der Komponenten pro Pixel. Da dieser Standard für RGB- und YCbCr-Bilder gilt, ist der für dieses Tag festgelegte Wert 3. |
| SATURATION | Dieses Tag gibt die Richtung der Sättigungsbearbeitung an, die von der Kamera beim Aufnehmen des Bildes angewendet wurde. |
| SCENE_CAPTURE_TYPE | Dieses Tag gibt den Typ der aufgenommenen Szene an. Es kann auch verwendet werden, um den Aufnahmemodus des Bildes zu speichern. |
| SCENE_TYPE | Gibt den Typ der Szene an. Wenn ein DSC das Bild aufgenommen hat, muss dieser Tag-Wert immer auf 1 gesetzt werden, was bedeutet, dass das Bild direkt fotografiert wurde. |
| SENSING_METHOD | Gibt den Bildsensors-Typ an der Kamera oder am Eingabegerät an. |
| SENSITIVITY_TYPE | Typ der fotografischen Empfindlichkeit |
| SHARPNESS | Dieses Tag gibt die Richtung der Schärfebearbeitung an, die von der Kamera beim Aufnehmen des Bildes angewendet wurde |
| SHUTTER_SPEED_VALUE | Der Wert der Verschlusszeit. |
| SOFTWARE | Dieses Tag zeichnet den Namen und die Version der Software oder Firmware der Kamera oder des Bildaufnahmegeräts auf, das zur Erstellung des Bildes verwendet wurde. Das genaue Format ist nicht festgelegt, es wird jedoch empfohlen, das unten gezeigte Beispiel zu befolgen. Wenn das Feld leer bleibt, wird es als unbekannt behandelt. |
| SPATIAL_FREQUENCY_RESPONSE | Dieses Tag zeichnet die räumliche Frequenztabelle der Kamera oder des Eingabegeräts sowie die SFR‑Werte in Richtung Bildbreite, Bildhöhe und Diagonalrichtung auf, wie in ISO 12233 angegeben. |
| SPECTRAL_SENSITIVITY | Gibt die spektrale Empfindlichkeit jedes Kanals der verwendeten Kamera an. |
| STANDARD_OUTPUT_SENSITIVITY | Gibt die standardmäßige Ausgangsempfindlichkeit der Kamera an. |
| STRIP_BYTE_COUNTS | Die Gesamtzahl der Bytes in jedem Streifen. |
| STRIP_OFFSETS | Für jeden Streifen der Byte‑Versatz dieses Streifens. Es wird empfohlen, dies so zu wählen, dass die Anzahl der Streifen‑Bytes 64 KB nicht überschreitet.<br/>                Aux‑Tag. |
| SUBJECT_AREA | Dieses Tag gibt die Position und den Bereich des Hauptmotivs in der Gesamtszene an. |
| SUBJECT_DISTANCE | Die Entfernung zum Motiv, angegeben in Metern. |
| SUBJECT_DISTANCE_RANGE | Dieses Tag gibt die Entfernung zum Motiv an. |
| SUBJECT_LOCATION | Gibt die Position des Hauptmotivs in der Szene an. Der Wert dieses Tags stellt das Pixel im Zentrum des Hauptmotivs relativ zum linken Rand dar, vor der Rotationsverarbeitung gemäß dem Rotation‑Tag. |
| SUBSEC_TIME | Ein Tag, das verwendet wird, um Sekundenbruchteile für das DateTime‑Tag aufzuzeichnen. |
| SUBSEC_TIME_DIGITIZED | Ein Tag, das verwendet wird, um Sekundenbruchteile für das DateTimeDigitized‑Tag aufzuzeichnen. |
| SUBSEC_TIME_ORIGINAL | Ein Tag, der verwendet wird, um Sekundenbruchteile für den DateTimeOriginal-Tag aufzuzeichnen. |
| TRANSFER_FUNCTION | Eine Transferfunktion für das Bild, beschrieben in tabellarischer Form. Normalerweise ist dieses Tag nicht erforderlich, da der Farbraum im Farbrauminformations-Tag ColorSpace angegeben ist. |
| USER_COMMENT | Ein Tag für Exif‑Benutzer, um Schlüsselwörter oder Kommentare zum Bild zu schreiben, zusätzlich zu denen in ImageDescription, und ohne die Zeichenkodierungsbeschränkungen des ImageDescription‑Tags. |
| WHITE_BALANCE | Dieses Tag gibt den beim Aufnehmen des Bildes eingestellten Weißabgleichmodus an. |
| WHITE_POINT | Die Chromatik des Weißpunkts des Bildes. Normalerweise ist dieses Tag nicht erforderlich, da der Farbraum im Farbrauminformations‑Tag ColorSpace angegeben ist. |
| X_RESOLUTION | Die Anzahl der Pixel pro ResolutionUnit in Richtung ImageWidth. Wenn die Bildauflösung unbekannt ist, wird 72 [dpi] angegeben. |
| Y_CB_CR_COEFFICIENTS | Die Matrixkoeffizienten für die Umwandlung von RGB zu YCbCr‑Bilddaten. |
| Y_CB_CR_POSITIONING | Die Position der Chrominanz‑Komponenten in Bezug auf die<br/>                Luminanz‑Komponente. Dieses Feld ist nur für<br/>                JPEG‑komprimierte Daten oder unkomprimierte YCbCr‑Daten vorgesehen. Der TIFF‑Standardwert ist 1 (zentriert); aber wenn Y:Cb:Cr = 4:2:2 ist, wird in diesem Standard empfohlen, 2 (nebeneinander) zu verwenden, um Daten zu speichern, um die Bildqualität bei der Anzeige<br/>                auf TV‑Systemen zu verbessern. Wenn dieses Feld nicht existiert, muss der Leser<br/>                den TIFF‑Standardwert annehmen. Im Fall von Y:Cb:Cr = 4:2:0 wird der<br/>                TIFF‑Standardwert (zentriert) empfohlen. Wenn der Leser<br/>                nicht die Fähigkeit hat, beide Arten von<br/>                YCbCrPositioning zu unterstützen, muss er unabhängig vom Wert in diesem Feld den TIFF‑Standardwert befolgen. Es ist vorzuziehen, dass Leser "<br/>                sowohl zentrierte als auch nebeneinander liegende Positionierung unterstützen können. |
| Y_CB_CR_SUB_SAMPLING | Das Abtastverhältnis der Chrominanz‑Komponenten in Bezug auf die Luminanz‑Komponente. |
| Y_RESOLUTION | Die Anzahl der Pixel pro ResolutionUnit in Richtung ImageLength. Der gleiche Wert wie bei XResolution wird angegeben. |
