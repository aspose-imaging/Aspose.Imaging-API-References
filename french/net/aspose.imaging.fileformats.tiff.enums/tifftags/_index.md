---
title: TiffTags
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lénumération de la balise tiff.
type: docs
weight: 7740
url: /fr/net/aspose.imaging.fileformats.tiff.enums/tifftags/
---
## TiffTags enumeration

L'énumération de la balise tiff.

```csharp
public enum TiffTags
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| SubFileType | `254` | Descripteur de données de sous-fichier. |
| OsubfileType | `255` | [obsolète par TIFF rév. 5.0] Type de données dans le sous-fichier. |
| ImageWidth | `256` | Largeur de l'image en pixels. |
| ImageLength | `257` | Hauteur de l'image en pixels. |
| BitsPerSample | `258` | Bits par canal (échantillon). |
| Compression | `259` | Technique de compression des données. |
| Photometric | `262` | Interprétation photométrique. |
| Thresholding | `263` | [obsolète par TIFF rév. 5.0] Seuil utilisé sur les données. |
| CellWidth | `264` | [obsolète par TIFF rév. 5.0] Largeur de la matrice de tramage. |
| CellLength | `265` | [obsolète par TIFF rév. 5.0] Hauteur de la matrice de tramage. |
| FillOrder | `266` | Ordre des données dans un octet. |
| DocumentName | `269` | Nom du document qui contient l'image. |
| ImageDescription | `270` | Informations sur l'image. |
| Make | `271` | Nom du fabricant du scanner. |
| Model | `272` | Nom/numéro du modèle de scanner. |
| StripOffsets | `273` | Décalages des bandes de données. |
| Orientation | `274` | [obsolète par TIFF rév. 5.0] Orientation des images. |
| SamplesPerPixel | `277` | Échantillons par pixel. |
| RowsPerStrip | `278` | Lignes par bande de données. |
| StripByteCounts | `279` | Nombre d'octets pour les bandes. |
| MinSampleValue | `280` | [obsolète par TIFF rév. 5.0] Valeur d'échantillon minimale. |
| MaxSampleValue | `281` | [obsolète par TIFF rév. 5.0] Valeur d'échantillon maximale. |
| Xresolution | `282` | Pixels/résolution en x. |
| Yresolution | `283` | Pixels/résolution en y. |
| PlanarConfig | `284` | Organisation du stockage. |
| PageName | `285` | L'image du nom de la page provient de. |
| Xposition | `286` | X décalage de page de l'image lhs. |
| Yposition | `287` | décalage de page Y de l'image lhs. |
| FreeOffsets | `288` | [obsolète par TIFF rév. 5.0] Décalage d'octet par rapport au bloc libre. |
| FreeByteCounts | `289` | [obsolète par TIFF rév. 5.0] Tailles des blocs libres. |
| GrayResponseUnit | `290` | [obsolète par TIFF rév. 6.0] Précision de la courbe d'échelle de gris. |
| GrayResponseCurve | `291` | [obsolète par TIFF rév. 6.0] Courbe de réponse en échelle de gris. |
| T4Options | `292` | TIFF 6.0 alias de nom propre pour GROUP3OPTIONS. Options pour le codage de fax CCITT Groupe 3. 32 bits indicateurs. |
| T6Options | `293` | Options pour le codage de fax CCITT Groupe 4. 32 bits d'indicateur. TIFF 6.0 alias de nom propre pour GROUP4OPTIONS. |
| ResolutionUnit | `296` | Unités de résolutions. |
| PageNumber | `297` | Numéros de page de plusieurs pages. |
| ColorResponseUnit | `300` | [obsolète par TIFF rév. 6.0] Précision de la courbe de couleur. |
| TransferFunction | `301` | Info colorimétrie. |
| Software | `305` | Nom et version. |
| DateTime | `306` | Date et heure de création. |
| Artist | `315` | Créateur de l'image. |
| HostComputer | `316` | Machine où créé. |
| Predictor | `317` | Schéma de prédiction avec LZW. |
| WhitePoint | `318` | Image point blanc. |
| PrimaryChromaticities | `319` | Chromaticités primaires. |
| ColorMap | `320` | Carte RVB pour l'image de la palette. |
| HalftoneHints | `321` | Informations sur les tons clairs et les ombres. |
| TileWidth | `322` | Largeur de mosaïque en pixels. |
| TileLength | `323` | Hauteur de tuile en pixels. |
| TileOffsets | `324` | Décalages des tuiles de données. |
| TileByteCounts | `325` | Nombre d'octets pour les vignettes. |
| BadFaxLines | `326` | Lignes avec un nombre de pixels incorrect. |
| CleanFaxData | `327` | Informations de ligne régénérées. |
| ConsecutiveBadFaxLines | `328` | Max lignes incorrectes consécutives. |
| SubIfd | `330` | Descripteurs de sous-image. |
| InkSet | `332` | Encres dans une image séparée. |
| InkNames | `333` | Noms ASCII des encres. |
| NumberOfInks | `334` | Nombre d'encres. |
| DotRange | `336` | Codes à points 0 % et 100 %. |
| TargetPrinter | `337` | Cible de séparation. |
| ExtraSamples | `338` | Informations sur les échantillons supplémentaires. |
| SampleFormat | `339` | Format d'échantillon de données. |
| SminSampleValue | `340` | Variable MinSampleValue. |
| SmaxSampleValue | `341` | Variable MaxSampleValue. |
| TransferRange | `342` | Variable TransferRange |
| ClipPath | `343` | ClipPath. Introduit post TIFF rev 6.0 par la note technique Adobe TIFF 2. |
| Xclippathunits | `344` | XClipPathUnits. Introduit post TIFF rev 6.0 par la note technique Adobe TIFF 2. |
| Yclippathunits | `345` | YClipPathUnits. Introduit post TIFF rev 6.0 par la note technique Adobe TIFF 2. |
| Indexed | `346` | Indexé. Introduit post TIFF rev 6.0 par Adobe TIFF Technote 3. |
| JpegTables | `347` | Flux de table JPEG. Introduit post TIFF rev 6.0. |
| OpiProxy | `351` | Proxy OPI. Introduit post TIFF rev 6.0 par Adobe TIFF technote. |
| JpegProc | `512` | [obsolète par la note technique #2 qui spécifie un schéma JPEG-in-TIFF révisé] Algorithme de traitement JPEG. |
| JpegInerchangeFormat | `513` | [obsolète par la note technique #2 qui spécifie un schéma JPEG-in-TIFF révisé] Pointeur vers le marqueur SOI. |
| JpegInterchangeFormatLength | `514` | [obsolète par la note technique #2 qui spécifie un schéma JPEG-in-TIFF révisé] longueur du flux JFIF |
| JpegRestartInterval | `515` | [obsolète par la note technique #2 qui spécifie un schéma JPEG-in-TIFF révisé] Longueur de l'intervalle de redémarrage. |
| JpegLosslessPredictors | `517` | [obsolète par la note technique #2 qui spécifie un schéma JPEG-in-TIFF révisé] Prédicteur de proc sans perte. |
| JpegPointTransform | `518` | [obsolète par la note technique #2 qui spécifie un schéma JPEG-in-TIFF révisé] Transformée ponctuelle sans perte. |
| JpegQTables | `519` | [obsolète par la note technique #2 qui spécifie un schéma JPEG-in-TIFF révisé] Décalages de la matrice Q. |
| JpegDCtables | `520` | [obsolète par la note technique #2 qui spécifie un schéma JPEG-in-TIFF révisé] décalages de table DCT. |
| JpegACtables | `521` | [obsolète par la note technique #2 qui spécifie un schéma JPEG-in-TIFF révisé] Décalages du coefficient AC. |
| YcbcrCoefficients | `529` | RVB -&gt; Transformée YCbCr. |
| YcbcrSubSampling | `530` | Facteurs de sous-échantillonnage YCbCr. |
| YcbcrPositioning | `531` | Positionnement du sous-échantillon. |
| ReferenceBlackWhite | `532` | Info colorimétrie. |
| XmlPacket | `700` | paquet XML. Introduit post TIFF rev 6.0 par Adobe XMP Specification, janvier 2004. |
| OpiImageid | `32781` | ID d'image OPI. Introduit post TIFF rev 6.0 par Adobe TIFF technote. |
| Refpts | `32953` | Points de référence des images. Balise privée enregistrée sur Island Graphics. |
| Copyright | `33432` | Chaîne de copyright. Cette balise est répertoriée dans le TIFF rev. 6.0 avec propriétaire inconnu. |
| PhotoshopResources | `34377` | Ressources d'images Photoshop. |
| IccProfile | `34675` | Le profil de périphérique ICC intégré |
| ExifIfdPointer | `34665` | Un pointeur vers l'IFD Exif. |
| XPTitle | `40091` | Informations sur l'image, utilisées par l'Explorateur Windows. LeXPTitle est ignoré par l'Explorateur Windows si leImageDescription la balise existe. |
| XPComment | `40092` | Commentaire sur l'image, utilisé par l'Explorateur Windows. |
| XPAuthor | `40093` | Image Author, utilisé par Windows Explorer. LeXPAuthor est ignoré par l'Explorateur Windows si leArtist la balise existe. |
| XPKeywords | `40094` | Mots clés d'image, utilisés par l'Explorateur Windows. |
| XPSubject | `40095` | Image du sujet, utilisée par l'Explorateur Windows. |

### Voir également

* espace de noms [Aspose.Imaging.FileFormats.Tiff.Enums](../../aspose.imaging.fileformats.tiff.enums)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
