---
title: "StretchMode"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L' Énumération spécifie le mode d'étirement bitma qui définit comment le système combine les lignes ou les colonnes d'un bitmap avec les pixels existants."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.wmf.consts/stretchmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StretchMode extends System.Enum
```

L'[StretchMode](../../com.aspose.imaging.fileformats.wmf.consts/stretchmode) Énumération spécifie le mode d'étirement du bitmap, qui définit comment le système combine les lignes ou les colonnes d'un bitmap avec les pixels existants.
## Champs

| Champ | Description |
| --- | --- |
| [BlackOnWhite](#BlackOnWhite) | Effectue une opération booléenne AND en utilisant les valeurs de couleur des pixels éliminés et existants. |
| [WhiteOnBlack](#WhiteOnBlack) | Effectue une opération booléenne OR en utilisant les valeurs de couleur des pixels éliminés et existants. |
| [ColorOnColor](#ColorOnColor) | Supprime les pixels. |
| [HalfTone](#HalfTone) | Mappe les pixels du rectangle source en blocs de pixels dans le rectangle de destination. |
### BlackOnWhite {#BlackOnWhite}
```
public static final int BlackOnWhite
```


Effectue une opération booléenne AND en utilisant les valeurs de couleur des pixels éliminés et existants. Si le bitmap est un bitmap monochrome, ce mode préserve les pixels noirs au détriment des pixels blancs.

### WhiteOnBlack {#WhiteOnBlack}
```
public static final int WhiteOnBlack
```


Effectue une opération booléenne OR en utilisant les valeurs de couleur des pixels éliminés et existants. Si le bitmap est un bitmap monochrome, ce mode préserve les pixels blancs au détriment des pixels noirs.

### ColorOnColor {#ColorOnColor}
```
public static final int ColorOnColor
```


Supprime les pixels. Ce mode supprime toutes les lignes de pixels éliminées sans essayer de préserver leurs informations.

### HalfTone {#HalfTone}
```
public static final int HalfTone
```


Mappe les pixels du rectangle source en blocs de pixels dans le rectangle de destination. La couleur moyenne du bloc de pixels de destination approxime la couleur des pixels source.

