---
title: "TextRenderingHint"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Spécifie la qualité du rendu du texte."
type: docs
weight: 115
url: /fr/java/com.aspose.imaging/textrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextRenderingHint extends System.Enum
```

Spécifie la qualité du rendu du texte.
## Champs

| Champ | Description |
| --- | --- |
| [SystemDefault](#SystemDefault) | Chaque caractère est dessiné en utilisant son bitmap de glyphe, avec l'indice de rendu par défaut du système. |
| [SingleBitPerPixelGridFit](#SingleBitPerPixelGridFit) | Chaque caractère est dessiné en utilisant son bitmap de glyphe. |
| [SingleBitPerPixel](#SingleBitPerPixel) | Chaque caractère est dessiné en utilisant son bitmap de glyphe. |
| [AntiAliasGridFit](#AntiAliasGridFit) | Chaque caractère est dessiné en utilisant son bitmap de glyphe antialiasé avec hinting. |
| [AntiAlias](#AntiAlias) | Chaque caractère est dessiné en utilisant son bitmap de glyphe antialiasé sans hinting. |
| [ClearTypeGridFit](#ClearTypeGridFit) | Chaque caractère est dessiné en utilisant son bitmap de glyphe ClearType avec hinting. |
### SystemDefault {#SystemDefault}
```
public static final int SystemDefault
```


Chaque caractère est dessiné en utilisant son bitmap de glyphe, avec l'indice de rendu par défaut du système. Le texte sera dessiné en utilisant les paramètres de lissage des polices que l'utilisateur a sélectionnés pour le système.

### SingleBitPerPixelGridFit {#SingleBitPerPixelGridFit}
```
public static final int SingleBitPerPixelGridFit
```


Chaque caractère est dessiné en utilisant son bitmap de glyphe. Le hinting est utilisé pour améliorer l'apparence des caractères sur les tiges et les courbes.

### SingleBitPerPixel {#SingleBitPerPixel}
```
public static final int SingleBitPerPixel
```


Chaque caractère est dessiné en utilisant son bitmap de glyphe. Le hinting n'est pas utilisé.

### AntiAliasGridFit {#AntiAliasGridFit}
```
public static final int AntiAliasGridFit
```


Chaque caractère est dessiné en utilisant son bitmap de glyphe antialiasé avec hinting. Qualité bien meilleure grâce à l'antialiasing, mais à un coût de performance plus élevé.

### AntiAlias {#AntiAlias}
```
public static final int AntiAlias
```


Chaque caractère est dessiné en utilisant son bitmap de glyphe antialiasé sans hinting. Qualité supérieure grâce à l'antialiasing. Les différences de largeur des tiges peuvent être perceptibles car le hinting est désactivé.

### ClearTypeGridFit {#ClearTypeGridFit}
```
public static final int ClearTypeGridFit
```


Chaque caractère est dessiné en utilisant son bitmap de glyphe ClearType avec hinting. Le réglage de la plus haute qualité. Utilisé pour tirer parti des fonctionnalités de police ClearType.

