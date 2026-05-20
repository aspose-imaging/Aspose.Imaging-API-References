---
title: "EmfPlusImageEffectsIdentifiers"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Gli identificatori ImageEffects definiscono GUID standard per specificare gli effetti immagine grafici."
type: docs
weight: 28
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusimageeffectsidentifiers/
---
**Inheritance:**
java.lang.Object
```
public final class EmfPlusImageEffectsIdentifiers
```

Gli identificatori ImageEffects definiscono GUID standard per specificare gli effetti grafici delle immagini. Questi identificatori sono usati dai driver di dispositivo per pubblicare i loro livelli di supporto per questi effetti. Le costanti degli identificatori sono definite usando la rappresentazione della stringa GUID con parentesi graffe ([MS-DTYP] sezione 2.3.4.3).

--------------------

Gli identificatori degli effetti immagine e i blocchi dei parametri degli effetti immagine sono specificati dai record [EmfPlusSerializableObject](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject) per i record [EmfPlusDrawImagePoints](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints).
## Campi

| Campo | Descrizione |
| --- | --- |
| [BLUR_EFFECT_GUID](#BLUR-EFFECT-GUID) | Specifica l'effetto di sfocatura. |
| [BRIGHTNESS_CONTRAST_EFFECT_GUID](#BRIGHTNESS-CONTRAST-EFFECT-GUID) | Specifica l'effetto di luminosità e contrasto. |
| [COLOR_BALANCE_EFFECT_GUID](#COLOR-BALANCE-EFFECT-GUID) | Specifica l'effetto di bilanciamento del colore. |
| [COLOR_CURVE_EFFECT_GUID](#COLOR-CURVE-EFFECT-GUID) | Specifica l'effetto di curva colore. |
| [COLOR_LOOKUP_TABLE_EFFECT_GUID](#COLOR-LOOKUP-TABLE-EFFECT-GUID) | Specifica l'effetto della tabella di ricerca dei colori. |
| [COLOR_MATRIX_EFFECT_GUID](#COLOR-MATRIX-EFFECT-GUID) | Specifica l'effetto della matrice dei colori. |
| [HUE_SATURATION_LIGHTNESS_EFFECT_GUID](#HUE-SATURATION-LIGHTNESS-EFFECT-GUID) | Specifica l'effetto tonalità, saturazione e luminosità. |
| [LEVELS_EFFECT_GUID](#LEVELS-EFFECT-GUID) | Specifica l'effetto dei livelli. |
| [RED_EYE_CORRECTION_EFFECT_GUID](#RED-EYE-CORRECTION-EFFECT-GUID) | Specifica l'effetto di correzione dell'occhio rosso. |
| [SHARPEN_EFFECT_GUID](#SHARPEN-EFFECT-GUID) | Specifica l'effetto di nitidezza. |
| [TINT_EFFECT_GUID](#TINT-EFFECT-GUID) | Specifica l'effetto di tinta. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [contain(String objectGuid)](#contain-java.lang.String-) | Contiene l'identificatore univoco dell'oggetto specificato. |
### BLUR_EFFECT_GUID {#BLUR-EFFECT-GUID}
```
public static final String BLUR_EFFECT_GUID
```


Specifica l'effetto di sfocatura.

### BRIGHTNESS_CONTRAST_EFFECT_GUID {#BRIGHTNESS-CONTRAST-EFFECT-GUID}
```
public static final String BRIGHTNESS_CONTRAST_EFFECT_GUID
```


Specifica l'effetto di luminosità e contrasto.

### COLOR_BALANCE_EFFECT_GUID {#COLOR-BALANCE-EFFECT-GUID}
```
public static final String COLOR_BALANCE_EFFECT_GUID
```


Specifica l'effetto di bilanciamento del colore.

### COLOR_CURVE_EFFECT_GUID {#COLOR-CURVE-EFFECT-GUID}
```
public static final String COLOR_CURVE_EFFECT_GUID
```


Specifica l'effetto di curva colore.

### COLOR_LOOKUP_TABLE_EFFECT_GUID {#COLOR-LOOKUP-TABLE-EFFECT-GUID}
```
public static final String COLOR_LOOKUP_TABLE_EFFECT_GUID
```


Specifica l'effetto della tabella di ricerca dei colori.

### COLOR_MATRIX_EFFECT_GUID {#COLOR-MATRIX-EFFECT-GUID}
```
public static final String COLOR_MATRIX_EFFECT_GUID
```


Specifica l'effetto della matrice dei colori.

### HUE_SATURATION_LIGHTNESS_EFFECT_GUID {#HUE-SATURATION-LIGHTNESS-EFFECT-GUID}
```
public static final String HUE_SATURATION_LIGHTNESS_EFFECT_GUID
```


Specifica l'effetto tonalità, saturazione e luminosità.

### LEVELS_EFFECT_GUID {#LEVELS-EFFECT-GUID}
```
public static final String LEVELS_EFFECT_GUID
```


Specifica l'effetto dei livelli.

### RED_EYE_CORRECTION_EFFECT_GUID {#RED-EYE-CORRECTION-EFFECT-GUID}
```
public static final String RED_EYE_CORRECTION_EFFECT_GUID
```


Specifica l'effetto di correzione dell'occhio rosso.

### SHARPEN_EFFECT_GUID {#SHARPEN-EFFECT-GUID}
```
public static final String SHARPEN_EFFECT_GUID
```


Specifica l'effetto di nitidezza.

### TINT_EFFECT_GUID {#TINT-EFFECT-GUID}
```
public static final String TINT_EFFECT_GUID
```


Specifica l'effetto di tinta.

### contain(String objectGuid) {#contain-java.lang.String-}
```
public static boolean contain(String objectGuid)
```


Contiene l'identificatore univoco dell'oggetto specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| objectGuid | java.lang.String | L'identificatore univoco dell'oggetto. |

**Returns:**
boolean - True se contiene.
