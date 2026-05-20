---
title: "EmfDibColors"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération DIBColors définit comment interpréter les valeurs dans la table de couleurs d'un DIB."
type: docs
weight: 17
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfDibColors extends System.Enum
```

L'énumération DIBColors définit comment interpréter les valeurs dans la table de couleurs d'un DIB.
## Champs

| Champ | Description |
| --- | --- |
| [DIB_RGB_COLORS](#DIB-RGB-COLORS) | La table de couleurs contient des valeurs RVB littérales |
| [DIB_PAL_COLORS](#DIB-PAL-COLORS) | La table de couleurs se compose d'un tableau d'index de 16 bits vers l'objet LogPalette (section 2.2.17) qui est actuellement défini dans le contexte du dispositif de lecture. |
| [DIB_PAL_INDICES](#DIB-PAL-INDICES) | Aucune table de couleurs n'existe. |
### DIB_RGB_COLORS {#DIB-RGB-COLORS}
```
public static final int DIB_RGB_COLORS
```


La table de couleurs contient des valeurs RVB littérales

### DIB_PAL_COLORS {#DIB-PAL-COLORS}
```
public static final int DIB_PAL_COLORS
```


La table de couleurs se compose d'un tableau d'index de 16 bits vers l'objet LogPalette (section 2.2.17) qui est actuellement défini dans le contexte du dispositif de lecture.

### DIB_PAL_INDICES {#DIB-PAL-INDICES}
```
public static final int DIB_PAL_INDICES
```


Aucune table de couleurs n'existe. Les pixels du DIB sont des indices dans la palette logique actuelle du contexte du dispositif de lecture.

