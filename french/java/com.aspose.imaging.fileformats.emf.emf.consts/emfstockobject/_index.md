---
title: "EmfStockObject"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération StockObject spécifie les index des objets graphiques logiques prédéfinis qui peuvent être utilisés dans les opérations graphiques.Les structures spécifiques des objets stock sont dépendantes de l'implémentation cependant les propriétés des objets stock DOIVENT être équivalentes aux propriétés des objets créés explicitement du même type."
type: docs
weight: 42
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfStockObject extends System.Enum
```

L'énumération StockObject spécifie les index des objets graphiques logiques prédéfinis qui peuvent être utilisés dans les opérations graphiques.Les structures spécifiques des objets stock sont dépendantes de l'implémentation ; cependant, les propriétés des objets stock DOIVENT être équivalentes aux propriétés des objets créés explicitement du même type. Ces propriétés sont spécifiées, lorsque cela est possible, pour les objets stock définis dans cette énumération.
## Champs

| Champ | Description |
| --- | --- |
| [WHITE_BRUSH](#WHITE-BRUSH) | Un pinceau blanc, de couleur unie, équivalent à un pinceau logique (objet LogBrushEx, section 2.2.12) avec les propriétés suivantes : BrushStyle : BS\\_SOLID (énumération WMF BrushStyle, [MS-WMF] section 2.1.1.4) Color : 0x00FFFFFF (objet WMF ColorRef, [MS-WMF] section 2.2.2.8) |
| [LTGRAY_BRUSH](#LTGRAY-BRUSH) | Un pinceau de couleur unie gris clair équivalent à un pinceau logique avec les propriétés suivantes : BrushStyle : BS\_SOLID Color : 0x00C0C0C0 |
| [GRAY_BRUSH](#GRAY-BRUSH) | Un pinceau de couleur unie gris équivalent à un pinceau logique avec les propriétés suivantes : BrushStyle : BS\_SOLID Color : 0x00808080 |
| [DKGRAY_BRUSH](#DKGRAY-BRUSH) | Un pinceau de couleur unie gris foncé équivalent à un pinceau logique avec les propriétés suivantes : BrushStyle : BS\_SOLID Color : 0x00404040 |
| [BLACK_BRUSH](#BLACK-BRUSH) | Un pinceau de couleur unie noir équivalent à un pinceau logique avec les propriétés suivantes : BrushStyle : BS\_SOLID Color : 0x00000000 |
| [NULL_BRUSH](#NULL-BRUSH) | Un pinceau nul équivalent à un pinceau logique avec les propriétés suivantes : BrushStyle : BS\_NULL |
| [WHITE_PEN](#WHITE-PEN) | Un stylo de couleur unie blanc équivalent à un stylo logique (objet LogPen, section 2.2.19) avec les propriétés suivantes : PenStyle : PS\_COSMETIC + PS\_SOLID (énumération PenStyle, section 2.1.25) ColorRef : 0x00FFFFFF (objet WMF ColorRef). |
| [BLACK_PEN](#BLACK-PEN) | Un stylo de couleur unie noir équivalent à un stylo logique avec les propriétés suivantes : PenStyle : PS\_COSMETIC + PS\_SOLID ColorRef : 0x00000000 |
| [NULL_PEN](#NULL-PEN) | Un stylo nul équivalent à un stylo logique avec les propriétés suivantes : PenStyle : PS\_NULL |
| [OEM_FIXED_FONT](#OEM-FIXED-FONT) | Une police à chasse fixe, jeu de caractères OEM, équivalente à une police logique (objet LogFont, section 2.2.13) avec les propriétés suivantes : Charset : OEM\_CHARSET (énumération WMF CharacterSet, [MS-WMF] section 2.1.1.5) PitchAndFamily : FF\_DONTCARE (énumération WMF FamilyFont, [MS-WMF] section 2.1.1.8) + FIXED\_PITCH (énumération WMF PitchFont, [MS-WMF] section 2.1.1.24) |
| [ANSI_FIXED_FONT](#ANSI-FIXED-FONT) | Une police à chasse fixe équivalente à une police logique avec les propriétés suivantes : Charset : ANSI\_CHARSET PitchAndFamily : FF\_DONTCARE + FIXED\_PITCH |
| [ANSI_VAR_FONT](#ANSI-VAR-FONT) | Une police à chasse variable équivalente à une police logique avec les propriétés suivantes : Charset : ANSI\_CHARSET PitchAndFamily : FF\_DONTCARE + VARIABLE\_PITCH |
| [SYSTEM_FONT](#SYSTEM-FONT) | Une police garantie disponible dans le système d’exploitation. |
| [DEVICE_DEFAULT_FONT](#DEVICE-DEFAULT-FONT) | La police par défaut fournie par le pilote du dispositif graphique pour le périphérique de sortie actuel. |
| [DEFAULT_PALETTE](#DEFAULT-PALETTE) | La palette par défaut définie pour le périphérique de sortie actuel. |
| [SYSTEM_FIXED_FONT](#SYSTEM-FIXED-FONT) | Une police à chasse fixe garantie disponible dans le système d’exploitation. |
| [DEFAULT_GUI_FONT](#DEFAULT-GUI-FONT) | Une police à chasse fixe garantie disponible dans le système d’exploitation. |
| [DC_BRUSH](#DC-BRUSH) | Le pinceau de couleur unie actuellement sélectionné dans le contexte de périphérique de lecture |
| [DC_PEN](#DC-PEN) | Le stylo de couleur unie actuellement sélectionné dans le contexte de périphérique de lecture |
### WHITE_BRUSH {#WHITE-BRUSH}
```
public static final int WHITE_BRUSH
```


Un pinceau blanc, de couleur unie, équivalent à un pinceau logique (objet LogBrushEx, section 2.2.12) avec les propriétés suivantes : BrushStyle : BS\\_SOLID (énumération WMF BrushStyle, [MS-WMF] section 2.1.1.4) Color : 0x00FFFFFF (objet WMF ColorRef, [MS-WMF] section 2.2.2.8)

### LTGRAY_BRUSH {#LTGRAY-BRUSH}
```
public static final int LTGRAY_BRUSH
```


Un pinceau de couleur unie gris clair équivalent à un pinceau logique avec les propriétés suivantes : BrushStyle : BS\_SOLID Color : 0x00C0C0C0

### GRAY_BRUSH {#GRAY-BRUSH}
```
public static final int GRAY_BRUSH
```


Un pinceau de couleur unie gris équivalent à un pinceau logique avec les propriétés suivantes : BrushStyle : BS\_SOLID Color : 0x00808080

### DKGRAY_BRUSH {#DKGRAY-BRUSH}
```
public static final int DKGRAY_BRUSH
```


Un pinceau de couleur unie gris foncé équivalent à un pinceau logique avec les propriétés suivantes : BrushStyle : BS\_SOLID Color : 0x00404040

### BLACK_BRUSH {#BLACK-BRUSH}
```
public static final int BLACK_BRUSH
```


Un pinceau de couleur unie noir équivalent à un pinceau logique avec les propriétés suivantes : BrushStyle : BS\_SOLID Color : 0x00000000

### NULL_BRUSH {#NULL-BRUSH}
```
public static final int NULL_BRUSH
```


Un pinceau nul équivalent à un pinceau logique avec les propriétés suivantes : BrushStyle : BS\_NULL

### WHITE_PEN {#WHITE-PEN}
```
public static final int WHITE_PEN
```


Un stylo de couleur unie blanc équivalent à un stylo logique (objet LogPen, section 2.2.19) avec les propriétés suivantes : PenStyle : PS\_COSMETIC + PS\_SOLID (énumération PenStyle, section 2.1.25) ColorRef : 0x00FFFFFF (objet WMF ColorRef).

### BLACK_PEN {#BLACK-PEN}
```
public static final int BLACK_PEN
```


Un stylo de couleur unie noir équivalent à un stylo logique avec les propriétés suivantes : PenStyle : PS\_COSMETIC + PS\_SOLID ColorRef : 0x00000000

### NULL_PEN {#NULL-PEN}
```
public static final int NULL_PEN
```


Un stylo nul équivalent à un stylo logique avec les propriétés suivantes : PenStyle : PS\_NULL

### OEM_FIXED_FONT {#OEM-FIXED-FONT}
```
public static final int OEM_FIXED_FONT
```


Une police à chasse fixe, jeu de caractères OEM, équivalente à une police logique (objet LogFont, section 2.2.13) avec les propriétés suivantes : Charset : OEM\_CHARSET (énumération WMF CharacterSet, [MS-WMF] section 2.1.1.5) PitchAndFamily : FF\_DONTCARE (énumération WMF FamilyFont, [MS-WMF] section 2.1.1.8) + FIXED\_PITCH (énumération WMF PitchFont, [MS-WMF] section 2.1.1.24)

### ANSI_FIXED_FONT {#ANSI-FIXED-FONT}
```
public static final int ANSI_FIXED_FONT
```


Une police à chasse fixe équivalente à une police logique avec les propriétés suivantes : Charset : ANSI\_CHARSET PitchAndFamily : FF\_DONTCARE + FIXED\_PITCH

### ANSI_VAR_FONT {#ANSI-VAR-FONT}
```
public static final int ANSI_VAR_FONT
```


Une police à chasse variable équivalente à une police logique avec les propriétés suivantes : Charset : ANSI\_CHARSET PitchAndFamily : FF\_DONTCARE + VARIABLE\_PITCH

### SYSTEM_FONT {#SYSTEM-FONT}
```
public static final int SYSTEM_FONT
```


Une police garantie disponible dans le système d’exploitation. La police réelle spécifiée par cette valeur dépend de l’implémentation

### DEVICE_DEFAULT_FONT {#DEVICE-DEFAULT-FONT}
```
public static final int DEVICE_DEFAULT_FONT
```


La police par défaut fournie par le pilote du dispositif graphique pour le périphérique de sortie actuel. La police réelle spécifiée par cette valeur dépend de l’implémentation

### DEFAULT_PALETTE {#DEFAULT-PALETTE}
```
public static final int DEFAULT_PALETTE
```


La palette par défaut définie pour le périphérique de sortie actuel. La palette réelle spécifiée par cette valeur dépend de l’implémentation

### SYSTEM_FIXED_FONT {#SYSTEM-FIXED-FONT}
```
public static final int SYSTEM_FIXED_FONT
```


Une police à chasse fixe garantie disponible dans le système d’exploitation. La police réelle spécifiée par cette valeur dépend de l’implémentation

### DEFAULT_GUI_FONT {#DEFAULT-GUI-FONT}
```
public static final int DEFAULT_GUI_FONT
```


Une police à chasse fixe garantie disponible dans le système d’exploitation. La police réelle spécifiée par cette valeur dépend de l’implémentation

### DC_BRUSH {#DC-BRUSH}
```
public static final int DC_BRUSH
```


Le pinceau de couleur unie actuellement sélectionné dans le contexte de périphérique de lecture

### DC_PEN {#DC-PEN}
```
public static final int DC_PEN
```


Le stylo de couleur unie actuellement sélectionné dans le contexte de périphérique de lecture

