---
title: "WmfColorUsageEnum"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération ColorUsage spécifie si une table de couleurs existe dans un bitmap indépendant du dispositif (DIB) et comment interpréter ses valeurs."
type: docs
weight: 15
url: /fr/java/com.aspose.imaging.fileformats.wmf.consts/wmfcolorusageenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfColorUsageEnum extends System.Enum
```

L'énumération ColorUsage spécifie si une table de couleurs existe dans un bitmap indépendant du dispositif (DIB) et comment interpréter ses valeurs.
## Champs

| Champ | Description |
| --- | --- |
| [DIB_RGB_COLORS](#DIB-RGB-COLORS) | La table de couleurs contient des valeurs RVB spécifiées par les objets RGBQuad (section 2.2.2.20). |
| [DIB_PAL_COLORS](#DIB-PAL-COLORS) | La table de couleurs contient des indices 16 bits dans la palette logique actuelle du contexte de périphérique de lecture. |
| [DIB_PAL_INDICES](#DIB-PAL-INDICES) | Aucune table de couleurs n'existe. |
### DIB_RGB_COLORS {#DIB-RGB-COLORS}
```
public static final int DIB_RGB_COLORS
```


La table de couleurs contient des valeurs RVB spécifiées par les objets RGBQuad (section 2.2.2.20).

### DIB_PAL_COLORS {#DIB-PAL-COLORS}
```
public static final int DIB_PAL_COLORS
```


La table de couleurs contient des indices 16 bits dans la palette logique actuelle du contexte de périphérique de lecture.

### DIB_PAL_INDICES {#DIB-PAL-INDICES}
```
public static final int DIB_PAL_INDICES
```


Aucune table de couleurs n'existe. Les pixels du DIB sont des indices dans la palette logique actuelle du contexte du dispositif de lecture.

