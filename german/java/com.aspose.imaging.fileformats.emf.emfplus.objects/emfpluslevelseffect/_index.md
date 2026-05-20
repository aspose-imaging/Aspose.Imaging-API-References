---
title: "EmfPlusLevelsEffect"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das LevelsEffect‑Objekt gibt Anpassungen für die Lichter, Mitten und Schatten eines Bildes an."
type: docs
weight: 51
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusLevelsEffect extends EmfPlusImageEffectsObjectType
```

Das LevelsEffect-Objekt gibt Anpassungen von Highlights, Mitten und Schatten eines Bildes an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusLevelsEffect()](#EmfPlusLevelsEffect--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHighlight()](#getHighlight--) | Liest oder schreibt die Angabe, wie stark die Lichter eines Bildes aufgehellt werden sollen. |
| [setHighlight(int value)](#setHighlight-int-) | Liest oder schreibt die Angabe, wie stark die Lichter eines Bildes aufgehellt werden sollen. |
| [getMidTone()](#getMidTone--) | Liest oder schreibt die Angabe, wie stark die Mitten eines Bildes aufgehellt oder abgedunkelt werden sollen. |
| [setMidTone(int value)](#setMidTone-int-) | Liest oder schreibt die Angabe, wie stark die Mitten eines Bildes aufgehellt oder abgedunkelt werden sollen. |
| [getShadow()](#getShadow--) | Liest oder schreibt die Angabe, wie stark die Schatten eines Bildes abgedunkelt werden sollen. |
| [setShadow(int value)](#setShadow-int-) | Liest oder schreibt die Angabe, wie stark die Schatten eines Bildes abgedunkelt werden sollen. |
### EmfPlusLevelsEffect() {#EmfPlusLevelsEffect--}
```
public EmfPlusLevelsEffect()
```


### getHighlight() {#getHighlight--}
```
public int getHighlight()
```


Liest oder schreibt die Angabe, wie stark die Lichter eines Bildes aufgehellt werden sollen. Die Farbkanalwerte am oberen Ende des Intensitätsbereichs werden stärker verändert als Werte in der Mitte oder am unteren Ende, was bedeutet, dass ein Bild aufgehellt werden kann, ohne den Kontrast zu den dunkleren Bildbereichen zu verlieren. 0 \\u2264 value < Gibt an, dass Lichter mit einem Intensitätsprozentsatz über diesem Schwellenwert 100 erhöht werden SOLLTEN. 100 Gibt an, dass Lichter NICHT geändert werden DÜRFEN.

Wert: Das Highlight.

**Returns:**
int
### setHighlight(int value) {#setHighlight-int-}
```
public void setHighlight(int value)
```


Liest oder schreibt die Angabe, wie stark die Lichter eines Bildes aufgehellt werden sollen. Die Farbkanalwerte am oberen Ende des Intensitätsbereichs werden stärker verändert als Werte in der Mitte oder am unteren Ende, was bedeutet, dass ein Bild aufgehellt werden kann, ohne den Kontrast zu den dunkleren Bildbereichen zu verlieren. 0 \\u2264 value < Gibt an, dass Lichter mit einem Intensitätsprozentsatz über diesem Schwellenwert 100 erhöht werden SOLLTEN. 100 Gibt an, dass Lichter NICHT geändert werden DÜRFEN.

Wert: Das Highlight.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getMidTone() {#getMidTone--}
```
public int getMidTone()
```


Liest oder schreibt die Angabe, wie stark die Mitten eines Bildes aufgehellt oder abgedunkelt werden sollen. Farbkanalwerte in der Mitte des Intensitätsbereichs werden stärker verändert als Werte nahe dem oberen oder unteren Ende, was bedeutet, dass ein Bild aufgehellt oder abgedunkelt werden kann, ohne den Kontrast zwischen den dunkelsten und hellsten Bildbereichen zu verlieren. -100 \\u2264 value < 0 Gibt an, dass die Mitten dunkler gemacht werden. 0 Gibt an, dass die Mitten NICHT geändert werden DÜRFEN. 0 < value \\u2264 100 Gibt an, dass die Mitten aufgehellt werden.

Wert: Der Mittelton.

**Returns:**
int
### setMidTone(int value) {#setMidTone-int-}
```
public void setMidTone(int value)
```


Liest oder schreibt die Angabe, wie stark die Mitten eines Bildes aufgehellt oder abgedunkelt werden sollen. Farbkanalwerte in der Mitte des Intensitätsbereichs werden stärker verändert als Werte nahe dem oberen oder unteren Ende, was bedeutet, dass ein Bild aufgehellt oder abgedunkelt werden kann, ohne den Kontrast zwischen den dunkelsten und hellsten Bildbereichen zu verlieren. -100 \\u2264 value < 0 Gibt an, dass die Mitten dunkler gemacht werden. 0 Gibt an, dass die Mitten NICHT geändert werden DÜRFEN. 0 < value \\u2264 100 Gibt an, dass die Mitten aufgehellt werden.

Wert: Der Mittelton.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getShadow() {#getShadow--}
```
public int getShadow()
```


Liest oder schreibt die Angabe, wie stark die Schatten eines Bildes abgedunkelt werden sollen. Farbkanalwerte am unteren Ende des Intensitätsbereichs werden stärker verändert als Werte in der Mitte oder am oberen Ende, was bedeutet, dass ein Bild abgedunkelt werden kann, ohne den Kontrast zu den helleren Bildbereichen zu verlieren. 0 Gibt an, dass Schatten NICHT geändert werden DÜRFEN. 0 < value \\u2264 100 Gibt an, dass Schatten mit einem Intensitätsprozentsatz unterhalb dieses Schwellenwertes dunkler gemacht werden.

Wert: Der Schatten.

**Returns:**
int
### setShadow(int value) {#setShadow-int-}
```
public void setShadow(int value)
```


Liest oder schreibt die Angabe, wie stark die Schatten eines Bildes abgedunkelt werden sollen. Farbkanalwerte am unteren Ende des Intensitätsbereichs werden stärker verändert als Werte in der Mitte oder am oberen Ende, was bedeutet, dass ein Bild abgedunkelt werden kann, ohne den Kontrast zu den helleren Bildbereichen zu verlieren. 0 Gibt an, dass Schatten NICHT geändert werden DÜRFEN. 0 < value \\u2264 100 Gibt an, dass Schatten mit einem Intensitätsprozentsatz unterhalb dieses Schwellenwertes dunkler gemacht werden.

Wert: Der Schatten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

