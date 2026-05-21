---
title: "EmfPlusImageEffectsIdentifiers"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Идентификаторы ImageEffects определяют стандартные GUID для указания графических эффектов изображения."
type: docs
weight: 28
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusimageeffectsidentifiers/
---
**Inheritance:**
java.lang.Object
```
public final class EmfPlusImageEffectsIdentifiers
```

Идентификаторы ImageEffects определяют стандартные GUID для указания графических эффектов изображения. Эти идентификаторы используются драйверами устройств для публикации их уровней поддержки этих эффектов. Константы идентификаторов определяются с использованием строкового представления GUID в фигурных скобках ([MS-DTYP] раздел 2.3.4.3).

--------------------

Идентификаторы эффектов изображения и блоки параметров Image Effects задаются записями [EmfPlusSerializableObject](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject) для записей [EmfPlusDrawImagePoints](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints).
## Поля

| Поле | Описание |
| --- | --- |
| [BLUR_EFFECT_GUID](#BLUR-EFFECT-GUID) | Указывает эффект размытия. |
| [BRIGHTNESS_CONTRAST_EFFECT_GUID](#BRIGHTNESS-CONTRAST-EFFECT-GUID) | Указывает эффект яркости и контрастности. |
| [COLOR_BALANCE_EFFECT_GUID](#COLOR-BALANCE-EFFECT-GUID) | Указывает эффект цветового баланса. |
| [COLOR_CURVE_EFFECT_GUID](#COLOR-CURVE-EFFECT-GUID) | Указывает эффект цветовой кривой. |
| [COLOR_LOOKUP_TABLE_EFFECT_GUID](#COLOR-LOOKUP-TABLE-EFFECT-GUID) | Указывает эффект таблицы поиска цветов. |
| [COLOR_MATRIX_EFFECT_GUID](#COLOR-MATRIX-EFFECT-GUID) | Указывает эффект цветовой матрицы. |
| [HUE_SATURATION_LIGHTNESS_EFFECT_GUID](#HUE-SATURATION-LIGHTNESS-EFFECT-GUID) | Указывает эффект оттенка, насыщенности и яркости. |
| [LEVELS_EFFECT_GUID](#LEVELS-EFFECT-GUID) | Указывает эффект уровней. |
| [RED_EYE_CORRECTION_EFFECT_GUID](#RED-EYE-CORRECTION-EFFECT-GUID) | Указывает эффект коррекции «красных глаз». |
| [SHARPEN_EFFECT_GUID](#SHARPEN-EFFECT-GUID) | Указывает эффект резкости. |
| [TINT_EFFECT_GUID](#TINT-EFFECT-GUID) | Указывает эффект тонирования. |
## Методы

| Метод | Описание |
| --- | --- |
| [contain(String objectGuid)](#contain-java.lang.String-) | Содержит указанный уникальный идентификатор объекта. |
### BLUR_EFFECT_GUID {#BLUR-EFFECT-GUID}
```
public static final String BLUR_EFFECT_GUID
```


Указывает эффект размытия.

### BRIGHTNESS_CONTRAST_EFFECT_GUID {#BRIGHTNESS-CONTRAST-EFFECT-GUID}
```
public static final String BRIGHTNESS_CONTRAST_EFFECT_GUID
```


Указывает эффект яркости и контрастности.

### COLOR_BALANCE_EFFECT_GUID {#COLOR-BALANCE-EFFECT-GUID}
```
public static final String COLOR_BALANCE_EFFECT_GUID
```


Указывает эффект цветового баланса.

### COLOR_CURVE_EFFECT_GUID {#COLOR-CURVE-EFFECT-GUID}
```
public static final String COLOR_CURVE_EFFECT_GUID
```


Указывает эффект цветовой кривой.

### COLOR_LOOKUP_TABLE_EFFECT_GUID {#COLOR-LOOKUP-TABLE-EFFECT-GUID}
```
public static final String COLOR_LOOKUP_TABLE_EFFECT_GUID
```


Указывает эффект таблицы поиска цветов.

### COLOR_MATRIX_EFFECT_GUID {#COLOR-MATRIX-EFFECT-GUID}
```
public static final String COLOR_MATRIX_EFFECT_GUID
```


Указывает эффект цветовой матрицы.

### HUE_SATURATION_LIGHTNESS_EFFECT_GUID {#HUE-SATURATION-LIGHTNESS-EFFECT-GUID}
```
public static final String HUE_SATURATION_LIGHTNESS_EFFECT_GUID
```


Указывает эффект оттенка, насыщенности и яркости.

### LEVELS_EFFECT_GUID {#LEVELS-EFFECT-GUID}
```
public static final String LEVELS_EFFECT_GUID
```


Указывает эффект уровней.

### RED_EYE_CORRECTION_EFFECT_GUID {#RED-EYE-CORRECTION-EFFECT-GUID}
```
public static final String RED_EYE_CORRECTION_EFFECT_GUID
```


Указывает эффект коррекции «красных глаз».

### SHARPEN_EFFECT_GUID {#SHARPEN-EFFECT-GUID}
```
public static final String SHARPEN_EFFECT_GUID
```


Указывает эффект резкости.

### TINT_EFFECT_GUID {#TINT-EFFECT-GUID}
```
public static final String TINT_EFFECT_GUID
```


Указывает эффект тонирования.

### contain(String objectGuid) {#contain-java.lang.String-}
```
public static boolean contain(String objectGuid)
```


Содержит указанный уникальный идентификатор объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| objectGuid | java.lang.String | Уникальный идентификатор объекта. |

**Returns:**
логический — True, если содержит.
