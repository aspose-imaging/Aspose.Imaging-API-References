---
title: EmfAlphaBlend
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EMR_ALPHABLEND spécifie un transfert en bloc de pixels dun bitmap source vers un rectangle de destination  y compris les données de transparence alpha selon une opération de fusion spécifiée.
type: docs
weight: 3200
url: /fr/aspose.imaging.fileformats.emf.emf.records/emfalphablend/
---
## EmfAlphaBlend class

L'enregistrement EMR_ALPHABLEND spécifie un transfert en bloc de pixels d'un bitmap source vers un rectangle de destination , y compris les données de transparence alpha, selon une opération de fusion spécifiée.

```csharp
public sealed class EmfAlphaBlend : EmfBitmapRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfAlphaBlend](emfalphablend)(EmfRecord) | Initialise une nouvelle instance du[`EmfAlphaBlend`](../emfalphablend) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BkSrcArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/bksrcargb32color) { get; set; } | Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8 qui spécifie la couleur d'arrière-plan du bitmap source. |
| [BlendFunction](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/blendfunction) { get; set; } | Obtient ou définit une structure qui spécifie les opérations de fusion pour les bitmaps source et de destination |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/bounds) { get; set; } | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit le rectangle de délimitation de destination en unités de périphérique. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cxdest) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la largeur logique du rectangle de destination . Cette valeur DOIT être supérieure à zéro. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cxsrc) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la largeur logique du rectangle source. Cette valeur DOIT être supérieure à zéro. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cydest) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la hauteur logique du rectangle de destination . Cette valeur DOIT être supérieure à zéro. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cysrc) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la hauteur logique du rectangle source . Cette valeur DOIT être supérieure à zéro. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtient ou définit la taille de l'enregistrement |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/sourcebitmap) { get; set; } | Obtient ou définit un tampon contenant le bitmap source, qui n'a pas besoin d'être contigu à la partie fixe de l'enregistrement EMR_ALPHABLEND. En conséquence, les champs de ce tampon qui sont étiquetés "UndefinedSpace" sont facultatifs et DOIVENT être ignorés. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtient ou définit le type. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/usagesrc) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie comment interpréter les valeurs de la table de couleurs dans l'en-tête du bitmap source. Cette valeur DOIT être dans l'énumération DIBColors (section 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/xdest) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la coordonnée x logique du coin supérieur gauche du rectangle de destination. |
| [XformSr](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/xformsr) { get; set; } | Obtient ou définit un objet XForm (section 2.2.28) qui spécifie une transformation d'espace universel en espace de page à appliquer au bitmap source. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/xsrc) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la coordonnée x logique du coin supérieur gauche du rectangle source. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/ydest) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la coordonnée y logique du coin supérieur gauche du rectangle de destination. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/ysrc) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la coordonnée y logique du coin supérieur gauche du rectangle source. |

### Voir également

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
