---
title: "EmfPlusColorCurveEffect"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das ColorCurveEffect-Objekt gibt eine von acht Anpassungen an der Farbkurve eines Bildes an."
type: docs
weight: 27
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorCurveEffect extends EmfPlusImageEffectsObjectType
```

Das ColorCurveEffect-Objekt gibt eine von acht Anpassungen an der Farbkurve eines Bildes an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusColorCurveEffect()](#EmfPlusColorCurveEffect--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCurveAdjustment()](#getCurveAdjustment--) | Liest oder schreibt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Kurvenanpassung angibt, die auf die Farben im Bitmap angewendet wird. |
| [setCurveAdjustment(int value)](#setCurveAdjustment-int-) | Liest oder schreibt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Kurvenanpassung angibt, die auf die Farben im Bitmap angewendet wird. |
| [getCurveChannel()](#getCurveChannel--) | Liest oder schreibt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die den Farbkanal angibt, auf den die Kurvenanpassung angewendet wird. |
| [setCurveChannel(int value)](#setCurveChannel-int-) | Liest oder schreibt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die den Farbkanal angibt, auf den die Kurvenanpassung angewendet wird. |
| [getAdjustmentIntensity()](#getAdjustmentIntensity--) | Liest oder schreibt eine 32‑Bit‑Ganzzahl mit Vorzeichen, die die Intensität der Kurvenanpassung für den durch CurveChannel angegebenen Farbkanal festlegt. |
| [setAdjustmentIntensity(int value)](#setAdjustmentIntensity-int-) | Liest oder schreibt eine 32‑Bit‑Ganzzahl mit Vorzeichen, die die Intensität der Kurvenanpassung für den durch CurveChannel angegebenen Farbkanal festlegt. |
### EmfPlusColorCurveEffect() {#EmfPlusColorCurveEffect--}
```
public EmfPlusColorCurveEffect()
```


### getCurveAdjustment() {#getCurveAdjustment--}
```
public int getCurveAdjustment()
```


Liest oder schreibt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Kurvenanpassung angibt, die auf die Farben im Bitmap angewendet wird. Dieser Wert MUSS in der CurveAdjustments‑Aufzählung (Abschnitt 2.1.1.7) definiert sein.

**Returns:**
int
### setCurveAdjustment(int value) {#setCurveAdjustment-int-}
```
public void setCurveAdjustment(int value)
```


Liest oder schreibt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Kurvenanpassung angibt, die auf die Farben im Bitmap angewendet wird. Dieser Wert MUSS in der CurveAdjustments‑Aufzählung (Abschnitt 2.1.1.7) definiert sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCurveChannel() {#getCurveChannel--}
```
public int getCurveChannel()
```


Liest oder schreibt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die den Farbkanal angibt, auf den die Kurvenanpassung angewendet wird. Dieser Wert MUSS in der CurveChannel‑Aufzählung (Abschnitt 2.1.1.8) definiert sein.

**Returns:**
int
### setCurveChannel(int value) {#setCurveChannel-int-}
```
public void setCurveChannel(int value)
```


Liest oder schreibt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die den Farbkanal angibt, auf den die Kurvenanpassung angewendet wird. Dieser Wert MUSS in der CurveChannel‑Aufzählung (Abschnitt 2.1.1.8) definiert sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getAdjustmentIntensity() {#getAdjustmentIntensity--}
```
public int getAdjustmentIntensity()
```


Liest oder schreibt eine 32‑Bit‑Ganzzahl mit Vorzeichen, die die Intensität der Kurvenanpassung für den durch CurveChannel angegebenen Farbkanal festlegt. Die sinnvollen Wertebereiche für dieses Feld variieren je nach CurveAdjustment‑Wert wie folgt: Belichtungsanpassungsbereich: -255 \\u2264 value < 0 Wenn der Wert sinkt, sollte die Belichtung des Bildes abnehmen. 0 Ein Wert von 0 gibt an, dass die Belichtung NICHT geändert werden DÜRFEN. 0 < value \\u2264 255 Wenn der Wert steigt, sollte die Belichtung des Bildes zunehmen. Dichteanpassungsbereich: -255 \\u2264 value < 0 Wenn der Wert sinkt, sollte die Dichte des Bildes abnehmen, was zu einem dunkleren Bild führt. 0 Ein Wert von 0 gibt an, dass die Dichte NICHT geändert werden DÜRFEN. 0 < value \\u2264 255 Wenn der Wert steigt, sollte die Dichte des Bildes zunehmen. Kontrastanpassungsbereich: -100 \\u2264 value < 0 Wenn der Wert sinkt, sollte der Kontrast des Bildes abnehmen. 0 Ein Wert von 0 gibt an, dass der Kontrast NICHT geändert werden DÜRFEN. 0 < value \\u2264 100 Wenn der Wert steigt, sollte der Kontrast des Bildes zunehmen. Highlight‑Anpassungsbereich: -100 \\u2264 value < 0 Wenn der Wert sinkt, sollten die hellen Bildbereiche dunkler erscheinen. 0 Ein Wert von 0 gibt an, dass das Highlight NICHT geändert werden DÜRFEN. 0 < value \\u2264 100 Wenn der Wert steigt, sollten die hellen Bildbereiche heller erscheinen. Schatten‑Anpassungsbereich: -100 \\u2264 value < 0 Wenn der Wert sinkt, sollten die dunklen Bildbereiche dunkler erscheinen. 0 Ein Wert von 0 gibt an, dass der Schatten NICHT geändert werden DÜRFEN. 0 < value \\u2264 100 Wenn der Wert steigt, sollten die dunklen Bildbereiche heller erscheinen. Weiß‑Sättigungs‑Anpassungsbereich: 0 \\u2014 255 Wenn der Wert steigt, erhöht sich die obere Grenze des Intensitätsbereichs des Farbkanals. Schwarz‑Sättigungs‑Anpassungsbereich: 0 \\u2014 255 Wenn der Wert steigt, erhöht sich die untere Grenze des Intensitätsbereichs des Farbkanals.

**Returns:**
int
### setAdjustmentIntensity(int value) {#setAdjustmentIntensity-int-}
```
public void setAdjustmentIntensity(int value)
```


Liest oder schreibt eine 32‑Bit‑Ganzzahl mit Vorzeichen, die die Intensität der Kurvenanpassung für den durch CurveChannel angegebenen Farbkanal festlegt. Die sinnvollen Wertebereiche für dieses Feld variieren je nach CurveAdjustment‑Wert wie folgt: Belichtungsanpassungsbereich: -255 \\u2264 value < 0 Wenn der Wert sinkt, sollte die Belichtung des Bildes abnehmen. 0 Ein Wert von 0 gibt an, dass die Belichtung NICHT geändert werden DÜRFEN. 0 < value \\u2264 255 Wenn der Wert steigt, sollte die Belichtung des Bildes zunehmen. Dichteanpassungsbereich: -255 \\u2264 value < 0 Wenn der Wert sinkt, sollte die Dichte des Bildes abnehmen, was zu einem dunkleren Bild führt. 0 Ein Wert von 0 gibt an, dass die Dichte NICHT geändert werden DÜRFEN. 0 < value \\u2264 255 Wenn der Wert steigt, sollte die Dichte des Bildes zunehmen. Kontrastanpassungsbereich: -100 \\u2264 value < 0 Wenn der Wert sinkt, sollte der Kontrast des Bildes abnehmen. 0 Ein Wert von 0 gibt an, dass der Kontrast NICHT geändert werden DÜRFEN. 0 < value \\u2264 100 Wenn der Wert steigt, sollte der Kontrast des Bildes zunehmen. Highlight‑Anpassungsbereich: -100 \\u2264 value < 0 Wenn der Wert sinkt, sollten die hellen Bildbereiche dunkler erscheinen. 0 Ein Wert von 0 gibt an, dass das Highlight NICHT geändert werden DÜRFEN. 0 < value \\u2264 100 Wenn der Wert steigt, sollten die hellen Bildbereiche heller erscheinen. Schatten‑Anpassungsbereich: -100 \\u2264 value < 0 Wenn der Wert sinkt, sollten die dunklen Bildbereiche dunkler erscheinen. 0 Ein Wert von 0 gibt an, dass der Schatten NICHT geändert werden DÜRFEN. 0 < value \\u2264 100 Wenn der Wert steigt, sollten die dunklen Bildbereiche heller erscheinen. Weiß‑Sättigungs‑Anpassungsbereich: 0 \\u2014 255 Wenn der Wert steigt, erhöht sich die obere Grenze des Intensitätsbereichs des Farbkanals. Schwarz‑Sättigungs‑Anpassungsbereich: 0 \\u2014 255 Wenn der Wert steigt, erhöht sich die untere Grenze des Intensitätsbereichs des Farbkanals.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

