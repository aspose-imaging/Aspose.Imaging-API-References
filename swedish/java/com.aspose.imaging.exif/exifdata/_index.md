---
title: "ExifData"
second_title: "Aspose.Imaging för Java API-referens"
description: "EXIF-datakontainer."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.exif/exifdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.exif.TiffDataTypeController](../../com.aspose.imaging.exif/tiffdatatypecontroller)

**All Implemented Interfaces:**
[com.aspose.imaging.metadata.IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)
```
public class ExifData extends TiffDataTypeController implements IImageMetadataFormat
```

EXIF-datakontainer.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ExifData()](#ExifData--) | Initierar en ny instans av klassen `ExifData`. |
| [ExifData(TiffDataType[] exifdata)](#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Initierar en ny instans av klassen `ExifData` med data från en array. |
| [ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---) | Initierar en ny instans av klassen `ExifData` med data från en array. |
| [ExifData(ExifData exifdata)](#ExifData-com.aspose.imaging.exif.ExifData-) | Initierar en ny instans av klassen [ExifData](../../com.aspose.imaging.exif/exifdata) med data från en array. |
| [ExifData(byte[] binaryData)](#ExifData-byte---) | Initierar en ny instans av klassen [ExifData](../../com.aspose.imaging.exif/exifdata). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isBigEndian()](#isBigEndian--) | Hämtar eller anger ett värde som indikerar om EXIF-data i strömmen som skapats från är big endian. |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | Hämtar eller anger ett värde som indikerar om EXIF-data i strömmen som skapats från är big endian. |
| [getMake()](#getMake--) | Hämtar tillverkaren av inspelningsutrustningen. |
| [setMake(String value)](#setMake-java.lang.String-) | Anger tillverkaren av inspelningsutrustningen. |
| [getApertureValue()](#getApertureValue--) | Hämtar eller anger bländarvärdet. |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller anger bländarvärdet. |
| [getBodySerialNumber()](#getBodySerialNumber--) | Hämtar eller anger kamerahusets serienummer. |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | Hämtar eller anger kamerahusets serienummer. |
| [getBrightnessValue()](#getBrightnessValue--) | Hämtar eller anger ljusstyrkevärdet. |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Hämtar eller anger ljusstyrkevärdet. |
| [getCFAPattern()](#getCFAPattern--) | Hämtar eller anger CFA-mönstret. |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | Hämtar eller anger CFA-mönstret. |
| [getCameraOwnerName()](#getCameraOwnerName--) | Hämtar eller anger kamerans ägarnamn |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | Hämtar eller anger kamerans ägarnamn |
| [getColorSpace()](#getColorSpace--) | Hämtar eller anger färgrymden. |
| [setColorSpace(int value)](#setColorSpace-int-) | Hämtar eller anger färgrymden. |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | Hämtar eller anger komponentkonfigurationen. |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | Hämtar eller anger komponentkonfigurationen. |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | Hämtar eller anger komprimerade bitar per pixel. |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller anger komprimerade bitar per pixel. |
| [getContrast()](#getContrast--) | Hämtar eller anger kontrasten. |
| [setContrast(int value)](#setContrast-int-) | Hämtar eller anger kontrasten. |
| [getCustomRendered()](#getCustomRendered--) | Hämtar eller anger anpassad återgivning. |
| [setCustomRendered(int value)](#setCustomRendered-int-) | Hämtar eller anger anpassad återgivning. |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | Hämtar eller anger datum och tid för digitalisering. |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | Hämtar eller anger datum och tid för digitalisering. |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | Hämtar eller anger originalets datum och tid. |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | Hämtar eller anger originalets datum och tid. |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | Hämtar eller anger beskrivning av enhetens inställningar. |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | Hämtar eller anger beskrivning av enhetens inställningar. |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | Hämtar eller anger digital zoomförhållande. |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller anger digital zoomförhållande. |
| [getExifVersion()](#getExifVersion--) | Hämtar eller anger EXIF-versionen. |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | Hämtar eller anger EXIF-versionen. |
| [getExposureBiasValue()](#getExposureBiasValue--) | Hämtar eller anger exponeringskompensationsvärdet. |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Hämtar eller anger exponeringskompensationsvärdet. |
| [getExposureIndex()](#getExposureIndex--) | Hämtar eller anger exponeringsindex. |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller anger exponeringsindex. |
| [getExposureMode()](#getExposureMode--) | Hämtar eller anger exponeringsläge. |
| [setExposureMode(int value)](#setExposureMode-int-) | Hämtar eller anger exponeringsläge. |
| [getExposureProgram()](#getExposureProgram--) | Hämtar eller anger exponeringsprogram. |
| [setExposureProgram(int value)](#setExposureProgram-int-) | Hämtar eller anger exponeringsprogram. |
| [getExposureTime()](#getExposureTime--) | Hämtar eller anger exponeringstid. |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller anger exponeringstid. |
| [getFNumber()](#getFNumber--) | Hämtar eller anger F‑numret. |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller anger F‑numret. |
| [getFileSource()](#getFileSource--) | Hämtar eller anger filkällans typ. |
| [setFileSource(byte value)](#setFileSource-byte-) | Hämtar eller anger filkällans typ. |
| [getFlash()](#getFlash--) | Hämtar eller anger blixten. |
| [setFlash(int value)](#setFlash-int-) | Hämtar eller anger blixten. |
| [getFlashEnergy()](#getFlashEnergy--) | Hämtar eller anger blixtenergi. |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller anger blixtenergi. |
| [getFlashpixVersion()](#getFlashpixVersion--) | Hämtar eller anger blixt‑pix‑version. |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | Hämtar eller anger blixt‑pix‑version. |
| [getFocalLength()](#getFocalLength--) | Hämtar eller anger brännvidden. |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller anger brännvidden. |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | Hämtar eller anger brännvidden i 35 mm film. |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | Hämtar eller anger brännvidden i 35 mm film. |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | Hämtar eller anger upplösningsenhet för fokalplanet. |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | Hämtar eller anger upplösningsenhet för fokalplanet. |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | Hämtar eller anger fokalplanets X‑upplösning. |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller anger fokalplanets X‑upplösning. |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | Hämtar eller anger fokalplanets Y‑upplösning. |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller anger fokalplanets Y‑upplösning. |
| [getGPSAltitude()](#getGPSAltitude--) | Hämtar eller anger GPS‑höjd. |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller anger GPS‑höjd. |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | Hämtar eller anger GPS‑höjden som referenshöjd. |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | Hämtar eller anger GPS‑höjden som referenshöjd. |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | Hämtar eller anger GPS‑områdesinformation. |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | Hämtar eller anger GPS‑områdesinformation. |
| [getGPSDOP()](#getGPSDOP--) | Hämtar eller anger GPS DOP (dataprecisionsgrad). |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller anger GPS DOP (dataprecisionsgrad). |
| [getGPSDestBearing()](#getGPSDestBearing--) | Hämtar eller anger GPS-bäring mot destinationspunkten. |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller anger GPS-bäring mot destinationspunkten. |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | Hämtar eller anger GPS-referensen som används för att ge bäringen mot destinationspunkten. |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | Hämtar eller anger GPS-referensen som används för att ge bäringen mot destinationspunkten. |
| [getGPSDestDistance()](#getGPSDestDistance--) | Hämtar eller anger GPS-avståndet till destinationspunkten. |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller anger GPS-avståndet till destinationspunkten. |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | Hämtar eller anger GPS-enheten som används för att uttrycka avståndet till destinationspunkten. |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | Hämtar eller anger GPS-enheten som används för att uttrycka avståndet till destinationspunkten. |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | Hämtar eller anger GPS-latituden för destinationspunkten. |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Hämtar eller anger GPS-latituden för destinationspunkten. |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | Hämtar eller anger GPS-värdet som indikerar om latituden för destinationspunkten är norra eller södra latitud. |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | Hämtar eller anger GPS-värdet som indikerar om latituden för destinationspunkten är norra eller södra latitud. |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | Hämtar eller anger GPS-longituden för destinationspunkten. |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Hämtar eller anger GPS-longituden för destinationspunkten. |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | Hämtar eller anger GPS-värdet som indikerar om longituden för destinationspunkten är östra eller västra longitud. |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | Hämtar eller anger GPS-värdet som indikerar om longituden för destinationspunkten är östra eller västra longitud. |
| [getGPSDifferential()](#getGPSDifferential--) | Hämtar eller anger ett GPS-värde som indikerar om differentialkorrigering tillämpas på GPS-mottagaren. |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | Hämtar eller anger ett GPS-värde som indikerar om differentialkorrigering tillämpas på GPS-mottagaren. |
| [getGPSImgDirection()](#getGPSImgDirection--) | Hämtar eller anger GPS-riktningen för bilden när den togs. |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller anger GPS-riktningen för bilden när den togs. |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | Hämtar eller anger GPS-referensen för att ange bildens riktning när den tas. |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | Hämtar eller anger GPS-referensen för att ange bildens riktning när den tas. |
| [getGPSDateStamp()](#getGPSDateStamp--) | Hämtar eller anger GPS-teckensträngen som registrerar datum- och tidsinformation i förhållande till UTC (Coordinated Universal Time). |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | Hämtar eller anger GPS-teckensträngen som registrerar datum- och tidsinformation i förhållande till UTC (Coordinated Universal Time). |
| [getGPSLatitude()](#getGPSLatitude--) | Hämtar eller anger GPS-latitud. |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Hämtar eller anger GPS-latitud. |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | Hämtar eller anger om GPS-latituden är norra eller södra latitud. |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | Hämtar eller anger om GPS-latituden är norra eller södra latitud. |
| [getGPSLongitude()](#getGPSLongitude--) | Hämtar eller anger GPS-longitud. |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Hämtar eller anger GPS-longitud. |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | Hämtar eller anger om GPS-longituden är östra eller västra longitud. |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | Hämtar eller anger om GPS-longituden är östra eller västra longitud. |
| [getGPSMapDatum()](#getGPSMapDatum--) | Hämtar eller anger GPS-geodetiska undersökningsdata som används av GPS-mottagaren. |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | Hämtar eller anger GPS-geodetiska undersökningsdata som används av GPS-mottagaren. |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | Hämtar eller anger GPS-mätningsläget. |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | Hämtar eller anger GPS-mätningsläget. |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | Hämtar eller anger GPS-teckensträngen som registrerar namnet på metoden som används för positionsbestämning. |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | Hämtar eller anger GPS-teckensträngen som registrerar namnet på metoden som används för positionsbestämning. |
| [getGPSSatellites()](#getGPSSatellites--) | Hämtar eller anger GPS-satelliterna som används för mätningar. |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | Hämtar eller anger GPS-satelliterna som används för mätningar. |
| [getGPSSpeed()](#getGPSSpeed--) | Hämtar eller anger hastigheten för GPS-mottagarens rörelse. |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller anger hastigheten för GPS-mottagarens rörelse. |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | Hämtar eller anger enheten som används för att uttrycka GPS-mottagarens rörelseshastighet. |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | Hämtar eller anger enheten som används för att uttrycka GPS-mottagarens rörelseshastighet. |
| [getGPSStatus()](#getGPSStatus--) | Hämtar eller anger statusen för GPS-mottagaren när bilden registreras. |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | Hämtar eller anger statusen för GPS-mottagaren när bilden registreras. |
| [getGPSTimestamp()](#getGPSTimestamp--) | Hämtar eller anger GPS-tiden som UTC (Coordinated Universal Time). |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.imaging.fileformats.tiff.TiffRational---) | Hämtar eller anger GPS-tiden som UTC (Coordinated Universal Time). |
| [getGPSTrack()](#getGPSTrack--) | Hämtar eller ställer in riktning för GPS-mottagarens rörelse. |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | Hämtar eller ställer in riktning för GPS-mottagarens rörelse. |
| [getGPSTrackRef()](#getGPSTrackRef--) | Hämtar eller ställer in referensen för att ange riktning för GPS-mottagarens rörelse. |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | Hämtar eller ställer in referensen för att ange riktning för GPS-mottagarens rörelse. |
| [getGPSVersionID()](#getGPSVersionID--) | Hämtar eller ställer in GPS-versionens identifierare. |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | Hämtar eller ställer in GPS-versionens identifierare. |
| [getGainControl()](#getGainControl--) | Hämtar eller ställer in graden av total bildförstärkningsjustering. |
| [setGainControl(int value)](#setGainControl-int-) | Hämtar eller ställer in graden av total bildförstärkningsjustering. |
| [getGamma()](#getGamma--) | Hämtar eller ställer in gamma. |
| [setGamma(TiffRational value)](#setGamma-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller ställer in gamma. |
| [getISOSpeed()](#getISOSpeed--) | Hämtar eller ställer in ISO-hastighet |
| [setISOSpeed(long value)](#setISOSpeed-long-) | Hämtar eller ställer in ISO-hastighet |
| [getISOSpeedValue()](#getISOSpeedValue--) | Hämtar ISO-hastighetsvärdet. |
| [setISOSpeedValue(long value)](#setISOSpeedValue-long-) | Ställer in ISO-hastighetsvärdet. |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | Hämtar eller ställer in ISO-hastighetslatitud yyy-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232. |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | Hämtar eller ställer in ISO-hastighetslatitud yyy-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232. |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | Hämtar eller ställer in ISO-hastighetslatitud zzz-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232. |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | Hämtar eller ställer in ISO-hastighetslatitud zzz-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232. |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | Hämtar eller ställer in den fotografiska känsligheten. |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | Hämtar eller ställer in den fotografiska känsligheten. |
| [getImageUniqueID()](#getImageUniqueID--) | Hämtar eller ställer in bildens unika identifierare. |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | Hämtar eller ställer in bildens unika identifierare. |
| [getLensMake()](#getLensMake--) | Hämtar eller ställer in linsens tillverkare. |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | Hämtar eller ställer in linsens tillverkare. |
| [getLensModel()](#getLensModel--) | Hämtar eller ställer in linsmodellen. |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | Hämtar eller ställer in linsmodellen. |
| [getLensSerialNumber()](#getLensSerialNumber--) | Hämtar eller ställer in linsens serienummer. |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | Hämtar eller ställer in linsens serienummer. |
| [getLensSpecification()](#getLensSpecification--) | Hämtar eller ställer in linsens specifikation |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.imaging.fileformats.tiff.TiffRational---) | Hämtar eller ställer in linsens specifikation |
| [getLightSource()](#getLightSource--) | Hämtar eller ställer in ljuskällan. |
| [setLightSource(int value)](#setLightSource-int-) | Hämtar eller ställer in ljuskällan. |
| [getMakerNoteData()](#getMakerNoteData--) | Hämtar tillverkarens noteringsdata. |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | Hämtar eller ställer in tillverkarens rånoteringsdata. |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | Hämtar eller ställer in tillverkarens rånoteringsdata. |
| [getMakerNotes()](#getMakerNotes--) | Hämtar tillverkarens noteringar. |
| [getMaxApertureValue()](#getMaxApertureValue--) | Hämtar eller ställer in maximalt bländarvärde. |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller ställer in maximalt bländarvärde. |
| [getMeteringMode()](#getMeteringMode--) | Hämtar eller ställer in mätarläget. |
| [setMeteringMode(int value)](#setMeteringMode-int-) | Hämtar eller ställer in mätarläget. |
| [getOECF()](#getOECF--) | Hämtar eller ställer in den optoelektriska konverteringsfunktionen (OECF) enligt ISO 14524. |
| [setOECF(byte[] value)](#setOECF-byte---) | Hämtar eller ställer in den optoelektriska konverteringsfunktionen (OECF) enligt ISO 14524. |
| [getOrientation()](#getOrientation--) | Hämtar orienteringen [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation). |
| [setOrientation(int value)](#setOrientation-int-) | Ställer in orienteringen [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation). |
| [getPixelXDimension()](#getPixelXDimension--) | Hämtar eller anger pixel x-dimensionen. |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | Hämtar eller anger pixel x-dimensionen. |
| [getPixelYDimension()](#getPixelYDimension--) | Hämtar eller anger pixel y-dimensionen. |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | Hämtar eller anger pixel y-dimensionen. |
| [getProperties()](#getProperties--) | Hämtar eller anger alla EXIF-taggar (inklusive vanliga och GPS-taggar). |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Hämtar eller anger alla EXIF-taggar (inklusive vanliga och GPS-taggar). |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | Hämtar eller anger det rekommenderade exponeringsindexet. |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | Hämtar eller anger det rekommenderade exponeringsindexet. |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | Hämtar eller anger den relaterade ljudfilen. |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | Hämtar eller anger den relaterade ljudfilen. |
| [getSaturation()](#getSaturation--) | Hämtar eller anger mättnaden. |
| [setSaturation(int value)](#setSaturation-int-) | Hämtar eller anger mättnaden. |
| [getSceneCaptureType()](#getSceneCaptureType--) | Hämtar eller anger scenfångsttypen. |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | Hämtar eller anger scenfångsttypen. |
| [getSceneType()](#getSceneType--) | Hämtar eller anger scen-typen. |
| [setSceneType(byte value)](#setSceneType-byte-) | Hämtar eller anger scen-typen. |
| [getSensingMethod()](#getSensingMethod--) | Hämtar eller anger avkänningsmetoden. |
| [setSensingMethod(int value)](#setSensingMethod-int-) | Hämtar eller anger avkänningsmetoden. |
| [getSensitivityType()](#getSensitivityType--) | Hämtar eller anger känslighetstypen. |
| [setSensitivityType(int value)](#setSensitivityType-int-) | Hämtar eller anger känslighetstypen. |
| [getSharpness()](#getSharpness--) | Hämtar eller anger skärpan. |
| [setSharpness(int value)](#setSharpness-int-) | Hämtar eller anger skärpan. |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | Hämtar eller anger slutartidsvärdet. |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Hämtar eller anger slutartidsvärdet. |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | Hämtar eller anger det spatiala frekvenssvaret. |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | Hämtar eller anger det spatiala frekvenssvaret. |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | Hämtar eller anger den spektrala känsligheten. |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | Hämtar eller anger den spektrala känsligheten. |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | Hämtar standardutgångskänsligheten |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | Sätter standardutgångskänsligheten |
| [getSubjectArea()](#getSubjectArea--) | Hämtar eller anger ämnesområdet. |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | Hämtar eller anger ämnesområdet. |
| [getSubjectDistance()](#getSubjectDistance--) | Hämtar eller anger avståndet till motivet. |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hämtar eller anger avståndet till motivet. |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | Hämtar eller anger avståndsområdet för motivet. |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | Hämtar eller anger avståndsområdet för motivet. |
| [getSubjectLocation()](#getSubjectLocation--) | Hämtar eller anger motivets plats. |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | Hämtar eller anger motivets plats. |
| [getSubsecTime()](#getSubsecTime--) | Hämtar eller anger bråkdelen av sekunder för DateTime-taggen. |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | Hämtar eller anger bråkdelen av sekunder för DateTime-taggen. |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | Hämtar eller anger bråkdelen av sekunder för DateTimeDigitized-taggen. |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | Hämtar eller anger bråkdelen av sekunder för DateTimeDigitized-taggen. |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | Hämtar eller anger bråkdelen av sekunder för DateTimeOriginal-taggen. |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | Hämtar eller anger bråkdelen av sekunder för DateTimeOriginal-taggen. |
| [getUserComment()](#getUserComment--) | Hämtar eller anger användarkommentaren. |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | Hämtar eller anger användarkommentaren. |
| [getWhiteBalance()](#getWhiteBalance--) | Hämtar eller anger vitbalansen. |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | Hämtar eller anger vitbalansen. |
| [getWhitePoint()](#getWhitePoint--) | Hämtar eller anger kromatiken för bildens vitpunkt. |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.imaging.fileformats.tiff.TiffRational---) | Hämtar eller anger kromatiken för bildens vitpunkt. |
| [getCommonTags()](#getCommonTags--) | Hämtar eller anger taggar, som tillhör den gemensamma sektionen. |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Hämtar eller anger taggar, som tillhör den gemensamma sektionen. |
| [getExifTags()](#getExifTags--) | Hämtar eller anger taggar som endast tillhör EXIF-sektionen. |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Hämtar eller anger taggar som endast tillhör EXIF-sektionen. |
| [getGPSTags()](#getGPSTags--) | Hämtar eller anger taggar, som endast tillhör GPS-sektionen. |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Hämtar eller anger taggar, som endast tillhör GPS-sektionen. |
| [getThumbnail()](#getThumbnail--) | Hämtar miniatyrbilden. |
| [setThumbnail(RasterImage value)](#setThumbnail-com.aspose.imaging.RasterImage-) | Anger miniatyrbilden. |
| [getXResolutionInt()](#getXResolutionInt--) | Hämtar x-upplösningen. |
| [setXResolution(int value)](#setXResolution-int-) | Anger x-upplösningen. |
| [getYResolutionInt()](#getYResolutionInt--) | Hämtar y-upplösningen. |
| [setYResolution(int value)](#setYResolution-int-) | Anger y-upplösningen. |
| [removeTag(int tagId)](#removeTag-int-) | Ta bort tagg från behållare |
| [getTagValue(int key)](#getTagValue-int-) | Hämtar taggvärdet. |

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


Initierar en ny instans av klassen `ExifData`.

### ExifData(TiffDataType[] exifdata) {#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] exifdata)
```


Initierar en ny instans av klassen `ExifData` med data från en array.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Array av EXIF-taggar tillsammans med gemensamma och GPS-taggar. |

### ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Initierar en ny instans av klassen `ExifData` med data från en array.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | De gemensamma taggarna. |
| exifTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | EXIF-taggarna. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | GPS-taggarna. |

### ExifData(ExifData exifdata) {#ExifData-com.aspose.imaging.exif.ExifData-}
```
public ExifData(ExifData exifdata)
```


Initierar en ny instans av klassen [ExifData](../../com.aspose.imaging.exif/exifdata) med data från en array.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| exifdata | [ExifData](../../com.aspose.imaging.exif/exifdata) | Array av EXIF-taggar tillsammans med gemensamma och GPS-taggar. |

### ExifData(byte[] binaryData) {#ExifData-byte---}
```
public ExifData(byte[] binaryData)
```


Initierar en ny instans av klassen [ExifData](../../com.aspose.imaging.exif/exifdata).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| binaryData | byte[] | Den binära datan. |

### isBigEndian() {#isBigEndian--}
```
public boolean isBigEndian()
```


Hämtar eller anger ett värde som indikerar om EXIF-data i strömmen som skapats från är big endian.

Värde: `true` om EXIF-data‑strömmen som den skapades från är big endian; annars `false`.

**Returns:**
boolean
### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


Hämtar eller anger ett värde som indikerar om EXIF-data i strömmen som skapats från är big endian.

Värde: `true` om EXIF-data‑strömmen som den skapades från är big endian; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getMake() {#getMake--}
```
public final String getMake()
```


Hämtar tillverkaren av inspelningsutrustningen.

Värde: Tillverkaren av inspelningsutrustningen.

**Returns:**
java.lang.String - tillverkaren av inspelningsutrustningen.
### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


Anger tillverkaren av inspelningsutrustningen.

Värde: Tillverkaren av inspelningsutrustningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | tillverkaren av inspelningsutrustningen. |

### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


Hämtar eller anger bländarvärdet.

Värde: Bländarvärdet.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


Hämtar eller anger bländarvärdet.

Värde: Bländarvärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


Hämtar eller anger kamerahusets serienummer.

Värde: Kroppens serienummer.

**Returns:**
java.lang.String
### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


Hämtar eller anger kamerahusets serienummer.

Värde: Kroppens serienummer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


Hämtar eller anger ljusstyrkevärdet.

Värde: Ljusstyrkevärdet.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


Hämtar eller anger ljusstyrkevärdet.

Värde: Ljusstyrkevärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


Hämtar eller anger CFA-mönstret.

Value: CFA-mönstret.

**Returns:**
byte[]
### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


Hämtar eller anger CFA-mönstret.

Value: CFA-mönstret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


Hämtar eller anger kamerans ägarnamn

Value: Namnet på kamerans ägare.

**Returns:**
java.lang.String
### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


Hämtar eller anger kamerans ägarnamn

Value: Namnet på kamerans ägare.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getColorSpace() {#getColorSpace--}
```
public int getColorSpace()
```


Hämtar eller anger färgrymden.

Value: Färgrymden.

**Returns:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


Hämtar eller anger färgrymden.

Value: Färgrymden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


Hämtar eller anger komponentkonfigurationen.

Value: Komponentkonfigurationen.

**Returns:**
byte[]
### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


Hämtar eller anger komponentkonfigurationen.

Value: Komponentkonfigurationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


Hämtar eller anger komprimerade bitar per pixel.

Value: Komprimerade bitar per pixel.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


Hämtar eller anger komprimerade bitar per pixel.

Value: Komprimerade bitar per pixel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getContrast() {#getContrast--}
```
public int getContrast()
```


Hämtar eller anger kontrasten.

Value: Kontrasten.

**Returns:**
int
### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


Hämtar eller anger kontrasten.

Value: Kontrasten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


Hämtar eller anger anpassad återgivning.

Value: Anpassad rendering.

**Returns:**
int
### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


Hämtar eller anger anpassad återgivning.

Value: Anpassad rendering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


Hämtar eller anger datum och tid för digitalisering.

Value: Datum och tid för digitalisering.

**Returns:**
java.lang.String
### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


Hämtar eller anger datum och tid för digitalisering.

Value: Datum och tid för digitalisering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


Hämtar eller anger originalets datum och tid.

Value: Ursprungligt datum och tid.

**Returns:**
java.lang.String
### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


Hämtar eller anger originalets datum och tid.

Value: Ursprungligt datum och tid.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


Hämtar eller anger beskrivning av enhetens inställningar.

Value: Beskrivning av enhetsinställning.

**Returns:**
byte[]
### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


Hämtar eller anger beskrivning av enhetens inställningar.

Value: Beskrivning av enhetsinställning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


Hämtar eller anger digital zoomförhållande.

Value: Digitalt zoomförhållande.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


Hämtar eller anger digital zoomförhållande.

Value: Digitalt zoomförhållande.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


Hämtar eller anger EXIF-versionen.

Value: EXIF-versionen.

**Returns:**
byte[]
### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


Hämtar eller anger EXIF-versionen.

Value: EXIF-versionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


Hämtar eller anger exponeringskompensationsvärdet.

Value: Exponeringskompensationsvärdet.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


Hämtar eller anger exponeringskompensationsvärdet.

Value: Exponeringskompensationsvärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


Hämtar eller anger exponeringsindex.

Value: Exponeringsindexet.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


Hämtar eller anger exponeringsindex.

Value: Exponeringsindexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


Hämtar eller anger exponeringsläge.

Value: Exponeringsläget.

**Returns:**
int
### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


Hämtar eller anger exponeringsläge.

Value: Exponeringsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


Hämtar eller anger exponeringsprogram.

Value: Exponeringsprogrammet.

**Returns:**
int
### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


Hämtar eller anger exponeringsprogram.

Value: Exponeringsprogrammet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


Hämtar eller anger exponeringstid.

Value: Exponeringstiden.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


Hämtar eller anger exponeringstid.

Value: Exponeringstiden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


Hämtar eller anger F‑numret.

Value: F-talet.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFNumber(TiffRational value) {#setFNumber-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


Hämtar eller anger F‑numret.

Value: F-talet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


Hämtar eller anger filkällans typ.

Value: Filkälltyp.

**Returns:**
byte
### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


Hämtar eller anger filkällans typ.

Value: Filkälltyp.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getFlash() {#getFlash--}
```
public int getFlash()
```


Hämtar eller anger blixten.

Value: Blixten.

**Returns:**
int
### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


Hämtar eller anger blixten.

Value: Blixten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


Hämtar eller anger blixtenergi.

Value: Blixtenergi.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


Hämtar eller anger blixtenergi.

Value: Blixtenergi.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


Hämtar eller anger blixt‑pix‑version.

Value: Flash-pix-version.

**Returns:**
byte[]
### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


Hämtar eller anger blixt‑pix‑version.

Value: Flash-pix-version.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


Hämtar eller anger brännvidden.

Value: Fokallängden.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


Hämtar eller anger brännvidden.

Value: Fokallängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


Hämtar eller anger brännvidden i 35 mm film.

Value: Fokallängd i 35 mm-film.

**Returns:**
int
### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


Hämtar eller anger brännvidden i 35 mm film.

Value: Fokallängd i 35 mm-film.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


Hämtar eller anger upplösningsenhet för fokalplanet.

Value: Upplösningsenhet för fokalplanet.

**Returns:**
int
### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


Hämtar eller anger upplösningsenhet för fokalplanet.

Value: Upplösningsenhet för fokalplanet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


Hämtar eller anger fokalplanets X‑upplösning.

Värde: Fokalplanets x-upplösning.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


Hämtar eller anger fokalplanets X‑upplösning.

Värde: Fokalplanets x-upplösning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


Hämtar eller anger fokalplanets Y‑upplösning.

Värde: Fokalplanets y-upplösning.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


Hämtar eller anger fokalplanets Y‑upplösning.

Värde: Fokalplanets y-upplösning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


Hämtar eller anger GPS‑höjd.

Värde: GPS-höjden.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


Hämtar eller anger GPS‑höjd.

Värde: GPS-höjden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


Hämtar eller anger GPS‑höjden som referenshöjd.

Värde: GPS-höjden som används som referenshöjd.

**Returns:**
byte
### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


Hämtar eller anger GPS‑höjden som referenshöjd.

Värde: GPS-höjden som används som referenshöjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


Hämtar eller anger GPS‑områdesinformation.

Värde: GPS-områdesinformation.

**Returns:**
byte[]
### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


Hämtar eller anger GPS‑områdesinformation.

Värde: GPS-områdesinformation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


Hämtar eller anger GPS DOP (dataprecisionsgrad).

Värde: GPS DOP (dataprecisionsgrad).

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


Hämtar eller anger GPS DOP (dataprecisionsgrad).

Värde: GPS DOP (dataprecisionsgrad).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


Hämtar eller anger GPS-bäring mot destinationspunkten.

Värde: GPS-riktningen till destinationspunkten.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


Hämtar eller anger GPS-bäring mot destinationspunkten.

Värde: GPS-riktningen till destinationspunkten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


Hämtar eller anger GPS-referensen som används för att ge bäringen mot destinationspunkten.

Värde: GPS-referensen som används för att ange riktningen till destinationspunkten.

**Returns:**
java.lang.String
### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


Hämtar eller anger GPS-referensen som används för att ge bäringen mot destinationspunkten.

Värde: GPS-referensen som används för att ange riktningen till destinationspunkten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


Hämtar eller anger GPS-avståndet till destinationspunkten.

Värde: GPS-avståndet till destinationspunkten.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


Hämtar eller anger GPS-avståndet till destinationspunkten.

Värde: GPS-avståndet till destinationspunkten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


Hämtar eller anger GPS-enheten som används för att uttrycka avståndet till destinationspunkten.

Värde: GPS-enheten som används för att uttrycka avståndet till destinationspunkten.

**Returns:**
java.lang.String
### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


Hämtar eller anger GPS-enheten som används för att uttrycka avståndet till destinationspunkten.

Värde: GPS-enheten som används för att uttrycka avståndet till destinationspunkten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


Hämtar eller anger GPS-latituden för destinationspunkten.

Värde: GPS-latituden för destinationspunkten.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


Hämtar eller anger GPS-latituden för destinationspunkten.

Värde: GPS-latituden för destinationspunkten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


Hämtar eller anger GPS-värdet som indikerar om latituden för destinationspunkten är norra eller södra latitud.

Värde: GPS-värdet som indikerar om latituden för destinationspunkten är nordlig eller sydlig latitud.

**Returns:**
java.lang.String
### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


Hämtar eller anger GPS-värdet som indikerar om latituden för destinationspunkten är norra eller södra latitud.

Värde: GPS-värdet som indikerar om latituden för destinationspunkten är nordlig eller sydlig latitud.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


Hämtar eller anger GPS-longituden för destinationspunkten.

Värde: GPS-longituden för destinationspunkten.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


Hämtar eller anger GPS-longituden för destinationspunkten.

Värde: GPS-longituden för destinationspunkten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


Hämtar eller anger GPS-värdet som indikerar om longituden för destinationspunkten är östra eller västra longitud.

Värde: GPS-värdet som indikerar om longituden för destinationspunkten är östlig eller västlig longitud.

**Returns:**
java.lang.String
### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


Hämtar eller anger GPS-värdet som indikerar om longituden för destinationspunkten är östra eller västra longitud.

Värde: GPS-värdet som indikerar om longituden för destinationspunkten är östlig eller västlig longitud.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


Hämtar eller anger ett GPS-värde som indikerar om differentialkorrigering tillämpas på GPS-mottagaren.

Värde: GPS-värdet som indikerar om differentialkorrigering tillämpas på GPS-mottagaren.

**Returns:**
int
### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


Hämtar eller anger ett GPS-värde som indikerar om differentialkorrigering tillämpas på GPS-mottagaren.

Värde: GPS-värdet som indikerar om differentialkorrigering tillämpas på GPS-mottagaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


Hämtar eller anger GPS-riktningen för bilden när den togs.

Värde: GPS-riktningen för bilden när den togs.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


Hämtar eller anger GPS-riktningen för bilden när den togs.

Värde: GPS-riktningen för bilden när den togs.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


Hämtar eller anger GPS-referensen för att ange bildens riktning när den tas.

Värde: GPS-referensen för att ange bildens riktning när den tas.

**Returns:**
java.lang.String
### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


Hämtar eller anger GPS-referensen för att ange bildens riktning när den tas.

Värde: GPS-referensen för att ange bildens riktning när den tas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


Hämtar eller anger GPS-teckensträngen som registrerar datum- och tidsinformation i förhållande till UTC (Coordinated Universal Time).

Värde: GPS-teckensträngen som registrerar datum- och tidsinformation i förhållande till UTC (Coordinated Universal Time).

**Returns:**
java.lang.String
### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


Hämtar eller anger GPS-teckensträngen som registrerar datum- och tidsinformation i förhållande till UTC (Coordinated Universal Time).

Värde: GPS-teckensträngen som registrerar datum- och tidsinformation i förhållande till UTC (Coordinated Universal Time).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


Hämtar eller anger GPS-latitud.

Värde: GPS-latituden.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


Hämtar eller anger GPS-latitud.

Värde: GPS-latituden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


Hämtar eller anger om GPS-latituden är norra eller södra latitud.

Värde: GPS-latituden är nordlig eller sydlig latitud.

**Returns:**
java.lang.String
### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


Hämtar eller anger om GPS-latituden är norra eller södra latitud.

Värde: GPS-latituden är nordlig eller sydlig latitud.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


Hämtar eller anger GPS-longitud.

Värde: GPS-longituden.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


Hämtar eller anger GPS-longitud.

Värde: GPS-longituden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


Hämtar eller anger om GPS-longituden är östra eller västra longitud.

Värde: GPS-longituden är östlig eller västlig longitud.

**Returns:**
java.lang.String
### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


Hämtar eller anger om GPS-longituden är östra eller västra longitud.

Värde: GPS-longituden är östlig eller västlig longitud.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


Hämtar eller anger GPS-geodetiska undersökningsdata som används av GPS-mottagaren.

Värde: GPS-geodetiska kartdata som används av GPS-mottagaren.

**Returns:**
java.lang.String
### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


Hämtar eller anger GPS-geodetiska undersökningsdata som används av GPS-mottagaren.

Värde: GPS-geodetiska kartdata som används av GPS-mottagaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


Hämtar eller anger GPS-mätningsläget.

Värde: GPS-mätningsläget.

**Returns:**
java.lang.String
### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


Hämtar eller anger GPS-mätningsläget.

Värde: GPS-mätningsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


Hämtar eller anger GPS-teckensträngen som registrerar namnet på metoden som används för positionsbestämning.

Värde: GPS-teckensträngen som registrerar namnet på metoden som används för positionsbestämning.

**Returns:**
byte[]
### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


Hämtar eller anger GPS-teckensträngen som registrerar namnet på metoden som används för positionsbestämning.

Värde: GPS-teckensträngen som registrerar namnet på metoden som används för positionsbestämning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


Hämtar eller anger GPS-satelliterna som används för mätningar.

Värde: GPS-satelliterna som används för mätningar.

**Returns:**
java.lang.String
### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


Hämtar eller anger GPS-satelliterna som används för mätningar.

Värde: GPS-satelliterna som används för mätningar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


Hämtar eller anger hastigheten för GPS-mottagarens rörelse.

Värde: Hastigheten för GPS-mottagarens rörelse.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


Hämtar eller anger hastigheten för GPS-mottagarens rörelse.

Värde: Hastigheten för GPS-mottagarens rörelse.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


Hämtar eller anger enheten som används för att uttrycka GPS-mottagarens rörelseshastighet.

Värde: Enheten som används för att uttrycka GPS-mottagarens rörelseshastighet.

**Returns:**
java.lang.String
### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


Hämtar eller anger enheten som används för att uttrycka GPS-mottagarens rörelseshastighet.

Värde: Enheten som används för att uttrycka GPS-mottagarens rörelseshastighet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


Hämtar eller anger statusen för GPS-mottagaren när bilden registreras.

Värde: Statusen för GPS-mottagaren när bilden spelas in.

**Returns:**
java.lang.String
### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


Hämtar eller anger statusen för GPS-mottagaren när bilden registreras.

Värde: Statusen för GPS-mottagaren när bilden spelas in.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


Hämtar eller anger GPS-tiden som UTC (Coordinated Universal Time).

Värde: GPS-tiden som UTC (Coordinated Universal Time).

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


Hämtar eller anger GPS-tiden som UTC (Coordinated Universal Time).

Värde: GPS-tiden som UTC (Coordinated Universal Time).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


Hämtar eller ställer in riktning för GPS-mottagarens rörelse.

Värde: Riktningen för GPS-mottagarens rörelse.

**Returns:**
java.lang.String
### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


Hämtar eller ställer in riktning för GPS-mottagarens rörelse.

Värde: Riktningen för GPS-mottagarens rörelse.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


Hämtar eller ställer in referensen för att ange riktning för GPS-mottagarens rörelse.

Värde: Referensen för att ange riktningen för GPS-mottagarens rörelse.

**Returns:**
java.lang.String
### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


Hämtar eller ställer in referensen för att ange riktning för GPS-mottagarens rörelse.

Värde: Referensen för att ange riktningen för GPS-mottagarens rörelse.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


Hämtar eller ställer in GPS-versionens identifierare.

Värde: GPS-versionens identifierare.

**Returns:**
byte[]
### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


Hämtar eller ställer in GPS-versionens identifierare.

Värde: GPS-versionens identifierare.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


Hämtar eller ställer in graden av total bildförstärkningsjustering.

Värde: Graden av den övergripande bildförstärkningsjusteringen.

**Returns:**
int
### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


Hämtar eller ställer in graden av total bildförstärkningsjustering.

Värde: Graden av den övergripande bildförstärkningsjusteringen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


Hämtar eller ställer in gamma.

Värde: Gamma-värdet.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGamma(TiffRational value) {#setGamma-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


Hämtar eller ställer in gamma.

Värde: Gamma-värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


Hämtar eller ställer in ISO-hastighet

Värde: ISO-hastigheten.

**Returns:**
long
### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


Hämtar eller ställer in ISO-hastighet

Värde: ISO-hastigheten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### getISOSpeedValue() {#getISOSpeedValue--}
```
public final long getISOSpeedValue()
```


Hämtar ISO-hastighetsvärdet.

Värde: ISO-hastighetsvärdet.

**Returns:**
long - ISO-hastighetsvärdet.
### setISOSpeedValue(long value) {#setISOSpeedValue-long-}
```
public final void setISOSpeedValue(long value)
```


Ställer in ISO-hastighetsvärdet.

Värde: ISO-hastighetsvärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | ISO-hastighetsvärdet. |

### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


Hämtar eller ställer in ISO-hastighetslatitud yyy-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232.

Värde: ISO-hastighetslatitud yyy-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232.

Denna tagg får inte registreras utan ISOSpeed och ISOSpeedLatitudeZZZ.

**Returns:**
long
### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


Hämtar eller ställer in ISO-hastighetslatitud yyy-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232.

Värde: ISO-hastighetslatitud yyy-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232.

Denna tagg får inte registreras utan ISOSpeed och ISOSpeedLatitudeZZZ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


Hämtar eller ställer in ISO-hastighetslatitud zzz-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232.

Värde: ISO-hastighetslatitud zzz-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232.

Denna tagg får inte registreras utan ISOSpeed och ISOSpeedLatitudeYYY.

**Returns:**
long
### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


Hämtar eller ställer in ISO-hastighetslatitud zzz-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232.

Värde: ISO-hastighetslatitud zzz-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232.

Denna tagg får inte registreras utan ISOSpeed och ISOSpeedLatitudeYYY.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


Hämtar eller ställer in den fotografiska känsligheten.

Värde: Den fotografiska känsligheten.

**Returns:**
long
### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


Hämtar eller ställer in den fotografiska känsligheten.

Värde: Den fotografiska känsligheten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


Hämtar eller ställer in bildens unika identifierare.

Värde: Bildens unika identifierare.

**Returns:**
java.lang.String
### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


Hämtar eller ställer in bildens unika identifierare.

Värde: Bildens unika identifierare.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


Hämtar eller ställer in linsens tillverkare.

Värde: Objektivtillverkaren.

**Returns:**
java.lang.String
### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


Hämtar eller ställer in linsens tillverkare.

Värde: Objektivtillverkaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


Hämtar eller ställer in linsmodellen.

Värde: Objektivmodellen.

**Returns:**
java.lang.String
### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


Hämtar eller ställer in linsmodellen.

Värde: Objektivmodellen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


Hämtar eller ställer in linsens serienummer.

Värde: Objektivets serienummer.

**Returns:**
java.lang.String
### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


Hämtar eller ställer in linsens serienummer.

Värde: Objektivets serienummer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


Hämtar eller ställer in linsens specifikation

Värde: Objektivspecifikationen.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


Hämtar eller ställer in linsens specifikation

Värde: Objektivspecifikationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


Hämtar eller ställer in ljuskällan.

Värde: Ljuskällan.

**Returns:**
int
### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


Hämtar eller ställer in ljuskällan.

Värde: Ljuskällan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


Hämtar tillverkarens noteringsdata.

Värde: Maker‑noteringsdata.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


Hämtar eller ställer in tillverkarens rånoteringsdata.

Värde: Rå maker‑noteringsdata.

**Returns:**
byte[]
### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


Hämtar eller ställer in tillverkarens rånoteringsdata.

Värde: Rå maker‑noteringsdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


Hämtar tillverkarens noteringar.

Värde: Maker‑noteringar.

**Returns:**
com.aspose.imaging.exif.MakerNote[] - maker‑noteringarna.

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


Hämtar eller ställer in maximalt bländarvärde.

Värde: Det maximala bländarvärdet.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


Hämtar eller ställer in maximalt bländarvärde.

Värde: Det maximala bländarvärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


Hämtar eller ställer in mätarläget.

Värde: Mätarläget.

**Returns:**
int
### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


Hämtar eller ställer in mätarläget.

Värde: Mätarläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


Hämtar eller ställer in den optoelektriska konverteringsfunktionen (OECF) enligt ISO 14524.

Värde: Den opto‑elektriska konverteringsfunktionen (OECF) enligt ISO 14524.

**Returns:**
byte[]
### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


Hämtar eller ställer in den optoelektriska konverteringsfunktionen (OECF) enligt ISO 14524.

Värde: Den opto‑elektriska konverteringsfunktionen (OECF) enligt ISO 14524.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Hämtar orienteringen [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation).

Värde: Orienteringen.

**Returns:**
int - orienteringen.
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Ställer in orienteringen [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation).

Värde: Orienteringen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | orienteringen. |

### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


Hämtar eller anger pixel x-dimensionen.

Värde: Pixelns x‑dimension.

**Returns:**
long
### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


Hämtar eller anger pixel x-dimensionen.

Värde: Pixelns x‑dimension.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


Hämtar eller anger pixel y-dimensionen.

Värde: Pixelns y‑dimension.

**Returns:**
long
### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


Hämtar eller anger pixel y-dimensionen.

Värde: Pixelns y‑dimension.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


Hämtar eller anger alla EXIF-taggar (inklusive vanliga och GPS-taggar).

Värde: EXIF‑taggarna (inklusive vanliga och GPS‑taggar).

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setProperties(TiffDataType[] value) {#setProperties-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


Hämtar eller anger alla EXIF-taggar (inklusive vanliga och GPS-taggar).

Värde: EXIF‑taggarna (inklusive vanliga och GPS‑taggar).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


Hämtar eller anger det rekommenderade exponeringsindexet.

Värde: Rekommenderat exponeringsindex.

**Returns:**
long
### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


Hämtar eller anger det rekommenderade exponeringsindexet.

Värde: Rekommenderat exponeringsindex.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


Hämtar eller anger den relaterade ljudfilen.

Värde: Den relaterade ljudfilen.

**Returns:**
java.lang.String
### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


Hämtar eller anger den relaterade ljudfilen.

Värde: Den relaterade ljudfilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


Hämtar eller anger mättnaden.

Värde: Mättnaden.

**Returns:**
int
### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


Hämtar eller anger mättnaden.

Värde: Mättnaden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


Hämtar eller anger scenfångsttypen.

Värde: Typen av scenupptagning.

**Returns:**
int
### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


Hämtar eller anger scenfångsttypen.

Värde: Typen av scenupptagning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


Hämtar eller anger scen-typen.

Värde: Typen av scenen.

**Returns:**
byte
### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


Hämtar eller anger scen-typen.

Värde: Typen av scenen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


Hämtar eller anger avkänningsmetoden.

Värde: Sensormetoden.

**Returns:**
int
### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


Hämtar eller anger avkänningsmetoden.

Värde: Sensormetoden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


Hämtar eller anger känslighetstypen.

Värde: Typen av känsligheten.

**Returns:**
int
### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


Hämtar eller anger känslighetstypen.

Värde: Typen av känsligheten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


Hämtar eller anger skärpan.

Värde: Skärpan.

**Returns:**
int
### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


Hämtar eller anger skärpan.

Värde: Skärpan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


Hämtar eller anger slutartidsvärdet.

Värde: Slutartidsvärdet.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


Hämtar eller anger slutartidsvärdet.

Värde: Slutartidsvärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


Hämtar eller anger det spatiala frekvenssvaret.

Värde: Det rumsliga frekvenssvaret.

**Returns:**
byte[]
### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


Hämtar eller anger det spatiala frekvenssvaret.

Värde: Det rumsliga frekvenssvaret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


Hämtar eller anger den spektrala känsligheten.

Värde: Spektralkänsligheten.

**Returns:**
java.lang.String
### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


Hämtar eller anger den spektrala känsligheten.

Värde: Spektralkänsligheten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


Hämtar standardutgångskänsligheten

Värde: Den standardutgångskänsligheten.

**Returns:**
long
### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


Sätter standardutgångskänsligheten

Värde: Den standardutgångskänsligheten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


Hämtar eller anger ämnesområdet.

Värde: Ämnesområdet.

**Returns:**
int[]
### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


Hämtar eller anger ämnesområdet.

Värde: Ämnesområdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


Hämtar eller anger avståndet till motivet.

Värde: Ämnesavståndet.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


Hämtar eller anger avståndet till motivet.

Värde: Ämnesavståndet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


Hämtar eller anger avståndsområdet för motivet.

Värde: Intervallet för ämnesavståndet.

**Returns:**
int
### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


Hämtar eller anger avståndsområdet för motivet.

Värde: Intervallet för ämnesavståndet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


Hämtar eller anger motivets plats.

Värde: Ämnesplatsen.

**Returns:**
int[]
### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


Hämtar eller anger motivets plats.

Värde: Ämnesplatsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


Hämtar eller anger bråkdelen av sekunder för DateTime-taggen.

Värde: Bråkdelen av sekunder för DateTime-taggen.

**Returns:**
java.lang.String
### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


Hämtar eller anger bråkdelen av sekunder för DateTime-taggen.

Värde: Bråkdelen av sekunder för DateTime-taggen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


Hämtar eller anger bråkdelen av sekunder för DateTimeDigitized-taggen.

Värde: Bråkdelen av sekunder för DateTimeDigitized-taggen.

**Returns:**
java.lang.String
### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


Hämtar eller anger bråkdelen av sekunder för DateTimeDigitized-taggen.

Värde: Bråkdelen av sekunder för DateTimeDigitized-taggen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


Hämtar eller anger bråkdelen av sekunder för DateTimeOriginal-taggen.

Värde: Bråkdelen av sekunder för DateTimeOriginal-taggen.

**Returns:**
java.lang.String
### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


Hämtar eller anger bråkdelen av sekunder för DateTimeOriginal-taggen.

Värde: Bråkdelen av sekunder för DateTimeOriginal-taggen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


Hämtar eller anger användarkommentaren.

Värde: Användarkommentaren.

**Returns:**
java.lang.String
### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


Hämtar eller anger användarkommentaren.

Värde: Användarkommentaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


Hämtar eller anger vitbalansen.

Värde: Vitbalansen.

**Returns:**
int
### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


Hämtar eller anger vitbalansen.

Värde: Vitbalansen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


Hämtar eller anger kromatiken för bildens vitpunkt.

Värde: Bildens vita punkts kromaticitet.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


Hämtar eller anger kromatiken för bildens vitpunkt.

Värde: Bildens vita punkts kromaticitet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


Hämtar eller anger taggar som tillhör den gemensamma sektionen. Detta gäller endast jpeg-bilder, i tiff-format används tiffOptions istället.

Värde: Taggar för den gemensamma sektionen.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


Hämtar eller anger taggar som tillhör den gemensamma sektionen. Detta gäller endast jpeg-bilder, i tiff-format används tiffOptions istället.

Värde: Taggar för den gemensamma sektionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


Hämtar eller anger taggar som endast tillhör EXIF-sektionen.

Värde: Taggar för EXIF-sektionen.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


Hämtar eller anger taggar som endast tillhör EXIF-sektionen.

Värde: Taggar för EXIF-sektionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


Hämtar eller anger taggar, som endast tillhör GPS-sektionen.

Värde: GPS-taggarna.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


Hämtar eller anger taggar, som endast tillhör GPS-sektionen.

Värde: GPS-taggarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getThumbnail() {#getThumbnail--}
```
public final RasterImage getThumbnail()
```


Hämtar miniatyrbilden.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the thumbnail image.
### setThumbnail(RasterImage value) {#setThumbnail-com.aspose.imaging.RasterImage-}
```
public final void setThumbnail(RasterImage value)
```


Anger miniatyrbilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RasterImage](../../com.aspose.imaging/rasterimage) | Miniatyrbilden. |

### getXResolutionInt() {#getXResolutionInt--}
```
public final int getXResolutionInt()
```


Hämtar x-upplösningen.

Värde: x-upplösningen.

**Returns:**
int - x-upplösningen.
### setXResolution(int value) {#setXResolution-int-}
```
public final void setXResolution(int value)
```


Anger x-upplösningen.

Värde: x-upplösningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | x-upplösningen. |

### getYResolutionInt() {#getYResolutionInt--}
```
public final int getYResolutionInt()
```


Hämtar y-upplösningen.

Värde: y-upplösningen.

**Returns:**
int - y-upplösningen.
### setYResolution(int value) {#setYResolution-int-}
```
public final void setYResolution(int value)
```


Anger y-upplösningen.

Värde: y-upplösningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | y-upplösningen. |

### removeTag(int tagId) {#removeTag-int-}
```
public void removeTag(int tagId)
```


Ta bort tagg från behållare

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagId | int | Taggidentifieraren att ta bort. |

### getTagValue(int key) {#getTagValue-int-}
```
public final TiffDataType getTagValue(int key)
```


Hämtar taggvärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key | int | Taggnyckeln [ExifProperties](../../com.aspose.imaging.exif/exifproperties). |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - The TiffDataType
