---
title: "EmfExtTextOutOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération ExtTextOutOptions spécifie les paramètres qui contrôlent divers aspects de la sortie de texte par les enregistrements EMR_SMALLTEXTOUTsection 2.3.5.37 et dans les objets EmrText."
type: docs
weight: 19
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfExtTextOutOptions extends System.Enum
```

L'énumération ExtTextOutOptions spécifie les paramètres qui contrôlent divers aspects de la sortie de texte par les enregistrements EMR\_SMALLTEXTOUT (section 2.3.5.37) et dans les objets EmrText.
## Champs

| Champ | Description |
| --- | --- |
| [ETO_OPAQUE](#ETO-OPAQUE) | Ce bit indique que la couleur d'arrière-plan actuelle DOIT être utilisée pour remplir le rectangle |
| [ETO_CLIPPED](#ETO-CLIPPED) | Ce bit indique que le texte DOIT être découpé au rectangle. |
| [ETO_GLYPH_INDEX](#ETO-GLYPH-INDEX) | Ce bit indique que les codes des caractères dans une chaîne de texte en sortie sont en réalité des index des glyphes de caractères dans une police TrueType. |
| [ETO_RTLREADING](#ETO-RTLREADING) | Ce bit indique que le texte DOIT être disposé dans un ordre de lecture de droite à gauche, au lieu de l'ordre par défaut de gauche à droite. |
| [ETO_NO_RECT](#ETO-NO-RECT) | Ce bit indique que l'enregistrement ne spécifie pas de rectangle englobant pour la sortie de texte. |
| [ETO_SMALL_CHARS](#ETO-SMALL-CHARS) | Ce bit indique que les codes des caractères dans une chaîne de texte en sortie sont sur 8 bits, dérivés des octets de poids faible des codes de caractères Unicode UTF16-LE de 16 bits, où l'octet de poids fort est supposé être 0. |
| [ETO_NUMERICSLOCAL](#ETO-NUMERICSLOCAL) | Ce bit indique que, pour afficher les nombres, les chiffres appropriés aux paramètres régionaux DOIVENT être utilisés |
| [ETO_NUMERICSLATIN](#ETO-NUMERICSLATIN) | Ce bit indique que, pour afficher les nombres, les chiffres européens DOIVENT être utilisés |
| [ETO_IGNORELANGUAGE](#ETO-IGNORELANGUAGE) | Ce bit indique qu'aucun traitement spécial du système d'exploitation pour le placement des glyphes ne doit être effectué sur les chaînes de droite à gauche ; c'est‑à‑dire que tout positionnement des glyphes DOIT être pris en charge par les enregistrements de dessin et d'état dans le métafichier. |
| [ETO_PDY](#ETO-PDY) | Ce bit indique que les valeurs de déplacement horizontal et vertical des caractères DOIVENT être fournies. |
| [ETO_REVERSE_INDEX_MAP](#ETO-REVERSE-INDEX-MAP) | Ce bit est réservé et NE DOIT PAS être utilisé |
### ETO_OPAQUE {#ETO-OPAQUE}
```
public static final int ETO_OPAQUE
```


Ce bit indique que la couleur d'arrière-plan actuelle DOIT être utilisée pour remplir le rectangle

### ETO_CLIPPED {#ETO-CLIPPED}
```
public static final int ETO_CLIPPED
```


Ce bit indique que le texte DOIT être découpé au rectangle.

### ETO_GLYPH_INDEX {#ETO-GLYPH-INDEX}
```
public static final int ETO_GLYPH_INDEX
```


Ce bit indique que les codes des caractères dans une chaîne de texte en sortie sont en réalité des index des glyphes de caractères dans une police TrueType. Les index de glyphes sont spécifiques à la police, de sorte que, pour afficher correctement les caractères lors de la lecture, la police utilisée DOIT être identique à celle utilisée pour générer les index.

### ETO_RTLREADING {#ETO-RTLREADING}
```
public static final int ETO_RTLREADING
```


Ce bit indique que le texte DOIT être disposé dans un ordre de lecture de droite à gauche, au lieu de l'ordre par défaut de gauche à droite. Cela DOIT être appliqué uniquement lorsque la police sélectionnée dans le contexte du dispositif de lecture est soit hébreu, soit arabe

### ETO_NO_RECT {#ETO-NO-RECT}
```
public static final int ETO_NO_RECT
```


Ce bit indique que l'enregistrement ne spécifie pas de rectangle englobant pour la sortie de texte.

### ETO_SMALL_CHARS {#ETO-SMALL-CHARS}
```
public static final int ETO_SMALL_CHARS
```


Ce bit indique que les codes des caractères dans une chaîne de texte en sortie sont sur 8 bits, dérivés des octets de poids faible des codes de caractères Unicode UTF16-LE de 16 bits, où l'octet de poids fort est supposé être 0.

### ETO_NUMERICSLOCAL {#ETO-NUMERICSLOCAL}
```
public static final int ETO_NUMERICSLOCAL
```


Ce bit indique que, pour afficher les nombres, les chiffres appropriés aux paramètres régionaux DOIVENT être utilisés

### ETO_NUMERICSLATIN {#ETO-NUMERICSLATIN}
```
public static final int ETO_NUMERICSLATIN
```


Ce bit indique que, pour afficher les nombres, les chiffres européens DOIVENT être utilisés

### ETO_IGNORELANGUAGE {#ETO-IGNORELANGUAGE}
```
public static final int ETO_IGNORELANGUAGE
```


Ce bit indique qu'aucun traitement spécial du système d'exploitation pour le placement des glyphes ne doit être effectué sur les chaînes de droite à gauche ; c'est‑à‑dire que tout positionnement des glyphes DOIT être pris en charge par les enregistrements de dessin et d'état dans le métafichier.

### ETO_PDY {#ETO-PDY}
```
public static final int ETO_PDY
```


Ce bit indique que les valeurs de déplacement horizontal et vertical des caractères DOIVENT être fournies.

### ETO_REVERSE_INDEX_MAP {#ETO-REVERSE-INDEX-MAP}
```
public static final int ETO_REVERSE_INDEX_MAP
```


Ce bit est réservé et NE DOIT PAS être utilisé

