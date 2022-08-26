---
title: EmfPlusSetTsGraphics
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EmfPlusSetTSGraphics spécifie létat dun contexte de périphérique graphique pour un serveur Terminal Server.
type: docs
weight: 6410
url: /fr/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---
## EmfPlusSetTsGraphics class

L'enregistrement EmfPlusSetTSGraphics spécifie l'état d'un contexte de périphérique graphique pour un serveur Terminal Server.

```csharp
public sealed class EmfPlusSetTsGraphics : EmfPlusTerminalServerRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfPlusSetTsGraphics](emfplussettsgraphics)(EmfPlusRecord) | Initialise une nouvelle instance du[`EmfPlusSetTsGraphics`](../emfplussettsgraphics) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AntiAliasMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/antialiasmode) { get; set; } | Obtient ou définit un entier non signé 8 bits qui spécifie la qualité du rendu des lignes, y compris le type d'anticrénelage des lignes. Il DOIT être défini dans l'énumération SmoothingMode (section 2.1.1.28). |
| [BasicVgaColors](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/basicvgacolors) { get; } | Obtient une valeur indiquant si [couleurs vga de base]. Si défini, la palette ne contient que les couleurs VGA de base. |
| [CompositingMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingmode) { get; set; } | Obtient ou définit un entier non signé de 8 bits qui spécifie comment les couleurs source sont combinées avec les couleurs d'arrière-plan. Il DOIT être une valeur dans l'énumération CompositingMode (section 2.1.1.5). |
| [CompositingQuality](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingquality) { get; set; } | Obtient ou définit un entier non signé de 8 bits qui spécifie le degré de lissage à appliquer aux lignes, aux courbes et aux bords des zones remplies pour les faire apparaître plus continus ou nettement définis. Il DOIT être une valeur dans l'énumération CompositingQuality (section 2.1.1.6). |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Obtient ou définit un entier non signé 32 bits qui DOIT définir le nombre aligné sur 32 bits de octets de données dans le champ RecordData qui suit. Ce numéro n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| [FilterType](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/filtertype) { get; set; } | Obtient ou définit un entier non signé de 8 bits qui spécifie comment la mise à l'échelle, y compris l'étirement et la réduction, est effectuée. Il DOIT être une valeur dans l'énumération FilterType (section 2.1.1.11). |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont l'opération doit être effectuée et sur la structure de l'enregistrement. |
| [HavePalette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/havepalette) { get; } | Obtient une valeur indiquant si [have palette]. S'il est défini, cet enregistrement contient un objet EmfPlusPalette (section 2.2.2.28) dans le champ Palette suivant les données d'état graphique. |
| [Palette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/palette) { get; set; } | Obtient ou définit un objet EmfPlusPalette facultatif. |
| [PixelOffset](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/pixeloffset) { get; set; } | Obtient ou définit un entier non signé de 8 bits qui spécifie la qualité globale de l'image et du processus de rendu du texte. Il DOIT être une valeur dans l'énumération PixelOffsetMode (section 2.1.1.26). |
| [RenderOriginX](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginx) { get; set; } | Obtient ou définit un entier signé 16 bits, qui est la coordonnée horizontale de l' origine pour le rendu des matrices de demi-teintes et de tramage. |
| [RenderOriginY](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginy) { get; set; } | Obtient ou définit un entier signé 16 bits, qui est la coordonnée verticale de l'origine pour le rendu des matrices de demi-teintes et de tramage. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le nombre d'octets alignés sur 32 bits dans l'enregistrement entier, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| [TextContrast](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textcontrast) { get; set; } | Obtient ou définit un entier non signé 16 bits qui spécifie la valeur de correction gamma utilisée pour le rendu du texte anticrénelé et ClearType. Cette valeur DOIT être comprise entre 0 et 12 inclus. |
| [TextRenderHint](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textrenderhint) { get; set; } | Obtient ou définit un entier non signé de 8 bits qui spécifie la qualité du rendu text , y compris le type d'anticrénelage du texte. Il DOIT être défini dans l'énumération TextRenderingHint (section 2.1.1.32). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |
| [WorldToDevice](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/worldtodevice) { get; set; } | Obtient ou définit un objet EmfPlusTransformMatrix 192 bits (section 2.2.2.47) qui spécifie les transformations de l'espace mondial vers l'espace périphérique. |

### Voir également

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
