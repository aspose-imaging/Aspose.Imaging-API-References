---
title: "OdTextAlignModeFlags"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les indicateurs de mode d'alignement du texte du document ouvert"
type: docs
weight: 14
url: /fr/java/com.aspose.imaging.fileformats.opendocument.enums/odtextalignmodeflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class OdTextAlignModeFlags extends System.Enum
```

Les indicateurs de mode d'alignement du texte du document ouvert
## Champs

| Champ | Description |
| --- | --- |
| [Noupdatecp](#Noupdatecp) | La position de dessin dans le contexte de périphérique de lecture NE DOIT PAS être mise à jour après chaque appel de sortie de texte. |
| [Left](#Left) | Le point de référence DOIT être sur le bord gauche du rectangle englobant. |
| [Top](#Top) | Le point de référence DOIT être sur le bord supérieur du rectangle englobant. |
| [Updatecp](#Updatecp) | La position de dessin dans le contexte de périphérique de lecture DOIT être mise à jour après chaque appel de sortie de texte. |
| [Right](#Right) | Le point de référence DOIT être sur le bord droit du rectangle englobant. |
| [Center](#Center) | Le point de référence DOIT être aligné horizontalement avec le centre du rectangle englobant. |
| [Justify](#Justify) | Le texte doit être aligné de manière à ce que chaque ligne de texte d'un paragraphe ait la même longueur. |
| [Bottom](#Bottom) | Le point de référence DOIT être sur le bord inférieur du rectangle englobant. |
| [Baseline](#Baseline) | Le point de référence DOIT être sur la ligne de base du texte. |
| [Rtlreading](#Rtlreading) | Le texte DOIT être disposé dans l'ordre de lecture de droite à gauche, au lieu de l'ordre par défaut de gauche à droite. |
| [Horizontal](#Horizontal) | Represents Horizontal text align sets (Left | Right | Centre) |
| [Vertical](#Vertical) | Represents Vertical text align sets (Top | Bottom | Ligne de base) |
### Noupdatecp {#Noupdatecp}
```
public static final int Noupdatecp
```


La position de dessin dans le contexte de périphérique de lecture NE DOIT PAS être mise à jour après chaque appel de sortie de texte. Le point de référence DOIT être transmis à la fonction de sortie de texte.

### Left {#Left}
```
public static final int Left
```


Le point de référence DOIT être sur le bord gauche du rectangle englobant.

### Top {#Top}
```
public static final int Top
```


Le point de référence DOIT être sur le bord supérieur du rectangle englobant.

### Updatecp {#Updatecp}
```
public static final int Updatecp
```


La position de dessin dans le contexte de périphérique de lecture DOIT être mise à jour après chaque appel de sortie de texte. Elle DOIT être utilisée comme point de référence.

### Right {#Right}
```
public static final int Right
```


Le point de référence DOIT être sur le bord droit du rectangle englobant.

### Center {#Center}
```
public static final int Center
```


Le point de référence DOIT être aligné horizontalement avec le centre du rectangle englobant.

### Justify {#Justify}
```
public static final int Justify
```


Le texte doit être aligné de manière à ce que chaque ligne de texte d'un paragraphe ait la même longueur.

### Bottom {#Bottom}
```
public static final int Bottom
```


Le point de référence DOIT être sur le bord inférieur du rectangle englobant.

### Baseline {#Baseline}
```
public static final int Baseline
```


Le point de référence DOIT être sur la ligne de base du texte.

### Rtlreading {#Rtlreading}
```
public static final int Rtlreading
```


Le texte DOIT être disposé dans l'ordre de lecture de droite à gauche, au lieu de l'ordre par défaut de gauche à droite. Cela DOIT être appliqué uniquement lorsque la police définie dans le contexte de périphérique de lecture est soit hébreu soit arabe.

### Horizontal {#Horizontal}
```
public static final int Horizontal
```


Représente les ensembles d'alignement horizontal du texte (Left | Right | Center)

### Vertical {#Vertical}
```
public static final int Vertical
```


Représente les ensembles d'alignement vertical du texte (Top | Bottom | Baseline)

