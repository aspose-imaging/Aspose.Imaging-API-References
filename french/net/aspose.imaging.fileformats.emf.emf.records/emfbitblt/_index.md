---
title: EmfBitBlt
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EMR_BITBLT spécifie un transfert en bloc de pixels dun bitmap source vers un rectangle de destination  éventuellement en combinaison avec un motif de pinceau selon une opération raster spécifiée.
type: docs
weight: 3250
url: /fr/net/aspose.imaging.fileformats.emf.emf.records/emfbitblt/
---
## EmfBitBlt class

L'enregistrement EMR_BITBLT spécifie un transfert en bloc de pixels d'un bitmap source vers un rectangle de destination , éventuellement en combinaison avec un motif de pinceau, selon une opération raster spécifiée.

```csharp
public sealed class EmfBitBlt : EmfBitmapRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfBitBlt](emfbitblt)(EmfRecord) | Initialise une nouvelle instance du[`EmfBitBlt`](../emfbitblt) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BitBltRasterOperation](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/bitbltrasteroperation) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le code d'opération raster . Ce code définit comment les données de couleur du rectangle source doivent être combinées avec les données de couleur du rectangle de destination et éventuellement un motif de pinceau, pour obtenir la couleur finale. |
| [BkSrcArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/bksrcargb32color) { get; set; } | Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8 qui spécifie la couleur d'arrière-plan du bitmap source. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/bounds) { get; set; } | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit le rectangle de délimitation de destination en unités de périphérique. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/cxdest) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la largeur logique des rectangles source et destination. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/cydest) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la hauteur logique des rectangles source et destination. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtient ou définit la taille de l'enregistrement |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/sourcebitmap) { get; set; } | Obtient ou définit un tampon contenant le bitmap source, qui n'a pas besoin d'être contigu à la partie fixe de l'enregistrement EMR_BITBLT. En conséquence, les champs de ce tampon qui sont étiquetés "UndefinedSpace" sont facultatifs et DOIVENT être ignorés. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtient ou définit le type. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/usagesrc) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie comment interpréter les valeurs de la table de couleurs dans l'en-tête du bitmap source. Cette valeur DOIT être dans l'énumération DIBColors (section 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/xdest) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la coordonnée x logique du coin supérieur gauche du rectangle de destination. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/xformsrc) { get; set; } | Obtient ou définit un objet XForm (section 2.2.28) qui spécifie une transformation d'espace universel en espace de page à appliquer au bitmap source. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/xsrc) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la coordonnée x logique du coin supérieur gauche du rectangle source. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/ydest) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la coordonnée y logique du coin supérieur gauche du rectangle de destination. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/ysrc) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la coordonnée y logique du coin supérieur gauche du rectangle source. |

### Voir également

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
