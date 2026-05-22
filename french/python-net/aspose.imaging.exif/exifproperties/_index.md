---
title: "ExifProperties Énumération"
type: docs
weight: 190
url: /fr/python-net/aspose.imaging.exif/exifproperties/
---

Liste des balises Exif

**Module:** [aspose.imaging.exif](/imaging/python-net/aspose.imaging.exif/)

**Full Name:** aspose.imaging.exif.ExifProperties

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| APERTURE_VALUE | La valeur d'ouverture de l'objectif. |
| ARTIST | Cette balise enregistre le nom du propriétaire de l'appareil, du photographe ou du créateur de l'image. Le format détaillé n'est pas spécifié, mais il est recommandé d'écrire l'information comme dans l'exemple ci‑dessous pour faciliter l'interopérabilité. Lorsqu'il n'est pas renseigné, il est considéré comme inconnu. Ex.) \"Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James\" |
| BITS_PER_SAMPLE | Le nombre de bits par composant d'image. Dans cette norme chaque composant de l'image est de 8 bits, ainsi la valeur pour cette balise est 8. |
| BODY_SERIAL_NUMBER | Contient le numéro de série du boîtier de l'appareil |
| BRIGHTNESS_VALUE | La valeur de luminosité. |
| CAMERA_OWNER_NAME | Contient le nom du propriétaire de l'appareil |
| CFA_PATTERN | Indique le motif géométrique du réseau de filtres de couleur (CFA) du capteur d'image lorsqu'un capteur couleur à puce unique est utilisé. Cela ne s'applique pas à toutes les méthodes de détection. |
| COLOR_SPACE | La balise d'information d'espace colorimétrique (ColorSpace) est toujours enregistrée comme le spécificateur d'espace colorimétrique. |
| COMPONENTS_CONFIGURATION | La configuration des composants. |
| COMPRESSED_BITS_PER_PIXEL | Spécifique aux données compressées ; indique les bits compressés par pixel. |
| COMPRESSION | Le schéma de compression utilisé pour les données d'image. Lorsqu'une image principale est compressée en JPEG, cette désignation n'est pas nécessaire et est omise. |
| CONTRAST | Cette balise indique la direction du traitement du contraste appliqué par l'appareil photo lors de la prise de vue. |
| COPYRIGHT | Informations de droit d'auteur. Dans cette norme, la balise est utilisée pour<br/>                indiquer les droits d'auteur du photographe et de l'éditeur. Il s'agit<br/>                de l'avis de droit d'auteur de la personne ou de l'organisation réclamant<br/>                des droits sur l'image. La déclaration de droit d'auteur d'interopérabilité<br/>                incluant la date et les droits doit être écrite dans ce<br/>                champ ; par ex., "Copyright, John Smith, 19xx. Tous droits<br/>                réservés.". Dans cette norme, le champ enregistre les droits d'auteur du<br/>                photographe et de l'éditeur, chacun étant enregistré dans une<br/>                partie distincte de la déclaration. Lorsqu'il existe une distinction claire<br/>                entre les droits d'auteur du photographe et de l'éditeur, ceux-ci doivent être<br/>                écrits dans l'ordre photographe suivi du droit d'auteur de l'éditeur,<br/>                séparés par NULL (dans ce cas, comme la déclaration se termine également par<br/>                un NULL, il y a deux codes NULL). Lorsque seul le droit d'auteur du photographe<br/>                est fourni, il se termine par un code NULL. Lorsque seul le droit d'auteur de l'éditeur est fourni, la partie du droit d'auteur du photographe<br/>                consiste en un espace suivi d'un code NULL de terminaison, puis<br/>                le droit d'auteur de l'éditeur est donné. Lorsque le champ est laissé vide, il est<br/>                considéré comme inconnu. |
| CUSTOM_RENDERED | Cette balise indique l'utilisation d'un traitement spécial sur les données d'image, tel qu'un rendu orienté vers la sortie. Lorsque un traitement spécial est effectué, le lecteur doit désactiver ou minimiser tout traitement supplémentaire. |
| DATE_TIME | La date et l'heure de création de l'image. Dans la norme Exif, il s'agit de la date et l'heure à laquelle le fichier a été modifié. |
| DATE_TIME_DIGITIZED | La date et l'heure de numérisation. |
| DATE_TIME_ORIGINAL | La date et l'heure auxquelles les données d'image originales ont été générées. |
| DEVICE_SETTING_DESCRIPTION | Cette balise indique les informations sur les conditions de prise de vue d'un modèle d'appareil photo particulier. La balise est utilisée uniquement pour indiquer les conditions de prise de vue dans le lecteur. |
| DIGITAL_ZOOM_RATIO | Cette balise indique le rapport de zoom numérique lors de la prise de l'image. Si le numérateur de la valeur enregistrée est 0, cela indique que le zoom numérique n'a pas été utilisé. |
| EXIF_IFD_POINTER | Un pointeur vers l'Exif IFD. En interopérabilité, l'Exif IFD a la même structure que celle de l'IFD spécifié dans le TIFF. Ordinairement, cependant, il ne contient pas de données d'image comme dans le cas du TIFF. |
| EXIF_VERSION | La version Exif. |
| EXPOSURE_BIAS_VALUE | La valeur du biais d'exposition. |
| EXPOSURE_INDEX | Indique l'indice d'exposition sélectionné sur l'appareil photo ou le dispositif d'entrée au moment où l'image est capturée. |
| EXPOSURE_MODE | Cette balise indique le mode d'exposition défini lors de la prise de la photo. En mode de bracketing automatique, l'appareil photo capture une série de cadres de la même scène avec différents réglages d'exposition. |
| EXPOSURE_PROGRAM | La classe du programme utilisé par l'appareil photo pour régler l'exposition lors de la prise de la photo. |
| EXPOSURE_TIME | Temps d'exposition, exprimé en secondes. |
| FILE_SOURCE | La source du fichier. |
| FLASH | Indique l'état du flash lors de la prise de la photo. |
| FLASHPIX_VERSION | La version du format Flashpix prise en charge par un fichier FPXR. |
| FLASH_ENERGY | Indique l'énergie du stroboscope au moment où l'image est capturée, mesurée en Beam Candle Power Seconds (BCPS). |
| FOCAL_LENGTH | La longueur focale réelle de l'objectif, en mm. |
| FOCAL_LENGTH_IN_35_MM_FILM | Cette balise indique la longueur focale équivalente en supposant un appareil photo à film 35 mm, en mm. Une valeur de 0 signifie que la longueur focale est inconnue. Notez que cette balise diffère de la balise FocalLength. |
| FOCAL_PLANE_RESOLUTION_UNIT | Indique l'unité de mesure de FocalPlaneXResolution et FocalPlaneYResolution. Cette valeur est identique à celle de ResolutionUnit. |
| FOCAL_PLANE_X_RESOLUTION | Indique le nombre de pixels dans la largeur de l'image (X) par unité de résolution du plan focal sur le plan focal de l'appareil photo. |
| FOCAL_PLANE_Y_RESOLUTION | Indique le nombre de pixels dans la hauteur de l'image (Y) par unité de résolution du plan focal sur le plan focal de l'appareil photo. |
| F_NUMBER | Le nombre F. |
| GAIN_CONTROL | Cette balise indique le degré d'ajustement global du gain de l'image. |
| GAMMA | Valeur gamma |
| GPSDOP | Indique le GPS DOP (degré de précision des données). Une valeur HDOP est écrite lors d'une mesure bidimensionnelle,<br/>                et PDOP lors d'une mesure tridimensionnelle. |
| GPS_ALTITUDE | Indique l'altitude basée sur la référence dans GPSAltitudeRef. L'altitude est exprimée comme une valeur RATIONAL.<br/>                L'unité de référence est le mètre. |
| GPS_ALTITUDE_REF | Indique l'altitude utilisée comme altitude de référence. Si la référence est le niveau de la mer et que l'altitude est au-dessus du niveau de la mer,<br/>                0 est donné. Si l'altitude est en dessous du niveau de la mer, une valeur de 1 est donnée et l'altitude est indiquée comme une valeur absolue dans<br/>                la balise GPSAltitude. |
| GPS_AREA_INFORMATION | Une chaîne de caractères enregistrant le nom de la zone GPS. Le premier octet indique<br/>                le code de caractère utilisé, suivi du nom de la zone GPS. |
| GPS_DATE_STAMP | Une chaîne de caractères enregistrant les informations de date et d'heure relatives à UTC<br/>                (Temps Universel Coordonné). Le format est AAAA:MM:JJ. |
| GPS_DEST_BEARING | Indique l'azimut vers le point de destination. L'intervalle des valeurs va de 0,00 à 359,99. |
| GPS_DEST_BEARING_REF | Indique la référence utilisée pour donner l'azimut vers le point de destination. 'T' désigne la direction vraie et 'M' est<br/>                la direction magnétique. |
| GPS_DEST_DISTANCE | Indique la distance jusqu'au point de destination. |
| GPS_DEST_DISTANCE_REF | Indique l'unité utilisée pour exprimer la distance jusqu'au point de destination. 'K', 'M' et 'N' représentent les kilomètres, les miles<br/>                et les nœuds. |
| GPS_DEST_LATITUDE | Indique la latitude du point de destination. La latitude est exprimée sous forme de trois valeurs RATIONAL donnant les<br/>                degrés, minutes et secondes, respectivement. Si la latitude est exprimée en degrés, minutes et secondes, un format typique serait dd/1,mm/1,ss/1. Lorsque les degrés et minutes sont utilisés et, par exemple, que des fractions de minutes sont<br/>                données avec deux décimales, le format serait dd/1,mmmm/100,0/1. |
| GPS_DEST_LATITUDE_REF | Indique si la latitude du point de destination est une latitude nord ou sud. La valeur ASCII 'N' indique la latitude nord<br/>                et 'S' indique la latitude sud. |
| GPS_DEST_LONGITUDE | Indique la longitude du point de destination. La longitude est exprimée sous forme de trois valeurs RATIONAL donnant les<br/>                degrés, minutes et secondes, respectivement. Si la longitude est exprimée en degrés, minutes et secondes, un format typique serait ddd/1,mm/1,ss/1. Lorsque les degrés et minutes sont utilisés et, par exemple, que des fractions de minutes sont<br/>                données avec deux décimales, le format serait ddd/1,mmmm/100,0/1. |
| GPS_DEST_LONGITUDE_REF | Indique si la longitude du point de destination est orientée à l'est ou à l'ouest. Le caractère ASCII 'E' indique l'est,<br/>                et 'W' indique l'ouest. |
| GPS_DIFFERENTIAL | Indique si une correction différentielle est appliquée au récepteur GPS. |
| GPS_IFD_POINTER | Le pointeur gps ifd. |
| GPS_IMG_DIRECTION | Indique la direction de l'image lorsqu'elle a été capturée. La plage de valeurs va de 0.00 à 359.99. |
| GPS_IMG_DIRECTION_REF | Indique la référence utilisée pour donner la direction de l'image lorsqu'elle est capturée. 'T' désigne la direction vraie et 'M' est<br/>                la direction magnétique. |
| GPS_LATITUDE | Indique la latitude. La latitude est exprimée sous forme de trois valeurs RATIONAL donnant les degrés, minutes et<br/>                secondes, respectivement. Si la latitude est exprimée en degrés, minutes et secondes, un format typique serait<br/>                dd/1,mm/1,ss/1. Lorsque les degrés et minutes sont utilisés et, par exemple, que des fractions de minutes sont données avec deux<br/>                décimales, le format serait dd/1,mmmm/100,0/1. |
| GPS_LATITUDE_REF | Indique si la latitude est nord ou sud. |
| GPS_LONGITUDE | Indique la longitude. La longitude est exprimée sous forme de trois valeurs RATIONAL donnant les degrés, minutes et<br/>                secondes, respectivement. Si la longitude est exprimée en degrés, minutes et secondes, un format typique serait<br/>                ddd/1,mm/1,ss/1. Lorsque les degrés et minutes sont utilisés et, par exemple, que des fractions de minutes sont données avec deux<br/>                décimales, le format serait ddd/1,mmmm/100,0/1. |
| GPS_LONGITUDE_REF | Indique si la longitude est orientée à l'est ou à l'ouest. |
| GPS_MAP_DATUM | Indique les données de levé géodésique utilisées par le récepteur GPS. |
| GPS_MEASURE_MODE | Indique le mode de mesure GPS. - 2- ou 3- dimensionnel. |
| GPS_PROCESSING_METHOD | Une chaîne de caractères enregistrant le nom de la méthode utilisée pour la localisation.<br/>                Le premier octet indique le code de caractères utilisé, suivi du nom<br/>                de la méthode. |
| GPS_SATELLITES | Indique les satellites GPS utilisés pour les mesures. Cette balise peut être utilisée pour décrire le nombre de satellites,<br/>                leur numéro d'ID, l'angle d'élévation, l'azimut, le SNR et d'autres informations en notation ASCII. Le format n'est pas<br/>                spécifié. Si le récepteur GPS est incapable de prendre des mesures, la valeur de la balise doit être définie sur NULL. |
| GPS_SPEED | Indique la vitesse du mouvement du récepteur GPS. |
| GPS_SPEED_REF | Indique l'unité utilisée pour exprimer la vitesse du mouvement du récepteur GPS. 'K', 'M' et 'N' représentent respectivement les kilomètres par<br/>                heure, les miles par heure et les nœuds. |
| GPS_STATUS | Indique l'état du récepteur GPS lors de l'enregistrement de l'image. |
| GPS_TIMESTAMP | Indique l'heure en UTC (Temps Universel Coordonné). Le horodatage est exprimé sous forme de trois valeurs RATIONAL<br/>                donnant l'heure, la minute et la seconde. |
| GPS_TRACK | Indique la direction du mouvement du récepteur GPS. L'intervalle des valeurs va de 0,00 à 359,99. |
| GPS_TRACK_REF | Indique la référence pour donner la direction du mouvement du récepteur GPS. 'T' désigne la direction vraie et 'M' est<br/>                la direction magnétique. |
| GPS_VERSION_ID | Indique la version de GPSInfoIFD. |
| IMAGE_DESCRIPTION | Une chaîne de caractères donnant le titre de l'image. Cela peut être un commentaire tel que "1988 company picnic" ou similaire. |
| IMAGE_LENGTH | Le nombre de lignes de données d'image. |
| IMAGE_UNIQUE_ID | L'identifiant unique de l'image. |
| IMAGE_WIDTH | Le nombre de colonnes des données d'image, égal au nombre de pixels par ligne. |
| ISO_SPEED | Informations sur la valeur de vitesse ISO telle que définie dans la norme ISO 12232. |
| ISO_SPEED_LATITUDE_YYY | Cette balise indique la valeur de latitude de vitesse ISO yyy telle que définie dans la norme ISO 12232. |
| ISO_SPEED_LATITUDE_ZZZ | Cette balise indique la valeur de latitude de vitesse ISO zzz telle que définie dans la norme ISO 12232. |
| JPEG_INTERCHANGE_FORMAT | Le décalage vers l'octet de départ (SOI) des données de vignette JPEG compressées. Ceci n'est pas utilisé pour les données JPEG de l'image principale. |
| JPEG_INTERCHANGE_FORMAT_LENGTH | Le nombre d'octets des données de vignette JPEG compressées. Ceci n'est pas utilisé pour les données JPEG de l'image principale. Les vignettes JPEG ne sont pas divisées mais sont enregistrées comme un flux JPEG continu du SOI à l'EOI. Les marqueurs Appn et COM ne doivent pas être enregistrés. Les vignettes compressées doivent être enregistrées dans un maximum de 64 Ko, y compris toutes les autres données à enregistrer dans l'APP1. |
| LENS_MAKE | Cette balise enregistre le fabricant de l'objectif. |
| LENS_MODEL | Cette balise enregistre le nom du modèle de l'objectif et le numéro du modèle. |
| LENS_SERIAL_NUMBER | Cette balise enregistre le numéro de série de l'objectif interchangeable. |
| LENS_SPECIFICATION | Cette balise indique la distance focale minimale, la distance focale maximale, le nombre F minimal à la distance focale minimale et le nombre F minimal à la distance focale maximale. |
| LIGHT_SOURCE | Le type de source lumineuse. |
| MAKE | Le fabricant de l'équipement d'enregistrement. Il s'agit du fabricant du DSC, du scanner, du numériseur vidéo ou de tout autre équipement ayant généré l'image. Lorsque le champ est laissé vide, il est considéré comme inconnu. |
| MAKER_NOTE | Une balise pour les fabricants d'outils Exif afin d'enregistrer toute information souhaitée. Le contenu dépend du fabricant, mais cette balise ne doit pas être utilisée à d'autres fins que celle prévue. |
| MAX_APERTURE_VALUE | La valeur d'ouverture maximale. |
| METERING_MODE | Le mode de mesure. |
| MODEL | Le nom ou le numéro de modèle de l'équipement. Il s'agit du nom ou du numéro de modèle du DSC, du scanner, du numériseur vidéo ou de tout autre équipement qui a généré l'image. Lorsqu'il est laissé vide, il est considéré comme inconnu. |
| OECF | Indique la fonction de conversion opto‑électrique (OECF) spécifiée dans la norme ISO 14524. |
| ORIENTATION | L'orientation de l'image vue en termes de lignes et de colonnes. |
| PHOTOGRAPHIC_SENSITIVITY | Indique la vitesse ISO et la latitude ISO de l'appareil photo ou du dispositif d'entrée, comme spécifié dans la norme ISO 12232. |
| PHOTOMETRIC_INTERPRETATION | La composition des pixels. |
| PIXEL_X_DIMENSION | Informations spécifiques aux données compressées. Lorsqu'un fichier compressé est enregistré, la largeur valide de l'image utile doit être enregistrée dans cette balise, qu'il y ait des données de remplissage ou un marqueur de redémarrage. |
| PIXEL_Y_DIMENSION | Informations spécifiques aux données compressées. Lorsqu'un fichier compressé est enregistré, la hauteur valide de l'image utile doit être enregistrée dans cette balise. |
| PLANAR_CONFIGURATION | Indique si les composants des pixels sont enregistrés dans un format chunky ou planar. Si ce champ n'existe pas, la valeur par défaut du TIFF de 1 (chunky) est supposée. |
| PRIMARY_CHROMATICITIES | La chromaticité des trois couleurs primaires de l'image. Normalement, cette balise n'est pas nécessaire, car l'espace colorimétrique est spécifié dans la balise d'information d'espace colorimétrique ColorSpace. |
| RECOMMENDED_EXPOSURE_INDEX | Indique l'indice d'exposition recommandé |
| REFERENCE_BLACK_WHITE | La valeur du point noir de référence et du point blanc de référence<br/>                valeur. Aucun défaut n'est fourni dans TIFF, mais les valeurs ci-dessous sont données comme défauts ici.<br/>                L'espace colorimétrique est déclaré<br/>                dans une balise d'information d'espace colorimétrique, avec la valeur par défaut<br/>                étant la valeur qui donne les caractéristiques d'image optimales<br/>                Interopérabilité de ces conditions |
| RELATED_SOUND_FILE | Le fichier audio associé. |
| RESOLUTION_UNIT | L'unité de mesure de XResolution et YResolution. La même unité est utilisée pour XResolution et YResolution. Si la résolution de l'image est inconnue, 2 (pouces) est désignée. |
| ROWS_PER_STRIP | Le nombre de lignes par bande. Il s'agit du nombre de lignes dans l'image d'une bande lorsque l'image est divisée en bandes. |
| SAMPLES_PER_PIXEL | Le nombre de composantes par pixel. Comme cette norme s'applique aux images RGB et YCbCr, la valeur définie pour cette balise est 3. |
| SATURATION | Cette balise indique la direction du traitement de saturation appliqué par l'appareil photo lors de la prise de vue. |
| SCENE_CAPTURE_TYPE | Cette balise indique le type de scène qui a été photographié. Elle peut également être utilisée pour enregistrer le mode dans lequel l'image a été prise. |
| SCENE_TYPE | Indique le type de scène. Si un DSC a enregistré l'image, la valeur de cette balise doit toujours être réglée sur 1, indiquant que l'image a été photographiée directement. |
| SENSING_METHOD | Indique le type de capteur d'image sur l'appareil photo ou le dispositif d'entrée. |
| SENSITIVITY_TYPE | Type de sensibilité photographique |
| SHARPNESS | Cette balise indique la direction du traitement de netteté appliqué par l'appareil photo lors de la prise de vue |
| SHUTTER_SPEED_VALUE | La valeur de la vitesse d'obturation. |
| LOGICIEL | Cette balise enregistre le nom et la version du logiciel ou du micrologiciel de l'appareil photo ou du dispositif d'entrée d'image utilisé pour générer l'image. Le format détaillé n'est pas spécifié, mais il est recommandé de suivre l'exemple présenté ci-dessous. Lorsque le champ est laissé vide, il est considéré comme inconnu. |
| SPATIAL_FREQUENCY_RESPONSE | Cette balise enregistre la table de fréquence spatiale de l'appareil photo ou du dispositif d'entrée ainsi que les valeurs SFR dans la direction de la largeur de l'image, de la hauteur de l'image et de la direction diagonale, comme spécifié dans la norme ISO 12233. |
| SPECTRAL_SENSITIVITY | Indique la sensibilité spectrale de chaque canal de l'appareil photo utilisé. |
| STANDARD_OUTPUT_SENSITIVITY | Indique la sensibilité de sortie standard de l'appareil photo |
| STRIP_BYTE_COUNTS | Le nombre total d'octets dans chaque bande. |
| STRIP_OFFSETS | Pour chaque bande, le décalage en octets de cette bande. Il est recommandé de choisir cela de façon que le nombre d'octets par bande ne dépasse pas 64 Koctets.<br/>                Balise auxiliaire. |
| SUBJECT_AREA | Cette balise indique l'emplacement et la zone du sujet principal dans la scène globale. |
| SUBJECT_DISTANCE | La distance au sujet, exprimée en mètres. |
| SUBJECT_DISTANCE_RANGE | Cette balise indique la distance au sujet. |
| SUBJECT_LOCATION | Indique l'emplacement du sujet principal dans la scène. La valeur de cette balise représente le pixel au centre du sujet principal par rapport au bord gauche, avant le traitement de rotation conformément à la balise Rotation. |
| SUBSEC_TIME | Une balise utilisée pour enregistrer les fractions de seconde pour la balise DateTime. |
| SUBSEC_TIME_DIGITIZED | Une balise utilisée pour enregistrer les fractions de seconde pour la balise DateTimeDigitized. |
| SUBSEC_TIME_ORIGINAL | Une balise utilisée pour enregistrer les fractions de seconde pour la balise DateTimeOriginal. |
| TRANSFER_FUNCTION | Une fonction de transfert pour l'image, décrite sous forme tabulaire. Normalement cette balise n'est pas nécessaire, car l'espace colorimétrique est spécifié dans la balise d'information d'espace colorimétrique ColorSpace. |
| USER_COMMENT | Une balise pour les utilisateurs Exif afin d'écrire des mots‑clés ou des commentaires sur l'image en plus de ceux présents dans ImageDescription, et sans les limitations de jeu de caractères de la balise ImageDescription. |
| WHITE_BALANCE | Cette balise indique le mode de balance des blancs réglé lors de la prise de vue de l'image. |
| WHITE_POINT | La chromaticité du point blanc de l'image. Normalement cette balise n'est pas nécessaire, car l'espace colorimétrique est spécifié dans la balise d'information d'espace colorimétrique ColorSpace. |
| X_RESOLUTION | Le nombre de pixels par ResolutionUnit dans la direction ImageWidth. Lorsque la résolution de l'image est inconnue, 72 [dpi] est indiqué. |
| Y_CB_CR_COEFFICIENTS | Les coefficients matriciels pour la transformation des données d'image de RGB vers YCbCr. |
| Y_CB_CR_POSITIONING | La position des composantes de chrominance par rapport au<br/>                composant de luminance. Ce champ est désigné uniquement pour les<br/>                données JPEG compressées ou les données YCbCr non compressées. La valeur par défaut du TIFF est 1 (centré) ; mais lorsque Y:Cb:Cr = 4:2:2, il est recommandé dans cette norme d'utiliser 2 (co‑situé) pour<br/>                enregistrer les données, afin d'améliorer la qualité de l'image lorsqu'elle est visualisée<br/>                sur des systèmes TV. Lorsque ce champ n'existe pas, le lecteur doit<br/>                supposer la valeur par défaut du TIFF. Dans le cas Y:Cb:Cr = 4:2:0, la<br/>                valeur par défaut du TIFF (centré) est recommandée. Si le lecteur<br/>                ne possède pas la capacité de prendre en charge les deux types de<br/>                YCbCrPositioning, il doit suivre la valeur par défaut du TIFF quel que soit<br/>                la valeur de ce champ. Il est préférable que les lecteurs "<br/>                puissent prendre en charge à la fois le positionnement centré et co‑situé. |
| Y_CB_CR_SUB_SAMPLING | Le rapport d'échantillonnage des composantes de chrominance par rapport à la composante de luminance. |
| Y_RESOLUTION | Le nombre de pixels par ResolutionUnit dans la direction ImageLength. La même valeur que XResolution est indiquée. |
