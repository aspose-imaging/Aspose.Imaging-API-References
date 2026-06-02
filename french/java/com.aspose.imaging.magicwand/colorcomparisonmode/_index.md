---
title: "ColorComparisonMode"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Spécifie comment les couleurs sont comparées pendant l'algorithme Magic Wand."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.magicwand/colorcomparisonmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorComparisonMode extends System.Enum
```

Spécifie comment les couleurs sont comparées pendant l'algorithme Magic Wand.
## Champs

| Champ | Description |
| --- | --- |
| [RgbDefault](#RgbDefault) | Les couleurs sont comparées dans l'espace couleur RGB. |
| [YuvDefault](#YuvDefault) | Les couleurs sont comparées dans l'espace couleur YUV. |
| [YuvLessLumaSensitive](#YuvLessLumaSensitive) | Les couleurs sont comparées dans l'espace couleur YUV. |
| [Custom](#Custom) | L'algorithme de comparaison de couleur est défini par l'utilisateur. |
### RgbDefault {#RgbDefault}
```
public static final int RgbDefault
```


Les couleurs sont comparées dans l'espace couleur RGB. Chaque différence de couleur doit satisfaire le seuil.

### YuvDefault {#YuvDefault}
```
public static final int YuvDefault
```


Les couleurs sont comparées dans l'espace couleur YUV. Chaque différence de couleur doit satisfaire le seuil.

### YuvLessLumaSensitive {#YuvLessLumaSensitive}
```
public static final int YuvLessLumaSensitive
```


Les couleurs sont comparées dans l'espace couleur YUV. Les différences d'information couleur doivent satisfaire le seuil, le seuil pour le composant de luminance est doublé.

### Custom {#Custom}
```
public static final int Custom
```


L'algorithme de comparaison de couleur est défini par l'utilisateur.

