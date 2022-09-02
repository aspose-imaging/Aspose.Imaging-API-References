---
title: WmfLogColorSpace
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lobjet LogColorSpace spécifie un espace colorimétrique logique pour le contexte de périphérique de lecture  qui peut être le nom dun profil de couleur en caractères ASCII.
type: docs
weight: 8750
url: /fr/net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/
---
## WmfLogColorSpace class

L'objet LogColorSpace spécifie un espace colorimétrique logique pour le contexte de périphérique de lecture , qui peut être le nom d'un profil de couleur en caractères ASCII.

```csharp
public class WmfLogColorSpace : MetaObject
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [WmfLogColorSpace](wmflogcolorspace)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [ColorSpaceType](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/colorspacetype) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie le type d'espace colorimétrique . Il DOIT être défini dans l'énumération LogicalColorSpace (section 2.1.1.14). Si cette valeur est LCS_sRGB ou LCS_WINDOWS_COLOR_SPACE, l'espace colorimétrique sRGB DOIT être utilisé. |
| [Endpoints](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/endpoints) { get; set; } | Obtient ou définit un objet CIEXYZTriple (section 2.2.2.7) qui définit les coordonnées de chromaticité CIE x, y et z des trois couleurs qui correspondent au RVBendpoints pour l'espace colorimétrique logical associé au bitmap. Si le [`ColorSpaceType`](./colorspacetype) le champ ne spécifie pas LCS_CALIBRATED_RGB, ce champ DOIT être ignoré. |
| [Filename](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/filename) { get; set; } | Obtient ou définit une chaîne de caractères ASCII facultative qui spécifie le nom d'un fichier contenant un profil de couleur. Si un nom de fichier est spécifié et que le[`ColorSpaceType`](./colorspacetype) est défini sur LCS_CALIBRATED_RGB, les autres champs de cette structure DEVRAIENT être ignorés. |
| [GammaBlue](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammablue) { get; set; } | Obtient ou définit une valeur à virgule fixe de 32 bits qui définit la courbe de réponse toned pour le bleu. Si la[`ColorSpaceType`](./colorspacetype) field ne spécifie pas LCS_CALIBRATED_RGB, ce champ DOIT être ignoré. |
| [GammaGreen](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammagreen) { get; set; } | Obtient ou définit une valeur à virgule fixe 32 bits qui définit la courbe de réponse toned pour le vert. Si la[`ColorSpaceType`](./colorspacetype) field ne spécifie pas LCS_CALIBRATED_RGB, ce champ DOIT être ignoré. |
| [GammaRed](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammared) { get; set; } | Obtient ou définit une valeur à virgule fixe 32 bits qui définit la courbe de réponse toned pour le rouge. Si la[`ColorSpaceType`](./colorspacetype) field ne spécifie pas LCS_CALIBRATED_RGB, ce champ DOIT être ignoré. |
| [Intent](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/intent) { get; set; } | Obtient ou définit un entier signé 32 bits qui définit l'intention de mappage de gamme . Il DOIT être défini dans l'énumération GamutMappingIntent (section 2.1.1.11). |
| [Signature](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/signature) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le signature d'objets de l'espace colorimétrique ; il DOIT être défini sur la valeur 0x50534F43, qui est le codage ASCII de la chaîne "PSOC". |
| [Size](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/size) { get; set; } | Obtient ou définit un entier non signé 32 bits qui définit le size de cet objet, en octets. |
| [Version](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/version) { get; set; } | Obtient ou définit un entier non signé 32 bits qui définit a version Numéro; il DOIT être 0x00000400. |

### Remarques

Les champs Endpoints, GammaRed, GammaGreen et GammaBlue sont utilisés pour spécifier un espace colorimétrique logique. Le champ Points de terminaison est un objet CIEXYZTriple qui contient les valeurs x, y et z du point de terminaison RVB de l'espace colorimétrique . La relation entre les valeurs tri-stimulus X,Y,Z et valeurs de chromaticité x,y,z est exprimée comme suit. x = X/(X+Y+Z) y = Y/(X+Y+Z) z = Z/(X+Y+Z) Les champs GammaRed, GammaGreen et GammaBlue contiennent des valeurs en "8.8 point fixe" format, qui est une technique pour représentant des nombres non entiers. Chaque valeur se compose d'une amplitude de zéroextended de 8 bits suivie d'une fraction de 8 bits, avec les 16 bits combinés décalés vers la gauche de 8 bits. Ainsi, en 32 bits, la valeur réelle NF est 00000000nnnnnnnnffffffff00000000, où "nnnnnnnn" et "ffffffff" sont des représentations binaires de N et F, respectivement. Par exemple, pour The Numéro réel 10.5, Nnnnnnnn serait 00001010 (binaire 10) et FFFFFFFFF serait 00000101 (binaire 5), et la valeur binaire complète de 32 bits

### Voir également

* class [MetaObject](../../aspose.imaging.fileformats.emf/metaobject)
* espace de noms [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
