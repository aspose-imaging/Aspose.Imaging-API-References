---
title: "EmfPlusBrightnessContrastEffect"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das BrightnessContrastEffect-Objekt gibt eine Erweiterung oder Kontraktion der hellsten und dunkelsten Bereiche eines Bildes an."
type: docs
weight: 23
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrightnesscontrasteffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusBrightnessContrastEffect extends EmfPlusImageEffectsObjectType
```

Das BrightnessContrastEffect-Objekt gibt eine Erweiterung oder Kontraktion der hellsten und dunkelsten Bereiche eines Bildes an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusBrightnessContrastEffect()](#EmfPlusBrightnessContrastEffect--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBrightnessLevel()](#getBrightnessLevel--) | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der den Helligkeitswert angibt. |
| [setBrightnessLevel(int value)](#setBrightnessLevel-int-) | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der den Helligkeitswert angibt. |
| [getContrastLevel()](#getContrastLevel--) | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der den Kontrastwert angibt. |
| [setContrastLevel(int value)](#setContrastLevel-int-) | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der den Kontrastwert angibt. |
### EmfPlusBrightnessContrastEffect() {#EmfPlusBrightnessContrastEffect--}
```
public EmfPlusBrightnessContrastEffect()
```


### getBrightnessLevel() {#getBrightnessLevel--}
```
public int getBrightnessLevel()
```


Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die Helligkeitsstufe angibt. Dieser Wert MUSS im Bereich -255 bis 255 liegen, mit den folgenden Wirkungen: -255 \\u2264 Wert < 0 Wenn der Wert abnimmt, SOLL die Helligkeit des Bildes abnehmen. 0 Ein Wert von 0 gibt an, dass die Helligkeit NICHT geändert werden DARF. 0 < Wert \\u2264 255 Wenn der Wert steigt, SOLL die Helligkeit des Bildes zunehmen.

**Returns:**
int
### setBrightnessLevel(int value) {#setBrightnessLevel-int-}
```
public void setBrightnessLevel(int value)
```


Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die Helligkeitsstufe angibt. Dieser Wert MUSS im Bereich -255 bis 255 liegen, mit den folgenden Wirkungen: -255 \\u2264 Wert < 0 Wenn der Wert abnimmt, SOLL die Helligkeit des Bildes abnehmen. 0 Ein Wert von 0 gibt an, dass die Helligkeit NICHT geändert werden DARF. 0 < Wert \\u2264 255 Wenn der Wert steigt, SOLL die Helligkeit des Bildes zunehmen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getContrastLevel() {#getContrastLevel--}
```
public int getContrastLevel()
```


Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die Kontraststufe angibt. Dieser Wert MUSS im Bereich -100 bis 100 liegen, mit den folgenden Wirkungen: -100 \\u2264 Wert < 0 Wenn der Wert abnimmt, SOLL der Kontrast des Bildes abnehmen. 0 Ein Wert von 0 gibt an, dass der Kontrast NICHT geändert werden DARF. 0 < Wert \\u2264 100 Wenn der Wert steigt, SOLL der Kontrast des Bildes zunehmen.

**Returns:**
int
### setContrastLevel(int value) {#setContrastLevel-int-}
```
public void setContrastLevel(int value)
```


Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die Kontraststufe angibt. Dieser Wert MUSS im Bereich -100 bis 100 liegen, mit den folgenden Wirkungen: -100 \\u2264 Wert < 0 Wenn der Wert abnimmt, SOLL der Kontrast des Bildes abnehmen. 0 Ein Wert von 0 gibt an, dass der Kontrast NICHT geändert werden DARF. 0 < Wert \\u2264 100 Wenn der Wert steigt, SOLL der Kontrast des Bildes zunehmen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

