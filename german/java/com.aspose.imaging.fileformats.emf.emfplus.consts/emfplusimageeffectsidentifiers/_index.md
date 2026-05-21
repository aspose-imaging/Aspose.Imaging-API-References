---
title: "EmfPlusImageEffectsIdentifiers"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die ImageEffects-Bezeichner definieren standardmäßige GUIDs zur Angabe von Grafik‑Bildeffekten."
type: docs
weight: 28
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusimageeffectsidentifiers/
---
**Inheritance:**
java.lang.Object
```
public final class EmfPlusImageEffectsIdentifiers
```

Die ImageEffects‑Bezeichner definieren Standard‑GUIDs zur Angabe von Grafikeffekten. Diese Bezeichner werden von Gerätetreibern verwendet, um ihre Unterstützungsstufen für diese Effekte zu veröffentlichen. Die Bezeichnerkonstanten werden mit der GUID‑Darstellung in geschweiften Klammern definiert ([MS‑DTYP] Abschnitt 2.3.4.3).

--------------------

Bild‑Effekt‑Bezeichner und Bild‑Effekt‑Parameterblöcke werden durch [EmfPlusSerializableObject](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject)-Datensätze für [EmfPlusDrawImagePoints](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints)-Datensätze spezifiziert.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [BLUR_EFFECT_GUID](#BLUR-EFFECT-GUID) | Gibt den Unschärfe‑Effekt an. |
| [BRIGHTNESS_CONTRAST_EFFECT_GUID](#BRIGHTNESS-CONTRAST-EFFECT-GUID) | Gibt den Helligkeits‑Kontrast‑Effekt an. |
| [COLOR_BALANCE_EFFECT_GUID](#COLOR-BALANCE-EFFECT-GUID) | Gibt den Farb‑Balance‑Effekt an. |
| [COLOR_CURVE_EFFECT_GUID](#COLOR-CURVE-EFFECT-GUID) | Gibt den Farbkurven‑Effekt an. |
| [COLOR_LOOKUP_TABLE_EFFECT_GUID](#COLOR-LOOKUP-TABLE-EFFECT-GUID) | Gibt den Effekt der Farb-Lookup-Tabelle an. |
| [COLOR_MATRIX_EFFECT_GUID](#COLOR-MATRIX-EFFECT-GUID) | Gibt den Effekt der Farbmatrix an. |
| [HUE_SATURATION_LIGHTNESS_EFFECT_GUID](#HUE-SATURATION-LIGHTNESS-EFFECT-GUID) | Gibt den Effekt von Farbton, Sättigung und Helligkeit an. |
| [LEVELS_EFFECT_GUID](#LEVELS-EFFECT-GUID) | Gibt den Ebenen-Effekt an. |
| [RED_EYE_CORRECTION_EFFECT_GUID](#RED-EYE-CORRECTION-EFFECT-GUID) | Gibt den Rote-Augen-Korrektureffekt an. |
| [SHARPEN_EFFECT_GUID](#SHARPEN-EFFECT-GUID) | Gibt den Schärfe-Effekt an. |
| [TINT_EFFECT_GUID](#TINT-EFFECT-GUID) | Gibt den Tönungs-Effekt an. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [contain(String objectGuid)](#contain-java.lang.String-) | Enthält die angegebene eindeutige Objektkennung. |
### BLUR_EFFECT_GUID {#BLUR-EFFECT-GUID}
```
public static final String BLUR_EFFECT_GUID
```


Gibt den Unschärfe‑Effekt an.

### BRIGHTNESS_CONTRAST_EFFECT_GUID {#BRIGHTNESS-CONTRAST-EFFECT-GUID}
```
public static final String BRIGHTNESS_CONTRAST_EFFECT_GUID
```


Gibt den Helligkeits‑Kontrast‑Effekt an.

### COLOR_BALANCE_EFFECT_GUID {#COLOR-BALANCE-EFFECT-GUID}
```
public static final String COLOR_BALANCE_EFFECT_GUID
```


Gibt den Farb‑Balance‑Effekt an.

### COLOR_CURVE_EFFECT_GUID {#COLOR-CURVE-EFFECT-GUID}
```
public static final String COLOR_CURVE_EFFECT_GUID
```


Gibt den Farbkurven‑Effekt an.

### COLOR_LOOKUP_TABLE_EFFECT_GUID {#COLOR-LOOKUP-TABLE-EFFECT-GUID}
```
public static final String COLOR_LOOKUP_TABLE_EFFECT_GUID
```


Gibt den Effekt der Farb-Lookup-Tabelle an.

### COLOR_MATRIX_EFFECT_GUID {#COLOR-MATRIX-EFFECT-GUID}
```
public static final String COLOR_MATRIX_EFFECT_GUID
```


Gibt den Effekt der Farbmatrix an.

### HUE_SATURATION_LIGHTNESS_EFFECT_GUID {#HUE-SATURATION-LIGHTNESS-EFFECT-GUID}
```
public static final String HUE_SATURATION_LIGHTNESS_EFFECT_GUID
```


Gibt den Effekt von Farbton, Sättigung und Helligkeit an.

### LEVELS_EFFECT_GUID {#LEVELS-EFFECT-GUID}
```
public static final String LEVELS_EFFECT_GUID
```


Gibt den Ebenen-Effekt an.

### RED_EYE_CORRECTION_EFFECT_GUID {#RED-EYE-CORRECTION-EFFECT-GUID}
```
public static final String RED_EYE_CORRECTION_EFFECT_GUID
```


Gibt den Rote-Augen-Korrektureffekt an.

### SHARPEN_EFFECT_GUID {#SHARPEN-EFFECT-GUID}
```
public static final String SHARPEN_EFFECT_GUID
```


Gibt den Schärfe-Effekt an.

### TINT_EFFECT_GUID {#TINT-EFFECT-GUID}
```
public static final String TINT_EFFECT_GUID
```


Gibt den Tönungs-Effekt an.

### contain(String objectGuid) {#contain-java.lang.String-}
```
public static boolean contain(String objectGuid)
```


Enthält die angegebene eindeutige Objektkennung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| objectGuid | java.lang.String | Die eindeutige Objektkennung. |

**Returns:**
boolescher Wert – Wahr, wenn enthalten.
