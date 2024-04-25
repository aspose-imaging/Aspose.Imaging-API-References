---
title: EmfLogFont
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lobjet LogFont spécifie les attributs de base dune police logique.
type: docs
weight: 3030
url: /fr/aspose.imaging.fileformats.emf.emf.objects/emflogfont/
---
## EmfLogFont class

L'objet LogFont spécifie les attributs de base d'une police logique.

```csharp
public class EmfLogFont : EmfObject
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfLogFont](emflogfont)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [CharSet](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/charset) { get; set; } | Obtient ou définit un entier non signé 8 bits qui spécifie le jeu de glyphes de caractères. Il DOIT être une valeur dans l'énumération WMF CharacterSet ([MS-WMF] section 2.1.1.5). Si le jeu de caractères est inconnu, le traitement du métafichier NE DOIT PAS tenter de traduire ou d'interpréter les chaînes rendues avec cette police. |
| [ClipPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/clipprecision) { get; set; } | Obtient ou définit un entier non signé 8 bits qui spécifie la précision de découpage. La précision de découpage définit comment découper les caractères qui sont partiellement en dehors de la zone de découpage. Il peut s'agir d'un ou plusieurs indicateurs WMF ClipPrecision |
| [Escapement](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/escapement) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie l'angle, en dixièmes de degrés, entre le vecteur d'échappement et l'axe x du périphérique. Le vecteur d'échappement est parallèle à la ligne de base d'une ligne de texte. |
| [Facename](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/facename) { get; set; } | Obtient ou définit un Facename (64 octets) : une chaîne de 32 caractères Unicode maximum qui spécifie le nom de la police de la police. Si la longueur de cette chaîne est inférieure à 32 caractères, un NULL de fin DOIT être présent, après quoi le reste de ce champ DOIT être ignoré. |
| [Height](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/height) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la hauteur, en unités logiques, de la cellule ou du caractère de la police. La valeur de hauteur de caractère, également connue sous le nom de taille em, est la valeur de hauteur de cellule de caractère moins la valeur d'interlignage interne. Le mappeur de polices DEVRAIT interpréter la valeur spécifiée dans le champ Hauteur de la manière suivante. |
| [Italic](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/italic) { get; set; } | Obtient ou définit un entier non signé 8 bits qui spécifie une police en italique s'il est défini sur 0x01 ; sinon, il DOIT être défini sur 0x00. |
| [Orientation](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/orientation) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie l'angle, en dixièmes de degrés, entre la ligne de base de chaque caractère et l'axe des x de l'appareil. |
| [OutPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/outprecision) { get; set; } | Obtient ou définit un entier non signé 8 bits qui spécifie la précision de sortie. La précision de sortie définit à quel point la police doit correspondre à la hauteur, la largeur, l'orientation des caractères , l'échappement, le pas et le type de police demandés. Il DOIT être une valeur du WMF OutPrecision enumeration |
| [PitchAndFamily](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/pitchandfamily) { get; set; } | Obtient ou définit un objet WMF PitchAndFamily ([MS-WMF] section 2.2.2.14) qui spécifie le pas et la famille de la police. Les familles de polices décrivent l'apparence d'une police d'une manière générale . Ils sont destinés à spécifier une police lorsque la police spécifiée n'est pas disponible. |
| [Quality](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/quality) { get; set; } | Obtient ou définit un entier non signé 8 bits qui spécifie la qualité de sortie. La qualité de sortie définit à quel point il faut essayer de faire correspondre les attributs de police logique à ceux d'une police physique réelle. Il DOIT être l'une des valeurs de l'énumération WMF FontQuality ([MS-WMF] section 2.1.1.10). |
| [Strikeout](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/strikeout) { get; set; } | Obtient ou définit un entier non signé 8 bits qui spécifie une police barrée si défini sur 0x01 ; sinon, il DOIT être défini sur 0x00. |
| [Underline](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/underline) { get; set; } | Obtient ou définit un entier non signé 8 bits qui spécifie une police soulignée si défini sur 0x01 ; sinon, il DOIT être défini sur 0x00. |
| [Weight](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/weight) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie le poids de la police dans la plage zéro à 1000. Par exemple, 400 est normal et 700 est gras. Si cette valeur est zéro, un poids par défaut peut être utilisé. |
| [Width](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/width) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie la largeur moyenne, en unités logiques, de caractères dans la police. Si la valeur du champ Width est zéro, une valeur appropriée DEVRAIT être calculée à partir d'autres valeurs LogFont pour trouver une police qui a le aspect ratio prévu par le typographe |

### Voir également

* class [EmfObject](../emfobject)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
