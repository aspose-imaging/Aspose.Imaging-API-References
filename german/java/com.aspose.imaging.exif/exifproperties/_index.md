---
title: "ExifProperties"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Exif-Tag-Liste"
type: docs
weight: 11
url: /de/java/com.aspose.imaging.exif/exifproperties/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ExifProperties extends System.Enum
```

Exif-Tag-Liste
## Felder

| Feld | Beschreibung |
| --- | --- |
| [ImageWidth](#ImageWidth) | Die Anzahl der Spalten der Bilddaten, gleich der Anzahl der Pixel pro Zeile. |
| [ImageLength](#ImageLength) | Die Anzahl der Zeilen der Bilddaten. |
| [BitsPerSample](#BitsPerSample) | Die Anzahl der Bits pro Bildkomponente. |
| [Compression](#Compression) | Das Komprimierungsschema, das für die Bilddaten verwendet wird. |
| [PhotometricInterpretation](#PhotometricInterpretation) | Die Pixelzusammensetzung. |
| [ImageDescription](#ImageDescription) | Eine Zeichenkette, die den Titel des Bildes angibt. |
| [Make](#Make) | Der Hersteller der Aufzeichnungsgeräte. |
| [Model](#Model) | Der Modellname oder die Modellnummer der Ausrüstung. |
| [Orientation](#Orientation) | Die Bildorientierung, betrachtet in Zeilen und Spalten. |
| [SamplesPerPixel](#SamplesPerPixel) | Die Anzahl der Komponenten pro Pixel. |
| [XResolution](#XResolution) | Die Anzahl der Pixel pro ResolutionUnit in Richtung ImageWidth. |
| [YResolution](#YResolution) | Die Anzahl der Pixel pro ResolutionUnit in Richtung ImageLength. |
| [PlanarConfiguration](#PlanarConfiguration) | Gibt an, ob Pixelkomponenten im Chunky- oder Planarformat aufgezeichnet werden. |
| [ResolutionUnit](#ResolutionUnit) | Die Einheit zur Messung von XResolution und YResolution. |
| [TransferFunction](#TransferFunction) | Eine Transferfunktion für das Bild, beschrieben in tabellarischer Form. |
| [Software](#Software) | Dieses Tag zeichnet den Namen und die Version der Software oder Firmware der Kamera oder des Bildaufnahmegeräts auf, das zur Erstellung des Bildes verwendet wurde. |
| [DateTime](#DateTime) | Datum und Uhrzeit der Bild-Erstellung. |
| [Artist](#Artist) | Dieses Tag zeichnet den Namen des Kamerabesitzers, Fotografen oder Bildschöpfers auf. |
| [WhitePoint](#WhitePoint) | Die Chromatik des Weißpunkts des Bildes. |
| [PrimaryChromaticities](#PrimaryChromaticities) | Die Chromatik der drei Primärfarben des Bildes. |
| [YCbCrCoefficients](#YCbCrCoefficients) | Die Matrixkoeffizienten für die Transformation von RGB zu YCbCr Bilddaten. |
| [YCbCrSubSampling](#YCbCrSubSampling) | Das Abtastverhältnis der Chrominanzkomponenten im Verhältnis zur Luminanzkomponente. |
| [YCbCrPositioning](#YCbCrPositioning) | Die Position der Chrominanzkomponenten im Verhältnis zur Luminanzkomponente. |
| [ReferenceBlackWhite](#ReferenceBlackWhite) | Der Referenzschwarzpunktwert und der Referenzweißpunktwert. |
| [Copyright](#Copyright) | Copyright-Informationen. |
| [ExposureTime](#ExposureTime) | Belichtungszeit, angegeben in Sekunden. |
| [FNumber](#FNumber) | Die Blendenzahl. |
| [ExposureProgram](#ExposureProgram) | Die Klasse des Programms, das von der Kamera verwendet wird, um die Belichtung beim Aufnehmen des Bildes einzustellen. |
| [SpectralSensitivity](#SpectralSensitivity) | Gibt die spektrale Empfindlichkeit jedes Kanals der verwendeten Kamera an. |
| [PhotographicSensitivity](#PhotographicSensitivity) | Gibt die ISO-Geschwindigkeit und ISO-Latitude der Kamera oder des Eingabegeräts gemäß ISO 12232 an. |
| [OECF](#OECF) | Gibt die in ISO 14524 angegebene Opto‑Elektrische Umwandlungsfunktion (OECF) an. |
| [ExifVersion](#ExifVersion) | Die Exif-Version. |
| [DateTimeOriginal](#DateTimeOriginal) | Datum und Uhrzeit, wann die Originalbilddaten erzeugt wurden. |
| [DateTimeDigitized](#DateTimeDigitized) | Das Digitalisierungsdatum und die -uhrzeit. |
| [ComponentsConfiguration](#ComponentsConfiguration) | Die Konfiguration der Komponenten. |
| [CompressedBitsPerPixel](#CompressedBitsPerPixel) | Spezifisch für komprimierte Daten; gibt die komprimierten Bits pro Pixel an. |
| [ShutterSpeedValue](#ShutterSpeedValue) | Der Wert der Verschlusszeit. |
| [ApertureValue](#ApertureValue) | Der Wert der Objektivblende. |
| [BrightnessValue](#BrightnessValue) | Der Helligkeitswert. |
| [ExposureBiasValue](#ExposureBiasValue) | Der Belichtungskorrekturwert. |
| [MaxApertureValue](#MaxApertureValue) | Der maximale Blendenwert. |
| [SubjectDistance](#SubjectDistance) | Die Entfernung zum Motiv, angegeben in Metern. |
| [MeteringMode](#MeteringMode) | Der Messmodus. |
| [LightSource](#LightSource) | Die Art der Lichtquelle. |
| [Flash](#Flash) | Gibt den Blitzstatus an, als das Bild aufgenommen wurde. |
| [FocalLength](#FocalLength) | Die tatsächliche Brennweite des Objektivs in mm. |
| [SubjectArea](#SubjectArea) | Dieses Tag gibt die Position und den Bereich des Hauptmotivs in der gesamten Szene an. |
| [MakerNote](#MakerNote) | Ein Tag für Hersteller von Exif-Schreibern, um beliebige gewünschte Informationen zu speichern. |
| [UserComment](#UserComment) | Ein Tag für Exif-Anwender, um Schlüsselwörter oder Kommentare zum Bild zu schreiben, zusätzlich zu denen im ImageDescription-Tag und ohne die Zeichenkodierungsbeschränkungen des ImageDescription-Tags. |
| [SubsecTime](#SubsecTime) | Ein Tag, das Bruchteile von Sekunden für das DateTime-Tag speichert. |
| [SubsecTimeOriginal](#SubsecTimeOriginal) | Ein Tag, das Bruchteile von Sekunden für das DateTimeOriginal-Tag speichert. |
| [SubsecTimeDigitized](#SubsecTimeDigitized) | Ein Tag, das Bruchteile von Sekunden für das DateTimeDigitized-Tag speichert. |
| [FlashpixVersion](#FlashpixVersion) | Die von einer FPXR-Datei unterstützte Flashpix-Formatversion. |
| [ColorSpace](#ColorSpace) | Das Farbraum-Informationstag (ColorSpace) wird immer als Farbraumspezifizierer aufgezeichnet. |
| [RelatedSoundFile](#RelatedSoundFile) | Die zugehörige Audiodatei. |
| [FlashEnergy](#FlashEnergy) | Gibt die Blitzenergie zum Zeitpunkt der Aufnahme des Bildes an, gemessen in Beam Candle Power Seconds (BCPS). |
| [SpatialFrequencyResponse](#SpatialFrequencyResponse) | Dieses Tag zeichnet die räumliche Frequenztafel und SFR-Werte der Kamera oder des Eingabegeräts in Richtung Bildbreite, Bildhöhe und Diagonalrichtung auf, wie in ISO 12233 angegeben. |
| [FocalPlaneXResolution](#FocalPlaneXResolution) | Gibt die Anzahl der Pixel in Bildbreite (X)-Richtung pro FocalPlaneResolutionUnit auf der Kamera-Brennweitebene an. |
| [FocalPlaneYResolution](#FocalPlaneYResolution) | Gibt die Anzahl der Pixel in Bildhöhe (Y)-Richtung pro FocalPlaneResolutionUnit auf der Kamera-Brennweitebene an. |
| [FocalPlaneResolutionUnit](#FocalPlaneResolutionUnit) | Gibt die Einheit zur Messung von FocalPlaneXResolution und FocalPlaneYResolution an. |
| [SubjectLocation](#SubjectLocation) | Gibt die Position des Hauptmotivs in der Szene an. |
| [ExposureIndex](#ExposureIndex) | Gibt den beim Aufnehmen des Bildes ausgewählten Belichtungsindex der Kamera oder des Eingabegeräts an. |
| [SensingMethod](#SensingMethod) | Gibt den Bildsensortyp der Kamera oder des Eingabegeräts an. |
| [FileSource](#FileSource) | Die Dateiquelle. |
| [SceneType](#SceneType) | Gibt den Szenentyp an. |
| [CFAPattern](#CFAPattern) | Gibt das geometrische Muster des Farbfilter-Arrays (CFA) des Bildsensors an, wenn ein Ein-Chip-Farbflächen-Sensor verwendet wird. |
| [CustomRendered](#CustomRendered) | Dieses Tag gibt die Verwendung spezieller Verarbeitung von Bilddaten an, z. B. Rendering für die Ausgabe. |
| [ExposureMode](#ExposureMode) | Dieses Tag gibt den eingestellten Belichtungsmodus bei der Aufnahme des Bildes an. |
| [WhiteBalance](#WhiteBalance) | Dieses Tag gibt den eingestellten Weißabgleichmodus bei der Aufnahme des Bildes an. |
| [DigitalZoomRatio](#DigitalZoomRatio) | Dieses Tag gibt das digitale Zoomverhältnis an, wenn das Bild aufgenommen wurde. |
| [FocalLengthIn35MmFilm](#FocalLengthIn35MmFilm) | Dieses Tag gibt die äquivalente Brennweite an, angenommen eine 35‑mm-Filmkamera, in mm. |
| [SceneCaptureType](#SceneCaptureType) | Dieses Tag gibt den Typ der aufgenommenen Szene an. |
| [GainControl](#GainControl) | Dieses Tag gibt den Grad der allgemeinen Bildverstärkungsanpassung an. |
| [Contrast](#Contrast) | Dieses Tag gibt die Richtung der vom Kamerasystem angewendeten Kontrastverarbeitung an, wenn das Bild aufgenommen wurde. |
| [Saturation](#Saturation) | Dieses Tag gibt die Richtung der vom Kamerasystem angewendeten Sättigungsverarbeitung an, wenn das Bild aufgenommen wurde. |
| [Sharpness](#Sharpness) | Dieses Tag gibt die Richtung der vom Kamerasystem angewendeten Schärfeverarbeitung an, wenn das Bild aufgenommen wurde |
| [DeviceSettingDescription](#DeviceSettingDescription) | Dieses Tag gibt Informationen zu den Aufnahmebedingungen eines bestimmten Kameramodells an. |
| [SubjectDistanceRange](#SubjectDistanceRange) | Dieses Tag gibt die Entfernung zum Motiv an. |
| [ImageUniqueID](#ImageUniqueID) | Die eindeutige Bild-ID. |
| [GPSVersionID](#GPSVersionID) | Gibt die Version von GPSInfoIFD an. |
| [GPSLatitudeRef](#GPSLatitudeRef) | Gibt an, ob die Breite nördlich oder südlich ist. |
| [GPSLatitude](#GPSLatitude) | Gibt die Breite an. |
| [GPSLongitudeRef](#GPSLongitudeRef) | Gibt an, ob die Länge östlich oder westlich ist. |
| [GPSLongitude](#GPSLongitude) | Gibt die Länge an. |
| [GPSAltitudeRef](#GPSAltitudeRef) | Gibt die als Referenz verwendete Höhe an. |
| [GPSAltitude](#GPSAltitude) | Gibt die Höhe basierend auf dem Referenzwert in GPSAltitudeRef an. |
| [GPSTimestamp](#GPSTimestamp) | Gibt die Zeit als UTC (Koordinierte Weltzeit) an. |
| [GPSSatellites](#GPSSatellites) | Gibt die für Messungen verwendeten GPS‑Satelliten an. |
| [GPSStatus](#GPSStatus) | Gibt den Status des GPS‑Empfängers an, wenn das Bild aufgenommen wird. |
| [GPSMeasureMode](#GPSMeasureMode) | Gibt den GPS‑Messmodus an. |
| [GPSDOP](#GPSDOP) | Gibt den GPS‑DOP (Grad der Datenpräzision) an. |
| [GPSSpeedRef](#GPSSpeedRef) | Gibt die Einheit an, die zur Angabe der Geschwindigkeit des GPS‑Empfängers verwendet wird. |
| [GPSSpeed](#GPSSpeed) | Gibt die Geschwindigkeit der GPS‑Empfängerbewegung an. |
| [GPSTrackRef](#GPSTrackRef) | Gibt die Referenz zur Angabe der Bewegungsrichtung des GPS‑Empfängers an. |
| [GPSTrack](#GPSTrack) | Gibt die Richtung der GPS-Empfängerbewegung an. |
| [GPSImgDirectionRef](#GPSImgDirectionRef) | Gibt die Referenz für die Angabe der Bildrichtung bei der Aufnahme an. |
| [GPSImgDirection](#GPSImgDirection) | Gibt die Richtung des Bildes bei der Aufnahme an. |
| [GPSMapDatum](#GPSMapDatum) | Gibt die vom GPS-Empfänger verwendeten geodätischen Vermessungsdaten an. |
| [GPSDestLatitudeRef](#GPSDestLatitudeRef) | Gibt an, ob die Breite des Zielpunkts nördliche oder südliche Breite ist. |
| [GPSDestLatitude](#GPSDestLatitude) | Gibt die Breite des Zielpunkts an. |
| [GPSDestLongitudeRef](#GPSDestLongitudeRef) | Gibt an, ob die Länge des Zielpunkts östliche oder westliche Länge ist. |
| [GPSDestLongitude](#GPSDestLongitude) | Gibt die Länge des Zielpunkts an. |
| [GPSDestBearingRef](#GPSDestBearingRef) | Gibt die für die Angabe des Kurses zum Zielpunkt verwendete Referenz an. |
| [GPSDestBearing](#GPSDestBearing) | Gibt den Kurs zum Zielpunkt an. |
| [GPSDestDistanceRef](#GPSDestDistanceRef) | Gibt die zur Angabe der Entfernung zum Zielpunkt verwendete Einheit an. |
| [GPSDestDistance](#GPSDestDistance) | Gibt die Entfernung zum Zielpunkt an. |
| [GPSProcessingMethod](#GPSProcessingMethod) | Eine Zeichenkette, die den Namen der zur Positionsbestimmung verwendeten Methode aufzeichnet. |
| [GPSAreaInformation](#GPSAreaInformation) | Eine Zeichenkette, die den Namen des GPS‑Gebiets aufzeichnet. |
| [GPSDateStamp](#GPSDateStamp) | Eine Zeichenkette, die Datums‑ und Zeitinformationen relativ zu UTC (Coordinated Universal Time) aufzeichnet. |
| [GPSDifferential](#GPSDifferential) | Gibt an, ob eine Differenzkorrektur auf den GPS‑Empfänger angewendet wird. |
| [StripOffsets](#StripOffsets) | Für jeden Streifen der Byte‑Versatz dieses Streifens. |
| [JPEGInterchangeFormat](#JPEGInterchangeFormat) | Der Versatz zum Startbyte (SOI) der JPEG‑komprimierten Vorschaudaten. |
| [JPEGInterchangeFormatLength](#JPEGInterchangeFormatLength) | Die Anzahl der Bytes der JPEG‑komprimierten Vorschaudaten. |
| [ExifIfdPointer](#ExifIfdPointer) | Ein Zeiger auf das Exif IFD. |
| [GPSIfdPointer](#GPSIfdPointer) | Der gps ifd pointer. |
| [RowsPerStrip](#RowsPerStrip) | Die Anzahl der Zeilen pro Streifen. |
| [StripByteCounts](#StripByteCounts) | Die Gesamtzahl der Bytes in jedem Streifen. |
| [PixelXDimension](#PixelXDimension) | Informationen, die sich speziell auf komprimierte Daten beziehen. |
| [PixelYDimension](#PixelYDimension) | Informationen, die sich speziell auf komprimierte Daten beziehen. |
| [Gamma](#Gamma) | Gamma-Wert |
| [SensitivityType](#SensitivityType) | Typ der fotografischen Empfindlichkeit |
| [StandardOutputSensitivity](#StandardOutputSensitivity) | Gibt die Standard-Ausgabesensitivität der Kamera an |
| [RecommendedExposureIndex](#RecommendedExposureIndex) | Gibt den empfohlenen Belichtungsindex an |
| [ISOSpeed](#ISOSpeed) | Informationen zum ISO-Geschwindigkeitswert gemäß ISO 12232 |
| [ISOSpeedLatitudeYYY](#ISOSpeedLatitudeYYY) | Dieses Tag gibt den ISO-Geschwindigkeitslatitudenwert yyy gemäß ISO 12232 an |
| [ISOSpeedLatitudeZZZ](#ISOSpeedLatitudeZZZ) | Dieses Tag gibt den ISO-Geschwindigkeitslatitudenwert zzz gemäß ISO 12232 an |
| [CameraOwnerName](#CameraOwnerName) | Enthält den Namen des Kamerabesitzers |
| [BodySerialNumber](#BodySerialNumber) | Enthält die Seriennummer des Kameragehäuses |
| [LensMake](#LensMake) | Dieses Tag zeichnet den Hersteller des Objektivs auf |
| [LensModel](#LensModel) | Dieses Tag zeichnet den Modellnamen und die Modellnummer des Objektivs\`s auf |
| [LensSerialNumber](#LensSerialNumber) | Dieses Tag zeichnet die Seriennummer des austauschbaren Objektivs auf |
| [LensSpecification](#LensSpecification) | Dieses Tag vermerkt die minimale Brennweite, maximale Brennweite, die minimale Blendenzahl bei der minimalen Brennweite und die minimale Blendenzahl bei der maximalen Brennweite |
### ImageWidth {#ImageWidth}
```
public static final int ImageWidth
```


Die Anzahl der Spalten der Bilddaten, gleich der Anzahl der Pixel pro Zeile.

### ImageLength {#ImageLength}
```
public static final int ImageLength
```


Die Anzahl der Zeilen der Bilddaten.

### BitsPerSample {#BitsPerSample}
```
public static final int BitsPerSample
```


Die Anzahl der Bits pro Bildkomponente. In diesem Standard hat jede Bildkomponente 8 Bits, daher ist der Wert für dieses Tag 8.

### Compression {#Compression}
```
public static final int Compression
```


Das Komprimierungsschema, das für die Bilddaten verwendet wird. Wenn ein Hauptbild JPEG-komprimiert ist, ist diese Bezeichnung nicht erforderlich und wird weggelassen.

### PhotometricInterpretation {#PhotometricInterpretation}
```
public static final int PhotometricInterpretation
```


Die Pixelzusammensetzung.

### ImageDescription {#ImageDescription}
```
public static final int ImageDescription
```


Eine Zeichenkette, die den Titel des Bildes angibt. Sie kann ein Kommentar wie "1988 Firmenpicknick" oder Ähnliches sein.

### Make {#Make}
```
public static final int Make
```


Der Hersteller der Aufzeichnungsgeräte. Dies ist der Hersteller des DSC, Scanners, Video-Digitalisierers oder anderer Geräte, die das Bild erzeugt haben. Wenn das Feld leer bleibt, wird es als unbekannt behandelt.

### Model {#Model}
```
public static final int Model
```


Der Modellname oder die Modellnummer des Geräts. Dies ist der Modellname oder die Modellnummer des DSC, Scanners, Video-Digitalisierers oder anderer Geräte, die das Bild erzeugt haben. Wenn das Feld leer bleibt, wird es als unbekannt behandelt.

### Orientation {#Orientation}
```
public static final int Orientation
```


Die Bildorientierung, betrachtet in Zeilen und Spalten.

### SamplesPerPixel {#SamplesPerPixel}
```
public static final int SamplesPerPixel
```


Die Anzahl der Komponenten pro Pixel. Da dieser Standard für RGB- und YCbCr-Bilder gilt, ist der für dieses Tag festgelegte Wert 3.

### XResolution {#XResolution}
```
public static final int XResolution
```


Die Anzahl der Pixel pro Auflösungseinheit in Richtung Bildbreite. Wenn die Bildauflösung unbekannt ist, wird 72 [dpi] angegeben.

### YResolution {#YResolution}
```
public static final int YResolution
```


Die Anzahl der Pixel pro Auflösungseinheit in Richtung Bildlänge. Der gleiche Wert wie bei XResolution wird angegeben.

### PlanarConfiguration {#PlanarConfiguration}
```
public static final int PlanarConfiguration
```


Gibt an, ob Pixelkomponenten im Chunky- oder Planarformat aufgezeichnet werden. Wenn dieses Feld nicht existiert, wird der TIFF-Standardwert 1 (Chunky) angenommen.

### ResolutionUnit {#ResolutionUnit}
```
public static final int ResolutionUnit
```


Die Einheit zur Messung von XResolution und YResolution. Für beide wird dieselbe Einheit verwendet. Wenn die Bildauflösung unbekannt ist, wird 2 (Zoll) angegeben.

### TransferFunction {#TransferFunction}
```
public static final int TransferFunction
```


Eine Transferfunktion für das Bild, beschrieben in tabellarischer Form. Normalerweise ist dieses Tag nicht erforderlich, da der Farbraum im ColorSpace-Tag angegeben wird.

### Software {#Software}
```
public static final int Software
```


Dieses Tag zeichnet den Namen und die Version der Software oder Firmware der Kamera oder des Bildaufnahmegeräts auf, das das Bild erzeugt hat. Das genaue Format ist nicht festgelegt, es wird jedoch empfohlen, dem unten gezeigten Beispiel zu folgen. Wenn das Feld leer bleibt, wird es als unbekannt behandelt.

### DateTime {#DateTime}
```
public static final int DateTime
```


Datum und Uhrzeit der Bilderstellung. Im Exif-Standard ist dies das Datum und die Uhrzeit, zu der die Datei geändert wurde.

### Artist {#Artist}
```
public static final int Artist
```


Dieses Tag zeichnet den Namen des Kamerabesitzers, Fotografen oder Bildschöpfers auf. Das genaue Format ist nicht festgelegt, es wird jedoch empfohlen, die Informationen wie im unten stehenden Beispiel für bessere Interoperabilität zu schreiben. Wenn das Feld leer bleibt, wird es als unbekannt behandelt. (Bsp. "Kamerabesitzer, John Smith; Fotograf, Michael Brown; Bildschöpfer, Ken James")

### WhitePoint {#WhitePoint}
```
public static final int WhitePoint
```


Die Chromatizität des Weißpunkts des Bildes. Normalerweise ist dieses Tag nicht erforderlich, da der Farbraum in den Farbrauminformationen des ColorSpace-Tags angegeben ist.

### PrimaryChromaticities {#PrimaryChromaticities}
```
public static final int PrimaryChromaticities
```


Die Chromatizität der drei Primärfarben des Bildes. Normalerweise ist dieses Tag nicht erforderlich, da der Farbraum in den Farbrauminformationen des ColorSpace-Tags angegeben ist.

### YCbCrCoefficients {#YCbCrCoefficients}
```
public static final int YCbCrCoefficients
```


Die Matrixkoeffizienten für die Transformation von RGB zu YCbCr Bilddaten.

### YCbCrSubSampling {#YCbCrSubSampling}
```
public static final int YCbCrSubSampling
```


Das Abtastverhältnis der Chrominanzkomponenten im Verhältnis zur Luminanzkomponente.

### YCbCrPositioning {#YCbCrPositioning}
```
public static final int YCbCrPositioning
```


Die Position der Chrominanzkomponenten in Relation zur Luminanzkomponente. Dieses Feld ist nur für JPEG‑komprimierte Daten oder unkomprimierte YCbCr‑Daten vorgesehen. Der TIFF‑Standardwert ist 1 (zentriert); bei Y:Cb:Cr = 4:2:2 wird in diesem Standard empfohlen, 2 (nebeneinander) zu verwenden, um Daten zu speichern, um die Bildqualität bei Anzeige auf TV‑Systemen zu verbessern. Existiert dieses Feld nicht, muss der Leser den TIFF‑Standardwert annehmen. Im Fall von Y:Cb:Cr = 4:2:0 wird der TIFF‑Standardwert (zentriert) empfohlen. Wenn der Leser nicht in der Lage ist, beide Arten von YCbCrPositioning zu unterstützen, muss er unabhängig vom Wert in diesem Feld den TIFF‑Standardwert verwenden. Es ist wünschenswert, dass Leser \" in der Lage sind, sowohl zentrierte als auch nebeneinander liegende Positionierungen zu unterstützen.

### ReferenceBlackWhite {#ReferenceBlackWhite}
```
public static final int ReferenceBlackWhite
```


Der Referenzwert für den Schwarzpunkt und der Referenzwert für den Weißpunkt. In TIFF werden keine Vorgaben bereitgestellt, aber die nachstehenden Werte werden hier als Vorgaben angegeben. Der Farbraum wird in einem Farbrauminformations‑Tag deklariert, wobei die Vorgabe der Wert ist, der die optimalen Bildmerkmale Interoperability unter diesen Bedingungen liefert.

### Copyright {#Copyright}
```
public static final int Copyright
```


Copyright‑Informationen. In diesem Standard wird das Tag verwendet, um sowohl die Urheberrechte des Fotografen als auch des Editors anzugeben. Es ist der Copyright‑Hinweis der Person oder Organisation, die Rechte an dem Bild beansprucht. Die Interoperability‑Copyright‑Erklärung inklusive Datum und Rechte sollte in diesem Feld geschrieben werden; z. B. \"Copyright, John Smith, 19xx. All rights reserved.\" In diesem Standard zeichnet das Feld sowohl die Urheberrechte des Fotografen als auch des Editors auf, wobei jedes in einem separaten Teil der Aussage gespeichert wird. Wenn eine klare Unterscheidung zwischen den Urheberrechten des Fotografen und des Editors besteht, werden sie in der Reihenfolge Fotograf gefolgt vom Editor‑Copyright geschrieben, getrennt durch NULL (in diesem Fall, da die Aussage ebenfalls mit einem NULL endet, gibt es zwei NULL‑Codes). Wird nur das Fotografen‑Copyright angegeben, wird es durch einen NULL‑Code beendet. Wird nur das Editor‑Copyright angegeben, besteht der Fotografen‑Copyright‑Teil aus einem Leerzeichen, gefolgt von einem abschließenden NULL‑Code, danach wird das Editor‑Copyright angegeben. Wird das Feld leer gelassen, gilt es als unbekannt.

### ExposureTime {#ExposureTime}
```
public static final int ExposureTime
```


Belichtungszeit, angegeben in Sekunden.

### FNumber {#FNumber}
```
public static final int FNumber
```


Die Blendenzahl.

### ExposureProgram {#ExposureProgram}
```
public static final int ExposureProgram
```


Die Klasse des Programms, das von der Kamera verwendet wird, um die Belichtung beim Aufnehmen des Bildes einzustellen.

### SpectralSensitivity {#SpectralSensitivity}
```
public static final int SpectralSensitivity
```


Gibt die spektrale Empfindlichkeit jedes Kanals der verwendeten Kamera an.

### PhotographicSensitivity {#PhotographicSensitivity}
```
public static final int PhotographicSensitivity
```


Gibt die ISO-Geschwindigkeit und ISO-Latitude der Kamera oder des Eingabegeräts gemäß ISO 12232 an.

### OECF {#OECF}
```
public static final int OECF
```


Gibt die in ISO 14524 angegebene Opto‑Elektrische Umwandlungsfunktion (OECF) an.

### ExifVersion {#ExifVersion}
```
public static final int ExifVersion
```


Die Exif-Version.

### DateTimeOriginal {#DateTimeOriginal}
```
public static final int DateTimeOriginal
```


Datum und Uhrzeit, wann die Originalbilddaten erzeugt wurden.

### DateTimeDigitized {#DateTimeDigitized}
```
public static final int DateTimeDigitized
```


Das Digitalisierungsdatum und die -uhrzeit.

### ComponentsConfiguration {#ComponentsConfiguration}
```
public static final int ComponentsConfiguration
```


Die Konfiguration der Komponenten.

### CompressedBitsPerPixel {#CompressedBitsPerPixel}
```
public static final int CompressedBitsPerPixel
```


Spezifisch für komprimierte Daten; gibt die komprimierten Bits pro Pixel an.

### ShutterSpeedValue {#ShutterSpeedValue}
```
public static final int ShutterSpeedValue
```


Der Wert der Verschlusszeit.

### ApertureValue {#ApertureValue}
```
public static final int ApertureValue
```


Der Wert der Objektivblende.

### BrightnessValue {#BrightnessValue}
```
public static final int BrightnessValue
```


Der Helligkeitswert.

### ExposureBiasValue {#ExposureBiasValue}
```
public static final int ExposureBiasValue
```


Der Belichtungskorrekturwert.

### MaxApertureValue {#MaxApertureValue}
```
public static final int MaxApertureValue
```


Der maximale Blendenwert.

### SubjectDistance {#SubjectDistance}
```
public static final int SubjectDistance
```


Die Entfernung zum Motiv, angegeben in Metern.

### MeteringMode {#MeteringMode}
```
public static final int MeteringMode
```


Der Messmodus.

### LightSource {#LightSource}
```
public static final int LightSource
```


Die Art der Lichtquelle.

### Flash {#Flash}
```
public static final int Flash
```


Gibt den Blitzstatus an, als das Bild aufgenommen wurde.

### FocalLength {#FocalLength}
```
public static final int FocalLength
```


Die tatsächliche Brennweite des Objektivs in mm.

### SubjectArea {#SubjectArea}
```
public static final int SubjectArea
```


Dieses Tag gibt die Position und den Bereich des Hauptmotivs in der gesamten Szene an.

### MakerNote {#MakerNote}
```
public static final int MakerNote
```


Ein Tag für Hersteller von Exif‑Schreibern, um beliebige gewünschte Informationen zu speichern. Der Inhalt liegt im Ermessen des Herstellers, aber dieses Tag sollte nicht für andere Zwecke als den vorgesehenen verwendet werden.

### UserComment {#UserComment}
```
public static final int UserComment
```


Ein Tag für Exif-Anwender, um Schlüsselwörter oder Kommentare zum Bild zu schreiben, zusätzlich zu denen im ImageDescription-Tag und ohne die Zeichenkodierungsbeschränkungen des ImageDescription-Tags.

### SubsecTime {#SubsecTime}
```
public static final int SubsecTime
```


Ein Tag, das Bruchteile von Sekunden für das DateTime-Tag speichert.

### SubsecTimeOriginal {#SubsecTimeOriginal}
```
public static final int SubsecTimeOriginal
```


Ein Tag, das Bruchteile von Sekunden für das DateTimeOriginal-Tag speichert.

### SubsecTimeDigitized {#SubsecTimeDigitized}
```
public static final int SubsecTimeDigitized
```


Ein Tag, das Bruchteile von Sekunden für das DateTimeDigitized-Tag speichert.

### FlashpixVersion {#FlashpixVersion}
```
public static final int FlashpixVersion
```


Die von einer FPXR-Datei unterstützte Flashpix-Formatversion.

### ColorSpace {#ColorSpace}
```
public static final int ColorSpace
```


Das Farbraum-Informationstag (ColorSpace) wird immer als Farbraumspezifizierer aufgezeichnet.

### RelatedSoundFile {#RelatedSoundFile}
```
public static final int RelatedSoundFile
```


Die zugehörige Audiodatei.

### FlashEnergy {#FlashEnergy}
```
public static final int FlashEnergy
```


Gibt die Blitzenergie zum Zeitpunkt der Aufnahme des Bildes an, gemessen in Beam Candle Power Seconds (BCPS).

### SpatialFrequencyResponse {#SpatialFrequencyResponse}
```
public static final int SpatialFrequencyResponse
```


Dieses Tag zeichnet die räumliche Frequenztafel und SFR-Werte der Kamera oder des Eingabegeräts in Richtung Bildbreite, Bildhöhe und Diagonalrichtung auf, wie in ISO 12233 angegeben.

### FocalPlaneXResolution {#FocalPlaneXResolution}
```
public static final int FocalPlaneXResolution
```


Gibt die Anzahl der Pixel in Bildbreite (X)-Richtung pro FocalPlaneResolutionUnit auf der Kamera-Brennweitebene an.

### FocalPlaneYResolution {#FocalPlaneYResolution}
```
public static final int FocalPlaneYResolution
```


Gibt die Anzahl der Pixel in Bildhöhe (Y)-Richtung pro FocalPlaneResolutionUnit auf der Kamera-Brennweitebene an.

### FocalPlaneResolutionUnit {#FocalPlaneResolutionUnit}
```
public static final int FocalPlaneResolutionUnit
```


Gibt die Einheit für die Messung von FocalPlaneXResolution und FocalPlaneYResolution an. Dieser Wert entspricht dem ResolutionUnit.

### SubjectLocation {#SubjectLocation}
```
public static final int SubjectLocation
```


Gibt die Position des Hauptmotivs in der Szene an. Der Wert dieses Tags stellt das Pixel im Zentrum des Hauptmotivs relativ zum linken Rand dar, bevor die Drehverarbeitung gemäß dem Rotation‑Tag erfolgt.

### ExposureIndex {#ExposureIndex}
```
public static final int ExposureIndex
```


Gibt den beim Aufnehmen des Bildes ausgewählten Belichtungsindex der Kamera oder des Eingabegeräts an.

### SensingMethod {#SensingMethod}
```
public static final int SensingMethod
```


Gibt den Bildsensortyp der Kamera oder des Eingabegeräts an.

### FileSource {#FileSource}
```
public static final int FileSource
```


Die Dateiquelle.

### SceneType {#SceneType}
```
public static final int SceneType
```


Gibt den Szenentyp an. Wenn ein DSC das Bild aufgenommen hat, muss dieser Tag‑Wert immer auf 1 gesetzt werden, was bedeutet, dass das Bild direkt fotografiert wurde.

### CFAPattern {#CFAPattern}
```
public static final int CFAPattern
```


Gibt das geometrische Muster des Color Filter Array (CFA) des Bildsensors an, wenn ein Ein-Chip‑Farbflächen‑Sensor verwendet wird. Es gilt nicht für alle Sensormethoden.

### CustomRendered {#CustomRendered}
```
public static final int CustomRendered
```


Dieses Tag weist auf die Verwendung einer speziellen Verarbeitung von Bilddaten hin, z. B. auf die Ausgabe ausgerichtetes Rendering. Wird eine Spezialverarbeitung durchgeführt, wird vom Leser erwartet, dass er weitere Verarbeitungen deaktiviert oder minimiert.

### ExposureMode {#ExposureMode}
```
public static final int ExposureMode
```


Dieses Tag gibt den beim Aufnehmen des Bildes eingestellten Belichtungsmodus an. Im Auto‑Bracketing‑Modus nimmt die Kamera eine Reihe von Aufnahmen derselben Szene mit unterschiedlichen Belichtungseinstellungen auf.

### WhiteBalance {#WhiteBalance}
```
public static final int WhiteBalance
```


Dieses Tag gibt den eingestellten Weißabgleichmodus bei der Aufnahme des Bildes an.

### DigitalZoomRatio {#DigitalZoomRatio}
```
public static final int DigitalZoomRatio
```


Dieses Tag gibt das digitale Zoom‑Verhältnis beim Aufnehmen des Bildes an. Ist der Zähler des aufgezeichneten Wertes 0, bedeutet dies, dass kein digitaler Zoom verwendet wurde.

### FocalLengthIn35MmFilm {#FocalLengthIn35MmFilm}
```
public static final int FocalLengthIn35MmFilm
```


Dieses Tag gibt die äquivalente Brennweite an, ausgehend von einer 35‑mm-Filmkamera, in mm. Ein Wert von 0 bedeutet, dass die Brennweite unbekannt ist. Hinweis: Dieses Tag unterscheidet sich vom FocalLength‑Tag.

### SceneCaptureType {#SceneCaptureType}
```
public static final int SceneCaptureType
```


Dieses Tag gibt den aufgenommenen Szenentyp an. Es kann auch verwendet werden, um den Modus zu speichern, in dem das Bild aufgenommen wurde.

### GainControl {#GainControl}
```
public static final int GainControl
```


Dieses Tag gibt den Grad der allgemeinen Bildverstärkungsanpassung an.

### Contrast {#Contrast}
```
public static final int Contrast
```


Dieses Tag gibt die Richtung der vom Kamerasystem angewendeten Kontrastverarbeitung an, wenn das Bild aufgenommen wurde.

### Saturation {#Saturation}
```
public static final int Saturation
```


Dieses Tag gibt die Richtung der vom Kamerasystem angewendeten Sättigungsverarbeitung an, wenn das Bild aufgenommen wurde.

### Sharpness {#Sharpness}
```
public static final int Sharpness
```


Dieses Tag gibt die Richtung der vom Kamerasystem angewendeten Schärfeverarbeitung an, wenn das Bild aufgenommen wurde

### DeviceSettingDescription {#DeviceSettingDescription}
```
public static final int DeviceSettingDescription
```


Dieses Tag liefert Informationen zu den Aufnahmebedingungen eines bestimmten Kameramodells. Das Tag wird ausschließlich verwendet, um die Aufnahmebedingungen im Leser anzuzeigen.

### SubjectDistanceRange {#SubjectDistanceRange}
```
public static final int SubjectDistanceRange
```


Dieses Tag gibt die Entfernung zum Motiv an.

### ImageUniqueID {#ImageUniqueID}
```
public static final int ImageUniqueID
```


Die eindeutige Bild-ID.

### GPSVersionID {#GPSVersionID}
```
public static final int GPSVersionID
```


Gibt die Version von GPSInfoIFD an.

### GPSLatitudeRef {#GPSLatitudeRef}
```
public static final int GPSLatitudeRef
```


Gibt an, ob die Breite nördlich oder südlich ist.

### GPSLatitude {#GPSLatitude}
```
public static final int GPSLatitude
```


Gibt die Breite an. Die Breite wird als drei RATIONAL‑Werte angegeben, die jeweils Grad, Minuten und Sekunden darstellen. Wird die Breite in Grad, Minuten und Sekunden ausgedrückt, hat ein typisches Format dd/1,mm/1,ss/1. Werden Grad und Minuten verwendet und beispielsweise Bruchteile von Minuten bis zu zwei Dezimalstellen angegeben, lautet das Format dd/1,mmmm/100,0/1.

### GPSLongitudeRef {#GPSLongitudeRef}
```
public static final int GPSLongitudeRef
```


Gibt an, ob die Länge östlich oder westlich ist.

### GPSLongitude {#GPSLongitude}
```
public static final int GPSLongitude
```


Gibt die Länge an. Die Länge wird als drei RATIONAL‑Werte angegeben, die jeweils Grad, Minuten und Sekunden darstellen. Wird die Länge in Grad, Minuten und Sekunden ausgedrückt, hat ein typisches Format ddd/1,mm/1,ss/1. Werden Grad und Minuten verwendet und beispielsweise Bruchteile von Minuten bis zu zwei Dezimalstellen angegeben, lautet das Format ddd/1,mmmm/100,0/1.

### GPSAltitudeRef {#GPSAltitudeRef}
```
public static final int GPSAltitudeRef
```


Gibt die als Referenz verwendete Höhe an. Wenn die Referenz Meereshöhe ist und die Höhe über dem Meeresspiegel liegt, wird 0 angegeben. Liegt die Höhe unter dem Meeresspiegel, wird ein Wert von 1 angegeben und die Höhe wird als absoluter Wert im GPSAltitude‑Tag angegeben.

### GPSAltitude {#GPSAltitude}
```
public static final int GPSAltitude
```


Gibt die Höhe basierend auf dem Referenzwert in GPSAltitudeRef an. Die Höhe wird als ein RATIONAL‑Wert ausgedrückt. Die Referenzeinheit ist Meter.

### GPSTimestamp {#GPSTimestamp}
```
public static final int GPSTimestamp
```


Gibt die Zeit als UTC (Coordinated Universal Time) an. Der Zeitstempel wird als drei RATIONAL‑Werte angegeben, die Stunde, Minute und Sekunde darstellen.

### GPSSatellites {#GPSSatellites}
```
public static final int GPSSatellites
```


Gibt die für Messungen verwendeten GPS‑Satelliten an. Dieses Tag kann verwendet werden, um die Anzahl der Satelliten, deren ID‑Nummer, Elevationswinkel, Azimut, SNR und weitere Informationen in ASCII‑Notation zu beschreiben. Das Format ist nicht spezifiziert. Ist der GPS‑Empfänger nicht in der Lage, Messungen durchzuführen, muss der Wert des Tags auf NULL gesetzt werden.

### GPSStatus {#GPSStatus}
```
public static final int GPSStatus
```


Gibt den Status des GPS‑Empfängers an, wenn das Bild aufgenommen wird.

### GPSMeasureMode {#GPSMeasureMode}
```
public static final int GPSMeasureMode
```


Gibt den GPS‑Messmodus an. – 2‑ oder 3‑dimensional.

### GPSDOP {#GPSDOP}
```
public static final int GPSDOP
```


Gibt den GPS‑DOP (Data Degree of Precision) an. Ein HDOP‑Wert wird bei zweidimensionaler Messung geschrieben, und ein PDOP‑Wert bei dreidimensionaler Messung.

### GPSSpeedRef {#GPSSpeedRef}
```
public static final int GPSSpeedRef
```


Gibt die Einheit an, in der die Geschwindigkeit des GPS‑Empfängers ausgedrückt wird. 'K', 'M' und 'N' stehen für Kilometer pro Stunde, Meilen pro Stunde und Knoten.

### GPSSpeed {#GPSSpeed}
```
public static final int GPSSpeed
```


Gibt die Geschwindigkeit der GPS‑Empfängerbewegung an.

### GPSTrackRef {#GPSTrackRef}
```
public static final int GPSTrackRef
```


Gibt die Referenz für die Angabe der Bewegungsrichtung des GPS‑Empfängers an. 'T' steht für wahre Richtung und 'M' für magnetische Richtung.

### GPSTrack {#GPSTrack}
```
public static final int GPSTrack
```


Gibt die Bewegungsrichtung des GPS‑Empfängers an. Der Wertebereich liegt zwischen 0.00 und 359.99.

### GPSImgDirectionRef {#GPSImgDirectionRef}
```
public static final int GPSImgDirectionRef
```


Gibt die Referenz für die Angabe der Bildrichtung bei der Aufnahme an. 'T' steht für wahre Richtung und 'M' für magnetische Richtung.

### GPSImgDirection {#GPSImgDirection}
```
public static final int GPSImgDirection
```


Gibt die Bildrichtung bei der Aufnahme an. Der Wertebereich liegt zwischen 0.00 und 359.99.

### GPSMapDatum {#GPSMapDatum}
```
public static final int GPSMapDatum
```


Gibt die vom GPS-Empfänger verwendeten geodätischen Vermessungsdaten an.

### GPSDestLatitudeRef {#GPSDestLatitudeRef}
```
public static final int GPSDestLatitudeRef
```


Gibt an, ob die Breite des Zielpunkts nördliche oder südliche Breite ist. Der ASCII‑Wert 'N' steht für nördliche Breite, 'S' für südliche Breite.

### GPSDestLatitude {#GPSDestLatitude}
```
public static final int GPSDestLatitude
```


Gibt die Breite des Zielpunkts an. Die Breite wird als drei RATIONAL‑Werte angegeben, die Grad, Minuten und Sekunden darstellen. Wird die Breite in Grad, Minuten und Sekunden angegeben, ist ein typisches Format dd/1,mm/1,ss/1. Werden Grad und Minuten verwendet und z. B. Minutenbruchteile bis zu zwei Dezimalstellen angegeben, lautet das Format dd/1,mmmm/100,0/1.

### GPSDestLongitudeRef {#GPSDestLongitudeRef}
```
public static final int GPSDestLongitudeRef
```


Gibt an, ob die Länge des Zielpunkts östliche oder westliche Länge ist. ASCII 'E' steht für östliche Länge, 'W' für westliche Länge.

### GPSDestLongitude {#GPSDestLongitude}
```
public static final int GPSDestLongitude
```


Gibt die Länge des Zielpunkts an. Die Länge wird als drei RATIONAL‑Werte angegeben, die Grad, Minuten und Sekunden darstellen. Wird die Länge in Grad, Minuten und Sekunden angegeben, ist ein typisches Format ddd/1,mm/1,ss/1. Werden Grad und Minuten verwendet und z. B. Minutenbruchteile bis zu zwei Dezimalstellen angegeben, lautet das Format ddd/1,mmmm/100,0/1.

### GPSDestBearingRef {#GPSDestBearingRef}
```
public static final int GPSDestBearingRef
```


Gibt die Referenz für die Angabe des Kurses zum Zielpunkt an. 'T' steht für wahre Richtung und 'M' für magnetische Richtung.

### GPSDestBearing {#GPSDestBearing}
```
public static final int GPSDestBearing
```


Gibt den Kurs zum Zielpunkt an. Der Wertebereich liegt zwischen 0.00 und 359.99.

### GPSDestDistanceRef {#GPSDestDistanceRef}
```
public static final int GPSDestDistanceRef
```


Gibt die Einheit an, die zur Angabe der Entfernung zum Zielpunkt verwendet wird. 'K', 'M' und 'N' stehen für Kilometer, Meilen und Knoten.

### GPSDestDistance {#GPSDestDistance}
```
public static final int GPSDestDistance
```


Gibt die Entfernung zum Zielpunkt an.

### GPSProcessingMethod {#GPSProcessingMethod}
```
public static final int GPSProcessingMethod
```


Eine Zeichenkette, die den Namen der zur Positionsbestimmung verwendeten Methode aufzeichnet. Das erste Byte gibt den verwendeten Zeichencode an, gefolgt vom Methodennamen.

### GPSAreaInformation {#GPSAreaInformation}
```
public static final int GPSAreaInformation
```


Eine Zeichenkette, die den Namen des GPS‑Gebiets aufzeichnet. Das erste Byte gibt den verwendeten Zeichencode an, gefolgt vom Namen des GPS‑Gebiets.

### GPSDateStamp {#GPSDateStamp}
```
public static final int GPSDateStamp
```


Eine Zeichenkette, die Datums‑ und Zeitinformationen relativ zu UTC (Coordinated Universal Time) aufzeichnet. Das Format ist JJJJ:MM:TT.

### GPSDifferential {#GPSDifferential}
```
public static final int GPSDifferential
```


Gibt an, ob eine Differenzkorrektur auf den GPS‑Empfänger angewendet wird.

### StripOffsets {#StripOffsets}
```
public static final int StripOffsets
```


Für jeden Streifen gibt der Byte‑Versatz dieses Streifens an. Es wird empfohlen, diesen so zu wählen, dass die Anzahl der Streifen‑Bytes 64 KB nicht überschreitet. Aux‑Tag.

### JPEGInterchangeFormat {#JPEGInterchangeFormat}
```
public static final int JPEGInterchangeFormat
```


Der Versatz zum Startbyte (SOI) der JPEG‑komprimierten Miniaturbilddaten. Dieser wird nicht für die primären JPEG‑Bilddaten verwendet.

### JPEGInterchangeFormatLength {#JPEGInterchangeFormatLength}
```
public static final int JPEGInterchangeFormatLength
```


Die Anzahl der Bytes der JPEG‑komprimierten Miniaturbilddaten. Dieser wird nicht für die primären JPEG‑Bilddaten verwendet. JPEG‑Miniaturbilder werden nicht aufgeteilt, sondern als durchgehender JPEG‑Bitstream von SOI bis EOI aufgezeichnet. Appn‑ und COM‑Marker sollten nicht aufgezeichnet werden. Komprimierte Miniaturbilder dürfen nicht mehr als 64 KB umfassen, einschließlich aller weiteren in APP1 zu speichernden Daten.

### ExifIfdPointer {#ExifIfdPointer}
```
public static final int ExifIfdPointer
```


Ein Zeiger auf das Exif‑IFD. Interoperabilität, das Exif‑IFD hat dieselbe Struktur wie das in TIFF spezifizierte IFD. In der Regel enthält es jedoch keine Bilddaten, wie es bei TIFF der Fall ist.

### GPSIfdPointer {#GPSIfdPointer}
```
public static final int GPSIfdPointer
```


Der gps ifd pointer.

### RowsPerStrip {#RowsPerStrip}
```
public static final int RowsPerStrip
```


Die Anzahl der Zeilen pro Streifen. Dies ist die Zeilenanzahl im Bild eines Streifens, wenn ein Bild in Streifen aufgeteilt wird.

### StripByteCounts {#StripByteCounts}
```
public static final int StripByteCounts
```


Die Gesamtzahl der Bytes in jedem Streifen.

### PixelXDimension {#PixelXDimension}
```
public static final int PixelXDimension
```


Informationen, die spezifisch für komprimierte Daten sind. Wenn eine komprimierte Datei aufgezeichnet wird, soll die gültige Breite des sinnvollen Bildes in diesem Tag gespeichert werden, unabhängig davon, ob Padding‑Daten oder ein Neustart‑Marker vorhanden sind.

### PixelYDimension {#PixelYDimension}
```
public static final int PixelYDimension
```


Informationen, die spezifisch für komprimierte Daten sind. Wenn eine komprimierte Datei aufgezeichnet wird, soll die gültige Höhe des sinnvollen Bildes in diesem Tag gespeichert werden.

### Gamma {#Gamma}
```
public static final int Gamma
```


Gamma-Wert

### SensitivityType {#SensitivityType}
```
public static final int SensitivityType
```


Typ der fotografischen Empfindlichkeit

### StandardOutputSensitivity {#StandardOutputSensitivity}
```
public static final int StandardOutputSensitivity
```


Gibt die Standard-Ausgabesensitivität der Kamera an

### RecommendedExposureIndex {#RecommendedExposureIndex}
```
public static final int RecommendedExposureIndex
```


Gibt den empfohlenen Belichtungsindex an

### ISOSpeed {#ISOSpeed}
```
public static final int ISOSpeed
```


Informationen zum ISO-Geschwindigkeitswert gemäß ISO 12232

### ISOSpeedLatitudeYYY {#ISOSpeedLatitudeYYY}
```
public static final int ISOSpeedLatitudeYYY
```


Dieses Tag gibt den ISO-Geschwindigkeitslatitudenwert yyy gemäß ISO 12232 an

### ISOSpeedLatitudeZZZ {#ISOSpeedLatitudeZZZ}
```
public static final int ISOSpeedLatitudeZZZ
```


Dieses Tag gibt den ISO-Geschwindigkeitslatitudenwert zzz gemäß ISO 12232 an

### CameraOwnerName {#CameraOwnerName}
```
public static final int CameraOwnerName
```


Enthält den Namen des Kamerabesitzers

### BodySerialNumber {#BodySerialNumber}
```
public static final int BodySerialNumber
```


Enthält die Seriennummer des Kameragehäuses

### LensMake {#LensMake}
```
public static final int LensMake
```


Dieses Tag zeichnet den Hersteller des Objektivs auf

### LensModel {#LensModel}
```
public static final int LensModel
```


Dieses Tag zeichnet den Modellnamen und die Modellnummer des Objektivs\`s auf

### LensSerialNumber {#LensSerialNumber}
```
public static final int LensSerialNumber
```


Dieses Tag zeichnet die Seriennummer des austauschbaren Objektivs auf

### LensSpecification {#LensSpecification}
```
public static final int LensSpecification
```


Dieses Tag vermerkt die minimale Brennweite, maximale Brennweite, die minimale Blendenzahl bei der minimalen Brennweite und die minimale Blendenzahl bei der maximalen Brennweite

