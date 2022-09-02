---
title: ExifProperties
second_title: Aspose.Imaging für .NET-API-Referenz
description: Liste der Exif-Tags
type: docs
weight: 1080
url: /de/net/aspose.imaging.exif/exifproperties/
---
## ExifProperties enumeration

Liste der Exif-Tags

```csharp
public enum ExifProperties : ushort
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| ImageWidth | `256` | Die Anzahl der Bilddatenspalten, gleich der Anzahl der Pixel pro Zeile. |
| ImageLength | `257` | Die Anzahl der Bilddatenzeilen. |
| BitsPerSample | `258` | Die Anzahl der Bits pro Bildkomponente. In diesem Standard hat jede Komponente des Bildes 8 Bit, also ist der Wert für dieses Tag 8. |
| Compression | `259` | Das für die Bilddaten verwendete Komprimierungsschema. Wenn ein Primärbild JPEG-komprimiert ist, ist diese Bezeichnung nicht erforderlich und wird weggelassen. |
| PhotometricInterpretation | `262` | Die Pixelzusammensetzung. |
| ImageDescription | `270` | Eine Zeichenfolge, die den Titel des Bildes angibt. Es kann sich um einen Kommentar wie „1988 Firmenpicknick“ oder ähnliches handeln. |
| Make | `271` | Der Hersteller des Kontrollgeräts. Dies ist der Hersteller des DSC, Scanners, Videodigitalisierers oder anderer Geräte, die das Bild erzeugt haben. Wenn das Feld leer gelassen wird, wird es als unbekannt behandelt. |
| Model | `272` | Der Modellname oder die Modellnummer des Geräts. Dies ist der Modellname oder die Nummer des DSC, Scanners, Videodigitalisierers oder anderer Geräte, die das Bild erzeugt haben. Wenn das Feld leer gelassen wird, wird es als unbekannt behandelt. |
| Orientation | `274` | Die Bildausrichtung, betrachtet in Zeilen und Spalten. |
| SamplesPerPixel | `277` | Die Anzahl der Komponenten pro Pixel. Da dieser Standard für RGB- und YCbCr-Bilder gilt, ist der für dieses Tag festgelegte Wert 3. |
| XResolution | `282` | Die Anzahl der Pixel pro Auflösungseinheit in Richtung ImageWidth. Wenn die Bildauflösung unbekannt ist, wird 72 [dpi] angegeben. |
| YResolution | `283` | Die Anzahl der Pixel pro Auflösungseinheit in der Richtung ImageLength. Derselbe Wert wie XResolution wird bezeichnet. |
| PlanarConfiguration | `284` | Gibt an, ob Pixelkomponenten in einem Chunky- oder Planar-Format aufgezeichnet werden. Wenn dieses Feld nicht vorhanden ist, wird der TIFF-Standardwert 1 (chunky) angenommen. |
| ResolutionUnit | `296` | Die Einheit zum Messen von XResolution und YResolution. Dieselbe Einheit wird sowohl für XResolution als auch für YResolution verwendet. Wenn die Bildauflösung unbekannt ist, wird 2 (Zoll) angegeben. |
| TransferFunction | `301` | Eine tabellarisch beschriebene Übertragungsfunktion für das Bild. Normalerweise ist dieses Tag nicht notwendig, da der Farbraum in der Farbrauminformation ColorSpace-Tag angegeben ist. |
| Software | `305` | Dieses Tag zeichnet den Namen und die Version der Software oder Firmware der Kamera oder des Bildeingabegeräts auf, die zum Generieren des Bildes verwendet werden. Das genaue Format ist nicht spezifiziert, aber es wird empfohlen, dem unten gezeigten Beispiel zu folgen. Wenn das Feld leer gelassen wird, wird es als unbekannt behandelt. |
| DateTime | `306` | Das Datum und die Uhrzeit der Image-Erstellung. Im Exif-Standard ist dies das Datum und die Uhrzeit, zu der die Datei geändert wurde. |
| Artist | `315` | Dieses Tag zeichnet den Namen des Kamerabesitzers, Fotografen oder Bildschöpfers auf. Das genaue Format ist nicht spezifiziert, aber es wird empfohlen, die Informationen wie im Beispiel unten zu schreiben, um die Interoperabilität zu erleichtern. Wenn das Feld leer gelassen wird, wird es als unbekannt behandelt. Bsp.) „Kamerabesitzer, John Smith; Fotograf, Michael Brown; Bildschöpfer, Ken James“ |
| WhitePoint | `318` | Die Farbart des Weißpunkts des Bildes. Normalerweise ist dieses Tag nicht erforderlich, da der Farbraum in der Farbrauminformation ColorSpace-Tag angegeben ist. |
| PrimaryChromaticities | `319` | Die Chromatizität der drei Primärfarben des Bildes. Normalerweise ist dieses Tag nicht erforderlich, da der Farbraum in den Farbrauminformationen ColorSpace-Tag angegeben ist. |
| YCbCrCoefficients | `529` | Die Matrixkoeffizienten für die Transformation von RGB- zu YCbCr-Bilddaten. |
| YCbCrSubSampling | `530` | Das Abtastverhältnis von Chrominanzkomponenten in Bezug auf die Luminanzkomponente. |
| YCbCrPositioning | `531` | Die Position der Chrominanzkomponenten in Bezug auf die Luminanzkomponente. Dieses Feld ist nur für JPEG-komprimierte Daten oder unkomprimierte YCbCr-Daten vorgesehen. Der Standardwert für TIFF ist 1 (zentriert); aber wenn Y:Cb:Cr = 4:2:2 ist, wird in diesem Standard empfohlen, dass 2 (co-sited) verwendet werden, um Daten aufzuzeichnen, um die Bildqualität zu verbessern, wenn sie auf Fernsehsystemen angesehen werden. Wenn dieses Feld nicht vorhanden ist, nimmt der Reader sollen die TIFF-Standardeinstellung an. Im Fall von Y:Cb:Cr = 4:2:0 wird die TIFF-Standardeinstellung (zentriert) empfohlen. Wenn der reader nicht in der Lage ist, beide Arten von YCbCrPositioning zu unterstützen, folgt er dem TIFF-Standard, unabhängig vom Wert in diesem Feld. Es ist vorzuziehen, dass Lesegeräte " in der Lage sind, sowohl die zentrierte als auch die ortsgleiche Positionierung zu unterstützen. |
| ReferenceBlackWhite | `532` | Der Schwarzpunkt-Referenzwert und der Weißpunkt-Referenzwert . In TIFF sind keine Standardwerte angegeben, aber die folgenden Werte werden hier als Standardwerte angegeben. Der Farbraum wird in einem Farbraum-Informations-Tag deklariert , wobei default der Wert ist, der die optimalen Bildeigenschaften angibt Interoperabilität diese Bedingungen |
| Copyright | `33432` | Copyright-Informationen. In diesem Standard wird das Tag verwendet, um sowohl die Urheberrechte des Fotografen als auch des Herausgebers anzugeben. Es ist der Urheberrechtsvermerk der Person oder Organisation, die Rechte an dem Bild beansprucht. Die Interoperabilitäts-Copyright -Erklärung einschließlich Datum und Rechte sollte in dieses -Feld geschrieben werden; zB "Copyright, John Smith, 19xx. Alle Rechte vorbehalten.". In diesem Standard erfasst das Feld sowohl die Urheberrechte des Fotografen als auch des Herausgebers, wobei jedes in einem separaten Teil der Erklärung erfasst wird. Wenn es eine klare Unterscheidung zwischen den Urheberrechten des Fotografen und des Herausgebers gibt, müssen diese in der Reihenfolge des Fotografen gefolgt vom Urheberrecht des Herausgebers geschrieben werden, durch NULL getrennt (in diesem Fall, da die Anweisung auch mit einer NULL endet, gibt es zwei NULL-Codes ). Wenn nur das copyright des Fotografen angegeben ist, wird es durch einen NULL-Code beendet. Wenn nur das Herausgeber-Copyright gegeben wird, besteht das Fotografen-Copyright part aus einem Leerzeichen gefolgt von einem abschließenden NULL-Code, dann wird das Herausgeber-Copyright gegeben. Wenn das Feld leer gelassen wird, wird es als unbekannt behandelt. |
| ExposureTime | `33434` | Belichtungszeit, angegeben in Sekunden. |
| FNumber | `33437` | Die F-Nummer. |
| ExposureProgram | `34850` | Die Klasse des Programms, das von der Kamera verwendet wird, um die Belichtung einzustellen, wenn das Bild aufgenommen wird. |
| SpectralSensitivity | `34852` | Gibt die spektrale Empfindlichkeit jedes Kanals der verwendeten Kamera an. |
| PhotographicSensitivity | `34855` | Gibt die ISO-Empfindlichkeit und den ISO-Breitengrad der Kamera oder des Eingabegeräts gemäß ISO 12232 an. |
| OECF | `34856` | Gibt die in ISO 14524 spezifizierte Opto-Electric Conversion Function (OECF) an. |
| ExifVersion | `36864` | Die Exif-Version. |
| DateTimeOriginal | `36867` | Datum und Uhrzeit der Generierung der ursprünglichen Bilddaten. |
| DateTimeDigitized | `36868` | Die Datumszeit digitalisiert. |
| ComponentsConfiguration | `37121` | Die Komponentenkonfiguration. |
| CompressedBitsPerPixel | `37122` | Spezifisch für komprimierte Daten; gibt die komprimierten Bits pro Pixel an. |
| ShutterSpeedValue | `37377` | Der Verschlusszeitwert. |
| ApertureValue | `37378` | Der Blendenwert des Objektivs. |
| BrightnessValue | `37379` | Der Helligkeitswert. |
| ExposureBiasValue | `37380` | Der Belichtungsverzerrungswert. |
| MaxApertureValue | `37381` | Der maximale Blendenwert. |
| SubjectDistance | `37382` | Die Entfernung zum Motiv, angegeben in Metern. |
| MeteringMode | `37383` | Der Messmodus. |
| LightSource | `37384` | Die freundliche Lichtquelle. |
| Flash | `37385` | Zeigt den Status des Blitzes an, als das Bild aufgenommen wurde. |
| FocalLength | `37386` | Die tatsächliche Brennweite des Objektivs in mm. |
| SubjectArea | `37396` | Dieses Tag gibt die Position und den Bereich des Hauptmotivs in der Gesamtszene an. |
| MakerNote | `37500` | Ein Tag für Hersteller von Exif-Brennern, um beliebige Informationen aufzuzeichnen. Der Inhalt ist Sache des Herstellers, aber dieses Tag sollte nicht für einen anderen als den vorgesehenen Zweck verwendet werden. |
| UserComment | `37510` | Ein Tag für Exif-Benutzer, um neben denen in ImageDescription Schlüsselwörter oder Kommentare zum Bild zu schreiben, und ohne die Zeichencodebeschränkungen des ImageDescription-Tags. |
| SubsecTime | `37520` | Ein Tag zum Aufzeichnen von Sekundenbruchteilen für das DateTime-Tag. |
| SubsecTimeOriginal | `37521` | Ein Tag zum Aufzeichnen von Bruchteilen von Sekunden für das DateTimeOriginal-Tag. |
| SubsecTimeDigitized | `37522` | Ein Tag zum Aufzeichnen von Bruchteilen von Sekunden für das DateTimeDigitalized-Tag. |
| FlashpixVersion | `40960` | Die Flashpix-Formatversion, die von einer FPXR-Datei unterstützt wird. |
| ColorSpace | `40961` | Das Farbrauminformations-Tag (ColorSpace) wird immer als Farbraumbezeichner aufgezeichnet. |
| RelatedSoundFile | `40964` | Die zugehörige Sounddatei. |
| FlashEnergy | `41483` | Gibt die Blitzenergie zum Zeitpunkt der Bildaufnahme an, gemessen in Beam Candle Power Seconds (BCPS). |
| SpatialFrequencyResponse | `41484` | Dieses Tag zeichnet die Ortsfrequenztabelle der Kamera oder des Eingabegeräts und SFR-Werte in Richtung der Bildbreite, Bildhöhe und Diagonalrichtung auf, wie in ISO 12233 angegeben. |
| FocalPlaneXResolution | `41486` | Gibt die Anzahl der Pixel in Richtung der Bildbreite (X) pro FocalPlaneResolutionUnit auf der Brennebene der Kamera an. |
| FocalPlaneYResolution | `41487` | Gibt die Anzahl der Pixel in Richtung der Bildhöhe (Y) pro FocalPlaneResolutionUnit auf der Brennebene der Kamera an. |
| FocalPlaneResolutionUnit | `41488` | Gibt die Einheit zum Messen von FocalPlaneXResolution und FocalPlaneYResolution an. Dieser Wert ist derselbe wie die Resolution Unit. |
| SubjectLocation | `41492` | Zeigt die Position des Hauptmotivs in der Szene an. Der Wert dieses Tags stellt das Pixel in der Mitte des Hauptmotivs relativ zum linken Rand dar, vor der Rotationsverarbeitung gemäß dem Rotation-Tag. |
| ExposureIndex | `41493` | Gibt den Belichtungsindex an, der zum Zeitpunkt der Aufnahme des Bildes auf der Kamera oder dem Eingabegerät ausgewählt wurde. |
| SensingMethod | `41495` | Gibt den Bildsensortyp der Kamera oder des Eingabegeräts an. |
| FileSource | `41728` | Die Dateiquelle. |
| SceneType | `41729` | Gibt den Szenentyp an. Wenn ein DSC das Bild aufgenommen hat, muss dieser Tag-Wert immer auf 1 gesetzt werden, was anzeigt, dass das Bild direkt fotografiert wurde. |
| CFAPattern | `41730` | Gibt das geometrische Muster des Farbfilterarrays (CFA) des Bildsensors an, wenn ein Ein-Chip-Farbbereichssensor verwendet wird. Es gilt nicht für alle Erfassungsmethoden. |
| CustomRendered | `41985` | Dieses Tag weist auf die Verwendung einer speziellen Verarbeitung von Bilddaten hin, z. B. auf die Ausgabe ausgerichtetes Rendern. Wenn eine spezielle Verarbeitung durchgeführt wird, wird vom Leser erwartet, dass er jede weitere Verarbeitung deaktiviert oder minimiert. |
| ExposureMode | `41986` | Dieses Tag zeigt den bei der Aufnahme des Bildes eingestellten Belichtungsmodus an. Im automatischen Belichtungsreihenmodus nimmt die Kamera eine Reihe von Einzelbildern derselben Szene mit unterschiedlichen Belichtungseinstellungen auf. |
| WhiteBalance | `41987` | Dieses Tag zeigt den Weißabgleichmodus an, der bei der Aufnahme des Bildes eingestellt war. |
| DigitalZoomRatio | `41988` | Dieses Tag gibt das digitale Zoomverhältnis an, als das Bild aufgenommen wurde. Wenn der Zähler des aufgezeichneten Werts 0 ist, bedeutet dies, dass der Digitalzoom nicht verwendet wurde. |
| FocalLengthIn35MmFilm | `41989` | Dieses Tag gibt die äquivalente Brennweite in mm an, wenn man von einer 35-mm-Filmkamera ausgeht. Ein Wert von 0 bedeutet, dass die Brennweite unbekannt ist. Beachten Sie, dass sich dieses Tag vom FocalLength-Tag unterscheidet. |
| SceneCaptureType | `41990` | Dieses Tag zeigt die Art der aufgenommenen Szene an. Es kann auch verwendet werden, um den Modus aufzuzeichnen, in dem das Bild aufgenommen wurde. |
| GainControl | `41991` | Dieses Tag gibt den Grad der Gesamtanpassung der Bildverstärkung an. |
| Contrast | `41992` | Dieses Tag gibt die Richtung der Kontrastverarbeitung an, die von der Kamera angewendet wurde, als das Bild aufgenommen wurde. |
| Saturation | `41993` | Dieses Tag gibt die Richtung der Sättigungsverarbeitung an, die von der Kamera angewendet wurde, als das Bild aufgenommen wurde. |
| Sharpness | `41994` | Dieses Tag gibt die Richtung der Schärfeverarbeitung an, die von der Kamera angewendet wurde, als das Bild aufgenommen wurde |
| DeviceSettingDescription | `41995` | Dieses Tag zeigt Informationen zu den Aufnahmebedingungen eines bestimmten Kameramodells an. Das Tag wird nur verwendet, um die Aufnahmebedingungen im Lesegerät anzuzeigen. |
| SubjectDistanceRange | `41996` | Dieses Tag zeigt die Entfernung zum Motiv an. |
| ImageUniqueID | `42016` | Die eindeutige Bild-ID. |
| GPSVersionID | `0` | Zeigt die Version von GPSInfoIFD an. |
| GPSLatitudeRef | `1` | Gibt an, ob der Breitengrad der nördliche oder der südliche Breitengrad ist. |
| GPSLatitude | `2` | Gibt den Breitengrad an. Der Breitengrad wird als drei RATIONAL-Werte ausgedrückt, die Grad, Minuten bzw. Sekunden angeben. Wenn der Breitengrad in Grad, Minuten und Sekunden ausgedrückt wird, wäre ein typisches Format dd/1,mm/1,ss/1. Wenn Grad und Minuten verwendet werden und beispielsweise Bruchteile von Minuten mit bis zu zwei Dezimalstellen angegeben werden, wäre das Format dd/1,mmmm/100,0/1. |
| GPSLongitudeRef | `3` | Gibt an, ob der Längengrad östlicher oder westlicher Längengrad ist. |
| GPSLongitude | `4` | Gibt den Längengrad an. Der Längengrad wird als drei RATIONAL-Werte ausgedrückt, die Grad, Minuten bzw. Sekunden angeben. Wenn Längengrade in Grad, Minuten und Sekunden ausgedrückt werden, wäre ein typisches Format ddd/1,mm/1,ss/1. Wenn Grad und Minuten verwendet werden und beispielsweise Bruchteile von Minuten mit bis zu zwei Dezimalstellen angegeben werden, wäre das Format ddd/1,mmmm/100,0/1. |
| GPSAltitudeRef | `5` | Zeigt die als Referenzhöhe verwendete Höhe an. Wenn die Referenz der Meeresspiegel ist und die Höhe über dem Meeresspiegel liegt, wird 0 angegeben. Wenn die Höhe unter dem Meeresspiegel liegt, wird ein Wert von 1 angegeben und die Höhe wird als absoluter Wert im GPSAltitude-Tag angegeben. |
| GPSAltitude | `6` | Zeigt die Höhe basierend auf der Referenz in GPSAltitudeRef an. Die Höhe wird als ein RATIONAL-Wert ausgedrückt. Die Referenzeinheit ist Meter. |
| GPSTimestamp | `7` | Zeigt die Zeit als UTC (Koordinierte Weltzeit) an. TimeStamp wird als drei RATIONAL-Werte ausgedrückt, die Stunde, Minute und Sekunde angeben. |
| GPSSatellites | `8` | Zeigt die für Messungen verwendeten GPS-Satelliten an. Dieses Tag kann verwendet werden, um die Anzahl der Satelliten, ihre ID-Nummer, Elevationswinkel, Azimut, SNR und andere Informationen in ASCII-Notation zu beschreiben. Das Format ist not angegeben. Wenn der GPS-Empfänger keine Messungen vornehmen kann, muss der Wert des Tags auf NULL gesetzt werden. |
| GPSStatus | `9` | Zeigt den Status des GPS-Empfängers an, wenn das Bild aufgezeichnet wird. |
| GPSMeasureMode | `10` | Zeigt den GPS-Messmodus an. - 2- oder 3-dimensional. |
| GPSDOP | `11` | Zeigt den GPS DOP (Datengenauigkeitsgrad) an. Bei einer zweidimensionalen Messung wird ein HDOP-Wert geschrieben, und bei einer dreidimensionalen Messung ein PDOP-Wert. |
| GPSSpeedRef | `12` | Gibt die Einheit an, die verwendet wird, um die Bewegungsgeschwindigkeit des GPS-Empfängers auszudrücken. „K“, „M“ und „N“ stehen für Kilometer pro Stunde, Meilen pro Stunde und Knoten. |
| GPSSpeed | `13` | Zeigt die Bewegungsgeschwindigkeit des GPS-Empfängers an. |
| GPSTrackRef | `14` | Gibt die Referenz an, um die Bewegungsrichtung des GPS-Empfängers anzugeben. „T“ bezeichnet die wahre Richtung und „M“ ist magnetische Richtung. |
| GPSTrack | `15` | Zeigt die Bewegungsrichtung des GPS-Empfängers an. Der Wertebereich reicht von 0,00 bis 359,99. |
| GPSImgDirectionRef | `16` | Gibt die Referenz an, um die Richtung des Bildes anzugeben, wenn es aufgenommen wird. „T“ bezeichnet die wahre Richtung und „M“ ist magnetische Richtung. |
| GPSImgDirection | `17` | Zeigt die Richtung des Bildes an, als es aufgenommen wurde. Der Wertebereich reicht von 0,00 bis 359,99. |
| GPSMapDatum | `18` | Gibt die vom GPS-Empfänger verwendeten geodätischen Vermessungsdaten an. |
| GPSDestLatitudeRef | `19` | Gibt an, ob der Breitengrad des Zielpunkts der nördliche oder der südliche Breitengrad ist. Der ASCII-Wert „N“ gibt den nördlichen Breitengrad an und „S“ den südlichen Breitengrad. |
| GPSDestLatitude | `20` | Zeigt den Breitengrad des Zielpunkts an. Der Breitengrad wird als drei RATIONAL-Werte ausgedrückt, die die Grad, Minuten bzw. Sekunden angeben. Wenn der Breitengrad in Grad, Minuten und Sekunden ausgedrückt wird, wäre ein typisches -Format dd/1,mm/1,ss/1. Wenn Grad und Minuten verwendet werden und beispielsweise Bruchteile von Minuten mit bis zu zwei Dezimalstellen angegeben werden, wäre das Format dd/1,mmmm/100,0/1. |
| GPSDestLongitudeRef | `21` | Gibt an, ob der Längengrad des Zielpunkts östlicher oder westlicher Längengrad ist. ASCII 'E' gibt den östlichen Längengrad an, und 'W' ist der westliche Längengrad. |
| GPSDestLongitude | `22` | Gibt den Längengrad des Zielpunkts an. Der Längengrad wird als drei RATIONAL-Werte ausgedrückt, die die Grad, Minuten bzw. Sekunden angeben. Wenn Längengrade in Grad, Minuten und Sekunden ausgedrückt werden, wäre ein typisches -Format ttd/1, mm/1, ss/1. Wenn Grad und Minuten verwendet werden und beispielsweise Bruchteile von Minuten mit bis zu zwei Dezimalstellen angegeben werden, wäre das Format ddd/1,mmmm/100,0/1. |
| GPSDestBearingRef | `23` | Gibt die Referenz an, die für die Peilung zum Zielpunkt verwendet wird. „T“ bezeichnet die wahre Richtung und „M“ ist magnetische Richtung. |
| GPSDestBearing | `24` | Zeigt die Peilung zum Zielpunkt an. Der Wertebereich reicht von 0,00 bis 359,99. |
| GPSDestDistanceRef | `25` | Gibt die Einheit an, die verwendet wird, um die Entfernung zum Zielpunkt auszudrücken. „K“, „M“ und „N“ stehen für Kilometer, Meilen und Knoten. |
| GPSDestDistance | `26` | Gibt die Entfernung zum Zielpunkt an. |
| GPSProcessingMethod | `27` | Eine Zeichenkette, die den Namen der für die Standortbestimmung verwendeten Methode aufzeichnet. Das erste Byte gibt den verwendeten Zeichencode an, gefolgt von dem Namen der Methode. |
| GPSAreaInformation | `28` | Eine Zeichenfolge, die den Namen des GPS-Bereichs aufzeichnet. Das erste Byte gibt den verwendeten Zeichencode an, gefolgt vom Namen des GPS-Bereichs. |
| GPSDateStamp | `29` | Eine Zeichenkette, die Datums- und Zeitinformationen relativ zu UTC (Koordinierte Weltzeit) aufzeichnet. Das Format ist JJJJ:MM:TT. |
| GPSDifferential | `30` | Gibt an, ob eine differentielle Korrektur auf den GPS-Empfänger angewendet wird. |
| StripOffsets | `273` | Für jeden Streifen der Byte-Offset dieses Streifens. Es wird empfohlen, dies so auszuwählen, dass die Anzahl der Strip-Bytes 64 KByte nicht überschreitet. Aux-Tag. |
| JPEGInterchangeFormat | `513` | Der Offset zum Startbyte (SOI) von JPEG-komprimierten Thumbnail-Daten. Dies wird nicht für Primärbild-JPEG-Daten verwendet. |
| JPEGInterchangeFormatLength | `514` | Die Anzahl der Bytes von JPEG-komprimierten Miniaturbilddaten. Dies wird nicht für Primärbild-JPEG-Daten verwendet. JPEG-Thumbnails werden nicht geteilt, sondern als kontinuierlicher JPEG-Bitstream von SOI zu EOI aufgezeichnet. Appn- und COM-Marker sollten nicht aufgezeichnet werden. Komprimierte Miniaturansichten dürfen nicht größer als 64 KB sein, einschließlich aller anderen Daten, die in APP1. aufgezeichnet werden sollen. |
| ExifIfdPointer | `34665` | Ein Zeiger auf das Exif IFD. Interoperabilität, Exif IFD hat die gleiche Struktur wie die in TIFF spezifizierte IFD. normalerweise enthält es jedoch keine Bilddaten wie im Fall von TIFF. |
| GPSIfdPointer | `34853` | Der GPS-IFD-Zeiger. |
| RowsPerStrip | `278` | Die Anzahl der Reihen pro Streifen. Dies ist die Anzahl der Zeilen im Bild eines Streifens, wenn ein Bild in Streifen unterteilt wird. |
| StripByteCounts | `279` | Die Gesamtzahl der Bytes in jedem Streifen. |
| PixelXDimension | `40962` | Spezifische Informationen zu komprimierten Daten. Wenn eine komprimierte Datei aufgezeichnet wird, muss die gültige Breite des aussagekräftigen Bildes in diesem Tag aufgezeichnet werden, unabhängig davon, ob Fülldaten oder eine Neustartmarkierung vorhanden sind. |
| PixelYDimension | `40963` | Spezifische Informationen zu komprimierten Daten. Wenn eine komprimierte Datei aufgezeichnet wird, muss die gültige Höhe des aussagekräftigen Bildes in diesem Tag aufgezeichnet werden |
| Gamma | `42240` | Gammawert |
| SensitivityType | `34864` | Art der fotografischen Empfindlichkeit |
| StandardOutputSensitivity | `34865` | Zeigt die Standardausgabeempfindlichkeit von camera an |
| RecommendedExposureIndex | `34866` | Zeigt den empfohlenen Belichtungsindex an |
| ISOSpeed | `34867` | Information über Isogeschwindigkeitswert wie in ISO 12232 definiert |
| ISOSpeedLatitudeYYY | `34868` | Dieses Tag zeigt den Wert für den Breitengrad der ISO-Geschwindigkeit yyy an, wie in ISO 12232 definiert. |
| ISOSpeedLatitudeZZZ | `34869` | Dieses Tag zeigt den zzz-Wert der ISO-Geschwindigkeitsbreite an, wie in ISO 12232 definiert. |
| CameraOwnerName | `42032` | Enthält den Namen des Kamerabesitzers |
| BodySerialNumber | `42033` | Enthält die Seriennummer des Kameragehäuses |
| LensMake | `42035` | Dieses Tag erfasst den Linsenhersteller |
| LensModel | `42036` | Dieses Tag zeichnet den Modellnamen und die Modellnummer des Objektivs auf |
| LensSerialNumber | `42037` | Dieses Tag speichert die Seriennummer des Wechselobjektivs |
| LensSpecification | `42034` | Dieses Tag notiert minimale Brennweite, maximale Brennweite, minimale F-Zahl in der minimalen Brennweite und minimale F-Zahl in maximaler Brennweite |

### Siehe auch

* namensraum [Aspose.Imaging.Exif](../../aspose.imaging.exif)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
