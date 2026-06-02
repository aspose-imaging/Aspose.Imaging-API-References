---
title: "EmfPlusLineCapType"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération LineCapType définit les types de caps de ligne à utiliser aux extrémités des lignes dessinées avec des stylos graphiques."
type: docs
weight: 31
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusLineCapType extends System.Enum
```

L'énumération LineCapType définit les types de caps de ligne à utiliser aux extrémités des lignes dessinées avec des stylos graphiques.

--------------------

Les caps de ligne graphiques sont spécifiés par les objets [EmfPlusPen](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspen) (section 2.2.1.7).
## Champs

| Champ | Description |
| --- | --- |
| [LineCapTypeFlat](#LineCapTypeFlat) | Spécifie un cap de ligne à bout carré. |
| [LineCapTypeSquare](#LineCapTypeSquare) | Spécifie un capuchon de ligne carré. |
| [LineCapTypeRound](#LineCapTypeRound) | Spécifie un cap de ligne circulaire. |
| [LineCapTypeTriangle](#LineCapTypeTriangle) | Spécifie un capuchon de ligne triangulaire. |
| [LineCapTypeNoAnchor](#LineCapTypeNoAnchor) | Spécifie que l'extrémité de la ligne n'est pas ancrée. |
| [LineCapTypeSquareAnchor](#LineCapTypeSquareAnchor) | Spécifie que l'extrémité de la ligne est ancrée avec un cap de ligne carré. |
| [LineCapTypeRoundAnchor](#LineCapTypeRoundAnchor) | Spécifie que l'extrémité de la ligne est ancrée avec un cap de ligne circulaire. |
| [LineCapTypeDiamondAnchor](#LineCapTypeDiamondAnchor) | Spécifie que l'extrémité de la ligne est ancrée avec un cap de ligne en forme de losange, qui est un carré tourné de 45 degrés. |
| [LineCapTypeArrowAnchor](#LineCapTypeArrowAnchor) | Spécifie que l'extrémité de la ligne est ancrée avec une forme de pointe de flèche. |
| [LineCapTypeAnchorMask](#LineCapTypeAnchorMask) | Masque utilisé pour vérifier si un cap de ligne est un cap d'ancrage. |
| [LineCapTypeCustom](#LineCapTypeCustom) | Spécifie un capuchon de ligne personnalisé. |
### LineCapTypeFlat {#LineCapTypeFlat}
```
public static final int LineCapTypeFlat
```


Spécifie un cap de ligne à bout carré. L'extrémité de la ligne DOIT être le dernier point de la ligne.

### LineCapTypeSquare {#LineCapTypeSquare}
```
public static final int LineCapTypeSquare
```


Spécifie un cap de ligne carré. Le centre du carré DOIT être situé au dernier point de la ligne. La largeur du carré est la largeur de la ligne.

### LineCapTypeRound {#LineCapTypeRound}
```
public static final int LineCapTypeRound
```


Spécifie un cap de ligne circulaire. Le centre du cercle DOIT être situé au dernier point de la ligne. Le diamètre du cercle est la largeur de la ligne.

### LineCapTypeTriangle {#LineCapTypeTriangle}
```
public static final int LineCapTypeTriangle
```


Spécifie un cap de ligne triangulaire. La base du triangle DOIT être située au dernier point de la ligne. La base du triangle est la largeur de la ligne.

### LineCapTypeNoAnchor {#LineCapTypeNoAnchor}
```
public static final int LineCapTypeNoAnchor
```


Spécifie que l'extrémité de la ligne n'est pas ancrée.

### LineCapTypeSquareAnchor {#LineCapTypeSquareAnchor}
```
public static final int LineCapTypeSquareAnchor
```


Spécifie que l'extrémité de la ligne est ancrée avec un cap de ligne carré. Le centre du carré DOIT être situé au dernier point de la ligne. La hauteur et la largeur du carré sont la largeur de la ligne.

### LineCapTypeRoundAnchor {#LineCapTypeRoundAnchor}
```
public static final int LineCapTypeRoundAnchor
```


Spécifie que l'extrémité de la ligne est ancrée avec un cap de ligne circulaire. Le centre du cercle DOIT être situé au dernier point de la ligne. Le cercle DEVRAIT être plus large que la ligne.

### LineCapTypeDiamondAnchor {#LineCapTypeDiamondAnchor}
```
public static final int LineCapTypeDiamondAnchor
```


Spécifie que l'extrémité de la ligne est ancrée avec un cap de ligne en forme de losange, qui est un carré tourné de 45 degrés. Le centre du losange DOIT être situé au dernier point de la ligne. Le losange DEVRAIT être plus large que la ligne.

### LineCapTypeArrowAnchor {#LineCapTypeArrowAnchor}
```
public static final int LineCapTypeArrowAnchor
```


Spécifie que l'extrémité de la ligne est ancrée avec une forme de pointe de flèche. Le point de la pointe de flèche DOIT être situé au dernier point de la ligne. La pointe de flèche DEVRAIT être plus large que la ligne.

### LineCapTypeAnchorMask {#LineCapTypeAnchorMask}
```
public static final int LineCapTypeAnchorMask
```


Masque utilisé pour vérifier si un cap de ligne est un cap d'ancrage.

### LineCapTypeCustom {#LineCapTypeCustom}
```
public static final int LineCapTypeCustom
```


Spécifie un capuchon de ligne personnalisé.

