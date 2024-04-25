---
title: EmfPlgBlt
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EMR_PLGBLT spécifie un transfert en bloc de pixels dun bitmap source vers un parallélogramme de destination  avec lapplication dun bitmap de masque de couleur.
type: docs
weight: 3950
url: /fr/aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---
## EmfPlgBlt class

L'enregistrement EMR_PLGBLT spécifie un transfert en bloc de pixels d'un bitmap source vers un parallélogramme de destination , avec l'application d'un bitmap de masque de couleur.

```csharp
public sealed class EmfPlgBlt : EmfBitmapRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfPlgBlt](emfplgblt)(EmfRecord) | Initialise une nouvelle instance du[`EmfPlgBlt`](../emfplgblt) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AptlDest](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/aptldest) { get; set; } | Obtient ou définit un tableau de trois objets WMF PointL ([MS-WMF] section 2.2.2.15) qui spécifie trois coins d'une zone de destination de parallélogramme pour le transfert de bloc. Le coin supérieur gauche du rectangle source est mappé sur le premier point de ce tableau, le coin supérieur droit au deuxième point et le coin inférieur gauche au troisième point. Le coin inférieur droit du rectangle source est mappé sur le quatrième point implicite du parallélogramme , qui est calculé à partir des trois premiers points (A, B et C) en les traitant comme des vecteurs . D = B + C A |
| [BkSrcArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/bksrcargb32color) { get; set; } | Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8) qui spécifie la couleur d'arrière-plan du bitmap source. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/bounds) { get; set; } | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit le rectangle de délimitation , en unités de périphérique, pour la sortie vers la destination. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/cxsrc) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la largeur logique du rectangle source. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/cysrc) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la hauteur logique du rectangle source. |
| [MaskBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/maskbitmap) { get; set; } | Obtient ou définit un tampon contenant le bitmap de masque, qui ne sont pas requis pour être contigus avec la partie fixe de l'enregistrement EMR_PLGBLT ou entre eux. En conséquence, les champs de ce tampon qui sont étiquetés "UndefinedSpace" sont facultatifs et DOIVENT être ignorés. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtient ou définit la taille de l'enregistrement |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/sourcebitmap) { get; set; } | Obtient ou définit un tampon contenant le bitmap source, qui ne sont pas requis pour être contigus avec la partie fixe de l'enregistrement EMR_PLGBLT ou entre eux. En conséquence, les champs de ce tampon qui sont étiquetés "UndefinedSpace" sont facultatifs et DOIVENT être ignorés. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtient ou définit le type. |
| [UsageMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/usagemask) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie comment interpréter les valeurs de la table de couleurs dans l'en-tête du masque bitmap. Cette valeur DOIT être dans l'énumération DIBColors. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/usagesrc) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie comment interpréter les valeurs de la table de couleurs dans l'en-tête du bitmap source. Cette valeur DOIT être dans le DIBColors enumeration |
| [XFormSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xformsrc) { get; set; } | Obtient ou définit un objet XForm (section 2.2.28) qui spécifie une transformation d'espace universel en espace de page à appliquer au bitmap source. |
| [XMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xmask) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la coordonnée x logique du coin supérieur gauche du bitmap de masque. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xsrc) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la coordonnée x logique du coin supérieur gauche du rectangle source. |
| [YMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/ymask) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la coordonnée y logique du coin supérieur gauche du bitmap de masque. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/ysrc) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la coordonnée y logique du coin supérieur gauche du rectangle source. |

### Voir également

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
