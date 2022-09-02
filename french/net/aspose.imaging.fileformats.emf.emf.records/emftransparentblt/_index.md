---
title: EmfTransparentBlt
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EMR_TRANSPARENTBLT spécifie un transfert en bloc de pixels dun bitmap source vers un rectangle de destination  traitant une couleur spécifiée comme transparente étirant ou compressant la sortie pour ladapter aux dimensions de la destination si nécessaire
type: docs
weight: 4640
url: /fr/net/aspose.imaging.fileformats.emf.emf.records/emftransparentblt/
---
## EmfTransparentBlt class

L'enregistrement EMR_TRANSPARENTBLT spécifie un transfert en bloc de pixels d'un bitmap source vers un rectangle de destination , traitant une couleur spécifiée comme transparente, étirant ou compressant la sortie pour l'adapter aux dimensions de la destination, si nécessaire

```csharp
public sealed class EmfTransparentBlt : EmfBitmapRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfTransparentBlt](emftransparentblt)(EmfRecord) | Initialise une nouvelle instance du[`EmfTransparentBlt`](../emftransparentblt) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/bounds) { get; set; } | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit le rectangle de délimitation de destination en unités de périphérique. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cxdest) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la largeur logique du rectangle de destination. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cxsrc) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la largeur logique du rectangle source. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cydest) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la hauteur logique du rectangle de destination. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cysrc) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la hauteur logique du rectangle source. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtient ou définit la taille de l'enregistrement |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/sourcebitmap) { get; set; } | Obtient ou définit un tampon contenant le bitmap source, qui ne doit pas nécessairement être contigu à la partie fixe de l'enregistrement EMR_TRANSPARENTBLT. En conséquence, les champs de ce tampon qui sont étiquetés "UndefinedSpace" sont facultatifs et DOIVENT être ignorés. |
| [SrcBkArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/srcbkargb32color) { get; set; } | Obtient ou définit un objet WMF ColorRef qui spécifie la couleur d'arrière-plan du bitmap source. |
| [TransparentArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/transparentargb32color) { get; set; } | Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8) qui spécifie la couleur du bitmap source à traiter comme transparente. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtient ou définit le type. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/usagesrc) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie comment interpréter les valeurs de la table de couleurs dans l'en-tête du bitmap source. Cette valeur DOIT être dans l'énumération DIBColors (section 2.1.9) |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xdest) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la coordonnée x logique du coin supérieur gauche du rectangle de destination. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xformsrc) { get; set; } | Obtient ou définit un objet XForm (section 2.2.28) qui spécifie une transformation d'espace universel en espace de page à appliquer au bitmap source. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xsrc) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la coordonnée x logique du coin supérieur gauche du rectangle source. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/ydest) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la coordonnée y logique du coin supérieur gauche du rectangle de destination. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/ysrc) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la coordonnée y logique du coin supérieur gauche du rectangle source. |

### Voir également

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
