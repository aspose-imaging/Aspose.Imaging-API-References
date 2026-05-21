---
title: "ExifProperties"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Liste des balises Exif"
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.exif/exifproperties/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ExifProperties extends System.Enum
```

Liste des balises Exif
## Champs

| Champ | Description |
| --- | --- |
| [ImageWidth](#ImageWidth) | Le nombre de colonnes des données d'image, égal au nombre de pixels par ligne. |
| [ImageLength](#ImageLength) | Le nombre de lignes des données d'image. |
| [BitsPerSample](#BitsPerSample) | Le nombre de bits par composant d'image. |
| [Compression](#Compression) | Le schéma de compression utilisé pour les données d'image. |
| [PhotometricInterpretation](#PhotometricInterpretation) | La composition des pixels. |
| [ImageDescription](#ImageDescription) | Une chaîne de caractères donnant le titre de l'image. |
| [Make](#Make) | Le fabricant de l'équipement d'enregistrement. |
| [Model](#Model) | Le nom du modèle ou le numéro de modèle de l'équipement. |
| [Orientation](#Orientation) | L'orientation de l'image vue en termes de lignes et de colonnes. |
| [SamplesPerPixel](#SamplesPerPixel) | Le nombre de composants par pixel. |
| [XResolution](#XResolution) | Le nombre de pixels par ResolutionUnit dans la direction ImageWidth. |
| [YResolution](#YResolution) | Le nombre de pixels par ResolutionUnit dans la direction ImageLength. |
| [PlanarConfiguration](#PlanarConfiguration) | Indique si les composants de pixel sont enregistrés au format chunky ou planar. |
| [ResolutionUnit](#ResolutionUnit) | L'unité de mesure de XResolution et YResolution. |
| [TransferFunction](#TransferFunction) | Une fonction de transfert pour l'image, décrite sous forme tabulaire. |
| [Software](#Software) | Cette balise enregistre le nom et la version du logiciel ou du firmware de l'appareil photo ou du dispositif d'entrée d'image utilisé pour générer l'image. |
| [DateTime](#DateTime) | La date et l'heure de création de l'image. |
| [Artist](#Artist) | Cette balise enregistre le nom du propriétaire de l'appareil photo, du photographe ou du créateur de l'image. |
| [WhitePoint](#WhitePoint) | La chromaticité du point blanc de l'image. |
| [PrimaryChromaticities](#PrimaryChromaticities) | La chromaticité des trois couleurs primaires de l'image. |
| [YCbCrCoefficients](#YCbCrCoefficients) | Les coefficients matriciels pour la transformation des données d'image de RGB à YCbCr. |
| [YCbCrSubSampling](#YCbCrSubSampling) | Le rapport d'échantillonnage des composantes de chrominance par rapport à la composante de luminance. |
| [YCbCrPositioning](#YCbCrPositioning) | La position des composantes de chrominance par rapport à la composante de luminance. |
| [ReferenceBlackWhite](#ReferenceBlackWhite) | La valeur du point noir de référence et la valeur du point blanc de référence. |
| [Copyright](#Copyright) | Informations sur le droit d'auteur. |
| [ExposureTime](#ExposureTime) | Temps d'exposition, exprimé en secondes. |
| [FNumber](#FNumber) | Le nombre F. |
| [ExposureProgram](#ExposureProgram) | La classe du programme utilisé par l'appareil photo pour régler l'exposition lors de la prise de vue. |
| [SpectralSensitivity](#SpectralSensitivity) | Indique la sensibilité spectrale de chaque canal de l'appareil photo utilisé. |
| [PhotographicSensitivity](#PhotographicSensitivity) | Indique la vitesse ISO et la latitude ISO de l'appareil photo ou du dispositif d'entrée tel que spécifié dans la norme ISO 12232. |
| [OECF](#OECF) | Indique la fonction de conversion opto-électrique (OECF) spécifiée dans la norme ISO 14524. |
| [ExifVersion](#ExifVersion) | La version Exif. |
| [DateTimeOriginal](#DateTimeOriginal) | La date et l'heure de génération des données d'image originales. |
| [DateTimeDigitized](#DateTimeDigitized) | La date et l'heure de numérisation. |
| [ComponentsConfiguration](#ComponentsConfiguration) | La configuration des composants. |
| [CompressedBitsPerPixel](#CompressedBitsPerPixel) | Spécifique aux données compressées ; indique le nombre de bits compressés par pixel. |
| [ShutterSpeedValue](#ShutterSpeedValue) | La valeur de la vitesse d'obturation. |
| [ApertureValue](#ApertureValue) | La valeur de l'ouverture de l'objectif. |
| [BrightnessValue](#BrightnessValue) | La valeur de la luminosité. |
| [ExposureBiasValue](#ExposureBiasValue) | La valeur du biais d'exposition. |
| [MaxApertureValue](#MaxApertureValue) | La valeur de l'ouverture maximale. |
| [SubjectDistance](#SubjectDistance) | La distance au sujet, exprimée en mètres. |
| [MeteringMode](#MeteringMode) | Le mode de mesure. |
| [LightSource](#LightSource) | Le type de source lumineuse. |
| [Flash](#Flash) | Indique l'état du flash lors de la prise de vue de l'image. |
| [FocalLength](#FocalLength) | La distance focale réelle de l'objectif, en mm. |
| [SubjectArea](#SubjectArea) | Cette balise indique l'emplacement et la zone du sujet principal dans la scène globale. |
| [MakerNote](#MakerNote) | Une balise pour les fabricants d'éditeurs Exif afin d'enregistrer toute information souhaitée. |
| [UserComment](#UserComment) | Une balise pour les utilisateurs Exif afin d'écrire des mots‑clés ou des commentaires sur l'image en plus de ceux de ImageDescription, et sans les limitations de code de caractères de la balise ImageDescription. |
| [SubsecTime](#SubsecTime) | Une balise utilisée pour enregistrer les fractions de seconde pour la balise DateTime. |
| [SubsecTimeOriginal](#SubsecTimeOriginal) | Une balise utilisée pour enregistrer les fractions de seconde pour la balise DateTimeOriginal. |
| [SubsecTimeDigitized](#SubsecTimeDigitized) | Une balise utilisée pour enregistrer les fractions de seconde pour la balise DateTimeDigitized. |
| [FlashpixVersion](#FlashpixVersion) | La version du format Flashpix prise en charge par un fichier FPXR. |
| [ColorSpace](#ColorSpace) | La balise d'information d'espace colorimétrique (ColorSpace) est toujours enregistrée comme le spécificateur d'espace colorimétrique. |
| [RelatedSoundFile](#RelatedSoundFile) | Le fichier audio associé. |
| [FlashEnergy](#FlashEnergy) | Indique l'énergie du stroboscope au moment de la capture de l'image, mesurée en Beam Candle Power Seconds (BCPS). |
| [SpatialFrequencyResponse](#SpatialFrequencyResponse) | Cette balise enregistre le tableau de fréquence spatiale de l'appareil photo ou du dispositif d'entrée ainsi que les valeurs SFR dans la direction de la largeur de l'image, de la hauteur de l'image et de la direction diagonale, comme spécifié dans ISO 12233. |
| [FocalPlaneXResolution](#FocalPlaneXResolution) | Indique le nombre de pixels dans la direction de la largeur de l'image (X) par FocalPlaneResolutionUnit sur le plan focal de l'appareil photo. |
| [FocalPlaneYResolution](#FocalPlaneYResolution) | Indique le nombre de pixels dans la direction de la hauteur de l'image (Y) par FocalPlaneResolutionUnit sur le plan focal de l'appareil photo. |
| [FocalPlaneResolutionUnit](#FocalPlaneResolutionUnit) | Indique l'unité de mesure de FocalPlaneXResolution et FocalPlaneYResolution. |
| [SubjectLocation](#SubjectLocation) | Indique l'emplacement du sujet principal dans la scène. |
| [ExposureIndex](#ExposureIndex) | Indique l'indice d'exposition sélectionné sur l'appareil photo ou le dispositif d'entrée au moment de la capture de l'image. |
| [SensingMethod](#SensingMethod) | Indique le type de capteur d'image sur l'appareil photo ou le dispositif d'entrée. |
| [FileSource](#FileSource) | La source du fichier. |
| [SceneType](#SceneType) | Indique le type de scène. |
| [CFAPattern](#CFAPattern) | Indique le motif géométrique du tableau de filtres de couleur (CFA) du capteur d'image lorsqu'un capteur à zone couleur à puce unique est utilisé. |
| [CustomRendered](#CustomRendered) | Cette balise indique l'utilisation d'un traitement spécial sur les données d'image, tel qu'un rendu orienté vers la sortie. |
| [ExposureMode](#ExposureMode) | Cette balise indique le mode d'exposition réglé lors de la prise de vue de l'image. |
| [WhiteBalance](#WhiteBalance) | Cette balise indique le mode de balance des blancs réglé lors de la prise de vue de l'image. |
| [DigitalZoomRatio](#DigitalZoomRatio) | Cette balise indique le rapport de zoom numérique lorsque l'image a été prise. |
| [FocalLengthIn35MmFilm](#FocalLengthIn35MmFilm) | Cette balise indique la distance focale équivalente en supposant un appareil photo à film 35 mm, en mm. |
| [SceneCaptureType](#SceneCaptureType) | Cette balise indique le type de scène qui a été photographié. |
| [GainControl](#GainControl) | Cette balise indique le degré d'ajustement global du gain de l'image. |
| [Contrast](#Contrast) | Cette balise indique la direction du traitement du contraste appliqué par l'appareil photo lorsque l'image a été prise. |
| [Saturation](#Saturation) | Cette balise indique la direction du traitement de la saturation appliqué par l'appareil photo lorsque l'image a été prise. |
| [Sharpness](#Sharpness) | Cette balise indique la direction du traitement de la netteté appliqué par l'appareil photo lorsque l'image a été prise |
| [DeviceSettingDescription](#DeviceSettingDescription) | Cette balise indique les informations sur les conditions de prise de vue d'un modèle d'appareil photo particulier. |
| [SubjectDistanceRange](#SubjectDistanceRange) | Cette balise indique la distance au sujet. |
| [ImageUniqueID](#ImageUniqueID) | L'identifiant unique de l'image. |
| [GPSVersionID](#GPSVersionID) | Indique la version de GPSInfoIFD. |
| [GPSLatitudeRef](#GPSLatitudeRef) | Indique si la latitude est nord ou sud. |
| [GPSLatitude](#GPSLatitude) | Indique la latitude. |
| [GPSLongitudeRef](#GPSLongitudeRef) | Indique si la longitude est orientée à l'est ou à l'ouest. |
| [GPSLongitude](#GPSLongitude) | Indique la longitude. |
| [GPSAltitudeRef](#GPSAltitudeRef) | Indique l'altitude utilisée comme altitude de référence. |
| [GPSAltitude](#GPSAltitude) | Indique l'altitude basée sur la référence dans GPSAltitudeRef. |
| [GPSTimestamp](#GPSTimestamp) | Indique l'heure en UTC (Temps Universel Coordonné). |
| [GPSSatellites](#GPSSatellites) | Indique les satellites GPS utilisés pour les mesures. |
| [GPSStatus](#GPSStatus) | Indique l'état du récepteur GPS lorsque l'image est enregistrée. |
| [GPSMeasureMode](#GPSMeasureMode) | Indique le mode de mesure GPS. |
| [GPSDOP](#GPSDOP) | Indique le DOP GPS (degré de précision des données). |
| [GPSSpeedRef](#GPSSpeedRef) | Indique l'unité utilisée pour exprimer la vitesse de déplacement du récepteur GPS. |
| [GPSSpeed](#GPSSpeed) | Indique la vitesse du déplacement du récepteur GPS. |
| [GPSTrackRef](#GPSTrackRef) | Indique la référence pour donner la direction du déplacement du récepteur GPS. |
| [GPSTrack](#GPSTrack) | Indique la direction du mouvement du récepteur GPS. |
| [GPSImgDirectionRef](#GPSImgDirectionRef) | Indique la référence pour donner la direction de l'image lors de sa capture. |
| [GPSImgDirection](#GPSImgDirection) | Indique la direction de l'image lorsqu'elle a été capturée. |
| [GPSMapDatum](#GPSMapDatum) | Indique les données de levé géodésique utilisées par le récepteur GPS. |
| [GPSDestLatitudeRef](#GPSDestLatitudeRef) | Indique si la latitude du point de destination est une latitude nord ou sud. |
| [GPSDestLatitude](#GPSDestLatitude) | Indique la latitude du point de destination. |
| [GPSDestLongitudeRef](#GPSDestLongitudeRef) | Indique si la longitude du point de destination est orientée à l'est ou à l'ouest. |
| [GPSDestLongitude](#GPSDestLongitude) | Indique la longitude du point de destination. |
| [GPSDestBearingRef](#GPSDestBearingRef) | Indique la référence utilisée pour donner le relèvement au point de destination. |
| [GPSDestBearing](#GPSDestBearing) | Indique le relèvement au point de destination. |
| [GPSDestDistanceRef](#GPSDestDistanceRef) | Indique l'unité utilisée pour exprimer la distance au point de destination. |
| [GPSDestDistance](#GPSDestDistance) | Indique la distance au point de destination. |
| [GPSProcessingMethod](#GPSProcessingMethod) | Une chaîne de caractères enregistrant le nom de la méthode utilisée pour la localisation. |
| [GPSAreaInformation](#GPSAreaInformation) | Une chaîne de caractères enregistrant le nom de la zone GPS. |
| [GPSDateStamp](#GPSDateStamp) | Une chaîne de caractères enregistrant les informations de date et d'heure relatives à UTC (Temps Universel Coordonné). |
| [GPSDifferential](#GPSDifferential) | Indique si une correction différentielle est appliquée au récepteur GPS. |
| [StripOffsets](#StripOffsets) | Pour chaque bande, le décalage en octets de cette bande. |
| [JPEGInterchangeFormat](#JPEGInterchangeFormat) | Le décalage vers l'octet de départ (SOI) des données de vignette compressées JPEG. |
| [JPEGInterchangeFormatLength](#JPEGInterchangeFormatLength) | Le nombre d'octets des données de vignette compressées JPEG. |
| [ExifIfdPointer](#ExifIfdPointer) | Un pointeur vers l'Exif IFD. |
| [GPSIfdPointer](#GPSIfdPointer) | Le pointeur gps ifd. |
| [RowsPerStrip](#RowsPerStrip) | Le nombre de lignes par bande. |
| [StripByteCounts](#StripByteCounts) | Le nombre total d'octets dans chaque bande. |
| [PixelXDimension](#PixelXDimension) | Informations spécifiques aux données compressées. |
| [PixelYDimension](#PixelYDimension) | Informations spécifiques aux données compressées. |
| [Gamma](#Gamma) | Valeur gamma |
| [SensitivityType](#SensitivityType) | Type de sensibilité photographique |
| [StandardOutputSensitivity](#StandardOutputSensitivity) | Indique la sensibilité de sortie standard de l'appareil photo |
| [RecommendedExposureIndex](#RecommendedExposureIndex) | Indique l'indice d'exposition recommandé |
| [ISOSpeed](#ISOSpeed) | Informations sur la valeur de vitesse ISO telle que définie dans la norme ISO 12232 |
| [ISOSpeedLatitudeYYY](#ISOSpeedLatitudeYYY) | Ce tag indique la valeur de latitude de vitesse ISO yyy telle que définie dans la norme ISO 12232 |
| [ISOSpeedLatitudeZZZ](#ISOSpeedLatitudeZZZ) | Ce tag indique la valeur de latitude de vitesse ISO zzz telle que définie dans la norme ISO 12232 |
| [CameraOwnerName](#CameraOwnerName) | Contient le nom du propriétaire de l'appareil photo |
| [BodySerialNumber](#BodySerialNumber) | Contient le numéro de série du corps de l'appareil photo |
| [LensMake](#LensMake) | Ce tag enregistre le fabricant de l'objectif |
| [LensModel](#LensModel) | Ce tag enregistre le nom du modèle et le numéro de modèle de l'objectif\`s |
| [LensSerialNumber](#LensSerialNumber) | Ce tag enregistre le numéro de série de l'objectif interchangeable |
| [LensSpecification](#LensSpecification) | Ce tag indique la distance focale minimale, la distance focale maximale, le nombre F minimal à la distance focale minimale et le nombre F minimal à la distance focale maximale |
### ImageWidth {#ImageWidth}
```
public static final int ImageWidth
```


Le nombre de colonnes des données d'image, égal au nombre de pixels par ligne.

### ImageLength {#ImageLength}
```
public static final int ImageLength
```


Le nombre de lignes des données d'image.

### BitsPerSample {#BitsPerSample}
```
public static final int BitsPerSample
```


Le nombre de bits par composant d'image. Dans cette norme chaque composant de l'image est de 8 bits, ainsi la valeur pour ce tag est 8.

### Compression {#Compression}
```
public static final int Compression
```


Le schéma de compression utilisé pour les données d'image. Lorsqu'une image principale est compressée en JPEG, cette désignation n'est pas nécessaire et est omise.

### PhotometricInterpretation {#PhotometricInterpretation}
```
public static final int PhotometricInterpretation
```


La composition des pixels.

### ImageDescription {#ImageDescription}
```
public static final int ImageDescription
```


Une chaîne de caractères donnant le titre de l'image. Il peut s'agir d'un commentaire tel que "1988 company picnic" ou similaire.

### Make {#Make}
```
public static final int Make
```


Le fabricant de l'équipement d'enregistrement. Il s'agit du fabricant du DSC, du scanner, du numériseur vidéo ou de tout autre équipement qui a généré l'image. Lorsque le champ est laissé vide, il est considéré comme inconnu.

### Model {#Model}
```
public static final int Model
```


Le nom du modèle ou le numéro du modèle de l'équipement. Il s'agit du nom ou du numéro du modèle du DSC, du scanner, du numériseur vidéo ou de tout autre équipement qui a généré l'image. Lorsque le champ est laissé vide, il est considéré comme inconnu.

### Orientation {#Orientation}
```
public static final int Orientation
```


L'orientation de l'image vue en termes de lignes et de colonnes.

### SamplesPerPixel {#SamplesPerPixel}
```
public static final int SamplesPerPixel
```


Le nombre de composants par pixel. Comme cette norme s'applique aux images RGB et YCbCr, la valeur définie pour ce tag est 3.

### XResolution {#XResolution}
```
public static final int XResolution
```


Le nombre de pixels par ResolutionUnit dans la direction ImageWidth. Lorsque la résolution de l'image est inconnue, 72 [dpi] est désigné.

### YResolution {#YResolution}
```
public static final int YResolution
```


Le nombre de pixels par ResolutionUnit dans la direction ImageLength. La même valeur que XResolution est désignée.

### PlanarConfiguration {#PlanarConfiguration}
```
public static final int PlanarConfiguration
```


Indique si les composants de pixel sont enregistrés dans un format chunky ou planar. Si ce champ n'existe pas, la valeur par défaut TIFF de 1 (chunky) est supposée.

### ResolutionUnit {#ResolutionUnit}
```
public static final int ResolutionUnit
```


L'unité de mesure de XResolution et YResolution. La même unité est utilisée pour XResolution et YResolution. Si la résolution de l'image est inconnue, 2 (pouces) est désignée.

### TransferFunction {#TransferFunction}
```
public static final int TransferFunction
```


Une fonction de transfert pour l'image, décrite sous forme tabulaire. Normalement ce tag n'est pas nécessaire, puisque l'espace colorimétrique est spécifié dans le tag d'information d'espace colorimétrique ColorSpace.

### Software {#Software}
```
public static final int Software
```


Ce tag enregistre le nom et la version du logiciel ou du firmware de l'appareil photo ou du dispositif d'entrée d'image utilisé pour générer l'image. Le format détaillé n'est pas spécifié, mais il est recommandé de suivre l'exemple ci-dessous. Lorsque le champ est laissé vide, il est considéré comme inconnu.

### DateTime {#DateTime}
```
public static final int DateTime
```


La date et l'heure de création de l'image. Dans la norme Exif, il s'agit de la date et de l'heure de modification du fichier.

### Artist {#Artist}
```
public static final int Artist
```


Ce tag enregistre le nom du propriétaire de l'appareil photo, du photographe ou du créateur d'image. Le format détaillé n'est pas spécifié, mais il est recommandé d'écrire l'information comme dans l'exemple ci-dessous pour faciliter l'interopérabilité. Lorsque le champ est laissé vide, il est considéré comme inconnu. (Ex. "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James")

### WhitePoint {#WhitePoint}
```
public static final int WhitePoint
```


La chromaticité du point blanc de l'image. Normalement, cette balise n'est pas nécessaire, car l'espace colorimétrique est spécifié dans la balise d'information d'espace colorimétrique ColorSpace.

### PrimaryChromaticities {#PrimaryChromaticities}
```
public static final int PrimaryChromaticities
```


La chromaticité des trois couleurs primaires de l'image. Normalement, cette balise n'est pas nécessaire, car l'espace colorimétrique est spécifié dans la balise d'information d'espace colorimétrique ColorSpace.

### YCbCrCoefficients {#YCbCrCoefficients}
```
public static final int YCbCrCoefficients
```


Les coefficients matriciels pour la transformation des données d'image de RGB à YCbCr.

### YCbCrSubSampling {#YCbCrSubSampling}
```
public static final int YCbCrSubSampling
```


Le rapport d'échantillonnage des composantes de chrominance par rapport à la composante de luminance.

### YCbCrPositioning {#YCbCrPositioning}
```
public static final int YCbCrPositioning
```


La position des composantes de chrominance par rapport à la composante de luminance. Ce champ est destiné uniquement aux données compressées JPEG ou aux données YCbCr non compressées. La valeur par défaut TIFF est 1 (centré) ; mais lorsque Y:Cb:Cr = 4:2:2, il est recommandé dans cette norme d'utiliser 2 (co‑situé) pour enregistrer les données, afin d'améliorer la qualité de l'image lorsqu'elle est affichée sur des systèmes TV. Lorsque ce champ n'existe pas, le lecteur doit supposer la valeur par défaut TIFF. Dans le cas de Y:Cb:Cr = 4:2:0, la valeur par défaut TIFF (centré) est recommandée. Si le lecteur n'est pas capable de prendre en charge les deux types de YCbCrPositioning, il doit suivre la valeur par défaut TIFF quel que soit la valeur de ce champ. Il est préférable que les lecteurs puissent prendre en charge à la fois le positionnement centré et co‑situé.

### ReferenceBlackWhite {#ReferenceBlackWhite}
```
public static final int ReferenceBlackWhite
```


La valeur du point noir de référence et la valeur du point blanc de référence. Aucun défaut n'est fourni dans le TIFF, mais les valeurs ci‑dessous sont données comme défauts ici. L'espace colorimétrique est déclaré dans une balise d'information d'espace colorimétrique, la valeur par défaut étant celle qui fournit les caractéristiques d'image optimales d'interopérabilité dans ces conditions.

### Copyright {#Copyright}
```
public static final int Copyright
```


Informations de droit d'auteur. Dans cette norme, la balise est utilisée pour indiquer à la fois les droits d'auteur du photographe et de l'éditeur. Il s'agit de la mention de droit d'auteur de la personne ou de l'organisation revendiquant les droits sur l'image. La déclaration de droit d'auteur d'interopérabilité, incluant la date et les droits, doit être écrite dans ce champ ; par exemple, « Copyright, John Smith, 19xx. Tous droits réservés. ». Dans cette norme, le champ enregistre à la fois les droits d'auteur du photographe et de l'éditeur, chaque droit étant enregistré dans une partie séparée de la déclaration. Lorsqu'il existe une distinction claire entre les droits du photographe et de l'éditeur, ils doivent être écrits dans l'ordre photographe suivi des droits de l'éditeur, séparés par NULL (dans ce cas, comme la déclaration se termine également par un NULL, il y a deux codes NULL). Lorsque seul le droit d'auteur du photographe est fourni, il est terminé par un code NULL. Lorsque seul le droit d'auteur de l'éditeur est fourni, la partie du photographe consiste en un espace suivi d'un code NULL terminateur, puis le droit d'auteur de l'éditeur est indiqué. Lorsque le champ est laissé vide, il est traité comme inconnu.

### ExposureTime {#ExposureTime}
```
public static final int ExposureTime
```


Temps d'exposition, exprimé en secondes.

### FNumber {#FNumber}
```
public static final int FNumber
```


Le nombre F.

### ExposureProgram {#ExposureProgram}
```
public static final int ExposureProgram
```


La classe du programme utilisé par l'appareil photo pour régler l'exposition lors de la prise de vue.

### SpectralSensitivity {#SpectralSensitivity}
```
public static final int SpectralSensitivity
```


Indique la sensibilité spectrale de chaque canal de l'appareil photo utilisé.

### PhotographicSensitivity {#PhotographicSensitivity}
```
public static final int PhotographicSensitivity
```


Indique la vitesse ISO et la latitude ISO de l'appareil photo ou du dispositif d'entrée tel que spécifié dans la norme ISO 12232.

### OECF {#OECF}
```
public static final int OECF
```


Indique la fonction de conversion opto-électrique (OECF) spécifiée dans la norme ISO 14524.

### ExifVersion {#ExifVersion}
```
public static final int ExifVersion
```


La version Exif.

### DateTimeOriginal {#DateTimeOriginal}
```
public static final int DateTimeOriginal
```


La date et l'heure de génération des données d'image originales.

### DateTimeDigitized {#DateTimeDigitized}
```
public static final int DateTimeDigitized
```


La date et l'heure de numérisation.

### ComponentsConfiguration {#ComponentsConfiguration}
```
public static final int ComponentsConfiguration
```


La configuration des composants.

### CompressedBitsPerPixel {#CompressedBitsPerPixel}
```
public static final int CompressedBitsPerPixel
```


Spécifique aux données compressées ; indique le nombre de bits compressés par pixel.

### ShutterSpeedValue {#ShutterSpeedValue}
```
public static final int ShutterSpeedValue
```


La valeur de la vitesse d'obturation.

### ApertureValue {#ApertureValue}
```
public static final int ApertureValue
```


La valeur de l'ouverture de l'objectif.

### BrightnessValue {#BrightnessValue}
```
public static final int BrightnessValue
```


La valeur de la luminosité.

### ExposureBiasValue {#ExposureBiasValue}
```
public static final int ExposureBiasValue
```


La valeur du biais d'exposition.

### MaxApertureValue {#MaxApertureValue}
```
public static final int MaxApertureValue
```


La valeur de l'ouverture maximale.

### SubjectDistance {#SubjectDistance}
```
public static final int SubjectDistance
```


La distance au sujet, exprimée en mètres.

### MeteringMode {#MeteringMode}
```
public static final int MeteringMode
```


Le mode de mesure.

### LightSource {#LightSource}
```
public static final int LightSource
```


Le type de source lumineuse.

### Flash {#Flash}
```
public static final int Flash
```


Indique l'état du flash lors de la prise de vue de l'image.

### FocalLength {#FocalLength}
```
public static final int FocalLength
```


La distance focale réelle de l'objectif, en mm.

### SubjectArea {#SubjectArea}
```
public static final int SubjectArea
```


Cette balise indique l'emplacement et la zone du sujet principal dans la scène globale.

### MakerNote {#MakerNote}
```
public static final int MakerNote
```


Une balise destinée aux fabricants d'écrivains Exif pour enregistrer toute information souhaitée. Le contenu dépend du fabricant, mais cette balise ne doit pas être utilisée à d'autres fins que celle prévue.

### UserComment {#UserComment}
```
public static final int UserComment
```


Une balise pour les utilisateurs Exif afin d'écrire des mots‑clés ou des commentaires sur l'image en plus de ceux de ImageDescription, et sans les limitations de code de caractères de la balise ImageDescription.

### SubsecTime {#SubsecTime}
```
public static final int SubsecTime
```


Une balise utilisée pour enregistrer les fractions de seconde pour la balise DateTime.

### SubsecTimeOriginal {#SubsecTimeOriginal}
```
public static final int SubsecTimeOriginal
```


Une balise utilisée pour enregistrer les fractions de seconde pour la balise DateTimeOriginal.

### SubsecTimeDigitized {#SubsecTimeDigitized}
```
public static final int SubsecTimeDigitized
```


Une balise utilisée pour enregistrer les fractions de seconde pour la balise DateTimeDigitized.

### FlashpixVersion {#FlashpixVersion}
```
public static final int FlashpixVersion
```


La version du format Flashpix prise en charge par un fichier FPXR.

### ColorSpace {#ColorSpace}
```
public static final int ColorSpace
```


La balise d'information d'espace colorimétrique (ColorSpace) est toujours enregistrée comme le spécificateur d'espace colorimétrique.

### RelatedSoundFile {#RelatedSoundFile}
```
public static final int RelatedSoundFile
```


Le fichier audio associé.

### FlashEnergy {#FlashEnergy}
```
public static final int FlashEnergy
```


Indique l'énergie du stroboscope au moment de la capture de l'image, mesurée en Beam Candle Power Seconds (BCPS).

### SpatialFrequencyResponse {#SpatialFrequencyResponse}
```
public static final int SpatialFrequencyResponse
```


Cette balise enregistre le tableau de fréquence spatiale de l'appareil photo ou du dispositif d'entrée ainsi que les valeurs SFR dans la direction de la largeur de l'image, de la hauteur de l'image et de la direction diagonale, comme spécifié dans ISO 12233.

### FocalPlaneXResolution {#FocalPlaneXResolution}
```
public static final int FocalPlaneXResolution
```


Indique le nombre de pixels dans la direction de la largeur de l'image (X) par FocalPlaneResolutionUnit sur le plan focal de l'appareil photo.

### FocalPlaneYResolution {#FocalPlaneYResolution}
```
public static final int FocalPlaneYResolution
```


Indique le nombre de pixels dans la direction de la hauteur de l'image (Y) par FocalPlaneResolutionUnit sur le plan focal de l'appareil photo.

### FocalPlaneResolutionUnit {#FocalPlaneResolutionUnit}
```
public static final int FocalPlaneResolutionUnit
```


Indique l'unité de mesure de FocalPlaneXResolution et FocalPlaneYResolution. Cette valeur est identique à ResolutionUnit.

### SubjectLocation {#SubjectLocation}
```
public static final int SubjectLocation
```


Indique l'emplacement du sujet principal dans la scène. La valeur de cette balise représente le pixel au centre du sujet principal par rapport au bord gauche, avant le traitement de rotation conformément à la balise Rotation.

### ExposureIndex {#ExposureIndex}
```
public static final int ExposureIndex
```


Indique l'indice d'exposition sélectionné sur l'appareil photo ou le dispositif d'entrée au moment de la capture de l'image.

### SensingMethod {#SensingMethod}
```
public static final int SensingMethod
```


Indique le type de capteur d'image sur l'appareil photo ou le dispositif d'entrée.

### FileSource {#FileSource}
```
public static final int FileSource
```


La source du fichier.

### SceneType {#SceneType}
```
public static final int SceneType
```


Indique le type de scène. Si un DSC a enregistré l'image, la valeur de cette balise doit toujours être définie à 1, indiquant que l'image a été photographiée directement.

### CFAPattern {#CFAPattern}
```
public static final int CFAPattern
```


Indique le motif géométrique du réseau de filtres de couleur (CFA) du capteur d'image lorsqu'un capteur à zone de couleur à puce unique est utilisé. Cela ne s'applique pas à toutes les méthodes de détection.

### CustomRendered {#CustomRendered}
```
public static final int CustomRendered
```


Cette balise indique l'utilisation d'un traitement spécial sur les données d'image, tel qu'un rendu adapté à la sortie. Lorsque ce traitement spécial est effectué, le lecteur doit désactiver ou minimiser tout traitement supplémentaire.

### ExposureMode {#ExposureMode}
```
public static final int ExposureMode
```


Cette balise indique le mode d'exposition réglé lors de la prise de vue. En mode auto-bracketing, l'appareil photo capture une série de cadres de la même scène avec des réglages d'exposition différents.

### WhiteBalance {#WhiteBalance}
```
public static final int WhiteBalance
```


Cette balise indique le mode de balance des blancs réglé lors de la prise de vue de l'image.

### DigitalZoomRatio {#DigitalZoomRatio}
```
public static final int DigitalZoomRatio
```


Cette balise indique le rapport du zoom numérique lors de la prise de vue. Si le numérateur de la valeur enregistrée est 0, cela indique que le zoom numérique n'a pas été utilisé.

### FocalLengthIn35MmFilm {#FocalLengthIn35MmFilm}
```
public static final int FocalLengthIn35MmFilm
```


Cette balise indique la distance focale équivalente en supposant un appareil photo à film 35 mm, en mm. Une valeur de 0 signifie que la distance focale est inconnue. Notez que cette balise diffère de la balise FocalLength.

### SceneCaptureType {#SceneCaptureType}
```
public static final int SceneCaptureType
```


Cette balise indique le type de scène qui a été photographié. Elle peut également être utilisée pour enregistrer le mode dans lequel l'image a été prise.

### GainControl {#GainControl}
```
public static final int GainControl
```


Cette balise indique le degré d'ajustement global du gain de l'image.

### Contrast {#Contrast}
```
public static final int Contrast
```


Cette balise indique la direction du traitement du contraste appliqué par l'appareil photo lorsque l'image a été prise.

### Saturation {#Saturation}
```
public static final int Saturation
```


Cette balise indique la direction du traitement de la saturation appliqué par l'appareil photo lorsque l'image a été prise.

### Sharpness {#Sharpness}
```
public static final int Sharpness
```


Cette balise indique la direction du traitement de la netteté appliqué par l'appareil photo lorsque l'image a été prise

### DeviceSettingDescription {#DeviceSettingDescription}
```
public static final int DeviceSettingDescription
```


Cette balise indique des informations sur les conditions de prise de vue d'un modèle d'appareil photo particulier. La balise est utilisée uniquement pour indiquer les conditions de prise de vue dans le lecteur.

### SubjectDistanceRange {#SubjectDistanceRange}
```
public static final int SubjectDistanceRange
```


Cette balise indique la distance au sujet.

### ImageUniqueID {#ImageUniqueID}
```
public static final int ImageUniqueID
```


L'identifiant unique de l'image.

### GPSVersionID {#GPSVersionID}
```
public static final int GPSVersionID
```


Indique la version de GPSInfoIFD.

### GPSLatitudeRef {#GPSLatitudeRef}
```
public static final int GPSLatitudeRef
```


Indique si la latitude est nord ou sud.

### GPSLatitude {#GPSLatitude}
```
public static final int GPSLatitude
```


Indique la latitude. La latitude est exprimée sous forme de trois valeurs RATIONAL donnant respectivement les degrés, minutes et secondes. Si la latitude est exprimée en degrés, minutes et secondes, un format typique serait dd/1,mm/1,ss/1. Lorsque les degrés et minutes sont utilisés et, par exemple, que des fractions de minutes sont données avec deux décimales, le format serait dd/1,mmmm/100,0/1.

### GPSLongitudeRef {#GPSLongitudeRef}
```
public static final int GPSLongitudeRef
```


Indique si la longitude est orientée à l'est ou à l'ouest.

### GPSLongitude {#GPSLongitude}
```
public static final int GPSLongitude
```


Indique la longitude. La longitude est exprimée sous forme de trois valeurs RATIONAL donnant respectivement les degrés, minutes et secondes. Si la longitude est exprimée en degrés, minutes et secondes, un format typique serait ddd/1,mm/1,ss/1. Lorsque les degrés et minutes sont utilisés et, par exemple, que des fractions de minutes sont données avec deux décimales, le format serait ddd/1,mmmm/100,0/1.

### GPSAltitudeRef {#GPSAltitudeRef}
```
public static final int GPSAltitudeRef
```


Indique l'altitude utilisée comme altitude de référence. Si la référence est le niveau de la mer et que l'altitude est au-dessus du niveau de la mer, la valeur 0 est donnée. Si l'altitude est en dessous du niveau de la mer, la valeur 1 est donnée et l'altitude est indiquée comme une valeur absolue dans la balise GPSAltitude.

### GPSAltitude {#GPSAltitude}
```
public static final int GPSAltitude
```


Indique l'altitude basée sur la référence dans GPSAltitudeRef. L'altitude est exprimée sous forme d'une valeur RATIONAL. L'unité de référence est le mètre.

### GPSTimestamp {#GPSTimestamp}
```
public static final int GPSTimestamp
```


Indique l'heure en UTC (Temps Universel Coordonné). TimeStamp est exprimé sous forme de trois valeurs RATIONAL donnant l'heure, la minute et la seconde.

### GPSSatellites {#GPSSatellites}
```
public static final int GPSSatellites
```


Indique les satellites GPS utilisés pour les mesures. Cette balise peut être utilisée pour décrire le nombre de satellites, leur numéro d'identification, l'angle d'élévation, l'azimut, le SNR et d'autres informations en notation ASCII. Le format n'est pas spécifié. Si le récepteur GPS est incapable de prendre des mesures, la valeur de la balise doit être définie sur NULL.

### GPSStatus {#GPSStatus}
```
public static final int GPSStatus
```


Indique l'état du récepteur GPS lorsque l'image est enregistrée.

### GPSMeasureMode {#GPSMeasureMode}
```
public static final int GPSMeasureMode
```


Indique le mode de mesure GPS. - 2‑ ou 3‑dimensionnel.

### GPSDOP {#GPSDOP}
```
public static final int GPSDOP
```


Indique le DOP GPS (degré de précision des données). Une valeur HDOP est écrite lors d'une mesure bidimensionnelle, et PDOP lors d'une mesure tridimensionnelle.

### GPSSpeedRef {#GPSSpeedRef}
```
public static final int GPSSpeedRef
```


Indique l'unité utilisée pour exprimer la vitesse du récepteur GPS. 'K', 'M' et 'N' représentent respectivement les kilomètres par heure, les miles par heure et les nœuds.

### GPSSpeed {#GPSSpeed}
```
public static final int GPSSpeed
```


Indique la vitesse du déplacement du récepteur GPS.

### GPSTrackRef {#GPSTrackRef}
```
public static final int GPSTrackRef
```


Indique la référence pour donner la direction du mouvement du récepteur GPS. 'T' désigne la direction vraie et 'M' la direction magnétique.

### GPSTrack {#GPSTrack}
```
public static final int GPSTrack
```


Indique la direction du mouvement du récepteur GPS. La plage de valeurs va de 0.00 à 359.99.

### GPSImgDirectionRef {#GPSImgDirectionRef}
```
public static final int GPSImgDirectionRef
```


Indique la référence pour donner la direction de l'image lors de la capture. 'T' désigne la direction vraie et 'M' la direction magnétique.

### GPSImgDirection {#GPSImgDirection}
```
public static final int GPSImgDirection
```


Indique la direction de l'image lors de la capture. La plage de valeurs va de 0.00 à 359.99.

### GPSMapDatum {#GPSMapDatum}
```
public static final int GPSMapDatum
```


Indique les données de levé géodésique utilisées par le récepteur GPS.

### GPSDestLatitudeRef {#GPSDestLatitudeRef}
```
public static final int GPSDestLatitudeRef
```


Indique si la latitude du point de destination est nord ou sud. La valeur ASCII 'N' indique la latitude nord, et 'S' la latitude sud.

### GPSDestLatitude {#GPSDestLatitude}
```
public static final int GPSDestLatitude
```


Indique la latitude du point de destination. La latitude est exprimée sous forme de trois valeurs RATIONAL donnant respectivement les degrés, minutes et secondes. Si la latitude est exprimée en degrés, minutes et secondes, un format typique serait dd/1,mm/1,ss/1. Lorsque les degrés et minutes sont utilisés et, par exemple, que des fractions de minutes sont données avec deux décimales, le format serait dd/1,mmmm/100,0/1.

### GPSDestLongitudeRef {#GPSDestLongitudeRef}
```
public static final int GPSDestLongitudeRef
```


Indique si la longitude du point de destination est est ou ouest. Le caractère ASCII 'E' indique la longitude est, et 'W' la longitude ouest.

### GPSDestLongitude {#GPSDestLongitude}
```
public static final int GPSDestLongitude
```


Indique la longitude du point de destination. La longitude est exprimée sous forme de trois valeurs RATIONAL donnant respectivement les degrés, minutes et secondes. Si la longitude est exprimée en degrés, minutes et secondes, un format typique serait ddd/1,mm/1,ss/1. Lorsque les degrés et minutes sont utilisés et, par exemple, que des fractions de minutes sont données avec deux décimales, le format serait ddd/1,mmmm/100,0/1.

### GPSDestBearingRef {#GPSDestBearingRef}
```
public static final int GPSDestBearingRef
```


Indique la référence utilisée pour donner le relèvement du point de destination. 'T' désigne la direction vraie et 'M' la direction magnétique.

### GPSDestBearing {#GPSDestBearing}
```
public static final int GPSDestBearing
```


Indique le relèvement du point de destination. La plage de valeurs va de 0.00 à 359.99.

### GPSDestDistanceRef {#GPSDestDistanceRef}
```
public static final int GPSDestDistanceRef
```


Indique l'unité utilisée pour exprimer la distance au point de destination. 'K', 'M' et 'N' représentent respectivement les kilomètres, les miles et les nœuds.

### GPSDestDistance {#GPSDestDistance}
```
public static final int GPSDestDistance
```


Indique la distance au point de destination.

### GPSProcessingMethod {#GPSProcessingMethod}
```
public static final int GPSProcessingMethod
```


Une chaîne de caractères enregistrant le nom de la méthode utilisée pour la localisation. Le premier octet indique le code de caractères utilisé, suivi du nom de la méthode.

### GPSAreaInformation {#GPSAreaInformation}
```
public static final int GPSAreaInformation
```


Une chaîne de caractères enregistrant le nom de la zone GPS. Le premier octet indique le code de caractères utilisé, suivi du nom de la zone GPS.

### GPSDateStamp {#GPSDateStamp}
```
public static final int GPSDateStamp
```


Une chaîne de caractères enregistrant les informations de date et d'heure relatives à l'UTC (Temps Universel Coordonné). Le format est YYYY:MM:DD.

### GPSDifferential {#GPSDifferential}
```
public static final int GPSDifferential
```


Indique si une correction différentielle est appliquée au récepteur GPS.

### StripOffsets {#StripOffsets}
```
public static final int StripOffsets
```


Pour chaque bande, le décalage en octets de cette bande. Il est recommandé de choisir cela de façon que le nombre d'octets de bande ne dépasse pas 64 KBytes. Tag auxiliaire.

### JPEGInterchangeFormat {#JPEGInterchangeFormat}
```
public static final int JPEGInterchangeFormat
```


Le décalage vers l'octet de départ (SOI) des données de vignette JPEG compressées. Ceci n'est pas utilisé pour les données JPEG de l'image principale.

### JPEGInterchangeFormatLength {#JPEGInterchangeFormatLength}
```
public static final int JPEGInterchangeFormatLength
```


Le nombre d'octets des données de vignette JPEG compressées. Ceci n'est pas utilisé pour les données JPEG de l'image principale. Les vignettes JPEG ne sont pas découpées mais enregistrées comme un flux JPEG continu du SOI à l'EOI. Les marqueurs Appn et COM ne doivent pas être enregistrés. Les vignettes compressées doivent être enregistrées dans un maximum de 64 KBytes, y compris toutes les autres données à enregistrer dans APP1.

### ExifIfdPointer {#ExifIfdPointer}
```
public static final int ExifIfdPointer
```


Un pointeur vers l'Exif IFD. L'interopérabilité, l'Exif IFD a la même structure que celle de l'IFD spécifié dans le TIFF. Ordinairement, cependant, il ne contient pas de données d'image comme dans le cas du TIFF.

### GPSIfdPointer {#GPSIfdPointer}
```
public static final int GPSIfdPointer
```


Le pointeur gps ifd.

### RowsPerStrip {#RowsPerStrip}
```
public static final int RowsPerStrip
```


Le nombre de lignes par bande. Il s'agit du nombre de lignes de l'image d'une bande lorsqu'une image est divisée en bandes.

### StripByteCounts {#StripByteCounts}
```
public static final int StripByteCounts
```


Le nombre total d'octets dans chaque bande.

### PixelXDimension {#PixelXDimension}
```
public static final int PixelXDimension
```


Informations spécifiques aux données compressées. Lorsqu'un fichier compressé est enregistré, la largeur valide de l'image significative doit être enregistrée dans cette balise, qu'il y ait des données de remplissage ou un marqueur de redémarrage.

### PixelYDimension {#PixelYDimension}
```
public static final int PixelYDimension
```


Informations spécifiques aux données compressées. Lorsqu'un fichier compressé est enregistré, la hauteur valide de l'image significative doit être enregistrée dans cette balise.

### Gamma {#Gamma}
```
public static final int Gamma
```


Valeur gamma

### SensitivityType {#SensitivityType}
```
public static final int SensitivityType
```


Type de sensibilité photographique

### StandardOutputSensitivity {#StandardOutputSensitivity}
```
public static final int StandardOutputSensitivity
```


Indique la sensibilité de sortie standard de l'appareil photo

### RecommendedExposureIndex {#RecommendedExposureIndex}
```
public static final int RecommendedExposureIndex
```


Indique l'indice d'exposition recommandé

### ISOSpeed {#ISOSpeed}
```
public static final int ISOSpeed
```


Informations sur la valeur de vitesse ISO telle que définie dans la norme ISO 12232

### ISOSpeedLatitudeYYY {#ISOSpeedLatitudeYYY}
```
public static final int ISOSpeedLatitudeYYY
```


Ce tag indique la valeur de latitude de vitesse ISO yyy telle que définie dans la norme ISO 12232

### ISOSpeedLatitudeZZZ {#ISOSpeedLatitudeZZZ}
```
public static final int ISOSpeedLatitudeZZZ
```


Ce tag indique la valeur de latitude de vitesse ISO zzz telle que définie dans la norme ISO 12232

### CameraOwnerName {#CameraOwnerName}
```
public static final int CameraOwnerName
```


Contient le nom du propriétaire de l'appareil photo

### BodySerialNumber {#BodySerialNumber}
```
public static final int BodySerialNumber
```


Contient le numéro de série du corps de l'appareil photo

### LensMake {#LensMake}
```
public static final int LensMake
```


Ce tag enregistre le fabricant de l'objectif

### LensModel {#LensModel}
```
public static final int LensModel
```


Ce tag enregistre le nom du modèle et le numéro de modèle de l'objectif\`s

### LensSerialNumber {#LensSerialNumber}
```
public static final int LensSerialNumber
```


Ce tag enregistre le numéro de série de l'objectif interchangeable

### LensSpecification {#LensSpecification}
```
public static final int LensSpecification
```


Ce tag indique la distance focale minimale, la distance focale maximale, le nombre F minimal à la distance focale minimale et le nombre F minimal à la distance focale maximale

