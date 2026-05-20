---
title: "ExifData"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Conteneur de données EXIF."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.exif/exifdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.exif.TiffDataTypeController](../../com.aspose.imaging.exif/tiffdatatypecontroller)

**All Implemented Interfaces:**
[com.aspose.imaging.metadata.IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)
```
public class ExifData extends TiffDataTypeController implements IImageMetadataFormat
```

Conteneur de données EXIF.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ExifData()](#ExifData--) | Initialise une nouvelle instance de la classe `ExifData`. |
| [ExifData(TiffDataType[] exifdata)](#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Initialise une nouvelle instance de la classe `ExifData` avec des données provenant du tableau. |
| [ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---) | Initialise une nouvelle instance de la classe `ExifData` avec des données provenant du tableau. |
| [ExifData(ExifData exifdata)](#ExifData-com.aspose.imaging.exif.ExifData-) | Initialise une nouvelle instance de la classe [ExifData](../../com.aspose.imaging.exif/exifdata) avec des données provenant du tableau. |
| [ExifData(byte[] binaryData)](#ExifData-byte---) | Initialise une nouvelle instance de la classe [ExifData](../../com.aspose.imaging.exif/exifdata). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [isBigEndian()](#isBigEndian--) | Obtient ou définit une valeur indiquant si les données EXIF du flux sont en big endian. |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | Obtient ou définit une valeur indiquant si les données EXIF du flux sont en big endian. |
| [getMake()](#getMake--) | Obtient le fabricant de l'équipement d'enregistrement. |
| [setMake(String value)](#setMake-java.lang.String-) | Définit le fabricant de l'équipement d'enregistrement. |
| [getApertureValue()](#getApertureValue--) | Obtient ou définit la valeur de l'ouverture. |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit la valeur de l'ouverture. |
| [getBodySerialNumber()](#getBodySerialNumber--) | Obtient ou définit le numéro de série du boîtier de l'appareil. |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | Obtient ou définit le numéro de série du boîtier de l'appareil. |
| [getBrightnessValue()](#getBrightnessValue--) | Obtient ou définit la valeur de la luminosité. |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Obtient ou définit la valeur de la luminosité. |
| [getCFAPattern()](#getCFAPattern--) | Obtient ou définit le motif CFA. |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | Obtient ou définit le motif CFA. |
| [getCameraOwnerName()](#getCameraOwnerName--) | Obtient ou définit le nom du propriétaire de l'appareil |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | Obtient ou définit le nom du propriétaire de l'appareil |
| [getColorSpace()](#getColorSpace--) | Obtient ou définit l'espace colorimétrique. |
| [setColorSpace(int value)](#setColorSpace-int-) | Obtient ou définit l'espace colorimétrique. |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | Obtient ou définit la configuration des composants. |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | Obtient ou définit la configuration des composants. |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | Obtient ou définit les bits compressés par pixel. |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit les bits compressés par pixel. |
| [getContrast()](#getContrast--) | Obtient ou définit le contraste. |
| [setContrast(int value)](#setContrast-int-) | Obtient ou définit le contraste. |
| [getCustomRendered()](#getCustomRendered--) | Obtient ou définit le rendu personnalisé. |
| [setCustomRendered(int value)](#setCustomRendered-int-) | Obtient ou définit le rendu personnalisé. |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | Obtient ou définit la date et l'heure de numérisation. |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | Obtient ou définit la date et l'heure de numérisation. |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | Obtient ou définit la date et l'heure d'origine. |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | Obtient ou définit la date et l'heure d'origine. |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | Obtient ou définit la description des paramètres de l'appareil |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | Obtient ou définit la description des paramètres de l'appareil |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | Obtient ou définit le rapport de zoom numérique. |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit le rapport de zoom numérique. |
| [getExifVersion()](#getExifVersion--) | Obtient ou définit la version EXIF. |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | Obtient ou définit la version EXIF. |
| [getExposureBiasValue()](#getExposureBiasValue--) | Obtient ou définit la valeur du biais d'exposition. |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Obtient ou définit la valeur du biais d'exposition. |
| [getExposureIndex()](#getExposureIndex--) | Obtient ou définit l'indice d'exposition. |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit l'indice d'exposition. |
| [getExposureMode()](#getExposureMode--) | Obtient ou définit le mode d'exposition. |
| [setExposureMode(int value)](#setExposureMode-int-) | Obtient ou définit le mode d'exposition. |
| [getExposureProgram()](#getExposureProgram--) | Obtient ou définit le programme d'exposition. |
| [setExposureProgram(int value)](#setExposureProgram-int-) | Obtient ou définit le programme d'exposition. |
| [getExposureTime()](#getExposureTime--) | Obtient ou définit le temps d'exposition. |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit le temps d'exposition. |
| [getFNumber()](#getFNumber--) | Obtient ou définit le nombre F. |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit le nombre F. |
| [getFileSource()](#getFileSource--) | Obtient ou définit le type de source du fichier. |
| [setFileSource(byte value)](#setFileSource-byte-) | Obtient ou définit le type de source du fichier. |
| [getFlash()](#getFlash--) | Obtient ou définit le flash. |
| [setFlash(int value)](#setFlash-int-) | Obtient ou définit le flash. |
| [getFlashEnergy()](#getFlashEnergy--) | Obtient ou définit l'énergie du flash. |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit l'énergie du flash. |
| [getFlashpixVersion()](#getFlashpixVersion--) | Obtient ou définit la version du pix du flash. |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | Obtient ou définit la version du pix du flash. |
| [getFocalLength()](#getFocalLength--) | Obtient ou définit la distance focale. |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit la distance focale. |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | Obtient ou définit la distance focale en film 35 mm. |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | Obtient ou définit la distance focale en film 35 mm. |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | Obtient ou définit l'unité de résolution du plan focal. |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | Obtient ou définit l'unité de résolution du plan focal. |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | Obtient ou définit la résolution X du plan focal. |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit la résolution X du plan focal. |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | Obtient ou définit la résolution Y du plan focal. |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit la résolution Y du plan focal. |
| [getGPSAltitude()](#getGPSAltitude--) | Obtient ou définit l'altitude GPS. |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit l'altitude GPS. |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | Obtient ou définit l'altitude GPS utilisée comme altitude de référence. |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | Obtient ou définit l'altitude GPS utilisée comme altitude de référence. |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | Obtient ou définit les informations de zone GPS. |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | Obtient ou définit les informations de zone GPS. |
| [getGPSDOP()](#getGPSDOP--) | Obtient ou définit le GPS DOP (degré de précision des données). |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit le GPS DOP (degré de précision des données). |
| [getGPSDestBearing()](#getGPSDestBearing--) | Obtient ou définit l'azimut GPS vers le point de destination. |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit l'azimut GPS vers le point de destination. |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | Obtient ou définit la référence GPS utilisée pour fournir l'azimut vers le point de destination. |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | Obtient ou définit la référence GPS utilisée pour fournir l'azimut vers le point de destination. |
| [getGPSDestDistance()](#getGPSDestDistance--) | Obtient ou définit la distance GPS jusqu'au point de destination. |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit la distance GPS jusqu'au point de destination. |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | Obtient ou définit l'unité GPS utilisée pour exprimer la distance jusqu'au point de destination. |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | Obtient ou définit l'unité GPS utilisée pour exprimer la distance jusqu'au point de destination. |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | Obtient ou définit la latitude GPS du point de destination. |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Obtient ou définit la latitude GPS du point de destination. |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | Obtient ou définit la valeur GPS indiquant si la latitude du point de destination est une latitude nord ou sud. |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | Obtient ou définit la valeur GPS indiquant si la latitude du point de destination est une latitude nord ou sud. |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | Obtient ou définit la longitude GPS du point de destination. |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Obtient ou définit la longitude GPS du point de destination. |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | Obtient ou définit la valeur GPS indiquant si la longitude du point de destination est une longitude est ou ouest. |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | Obtient ou définit la valeur GPS indiquant si la longitude du point de destination est une longitude est ou ouest. |
| [getGPSDifferential()](#getGPSDifferential--) | Obtient ou définit une valeur GPS indiquant si une correction différentielle est appliquée au récepteur GPS. |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | Obtient ou définit une valeur GPS indiquant si une correction différentielle est appliquée au récepteur GPS. |
| [getGPSImgDirection()](#getGPSImgDirection--) | Obtient ou définit la direction GPS de l'image lorsqu'elle a été capturée. |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit la direction GPS de l'image lorsqu'elle a été capturée. |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | Obtient ou définit la référence GPS pour fournir la direction de l'image lorsqu'elle est capturée. |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | Obtient ou définit la référence GPS pour fournir la direction de l'image lorsqu'elle est capturée. |
| [getGPSDateStamp()](#getGPSDateStamp--) | Obtient ou définit la chaîne de caractères GPS enregistrant les informations de date et d'heure relatives à l'UTC (Temps Universel Coordonné). |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | Obtient ou définit la chaîne de caractères GPS enregistrant les informations de date et d'heure relatives à l'UTC (Temps Universel Coordonné). |
| [getGPSLatitude()](#getGPSLatitude--) | Obtient ou définit la latitude GPS. |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Obtient ou définit la latitude GPS. |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | Obtient ou définit si la latitude GPS est une latitude nord ou sud. |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | Obtient ou définit si la latitude GPS est une latitude nord ou sud. |
| [getGPSLongitude()](#getGPSLongitude--) | Obtient ou définit la longitude GPS. |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Obtient ou définit la longitude GPS. |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | Obtient ou définit si la longitude GPS est une longitude est ou ouest. |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | Obtient ou définit si la longitude GPS est une longitude est ou ouest. |
| [getGPSMapDatum()](#getGPSMapDatum--) | Obtient ou définit les données d'arpentage géodésique GPS utilisées par le récepteur GPS. |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | Obtient ou définit les données d'arpentage géodésique GPS utilisées par le récepteur GPS. |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | Obtient ou définit le mode de mesure GPS. |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | Obtient ou définit le mode de mesure GPS. |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | Obtient ou définit la chaîne de caractères GPS enregistrant le nom de la méthode utilisée pour la localisation. |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | Obtient ou définit la chaîne de caractères GPS enregistrant le nom de la méthode utilisée pour la localisation. |
| [getGPSSatellites()](#getGPSSatellites--) | Obtient ou définit les satellites GPS utilisés pour les mesures. |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | Obtient ou définit les satellites GPS utilisés pour les mesures. |
| [getGPSSpeed()](#getGPSSpeed--) | Obtient ou définit la vitesse du mouvement du récepteur GPS. |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit la vitesse du mouvement du récepteur GPS. |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | Obtient ou définit l'unité utilisée pour exprimer la vitesse de déplacement du récepteur GPS. |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | Obtient ou définit l'unité utilisée pour exprimer la vitesse de déplacement du récepteur GPS. |
| [getGPSStatus()](#getGPSStatus--) | Obtient ou définit l'état du récepteur GPS lorsque l'image est enregistrée. |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | Obtient ou définit l'état du récepteur GPS lorsque l'image est enregistrée. |
| [getGPSTimestamp()](#getGPSTimestamp--) | Obtient ou définit l'heure GPS en UTC (Temps Universel Coordonné). |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.imaging.fileformats.tiff.TiffRational---) | Obtient ou définit l'heure GPS en UTC (Temps Universel Coordonné). |
| [getGPSTrack()](#getGPSTrack--) | Obtient ou définit la direction du mouvement du récepteur GPS. |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | Obtient ou définit la direction du mouvement du récepteur GPS. |
| [getGPSTrackRef()](#getGPSTrackRef--) | Obtient ou définit la référence pour donner la direction du mouvement du récepteur GPS. |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | Obtient ou définit la référence pour donner la direction du mouvement du récepteur GPS. |
| [getGPSVersionID()](#getGPSVersionID--) | Obtient ou définit l'identifiant de version du GPS. |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | Obtient ou définit l'identifiant de version du GPS. |
| [getGainControl()](#getGainControl--) | Obtient ou définit le degré d'ajustement global du gain de l'image. |
| [setGainControl(int value)](#setGainControl-int-) | Obtient ou définit le degré d'ajustement global du gain de l'image. |
| [getGamma()](#getGamma--) | Obtient ou définit le gamma. |
| [setGamma(TiffRational value)](#setGamma-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit le gamma. |
| [getISOSpeed()](#getISOSpeed--) | Obtient ou définit la vitesse ISO |
| [setISOSpeed(long value)](#setISOSpeed-long-) | Obtient ou définit la vitesse ISO |
| [getISOSpeedValue()](#getISOSpeedValue--) | Obtient la valeur de vitesse ISO. |
| [setISOSpeedValue(long value)](#setISOSpeedValue-long-) | Définit la valeur de vitesse ISO. |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | Obtient ou définit la valeur de latitude yyy de vitesse ISO d'un appareil photo ou dispositif d'entrée telle que définie dans la norme ISO 12232. |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | Obtient ou définit la valeur de latitude yyy de vitesse ISO d'un appareil photo ou dispositif d'entrée telle que définie dans la norme ISO 12232. |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | Obtient ou définit la valeur de latitude zzz de vitesse ISO d'un appareil photo ou dispositif d'entrée telle que définie dans la norme ISO 12232. |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | Obtient ou définit la valeur de latitude zzz de vitesse ISO d'un appareil photo ou dispositif d'entrée telle que définie dans la norme ISO 12232. |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | Obtient ou définit la sensibilité photographique. |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | Obtient ou définit la sensibilité photographique. |
| [getImageUniqueID()](#getImageUniqueID--) | Obtient ou définit l'identifiant unique de l'image. |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | Obtient ou définit l'identifiant unique de l'image. |
| [getLensMake()](#getLensMake--) | Obtient ou définit le fabricant de l'objectif. |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | Obtient ou définit le fabricant de l'objectif. |
| [getLensModel()](#getLensModel--) | Obtient ou définit le modèle de l'objectif. |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | Obtient ou définit le modèle de l'objectif. |
| [getLensSerialNumber()](#getLensSerialNumber--) | Obtient ou définit le numéro de série de l'objectif. |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | Obtient ou définit le numéro de série de l'objectif. |
| [getLensSpecification()](#getLensSpecification--) | Obtient ou définit les spécifications de l'objectif |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.imaging.fileformats.tiff.TiffRational---) | Obtient ou définit les spécifications de l'objectif |
| [getLightSource()](#getLightSource--) | Obtient ou définit la source de lumière. |
| [setLightSource(int value)](#setLightSource-int-) | Obtient ou définit la source de lumière. |
| [getMakerNoteData()](#getMakerNoteData--) | Obtient les données de note du fabricant. |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | Obtient ou définit les données brutes de la note du fabricant. |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | Obtient ou définit les données brutes de la note du fabricant. |
| [getMakerNotes()](#getMakerNotes--) | Obtient les notes du fabricant. |
| [getMaxApertureValue()](#getMaxApertureValue--) | Obtient ou définit la valeur d'ouverture maximale. |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit la valeur d'ouverture maximale. |
| [getMeteringMode()](#getMeteringMode--) | Obtient ou définit le mode de mesure. |
| [setMeteringMode(int value)](#setMeteringMode-int-) | Obtient ou définit le mode de mesure. |
| [getOECF()](#getOECF--) | Obtient ou définit la fonction de conversion opto-électrique (OECF) spécifiée dans la norme ISO 14524. |
| [setOECF(byte[] value)](#setOECF-byte---) | Obtient ou définit la fonction de conversion opto-électrique (OECF) spécifiée dans la norme ISO 14524. |
| [getOrientation()](#getOrientation--) | Obtient l'orientation [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation). |
| [setOrientation(int value)](#setOrientation-int-) | Définit l'orientation [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation). |
| [getPixelXDimension()](#getPixelXDimension--) | Obtient ou définit la dimension x du pixel. |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | Obtient ou définit la dimension x du pixel. |
| [getPixelYDimension()](#getPixelYDimension--) | Obtient ou définit la dimension y du pixel. |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | Obtient ou définit la dimension y du pixel. |
| [getProperties()](#getProperties--) | Obtient ou définit toutes les balises EXIF (y compris les balises courantes et GPS). |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Obtient ou définit toutes les balises EXIF (y compris les balises courantes et GPS). |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | Obtient ou définit l'indice d'exposition recommandé. |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | Obtient ou définit l'indice d'exposition recommandé. |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | Obtient ou définit le fichier audio associé. |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | Obtient ou définit le fichier audio associé. |
| [getSaturation()](#getSaturation--) | Obtient ou définit la saturation. |
| [setSaturation(int value)](#setSaturation-int-) | Obtient ou définit la saturation. |
| [getSceneCaptureType()](#getSceneCaptureType--) | Obtient ou définit le type de capture de scène. |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | Obtient ou définit le type de capture de scène. |
| [getSceneType()](#getSceneType--) | Obtient ou définit le type de scène. |
| [setSceneType(byte value)](#setSceneType-byte-) | Obtient ou définit le type de scène. |
| [getSensingMethod()](#getSensingMethod--) | Obtient ou définit la méthode de détection. |
| [setSensingMethod(int value)](#setSensingMethod-int-) | Obtient ou définit la méthode de détection. |
| [getSensitivityType()](#getSensitivityType--) | Obtient ou définit le type de sensibilité. |
| [setSensitivityType(int value)](#setSensitivityType-int-) | Obtient ou définit le type de sensibilité. |
| [getSharpness()](#getSharpness--) | Obtient ou définit la netteté. |
| [setSharpness(int value)](#setSharpness-int-) | Obtient ou définit la netteté. |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | Obtient ou définit la valeur de la vitesse d'obturation. |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Obtient ou définit la valeur de la vitesse d'obturation. |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | Obtient ou définit la réponse en fréquence spatiale. |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | Obtient ou définit la réponse en fréquence spatiale. |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | Obtient ou définit la sensibilité spectrale. |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | Obtient ou définit la sensibilité spectrale. |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | Obtient la sensibilité de sortie standard |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | Définit la sensibilité de sortie standard |
| [getSubjectArea()](#getSubjectArea--) | Obtient ou définit la zone du sujet. |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | Obtient ou définit la zone du sujet. |
| [getSubjectDistance()](#getSubjectDistance--) | Obtient ou définit la distance du sujet. |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtient ou définit la distance du sujet. |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | Obtient ou définit la plage de distance du sujet. |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | Obtient ou définit la plage de distance du sujet. |
| [getSubjectLocation()](#getSubjectLocation--) | Obtient ou définit l'emplacement du sujet. |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | Obtient ou définit l'emplacement du sujet. |
| [getSubsecTime()](#getSubsecTime--) | Obtient ou définit les fractions de seconde pour la balise DateTime. |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | Obtient ou définit les fractions de seconde pour la balise DateTime. |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | Obtient ou définit les fractions de seconde pour la balise DateTimeDigitized. |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | Obtient ou définit les fractions de seconde pour la balise DateTimeDigitized. |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | Obtient ou définit les fractions de seconde pour la balise DateTimeOriginal. |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | Obtient ou définit les fractions de seconde pour la balise DateTimeOriginal. |
| [getUserComment()](#getUserComment--) | Obtient ou définit le commentaire de l'utilisateur. |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | Obtient ou définit le commentaire de l'utilisateur. |
| [getWhiteBalance()](#getWhiteBalance--) | Obtient ou définit la balance des blancs. |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | Obtient ou définit la balance des blancs. |
| [getWhitePoint()](#getWhitePoint--) | Obtient ou définit la chromaticité du point blanc de l'image. |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.imaging.fileformats.tiff.TiffRational---) | Obtient ou définit la chromaticité du point blanc de l'image. |
| [getCommonTags()](#getCommonTags--) | Obtient ou définit les balises qui appartiennent à la section commune. |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Obtient ou définit les balises qui appartiennent à la section commune. |
| [getExifTags()](#getExifTags--) | Obtient ou définit les balises qui appartiennent uniquement à la section EXIF. |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Obtient ou définit les balises qui appartiennent uniquement à la section EXIF. |
| [getGPSTags()](#getGPSTags--) | Obtient ou définit les balises qui appartiennent uniquement à la section GPS. |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Obtient ou définit les balises qui appartiennent uniquement à la section GPS. |
| [getThumbnail()](#getThumbnail--) | Obtient l'image miniature. |
| [setThumbnail(RasterImage value)](#setThumbnail-com.aspose.imaging.RasterImage-) | Définit l'image miniature. |
| [getXResolutionInt()](#getXResolutionInt--) | Obtient la résolution x. |
| [setXResolution(int value)](#setXResolution-int-) | Définit la résolution x. |
| [getYResolutionInt()](#getYResolutionInt--) | Obtient la résolution y. |
| [setYResolution(int value)](#setYResolution-int-) | Définit la résolution y. |
| [removeTag(int tagId)](#removeTag-int-) | Supprimer la balise du conteneur |
| [getTagValue(int key)](#getTagValue-int-) | Obtient la valeur de la balise. |

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


Initialise une nouvelle instance de la classe `ExifData`.

### ExifData(TiffDataType[] exifdata) {#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] exifdata)
```


Initialise une nouvelle instance de la classe `ExifData` avec des données provenant du tableau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Tableau de balises EXIF avec les balises communes et GPS. |

### ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Initialise une nouvelle instance de la classe `ExifData` avec des données provenant du tableau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Les balises communes. |
| exifTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Les balises EXIF. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Les balises GPS. |

### ExifData(ExifData exifdata) {#ExifData-com.aspose.imaging.exif.ExifData-}
```
public ExifData(ExifData exifdata)
```


Initialise une nouvelle instance de la classe [ExifData](../../com.aspose.imaging.exif/exifdata) avec des données provenant du tableau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| exifdata | [ExifData](../../com.aspose.imaging.exif/exifdata) | Tableau de balises EXIF avec les balises communes et GPS. |

### ExifData(byte[] binaryData) {#ExifData-byte---}
```
public ExifData(byte[] binaryData)
```


Initialise une nouvelle instance de la classe [ExifData](../../com.aspose.imaging.exif/exifdata).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| binaryData | byte[] | Les données binaires. |

### isBigEndian() {#isBigEndian--}
```
public boolean isBigEndian()
```


Obtient ou définit une valeur indiquant si les données EXIF du flux sont en big endian.

Valeur: `true` si le flux de données EXIF à partir duquel il a été créé est en big endian; sinon, `false`.

**Returns:**
boolean
### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


Obtient ou définit une valeur indiquant si les données EXIF du flux sont en big endian.

Valeur: `true` si le flux de données EXIF à partir duquel il a été créé est en big endian; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getMake() {#getMake--}
```
public final String getMake()
```


Obtient le fabricant de l'équipement d'enregistrement.

Valeur: Le fabricant de l'équipement d'enregistrement.

**Returns:**
java.lang.String - le fabricant de l'équipement d'enregistrement.
### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


Définit le fabricant de l'équipement d'enregistrement.

Valeur: Le fabricant de l'équipement d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | le fabricant de l'équipement d'enregistrement. |

### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


Obtient ou définit la valeur de l'ouverture.

Valeur: La valeur d'ouverture.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


Obtient ou définit la valeur de l'ouverture.

Valeur: La valeur d'ouverture.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


Obtient ou définit le numéro de série du boîtier de l'appareil.

Valeur: Le numéro de série du corps.

**Returns:**
java.lang.String
### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


Obtient ou définit le numéro de série du boîtier de l'appareil.

Valeur: Le numéro de série du corps.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


Obtient ou définit la valeur de la luminosité.

Valeur: La valeur de luminosité.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


Obtient ou définit la valeur de la luminosité.

Valeur: La valeur de luminosité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


Obtient ou définit le motif CFA.

Valeur: Le motif CFA.

**Returns:**
byte[]
### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


Obtient ou définit le motif CFA.

Valeur: Le motif CFA.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


Obtient ou définit le nom du propriétaire de l'appareil

Valeur: Le nom du propriétaire de l’appareil photo.

**Returns:**
java.lang.String
### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


Obtient ou définit le nom du propriétaire de l'appareil

Valeur: Le nom du propriétaire de l’appareil photo.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getColorSpace() {#getColorSpace--}
```
public int getColorSpace()
```


Obtient ou définit l'espace colorimétrique.

Valeur: L’espace colorimétrique.

**Returns:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


Obtient ou définit l'espace colorimétrique.

Valeur: L’espace colorimétrique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


Obtient ou définit la configuration des composants.

Valeur: La configuration des composants.

**Returns:**
byte[]
### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


Obtient ou définit la configuration des composants.

Valeur: La configuration des composants.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


Obtient ou définit les bits compressés par pixel.

Valeur: Les bits compressés par pixel.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


Obtient ou définit les bits compressés par pixel.

Valeur: Les bits compressés par pixel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getContrast() {#getContrast--}
```
public int getContrast()
```


Obtient ou définit le contraste.

Valeur: Le contraste.

**Returns:**
int
### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


Obtient ou définit le contraste.

Valeur: Le contraste.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


Obtient ou définit le rendu personnalisé.

Valeur: Le rendu personnalisé.

**Returns:**
int
### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


Obtient ou définit le rendu personnalisé.

Valeur: Le rendu personnalisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


Obtient ou définit la date et l'heure de numérisation.

Valeur: La date et l’heure de numérisation.

**Returns:**
java.lang.String
### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


Obtient ou définit la date et l'heure de numérisation.

Valeur: La date et l’heure de numérisation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


Obtient ou définit la date et l'heure d'origine.

Valeur: La date et l’heure d’origine.

**Returns:**
java.lang.String
### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


Obtient ou définit la date et l'heure d'origine.

Valeur: La date et l’heure d’origine.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


Obtient ou définit la description des paramètres de l'appareil

Valeur: La description des réglages de l’appareil.

**Returns:**
byte[]
### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


Obtient ou définit la description des paramètres de l'appareil

Valeur: La description des réglages de l’appareil.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


Obtient ou définit le rapport de zoom numérique.

Valeur: Le rapport de zoom numérique.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


Obtient ou définit le rapport de zoom numérique.

Valeur: Le rapport de zoom numérique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


Obtient ou définit la version EXIF.

Valeur: La version EXIF.

**Returns:**
byte[]
### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


Obtient ou définit la version EXIF.

Valeur: La version EXIF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


Obtient ou définit la valeur du biais d'exposition.

Valeur: La valeur du biais d’exposition.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


Obtient ou définit la valeur du biais d'exposition.

Valeur: La valeur du biais d’exposition.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


Obtient ou définit l'indice d'exposition.

Valeur: L’indice de l’exposition.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


Obtient ou définit l'indice d'exposition.

Valeur: L’indice de l’exposition.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


Obtient ou définit le mode d'exposition.

Valeur: Le mode d’exposition.

**Returns:**
int
### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


Obtient ou définit le mode d'exposition.

Valeur: Le mode d’exposition.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


Obtient ou définit le programme d'exposition.

Valeur: Le programme d’exposition.

**Returns:**
int
### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


Obtient ou définit le programme d'exposition.

Valeur: Le programme d’exposition.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


Obtient ou définit le temps d'exposition.

Valeur: Le temps d’exposition.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


Obtient ou définit le temps d'exposition.

Valeur: Le temps d’exposition.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


Obtient ou définit le nombre F.

Valeur: Le nombre F.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFNumber(TiffRational value) {#setFNumber-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


Obtient ou définit le nombre F.

Valeur: Le nombre F.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


Obtient ou définit le type de source du fichier.

Valeur: Le type de source du fichier.

**Returns:**
byte
### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


Obtient ou définit le type de source du fichier.

Valeur: Le type de source du fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getFlash() {#getFlash--}
```
public int getFlash()
```


Obtient ou définit le flash.

Valeur: Le flash.

**Returns:**
int
### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


Obtient ou définit le flash.

Valeur: Le flash.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


Obtient ou définit l'énergie du flash.

Valeur: L’énergie du flash.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


Obtient ou définit l'énergie du flash.

Valeur: L’énergie du flash.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


Obtient ou définit la version du pix du flash.

Valeur: La version du pix du flash.

**Returns:**
byte[]
### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


Obtient ou définit la version du pix du flash.

Valeur: La version du pix du flash.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


Obtient ou définit la distance focale.

Valeur: La longueur focale.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


Obtient ou définit la distance focale.

Valeur: La longueur focale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


Obtient ou définit la distance focale en film 35 mm.

Valeur: La longueur focale en film 35 mm.

**Returns:**
int
### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


Obtient ou définit la distance focale en film 35 mm.

Valeur: La longueur focale en film 35 mm.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


Obtient ou définit l'unité de résolution du plan focal.

Valeur: L’unité de résolution du plan focal.

**Returns:**
int
### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


Obtient ou définit l'unité de résolution du plan focal.

Valeur: L’unité de résolution du plan focal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


Obtient ou définit la résolution X du plan focal.

Valeur : La résolution x du plan focal.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


Obtient ou définit la résolution X du plan focal.

Valeur : La résolution x du plan focal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


Obtient ou définit la résolution Y du plan focal.

Valeur : La résolution y du plan focal.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


Obtient ou définit la résolution Y du plan focal.

Valeur : La résolution y du plan focal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


Obtient ou définit l'altitude GPS.

Valeur : L'altitude GPS.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


Obtient ou définit l'altitude GPS.

Valeur : L'altitude GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


Obtient ou définit l'altitude GPS utilisée comme altitude de référence.

Valeur : L'altitude GPS utilisée comme altitude de référence.

**Returns:**
byte
### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


Obtient ou définit l'altitude GPS utilisée comme altitude de référence.

Valeur : L'altitude GPS utilisée comme altitude de référence.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


Obtient ou définit les informations de zone GPS.

Valeur : Les informations de zone GPS.

**Returns:**
byte[]
### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


Obtient ou définit les informations de zone GPS.

Valeur : Les informations de zone GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


Obtient ou définit le GPS DOP (degré de précision des données).

Valeur : Le DOP GPS (degré de précision des données).

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


Obtient ou définit le GPS DOP (degré de précision des données).

Valeur : Le DOP GPS (degré de précision des données).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


Obtient ou définit l'azimut GPS vers le point de destination.

Valeur : L'azimut GPS vers le point de destination.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


Obtient ou définit l'azimut GPS vers le point de destination.

Valeur : L'azimut GPS vers le point de destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


Obtient ou définit la référence GPS utilisée pour fournir l'azimut vers le point de destination.

Valeur : La référence GPS utilisée pour fournir l'azimut vers le point de destination.

**Returns:**
java.lang.String
### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


Obtient ou définit la référence GPS utilisée pour fournir l'azimut vers le point de destination.

Valeur : La référence GPS utilisée pour fournir l'azimut vers le point de destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


Obtient ou définit la distance GPS jusqu'au point de destination.

Valeur : La distance GPS au point de destination.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


Obtient ou définit la distance GPS jusqu'au point de destination.

Valeur : La distance GPS au point de destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


Obtient ou définit l'unité GPS utilisée pour exprimer la distance jusqu'au point de destination.

Valeur : L'unité GPS utilisée pour exprimer la distance au point de destination.

**Returns:**
java.lang.String
### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


Obtient ou définit l'unité GPS utilisée pour exprimer la distance jusqu'au point de destination.

Valeur : L'unité GPS utilisée pour exprimer la distance au point de destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


Obtient ou définit la latitude GPS du point de destination.

Valeur : La latitude GPS du point de destination.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


Obtient ou définit la latitude GPS du point de destination.

Valeur : La latitude GPS du point de destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


Obtient ou définit la valeur GPS indiquant si la latitude du point de destination est une latitude nord ou sud.

Valeur : La valeur GPS indiquant si la latitude du point de destination est nord ou sud.

**Returns:**
java.lang.String
### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


Obtient ou définit la valeur GPS indiquant si la latitude du point de destination est une latitude nord ou sud.

Valeur : La valeur GPS indiquant si la latitude du point de destination est nord ou sud.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


Obtient ou définit la longitude GPS du point de destination.

Valeur : La longitude GPS du point de destination.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


Obtient ou définit la longitude GPS du point de destination.

Valeur : La longitude GPS du point de destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


Obtient ou définit la valeur GPS indiquant si la longitude du point de destination est une longitude est ou ouest.

Valeur : La valeur GPS indiquant si la longitude du point de destination est est ou ouest.

**Returns:**
java.lang.String
### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


Obtient ou définit la valeur GPS indiquant si la longitude du point de destination est une longitude est ou ouest.

Valeur : La valeur GPS indiquant si la longitude du point de destination est est ou ouest.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


Obtient ou définit une valeur GPS indiquant si une correction différentielle est appliquée au récepteur GPS.

Valeur : La valeur GPS indiquant si une correction différentielle est appliquée au récepteur GPS.

**Returns:**
int
### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


Obtient ou définit une valeur GPS indiquant si une correction différentielle est appliquée au récepteur GPS.

Valeur : La valeur GPS indiquant si une correction différentielle est appliquée au récepteur GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


Obtient ou définit la direction GPS de l'image lorsqu'elle a été capturée.

Valeur : La direction GPS de l'image lorsqu'elle a été capturée.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


Obtient ou définit la direction GPS de l'image lorsqu'elle a été capturée.

Valeur : La direction GPS de l'image lorsqu'elle a été capturée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


Obtient ou définit la référence GPS pour fournir la direction de l'image lorsqu'elle est capturée.

Valeur : La référence GPS pour fournir la direction de l'image lorsqu'elle est capturée.

**Returns:**
java.lang.String
### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


Obtient ou définit la référence GPS pour fournir la direction de l'image lorsqu'elle est capturée.

Valeur : La référence GPS pour fournir la direction de l'image lorsqu'elle est capturée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


Obtient ou définit la chaîne de caractères GPS enregistrant les informations de date et d'heure relatives à l'UTC (Temps Universel Coordonné).

Valeur : La chaîne de caractères GPS enregistrant les informations de date et d'heure relatives à UTC (Temps Universel Coordonné).

**Returns:**
java.lang.String
### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


Obtient ou définit la chaîne de caractères GPS enregistrant les informations de date et d'heure relatives à l'UTC (Temps Universel Coordonné).

Valeur : La chaîne de caractères GPS enregistrant les informations de date et d'heure relatives à UTC (Temps Universel Coordonné).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


Obtient ou définit la latitude GPS.

Valeur : La latitude GPS.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


Obtient ou définit la latitude GPS.

Valeur : La latitude GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


Obtient ou définit si la latitude GPS est une latitude nord ou sud.

Valeur : La latitude GPS est nord ou sud.

**Returns:**
java.lang.String
### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


Obtient ou définit si la latitude GPS est une latitude nord ou sud.

Valeur : La latitude GPS est nord ou sud.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


Obtient ou définit la longitude GPS.

Valeur : La longitude GPS.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


Obtient ou définit la longitude GPS.

Valeur : La longitude GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


Obtient ou définit si la longitude GPS est une longitude est ou ouest.

Valeur : La longitude GPS est est ou ouest.

**Returns:**
java.lang.String
### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


Obtient ou définit si la longitude GPS est une longitude est ou ouest.

Valeur : La longitude GPS est est ou ouest.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


Obtient ou définit les données d'arpentage géodésique GPS utilisées par le récepteur GPS.

Valeur : Les données de levé géodésique GPS utilisées par le récepteur GPS.

**Returns:**
java.lang.String
### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


Obtient ou définit les données d'arpentage géodésique GPS utilisées par le récepteur GPS.

Valeur : Les données de levé géodésique GPS utilisées par le récepteur GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


Obtient ou définit le mode de mesure GPS.

Valeur : Le mode de mesure GPS.

**Returns:**
java.lang.String
### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


Obtient ou définit le mode de mesure GPS.

Valeur : Le mode de mesure GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


Obtient ou définit la chaîne de caractères GPS enregistrant le nom de la méthode utilisée pour la localisation.

Valeur : La chaîne de caractères GPS enregistrant le nom de la méthode utilisée pour la localisation.

**Returns:**
byte[]
### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


Obtient ou définit la chaîne de caractères GPS enregistrant le nom de la méthode utilisée pour la localisation.

Valeur : La chaîne de caractères GPS enregistrant le nom de la méthode utilisée pour la localisation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


Obtient ou définit les satellites GPS utilisés pour les mesures.

Valeur : Les satellites GPS utilisés pour les mesures.

**Returns:**
java.lang.String
### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


Obtient ou définit les satellites GPS utilisés pour les mesures.

Valeur : Les satellites GPS utilisés pour les mesures.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


Obtient ou définit la vitesse du mouvement du récepteur GPS.

Valeur : La vitesse du mouvement du récepteur GPS.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


Obtient ou définit la vitesse du mouvement du récepteur GPS.

Valeur : La vitesse du mouvement du récepteur GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


Obtient ou définit l'unité utilisée pour exprimer la vitesse de déplacement du récepteur GPS.

Valeur : L'unité utilisée pour exprimer la vitesse du mouvement du récepteur GPS.

**Returns:**
java.lang.String
### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


Obtient ou définit l'unité utilisée pour exprimer la vitesse de déplacement du récepteur GPS.

Valeur : L'unité utilisée pour exprimer la vitesse du mouvement du récepteur GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


Obtient ou définit l'état du récepteur GPS lorsque l'image est enregistrée.

Valeur : L'état du récepteur GPS lorsque l'image est enregistrée.

**Returns:**
java.lang.String
### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


Obtient ou définit l'état du récepteur GPS lorsque l'image est enregistrée.

Valeur : L'état du récepteur GPS lorsque l'image est enregistrée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


Obtient ou définit l'heure GPS en UTC (Temps Universel Coordonné).

Valeur : L'heure GPS en UTC (Temps Universel Coordonné).

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


Obtient ou définit l'heure GPS en UTC (Temps Universel Coordonné).

Valeur : L'heure GPS en UTC (Temps Universel Coordonné).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


Obtient ou définit la direction du mouvement du récepteur GPS.

Valeur : La direction du mouvement du récepteur GPS.

**Returns:**
java.lang.String
### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


Obtient ou définit la direction du mouvement du récepteur GPS.

Valeur : La direction du mouvement du récepteur GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


Obtient ou définit la référence pour donner la direction du mouvement du récepteur GPS.

Valeur : La référence pour donner la direction du mouvement du récepteur GPS.

**Returns:**
java.lang.String
### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


Obtient ou définit la référence pour donner la direction du mouvement du récepteur GPS.

Valeur : La référence pour donner la direction du mouvement du récepteur GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


Obtient ou définit l'identifiant de version du GPS.

Valeur : L'identifiant de version GPS.

**Returns:**
byte[]
### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


Obtient ou définit l'identifiant de version du GPS.

Valeur : L'identifiant de version GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


Obtient ou définit le degré d'ajustement global du gain de l'image.

Valeur : Le degré d'ajustement global du gain de l'image.

**Returns:**
int
### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


Obtient ou définit le degré d'ajustement global du gain de l'image.

Valeur : Le degré d'ajustement global du gain de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


Obtient ou définit le gamma.

Valeur : La valeur gamma.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGamma(TiffRational value) {#setGamma-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


Obtient ou définit le gamma.

Valeur : La valeur gamma.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


Obtient ou définit la vitesse ISO

Valeur : La vitesse ISO.

**Returns:**
long
### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


Obtient ou définit la vitesse ISO

Valeur : La vitesse ISO.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### getISOSpeedValue() {#getISOSpeedValue--}
```
public final long getISOSpeedValue()
```


Obtient la valeur de vitesse ISO.

Valeur : La valeur de vitesse iso.

**Returns:**
long - la valeur de vitesse iso.
### setISOSpeedValue(long value) {#setISOSpeedValue-long-}
```
public final void setISOSpeedValue(long value)
```


Définit la valeur de vitesse ISO.

Valeur : La valeur de vitesse iso.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | la valeur de vitesse iso. |

### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


Obtient ou définit la valeur de latitude yyy de vitesse ISO d'un appareil photo ou dispositif d'entrée telle que définie dans la norme ISO 12232.

Valeur : La valeur de latitude de vitesse ISO yyy d'un appareil photo ou dispositif d'entrée définie dans ISO 12232.

Cette balise ne doit pas être enregistrée sans ISOSpeed et ISOSpeedLatitudeZZZ

**Returns:**
long
### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


Obtient ou définit la valeur de latitude yyy de vitesse ISO d'un appareil photo ou dispositif d'entrée telle que définie dans la norme ISO 12232.

Valeur : La valeur de latitude de vitesse ISO yyy d'un appareil photo ou dispositif d'entrée définie dans ISO 12232.

Cette balise ne doit pas être enregistrée sans ISOSpeed et ISOSpeedLatitudeZZZ

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


Obtient ou définit la valeur de latitude zzz de vitesse ISO d'un appareil photo ou dispositif d'entrée telle que définie dans la norme ISO 12232.

Valeur : La valeur de latitude de vitesse ISO zzz d'un appareil photo ou dispositif d'entrée définie dans ISO 12232.

Cette balise ne doit pas être enregistrée sans ISOSpeed et ISOSpeedLatitudeYYY

**Returns:**
long
### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


Obtient ou définit la valeur de latitude zzz de vitesse ISO d'un appareil photo ou dispositif d'entrée telle que définie dans la norme ISO 12232.

Valeur : La valeur de latitude de vitesse ISO zzz d'un appareil photo ou dispositif d'entrée définie dans ISO 12232.

Cette balise ne doit pas être enregistrée sans ISOSpeed et ISOSpeedLatitudeYYY

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


Obtient ou définit la sensibilité photographique.

Valeur : La sensibilité photographique.

**Returns:**
long
### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


Obtient ou définit la sensibilité photographique.

Valeur : La sensibilité photographique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


Obtient ou définit l'identifiant unique de l'image.

Valeur : L'identifiant unique de l'image.

**Returns:**
java.lang.String
### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


Obtient ou définit l'identifiant unique de l'image.

Valeur : L'identifiant unique de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


Obtient ou définit le fabricant de l'objectif.

Valeur : Le fabricant de l'objectif.

**Returns:**
java.lang.String
### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


Obtient ou définit le fabricant de l'objectif.

Valeur : Le fabricant de l'objectif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


Obtient ou définit le modèle de l'objectif.

Valeur : Le modèle de l'objectif.

**Returns:**
java.lang.String
### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


Obtient ou définit le modèle de l'objectif.

Valeur : Le modèle de l'objectif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


Obtient ou définit le numéro de série de l'objectif.

Valeur : Le numéro de série de l'objectif.

**Returns:**
java.lang.String
### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


Obtient ou définit le numéro de série de l'objectif.

Valeur : Le numéro de série de l'objectif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


Obtient ou définit les spécifications de l'objectif

Valeur : La spécification de l'objectif.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


Obtient ou définit les spécifications de l'objectif

Valeur : La spécification de l'objectif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


Obtient ou définit la source de lumière.

Valeur : La source de lumière.

**Returns:**
int
### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


Obtient ou définit la source de lumière.

Valeur : La source de lumière.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


Obtient les données de note du fabricant.

Valeur : les données de la note du fabricant.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


Obtient ou définit les données brutes de la note du fabricant.

Valeur : les données brutes de la note du fabricant.

**Returns:**
byte[]
### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


Obtient ou définit les données brutes de la note du fabricant.

Valeur : les données brutes de la note du fabricant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


Obtient les notes du fabricant.

Valeur : les notes du fabricant.

**Returns:**
com.aspose.imaging.exif.MakerNote[] - les notes du fabricant.

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


Obtient ou définit la valeur d'ouverture maximale.

Valeur : la valeur maximale de l'ouverture.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


Obtient ou définit la valeur d'ouverture maximale.

Valeur : la valeur maximale de l'ouverture.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


Obtient ou définit le mode de mesure.

Valeur : le mode de mesure.

**Returns:**
int
### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


Obtient ou définit le mode de mesure.

Valeur : le mode de mesure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


Obtient ou définit la fonction de conversion opto-électrique (OECF) spécifiée dans la norme ISO 14524.

Valeur : la fonction de conversion opto-électrique (OECF) spécifiée dans la norme ISO 14524.

**Returns:**
byte[]
### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


Obtient ou définit la fonction de conversion opto-électrique (OECF) spécifiée dans la norme ISO 14524.

Valeur : la fonction de conversion opto-électrique (OECF) spécifiée dans la norme ISO 14524.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Obtient l'orientation [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation).

Valeur : l'orientation.

**Returns:**
int - l'orientation.
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Définit l'orientation [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation).

Valeur : l'orientation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | l'orientation. |

### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


Obtient ou définit la dimension x du pixel.

Valeur : la dimension x du pixel.

**Returns:**
long
### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


Obtient ou définit la dimension x du pixel.

Valeur : la dimension x du pixel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


Obtient ou définit la dimension y du pixel.

Valeur : la dimension y du pixel.

**Returns:**
long
### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


Obtient ou définit la dimension y du pixel.

Valeur : la dimension y du pixel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


Obtient ou définit toutes les balises EXIF (y compris les balises courantes et GPS).

Valeur : les balises EXIF (y compris les balises communes et GPS).

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setProperties(TiffDataType[] value) {#setProperties-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


Obtient ou définit toutes les balises EXIF (y compris les balises courantes et GPS).

Valeur : les balises EXIF (y compris les balises communes et GPS).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


Obtient ou définit l'indice d'exposition recommandé.

Valeur : l'indice d'exposition recommandé.

**Returns:**
long
### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


Obtient ou définit l'indice d'exposition recommandé.

Valeur : l'indice d'exposition recommandé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


Obtient ou définit le fichier audio associé.

Valeur : le fichier audio associé.

**Returns:**
java.lang.String
### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


Obtient ou définit le fichier audio associé.

Valeur : le fichier audio associé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


Obtient ou définit la saturation.

Valeur : la saturation.

**Returns:**
int
### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


Obtient ou définit la saturation.

Valeur : la saturation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


Obtient ou définit le type de capture de scène.

Valeur : le type de capture de la scène.

**Returns:**
int
### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


Obtient ou définit le type de capture de scène.

Valeur : le type de capture de la scène.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


Obtient ou définit le type de scène.

Valeur : le type de la scène.

**Returns:**
byte
### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


Obtient ou définit le type de scène.

Valeur : le type de la scène.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


Obtient ou définit la méthode de détection.

Valeur : la méthode de détection.

**Returns:**
int
### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


Obtient ou définit la méthode de détection.

Valeur : la méthode de détection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


Obtient ou définit le type de sensibilité.

Valeur : le type de sensibilité.

**Returns:**
int
### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


Obtient ou définit le type de sensibilité.

Valeur : le type de sensibilité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


Obtient ou définit la netteté.

Valeur : la netteté.

**Returns:**
int
### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


Obtient ou définit la netteté.

Valeur : la netteté.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


Obtient ou définit la valeur de la vitesse d'obturation.

Valeur : la valeur de la vitesse d'obturation.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


Obtient ou définit la valeur de la vitesse d'obturation.

Valeur : la valeur de la vitesse d'obturation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


Obtient ou définit la réponse en fréquence spatiale.

Valeur : la réponse en fréquence spatiale.

**Returns:**
byte[]
### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


Obtient ou définit la réponse en fréquence spatiale.

Valeur : la réponse en fréquence spatiale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


Obtient ou définit la sensibilité spectrale.

Valeur : la sensibilité spectrale.

**Returns:**
java.lang.String
### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


Obtient ou définit la sensibilité spectrale.

Valeur : la sensibilité spectrale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


Obtient la sensibilité de sortie standard

Valeur : La sensibilité de sortie standard.

**Returns:**
long
### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


Définit la sensibilité de sortie standard

Valeur : La sensibilité de sortie standard.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


Obtient ou définit la zone du sujet.

Valeur : La zone du sujet.

**Returns:**
int[]
### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


Obtient ou définit la zone du sujet.

Valeur : La zone du sujet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


Obtient ou définit la distance du sujet.

Valeur : La distance du sujet.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


Obtient ou définit la distance du sujet.

Valeur : La distance du sujet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


Obtient ou définit la plage de distance du sujet.

Valeur : La plage de distance du sujet.

**Returns:**
int
### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


Obtient ou définit la plage de distance du sujet.

Valeur : La plage de distance du sujet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


Obtient ou définit l'emplacement du sujet.

Valeur : L'emplacement du sujet.

**Returns:**
int[]
### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


Obtient ou définit l'emplacement du sujet.

Valeur : L'emplacement du sujet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


Obtient ou définit les fractions de seconde pour la balise DateTime.

Valeur : Les fractions de seconde pour la balise DateTime.

**Returns:**
java.lang.String
### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


Obtient ou définit les fractions de seconde pour la balise DateTime.

Valeur : Les fractions de seconde pour la balise DateTime.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


Obtient ou définit les fractions de seconde pour la balise DateTimeDigitized.

Valeur : Les fractions de seconde pour la balise DateTimeDigitized.

**Returns:**
java.lang.String
### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


Obtient ou définit les fractions de seconde pour la balise DateTimeDigitized.

Valeur : Les fractions de seconde pour la balise DateTimeDigitized.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


Obtient ou définit les fractions de seconde pour la balise DateTimeOriginal.

Valeur : Les fractions de seconde pour la balise DateTimeOriginal.

**Returns:**
java.lang.String
### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


Obtient ou définit les fractions de seconde pour la balise DateTimeOriginal.

Valeur : Les fractions de seconde pour la balise DateTimeOriginal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


Obtient ou définit le commentaire de l'utilisateur.

Valeur : Le commentaire de l'utilisateur.

**Returns:**
java.lang.String
### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


Obtient ou définit le commentaire de l'utilisateur.

Valeur : Le commentaire de l'utilisateur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


Obtient ou définit la balance des blancs.

Valeur : La balance des blancs.

**Returns:**
int
### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


Obtient ou définit la balance des blancs.

Valeur : La balance des blancs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


Obtient ou définit la chromaticité du point blanc de l'image.

Valeur : La chromaticité du point blanc de l'image.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


Obtient ou définit la chromaticité du point blanc de l'image.

Valeur : La chromaticité du point blanc de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


Obtient ou définit les balises qui appartiennent à la section commune. Cela s'applique uniquement aux images jpeg, le format tiff utilise tiffOptions à la place.

Valeur : Les balises de la section commune.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


Obtient ou définit les balises qui appartiennent à la section commune. Cela s'applique uniquement aux images jpeg, le format tiff utilise tiffOptions à la place.

Valeur : Les balises de la section commune.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


Obtient ou définit les balises qui appartiennent uniquement à la section EXIF.

Valeur : Les balises de la section EXIF.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


Obtient ou définit les balises qui appartiennent uniquement à la section EXIF.

Valeur : Les balises de la section EXIF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


Obtient ou définit les balises qui appartiennent uniquement à la section GPS.

Valeur : Les balises GPS.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


Obtient ou définit les balises qui appartiennent uniquement à la section GPS.

Valeur : Les balises GPS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getThumbnail() {#getThumbnail--}
```
public final RasterImage getThumbnail()
```


Obtient l'image miniature.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the thumbnail image.
### setThumbnail(RasterImage value) {#setThumbnail-com.aspose.imaging.RasterImage-}
```
public final void setThumbnail(RasterImage value)
```


Définit l'image miniature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RasterImage](../../com.aspose.imaging/rasterimage) | l'image miniature. |

### getXResolutionInt() {#getXResolutionInt--}
```
public final int getXResolutionInt()
```


Obtient la résolution x.

Valeur : La résolution x.

**Returns:**
int - la résolution x.
### setXResolution(int value) {#setXResolution-int-}
```
public final void setXResolution(int value)
```


Définit la résolution x.

Valeur : La résolution x.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | la résolution x. |

### getYResolutionInt() {#getYResolutionInt--}
```
public final int getYResolutionInt()
```


Obtient la résolution y.

Valeur : La résolution y.

**Returns:**
int - la résolution y.
### setYResolution(int value) {#setYResolution-int-}
```
public final void setYResolution(int value)
```


Définit la résolution y.

Valeur : La résolution y.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | la résolution y. |

### removeTag(int tagId) {#removeTag-int-}
```
public void removeTag(int tagId)
```


Supprimer la balise du conteneur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tagId | int | L'identifiant de la balise à supprimer. |

### getTagValue(int key) {#getTagValue-int-}
```
public final TiffDataType getTagValue(int key)
```


Obtient la valeur de la balise.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| key | int | La clé de la balise [ExifProperties](../../com.aspose.imaging.exif/exifproperties). |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - The TiffDataType
