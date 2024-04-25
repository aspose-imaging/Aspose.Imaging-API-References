---
title: EmfStockObject
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lénumération StockObject spécifie les index des objets graphiques logiques prédéfinis qui peuvent être utilisés dans les opérations graphiques. Les structures spécifiques des objets stock dépendent de limplémentation  cependant les propriétés des objets de stock DEVRAIENT être équivalentes à les propriétés des objets explicitement créés du même type. Ces propriétés sont spécifiées dans la mesure du possible pour les objets de stock définis dans cette énumération.
type: docs
weight: 2860
url: /fr/aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---
## EmfStockObject enumeration

L'énumération StockObject spécifie les index des objets graphiques logiques prédéfinis qui peuvent être utilisés dans les opérations graphiques. Les structures spécifiques des objets stock dépendent de l'implémentation ; cependant, les propriétés des objets de stock DEVRAIENT être équivalentes à les propriétés des objets explicitement créés du même type. Ces propriétés sont spécifiées dans la mesure du possible pour les objets de stock définis dans cette énumération.

```csharp
public enum EmfStockObject
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| WHITE_BRUSH | `-2147483648` | Un pinceau blanc de couleur unie qui équivaut à un pinceau logique (objet LogBrushEx, section 2.2.12) avec les propriétés suivantes : BrushStyle : BS_SOLID (énumération WMF BrushStyle, [MS-WMF] section 2.1.1.4) Couleur : 0x00FFFFFF (objet WMF ColorRef, [MS-WMF] section 2.2.2.8) |
| LTGRAY_BRUSH | `-2147483647` | Un pinceau gris clair de couleur unie qui équivaut à un pinceau logique avec les propriétés suivantes : BrushStyle : BS_SOLID Color : 0x00C0C0C0 |
| GRAY_BRUSH | `-2147483646` | Un pinceau gris de couleur unie qui équivaut à un pinceau logique avec les propriétés suivantes : BrushStyle : BS_SOLID Color : 0x00808080 |
| DKGRAY_BRUSH | `-2147483645` | Un pinceau de couleur unie gris foncé qui équivaut à un pinceau logique avec les propriétés suivantes : BrushStyle : BS_SOLID Color : 0x00404040 |
| BLACK_BRUSH | `-2147483644` | Un pinceau noir de couleur unie qui équivaut à un pinceau logique avec les propriétés suivantes : BrushStyle : BS_SOLID Color : 0x00000000 |
| NULL_BRUSH | `-2147483643` | Un pinceau nul qui équivaut à un pinceau logique avec les propriétés suivantes : BrushStyle : BS_NULL |
| WHITE_PEN | `-2147483642` | Un stylo blanc de couleur unie qui équivaut à un stylo logique (objet LogPen, section 2.2.19) avec les propriétés suivantes : PenStyle : PS_COSMETIC + PS_SOLID (énumération PenStyle, section 2.1.25) ColorRef : 0x00FFFFFF ( objet WMF ColorRef). |
| BLACK_PEN | `-2147483641` | Un stylo noir de couleur unie qui équivaut à un stylo logique avec les propriétés suivantes : PenStyle : PS_COSMETIC + PS_SOLID ColorRef : 0x00000000 |
| NULL_PEN | `-2147483640` | Un stylo nul qui équivaut à un stylo logique avec les propriétés suivantes : PenStyle : PS_NULL |
| OEM_FIXED_FONT | `-2147483638` | Une police de jeu de caractères OEM à largeur fixe qui équivaut à une police logique (objet LogFont, section 2.2.13) avec les propriétés suivantes : Charset : OEM_CHARSET (énumération WMF CharacterSet, [MS-WMF] section 2.1.1.5 ) PitchAndFamily : FF_DONTCARE (énumération WMF FamilyFont, [MS-WMF] section 2.1.1.8) + FIXED_PITCH (énumération WMF PitchFont, [MS-WMF] section 2.1.1.24) |
| ANSI_FIXED_FONT | `-2147483637` | Une police à largeur fixe équivalente à une police logique avec les propriétés suivantes : Charset : ANSI_CHARSET PitchAndFamily : FF_DONTCARE + FIXED_PITCH |
| ANSI_VAR_FONT | `-2147483636` | Une police à largeur variable qui équivaut à une police logique avec les propriétés suivantes : Charset : ANSI_CHARSET PitchAndFamily : FF_DONTCARE + VARIABLE_PITCH |
| SYSTEM_FONT | `-2147483635` | Une police dont la disponibilité est garantie dans le système d'exploitation. La police réelle spécifiée par cette valeur dépend de l'implémentation |
| DEVICE_DEFAULT_FONT | `-2147483634` | La police par défaut fournie par le pilote de périphérique graphique pour le périphérique de sortie actuel. La police réelle spécifiée par cette valeur dépend de l'implémentation |
| DEFAULT_PALETTE | `-2147483633` | La palette par défaut définie pour le périphérique de sortie actuel. La palette réelle spécifiée par cette valeur dépend de l'implémentation |
| SYSTEM_FIXED_FONT | `-2147483632` | Une police à largeur fixe dont la disponibilité est garantie dans le système d'exploitation. La police réelle spécifiée par cette valeur dépend de l'implémentation |
| DEFAULT_GUI_FONT | `-2147483631` | Une police à largeur fixe dont la disponibilité est garantie dans le système d'exploitation. La police réelle spécifiée par cette valeur dépend de l'implémentation |
| DC_BRUSH | `-2147483630` | Le pinceau de couleur unie actuellement sélectionné dans le contexte de l'appareil de lecture |
| DC_PEN | `-2147483629` | Le stylet de couleur unie actuellement sélectionné dans le contexte de l'appareil de lecture |

### Voir également

* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
