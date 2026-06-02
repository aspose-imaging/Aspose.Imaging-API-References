---
title: "EmfPlusImageEffectsIdentifiers"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les identifiants ImageEffects définissent des GUID standard pour spécifier les effets d'image graphiques."
type: docs
weight: 28
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusimageeffectsidentifiers/
---
**Inheritance:**
java.lang.Object
```
public final class EmfPlusImageEffectsIdentifiers
```

Les identifiants ImageEffects définissent des GUID standard pour spécifier les effets d'image graphiques. Ces identifiants sont utilisés par les pilotes de périphérique pour publier leurs niveaux de prise en charge de ces effets. Les constantes d'identifiant sont définies en utilisant la représentation de chaîne GUID entre accolades ([MS-DTYP] section 2.3.4.3).

--------------------

Les identifiants d'effets d'image et les blocs de paramètres d'effets d'image sont spécifiés par les enregistrements [EmfPlusSerializableObject](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject) pour les enregistrements [EmfPlusDrawImagePoints](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints).
## Champs

| Champ | Description |
| --- | --- |
| [BLUR_EFFECT_GUID](#BLUR-EFFECT-GUID) | Spécifie l'effet de flou. |
| [BRIGHTNESS_CONTRAST_EFFECT_GUID](#BRIGHTNESS-CONTRAST-EFFECT-GUID) | Spécifie l'effet de contraste de luminosité. |
| [COLOR_BALANCE_EFFECT_GUID](#COLOR-BALANCE-EFFECT-GUID) | Spécifie l'effet de balance des couleurs. |
| [COLOR_CURVE_EFFECT_GUID](#COLOR-CURVE-EFFECT-GUID) | Spécifie l'effet de courbe de couleur. |
| [COLOR_LOOKUP_TABLE_EFFECT_GUID](#COLOR-LOOKUP-TABLE-EFFECT-GUID) | Spécifie l'effet de table de recherche de couleur. |
| [COLOR_MATRIX_EFFECT_GUID](#COLOR-MATRIX-EFFECT-GUID) | Spécifie l'effet de matrice de couleur. |
| [HUE_SATURATION_LIGHTNESS_EFFECT_GUID](#HUE-SATURATION-LIGHTNESS-EFFECT-GUID) | Spécifie l'effet de teinte, saturation et luminosité. |
| [LEVELS_EFFECT_GUID](#LEVELS-EFFECT-GUID) | Spécifie l'effet de niveaux. |
| [RED_EYE_CORRECTION_EFFECT_GUID](#RED-EYE-CORRECTION-EFFECT-GUID) | Spécifie l'effet de correction des yeux rouges. |
| [SHARPEN_EFFECT_GUID](#SHARPEN-EFFECT-GUID) | Spécifie l'effet d'accentuation. |
| [TINT_EFFECT_GUID](#TINT-EFFECT-GUID) | Spécifie l'effet de teinte. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [contain(String objectGuid)](#contain-java.lang.String-) | Contient l'identifiant unique de l'objet spécifié. |
### BLUR_EFFECT_GUID {#BLUR-EFFECT-GUID}
```
public static final String BLUR_EFFECT_GUID
```


Spécifie l'effet de flou.

### BRIGHTNESS_CONTRAST_EFFECT_GUID {#BRIGHTNESS-CONTRAST-EFFECT-GUID}
```
public static final String BRIGHTNESS_CONTRAST_EFFECT_GUID
```


Spécifie l'effet de contraste de luminosité.

### COLOR_BALANCE_EFFECT_GUID {#COLOR-BALANCE-EFFECT-GUID}
```
public static final String COLOR_BALANCE_EFFECT_GUID
```


Spécifie l'effet de balance des couleurs.

### COLOR_CURVE_EFFECT_GUID {#COLOR-CURVE-EFFECT-GUID}
```
public static final String COLOR_CURVE_EFFECT_GUID
```


Spécifie l'effet de courbe de couleur.

### COLOR_LOOKUP_TABLE_EFFECT_GUID {#COLOR-LOOKUP-TABLE-EFFECT-GUID}
```
public static final String COLOR_LOOKUP_TABLE_EFFECT_GUID
```


Spécifie l'effet de table de recherche de couleur.

### COLOR_MATRIX_EFFECT_GUID {#COLOR-MATRIX-EFFECT-GUID}
```
public static final String COLOR_MATRIX_EFFECT_GUID
```


Spécifie l'effet de matrice de couleur.

### HUE_SATURATION_LIGHTNESS_EFFECT_GUID {#HUE-SATURATION-LIGHTNESS-EFFECT-GUID}
```
public static final String HUE_SATURATION_LIGHTNESS_EFFECT_GUID
```


Spécifie l'effet de teinte, saturation et luminosité.

### LEVELS_EFFECT_GUID {#LEVELS-EFFECT-GUID}
```
public static final String LEVELS_EFFECT_GUID
```


Spécifie l'effet de niveaux.

### RED_EYE_CORRECTION_EFFECT_GUID {#RED-EYE-CORRECTION-EFFECT-GUID}
```
public static final String RED_EYE_CORRECTION_EFFECT_GUID
```


Spécifie l'effet de correction des yeux rouges.

### SHARPEN_EFFECT_GUID {#SHARPEN-EFFECT-GUID}
```
public static final String SHARPEN_EFFECT_GUID
```


Spécifie l'effet d'accentuation.

### TINT_EFFECT_GUID {#TINT-EFFECT-GUID}
```
public static final String TINT_EFFECT_GUID
```


Spécifie l'effet de teinte.

### contain(String objectGuid) {#contain-java.lang.String-}
```
public static boolean contain(String objectGuid)
```


Contient l'identifiant unique de l'objet spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| objectGuid | java.lang.String | L'identifiant unique de l'objet. |

**Returns:**
booléen - Vrai si contient.
