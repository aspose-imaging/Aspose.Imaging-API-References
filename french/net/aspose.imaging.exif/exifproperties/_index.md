---
title: ExifProperties
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Liste des balises Exif
type: docs
weight: 1080
url: /fr/net/aspose.imaging.exif/exifproperties/
---
## ExifProperties enumeration

Liste des balises Exif

```csharp
public enum ExifProperties : ushort
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| ImageWidth | `256` | Le nombre de colonnes de données d'image, égal au nombre de pixels par ligne. |
| ImageLength | `257` | Le nombre de lignes de données d'image. |
| BitsPerSample | `258` | Le nombre de bits par composant d'image. Dans cette norme, chaque composant de l'image est de 8 bits, donc la valeur de cette balise est 8. |
| Compression | `259` | Le schéma de compression utilisé pour les données d'image. Lorsqu'une image principale est compressée au format JPEG, cette désignation n'est pas nécessaire et est omise. |
| PhotometricInterpretation | `262` | La composition en pixels. |
| ImageDescription | `270` | Une chaîne de caractères donnant le titre de l'image. Il peut s'agir d'un commentaire tel que "pique-nique d'entreprise de 1988" ou similaire. |
| Make | `271` | Le fabricant de l'équipement d'enregistrement. Il s'agit du fabricant du DSC, du scanner, du numériseur vidéo ou de tout autre équipement qui a généré l'image. Lorsque le champ est laissé vide, il est traité comme inconnu. |
| Model | `272` | Le nom du modèle ou le numéro de modèle de l'équipement. Il s'agit du nom ou du numéro de modèle du DSC, du scanner, du numériseur vidéo ou de tout autre équipement qui a généré l'image. Lorsque le champ est laissé vide, il est traité comme inconnu. |
| Orientation | `274` | L'orientation de l'image vue en termes de lignes et de colonnes. |
| SamplesPerPixel | `277` | Le nombre de composants par pixel. Étant donné que cette norme s'applique aux images RVB et YCbCr, la valeur définie pour cette balise est 3. |
| XResolution | `282` | Le nombre de pixels par ResolutionUnit dans la direction ImageWidth. Lorsque la résolution de l'image est inconnue, 72 [dpi] est désigné. |
| YResolution | `283` | Le nombre de pixels par ResolutionUnit dans la direction ImageLength. La même valeur que XResolution est désignée. |
| PlanarConfiguration | `284` | Indique si les composants de pixels sont enregistrés dans un format chunky ou planaire. Si ce champ n'existe pas, la valeur TIFF par défaut de 1 (volumineux) est utilisée. |
| ResolutionUnit | `296` | L'unité de mesure XResolution et YResolution. La même unité est utilisée pour XResolution et YResolution. Si la résolution de l'image est inconnue, 2 (pouces) est désigné. |
| TransferFunction | `301` | Une fonction de transfert pour l'image, décrite sous forme de tableau. Normalement, cette balise n'est pas nécessaire, car l'espace colorimétrique est spécifié dans les informations sur l'espace colorimétrique Balise ColorSpace. |
| Software | `305` | Cette balise enregistre le nom et la version du logiciel ou du micrologiciel de la caméra ou du périphérique d'entrée d'image utilisé pour générer l'image. Le format détaillé n'est pas spécifié, mais il est recommandé de suivre l'exemple ci-dessous. Lorsque le champ est laissé vide, il est traité comme inconnu. |
| DateTime | `306` | La date et l'heure de création de l'image. En standard Exif, il s'agit de la date et de l'heure auxquelles le fichier a été modifié. |
| Artist | `315` | Cette balise enregistre le nom du propriétaire de l'appareil photo, du photographe ou du créateur de l'image. Le format détaillé n'est pas spécifié, mais il est recommandé que les informations soient écrites comme dans l'exemple ci-dessous pour faciliter l'interopérabilité. Lorsque le champ est laissé vide, il est traité comme inconnu. Ex.) "Propriétaire de l'appareil photo, John Smith ; Photographe, Michael Brown ; Créateur d'images, Ken James" |
| WhitePoint | `318` | La chromaticité du point blanc de l'image. Normalement, cette balise n'est pas nécessaire, car l'espace colorimétrique est spécifié dans les informations sur l'espace colorimétrique Balise ColorSpace. |
| PrimaryChromaticities | `319` | La chromaticité des trois couleurs primaires de l'image. Normalement, cette balise n'est pas nécessaire, car l'espace colorimétrique est spécifié dans les informations sur l'espace colorimétrique. Balise ColorSpace. |
| YCbCrCoefficients | `529` | Les coefficients de matrice pour la transformation des données d'image RVB en YCbCr. |
| YCbCrSubSampling | `530` | Le taux d'échantillonnage des composantes de chrominance par rapport à la composante de luminance. |
| YCbCrPositioning | `531` | La position des composantes de chrominance par rapport à la composante de luminance. Ce champ est désigné uniquement pour les données compressées JPEG ou les données YCbCr non compressées. Le TIFF par défaut est 1 (centré) ; mais lorsque Y:Cb:Cr = 4:2:2, il est recommandé dans cette norme que 2 (co-situé) soit utilisé pour enregistrer les données, afin d'améliorer la qualité de l'image lorsqu'elle est vue sur des systèmes de télévision. Lorsque ce champ n'existe pas, le lecteur doit adopter le TIFF par défaut. Dans le cas de Y:Cb:Cr = 4:2:0, la valeur par défaut TIFF (centrée) est recommandée. Si le lecteur n'a pas la capacité de prendre en charge les deux types de YCbCrPositioning, il doit suivre le TIFF par défaut indépendamment de la valeur dans ce champ. Il est préférable que les lecteurs " puissent prendre en charge à la fois le positionnement centré et co-situé. |
| ReferenceBlackWhite | `532` | La valeur du point noir de référence et la valeur du point blanc de référence . Aucune valeur par défaut n'est donnée dans TIFF, mais les valeurs ci-dessous sont données par défaut ici. L'espace colorimétrique est déclaré dans une balise d'informations d'espace colorimétrique, la valeur par défaut étant la valeur qui donne les caractéristiques optimales de l'image Interopérabilité ces conditions |
| Copyright | `33432` | Informations de copyright. Dans cette norme, la balise est utilisée pour indiquer à la fois les droits d'auteur du photographe et de l'éditeur. Il s'agit de l'avis de droit d'auteur de la personne ou de l'organisation revendiquant les droits sur l'image. La déclaration d'interopérabilité copyright , y compris la date et les droits, doit être écrite dans ce champ ; par exemple, "Copyright, John Smith, 19xx. Tous droits réservés.". Dans cette norme, le champ enregistre à la fois les droits d'auteur du photographe et de l'éditeur, chacun étant enregistré dans une partie distincte de la déclaration. Lorsqu'il y a une distinction claire entre les droits d'auteur du photographe et de l'éditeur, ceux-ci doivent être écrits dans l'ordre du photographe suivi du droit d'auteur de l'éditeur, séparés par NULL (dans ce cas, puisque la déclaration se termine également par un NULL, il y a deux codes NULL ). Lorsque seul le copyright du photographe est donné, il se termine par un code NULL . Lorsque seul le droit d'auteur de l'éditeur est donné, la partie du droit d'auteur du photographe se compose d'un espace suivi d'un code NULL de fin, puis le droit d'auteur de l'éditeur est donné. Lorsque le champ est laissé vide, il est traité comme inconnu. |
| ExposureTime | `33434` | Temps d'exposition, exprimé en secondes. |
| FNumber | `33437` | Le nombre F. |
| ExposureProgram | `34850` | La classe du programme utilisé par l'appareil photo pour régler l'exposition lorsque la photo est prise. |
| SpectralSensitivity | `34852` | Indique la sensibilité spectrale de chaque canal de la caméra utilisée. |
| PhotographicSensitivity | `34855` | Indique la vitesse ISO et la latitude ISO de l'appareil photo ou du périphérique d'entrée comme spécifié dans la norme ISO 12232. |
| OECF | `34856` | Indique la fonction de conversion opto-électrique (OECF) spécifiée dans la norme ISO 14524. |
| ExifVersion | `36864` | La version exif. |
| DateTimeOriginal | `36867` | La date et l'heure auxquelles les données d'image d'origine ont été générées. |
| DateTimeDigitized | `36868` | La date heure numérisée. |
| ComponentsConfiguration | `37121` | La configuration des composants. |
| CompressedBitsPerPixel | `37122` | Spécifique aux données compressées ; indique les bits compressés par pixel. |
| ShutterSpeedValue | `37377` | La valeur de la vitesse d'obturation. |
| ApertureValue | `37378` | La valeur d'ouverture de l'objectif. |
| BrightnessValue | `37379` | La valeur de luminosité. |
| ExposureBiasValue | `37380` | La valeur du biais d'exposition. |
| MaxApertureValue | `37381` | La valeur d'ouverture maximale. |
| SubjectDistance | `37382` | La distance au sujet, donnée en mètres. |
| MeteringMode | `37383` | Le mode de mesure. |
| LightSource | `37384` | La gentille source de lumière. |
| Flash | `37385` | Indique l'état du flash lors de la prise de vue. |
| FocalLength | `37386` | La distance focale réelle de l'objectif, en mm. |
| SubjectArea | `37396` | Cette balise indique l'emplacement et la zone du sujet principal dans la scène globale. |
| MakerNote | `37500` | Une étiquette pour les fabricants d'écrivains Exif pour enregistrer toutes les informations souhaitées. Le contenu appartient au fabricant, mais cette étiquette ne doit pas être utilisée à d'autres fins que celles pour lesquelles elle a été conçue. |
| UserComment | `37510` | Une balise permettant aux utilisateurs d'Exif d'écrire des mots-clés ou des commentaires sur l'image en plus de ceux de ImageDescription, et sans les limitations de code de caractères de la balise ImageDescription. |
| SubsecTime | `37520` | Une balise utilisée pour enregistrer des fractions de secondes pour la balise DateTime. |
| SubsecTimeOriginal | `37521` | Une balise utilisée pour enregistrer des fractions de secondes pour la balise DateTimeOriginal. |
| SubsecTimeDigitized | `37522` | Une balise utilisée pour enregistrer des fractions de secondes pour la balise DateTimeDigitized. |
| FlashpixVersion | `40960` | La version du format Flashpix prise en charge par un fichier FPXR. |
| ColorSpace | `40961` | La balise d'informations sur l'espace colorimétrique (ColorSpace) est toujours enregistrée en tant que spécificateur d'espace colorimétrique. |
| RelatedSoundFile | `40964` | Le fichier son associé. |
| FlashEnergy | `41483` | Indique l'énergie stroboscopique au moment de la capture de l'image, mesurée en secondes de puissance de bougie de faisceau (BCPS). |
| SpatialFrequencyResponse | `41484` | Cette balise enregistre la table de fréquences spatiales de la caméra ou du périphérique d'entrée et les valeurs SFR dans le sens de la largeur de l'image, de la hauteur de l'image et de la direction diagonale, comme spécifié dans la norme ISO 12233. |
| FocalPlaneXResolution | `41486` | Indique le nombre de pixels dans la direction de la largeur de l'image (X) par FocalPlaneResolutionUnit sur le plan focal de la caméra. |
| FocalPlaneYResolution | `41487` | Indique le nombre de pixels dans la direction de la hauteur de l'image (Y) par FocalPlaneResolutionUnit sur le plan focal de la caméra. |
| FocalPlaneResolutionUnit | `41488` | Indique l'unité de mesure de FocalPlaneXResolution et FocalPlaneYResolution. Cette valeur est identique à ResolutionUnit. |
| SubjectLocation | `41492` | Indique l'emplacement du sujet principal dans la scène. La valeur de cette balise représente le pixel au centre du sujet principal par rapport au bord gauche, avant le traitement de rotation conformément à la balise Rotation. |
| ExposureIndex | `41493` | Indique l'indice d'exposition sélectionné sur l'appareil photo ou le périphérique d'entrée au moment où l'image est capturée. |
| SensingMethod | `41495` | Indique le type de capteur d'image sur la caméra ou le périphérique d'entrée. |
| FileSource | `41728` | La source du fichier. |
| SceneType | `41729` | Indique le type de scène. Si un DSC a enregistré l'image, cette valeur de balise doit toujours être définie sur 1, indiquant que l'image a été directement photographiée. |
| CFAPattern | `41730` | Indique le motif géométrique du réseau de filtres de couleur (CFA) du capteur d'image lorsqu'un capteur de zone de couleur à une puce est utilisé. Cela ne s'applique pas à toutes les méthodes de détection. |
| CustomRendered | `41985` | Cette balise indique l'utilisation d'un traitement spécial sur les données d'image, comme le rendu adapté à la sortie. Lorsqu'un traitement spécial est effectué, le lecteur doit désactiver ou minimiser tout traitement ultérieur. |
| ExposureMode | `41986` | Cette balise indique le mode d'exposition défini lors de la prise de vue. En mode de bracketing automatique, l'appareil photo prend une série d'images de la même scène avec différents réglages d'exposition. |
| WhiteBalance | `41987` | Cette balise indique le mode de balance des blancs défini lors de la prise de vue. |
| DigitalZoomRatio | `41988` | Cette balise indique le taux de zoom numérique lorsque l'image a été prise. Si le numérateur de la valeur enregistrée est 0, cela indique que le zoom numérique n'a pas été utilisé. |
| FocalLengthIn35MmFilm | `41989` | Cette étiquette indique la distance focale équivalente en supposant un appareil photo argentique 35 mm, en mm. Une valeur de 0 signifie que la distance focale est inconnue. Notez que cette balise diffère de la balise FocalLength. |
| SceneCaptureType | `41990` | Cette balise indique le type de scène qui a été tournée. Il peut également être utilisé pour enregistrer le mode dans lequel l'image a été prise. |
| GainControl | `41991` | Cette balise indique le degré d'ajustement global du gain d'image. |
| Contrast | `41992` | Cette balise indique la direction du traitement du contraste appliqué par l'appareil photo lors de la prise de vue. |
| Saturation | `41993` | Cette balise indique le sens du traitement de saturation appliqué par la caméra lors de la prise de vue. |
| Sharpness | `41994` | Cette balise indique le sens du traitement de la netteté appliqué par l'appareil photo lors de la prise de vue |
| DeviceSettingDescription | `41995` | Cette balise indique des informations sur les conditions de prise de vue d'un modèle d'appareil photo particulier. La balise sert uniquement à indiquer les conditions de prise de vue dans le lecteur. |
| SubjectDistanceRange | `41996` | Cette balise indique la distance au sujet. |
| ImageUniqueID | `42016` | L'identifiant unique de l'image. |
| GPSVersionID | `0` | Indique la version de GPSInfoIFD. |
| GPSLatitudeRef | `1` | Indique si la latitude est nord ou sud. |
| GPSLatitude | `2` | Indique la latitude. La latitude est exprimée sous la forme de trois valeurs RATIONAL donnant respectivement les degrés, les minutes et les secondes. Si la latitude est exprimée en degrés, minutes et secondes, un format typique serait dd/1,mm/1,ss/1. Lorsque des degrés et des minutes sont utilisés et, par exemple, des fractions de minutes sont données jusqu'à deux décimales, le format serait dd/1,mmmm/100,0/1. |
| GPSLongitudeRef | `3` | Indique si la longitude est est ou ouest. |
| GPSLongitude | `4` | Indique la longitude. La longitude est exprimée sous la forme de trois valeurs RATIONAL donnant respectivement les degrés, les minutes et les secondes. Si la longitude est exprimée en degrés, minutes et secondes, un format typique serait ddd/1,mm/1,ss/1. Lorsque des degrés et des minutes sont utilisés et, par exemple, des fractions de minutes sont données jusqu'à deux décimales, le format serait ddd/1,mmmm/100,0/1. |
| GPSAltitudeRef | `5` | Indique l'altitude utilisée comme altitude de référence. Si la référence est le niveau de la mer et que l'altitude est au-dessus du niveau de la mer, 0 est donné. Si l'altitude est inférieure au niveau de la mer, la valeur 1 est donnée et l'altitude est indiquée en valeur absolue dans la balise GPSAltitude. |
| GPSAltitude | `6` | Indique l'altitude basée sur la référence dans GPSAltitudeRef. L'altitude est exprimée sous la forme d'une valeur RATIONAL. L'unité de référence est le mètre. |
| GPSTimestamp | `7` | Indique l'heure en UTC (Coordinated Universal Time). TimeStamp est exprimé en trois valeurs RATIONAL donnant l'heure, la minute et la seconde. |
| GPSSatellites | `8` | Indique les satellites GPS utilisés pour les mesures. Cette balise peut être utilisée pour décrire le nombre de satellites, leur numéro d'identification, l'angle d'élévation, l'azimut, le SNR et d'autres informations en notation ASCII. Le format n'est pas spécifié. Si le récepteur GPS est incapable de prendre des mesures, la valeur de la balise doit être définie sur NULL. |
| GPSStatus | `9` | Indique l'état du récepteur GPS lorsque l'image est enregistrée. |
| GPSMeasureMode | `10` | Indique le mode de mesure GPS. - 2 ou 3 dimensions. |
| GPSDOP | `11` | Indique le DOP GPS (degré de précision des données). Une valeur HDOP est écrite lors d'une mesure bidimensionnelle, et PDOP lors d'une mesure tridimensionnelle. |
| GPSSpeedRef | `12` | Indique l'unité utilisée pour exprimer la vitesse de déplacement du récepteur GPS. 'K' 'M' et 'N' représentent les kilomètres par heure, les miles par heure et les nœuds. |
| GPSSpeed | `13` | Indique la vitesse de déplacement du récepteur GPS. |
| GPSTrackRef | `14` | Indique la référence pour donner le sens de déplacement du récepteur GPS. 'T' indique la vraie direction et 'M' est la direction magnétique. |
| GPSTrack | `15` | Indique la direction du mouvement du récepteur GPS. La plage de valeurs va de 0,00 à 359,99. |
| GPSImgDirectionRef | `16` | Indique la référence pour donner la direction de l'image lors de sa capture. 'T' indique la vraie direction et 'M' est la direction magnétique. |
| GPSImgDirection | `17` | Indique la direction de l'image lors de sa capture. La plage de valeurs va de 0,00 à 359,99. |
| GPSMapDatum | `18` | Indique les données géodésiques utilisées par le récepteur GPS. |
| GPSDestLatitudeRef | `19` | Indique si la latitude du point de destination est la latitude nord ou sud. La valeur ASCII "N" indique la latitude nord et "S" la latitude sud. |
| GPSDestLatitude | `20` | Indique la latitude du point de destination. La latitude est exprimée sous la forme de trois valeurs RATIONAL donnant respectivement les degrés, minutes et secondes. Si la latitude est exprimée en degrés, minutes et secondes, un format typique serait dd/1,mm/1,ss/1. Lorsque des degrés et des minutes sont utilisés et, par exemple, des fractions de minutes sont données jusqu'à deux décimales, le format serait dd/1,mmmm/100,0/1. |
| GPSDestLongitudeRef | `21` | Indique si la longitude du point de destination est la longitude est ou ouest. ASCII 'E' indique la longitude est, et 'W' est la longitude ouest. |
| GPSDestLongitude | `22` | Indique la longitude du point de destination. La longitude est exprimée sous la forme de trois valeurs RATIONAL donnant respectivement les degrés, minutes et secondes. Si la longitude est exprimée en degrés, minutes et secondes, un format typique serait ddd/1,mm/1,ss/1. Lorsque des degrés et des minutes sont utilisés et, par exemple, des fractions de minutes sont données jusqu'à deux décimales, le format serait ddd/1,mmmm/100,0/1. |
| GPSDestBearingRef | `23` | Indique la référence utilisée pour donner le relèvement au point de destination. 'T' indique la vraie direction et 'M' est la direction magnétique. |
| GPSDestBearing | `24` | Indique le relèvement jusqu'au point de destination. La plage de valeurs va de 0,00 à 359,99. |
| GPSDestDistanceRef | `25` | Indique l'unité utilisée pour exprimer la distance jusqu'au point de destination. 'K', 'M' et 'N' représentent les kilomètres, les miles et les nœuds. |
| GPSDestDistance | `26` | Indique la distance jusqu'au point de destination. |
| GPSProcessingMethod | `27` | Chaîne de caractères enregistrant le nom de la méthode utilisée pour la localisation. Le premier octet indique le code de caractère utilisé, suivi du nom de la méthode. |
| GPSAreaInformation | `28` | Une chaîne de caractères enregistrant le nom de la zone GPS. Le premier octet indique le code de caractère utilisé, suivi du nom de la zone GPS. |
| GPSDateStamp | `29` | Une chaîne de caractères enregistrant les informations de date et d'heure relatives à UTC (Coordinated Universal Time). Le format est AAAA:MM:JJ. |
| GPSDifferential | `30` | Indique si la correction différentielle est appliquée au récepteur GPS. |
| StripOffsets | `273` | Pour chaque bande, le décalage d'octet de cette bande. Il est recommandé de sélectionner cette option afin que le nombre d'octets de bande ne dépasse pas 64 Ko. Aux tag. |
| JPEGInterchangeFormat | `513` | Le décalage par rapport à l'octet de début (SOI) des données de vignette compressées JPEG. Ceci n'est pas utilisé pour les données JPEG de l'image principale. |
| JPEGInterchangeFormatLength | `514` | Le nombre d'octets de données de vignettes compressées JPEG. Ceci n'est pas utilisé pour les données JPEG de l'image primaire. Les vignettes JPEG ne sont pas divisées mais sont enregistrées sous la forme d'un flux binaire JPEG continu de SOI à EOI. Les marqueurs Appn et COM ne doivent pas être enregistrés. Les vignettes compressées doivent être enregistrées dans un maximum de 64 Ko, y compris toutes les autres données à enregistrer dans APP1. |
| ExifIfdPointer | `34665` | Un pointeur vers l'IFD Exif. Interopérabilité, Exif IFD a la même structure que celle de l'IFD spécifié dans TIFF. cependant, il ne contient généralement pas de données d'image comme dans le cas du format TIFF. |
| GPSIfdPointer | `34853` | Le pointeur GPS ifd. |
| RowsPerStrip | `278` | Le nombre de lignes par bande. Il s'agit du nombre de lignes dans l'image d'une bande lorsqu'une image est divisée en bandes. |
| StripByteCounts | `279` | Le nombre total d'octets dans chaque bande. |
| PixelXDimension | `40962` | Informations spécifiques aux données compressées. Lorsqu'un fichier compressé est enregistré, la largeur valide de l'image significative doit être enregistrée dans cette balise, qu'il y ait ou non des données de remplissage ou un marqueur de redémarrage. |
| PixelYDimension | `40963` | Informations spécifiques aux données compressées. Lorsqu'un fichier compressé est enregistré, la hauteur valide de l'image significative doit être enregistrée dans cette balise |
| Gamma | `42240` | Valeur gamma |
| SensitivityType | `34864` | Type de sensibilité photographique |
| StandardOutputSensitivity | `34865` | Indique la sensibilité de sortie standard de la caméra |
| RecommendedExposureIndex | `34866` | Indique l'indice d'exposition recommandé |
| ISOSpeed | `34867` | Informations sur la valeur de vitesse iso telle que définie dans la norme ISO 12232 |
| ISOSpeedLatitudeYYY | `34868` | Cette balise indique la valeur de latitude de vitesse ISO yyy telle que définie dans la norme ISO 12232 |
| ISOSpeedLatitudeZZZ | `34869` | Cette balise indique la valeur de latitude de vitesse ISO zzz telle que définie dans la norme ISO 12232 |
| CameraOwnerName | `42032` | Contient le nom du propriétaire de la caméra |
| BodySerialNumber | `42033` | Contient le numéro de série du boîtier de l'appareil photo |
| LensMake | `42035` | Cette balise enregistre le fabricant de l'objectif |
| LensModel | `42036` | Cette étiquette enregistre le nom et le numéro de modèle de l'objectif |
| LensSerialNumber | `42037` | Cette étiquette enregistre le numéro de série de l'objectif interchangeable |
| LensSpecification | `42034` | Cette balise indique la distance focale minimale, la distance focale maximale, le nombre F minimal dans la distance focale minimale et le nombre F minimal dans la distance focale maximale |

### Voir également

* espace de noms [Aspose.Imaging.Exif](../../aspose.imaging.exif)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
