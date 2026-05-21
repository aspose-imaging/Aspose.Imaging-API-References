---
title: "ColorMatrixFlag"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Spécifie les types d'images et de couleurs qui seront affectés par les paramètres d'ajustement des couleurs et du niveau de gris d'un."
type: docs
weight: 27
url: /fr/java/com.aspose.imaging/colormatrixflag/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorMatrixFlag extends System.Enum
```

Spécifie les types d'images et de couleurs qui seront affectés par les paramètres d'ajustement des couleurs et du niveau de gris d'un [ImageAttributes](../../com.aspose.imaging/imageattributes).
## Champs

| Champ | Description |
| --- | --- |
| [Default](#Default) | Toutes les valeurs de couleur, y compris les nuances de gris, sont ajustées par la même matrice d'ajustement des couleurs. |
| [SkipGrays](#SkipGrays) | Toutes les couleurs sont ajustées, mais les nuances de gris ne le sont pas. |
| [AltGrays](#AltGrays) | Seules les nuances de gris sont ajustées. |
### Default {#Default}
```
public static final int Default
```


Toutes les valeurs de couleur, y compris les nuances de gris, sont ajustées par la même matrice d'ajustement des couleurs.

### SkipGrays {#SkipGrays}
```
public static final int SkipGrays
```


Toutes les couleurs sont ajustées, mais les nuances de gris ne le sont pas. Une nuance de gris est toute couleur dont les composantes rouge, verte et bleue ont la même valeur.

### AltGrays {#AltGrays}
```
public static final int AltGrays
```


Seules les nuances de gris sont ajustées.

