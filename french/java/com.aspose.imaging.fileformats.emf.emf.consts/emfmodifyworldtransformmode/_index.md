---
title: "EmfModifyWorldTransformMode"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération ModifyWorldTransformMode définit des modes d'utilisation des données de transformation spécifiées pour modifier la transformation de l'espace mondial vers l'espace page qui est actuellement définie dans le contexte du dispositif de lecture."
type: docs
weight: 33
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfModifyWorldTransformMode extends System.Enum
```

L'énumération ModifyWorldTransformMode définit des modes d'utilisation des données de transformation spécifiées pour modifier la transformation de l'espace mondial vers l'espace page qui est actuellement définie dans le contexte du dispositif de lecture.
## Champs

| Champ | Description |
| --- | --- |
| [MWT_IDENTITY](#MWT-IDENTITY) | Réinitialiser la transformation actuelle en utilisant la matrice identité. |
| [MWT_LEFTMULTIPLY](#MWT-LEFTMULTIPLY) | Multiplier la transformation actuelle. |
| [MWT_RIGHTMULTIPLY](#MWT-RIGHTMULTIPLY) | Multiplier la transformation actuelle. |
| [MWT_SET](#MWT-SET) | Exécuter la fonction d’un enregistrement EMR\_SETWORLDTRANSFORM (section 2.3.12.2). |
### MWT_IDENTITY {#MWT-IDENTITY}
```
public static final int MWT_IDENTITY
```


Réinitialisez la transformation actuelle en utilisant la matrice identité. Dans ce mode, les données de transformation spécifiées sont ignorées.

### MWT_LEFTMULTIPLY {#MWT-LEFTMULTIPLY}
```
public static final int MWT_LEFTMULTIPLY
```


Multipliez la transformation actuelle. Dans ce mode, les données de transformation spécifiées sont le multiplicande gauche, et la transformation actuellement définie dans le contexte du dispositif de lecture est le multiplicande droit.

### MWT_RIGHTMULTIPLY {#MWT-RIGHTMULTIPLY}
```
public static final int MWT_RIGHTMULTIPLY
```


Multipliez la transformation actuelle. Dans ce mode, les données de transformation spécifiées sont le multiplicande droit, et la transformation actuellement définie dans le contexte du dispositif de lecture est le multiplicande gauche.

### MWT_SET {#MWT-SET}
```
public static final int MWT_SET
```


Exécuter la fonction d’un enregistrement EMR\_SETWORLDTRANSFORM (section 2.3.12.2).

