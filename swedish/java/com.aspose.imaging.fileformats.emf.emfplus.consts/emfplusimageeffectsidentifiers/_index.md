---
title: "EmfPlusImageEffectsIdentifiers"
second_title: "Aspose.Imaging för Java API-referens"
description: "ImageEffects‑identifierarna definierar standard‑GUID:er för att specificera grafikbild‑effekter."
type: docs
weight: 28
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusimageeffectsidentifiers/
---
**Inheritance:**
java.lang.Object
```
public final class EmfPlusImageEffectsIdentifiers
```

ImageEffects‑identifierarna definierar standard‑GUID:er för att specificera grafik‑bild‑effekter. Dessa identifierare används av drivrutiner för att publicera deras stödnivåer för dessa effekter. Identifierarkonstanterna definieras med GUID‑strängrepresentationen med klammerparenteser ([MS-DTYP] avsnitt 2.3.4.3).

--------------------

Bild‑effekt‑identifierare och Image Effects‑parameterblock specificeras av [EmfPlusSerializableObject](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject)-poster för [EmfPlusDrawImagePoints](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints)-poster.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [BLUR_EFFECT_GUID](#BLUR-EFFECT-GUID) | Anger suddeffekten. |
| [BRIGHTNESS_CONTRAST_EFFECT_GUID](#BRIGHTNESS-CONTRAST-EFFECT-GUID) | Anger ljusstyrke‑kontrast‑effekten. |
| [COLOR_BALANCE_EFFECT_GUID](#COLOR-BALANCE-EFFECT-GUID) | Anger färgbalans‑effekten. |
| [COLOR_CURVE_EFFECT_GUID](#COLOR-CURVE-EFFECT-GUID) | Anger färgkurveffekten. |
| [COLOR_LOOKUP_TABLE_EFFECT_GUID](#COLOR-LOOKUP-TABLE-EFFECT-GUID) | Anger färguppslagstabellseffekten. |
| [COLOR_MATRIX_EFFECT_GUID](#COLOR-MATRIX-EFFECT-GUID) | Anger färgmatriseffekten. |
| [HUE_SATURATION_LIGHTNESS_EFFECT_GUID](#HUE-SATURATION-LIGHTNESS-EFFECT-GUID) | Anger nyans-mättnad-ljusstyrkeffekten. |
| [LEVELS_EFFECT_GUID](#LEVELS-EFFECT-GUID) | Anger nivåeffekten. |
| [RED_EYE_CORRECTION_EFFECT_GUID](#RED-EYE-CORRECTION-EFFECT-GUID) | Anger röda-ögonkorrigeringseffekten. |
| [SHARPEN_EFFECT_GUID](#SHARPEN-EFFECT-GUID) | Anger skärpeffekten. |
| [TINT_EFFECT_GUID](#TINT-EFFECT-GUID) | Anger toningseffekten. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [contain(String objectGuid)](#contain-java.lang.String-) | Innehåller det angivna objektets unika identifierare. |
### BLUR_EFFECT_GUID {#BLUR-EFFECT-GUID}
```
public static final String BLUR_EFFECT_GUID
```


Anger suddeffekten.

### BRIGHTNESS_CONTRAST_EFFECT_GUID {#BRIGHTNESS-CONTRAST-EFFECT-GUID}
```
public static final String BRIGHTNESS_CONTRAST_EFFECT_GUID
```


Anger ljusstyrke‑kontrast‑effekten.

### COLOR_BALANCE_EFFECT_GUID {#COLOR-BALANCE-EFFECT-GUID}
```
public static final String COLOR_BALANCE_EFFECT_GUID
```


Anger färgbalans‑effekten.

### COLOR_CURVE_EFFECT_GUID {#COLOR-CURVE-EFFECT-GUID}
```
public static final String COLOR_CURVE_EFFECT_GUID
```


Anger färgkurveffekten.

### COLOR_LOOKUP_TABLE_EFFECT_GUID {#COLOR-LOOKUP-TABLE-EFFECT-GUID}
```
public static final String COLOR_LOOKUP_TABLE_EFFECT_GUID
```


Anger färguppslagstabellseffekten.

### COLOR_MATRIX_EFFECT_GUID {#COLOR-MATRIX-EFFECT-GUID}
```
public static final String COLOR_MATRIX_EFFECT_GUID
```


Anger färgmatriseffekten.

### HUE_SATURATION_LIGHTNESS_EFFECT_GUID {#HUE-SATURATION-LIGHTNESS-EFFECT-GUID}
```
public static final String HUE_SATURATION_LIGHTNESS_EFFECT_GUID
```


Anger nyans-mättnad-ljusstyrkeffekten.

### LEVELS_EFFECT_GUID {#LEVELS-EFFECT-GUID}
```
public static final String LEVELS_EFFECT_GUID
```


Anger nivåeffekten.

### RED_EYE_CORRECTION_EFFECT_GUID {#RED-EYE-CORRECTION-EFFECT-GUID}
```
public static final String RED_EYE_CORRECTION_EFFECT_GUID
```


Anger röda-ögonkorrigeringseffekten.

### SHARPEN_EFFECT_GUID {#SHARPEN-EFFECT-GUID}
```
public static final String SHARPEN_EFFECT_GUID
```


Anger skärpeffekten.

### TINT_EFFECT_GUID {#TINT-EFFECT-GUID}
```
public static final String TINT_EFFECT_GUID
```


Anger toningseffekten.

### contain(String objectGuid) {#contain-java.lang.String-}
```
public static boolean contain(String objectGuid)
```


Innehåller det angivna objektets unika identifierare.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objectGuid | java.lang.String | Objektets unika identifierare. |

**Returns:**
boolesk - True om den innehåller.
