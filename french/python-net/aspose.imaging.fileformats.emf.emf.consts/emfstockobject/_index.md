---
title: "Énumération EmfStockObject"
type: docs
weight: 330
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---

L'énumération StockObject spécifie les index des objets graphiques logiques prédéfinis <br/>            qui peuvent être utilisés dans les opérations graphiques. Les structures spécifiques des objets stock sont <br/>            dépendantes de l'implémentation ; cependant, les propriétés des objets stock DOIVENT être équivalentes aux <br/>            propriétés des objets créés explicitement du même type. <br/>            Ces propriétés sont spécifiées, lorsque cela est possible, pour les objets stock définis dans cette énumération.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfStockObject

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| ANSI_FIXED_FONT | Une police à largeur fixe équivalente à une police logique avec les propriétés suivantes :<br/>            Charset: ANSI_CHARSET<br/>            PitchAndFamily: FF_DONTCARE + FIXED_PITCH |
| ANSI_VAR_FONT | Une police à largeur variable équivalente à une police logique avec les propriétés suivantes :<br/>            Charset: ANSI_CHARSET<br/>            PitchAndFamily: FF_DONTCARE + VARIABLE_PITCH |
| BLACK_BRUSH | Un pinceau noir, couleur unie, équivalent à un pinceau logique avec les propriétés suivantes :<br/>            BrushStyle: BS_SOLID<br/>            Color: 0x00000000 |
| BLACK_PEN | Un crayon noir, couleur unie, équivalent à un crayon logique avec les propriétés suivantes :<br/>            PenStyle: PS_COSMETIC + PS_SOLID<br/>            ColorRef: 0x00000000 |
| DC_BRUSH | Le pinceau couleur unie actuellement sélectionné dans le contexte du dispositif de lecture |
| DC_PEN | Le crayon couleur unie actuellement sélectionné dans le contexte du dispositif de lecture |
| DEFAULT_GUI_FONT | Une police à largeur fixe garantie d'être disponible dans le système d'exploitation. <br/>            La police réelle spécifiée par cette valeur dépend de l'implémentation |
| DEFAULT_PALETTE | La palette par défaut définie pour le dispositif de sortie actuel. <br/>            La palette réelle spécifiée par cette valeur dépend de l'implémentation |
| DEVICE_DEFAULT_FONT | La police par défaut fournie par le pilote du dispositif graphique pour le dispositif de sortie actuel. <br/>            La police réelle spécifiée par cette valeur dépend de l'implémentation |
| DKGRAY_BRUSH | Un pinceau gris foncé, à couleur unie, équivalent à un pinceau logique avec les propriétés suivantes :<br/>            BrushStyle: BS_SOLID<br/>            Color: 0x00404040 |
| GRAY_BRUSH | Un pinceau gris, à couleur unie, équivalent à un pinceau logique avec les propriétés suivantes :<br/>            BrushStyle: BS_SOLID<br/>            Color: 0x00808080 |
| LTGRAY_BRUSH | Un pinceau gris clair, à couleur unie, équivalent à un pinceau logique avec les propriétés suivantes :<br/>            BrushStyle: BS_SOLID<br/>            Color: 0x00C0C0C0 |
| NULL_BRUSH | Un pinceau nul équivalent à un pinceau logique avec les propriétés suivantes :<br/>            BrushStyle: BS_NULL |
| NULL_PEN | Un crayon nul équivalent à un crayon logique avec les propriétés suivantes :<br/>            PenStyle: PS_NULL |
| OEM_FIXED_FONT | Une police à chasse fixe, jeu de caractères OEM, équivalente à une police logique <br/>            (objet LogFont, section 2.2.13) avec les propriétés suivantes :<br/>            Charset: OEM_CHARSET (énumération WMF CharacterSet, [MS-WMF] section 2.1.1.5)<br/>            PitchAndFamily: FF_DONTCARE (énumération WMF FamilyFont, [MS-WMF] section 2.1.1.8) <br/>            + FIXED_PITCH (énumération WMF PitchFont, [MS-WMF] section 2.1.1.24) |
| SYSTEM_FIXED_FONT | Une police à largeur fixe garantie d'être disponible dans le système d'exploitation. <br/>            La police réelle spécifiée par cette valeur dépend de l'implémentation |
| SYSTEM_FONT | Une police garantie d'être disponible dans le système d'exploitation. <br/>            La police réelle spécifiée par cette valeur dépend de l'implémentation |
| WHITE_BRUSH | Un pinceau blanc, à couleur unie, équivalent à un pinceau logique <br/>            (objet LogBrushEx, section 2.2.12) avec les propriétés suivantes :<br/>            BrushStyle: BS_SOLID (énumération WMF BrushStyle, [MS-WMF] section 2.1.1.4)<br/>            Color: 0x00FFFFFF (objet WMF ColorRef, [MS-WMF] section 2.2.2.8) |
| WHITE_PEN | Un crayon blanc, à couleur unie, équivalent à un crayon logique (objet LogPen, section 2.2.19)<br/>            avec les propriétés suivantes :<br/>            PenStyle: PS_COSMETIC + PS_SOLID (énumération PenStyle, section 2.1.25)<br/>            ColorRef: 0x00FFFFFF (objet WMF ColorRef). |
