---
title: "ExifData"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "EXIF-Datencontainer."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.exif/exifdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.exif.TiffDataTypeController](../../com.aspose.imaging.exif/tiffdatatypecontroller)

**All Implemented Interfaces:**
[com.aspose.imaging.metadata.IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)
```
public class ExifData extends TiffDataTypeController implements IImageMetadataFormat
```

EXIF-Datencontainer.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ExifData()](#ExifData--) | Initialisiert eine neue Instanz der `ExifData`-Klasse. |
| [ExifData(TiffDataType[] exifdata)](#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Initialisiert eine neue Instanz der `ExifData`-Klasse mit Daten aus einem Array. |
| [ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---) | Initialisiert eine neue Instanz der `ExifData`-Klasse mit Daten aus einem Array. |
| [ExifData(ExifData exifdata)](#ExifData-com.aspose.imaging.exif.ExifData-) | Initialisiert eine neue Instanz der [ExifData](../../com.aspose.imaging.exif/exifdata)-Klasse mit Daten aus einem Array. |
| [ExifData(byte[] binaryData)](#ExifData-byte---) | Initialisiert eine neue Instanz der [ExifData](../../com.aspose.imaging.exif/exifdata)-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isBigEndian()](#isBigEndian--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob die aus dem Stream erstellten EXIF-Daten im Big-Endian-Format vorliegen. |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob die aus dem Stream erstellten EXIF-Daten im Big-Endian-Format vorliegen. |
| [getMake()](#getMake--) | Ruft den Hersteller der Aufnahmeeinrichtung ab. |
| [setMake(String value)](#setMake-java.lang.String-) | Legt den Hersteller der Aufnahmeeinrichtung fest. |
| [getApertureValue()](#getApertureValue--) | Ruft den Blendenwert ab oder legt ihn fest. |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ruft den Blendenwert ab oder legt ihn fest. |
| [getBodySerialNumber()](#getBodySerialNumber--) | Ruft die Seriennummer des Kameragehäuses ab oder legt sie fest. |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | Ruft die Seriennummer des Kameragehäuses ab oder legt sie fest. |
| [getBrightnessValue()](#getBrightnessValue--) | Ruft den Helligkeitswert ab oder legt ihn fest. |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Ruft den Helligkeitswert ab oder legt ihn fest. |
| [getCFAPattern()](#getCFAPattern--) | Ruft das CFA-Muster ab oder legt es fest. |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | Ruft das CFA-Muster ab oder legt es fest. |
| [getCameraOwnerName()](#getCameraOwnerName--) | Ruft den Namen des Kamerabesitzers ab oder legt ihn fest |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | Ruft den Namen des Kamerabesitzers ab oder legt ihn fest |
| [getColorSpace()](#getColorSpace--) | Ruft den Farbraum ab oder legt ihn fest. |
| [setColorSpace(int value)](#setColorSpace-int-) | Ruft den Farbraum ab oder legt ihn fest. |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | Ruft die Komponenten-Konfiguration ab oder legt sie fest. |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | Ruft die Komponenten-Konfiguration ab oder legt sie fest. |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | Ruft die komprimierten Bits pro Pixel ab oder legt sie fest. |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ruft die komprimierten Bits pro Pixel ab oder legt sie fest. |
| [getContrast()](#getContrast--) | Liest oder setzt den Kontrast. |
| [setContrast(int value)](#setContrast-int-) | Liest oder setzt den Kontrast. |
| [getCustomRendered()](#getCustomRendered--) | Liest oder setzt das benutzerdefinierte Rendering. |
| [setCustomRendered(int value)](#setCustomRendered-int-) | Liest oder setzt das benutzerdefinierte Rendering. |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | Liest oder setzt das digitalisierte Datum und die Uhrzeit. |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | Liest oder setzt das digitalisierte Datum und die Uhrzeit. |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | Liest oder setzt das ursprüngliche Datum und die Uhrzeit. |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | Liest oder setzt das ursprüngliche Datum und die Uhrzeit. |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | Liest oder setzt die Geräte‑Einstellungsbeschreibung. |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | Liest oder setzt die Geräte‑Einstellungsbeschreibung. |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | Liest oder setzt das digitale Zoomverhältnis. |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.imaging.fileformats.tiff.TiffRational-) | Liest oder setzt das digitale Zoomverhältnis. |
| [getExifVersion()](#getExifVersion--) | Liest oder setzt die EXIF-Version. |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | Liest oder setzt die EXIF-Version. |
| [getExposureBiasValue()](#getExposureBiasValue--) | Liest oder setzt den Belichtungswert. |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Liest oder setzt den Belichtungswert. |
| [getExposureIndex()](#getExposureIndex--) | Liest oder setzt den Belichtungsindex. |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.imaging.fileformats.tiff.TiffRational-) | Liest oder setzt den Belichtungsindex. |
| [getExposureMode()](#getExposureMode--) | Liest oder setzt den Belichtungsmodus. |
| [setExposureMode(int value)](#setExposureMode-int-) | Liest oder setzt den Belichtungsmodus. |
| [getExposureProgram()](#getExposureProgram--) | Liest oder setzt das Belichtungsprogramm. |
| [setExposureProgram(int value)](#setExposureProgram-int-) | Liest oder setzt das Belichtungsprogramm. |
| [getExposureTime()](#getExposureTime--) | Liest oder setzt die Belichtungszeit. |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.imaging.fileformats.tiff.TiffRational-) | Liest oder setzt die Belichtungszeit. |
| [getFNumber()](#getFNumber--) | Liest oder setzt die Blendenzahl. |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.imaging.fileformats.tiff.TiffRational-) | Liest oder setzt die Blendenzahl. |
| [getFileSource()](#getFileSource--) | Liest oder setzt den Dateiquellen‑Typ. |
| [setFileSource(byte value)](#setFileSource-byte-) | Liest oder setzt den Dateiquellen‑Typ. |
| [getFlash()](#getFlash--) | Liest oder setzt den Blitz. |
| [setFlash(int value)](#setFlash-int-) | Liest oder setzt den Blitz. |
| [getFlashEnergy()](#getFlashEnergy--) | Liest oder setzt die Blitzenergie. |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.imaging.fileformats.tiff.TiffRational-) | Liest oder setzt die Blitzenergie. |
| [getFlashpixVersion()](#getFlashpixVersion--) | Liest oder setzt die Blitz‑Pix‑Version. |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | Liest oder setzt die Blitz‑Pix‑Version. |
| [getFocalLength()](#getFocalLength--) | Liest oder setzt die Brennweite. |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.imaging.fileformats.tiff.TiffRational-) | Liest oder setzt die Brennweite. |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | Liest oder setzt die Brennweite in 35 mm-Film. |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | Liest oder setzt die Brennweite in 35 mm-Film. |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | Liest oder setzt die Auflösungseinheit der Bildebene. |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | Liest oder setzt die Auflösungseinheit der Bildebene. |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | Liest oder setzt die X‑Auflösung der Bildebene. |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Liest oder setzt die X‑Auflösung der Bildebene. |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | Liest oder setzt die Y‑Auflösung der Bildebene. |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Liest oder setzt die Y‑Auflösung der Bildebene. |
| [getGPSAltitude()](#getGPSAltitude--) | Liest oder setzt die GPS-Höhe. |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.imaging.fileformats.tiff.TiffRational-) | Liest oder setzt die GPS-Höhe. |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | Liest oder setzt die GPS-Höhe, die als Referenzhöhe verwendet wird. |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | Liest oder setzt die GPS-Höhe, die als Referenzhöhe verwendet wird. |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | Liest oder setzt die GPS-Bereichsinformation. |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | Liest oder setzt die GPS-Bereichsinformation. |
| [getGPSDOP()](#getGPSDOP--) | Liest oder setzt den GPS DOP (Datengrad der Genauigkeit). |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.imaging.fileformats.tiff.TiffRational-) | Liest oder setzt den GPS DOP (Datengrad der Genauigkeit). |
| [getGPSDestBearing()](#getGPSDestBearing--) | Liest oder setzt die GPS-Richtung zum Zielpunkt. |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.imaging.fileformats.tiff.TiffRational-) | Liest oder setzt die GPS-Richtung zum Zielpunkt. |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | Liest oder setzt die GPS-Referenz, die zur Angabe der Richtung zum Zielpunkt verwendet wird. |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | Liest oder setzt die GPS-Referenz, die zur Angabe der Richtung zum Zielpunkt verwendet wird. |
| [getGPSDestDistance()](#getGPSDestDistance--) | Liest oder setzt die GPS-Entfernung zum Zielpunkt. |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.imaging.fileformats.tiff.TiffRational-) | Liest oder setzt die GPS-Entfernung zum Zielpunkt. |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | Liest oder setzt die GPS-Einheit, die zur Angabe der Entfernung zum Zielpunkt verwendet wird. |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | Liest oder setzt die GPS-Einheit, die zur Angabe der Entfernung zum Zielpunkt verwendet wird. |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | Liest oder setzt den GPS-Breitengrad des Zielpunkts. |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Liest oder setzt den GPS-Breitengrad des Zielpunkts. |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | Liest oder setzt den GPS-Wert, der angibt, ob der Breitengrad des Zielpunkts nördlich oder südlich ist. |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | Liest oder setzt den GPS-Wert, der angibt, ob der Breitengrad des Zielpunkts nördlich oder südlich ist. |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | Liest oder setzt den GPS-Längengrad des Zielpunkts. |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Liest oder setzt den GPS-Längengrad des Zielpunkts. |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | Liest oder setzt den GPS-Wert, der angibt, ob der Längengrad des Zielpunkts östlich oder westlich ist. |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | Liest oder setzt den GPS-Wert, der angibt, ob der Längengrad des Zielpunkts östlich oder westlich ist. |
| [getGPSDifferential()](#getGPSDifferential--) | Liest oder setzt einen GPS-Wert, der angibt, ob eine differentielle Korrektur auf den GPS-Empfänger angewendet wird. |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | Liest oder setzt einen GPS-Wert, der angibt, ob eine differentielle Korrektur auf den GPS-Empfänger angewendet wird. |
| [getGPSImgDirection()](#getGPSImgDirection--) | Liest oder setzt die GPS-Richtung des Bildes zum Zeitpunkt der Aufnahme. |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.imaging.fileformats.tiff.TiffRational-) | Liest oder setzt die GPS-Richtung des Bildes zum Zeitpunkt der Aufnahme. |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | Liest oder setzt die GPS-Referenz zur Angabe der Bildrichtung bei der Aufnahme. |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | Liest oder setzt die GPS-Referenz zur Angabe der Bildrichtung bei der Aufnahme. |
| [getGPSDateStamp()](#getGPSDateStamp--) | Liest oder setzt die GPS-Zeichenkette, die Datum- und Zeitinformationen relativ zu UTC (Koordinierte Weltzeit) aufzeichnet. |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | Liest oder setzt die GPS-Zeichenkette, die Datum- und Zeitinformationen relativ zu UTC (Koordinierte Weltzeit) aufzeichnet. |
| [getGPSLatitude()](#getGPSLatitude--) | Liest oder setzt den GPS-Breitengrad. |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Liest oder setzt den GPS-Breitengrad. |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | Liest oder setzt, ob der GPS-Breitengrad nördlich oder südlich ist. |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | Liest oder setzt, ob der GPS-Breitengrad nördlich oder südlich ist. |
| [getGPSLongitude()](#getGPSLongitude--) | Liest oder setzt den GPS-Längengrad. |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Liest oder setzt den GPS-Längengrad. |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | Liest oder setzt, ob der GPS-Längengrad östlich oder westlich ist. |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | Liest oder setzt, ob der GPS-Längengrad östlich oder westlich ist. |
| [getGPSMapDatum()](#getGPSMapDatum--) | Liest oder setzt die GPS-geodätischen Vermessungsdaten, die vom GPS-Empfänger verwendet werden. |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | Liest oder setzt die GPS-geodätischen Vermessungsdaten, die vom GPS-Empfänger verwendet werden. |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | Liest oder setzt den GPS-Messmodus. |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | Liest oder setzt den GPS-Messmodus. |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | Liest oder setzt die GPS-Zeichenkette, die den Namen der zur Positionsbestimmung verwendeten Methode aufzeichnet. |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | Liest oder setzt die GPS-Zeichenkette, die den Namen der zur Positionsbestimmung verwendeten Methode aufzeichnet. |
| [getGPSSatellites()](#getGPSSatellites--) | Liest oder setzt die GPS-Satelliten, die für Messungen verwendet werden. |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | Liest oder setzt die GPS-Satelliten, die für Messungen verwendet werden. |
| [getGPSSpeed()](#getGPSSpeed--) | Liest oder setzt die Geschwindigkeit der GPS-Empfängerbewegung. |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.imaging.fileformats.tiff.TiffRational-) | Liest oder setzt die Geschwindigkeit der GPS-Empfängerbewegung. |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | Liest oder setzt die Einheit, die zur Angabe der Geschwindigkeit der GPS-Empfängerbewegung verwendet wird. |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | Liest oder setzt die Einheit, die zur Angabe der Geschwindigkeit der GPS-Empfängerbewegung verwendet wird. |
| [getGPSStatus()](#getGPSStatus--) | Liest oder setzt den Status des GPS-Empfängers, wenn das Bild aufgenommen wird. |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | Liest oder setzt den Status des GPS-Empfängers, wenn das Bild aufgenommen wird. |
| [getGPSTimestamp()](#getGPSTimestamp--) | Liest oder setzt die GPS-Zeit als UTC (Koordinierte Weltzeit). |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.imaging.fileformats.tiff.TiffRational---) | Liest oder setzt die GPS-Zeit als UTC (Koordinierte Weltzeit). |
| [getGPSTrack()](#getGPSTrack--) | Liest oder setzt die Richtung der GPS‑Empfängerbewegung. |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | Liest oder setzt die Richtung der GPS‑Empfängerbewegung. |
| [getGPSTrackRef()](#getGPSTrackRef--) | Liest oder setzt die Referenz zur Angabe der Richtung der GPS‑Empfängerbewegung. |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | Liest oder setzt die Referenz zur Angabe der Richtung der GPS‑Empfängerbewegung. |
| [getGPSVersionID()](#getGPSVersionID--) | Liest oder setzt den GPS‑Versionsbezeichner. |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | Liest oder setzt den GPS‑Versionsbezeichner. |
| [getGainControl()](#getGainControl--) | Liest oder setzt den Grad der Gesamtabstimmung des Bildverstärkers. |
| [setGainControl(int value)](#setGainControl-int-) | Liest oder setzt den Grad der Gesamtabstimmung des Bildverstärkers. |
| [getGamma()](#getGamma--) | Liest oder setzt das Gamma. |
| [setGamma(TiffRational value)](#setGamma-com.aspose.imaging.fileformats.tiff.TiffRational-) | Liest oder setzt das Gamma. |
| [getISOSpeed()](#getISOSpeed--) | Liest oder setzt die ISO‑Geschwindigkeit |
| [setISOSpeed(long value)](#setISOSpeed-long-) | Liest oder setzt die ISO‑Geschwindigkeit |
| [getISOSpeedValue()](#getISOSpeedValue--) | Liest den ISO‑Geschwindigkeitswert. |
| [setISOSpeedValue(long value)](#setISOSpeedValue-long-) | Setzt den ISO‑Geschwindigkeitswert. |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | Liest oder setzt den ISO speed latitude yyy Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist. |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | Liest oder setzt den ISO speed latitude yyy Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist. |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | Liest oder setzt den ISO speed latitude zzz Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist. |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | Liest oder setzt den ISO speed latitude zzz Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist. |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | Liest oder setzt die fotografische Empfindlichkeit. |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | Liest oder setzt die fotografische Empfindlichkeit. |
| [getImageUniqueID()](#getImageUniqueID--) | Liest oder setzt die eindeutige Bildkennung. |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | Liest oder setzt die eindeutige Bildkennung. |
| [getLensMake()](#getLensMake--) | Liest oder setzt den Hersteller des Objektivs. |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | Liest oder setzt den Hersteller des Objektivs. |
| [getLensModel()](#getLensModel--) | Liest oder setzt das Objektivmodell. |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | Liest oder setzt das Objektivmodell. |
| [getLensSerialNumber()](#getLensSerialNumber--) | Liest oder setzt die Seriennummer des Objektivs. |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | Liest oder setzt die Seriennummer des Objektivs. |
| [getLensSpecification()](#getLensSpecification--) | Liest oder setzt die Objektivspezifikation |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.imaging.fileformats.tiff.TiffRational---) | Liest oder setzt die Objektivspezifikation |
| [getLightSource()](#getLightSource--) | Liest oder setzt die Lichtquelle. |
| [setLightSource(int value)](#setLightSource-int-) | Liest oder setzt die Lichtquelle. |
| [getMakerNoteData()](#getMakerNoteData--) | Liest die Hersteller‑Notizdaten. |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | Liest oder setzt die rohen Hersteller‑Notizdaten. |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | Liest oder setzt die rohen Hersteller‑Notizdaten. |
| [getMakerNotes()](#getMakerNotes--) | Liest die Hersteller‑Notizen. |
| [getMaxApertureValue()](#getMaxApertureValue--) | Liest oder setzt den maximalen Blendenwert. |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-) | Liest oder setzt den maximalen Blendenwert. |
| [getMeteringMode()](#getMeteringMode--) | Liest oder setzt den Messmodus. |
| [setMeteringMode(int value)](#setMeteringMode-int-) | Liest oder setzt den Messmodus. |
| [getOECF()](#getOECF--) | Liest oder setzt die Opto‑Elektrische Umwandlungsfunktion (OECF), die in ISO 14524 spezifiziert ist. |
| [setOECF(byte[] value)](#setOECF-byte---) | Liest oder setzt die Opto‑Elektrische Umwandlungsfunktion (OECF), die in ISO 14524 spezifiziert ist. |
| [getOrientation()](#getOrientation--) | Liest die Orientierung [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation). |
| [setOrientation(int value)](#setOrientation-int-) | Setzt die Orientierung [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation). |
| [getPixelXDimension()](#getPixelXDimension--) | Liest oder setzt die Pixel‑x‑Dimension. |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | Liest oder setzt die Pixel‑x‑Dimension. |
| [getPixelYDimension()](#getPixelYDimension--) | Liest oder setzt die Pixel‑y‑Dimension. |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | Liest oder setzt die Pixel‑y‑Dimension. |
| [getProperties()](#getProperties--) | Liest oder setzt alle EXIF‑Tags (einschließlich gängiger und GPS‑Tags). |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Liest oder setzt alle EXIF‑Tags (einschließlich gängiger und GPS‑Tags). |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | Liest oder setzt den empfohlenen Belichtungsindex. |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | Liest oder setzt den empfohlenen Belichtungsindex. |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | Liest oder setzt die zugehörige Audiodatei. |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | Liest oder setzt die zugehörige Audiodatei. |
| [getSaturation()](#getSaturation--) | Liest oder setzt die Sättigung. |
| [setSaturation(int value)](#setSaturation-int-) | Liest oder setzt die Sättigung. |
| [getSceneCaptureType()](#getSceneCaptureType--) | Liest oder setzt den Aufnahmetyp der Szene. |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | Liest oder setzt den Aufnahmetyp der Szene. |
| [getSceneType()](#getSceneType--) | Liest oder setzt den Szenentyp. |
| [setSceneType(byte value)](#setSceneType-byte-) | Liest oder setzt den Szenentyp. |
| [getSensingMethod()](#getSensingMethod--) | Liest oder setzt die Erfassungsmethode. |
| [setSensingMethod(int value)](#setSensingMethod-int-) | Liest oder setzt die Erfassungsmethode. |
| [getSensitivityType()](#getSensitivityType--) | Liest oder setzt den Empfindlichkeitstyp. |
| [setSensitivityType(int value)](#setSensitivityType-int-) | Liest oder setzt den Empfindlichkeitstyp. |
| [getSharpness()](#getSharpness--) | Liest oder setzt die Schärfe. |
| [setSharpness(int value)](#setSharpness-int-) | Liest oder setzt die Schärfe. |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | Liest oder setzt den Wert der Verschlusszeit. |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Liest oder setzt den Wert der Verschlusszeit. |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | Liest oder setzt die räumliche Frequenzantwort. |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | Liest oder setzt die räumliche Frequenzantwort. |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | Liest oder setzt die spektrale Empfindlichkeit. |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | Liest oder setzt die spektrale Empfindlichkeit. |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | Liest die Standardausgabesensitivität |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | Setzt die Standardausgabesensitivität |
| [getSubjectArea()](#getSubjectArea--) | Liest oder setzt den Motivbereich. |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | Liest oder setzt den Motivbereich. |
| [getSubjectDistance()](#getSubjectDistance--) | Liest oder setzt die Motivdistanz. |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.imaging.fileformats.tiff.TiffRational-) | Liest oder setzt die Motivdistanz. |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | Liest oder setzt den Abstandbereich des Motivs. |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | Liest oder setzt den Abstandbereich des Motivs. |
| [getSubjectLocation()](#getSubjectLocation--) | Liest oder setzt die Motivposition. |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | Liest oder setzt die Motivposition. |
| [getSubsecTime()](#getSubsecTime--) | Liest oder setzt die Sekundenbruchteile für das DateTime‑Tag. |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | Liest oder setzt die Sekundenbruchteile für das DateTime‑Tag. |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | Liest oder setzt die Sekundenbruchteile für das DateTimeDigitized‑Tag. |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | Liest oder setzt die Sekundenbruchteile für das DateTimeDigitized‑Tag. |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | Liest oder setzt die Sekundenbruchteile für das DateTimeOriginal‑Tag. |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | Liest oder setzt die Sekundenbruchteile für das DateTimeOriginal‑Tag. |
| [getUserComment()](#getUserComment--) | Liest oder setzt den Benutzerkommentar. |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | Liest oder setzt den Benutzerkommentar. |
| [getWhiteBalance()](#getWhiteBalance--) | Liest oder setzt den Weißabgleich. |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | Liest oder setzt den Weißabgleich. |
| [getWhitePoint()](#getWhitePoint--) | Liest oder setzt die Chromatizität des Weißpunkts des Bildes. |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.imaging.fileformats.tiff.TiffRational---) | Liest oder setzt die Chromatizität des Weißpunkts des Bildes. |
| [getCommonTags()](#getCommonTags--) | Liest oder setzt Tags, die zum gemeinsamen Abschnitt gehören. |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Liest oder setzt Tags, die zum gemeinsamen Abschnitt gehören. |
| [getExifTags()](#getExifTags--) | Liest oder setzt Tags, die ausschließlich zum EXIF-Abschnitt gehören. |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Liest oder setzt Tags, die ausschließlich zum EXIF-Abschnitt gehören. |
| [getGPSTags()](#getGPSTags--) | Liest oder setzt Tags, die ausschließlich zum GPS-Abschnitt gehören. |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Liest oder setzt Tags, die ausschließlich zum GPS-Abschnitt gehören. |
| [getThumbnail()](#getThumbnail--) | Liest das Vorschaubild. |
| [setThumbnail(RasterImage value)](#setThumbnail-com.aspose.imaging.RasterImage-) | Setzt das Vorschaubild. |
| [getXResolutionInt()](#getXResolutionInt--) | Liest die X-Auflösung. |
| [setXResolution(int value)](#setXResolution-int-) | Setzt die X-Auflösung. |
| [getYResolutionInt()](#getYResolutionInt--) | Liest die Y-Auflösung. |
| [setYResolution(int value)](#setYResolution-int-) | Setzt die Y-Auflösung. |
| [removeTag(int tagId)](#removeTag-int-) | Tag aus dem Container entfernen |
| [getTagValue(int key)](#getTagValue-int-) | Liest den Tag-Wert. |

## Example: Access camera manufacturer maker notes in Jpeg image.

``` java
try (JpegImage image = (JpegImage)Image.load("Sample.jpg"))
{
    for (MakerNote makerNote : image.getExifData().getMakerNotes())
    {
        System.out.format("Name = %s, Value = %s", makerNote.getName(), makerNote.getValue());
    }
}
```

### ExifData() {#ExifData--}
```
public ExifData()
```


Initialisiert eine neue Instanz der `ExifData`-Klasse.

### ExifData(TiffDataType[] exifdata) {#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] exifdata)
```


Initialisiert eine neue Instanz der `ExifData`-Klasse mit Daten aus einem Array.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Array von EXIF-Tags zusammen mit gemeinsamen und GPS-Tags. |

### ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Initialisiert eine neue Instanz der `ExifData`-Klasse mit Daten aus einem Array.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Die gemeinsamen Tags. |
| exifTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Die EXIF-Tags. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Die GPS-Tags. |

### ExifData(ExifData exifdata) {#ExifData-com.aspose.imaging.exif.ExifData-}
```
public ExifData(ExifData exifdata)
```


Initialisiert eine neue Instanz der [ExifData](../../com.aspose.imaging.exif/exifdata)-Klasse mit Daten aus einem Array.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| exifdata | [ExifData](../../com.aspose.imaging.exif/exifdata) | Array von EXIF-Tags zusammen mit gemeinsamen und GPS-Tags. |

### ExifData(byte[] binaryData) {#ExifData-byte---}
```
public ExifData(byte[] binaryData)
```


Initialisiert eine neue Instanz der [ExifData](../../com.aspose.imaging.exif/exifdata)-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| binaryData | byte[] | Die Binärdaten. |

### isBigEndian() {#isBigEndian--}
```
public boolean isBigEndian()
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob die aus dem Stream erstellten EXIF-Daten im Big-Endian-Format vorliegen.

Wert: `true`, wenn die aus dem Stream erstellten EXIF-Daten big endian sind; andernfalls `false`.

**Returns:**
boolean
### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob die aus dem Stream erstellten EXIF-Daten im Big-Endian-Format vorliegen.

Wert: `true`, wenn die aus dem Stream erstellten EXIF-Daten big endian sind; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getMake() {#getMake--}
```
public final String getMake()
```


Ruft den Hersteller der Aufnahmeeinrichtung ab.

Wert: Der Hersteller des Aufzeichnungsgeräts.

**Returns:**
java.lang.String - der Hersteller des Aufzeichnungsgeräts.
### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


Legt den Hersteller der Aufnahmeeinrichtung fest.

Wert: Der Hersteller des Aufzeichnungsgeräts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | der Hersteller des Aufzeichnungsgeräts. |

### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


Ruft den Blendenwert ab oder legt ihn fest.

Wert: Der Blendenwert.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


Ruft den Blendenwert ab oder legt ihn fest.

Wert: Der Blendenwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


Ruft die Seriennummer des Kameragehäuses ab oder legt sie fest.

Wert: Die Seriennummer des Gehäuses.

**Returns:**
java.lang.String
### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


Ruft die Seriennummer des Kameragehäuses ab oder legt sie fest.

Wert: Die Seriennummer des Gehäuses.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


Ruft den Helligkeitswert ab oder legt ihn fest.

Wert: Der Helligkeitswert.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


Ruft den Helligkeitswert ab oder legt ihn fest.

Wert: Der Helligkeitswert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


Ruft das CFA-Muster ab oder legt es fest.

Wert: Das CFA-Muster.

**Returns:**
byte[]
### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


Ruft das CFA-Muster ab oder legt es fest.

Wert: Das CFA-Muster.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


Ruft den Namen des Kamerabesitzers ab oder legt ihn fest

Wert: Der Name des Kamerabesitzers.

**Returns:**
java.lang.String
### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


Ruft den Namen des Kamerabesitzers ab oder legt ihn fest

Wert: Der Name des Kamerabesitzers.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getColorSpace() {#getColorSpace--}
```
public int getColorSpace()
```


Ruft den Farbraum ab oder legt ihn fest.

Wert: Der Farbraum.

**Returns:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


Ruft den Farbraum ab oder legt ihn fest.

Wert: Der Farbraum.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


Ruft die Komponenten-Konfiguration ab oder legt sie fest.

Wert: Die Komponenten‑Konfiguration.

**Returns:**
byte[]
### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


Ruft die Komponenten-Konfiguration ab oder legt sie fest.

Wert: Die Komponenten‑Konfiguration.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


Ruft die komprimierten Bits pro Pixel ab oder legt sie fest.

Wert: Die komprimierten Bits pro Pixel.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


Ruft die komprimierten Bits pro Pixel ab oder legt sie fest.

Wert: Die komprimierten Bits pro Pixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getContrast() {#getContrast--}
```
public int getContrast()
```


Liest oder setzt den Kontrast.

Wert: Der Kontrast.

**Returns:**
int
### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


Liest oder setzt den Kontrast.

Wert: Der Kontrast.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


Liest oder setzt das benutzerdefinierte Rendering.

Wert: Die benutzerdefinierte Darstellung.

**Returns:**
int
### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


Liest oder setzt das benutzerdefinierte Rendering.

Wert: Die benutzerdefinierte Darstellung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


Liest oder setzt das digitalisierte Datum und die Uhrzeit.

Wert: Das Datum und die Uhrzeit der Digitalisierung.

**Returns:**
java.lang.String
### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


Liest oder setzt das digitalisierte Datum und die Uhrzeit.

Wert: Das Datum und die Uhrzeit der Digitalisierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


Liest oder setzt das ursprüngliche Datum und die Uhrzeit.

Wert: Das ursprüngliche Datum und die Uhrzeit.

**Returns:**
java.lang.String
### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


Liest oder setzt das ursprüngliche Datum und die Uhrzeit.

Wert: Das ursprüngliche Datum und die Uhrzeit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


Liest oder setzt die Geräte‑Einstellungsbeschreibung.

Wert: Die Geräte‑Einstellungsbeschreibung.

**Returns:**
byte[]
### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


Liest oder setzt die Geräte‑Einstellungsbeschreibung.

Wert: Die Geräte‑Einstellungsbeschreibung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


Liest oder setzt das digitale Zoomverhältnis.

Wert: Das digitale Zoom‑Verhältnis.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


Liest oder setzt das digitale Zoomverhältnis.

Wert: Das digitale Zoom‑Verhältnis.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


Liest oder setzt die EXIF-Version.

Wert: Die EXIF-Version.

**Returns:**
byte[]
### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


Liest oder setzt die EXIF-Version.

Wert: Die EXIF-Version.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


Liest oder setzt den Belichtungswert.

Wert: Der Belichtungswert.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


Liest oder setzt den Belichtungswert.

Wert: Der Belichtungswert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


Liest oder setzt den Belichtungsindex.

Wert: Der Belichtungsindex.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


Liest oder setzt den Belichtungsindex.

Wert: Der Belichtungsindex.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


Liest oder setzt den Belichtungsmodus.

Wert: Der Belichtungsmodus.

**Returns:**
int
### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


Liest oder setzt den Belichtungsmodus.

Wert: Der Belichtungsmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


Liest oder setzt das Belichtungsprogramm.

Wert: Das Belichtungsprogramm.

**Returns:**
int
### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


Liest oder setzt das Belichtungsprogramm.

Wert: Das Belichtungsprogramm.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


Liest oder setzt die Belichtungszeit.

Wert: Die Belichtungszeit.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


Liest oder setzt die Belichtungszeit.

Wert: Die Belichtungszeit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


Liest oder setzt die Blendenzahl.

Wert: Die Blendenzahl.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFNumber(TiffRational value) {#setFNumber-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


Liest oder setzt die Blendenzahl.

Wert: Die Blendenzahl.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


Liest oder setzt den Dateiquellen‑Typ.

Wert: Der Dateiquellen‑Typ.

**Returns:**
byte
### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


Liest oder setzt den Dateiquellen‑Typ.

Wert: Der Dateiquellen‑Typ.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getFlash() {#getFlash--}
```
public int getFlash()
```


Liest oder setzt den Blitz.

Wert: Der Blitz.

**Returns:**
int
### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


Liest oder setzt den Blitz.

Wert: Der Blitz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


Liest oder setzt die Blitzenergie.

Wert: Die Blitzenergie.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


Liest oder setzt die Blitzenergie.

Wert: Die Blitzenergie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


Liest oder setzt die Blitz‑Pix‑Version.

Wert: Die Blitz‑Pix‑Version.

**Returns:**
byte[]
### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


Liest oder setzt die Blitz‑Pix‑Version.

Wert: Die Blitz‑Pix‑Version.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


Liest oder setzt die Brennweite.

Wert: Die Brennweite.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


Liest oder setzt die Brennweite.

Wert: Die Brennweite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


Liest oder setzt die Brennweite in 35 mm-Film.

Wert: Die Brennweite in 35‑mm-Film.

**Returns:**
int
### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


Liest oder setzt die Brennweite in 35 mm-Film.

Wert: Die Brennweite in 35‑mm-Film.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


Liest oder setzt die Auflösungseinheit der Bildebene.

Wert: Die Auflösungseinheit der Bildebene.

**Returns:**
int
### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


Liest oder setzt die Auflösungseinheit der Bildebene.

Wert: Die Auflösungseinheit der Bildebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


Liest oder setzt die X‑Auflösung der Bildebene.

Wert: Die Auflösung der Brennebene x.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


Liest oder setzt die X‑Auflösung der Bildebene.

Wert: Die Auflösung der Brennebene x.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


Liest oder setzt die Y‑Auflösung der Bildebene.

Wert: Die Auflösung der Brennebene y.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


Liest oder setzt die Y‑Auflösung der Bildebene.

Wert: Die Auflösung der Brennebene y.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


Liest oder setzt die GPS-Höhe.

Wert: Die GPS-Höhe.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


Liest oder setzt die GPS-Höhe.

Wert: Die GPS-Höhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


Liest oder setzt die GPS-Höhe, die als Referenzhöhe verwendet wird.

Wert: Die GPS-Höhe, die als Referenzhöhe verwendet wird.

**Returns:**
byte
### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


Liest oder setzt die GPS-Höhe, die als Referenzhöhe verwendet wird.

Wert: Die GPS-Höhe, die als Referenzhöhe verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


Liest oder setzt die GPS-Bereichsinformation.

Wert: Die GPS-Flächeninformation.

**Returns:**
byte[]
### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


Liest oder setzt die GPS-Bereichsinformation.

Wert: Die GPS-Flächeninformation.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


Liest oder setzt den GPS DOP (Datengrad der Genauigkeit).

Wert: Der GPS-DOP (Datengrad der Präzision).

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


Liest oder setzt den GPS DOP (Datengrad der Genauigkeit).

Wert: Der GPS-DOP (Datengrad der Präzision).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


Liest oder setzt die GPS-Richtung zum Zielpunkt.

Wert: Der GPS-Kurs zum Zielpunkt.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


Liest oder setzt die GPS-Richtung zum Zielpunkt.

Wert: Der GPS-Kurs zum Zielpunkt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


Liest oder setzt die GPS-Referenz, die zur Angabe der Richtung zum Zielpunkt verwendet wird.

Wert: Die GPS-Referenz, die zur Angabe des Kurses zum Zielpunkt verwendet wird.

**Returns:**
java.lang.String
### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


Liest oder setzt die GPS-Referenz, die zur Angabe der Richtung zum Zielpunkt verwendet wird.

Wert: Die GPS-Referenz, die zur Angabe des Kurses zum Zielpunkt verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


Liest oder setzt die GPS-Entfernung zum Zielpunkt.

Wert: Die GPS-Entfernung zum Zielpunkt.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


Liest oder setzt die GPS-Entfernung zum Zielpunkt.

Wert: Die GPS-Entfernung zum Zielpunkt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


Liest oder setzt die GPS-Einheit, die zur Angabe der Entfernung zum Zielpunkt verwendet wird.

Wert: Die GPS-Einheit, die zur Angabe der Entfernung zum Zielpunkt verwendet wird.

**Returns:**
java.lang.String
### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


Liest oder setzt die GPS-Einheit, die zur Angabe der Entfernung zum Zielpunkt verwendet wird.

Wert: Die GPS-Einheit, die zur Angabe der Entfernung zum Zielpunkt verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


Liest oder setzt den GPS-Breitengrad des Zielpunkts.

Wert: Der GPS-Breitengrad des Zielpunkts.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


Liest oder setzt den GPS-Breitengrad des Zielpunkts.

Wert: Der GPS-Breitengrad des Zielpunkts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


Liest oder setzt den GPS-Wert, der angibt, ob der Breitengrad des Zielpunkts nördlich oder südlich ist.

Wert: Der GPS-Wert, der angibt, ob der Breitengrad des Zielpunkts nördlich oder südlich ist.

**Returns:**
java.lang.String
### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


Liest oder setzt den GPS-Wert, der angibt, ob der Breitengrad des Zielpunkts nördlich oder südlich ist.

Wert: Der GPS-Wert, der angibt, ob der Breitengrad des Zielpunkts nördlich oder südlich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


Liest oder setzt den GPS-Längengrad des Zielpunkts.

Wert: Der GPS-Längengrad des Zielpunkts.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


Liest oder setzt den GPS-Längengrad des Zielpunkts.

Wert: Der GPS-Längengrad des Zielpunkts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


Liest oder setzt den GPS-Wert, der angibt, ob der Längengrad des Zielpunkts östlich oder westlich ist.

Wert: Der GPS-Wert, der angibt, ob der Längengrad des Zielpunkts östlich oder westlich ist.

**Returns:**
java.lang.String
### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


Liest oder setzt den GPS-Wert, der angibt, ob der Längengrad des Zielpunkts östlich oder westlich ist.

Wert: Der GPS-Wert, der angibt, ob der Längengrad des Zielpunkts östlich oder westlich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


Liest oder setzt einen GPS-Wert, der angibt, ob eine differentielle Korrektur auf den GPS-Empfänger angewendet wird.

Wert: Der GPS-Wert, der angibt, ob eine differentielle Korrektur auf den GPS-Empfänger angewendet wird.

**Returns:**
int
### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


Liest oder setzt einen GPS-Wert, der angibt, ob eine differentielle Korrektur auf den GPS-Empfänger angewendet wird.

Wert: Der GPS-Wert, der angibt, ob eine differentielle Korrektur auf den GPS-Empfänger angewendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


Liest oder setzt die GPS-Richtung des Bildes zum Zeitpunkt der Aufnahme.

Wert: Die GPS-Richtung des Bildes bei der Aufnahme.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


Liest oder setzt die GPS-Richtung des Bildes zum Zeitpunkt der Aufnahme.

Wert: Die GPS-Richtung des Bildes bei der Aufnahme.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


Liest oder setzt die GPS-Referenz zur Angabe der Bildrichtung bei der Aufnahme.

Wert: Die GPS-Referenz zur Angabe der Bildrichtung bei der Aufnahme.

**Returns:**
java.lang.String
### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


Liest oder setzt die GPS-Referenz zur Angabe der Bildrichtung bei der Aufnahme.

Wert: Die GPS-Referenz zur Angabe der Bildrichtung bei der Aufnahme.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


Liest oder setzt die GPS-Zeichenkette, die Datum- und Zeitinformationen relativ zu UTC (Koordinierte Weltzeit) aufzeichnet.

Wert: Die GPS-Zeichenkette, die Datum- und Zeitinformationen relativ zu UTC (Koordinierte Weltzeit) aufzeichnet.

**Returns:**
java.lang.String
### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


Liest oder setzt die GPS-Zeichenkette, die Datum- und Zeitinformationen relativ zu UTC (Koordinierte Weltzeit) aufzeichnet.

Wert: Die GPS-Zeichenkette, die Datum- und Zeitinformationen relativ zu UTC (Koordinierte Weltzeit) aufzeichnet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


Liest oder setzt den GPS-Breitengrad.

Wert: Der GPS-Breitengrad.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


Liest oder setzt den GPS-Breitengrad.

Wert: Der GPS-Breitengrad.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


Liest oder setzt, ob der GPS-Breitengrad nördlich oder südlich ist.

Wert: Der GPS-Breitengrad ist nördlich oder südlich.

**Returns:**
java.lang.String
### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


Liest oder setzt, ob der GPS-Breitengrad nördlich oder südlich ist.

Wert: Der GPS-Breitengrad ist nördlich oder südlich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


Liest oder setzt den GPS-Längengrad.

Wert: Der GPS-Längengrad.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


Liest oder setzt den GPS-Längengrad.

Wert: Der GPS-Längengrad.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


Liest oder setzt, ob der GPS-Längengrad östlich oder westlich ist.

Wert: Der GPS-Längengrad ist östlich oder westlich.

**Returns:**
java.lang.String
### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


Liest oder setzt, ob der GPS-Längengrad östlich oder westlich ist.

Wert: Der GPS-Längengrad ist östlich oder westlich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


Liest oder setzt die GPS-geodätischen Vermessungsdaten, die vom GPS-Empfänger verwendet werden.

Wert: Die GPS-geodätischen Vermessungsdaten, die vom GPS-Empfänger verwendet werden.

**Returns:**
java.lang.String
### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


Liest oder setzt die GPS-geodätischen Vermessungsdaten, die vom GPS-Empfänger verwendet werden.

Wert: Die GPS-geodätischen Vermessungsdaten, die vom GPS-Empfänger verwendet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


Liest oder setzt den GPS-Messmodus.

Wert: Der GPS-Messmodus.

**Returns:**
java.lang.String
### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


Liest oder setzt den GPS-Messmodus.

Wert: Der GPS-Messmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


Liest oder setzt die GPS-Zeichenkette, die den Namen der zur Positionsbestimmung verwendeten Methode aufzeichnet.

Wert: Die GPS-Zeichenkette, die den Namen der zur Positionsbestimmung verwendeten Methode aufzeichnet.

**Returns:**
byte[]
### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


Liest oder setzt die GPS-Zeichenkette, die den Namen der zur Positionsbestimmung verwendeten Methode aufzeichnet.

Wert: Die GPS-Zeichenkette, die den Namen der zur Positionsbestimmung verwendeten Methode aufzeichnet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


Liest oder setzt die GPS-Satelliten, die für Messungen verwendet werden.

Wert: Die GPS‑Satelliten, die für Messungen verwendet werden.

**Returns:**
java.lang.String
### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


Liest oder setzt die GPS-Satelliten, die für Messungen verwendet werden.

Wert: Die GPS‑Satelliten, die für Messungen verwendet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


Liest oder setzt die Geschwindigkeit der GPS-Empfängerbewegung.

Wert: Die Geschwindigkeit der GPS‑Empfängerbewegung.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


Liest oder setzt die Geschwindigkeit der GPS-Empfängerbewegung.

Wert: Die Geschwindigkeit der GPS‑Empfängerbewegung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


Liest oder setzt die Einheit, die zur Angabe der Geschwindigkeit der GPS-Empfängerbewegung verwendet wird.

Wert: Die Einheit, die verwendet wird, um die Geschwindigkeit der GPS‑Empfängerbewegung auszudrücken.

**Returns:**
java.lang.String
### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


Liest oder setzt die Einheit, die zur Angabe der Geschwindigkeit der GPS-Empfängerbewegung verwendet wird.

Wert: Die Einheit, die verwendet wird, um die Geschwindigkeit der GPS‑Empfängerbewegung auszudrücken.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


Liest oder setzt den Status des GPS-Empfängers, wenn das Bild aufgenommen wird.

Wert: Der Status des GPS‑Empfängers, wenn das Bild aufgenommen wird.

**Returns:**
java.lang.String
### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


Liest oder setzt den Status des GPS-Empfängers, wenn das Bild aufgenommen wird.

Wert: Der Status des GPS‑Empfängers, wenn das Bild aufgenommen wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


Liest oder setzt die GPS-Zeit als UTC (Koordinierte Weltzeit).

Wert: Die GPS‑Zeit als UTC (Koordinierte Weltzeit).

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


Liest oder setzt die GPS-Zeit als UTC (Koordinierte Weltzeit).

Wert: Die GPS‑Zeit als UTC (Koordinierte Weltzeit).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


Liest oder setzt die Richtung der GPS‑Empfängerbewegung.

Wert: Die Richtung der GPS‑Empfängerbewegung.

**Returns:**
java.lang.String
### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


Liest oder setzt die Richtung der GPS‑Empfängerbewegung.

Wert: Die Richtung der GPS‑Empfängerbewegung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


Liest oder setzt die Referenz zur Angabe der Richtung der GPS‑Empfängerbewegung.

Wert: Die Referenz zur Angabe der Richtung der GPS‑Empfängerbewegung.

**Returns:**
java.lang.String
### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


Liest oder setzt die Referenz zur Angabe der Richtung der GPS‑Empfängerbewegung.

Wert: Die Referenz zur Angabe der Richtung der GPS‑Empfängerbewegung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


Liest oder setzt den GPS‑Versionsbezeichner.

Wert: Der GPS‑Versionsbezeichner.

**Returns:**
byte[]
### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


Liest oder setzt den GPS‑Versionsbezeichner.

Wert: Der GPS‑Versionsbezeichner.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


Liest oder setzt den Grad der Gesamtabstimmung des Bildverstärkers.

Wert: Der Grad der Gesamtverstärkung des Bildes.

**Returns:**
int
### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


Liest oder setzt den Grad der Gesamtabstimmung des Bildverstärkers.

Wert: Der Grad der Gesamtverstärkung des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


Liest oder setzt das Gamma.

Wert: Der Gamma‑Wert.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGamma(TiffRational value) {#setGamma-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


Liest oder setzt das Gamma.

Wert: Der Gamma‑Wert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


Liest oder setzt die ISO‑Geschwindigkeit

Wert: Die ISO‑Geschwindigkeit.

**Returns:**
long
### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


Liest oder setzt die ISO‑Geschwindigkeit

Wert: Die ISO‑Geschwindigkeit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### getISOSpeedValue() {#getISOSpeedValue--}
```
public final long getISOSpeedValue()
```


Liest den ISO‑Geschwindigkeitswert.

Wert: Der ISO‑Geschwindigkeitswert.

**Returns:**
long - der ISO‑Geschwindigkeitswert.
### setISOSpeedValue(long value) {#setISOSpeedValue-long-}
```
public final void setISOSpeedValue(long value)
```


Setzt den ISO‑Geschwindigkeitswert.

Wert: Der ISO‑Geschwindigkeitswert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | der ISO‑Geschwindigkeitswert. |

### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


Liest oder setzt den ISO speed latitude yyy Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist.

Wert: Der ISO speed latitude yyy-Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist.

Dieses Tag darf nicht ohne ISOSpeed und ISOSpeedLatitudeZZZ aufgezeichnet werden.

**Returns:**
long
### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


Liest oder setzt den ISO speed latitude yyy Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist.

Wert: Der ISO speed latitude yyy-Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist.

Dieses Tag darf nicht ohne ISOSpeed und ISOSpeedLatitudeZZZ aufgezeichnet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


Liest oder setzt den ISO speed latitude zzz Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist.

Wert: Der ISO speed latitude zzz-Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist.

Dieses Tag darf nicht ohne ISOSpeed und ISOSpeedLatitudeYYY aufgezeichnet werden.

**Returns:**
long
### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


Liest oder setzt den ISO speed latitude zzz Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist.

Wert: Der ISO speed latitude zzz-Wert einer Kamera oder eines Eingabegeräts, der in ISO 12232 definiert ist.

Dieses Tag darf nicht ohne ISOSpeed und ISOSpeedLatitudeYYY aufgezeichnet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


Liest oder setzt die fotografische Empfindlichkeit.

Wert: Die fotografische Empfindlichkeit.

**Returns:**
long
### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


Liest oder setzt die fotografische Empfindlichkeit.

Wert: Die fotografische Empfindlichkeit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


Liest oder setzt die eindeutige Bildkennung.

Wert: Der eindeutige Bildbezeichner.

**Returns:**
java.lang.String
### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


Liest oder setzt die eindeutige Bildkennung.

Wert: Der eindeutige Bildbezeichner.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


Liest oder setzt den Hersteller des Objektivs.

Wert: Der Linsenhersteller.

**Returns:**
java.lang.String
### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


Liest oder setzt den Hersteller des Objektivs.

Wert: Der Linsenhersteller.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


Liest oder setzt das Objektivmodell.

Wert: Das Linsenmodell.

**Returns:**
java.lang.String
### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


Liest oder setzt das Objektivmodell.

Wert: Das Linsenmodell.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


Liest oder setzt die Seriennummer des Objektivs.

Wert: Die Seriennummer des lens.

**Returns:**
java.lang.String
### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


Liest oder setzt die Seriennummer des Objektivs.

Wert: Die Seriennummer des lens.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


Liest oder setzt die Objektivspezifikation

Wert: Die Linsenspezifikation.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


Liest oder setzt die Objektivspezifikation

Wert: Die Linsenspezifikation.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


Liest oder setzt die Lichtquelle.

Wert: Die Lichtquelle.

**Returns:**
int
### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


Liest oder setzt die Lichtquelle.

Wert: Die Lichtquelle.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


Liest die Hersteller‑Notizdaten.

Wert: Die Maker-Notizdaten.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


Liest oder setzt die rohen Hersteller‑Notizdaten.

Wert: Die rohen Maker-Notizdaten.

**Returns:**
byte[]
### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


Liest oder setzt die rohen Hersteller‑Notizdaten.

Wert: Die rohen Maker-Notizdaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


Liest die Hersteller‑Notizen.

Wert: Die Maker-Notizen.

**Returns:**
com.aspose.imaging.exif.MakerNote[] - die Maker-Notizen.

**Example: Access camera manufacturer maker notes in Jpeg image.**

``` java
try (JpegImage image = (JpegImage)Image.load("Sample.jpg"))
{
    for (MakerNote makerNote : image.getExifData().getMakerNotes())
    {
        System.out.format("Name = %s, Value = %s", makerNote.getName(), makerNote.getValue());
    }
}
```

### getMaxApertureValue() {#getMaxApertureValue--}
```
public TiffRational getMaxApertureValue()
```


Liest oder setzt den maximalen Blendenwert.

Wert: Der maximale Blendenwert.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


Liest oder setzt den maximalen Blendenwert.

Wert: Der maximale Blendenwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


Liest oder setzt den Messmodus.

Wert: Der Messmodus.

**Returns:**
int
### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


Liest oder setzt den Messmodus.

Wert: Der Messmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


Liest oder setzt die Opto‑Elektrische Umwandlungsfunktion (OECF), die in ISO 14524 spezifiziert ist.

Wert: Die Opto-Elektrische Umwandlungsfunktion (OECF) gemäß ISO 14524.

**Returns:**
byte[]
### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


Liest oder setzt die Opto‑Elektrische Umwandlungsfunktion (OECF), die in ISO 14524 spezifiziert ist.

Wert: Die Opto-Elektrische Umwandlungsfunktion (OECF) gemäß ISO 14524.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Liest die Orientierung [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation).

Wert: Die Ausrichtung.

**Returns:**
int - die Ausrichtung.
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Setzt die Orientierung [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation).

Wert: Die Ausrichtung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die Ausrichtung. |

### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


Liest oder setzt die Pixel‑x‑Dimension.

Wert: Die Pixel-x-Dimension.

**Returns:**
long
### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


Liest oder setzt die Pixel‑x‑Dimension.

Wert: Die Pixel-x-Dimension.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


Liest oder setzt die Pixel‑y‑Dimension.

Wert: Die Pixel-y-Dimension.

**Returns:**
long
### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


Liest oder setzt die Pixel‑y‑Dimension.

Wert: Die Pixel-y-Dimension.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


Liest oder setzt alle EXIF‑Tags (einschließlich gängiger und GPS‑Tags).

Wert: Die EXIF-Tags (einschließlich gängiger und GPS-Tags).

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setProperties(TiffDataType[] value) {#setProperties-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


Liest oder setzt alle EXIF‑Tags (einschließlich gängiger und GPS‑Tags).

Wert: Die EXIF-Tags (einschließlich gängiger und GPS-Tags).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


Liest oder setzt den empfohlenen Belichtungsindex.

Wert: Der empfohlene Belichtungsindex.

**Returns:**
long
### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


Liest oder setzt den empfohlenen Belichtungsindex.

Wert: Der empfohlene Belichtungsindex.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


Liest oder setzt die zugehörige Audiodatei.

Wert: Die zugehörige Audiodatei.

**Returns:**
java.lang.String
### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


Liest oder setzt die zugehörige Audiodatei.

Wert: Die zugehörige Audiodatei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


Liest oder setzt die Sättigung.

Wert: Die Sättigung.

**Returns:**
int
### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


Liest oder setzt die Sättigung.

Wert: Die Sättigung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


Liest oder setzt den Aufnahmetyp der Szene.

Wert: Der Typ der Szenenerfassung.

**Returns:**
int
### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


Liest oder setzt den Aufnahmetyp der Szene.

Wert: Der Typ der Szenenerfassung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


Liest oder setzt den Szenentyp.

Wert: Der Typ der Szene.

**Returns:**
byte
### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


Liest oder setzt den Szenentyp.

Wert: Der Typ der Szene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


Liest oder setzt die Erfassungsmethode.

Wert: Die Erfassungsmethode.

**Returns:**
int
### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


Liest oder setzt die Erfassungsmethode.

Wert: Die Erfassungsmethode.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


Liest oder setzt den Empfindlichkeitstyp.

Wert: Der Typ der Empfindlichkeit.

**Returns:**
int
### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


Liest oder setzt den Empfindlichkeitstyp.

Wert: Der Typ der Empfindlichkeit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


Liest oder setzt die Schärfe.

Wert: Die Schärfe.

**Returns:**
int
### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


Liest oder setzt die Schärfe.

Wert: Die Schärfe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


Liest oder setzt den Wert der Verschlusszeit.

Wert: Der Verschlusszeitwert.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


Liest oder setzt den Wert der Verschlusszeit.

Wert: Der Verschlusszeitwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


Liest oder setzt die räumliche Frequenzantwort.

Wert: Die räumliche Frequenzantwort.

**Returns:**
byte[]
### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


Liest oder setzt die räumliche Frequenzantwort.

Wert: Die räumliche Frequenzantwort.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


Liest oder setzt die spektrale Empfindlichkeit.

Wert: Die spektrale Empfindlichkeit.

**Returns:**
java.lang.String
### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


Liest oder setzt die spektrale Empfindlichkeit.

Wert: Die spektrale Empfindlichkeit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


Liest die Standardausgabesensitivität

Wert: Die Standardausgabesensitivität.

**Returns:**
long
### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


Setzt die Standardausgabesensitivität

Wert: Die Standardausgabesensitivität.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


Liest oder setzt den Motivbereich.

Wert: Der Motivbereich.

**Returns:**
int[]
### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


Liest oder setzt den Motivbereich.

Wert: Der Motivbereich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


Liest oder setzt die Motivdistanz.

Wert: Die Motiventfernung.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


Liest oder setzt die Motivdistanz.

Wert: Die Motiventfernung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


Liest oder setzt den Abstandbereich des Motivs.

Wert: Der Motiventfernungsbereich.

**Returns:**
int
### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


Liest oder setzt den Abstandbereich des Motivs.

Wert: Der Motiventfernungsbereich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


Liest oder setzt die Motivposition.

Wert: Der Motivstandort.

**Returns:**
int[]
### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


Liest oder setzt die Motivposition.

Wert: Der Motivstandort.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


Liest oder setzt die Sekundenbruchteile für das DateTime‑Tag.

Wert: Die Sekundenbruchteile für das DateTime-Tag.

**Returns:**
java.lang.String
### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


Liest oder setzt die Sekundenbruchteile für das DateTime‑Tag.

Wert: Die Sekundenbruchteile für das DateTime-Tag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


Liest oder setzt die Sekundenbruchteile für das DateTimeDigitized‑Tag.

Wert: Die Sekundenbruchteile für das DateTimeDigitized-Tag.

**Returns:**
java.lang.String
### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


Liest oder setzt die Sekundenbruchteile für das DateTimeDigitized‑Tag.

Wert: Die Sekundenbruchteile für das DateTimeDigitized-Tag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


Liest oder setzt die Sekundenbruchteile für das DateTimeOriginal‑Tag.

Wert: Die Sekundenbruchteile für das DateTimeOriginal-Tag.

**Returns:**
java.lang.String
### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


Liest oder setzt die Sekundenbruchteile für das DateTimeOriginal‑Tag.

Wert: Die Sekundenbruchteile für das DateTimeOriginal-Tag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


Liest oder setzt den Benutzerkommentar.

Wert: Der Benutzerkommentar.

**Returns:**
java.lang.String
### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


Liest oder setzt den Benutzerkommentar.

Wert: Der Benutzerkommentar.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


Liest oder setzt den Weißabgleich.

Wert: Der Weißabgleich.

**Returns:**
int
### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


Liest oder setzt den Weißabgleich.

Wert: Der Weißabgleich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


Liest oder setzt die Chromatizität des Weißpunkts des Bildes.

Wert: Die Chromatik des Weißpunkts des Bildes.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


Liest oder setzt die Chromatizität des Weißpunkts des Bildes.

Wert: Die Chromatik des Weißpunkts des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


Liest oder setzt Tags, die zum gemeinsamen Abschnitt gehören. Dies gilt nur für JPEG-Bilder, im TIFF-Format werden stattdessen tiffOptions verwendet.

Wert: Die Tags des gemeinsamen Abschnitts.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


Liest oder setzt Tags, die zum gemeinsamen Abschnitt gehören. Dies gilt nur für JPEG-Bilder, im TIFF-Format werden stattdessen tiffOptions verwendet.

Wert: Die Tags des gemeinsamen Abschnitts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


Liest oder setzt Tags, die ausschließlich zum EXIF-Abschnitt gehören.

Wert: Die Tags des EXIF-Abschnitts.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


Liest oder setzt Tags, die ausschließlich zum EXIF-Abschnitt gehören.

Wert: Die Tags des EXIF-Abschnitts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


Liest oder setzt Tags, die ausschließlich zum GPS-Abschnitt gehören.

Wert: Die GPS-Tags.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


Liest oder setzt Tags, die ausschließlich zum GPS-Abschnitt gehören.

Wert: Die GPS-Tags.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getThumbnail() {#getThumbnail--}
```
public final RasterImage getThumbnail()
```


Liest das Vorschaubild.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the thumbnail image.
### setThumbnail(RasterImage value) {#setThumbnail-com.aspose.imaging.RasterImage-}
```
public final void setThumbnail(RasterImage value)
```


Setzt das Vorschaubild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RasterImage](../../com.aspose.imaging/rasterimage) | das Miniaturbild. |

### getXResolutionInt() {#getXResolutionInt--}
```
public final int getXResolutionInt()
```


Liest die X-Auflösung.

Wert: Die x-Auflösung.

**Returns:**
int - die x-Auflösung.
### setXResolution(int value) {#setXResolution-int-}
```
public final void setXResolution(int value)
```


Setzt die X-Auflösung.

Wert: Die x-Auflösung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die x-Auflösung. |

### getYResolutionInt() {#getYResolutionInt--}
```
public final int getYResolutionInt()
```


Liest die Y-Auflösung.

Wert: Die y-Auflösung.

**Returns:**
int - die y-Auflösung.
### setYResolution(int value) {#setYResolution-int-}
```
public final void setYResolution(int value)
```


Setzt die Y-Auflösung.

Wert: Die y-Auflösung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die y-Auflösung. |

### removeTag(int tagId) {#removeTag-int-}
```
public void removeTag(int tagId)
```


Tag aus dem Container entfernen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tagId | int | Der Tag-Identifikator zum Entfernen. |

### getTagValue(int key) {#getTagValue-int-}
```
public final TiffDataType getTagValue(int key)
```


Liest den Tag-Wert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | int | Der Tag-Schlüssel [ExifProperties](../../com.aspose.imaging.exif/exifproperties). |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - The TiffDataType
