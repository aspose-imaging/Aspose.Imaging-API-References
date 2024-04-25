---
title: EmfStretchBlt
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EMR_STRETCHBLT spécifie un transfert en bloc de pixels dun bitmap source vers un rectangle de destination  éventuellement en combinaison avec un motif de pinceau selon une opération raster spécifiée étirant ou comprimant la sortie pour ladapter aux dimensions de la destination si nécessaire .
type: docs
weight: 4590
url: /fr/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/
---
## EmfStretchBlt class

L'enregistrement EMR_STRETCHBLT spécifie un transfert en bloc de pixels d'un bitmap source vers un rectangle de destination , éventuellement en combinaison avec un motif de pinceau, selon une opération raster spécifiée, étirant ou comprimant la sortie pour l'adapter aux dimensions de la destination, si nécessaire .

```csharp
public sealed class EmfStretchBlt : EmfBitmapRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfStretchBlt](emfstretchblt#constructor)() | Initialise une nouvelle instance du[`EmfStretchBlt`](../emfstretchblt) classe. |
| [EmfStretchBlt](emfstretchblt#constructor_1)(EmfRecord) | Initialise une nouvelle instance du[`EmfStretchBlt`](../emfstretchblt) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Argb32BkColorSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/argb32bkcolorsrc) { get; set; } | Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8 qui spécifie la couleur d'arrière-plan du bitmap source. |
| [BitBltRasterOperation](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/bitbltrasteroperation) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le code d'opération raster . Ce code définit comment les données de couleur du rectangle source doivent être combinées avec les données de couleur du rectangle de destination et éventuellement un motif de pinceau, pour obtenir la couleur finale |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/bounds) { get; set; } | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit le rectangle de délimitation de destination en unités de périphérique. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cxdest) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la largeur logique du rectangle de destination. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cxsrc) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la largeur logique du rectangle source. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cydest) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la hauteur logique du rectangle de destination. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cysrc) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la hauteur logique du rectangle source. |
| [DestRect](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/destrect) { get; set; } | Obtient ou définit la destination rect. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtient ou définit la taille de l'enregistrement |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/sourcebitmap) { get; set; } | Obtient ou définit un tampon contenant le bitmap source, qui ne doit pas nécessairement être contigu à la partie fixe de l'enregistrement EMR_STRETCHBLT. En conséquence, les champs de ce tampon qui sont étiquetés "UndefinedSpace" sont facultatifs et DOIVENT être ignorés. |
| [SrcRect](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/srcrect) { get; set; } | Obtient ou définit la source rect. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtient ou définit le type. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/usagesrc) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie comment interpréter les valeurs de la table de couleurs dans l'en-tête du bitmap source. Cette valeur DOIT être dans l'énumération DIBColors (section 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xdest) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la coordonnée x logique du coin supérieur gauche du rectangle de destination. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xformsrc) { get; set; } | Obtient ou définit un objet XForm (section 2.2.28) qui spécifie une transformation d'espace universel en espace de page à appliquer au bitmap source. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xsrc) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la coordonnée x logique du coin supérieur gauche du rectangle source. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/ydest) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la coordonnée y logique du coin supérieur gauche du rectangle de destination. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/ysrc) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la coordonnée y logique du coin supérieur gauche du rectangle source. |

### Voir également

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
