---
title: "ExifData"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Contenitore di dati EXIF."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.exif/exifdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.exif.TiffDataTypeController](../../com.aspose.imaging.exif/tiffdatatypecontroller)

**All Implemented Interfaces:**
[com.aspose.imaging.metadata.IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)
```
public class ExifData extends TiffDataTypeController implements IImageMetadataFormat
```

Contenitore di dati EXIF.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ExifData()](#ExifData--) | Inizializza una nuova istanza della classe `ExifData`. |
| [ExifData(TiffDataType[] exifdata)](#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Inizializza una nuova istanza della classe `ExifData` con dati da un array. |
| [ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---) | Inizializza una nuova istanza della classe `ExifData` con dati da un array. |
| [ExifData(ExifData exifdata)](#ExifData-com.aspose.imaging.exif.ExifData-) | Inizializza una nuova istanza della classe [ExifData](../../com.aspose.imaging.exif/exifdata) con dati da un array. |
| [ExifData(byte[] binaryData)](#ExifData-byte---) | Inizializza una nuova istanza della classe [ExifData](../../com.aspose.imaging.exif/exifdata). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isBigEndian()](#isBigEndian--) | Ottiene o imposta un valore che indica se i dati EXIF del flusso da cui è stato creato sono big endian. |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | Ottiene o imposta un valore che indica se i dati EXIF del flusso da cui è stato creato sono big endian. |
| [getMake()](#getMake--) | Ottiene il produttore dell'attrezzatura di registrazione. |
| [setMake(String value)](#setMake-java.lang.String-) | Imposta il produttore dell'attrezzatura di registrazione. |
| [getApertureValue()](#getApertureValue--) | Ottiene o imposta il valore dell'apertura. |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta il valore dell'apertura. |
| [getBodySerialNumber()](#getBodySerialNumber--) | Ottiene o imposta il numero di serie del corpo della fotocamera. |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | Ottiene o imposta il numero di serie del corpo della fotocamera. |
| [getBrightnessValue()](#getBrightnessValue--) | Ottiene o imposta il valore della luminosità. |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Ottiene o imposta il valore della luminosità. |
| [getCFAPattern()](#getCFAPattern--) | Ottiene o imposta il modello CFA. |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | Ottiene o imposta il modello CFA. |
| [getCameraOwnerName()](#getCameraOwnerName--) | Ottiene o imposta il nome del proprietario della fotocamera |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | Ottiene o imposta il nome del proprietario della fotocamera |
| [getColorSpace()](#getColorSpace--) | Ottiene o imposta lo spazio colore. |
| [setColorSpace(int value)](#setColorSpace-int-) | Ottiene o imposta lo spazio colore. |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | Ottiene o imposta la configurazione dei componenti. |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | Ottiene o imposta la configurazione dei componenti. |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | Ottiene o imposta i bit compressi per pixel. |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta i bit compressi per pixel. |
| [getContrast()](#getContrast--) | Ottiene o imposta il contrasto. |
| [setContrast(int value)](#setContrast-int-) | Ottiene o imposta il contrasto. |
| [getCustomRendered()](#getCustomRendered--) | Ottiene o imposta il render personalizzato. |
| [setCustomRendered(int value)](#setCustomRendered-int-) | Ottiene o imposta il render personalizzato. |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | Ottiene o imposta la data e ora di digitalizzazione. |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | Ottiene o imposta la data e ora di digitalizzazione. |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | Ottiene o imposta la data e ora originale. |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | Ottiene o imposta la data e ora originale. |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | Ottiene o imposta la descrizione delle impostazioni del dispositivo. |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | Ottiene o imposta la descrizione delle impostazioni del dispositivo. |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | Ottiene o imposta il rapporto zoom digitale. |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta il rapporto zoom digitale. |
| [getExifVersion()](#getExifVersion--) | Ottiene o imposta la versione EXIF. |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | Ottiene o imposta la versione EXIF. |
| [getExposureBiasValue()](#getExposureBiasValue--) | Ottiene o imposta il valore di compensazione dell'esposizione. |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Ottiene o imposta il valore di compensazione dell'esposizione. |
| [getExposureIndex()](#getExposureIndex--) | Ottiene o imposta l'indice di esposizione. |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta l'indice di esposizione. |
| [getExposureMode()](#getExposureMode--) | Ottiene o imposta la modalità di esposizione. |
| [setExposureMode(int value)](#setExposureMode-int-) | Ottiene o imposta la modalità di esposizione. |
| [getExposureProgram()](#getExposureProgram--) | Ottiene o imposta il programma di esposizione. |
| [setExposureProgram(int value)](#setExposureProgram-int-) | Ottiene o imposta il programma di esposizione. |
| [getExposureTime()](#getExposureTime--) | Ottiene o imposta il tempo di esposizione. |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta il tempo di esposizione. |
| [getFNumber()](#getFNumber--) | Ottiene o imposta il numero F. |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta il numero F. |
| [getFileSource()](#getFileSource--) | Ottiene o imposta il tipo di origine del file. |
| [setFileSource(byte value)](#setFileSource-byte-) | Ottiene o imposta il tipo di origine del file. |
| [getFlash()](#getFlash--) | Ottiene o imposta il flash. |
| [setFlash(int value)](#setFlash-int-) | Ottiene o imposta il flash. |
| [getFlashEnergy()](#getFlashEnergy--) | Ottiene o imposta l'energia del flash. |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta l'energia del flash. |
| [getFlashpixVersion()](#getFlashpixVersion--) | Ottiene o imposta la versione flash pix. |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | Ottiene o imposta la versione flash pix. |
| [getFocalLength()](#getFocalLength--) | Ottiene o imposta la lunghezza focale. |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta la lunghezza focale. |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | Ottiene o imposta la lunghezza focale in pellicola da 35 mm. |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | Ottiene o imposta la lunghezza focale in pellicola da 35 mm. |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | Ottiene o imposta l'unità di risoluzione del piano focale. |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | Ottiene o imposta l'unità di risoluzione del piano focale. |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | Ottiene o imposta la risoluzione X del piano focale. |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta la risoluzione X del piano focale. |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | Ottiene o imposta la risoluzione Y del piano focale. |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta la risoluzione Y del piano focale. |
| [getGPSAltitude()](#getGPSAltitude--) | Ottiene o imposta l'altitudine GPS. |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta l'altitudine GPS. |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | Ottiene o imposta l'altitudine GPS usata come altitudine di riferimento. |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | Ottiene o imposta l'altitudine GPS usata come altitudine di riferimento. |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | Ottiene o imposta le informazioni sull'area GPS. |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | Ottiene o imposta le informazioni sull'area GPS. |
| [getGPSDOP()](#getGPSDOP--) | Ottiene o imposta il GPS DOP (grado di precisione dei dati). |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta il GPS DOP (grado di precisione dei dati). |
| [getGPSDestBearing()](#getGPSDestBearing--) | Ottiene o imposta la direzione GPS verso il punto di destinazione. |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta la direzione GPS verso il punto di destinazione. |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | Ottiene o imposta il riferimento GPS usato per fornire la direzione al punto di destinazione. |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | Ottiene o imposta il riferimento GPS usato per fornire la direzione al punto di destinazione. |
| [getGPSDestDistance()](#getGPSDestDistance--) | Ottiene o imposta la distanza GPS al punto di destinazione. |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta la distanza GPS al punto di destinazione. |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | Ottiene o imposta l'unità GPS usata per esprimere la distanza al punto di destinazione. |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | Ottiene o imposta l'unità GPS usata per esprimere la distanza al punto di destinazione. |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | Ottiene o imposta la latitudine GPS del punto di destinazione. |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Ottiene o imposta la latitudine GPS del punto di destinazione. |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | Ottiene o imposta il valore GPS che indica se la latitudine del punto di destinazione è nord o sud. |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | Ottiene o imposta il valore GPS che indica se la latitudine del punto di destinazione è nord o sud. |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | Ottiene o imposta la longitudine GPS del punto di destinazione. |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Ottiene o imposta la longitudine GPS del punto di destinazione. |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | Ottiene o imposta il valore GPS che indica se la longitudine del punto di destinazione è est o ovest. |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | Ottiene o imposta il valore GPS che indica se la longitudine del punto di destinazione è est o ovest. |
| [getGPSDifferential()](#getGPSDifferential--) | Ottiene o imposta un valore GPS che indica se la correzione differenziale è applicata al ricevitore GPS. |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | Ottiene o imposta un valore GPS che indica se la correzione differenziale è applicata al ricevitore GPS. |
| [getGPSImgDirection()](#getGPSImgDirection--) | Ottiene o imposta la direzione GPS dell'immagine al momento della cattura. |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta la direzione GPS dell'immagine al momento della cattura. |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | Ottiene o imposta il riferimento GPS per fornire la direzione dell'immagine al momento della cattura. |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | Ottiene o imposta il riferimento GPS per fornire la direzione dell'immagine al momento della cattura. |
| [getGPSDateStamp()](#getGPSDateStamp--) | Ottiene o imposta la stringa di caratteri GPS che registra le informazioni di data e ora relative a UTC (Tempo Coordinato Universale). |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | Ottiene o imposta la stringa di caratteri GPS che registra le informazioni di data e ora relative a UTC (Tempo Coordinato Universale). |
| [getGPSLatitude()](#getGPSLatitude--) | Ottiene o imposta la latitudine GPS. |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Ottiene o imposta la latitudine GPS. |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | Ottiene o imposta se la latitudine GPS è nord o sud. |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | Ottiene o imposta se la latitudine GPS è nord o sud. |
| [getGPSLongitude()](#getGPSLongitude--) | Ottiene o imposta la longitudine GPS. |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Ottiene o imposta la longitudine GPS. |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | Ottiene o imposta se la longitudine GPS è est o ovest. |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | Ottiene o imposta se la longitudine GPS è est o ovest. |
| [getGPSMapDatum()](#getGPSMapDatum--) | Ottiene o imposta i dati di rilevamento geodetico GPS usati dal ricevitore GPS. |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | Ottiene o imposta i dati di rilevamento geodetico GPS usati dal ricevitore GPS. |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | Ottiene o imposta la modalità di misurazione GPS. |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | Ottiene o imposta la modalità di misurazione GPS. |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | Ottiene o imposta la stringa di caratteri GPS che registra il nome del metodo usato per la ricerca della posizione. |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | Ottiene o imposta la stringa di caratteri GPS che registra il nome del metodo usato per la ricerca della posizione. |
| [getGPSSatellites()](#getGPSSatellites--) | Ottiene o imposta i satelliti GPS usati per le misurazioni. |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | Ottiene o imposta i satelliti GPS usati per le misurazioni. |
| [getGPSSpeed()](#getGPSSpeed--) | Ottiene o imposta la velocità di movimento del ricevitore GPS. |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta la velocità di movimento del ricevitore GPS. |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | Ottiene o imposta l'unità usata per esprimere la velocità di movimento del ricevitore GPS. |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | Ottiene o imposta l'unità usata per esprimere la velocità di movimento del ricevitore GPS. |
| [getGPSStatus()](#getGPSStatus--) | Ottiene o imposta lo stato del ricevitore GPS al momento della registrazione dell'immagine. |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | Ottiene o imposta lo stato del ricevitore GPS al momento della registrazione dell'immagine. |
| [getGPSTimestamp()](#getGPSTimestamp--) | Ottiene o imposta l'ora GPS come UTC (Tempo Coordinato Universale). |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.imaging.fileformats.tiff.TiffRational---) | Ottiene o imposta l'ora GPS come UTC (Tempo Coordinato Universale). |
| [getGPSTrack()](#getGPSTrack--) | Ottiene o imposta la direzione del movimento del ricevitore GPS. |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | Ottiene o imposta la direzione del movimento del ricevitore GPS. |
| [getGPSTrackRef()](#getGPSTrackRef--) | Ottiene o imposta il riferimento per fornire la direzione del movimento del ricevitore GPS. |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | Ottiene o imposta il riferimento per fornire la direzione del movimento del ricevitore GPS. |
| [getGPSVersionID()](#getGPSVersionID--) | Ottiene o imposta l'identificatore della versione GPS. |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | Ottiene o imposta l'identificatore della versione GPS. |
| [getGainControl()](#getGainControl--) | Ottiene o imposta il grado di regolazione complessiva del guadagno dell'immagine. |
| [setGainControl(int value)](#setGainControl-int-) | Ottiene o imposta il grado di regolazione complessiva del guadagno dell'immagine. |
| [getGamma()](#getGamma--) | Ottiene o imposta il valore gamma. |
| [setGamma(TiffRational value)](#setGamma-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta il valore gamma. |
| [getISOSpeed()](#getISOSpeed--) | Ottiene o imposta la velocità ISO |
| [setISOSpeed(long value)](#setISOSpeed-long-) | Ottiene o imposta la velocità ISO |
| [getISOSpeedValue()](#getISOSpeedValue--) | Ottiene il valore della velocità ISO. |
| [setISOSpeedValue(long value)](#setISOSpeedValue-long-) | Imposta il valore della velocità ISO. |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | Ottiene o imposta il valore della latitudine yyy della velocità ISO di una fotocamera o dispositivo di input definito nella ISO 12232. |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | Ottiene o imposta il valore della latitudine yyy della velocità ISO di una fotocamera o dispositivo di input definito nella ISO 12232. |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | Ottiene o imposta il valore della latitudine zzz della velocità ISO di una fotocamera o dispositivo di input definito nella ISO 12232. |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | Ottiene o imposta il valore della latitudine zzz della velocità ISO di una fotocamera o dispositivo di input definito nella ISO 12232. |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | Ottiene o imposta la sensibilità fotografica. |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | Ottiene o imposta la sensibilità fotografica. |
| [getImageUniqueID()](#getImageUniqueID--) | Ottiene o imposta l'identificatore univoco dell'immagine. |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | Ottiene o imposta l'identificatore univoco dell'immagine. |
| [getLensMake()](#getLensMake--) | Ottiene o imposta il produttore dell'obiettivo. |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | Ottiene o imposta il produttore dell'obiettivo. |
| [getLensModel()](#getLensModel--) | Ottiene o imposta il modello dell'obiettivo. |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | Ottiene o imposta il modello dell'obiettivo. |
| [getLensSerialNumber()](#getLensSerialNumber--) | Ottiene o imposta il numero di serie dell'obiettivo. |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | Ottiene o imposta il numero di serie dell'obiettivo. |
| [getLensSpecification()](#getLensSpecification--) | Ottiene o imposta la specifica dell'obiettivo |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.imaging.fileformats.tiff.TiffRational---) | Ottiene o imposta la specifica dell'obiettivo |
| [getLightSource()](#getLightSource--) | Ottiene o imposta la sorgente luminosa. |
| [setLightSource(int value)](#setLightSource-int-) | Ottiene o imposta la sorgente luminosa. |
| [getMakerNoteData()](#getMakerNoteData--) | Ottiene i dati della nota del produttore. |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | Ottiene o imposta i dati grezzi della nota del produttore. |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | Ottiene o imposta i dati grezzi della nota del produttore. |
| [getMakerNotes()](#getMakerNotes--) | Ottiene le note del produttore. |
| [getMaxApertureValue()](#getMaxApertureValue--) | Ottiene o imposta il valore dell'apertura massima. |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta il valore dell'apertura massima. |
| [getMeteringMode()](#getMeteringMode--) | Ottiene o imposta la modalità di misurazione. |
| [setMeteringMode(int value)](#setMeteringMode-int-) | Ottiene o imposta la modalità di misurazione. |
| [getOECF()](#getOECF--) | Ottiene o imposta la Funzione di Conversione Opto-Elettrica (OECF) specificata nella ISO 14524. |
| [setOECF(byte[] value)](#setOECF-byte---) | Ottiene o imposta la Funzione di Conversione Opto-Elettrica (OECF) specificata nella ISO 14524. |
| [getOrientation()](#getOrientation--) | Ottiene l'orientamento [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation). |
| [setOrientation(int value)](#setOrientation-int-) | Imposta l'orientamento [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation). |
| [getPixelXDimension()](#getPixelXDimension--) | Ottiene o imposta la dimensione x del pixel. |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | Ottiene o imposta la dimensione x del pixel. |
| [getPixelYDimension()](#getPixelYDimension--) | Ottiene o imposta la dimensione y del pixel. |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | Ottiene o imposta la dimensione y del pixel. |
| [getProperties()](#getProperties--) | Ottiene o imposta tutti i tag EXIF (inclusi i tag comuni e GPS). |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Ottiene o imposta tutti i tag EXIF (inclusi i tag comuni e GPS). |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | Ottiene o imposta l'indice di esposizione consigliato. |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | Ottiene o imposta l'indice di esposizione consigliato. |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | Ottiene o imposta il file audio correlato. |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | Ottiene o imposta il file audio correlato. |
| [getSaturation()](#getSaturation--) | Ottiene o imposta la saturazione. |
| [setSaturation(int value)](#setSaturation-int-) | Ottiene o imposta la saturazione. |
| [getSceneCaptureType()](#getSceneCaptureType--) | Ottiene o imposta il tipo di acquisizione della scena. |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | Ottiene o imposta il tipo di acquisizione della scena. |
| [getSceneType()](#getSceneType--) | Ottiene o imposta il tipo di scena. |
| [setSceneType(byte value)](#setSceneType-byte-) | Ottiene o imposta il tipo di scena. |
| [getSensingMethod()](#getSensingMethod--) | Ottiene o imposta il metodo di rilevamento. |
| [setSensingMethod(int value)](#setSensingMethod-int-) | Ottiene o imposta il metodo di rilevamento. |
| [getSensitivityType()](#getSensitivityType--) | Ottiene o imposta il tipo di sensibilità. |
| [setSensitivityType(int value)](#setSensitivityType-int-) | Ottiene o imposta il tipo di sensibilità. |
| [getSharpness()](#getSharpness--) | Ottiene o imposta la nitidezza. |
| [setSharpness(int value)](#setSharpness-int-) | Ottiene o imposta la nitidezza. |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | Ottiene o imposta il valore della velocità dell'otturatore. |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Ottiene o imposta il valore della velocità dell'otturatore. |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | Ottiene o imposta la risposta in frequenza spaziale. |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | Ottiene o imposta la risposta in frequenza spaziale. |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | Ottiene o imposta la sensibilità spettrale. |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | Ottiene o imposta la sensibilità spettrale. |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | Ottiene la sensibilità di uscita standard |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | Imposta la sensibilità di uscita standard |
| [getSubjectArea()](#getSubjectArea--) | Ottiene o imposta l'area del soggetto. |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | Ottiene o imposta l'area del soggetto. |
| [getSubjectDistance()](#getSubjectDistance--) | Ottiene o imposta la distanza del soggetto. |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.imaging.fileformats.tiff.TiffRational-) | Ottiene o imposta la distanza del soggetto. |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | Ottiene o imposta l'intervallo di distanza del soggetto. |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | Ottiene o imposta l'intervallo di distanza del soggetto. |
| [getSubjectLocation()](#getSubjectLocation--) | Ottiene o imposta la posizione del soggetto. |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | Ottiene o imposta la posizione del soggetto. |
| [getSubsecTime()](#getSubsecTime--) | Ottiene o imposta le frazioni di secondo per il tag DateTime. |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | Ottiene o imposta le frazioni di secondo per il tag DateTime. |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | Ottiene o imposta le frazioni di secondo per il tag DateTimeDigitized. |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | Ottiene o imposta le frazioni di secondo per il tag DateTimeDigitized. |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | Ottiene o imposta le frazioni di secondo per il tag DateTimeOriginal. |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | Ottiene o imposta le frazioni di secondo per il tag DateTimeOriginal. |
| [getUserComment()](#getUserComment--) | Ottiene o imposta il commento dell'utente. |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | Ottiene o imposta il commento dell'utente. |
| [getWhiteBalance()](#getWhiteBalance--) | Ottiene o imposta il bilanciamento del bianco. |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | Ottiene o imposta il bilanciamento del bianco. |
| [getWhitePoint()](#getWhitePoint--) | Ottiene o imposta la cromaticità del punto bianco dell'immagine. |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.imaging.fileformats.tiff.TiffRational---) | Ottiene o imposta la cromaticità del punto bianco dell'immagine. |
| [getCommonTags()](#getCommonTags--) | Ottiene o imposta i tag, che appartengono alla sezione comune. |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Ottiene o imposta i tag, che appartengono alla sezione comune. |
| [getExifTags()](#getExifTags--) | Ottiene o imposta i tag che appartengono solo alla sezione EXIF. |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Ottiene o imposta i tag che appartengono solo alla sezione EXIF. |
| [getGPSTags()](#getGPSTags--) | Ottiene o imposta i tag, che appartengono solo alla sezione GPS. |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Ottiene o imposta i tag, che appartengono solo alla sezione GPS. |
| [getThumbnail()](#getThumbnail--) | Ottiene l'immagine miniatura. |
| [setThumbnail(RasterImage value)](#setThumbnail-com.aspose.imaging.RasterImage-) | Imposta l'immagine miniatura. |
| [getXResolutionInt()](#getXResolutionInt--) | Ottiene la risoluzione x. |
| [setXResolution(int value)](#setXResolution-int-) | Imposta la risoluzione x. |
| [getYResolutionInt()](#getYResolutionInt--) | Ottiene la risoluzione y. |
| [setYResolution(int value)](#setYResolution-int-) | Imposta la risoluzione y. |
| [removeTag(int tagId)](#removeTag-int-) | Rimuovi il tag dal contenitore |
| [getTagValue(int key)](#getTagValue-int-) | Ottiene il valore del tag. |

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


Inizializza una nuova istanza della classe `ExifData`.

### ExifData(TiffDataType[] exifdata) {#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] exifdata)
```


Inizializza una nuova istanza della classe `ExifData` con dati da un array.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Array di tag EXIF insieme a tag comuni e GPS. |

### ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Inizializza una nuova istanza della classe `ExifData` con dati da un array.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | I tag comuni. |
| exifTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | I tag EXIF. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | I tag GPS. |

### ExifData(ExifData exifdata) {#ExifData-com.aspose.imaging.exif.ExifData-}
```
public ExifData(ExifData exifdata)
```


Inizializza una nuova istanza della classe [ExifData](../../com.aspose.imaging.exif/exifdata) con dati da un array.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| exifdata | [ExifData](../../com.aspose.imaging.exif/exifdata) | Array di tag EXIF insieme a tag comuni e GPS. |

### ExifData(byte[] binaryData) {#ExifData-byte---}
```
public ExifData(byte[] binaryData)
```


Inizializza una nuova istanza della classe [ExifData](../../com.aspose.imaging.exif/exifdata).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| binaryData | byte[] | I dati binari. |

### isBigEndian() {#isBigEndian--}
```
public boolean isBigEndian()
```


Ottiene o imposta un valore che indica se i dati EXIF del flusso da cui è stato creato sono big endian.

Valore: `true` se il flusso di dati EXIF da cui è stato creato è big endian; altrimenti, `false`.

**Returns:**
boolean
### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


Ottiene o imposta un valore che indica se i dati EXIF del flusso da cui è stato creato sono big endian.

Valore: `true` se il flusso di dati EXIF da cui è stato creato è big endian; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getMake() {#getMake--}
```
public final String getMake()
```


Ottiene il produttore dell'attrezzatura di registrazione.

Valore: Il produttore dell'attrezzatura di registrazione.

**Returns:**
java.lang.String - il produttore dell'attrezzatura di registrazione.
### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


Imposta il produttore dell'attrezzatura di registrazione.

Valore: Il produttore dell'attrezzatura di registrazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | il produttore dell'attrezzatura di registrazione. |

### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


Ottiene o imposta il valore dell'apertura.

Valore: Il valore dell'apertura.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


Ottiene o imposta il valore dell'apertura.

Valore: Il valore dell'apertura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


Ottiene o imposta il numero di serie del corpo della fotocamera.

Valore: Il numero di serie del corpo.

**Returns:**
java.lang.String
### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


Ottiene o imposta il numero di serie del corpo della fotocamera.

Valore: Il numero di serie del corpo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


Ottiene o imposta il valore della luminosità.

Valore: Il valore della luminosità.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


Ottiene o imposta il valore della luminosità.

Valore: Il valore della luminosità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


Ottiene o imposta il modello CFA.

Valore: Il modello CFA.

**Returns:**
byte[]
### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


Ottiene o imposta il modello CFA.

Valore: Il modello CFA.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


Ottiene o imposta il nome del proprietario della fotocamera

Valore: Il nome del proprietario della fotocamera.

**Returns:**
java.lang.String
### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


Ottiene o imposta il nome del proprietario della fotocamera

Valore: Il nome del proprietario della fotocamera.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getColorSpace() {#getColorSpace--}
```
public int getColorSpace()
```


Ottiene o imposta lo spazio colore.

Valore: Lo spazio colore.

**Returns:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


Ottiene o imposta lo spazio colore.

Valore: Lo spazio colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


Ottiene o imposta la configurazione dei componenti.

Valore: La configurazione dei componenti.

**Returns:**
byte[]
### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


Ottiene o imposta la configurazione dei componenti.

Valore: La configurazione dei componenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


Ottiene o imposta i bit compressi per pixel.

Valore: I bit compressi per pixel.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


Ottiene o imposta i bit compressi per pixel.

Valore: I bit compressi per pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getContrast() {#getContrast--}
```
public int getContrast()
```


Ottiene o imposta il contrasto.

Valore: Il contrasto.

**Returns:**
int
### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


Ottiene o imposta il contrasto.

Valore: Il contrasto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


Ottiene o imposta il render personalizzato.

Valore: Il rendering personalizzato.

**Returns:**
int
### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


Ottiene o imposta il render personalizzato.

Valore: Il rendering personalizzato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


Ottiene o imposta la data e ora di digitalizzazione.

Valore: La data e ora di digitalizzazione.

**Returns:**
java.lang.String
### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


Ottiene o imposta la data e ora di digitalizzazione.

Valore: La data e ora di digitalizzazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


Ottiene o imposta la data e ora originale.

Valore: La data e ora originale.

**Returns:**
java.lang.String
### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


Ottiene o imposta la data e ora originale.

Valore: La data e ora originale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


Ottiene o imposta la descrizione delle impostazioni del dispositivo.

Valore: La descrizione delle impostazioni del dispositivo.

**Returns:**
byte[]
### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


Ottiene o imposta la descrizione delle impostazioni del dispositivo.

Valore: La descrizione delle impostazioni del dispositivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


Ottiene o imposta il rapporto zoom digitale.

Valore: Il rapporto di zoom digitale.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


Ottiene o imposta il rapporto zoom digitale.

Valore: Il rapporto di zoom digitale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


Ottiene o imposta la versione EXIF.

Valore: La versione EXIF.

**Returns:**
byte[]
### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


Ottiene o imposta la versione EXIF.

Valore: La versione EXIF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


Ottiene o imposta il valore di compensazione dell'esposizione.

Valore: Il valore di compensazione dell'esposizione.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


Ottiene o imposta il valore di compensazione dell'esposizione.

Valore: Il valore di compensazione dell'esposizione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


Ottiene o imposta l'indice di esposizione.

Valore: L'indice dell'esposizione.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


Ottiene o imposta l'indice di esposizione.

Valore: L'indice dell'esposizione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


Ottiene o imposta la modalità di esposizione.

Valore: La modalità di esposizione.

**Returns:**
int
### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


Ottiene o imposta la modalità di esposizione.

Valore: La modalità di esposizione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


Ottiene o imposta il programma di esposizione.

Valore: Il programma di esposizione.

**Returns:**
int
### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


Ottiene o imposta il programma di esposizione.

Valore: Il programma di esposizione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


Ottiene o imposta il tempo di esposizione.

Valore: Il tempo di esposizione.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


Ottiene o imposta il tempo di esposizione.

Valore: Il tempo di esposizione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


Ottiene o imposta il numero F.

Valore: Il numero F.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFNumber(TiffRational value) {#setFNumber-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


Ottiene o imposta il numero F.

Valore: Il numero F.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


Ottiene o imposta il tipo di origine del file.

Valore: Il tipo di origine del file.

**Returns:**
byte
### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


Ottiene o imposta il tipo di origine del file.

Valore: Il tipo di origine del file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getFlash() {#getFlash--}
```
public int getFlash()
```


Ottiene o imposta il flash.

Valore: Il flash.

**Returns:**
int
### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


Ottiene o imposta il flash.

Valore: Il flash.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


Ottiene o imposta l'energia del flash.

Valore: L'energia del flash.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


Ottiene o imposta l'energia del flash.

Valore: L'energia del flash.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


Ottiene o imposta la versione flash pix.

Valore: La versione flash pix.

**Returns:**
byte[]
### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


Ottiene o imposta la versione flash pix.

Valore: La versione flash pix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


Ottiene o imposta la lunghezza focale.

Valore: La lunghezza focale.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


Ottiene o imposta la lunghezza focale.

Valore: La lunghezza focale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


Ottiene o imposta la lunghezza focale in pellicola da 35 mm.

Valore: La lunghezza focale in pellicola da 35 mm.

**Returns:**
int
### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


Ottiene o imposta la lunghezza focale in pellicola da 35 mm.

Valore: La lunghezza focale in pellicola da 35 mm.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


Ottiene o imposta l'unità di risoluzione del piano focale.

Valore: L'unità di risoluzione del piano focale.

**Returns:**
int
### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


Ottiene o imposta l'unità di risoluzione del piano focale.

Valore: L'unità di risoluzione del piano focale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


Ottiene o imposta la risoluzione X del piano focale.

Value: La risoluzione x del piano focale.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


Ottiene o imposta la risoluzione X del piano focale.

Value: La risoluzione x del piano focale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


Ottiene o imposta la risoluzione Y del piano focale.

Value: La risoluzione y del piano focale.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


Ottiene o imposta la risoluzione Y del piano focale.

Value: La risoluzione y del piano focale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


Ottiene o imposta l'altitudine GPS.

Value: L'altitudine GPS.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


Ottiene o imposta l'altitudine GPS.

Value: L'altitudine GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


Ottiene o imposta l'altitudine GPS usata come altitudine di riferimento.

Value: L'altitudine GPS usata come altitudine di riferimento.

**Returns:**
byte
### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


Ottiene o imposta l'altitudine GPS usata come altitudine di riferimento.

Value: L'altitudine GPS usata come altitudine di riferimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


Ottiene o imposta le informazioni sull'area GPS.

Value: Le informazioni sull'area GPS.

**Returns:**
byte[]
### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


Ottiene o imposta le informazioni sull'area GPS.

Value: Le informazioni sull'area GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


Ottiene o imposta il GPS DOP (grado di precisione dei dati).

Value: Il DOP GPS (grado di precisione dei dati).

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


Ottiene o imposta il GPS DOP (grado di precisione dei dati).

Value: Il DOP GPS (grado di precisione dei dati).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


Ottiene o imposta la direzione GPS verso il punto di destinazione.

Value: L'azimut GPS verso il punto di destinazione.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


Ottiene o imposta la direzione GPS verso il punto di destinazione.

Value: L'azimut GPS verso il punto di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


Ottiene o imposta il riferimento GPS usato per fornire la direzione al punto di destinazione.

Value: Il riferimento GPS usato per fornire l'azimut verso il punto di destinazione.

**Returns:**
java.lang.String
### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


Ottiene o imposta il riferimento GPS usato per fornire la direzione al punto di destinazione.

Value: Il riferimento GPS usato per fornire l'azimut verso il punto di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


Ottiene o imposta la distanza GPS al punto di destinazione.

Value: La distanza GPS al punto di destinazione.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


Ottiene o imposta la distanza GPS al punto di destinazione.

Value: La distanza GPS al punto di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


Ottiene o imposta l'unità GPS usata per esprimere la distanza al punto di destinazione.

Value: L'unità GPS usata per esprimere la distanza al punto di destinazione.

**Returns:**
java.lang.String
### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


Ottiene o imposta l'unità GPS usata per esprimere la distanza al punto di destinazione.

Value: L'unità GPS usata per esprimere la distanza al punto di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


Ottiene o imposta la latitudine GPS del punto di destinazione.

Value: La latitudine GPS del punto di destinazione.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


Ottiene o imposta la latitudine GPS del punto di destinazione.

Value: La latitudine GPS del punto di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


Ottiene o imposta il valore GPS che indica se la latitudine del punto di destinazione è nord o sud.

Value: Il valore GPS che indica se la latitudine del punto di destinazione è nord o sud.

**Returns:**
java.lang.String
### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


Ottiene o imposta il valore GPS che indica se la latitudine del punto di destinazione è nord o sud.

Value: Il valore GPS che indica se la latitudine del punto di destinazione è nord o sud.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


Ottiene o imposta la longitudine GPS del punto di destinazione.

Value: La longitudine GPS del punto di destinazione.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


Ottiene o imposta la longitudine GPS del punto di destinazione.

Value: La longitudine GPS del punto di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


Ottiene o imposta il valore GPS che indica se la longitudine del punto di destinazione è est o ovest.

Value: Il valore GPS che indica se la longitudine del punto di destinazione è est o ovest.

**Returns:**
java.lang.String
### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


Ottiene o imposta il valore GPS che indica se la longitudine del punto di destinazione è est o ovest.

Value: Il valore GPS che indica se la longitudine del punto di destinazione è est o ovest.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


Ottiene o imposta un valore GPS che indica se la correzione differenziale è applicata al ricevitore GPS.

Value: Il valore GPS che indica se è applicata la correzione differenziale al ricevitore GPS.

**Returns:**
int
### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


Ottiene o imposta un valore GPS che indica se la correzione differenziale è applicata al ricevitore GPS.

Value: Il valore GPS che indica se è applicata la correzione differenziale al ricevitore GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


Ottiene o imposta la direzione GPS dell'immagine al momento della cattura.

Value: La direzione GPS dell'immagine al momento della cattura.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


Ottiene o imposta la direzione GPS dell'immagine al momento della cattura.

Value: La direzione GPS dell'immagine al momento della cattura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


Ottiene o imposta il riferimento GPS per fornire la direzione dell'immagine al momento della cattura.

Value: Il riferimento GPS per fornire la direzione dell'immagine al momento della cattura.

**Returns:**
java.lang.String
### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


Ottiene o imposta il riferimento GPS per fornire la direzione dell'immagine al momento della cattura.

Value: Il riferimento GPS per fornire la direzione dell'immagine al momento della cattura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


Ottiene o imposta la stringa di caratteri GPS che registra le informazioni di data e ora relative a UTC (Tempo Coordinato Universale).

Value: La stringa di caratteri GPS che registra le informazioni di data e ora relative a UTC (Tempo Coordinato Universale).

**Returns:**
java.lang.String
### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


Ottiene o imposta la stringa di caratteri GPS che registra le informazioni di data e ora relative a UTC (Tempo Coordinato Universale).

Value: La stringa di caratteri GPS che registra le informazioni di data e ora relative a UTC (Tempo Coordinato Universale).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


Ottiene o imposta la latitudine GPS.

Value: La latitudine GPS.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


Ottiene o imposta la latitudine GPS.

Value: La latitudine GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


Ottiene o imposta se la latitudine GPS è nord o sud.

Value: La latitudine GPS è nord o sud.

**Returns:**
java.lang.String
### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


Ottiene o imposta se la latitudine GPS è nord o sud.

Value: La latitudine GPS è nord o sud.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


Ottiene o imposta la longitudine GPS.

Value: La longitudine GPS.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


Ottiene o imposta la longitudine GPS.

Value: La longitudine GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


Ottiene o imposta se la longitudine GPS è est o ovest.

Value: La longitudine GPS è est o ovest.

**Returns:**
java.lang.String
### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


Ottiene o imposta se la longitudine GPS è est o ovest.

Value: La longitudine GPS è est o ovest.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


Ottiene o imposta i dati di rilevamento geodetico GPS usati dal ricevitore GPS.

Value: I dati di rilevamento geodetico GPS usati dal ricevitore GPS.

**Returns:**
java.lang.String
### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


Ottiene o imposta i dati di rilevamento geodetico GPS usati dal ricevitore GPS.

Value: I dati di rilevamento geodetico GPS usati dal ricevitore GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


Ottiene o imposta la modalità di misurazione GPS.

Value: La modalità di misurazione GPS.

**Returns:**
java.lang.String
### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


Ottiene o imposta la modalità di misurazione GPS.

Value: La modalità di misurazione GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


Ottiene o imposta la stringa di caratteri GPS che registra il nome del metodo usato per la ricerca della posizione.

Value: La stringa di caratteri GPS che registra il nome del metodo usato per la localizzazione.

**Returns:**
byte[]
### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


Ottiene o imposta la stringa di caratteri GPS che registra il nome del metodo usato per la ricerca della posizione.

Value: La stringa di caratteri GPS che registra il nome del metodo usato per la localizzazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


Ottiene o imposta i satelliti GPS usati per le misurazioni.

Valore: I satelliti GPS utilizzati per le misurazioni.

**Returns:**
java.lang.String
### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


Ottiene o imposta i satelliti GPS usati per le misurazioni.

Valore: I satelliti GPS utilizzati per le misurazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


Ottiene o imposta la velocità di movimento del ricevitore GPS.

Valore: La velocità del movimento del ricevitore GPS.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


Ottiene o imposta la velocità di movimento del ricevitore GPS.

Valore: La velocità del movimento del ricevitore GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


Ottiene o imposta l'unità usata per esprimere la velocità di movimento del ricevitore GPS.

Valore: L'unità utilizzata per esprimere la velocità di movimento del ricevitore GPS.

**Returns:**
java.lang.String
### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


Ottiene o imposta l'unità usata per esprimere la velocità di movimento del ricevitore GPS.

Valore: L'unità utilizzata per esprimere la velocità di movimento del ricevitore GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


Ottiene o imposta lo stato del ricevitore GPS al momento della registrazione dell'immagine.

Valore: Lo stato del ricevitore GPS quando l'immagine è registrata.

**Returns:**
java.lang.String
### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


Ottiene o imposta lo stato del ricevitore GPS al momento della registrazione dell'immagine.

Valore: Lo stato del ricevitore GPS quando l'immagine è registrata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


Ottiene o imposta l'ora GPS come UTC (Tempo Coordinato Universale).

Valore: Il tempo GPS come UTC (Tempo Coordinato Universale).

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


Ottiene o imposta l'ora GPS come UTC (Tempo Coordinato Universale).

Valore: Il tempo GPS come UTC (Tempo Coordinato Universale).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


Ottiene o imposta la direzione del movimento del ricevitore GPS.

Valore: La direzione del movimento del ricevitore GPS.

**Returns:**
java.lang.String
### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


Ottiene o imposta la direzione del movimento del ricevitore GPS.

Valore: La direzione del movimento del ricevitore GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


Ottiene o imposta il riferimento per fornire la direzione del movimento del ricevitore GPS.

Valore: Il riferimento per indicare la direzione del movimento del ricevitore GPS.

**Returns:**
java.lang.String
### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


Ottiene o imposta il riferimento per fornire la direzione del movimento del ricevitore GPS.

Valore: Il riferimento per indicare la direzione del movimento del ricevitore GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


Ottiene o imposta l'identificatore della versione GPS.

Valore: L'identificatore della versione GPS.

**Returns:**
byte[]
### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


Ottiene o imposta l'identificatore della versione GPS.

Valore: L'identificatore della versione GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


Ottiene o imposta il grado di regolazione complessiva del guadagno dell'immagine.

Valore: Il grado di regolazione complessiva del guadagno dell'immagine.

**Returns:**
int
### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


Ottiene o imposta il grado di regolazione complessiva del guadagno dell'immagine.

Valore: Il grado di regolazione complessiva del guadagno dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


Ottiene o imposta il valore gamma.

Valore: Il valore gamma.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGamma(TiffRational value) {#setGamma-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


Ottiene o imposta il valore gamma.

Valore: Il valore gamma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


Ottiene o imposta la velocità ISO

Valore: La velocità ISO.

**Returns:**
long
### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


Ottiene o imposta la velocità ISO

Valore: La velocità ISO.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### getISOSpeedValue() {#getISOSpeedValue--}
```
public final long getISOSpeedValue()
```


Ottiene il valore della velocità ISO.

Valore: Il valore della velocità ISO.

**Returns:**
long - il valore della velocità ISO.
### setISOSpeedValue(long value) {#setISOSpeedValue-long-}
```
public final void setISOSpeedValue(long value)
```


Imposta il valore della velocità ISO.

Valore: Il valore della velocità ISO.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | il valore della velocità ISO. |

### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


Ottiene o imposta il valore della latitudine yyy della velocità ISO di una fotocamera o dispositivo di input definito nella ISO 12232.

Valore: Il valore della latitudine di velocità ISO yyy di una fotocamera o dispositivo di input definito nella ISO 12232.

Questo tag non deve essere registrato senza ISOSpeed e ISOSpeedLatitudeZZZ

**Returns:**
long
### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


Ottiene o imposta il valore della latitudine yyy della velocità ISO di una fotocamera o dispositivo di input definito nella ISO 12232.

Valore: Il valore della latitudine di velocità ISO yyy di una fotocamera o dispositivo di input definito nella ISO 12232.

Questo tag non deve essere registrato senza ISOSpeed e ISOSpeedLatitudeZZZ

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


Ottiene o imposta il valore della latitudine zzz della velocità ISO di una fotocamera o dispositivo di input definito nella ISO 12232.

Valore: Il valore della latitudine di velocità ISO zzz di una fotocamera o dispositivo di input definito nella ISO 12232.

Questo tag non deve essere registrato senza ISOSpeed e ISOSpeedLatitudeYYY

**Returns:**
long
### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


Ottiene o imposta il valore della latitudine zzz della velocità ISO di una fotocamera o dispositivo di input definito nella ISO 12232.

Valore: Il valore della latitudine di velocità ISO zzz di una fotocamera o dispositivo di input definito nella ISO 12232.

Questo tag non deve essere registrato senza ISOSpeed e ISOSpeedLatitudeYYY

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


Ottiene o imposta la sensibilità fotografica.

Valore: La sensibilità fotografica.

**Returns:**
long
### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


Ottiene o imposta la sensibilità fotografica.

Valore: La sensibilità fotografica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


Ottiene o imposta l'identificatore univoco dell'immagine.

Valore: L'identificatore unico dell'immagine.

**Returns:**
java.lang.String
### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


Ottiene o imposta l'identificatore univoco dell'immagine.

Valore: L'identificatore unico dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


Ottiene o imposta il produttore dell'obiettivo.

Valore: Il produttore dell'obiettivo.

**Returns:**
java.lang.String
### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


Ottiene o imposta il produttore dell'obiettivo.

Valore: Il produttore dell'obiettivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


Ottiene o imposta il modello dell'obiettivo.

Valore: Il modello dell'obiettivo.

**Returns:**
java.lang.String
### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


Ottiene o imposta il modello dell'obiettivo.

Valore: Il modello dell'obiettivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


Ottiene o imposta il numero di serie dell'obiettivo.

Valore: Il numero di serie dell'obiettivo.

**Returns:**
java.lang.String
### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


Ottiene o imposta il numero di serie dell'obiettivo.

Valore: Il numero di serie dell'obiettivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


Ottiene o imposta la specifica dell'obiettivo

Valore: La specifica dell'obiettivo.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


Ottiene o imposta la specifica dell'obiettivo

Valore: La specifica dell'obiettivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


Ottiene o imposta la sorgente luminosa.

Valore: La sorgente luminosa.

**Returns:**
int
### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


Ottiene o imposta la sorgente luminosa.

Valore: La sorgente luminosa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


Ottiene i dati della nota del produttore.

Valore: i dati della nota del produttore.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


Ottiene o imposta i dati grezzi della nota del produttore.

Valore: i dati grezzi della nota del produttore.

**Returns:**
byte[]
### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


Ottiene o imposta i dati grezzi della nota del produttore.

Valore: i dati grezzi della nota del produttore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


Ottiene le note del produttore.

Valore: le note del produttore.

**Returns:**
com.aspose.imaging.exif.MakerNote[] - le note del produttore.

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


Ottiene o imposta il valore dell'apertura massima.

Valore: il valore dell'apertura massima.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


Ottiene o imposta il valore dell'apertura massima.

Valore: il valore dell'apertura massima.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


Ottiene o imposta la modalità di misurazione.

Valore: la modalità di misurazione.

**Returns:**
int
### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


Ottiene o imposta la modalità di misurazione.

Valore: la modalità di misurazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


Ottiene o imposta la Funzione di Conversione Opto-Elettrica (OECF) specificata nella ISO 14524.

Valore: la Funzione di Conversione Opto-Elettrica (OECF) specificata nella ISO 14524.

**Returns:**
byte[]
### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


Ottiene o imposta la Funzione di Conversione Opto-Elettrica (OECF) specificata nella ISO 14524.

Valore: la Funzione di Conversione Opto-Elettrica (OECF) specificata nella ISO 14524.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Ottiene l'orientamento [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation).

Valore: l'orientamento.

**Returns:**
int - l'orientamento.
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Imposta l'orientamento [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation).

Valore: l'orientamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | l'orientamento. |

### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


Ottiene o imposta la dimensione x del pixel.

Valore: la dimensione x del pixel.

**Returns:**
long
### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


Ottiene o imposta la dimensione x del pixel.

Valore: la dimensione x del pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


Ottiene o imposta la dimensione y del pixel.

Valore: la dimensione y del pixel.

**Returns:**
long
### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


Ottiene o imposta la dimensione y del pixel.

Valore: la dimensione y del pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


Ottiene o imposta tutti i tag EXIF (inclusi i tag comuni e GPS).

Valore: i tag EXIF (inclusi i tag comuni e GPS).

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setProperties(TiffDataType[] value) {#setProperties-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


Ottiene o imposta tutti i tag EXIF (inclusi i tag comuni e GPS).

Valore: i tag EXIF (inclusi i tag comuni e GPS).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


Ottiene o imposta l'indice di esposizione consigliato.

Valore: l'indice di esposizione consigliato.

**Returns:**
long
### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


Ottiene o imposta l'indice di esposizione consigliato.

Valore: l'indice di esposizione consigliato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


Ottiene o imposta il file audio correlato.

Valore: il file audio correlato.

**Returns:**
java.lang.String
### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


Ottiene o imposta il file audio correlato.

Valore: il file audio correlato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


Ottiene o imposta la saturazione.

Valore: la saturazione.

**Returns:**
int
### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


Ottiene o imposta la saturazione.

Valore: la saturazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


Ottiene o imposta il tipo di acquisizione della scena.

Valore: il tipo di cattura della scena.

**Returns:**
int
### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


Ottiene o imposta il tipo di acquisizione della scena.

Valore: il tipo di cattura della scena.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


Ottiene o imposta il tipo di scena.

Valore: il tipo di scena.

**Returns:**
byte
### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


Ottiene o imposta il tipo di scena.

Valore: il tipo di scena.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


Ottiene o imposta il metodo di rilevamento.

Valore: il metodo di rilevamento.

**Returns:**
int
### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


Ottiene o imposta il metodo di rilevamento.

Valore: il metodo di rilevamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


Ottiene o imposta il tipo di sensibilità.

Valore: il tipo di sensibilità.

**Returns:**
int
### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


Ottiene o imposta il tipo di sensibilità.

Valore: il tipo di sensibilità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


Ottiene o imposta la nitidezza.

Valore: la nitidezza.

**Returns:**
int
### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


Ottiene o imposta la nitidezza.

Valore: la nitidezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


Ottiene o imposta il valore della velocità dell'otturatore.

Valore: il valore della velocità dell'otturatore.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


Ottiene o imposta il valore della velocità dell'otturatore.

Valore: il valore della velocità dell'otturatore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


Ottiene o imposta la risposta in frequenza spaziale.

Valore: la risposta in frequenza spaziale.

**Returns:**
byte[]
### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


Ottiene o imposta la risposta in frequenza spaziale.

Valore: la risposta in frequenza spaziale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


Ottiene o imposta la sensibilità spettrale.

Valore: la sensibilità spettrale.

**Returns:**
java.lang.String
### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


Ottiene o imposta la sensibilità spettrale.

Valore: la sensibilità spettrale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


Ottiene la sensibilità di uscita standard

Valore: La sensibilità di output standard.

**Returns:**
long
### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


Imposta la sensibilità di uscita standard

Valore: La sensibilità di output standard.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


Ottiene o imposta l'area del soggetto.

Valore: L'area del soggetto.

**Returns:**
int[]
### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


Ottiene o imposta l'area del soggetto.

Valore: L'area del soggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


Ottiene o imposta la distanza del soggetto.

Valore: La distanza del soggetto.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


Ottiene o imposta la distanza del soggetto.

Valore: La distanza del soggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


Ottiene o imposta l'intervallo di distanza del soggetto.

Valore: L'intervallo di distanza del soggetto.

**Returns:**
int
### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


Ottiene o imposta l'intervallo di distanza del soggetto.

Valore: L'intervallo di distanza del soggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


Ottiene o imposta la posizione del soggetto.

Valore: La posizione del soggetto.

**Returns:**
int[]
### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


Ottiene o imposta la posizione del soggetto.

Valore: La posizione del soggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


Ottiene o imposta le frazioni di secondo per il tag DateTime.

Valore: I frazioni di secondo per il tag DateTime.

**Returns:**
java.lang.String
### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


Ottiene o imposta le frazioni di secondo per il tag DateTime.

Valore: I frazioni di secondo per il tag DateTime.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


Ottiene o imposta le frazioni di secondo per il tag DateTimeDigitized.

Valore: I frazioni di secondo per il tag DateTimeDigitized.

**Returns:**
java.lang.String
### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


Ottiene o imposta le frazioni di secondo per il tag DateTimeDigitized.

Valore: I frazioni di secondo per il tag DateTimeDigitized.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


Ottiene o imposta le frazioni di secondo per il tag DateTimeOriginal.

Valore: I frazioni di secondo per il tag DateTimeOriginal.

**Returns:**
java.lang.String
### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


Ottiene o imposta le frazioni di secondo per il tag DateTimeOriginal.

Valore: I frazioni di secondo per il tag DateTimeOriginal.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


Ottiene o imposta il commento dell'utente.

Valore: Il commento dell'utente.

**Returns:**
java.lang.String
### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


Ottiene o imposta il commento dell'utente.

Valore: Il commento dell'utente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


Ottiene o imposta il bilanciamento del bianco.

Valore: Il bilanciamento del bianco.

**Returns:**
int
### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


Ottiene o imposta il bilanciamento del bianco.

Valore: Il bilanciamento del bianco.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


Ottiene o imposta la cromaticità del punto bianco dell'immagine.

Valore: La cromaticità del punto bianco dell'immagine.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


Ottiene o imposta la cromaticità del punto bianco dell'immagine.

Valore: La cromaticità del punto bianco dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


Ottiene o imposta i tag, che appartengono alla sezione comune. Questo si applica solo alle immagini jpeg, nel formato tiff vengono utilizzate tiffOptions invece

Valore: I tag della sezione comune.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


Ottiene o imposta i tag, che appartengono alla sezione comune. Questo si applica solo alle immagini jpeg, nel formato tiff vengono utilizzate tiffOptions invece

Valore: I tag della sezione comune.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


Ottiene o imposta i tag che appartengono solo alla sezione EXIF.

Valore: I tag della sezione EXIF.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


Ottiene o imposta i tag che appartengono solo alla sezione EXIF.

Valore: I tag della sezione EXIF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


Ottiene o imposta i tag, che appartengono solo alla sezione GPS.

Valore: I tag GPS.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


Ottiene o imposta i tag, che appartengono solo alla sezione GPS.

Valore: I tag GPS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getThumbnail() {#getThumbnail--}
```
public final RasterImage getThumbnail()
```


Ottiene l'immagine miniatura.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the thumbnail image.
### setThumbnail(RasterImage value) {#setThumbnail-com.aspose.imaging.RasterImage-}
```
public final void setThumbnail(RasterImage value)
```


Imposta l'immagine miniatura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RasterImage](../../com.aspose.imaging/rasterimage) | l'immagine miniatura. |

### getXResolutionInt() {#getXResolutionInt--}
```
public final int getXResolutionInt()
```


Ottiene la risoluzione x.

Valore: La risoluzione x.

**Returns:**
int - la risoluzione x.
### setXResolution(int value) {#setXResolution-int-}
```
public final void setXResolution(int value)
```


Imposta la risoluzione x.

Valore: La risoluzione x.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | la risoluzione x. |

### getYResolutionInt() {#getYResolutionInt--}
```
public final int getYResolutionInt()
```


Ottiene la risoluzione y.

Valore: La risoluzione y.

**Returns:**
int - la risoluzione y.
### setYResolution(int value) {#setYResolution-int-}
```
public final void setYResolution(int value)
```


Imposta la risoluzione y.

Valore: La risoluzione y.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | la risoluzione y. |

### removeTag(int tagId) {#removeTag-int-}
```
public void removeTag(int tagId)
```


Rimuovi il tag dal contenitore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tagId | int | L'identificatore del tag da rimuovere. |

### getTagValue(int key) {#getTagValue-int-}
```
public final TiffDataType getTagValue(int key)
```


Ottiene il valore del tag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | int | La chiave del tag [ExifProperties](../../com.aspose.imaging.exif/exifproperties). |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - The TiffDataType
