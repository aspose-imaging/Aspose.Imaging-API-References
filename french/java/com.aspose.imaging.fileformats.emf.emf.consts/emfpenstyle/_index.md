---
title: "EmfPenStyle"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération PenStyle définit les attributs des stylos qui peuvent être utilisés dans les opérations graphiques."
type: docs
weight: 34
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.consts/emfpenstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPenStyle extends System.Enum
```

L'énumération PenStyle définit les attributs des stylos qui peuvent être utilisés dans les opérations graphiques. Un style de stylo est une combinaison du type de stylo, du style de ligne, du bout de ligne et de la jointure de ligne.
## Champs

| Champ | Description |
| --- | --- |
| [PS_COSMETIC](#PS-COSMETIC) | Un type de stylo qui spécifie une ligne d'une largeur d'une unité logique et un style de couleur unie |
| [PS_ENDCAP_ROUND](#PS-ENDCAP-ROUND) | Un bout de ligne qui spécifie des extrémités rondes. |
| [PS_JOIN_ROUND](#PS-JOIN-ROUND) | Une jointure de ligne qui spécifie des jointures rondes |
| [PS_SOLID](#PS-SOLID) | Un style de ligne de couleur unie |
| [PS_DASH](#PS-DASH) | Un style de ligne en tirets |
| [PS_DOT](#PS-DOT) | Un style de ligne en points. |
| [PS_DASHDOT](#PS-DASHDOT) | Un style de ligne composé d'alternance de tirets et de points |
| [PS_DASHDOTDOT](#PS-DASHDOTDOT) | Un style de ligne qui consiste en tirets et points doubles. |
| [PS_NULL](#PS-NULL) | Un style de ligne qui est invisible. |
| [PS_INSIDEFRAME](#PS-INSIDEFRAME) | Un style de ligne qui est d'une couleur unie. |
| [PS_USERSTYLE](#PS-USERSTYLE) | Un style de ligne défini par un tableau de style, qui spécifie les longueurs des tirets et des espaces dans la ligne |
| [PS_ALTERNATE](#PS-ALTERNATE) | Un style de ligne dans lequel chaque deuxième pixel est défini. |
| [PS_ENDCAP_SQUARE](#PS-ENDCAP-SQUARE) | Une extrémité de ligne qui spécifie des terminaisons carrées. |
| [PS_ENDCAP_FLAT](#PS-ENDCAP-FLAT) | Une extrémité de ligne qui spécifie des terminaisons plates. |
| [PS_JOIN_BEVEL](#PS-JOIN-BEVEL) | Une jointure de ligne qui spécifie des jointures biseautées. |
| [PS_JOIN_MITER](#PS-JOIN-MITER) | Une jointure de ligne qui spécifie des jointures en onglet lorsque les longueurs des jointures sont dans la limite de longueur d'onglet actuelle définie dans le contexte du dispositif de lecture. |
| [PS_GEOMETRIC](#PS-GEOMETRIC) | Un type de stylo qui spécifie une ligne d'une largeur mesurée en unités logiques et un style pouvant contenir n'importe lequel des attributs d'un pinceau. |
| [StyleMask](#StyleMask) | Le masque de style |
| [EndCapMask](#EndCapMask) | Le masque d'extrémité |
| [JoinMask](#JoinMask) | Le masque de jointure |
| [TypeMask](#TypeMask) | Le masque de type |
### PS_COSMETIC {#PS-COSMETIC}
```
public static final int PS_COSMETIC
```


Un type de stylo qui spécifie une ligne d'une largeur d'une unité logique et un style de couleur unie

### PS_ENDCAP_ROUND {#PS-ENDCAP-ROUND}
```
public static final int PS_ENDCAP_ROUND
```


Un bout de ligne qui spécifie des extrémités rondes.

### PS_JOIN_ROUND {#PS-JOIN-ROUND}
```
public static final int PS_JOIN_ROUND
```


Une jointure de ligne qui spécifie des jointures rondes

### PS_SOLID {#PS-SOLID}
```
public static final int PS_SOLID
```


Un style de ligne de couleur unie

### PS_DASH {#PS-DASH}
```
public static final int PS_DASH
```


Un style de ligne en tirets

### PS_DOT {#PS-DOT}
```
public static final int PS_DOT
```


Un style de ligne en points.

### PS_DASHDOT {#PS-DASHDOT}
```
public static final int PS_DASHDOT
```


Un style de ligne composé d'alternance de tirets et de points

### PS_DASHDOTDOT {#PS-DASHDOTDOT}
```
public static final int PS_DASHDOTDOT
```


Un style de ligne qui consiste en tirets et points doubles.

### PS_NULL {#PS-NULL}
```
public static final int PS_NULL
```


Un style de ligne qui est invisible.

### PS_INSIDEFRAME {#PS-INSIDEFRAME}
```
public static final int PS_INSIDEFRAME
```


Un style de ligne qui est d'une couleur unie. Lorsque ce style est spécifié dans un enregistrement de dessin qui prend un rectangle englobant, les dimensions de la figure sont réduites afin qu'elle tienne entièrement dans le rectangle englobant, en tenant compte de la largeur du stylo.

### PS_USERSTYLE {#PS-USERSTYLE}
```
public static final int PS_USERSTYLE
```


Un style de ligne défini par un tableau de style, qui spécifie les longueurs des tirets et des espaces dans la ligne

### PS_ALTERNATE {#PS-ALTERNATE}
```
public static final int PS_ALTERNATE
```


Un style de ligne dans lequel chaque deuxième pixel est défini. Ce style n'est applicable qu'à un type de stylo PS\_COSMETIC

### PS_ENDCAP_SQUARE {#PS-ENDCAP-SQUARE}
```
public static final int PS_ENDCAP_SQUARE
```


Une extrémité de ligne qui spécifie des terminaisons carrées.

### PS_ENDCAP_FLAT {#PS-ENDCAP-FLAT}
```
public static final int PS_ENDCAP_FLAT
```


Une extrémité de ligne qui spécifie des terminaisons plates.

### PS_JOIN_BEVEL {#PS-JOIN-BEVEL}
```
public static final int PS_JOIN_BEVEL
```


Une jointure de ligne qui spécifie des jointures biseautées.

### PS_JOIN_MITER {#PS-JOIN-MITER}
```
public static final int PS_JOIN_MITER
```


Une jointure de ligne qui spécifie des jointures en onglet lorsque les longueurs des jointures sont dans la limite de longueur d'onglet actuelle définie dans le contexte du dispositif de lecture. Si les longueurs des jointures dépassent la limite d'onglet, des jointures biseautées sont spécifiées

### PS_GEOMETRIC {#PS-GEOMETRIC}
```
public static final int PS_GEOMETRIC
```


Un type de stylo qui spécifie une ligne d'une largeur mesurée en unités logiques et un style pouvant contenir n'importe lequel des attributs d'un pinceau.

### StyleMask {#StyleMask}
```
public static final int StyleMask
```


Le masque de style

### EndCapMask {#EndCapMask}
```
public static final int EndCapMask
```


Le masque d'extrémité

### JoinMask {#JoinMask}
```
public static final int JoinMask
```


Le masque de jointure

### TypeMask {#TypeMask}
```
public static final int TypeMask
```


Le masque de type

