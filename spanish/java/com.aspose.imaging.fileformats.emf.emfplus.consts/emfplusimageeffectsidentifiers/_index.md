---
title: "EmfPlusImageEffectsIdentifiers"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Los identificadores ImageEffects definen GUID estándar para especificar efectos de imagen gráficos."
type: docs
weight: 28
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusimageeffectsidentifiers/
---
**Inheritance:**
java.lang.Object
```
public final class EmfPlusImageEffectsIdentifiers
```

Los identificadores ImageEffects definen GUID estándar para especificar efectos de imagen gráficos. Estos identificadores son utilizados por los controladores de dispositivo para publicar sus niveles de soporte para estos efectos. Las constantes de identificador se definen usando la representación de cadena con llaves GUID ([MS-DTYP] sección 2.3.4.3).

--------------------

Los identificadores de efectos de imagen y los bloques de parámetros de efectos de imagen se especifican mediante registros [EmfPlusSerializableObject](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject) para registros [EmfPlusDrawImagePoints](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints).
## Campos

| Campo | Descripción |
| --- | --- |
| [BLUR_EFFECT_GUID](#BLUR-EFFECT-GUID) | Especifica el efecto de desenfoque. |
| [BRIGHTNESS_CONTRAST_EFFECT_GUID](#BRIGHTNESS-CONTRAST-EFFECT-GUID) | Especifica el efecto de brillo y contraste. |
| [COLOR_BALANCE_EFFECT_GUID](#COLOR-BALANCE-EFFECT-GUID) | Especifica el efecto de balance de color. |
| [COLOR_CURVE_EFFECT_GUID](#COLOR-CURVE-EFFECT-GUID) | Especifica el efecto de curva de color. |
| [COLOR_LOOKUP_TABLE_EFFECT_GUID](#COLOR-LOOKUP-TABLE-EFFECT-GUID) | Especifica el efecto de tabla de búsqueda de colores. |
| [COLOR_MATRIX_EFFECT_GUID](#COLOR-MATRIX-EFFECT-GUID) | Especifica el efecto de matriz de colores. |
| [HUE_SATURATION_LIGHTNESS_EFFECT_GUID](#HUE-SATURATION-LIGHTNESS-EFFECT-GUID) | Especifica el efecto de tono, saturación y luminosidad. |
| [LEVELS_EFFECT_GUID](#LEVELS-EFFECT-GUID) | Especifica el efecto de niveles. |
| [RED_EYE_CORRECTION_EFFECT_GUID](#RED-EYE-CORRECTION-EFFECT-GUID) | Especifica el efecto de corrección de ojos rojos. |
| [SHARPEN_EFFECT_GUID](#SHARPEN-EFFECT-GUID) | Especifica el efecto de enfoque. |
| [TINT_EFFECT_GUID](#TINT-EFFECT-GUID) | Especifica el efecto de tono. |
## Métodos

| Método | Descripción |
| --- | --- |
| [contain(String objectGuid)](#contain-java.lang.String-) | Contiene el identificador único del objeto especificado. |
### BLUR_EFFECT_GUID {#BLUR-EFFECT-GUID}
```
public static final String BLUR_EFFECT_GUID
```


Especifica el efecto de desenfoque.

### BRIGHTNESS_CONTRAST_EFFECT_GUID {#BRIGHTNESS-CONTRAST-EFFECT-GUID}
```
public static final String BRIGHTNESS_CONTRAST_EFFECT_GUID
```


Especifica el efecto de brillo y contraste.

### COLOR_BALANCE_EFFECT_GUID {#COLOR-BALANCE-EFFECT-GUID}
```
public static final String COLOR_BALANCE_EFFECT_GUID
```


Especifica el efecto de balance de color.

### COLOR_CURVE_EFFECT_GUID {#COLOR-CURVE-EFFECT-GUID}
```
public static final String COLOR_CURVE_EFFECT_GUID
```


Especifica el efecto de curva de color.

### COLOR_LOOKUP_TABLE_EFFECT_GUID {#COLOR-LOOKUP-TABLE-EFFECT-GUID}
```
public static final String COLOR_LOOKUP_TABLE_EFFECT_GUID
```


Especifica el efecto de tabla de búsqueda de colores.

### COLOR_MATRIX_EFFECT_GUID {#COLOR-MATRIX-EFFECT-GUID}
```
public static final String COLOR_MATRIX_EFFECT_GUID
```


Especifica el efecto de matriz de colores.

### HUE_SATURATION_LIGHTNESS_EFFECT_GUID {#HUE-SATURATION-LIGHTNESS-EFFECT-GUID}
```
public static final String HUE_SATURATION_LIGHTNESS_EFFECT_GUID
```


Especifica el efecto de tono, saturación y luminosidad.

### LEVELS_EFFECT_GUID {#LEVELS-EFFECT-GUID}
```
public static final String LEVELS_EFFECT_GUID
```


Especifica el efecto de niveles.

### RED_EYE_CORRECTION_EFFECT_GUID {#RED-EYE-CORRECTION-EFFECT-GUID}
```
public static final String RED_EYE_CORRECTION_EFFECT_GUID
```


Especifica el efecto de corrección de ojos rojos.

### SHARPEN_EFFECT_GUID {#SHARPEN-EFFECT-GUID}
```
public static final String SHARPEN_EFFECT_GUID
```


Especifica el efecto de enfoque.

### TINT_EFFECT_GUID {#TINT-EFFECT-GUID}
```
public static final String TINT_EFFECT_GUID
```


Especifica el efecto de tono.

### contain(String objectGuid) {#contain-java.lang.String-}
```
public static boolean contain(String objectGuid)
```


Contiene el identificador único del objeto especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objectGuid | java.lang.String | El identificador único del objeto. |

**Returns:**
booleano - Verdadero si contiene.
