---
title: EmfStretchDiBits
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EMR_STRETCHDIBITS spécifie un transfert en bloc de pixels dun bitmap source vers un rectangle de destination  éventuellement en combinaison avec un motif de pinceau selon une opération raster spécifiée étirant ou comprimant la sortie pour ladapter aux dimensions de la destination si nécessaire.
type: docs
weight: 4600
url: /fr/net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---
## EmfStretchDiBits class

L'enregistrement EMR_STRETCHDIBITS spécifie un transfert en bloc de pixels d'un bitmap source vers un rectangle de destination , éventuellement en combinaison avec un motif de pinceau, selon une opération raster spécifiée, étirant ou comprimant la sortie pour l'adapter aux dimensions de la destination, si nécessaire.

```csharp
public sealed class EmfStretchDiBits : EmfBitmapRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfStretchDiBits](emfstretchdibits)(EmfRecord) | Initialise une nouvelle instance du[`EmfStretchDiBits`](../emfstretchdibits) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BitBltRasterOperation](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/bitbltrasteroperation) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie un code d'opération raster . Ces codes définissent comment les données de couleur du rectangle source doivent être combinées avec les données de couleur du rectangle de destination et éventuellement un motif de pinceau, pour obtenir la couleur finale. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/bounds) { get; set; } | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit le rectangle de délimitation de destination en unités de périphérique. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cxdest) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la largeur logique du rectangle de destination. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cxsrc) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la largeur en pixels du rectangle source. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cydest) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la hauteur logique du rectangle de destination. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cysrc) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la hauteur en pixels du rectangle source. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtient ou définit la taille de l'enregistrement |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/sourcebitmap) { get; set; } | Obtient ou définit un tampon contenant le bitmap source, qui n'a pas besoin d'être contigu à la partie fixe de l'enregistrement EMR_STRETCHDIBITS. En conséquence, les champs de ce tampon qui sont étiquetés "UndefinedSpace" sont facultatifs et DOIVENT être ignorés. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtient ou définit le type. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/usagesrc) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie comment interpréter les valeurs de la table de couleurs dans l'en-tête du bitmap source. Cette valeur DOIT être dans l'énumération DIBColors (section 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/xdest) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la coordonnée x logique du coin supérieur gauche du rectangle de destination. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/xsrc) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la coordonnée x en pixels du coin supérieur gauche du rectangle source. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/ydest) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la coordonnée y logique du coin supérieur gauche du rectangle de destination. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/ysrc) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la coordonnée y en pixels du coin supérieur gauche du rectangle source. |

### Remarques

Cet enregistrement prend en charge les images source aux formats JPEG et PNG. Le champ Compression dans l'en-tête du bitmap source spécifie le format de l'image. Si les signes des champs hauteur et largeur source et destination diffèrent, cet enregistrement spécifie une copie d'image miroir du bitmap source vers la destination. Autrement dit, si cxSrc et cxDest ont signes différents, une image miroir du bitmap source le long de l'axe des x est spécifiée. Si cySrc et cyDest ont des signes différents, une image miroir du bitmap source le long de l'axe y est spécifiée.

### Voir également

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
