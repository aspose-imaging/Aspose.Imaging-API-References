---
title: "EmfColorSpace"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération ColorSpace est utilisée pour spécifier quand activer ou désactiver la preuve des couleurs et quand supprimer les transformations."
type: docs
weight: 15
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.consts/emfcolorspace/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfColorSpace extends System.Enum
```

L'énumération ColorSpace est utilisée pour spécifier quand activer ou désactiver la preuve couleur, et quand supprimer les transformations.
## Champs

| Champ | Description |
| --- | --- |
| [CS_ENABLE](#CS-ENABLE) | Mappe les couleurs à la gamme de couleurs de l'appareil cible. |
| [CS_DISABLE](#CS-DISABLE) | Désactive la preuve des couleurs. |
| [CS_DELETE_TRANSFORM](#CS-DELETE-TRANSFORM) | Si la gestion des couleurs est activée pour le profil cible, la désactive et supprime la transformation concaténée. |
### CS_ENABLE {#CS-ENABLE}
```
public static final int CS_ENABLE
```


Mappe les couleurs à la gamme de couleurs de l'appareil cible. Cela active la preuve des couleurs. Toutes les commandes de dessin suivantes vers le contexte de l'appareil de lecture rendront les couleurs comme elles apparaîtraient sur l'appareil cible.

### CS_DISABLE {#CS-DISABLE}
```
public static final int CS_DISABLE
```


Désactive la preuve des couleurs.

### CS_DELETE_TRANSFORM {#CS-DELETE-TRANSFORM}
```
public static final int CS_DELETE_TRANSFORM
```


Si la gestion des couleurs est activée pour le profil cible, la désactive et supprime la transformation concaténée.

