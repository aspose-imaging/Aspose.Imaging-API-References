---
title: "AnimationDisposalMethods"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Indique la manière dont le graphique doit être traité après affichage."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging/animationdisposalmethods/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class AnimationDisposalMethods extends System.Enum
```

Indique la manière dont le graphique doit être traité après affichage.
## Champs

| Champ | Description |
| --- | --- |
| [PRESERVE](#PRESERVE) | Ne pas disposer. |
| [BACKGROUND](#BACKGROUND) | Restaurer à la couleur d'arrière-plan. |
| [PREVIOUS](#PREVIOUS) | Restaurer à la précédente. |
### PRESERVE {#PRESERVE}
```
public static final int PRESERVE
```


Ne pas disposer. Le graphique doit rester en place.

### BACKGROUND {#BACKGROUND}
```
public static final int BACKGROUND
```


Restaurer à la couleur d'arrière-plan. La zone utilisée par le graphique doit être restaurée à la couleur d'arrière-plan.

### PREVIOUS {#PREVIOUS}
```
public static final int PREVIOUS
```


Restaurer à la précédente. Le décodeur doit restaurer la zone écrasée par le graphique avec ce qui était présent avant le rendu du graphique.

