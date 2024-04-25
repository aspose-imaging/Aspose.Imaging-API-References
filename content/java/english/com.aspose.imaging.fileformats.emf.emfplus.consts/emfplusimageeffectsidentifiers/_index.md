---
title: EmfPlusImageEffectsIdentifiers
second_title: Aspose.Imaging for Java API Reference
description: The ImageEffects identifiers define standard GUIDs for specifying graphics image effects.
type: docs
weight: 28
url: /com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusimageeffectsidentifiers/
---
**Inheritance:**
java.lang.Object
```
public final class EmfPlusImageEffectsIdentifiers
```

The ImageEffects identifiers define standard GUIDs for specifying graphics image effects. These identifiers are used by device drivers to publish their levels of support for these effects. The identifier constants are defined using the GUID curly-braced string representation ([MS-DTYP] section 2.3.4.3).

--------------------

Image effects identifiers and Image Effects Parameter Blocks are specified by [EmfPlusSerializableObject](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject) records for [EmfPlusDrawImagePoints](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints) records.
## Fields

| Field | Description |
| --- | --- |
| [BLUR_EFFECT_GUID](#BLUR-EFFECT-GUID) | Specifies the blur effect. |
| [BRIGHTNESS_CONTRAST_EFFECT_GUID](#BRIGHTNESS-CONTRAST-EFFECT-GUID) | Specifies the brightness contrast effect. |
| [COLOR_BALANCE_EFFECT_GUID](#COLOR-BALANCE-EFFECT-GUID) | Specifies the color balance effect. |
| [COLOR_CURVE_EFFECT_GUID](#COLOR-CURVE-EFFECT-GUID) | Specifies the color curve effect. |
| [COLOR_LOOKUP_TABLE_EFFECT_GUID](#COLOR-LOOKUP-TABLE-EFFECT-GUID) | Specifies the color lookup table effect. |
| [COLOR_MATRIX_EFFECT_GUID](#COLOR-MATRIX-EFFECT-GUID) | Specifies the color matrix effect. |
| [HUE_SATURATION_LIGHTNESS_EFFECT_GUID](#HUE-SATURATION-LIGHTNESS-EFFECT-GUID) | Specifies the hue saturation lightness effect. |
| [LEVELS_EFFECT_GUID](#LEVELS-EFFECT-GUID) | Specifies the levels effect. |
| [RED_EYE_CORRECTION_EFFECT_GUID](#RED-EYE-CORRECTION-EFFECT-GUID) | Specifies the red-eye correction effect. |
| [SHARPEN_EFFECT_GUID](#SHARPEN-EFFECT-GUID) | Specifies the sharpen effect. |
| [TINT_EFFECT_GUID](#TINT-EFFECT-GUID) | Specifies the tint effect. |
## Methods

| Method | Description |
| --- | --- |
| [contain(String objectGuid)](#contain-java.lang.String-) | Contains the specified object unique identifier. |
### BLUR_EFFECT_GUID {#BLUR-EFFECT-GUID}
```
public static final String BLUR_EFFECT_GUID
```


Specifies the blur effect.

### BRIGHTNESS_CONTRAST_EFFECT_GUID {#BRIGHTNESS-CONTRAST-EFFECT-GUID}
```
public static final String BRIGHTNESS_CONTRAST_EFFECT_GUID
```


Specifies the brightness contrast effect.

### COLOR_BALANCE_EFFECT_GUID {#COLOR-BALANCE-EFFECT-GUID}
```
public static final String COLOR_BALANCE_EFFECT_GUID
```


Specifies the color balance effect.

### COLOR_CURVE_EFFECT_GUID {#COLOR-CURVE-EFFECT-GUID}
```
public static final String COLOR_CURVE_EFFECT_GUID
```


Specifies the color curve effect.

### COLOR_LOOKUP_TABLE_EFFECT_GUID {#COLOR-LOOKUP-TABLE-EFFECT-GUID}
```
public static final String COLOR_LOOKUP_TABLE_EFFECT_GUID
```


Specifies the color lookup table effect.

### COLOR_MATRIX_EFFECT_GUID {#COLOR-MATRIX-EFFECT-GUID}
```
public static final String COLOR_MATRIX_EFFECT_GUID
```


Specifies the color matrix effect.

### HUE_SATURATION_LIGHTNESS_EFFECT_GUID {#HUE-SATURATION-LIGHTNESS-EFFECT-GUID}
```
public static final String HUE_SATURATION_LIGHTNESS_EFFECT_GUID
```


Specifies the hue saturation lightness effect.

### LEVELS_EFFECT_GUID {#LEVELS-EFFECT-GUID}
```
public static final String LEVELS_EFFECT_GUID
```


Specifies the levels effect.

### RED_EYE_CORRECTION_EFFECT_GUID {#RED-EYE-CORRECTION-EFFECT-GUID}
```
public static final String RED_EYE_CORRECTION_EFFECT_GUID
```


Specifies the red-eye correction effect.

### SHARPEN_EFFECT_GUID {#SHARPEN-EFFECT-GUID}
```
public static final String SHARPEN_EFFECT_GUID
```


Specifies the sharpen effect.

### TINT_EFFECT_GUID {#TINT-EFFECT-GUID}
```
public static final String TINT_EFFECT_GUID
```


Specifies the tint effect.

### contain(String objectGuid) {#contain-java.lang.String-}
```
public static boolean contain(String objectGuid)
```


Contains the specified object unique identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| objectGuid | java.lang.String | The object unique identifier. |

**Returns:**
boolean - True if contains.
