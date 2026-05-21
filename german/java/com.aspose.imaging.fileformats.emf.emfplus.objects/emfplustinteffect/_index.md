---
title: "EmfPlusTintEffect"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das TintEffect-Objekt gibt eine Zugabe von Schwarz oder Weiß zu einem angegebenen Farbton in einem Bild an."
type: docs
weight: 79
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustinteffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusTintEffect extends EmfPlusImageEffectsObjectType
```

Das TintEffect-Objekt gibt eine Zugabe von Schwarz oder Weiß zu einem angegebenen Farbton in einem Bild an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusTintEffect()](#EmfPlusTintEffect--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHue()](#getHue--) | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der den Farbton angibt, auf den der Tönungseffekt angewendet wird. |
| [setHue(int value)](#setHue-int-) | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der den Farbton angibt, auf den der Tönungseffekt angewendet wird. |
| [getAmount()](#getAmount--) | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der angibt, wie stark der Farbton verstärkt oder abgeschwächt wird. |
| [setAmount(int value)](#setAmount-int-) | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der angibt, wie stark der Farbton verstärkt oder abgeschwächt wird. |
### EmfPlusTintEffect() {#EmfPlusTintEffect--}
```
public EmfPlusTintEffect()
```


### getHue() {#getHue--}
```
public int getHue()
```


Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der den Farbton angibt, auf den der Tönungseffekt angewendet wird. -180 \\u2264 value < 0 Die Farbe bei einer angegebenen gegen den Uhrzeigersinn gedrehten Rotation des Farbkreises, beginnend bei Blau. 0 Ein Wert von 0 gibt die Farbe Blau im Farbkreis an. 0 < value \\u2264 180 Die Farbe bei einer angegebenen im Uhrzeigersinn gedrehten Rotation des Farbkreises, beginnend bei Blau.

**Returns:**
int
### setHue(int value) {#setHue-int-}
```
public void setHue(int value)
```


Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der den Farbton angibt, auf den der Tönungseffekt angewendet wird. -180 \\u2264 value < 0 Die Farbe bei einer angegebenen gegen den Uhrzeigersinn gedrehten Rotation des Farbkreises, beginnend bei Blau. 0 Ein Wert von 0 gibt die Farbe Blau im Farbkreis an. 0 < value \\u2264 180 Die Farbe bei einer angegebenen im Uhrzeigersinn gedrehten Rotation des Farbkreises, beginnend bei Blau.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getAmount() {#getAmount--}
```
public int getAmount()
```


Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der angibt, wie stark der Farbton verstärkt oder abgeschwächt wird. -100 \\u2264 value < 0 Negative Werte geben an, wie stark der Farbton abgeschwächt wird, was einer Zugabe von Schwarz entspricht. 0 Ein Wert von 0 gibt an, dass die Tönung DARF NICHT geändert werden. 0 < value \\u2264 100 Positive Werte geben an, wie stark der Farbton verstärkt wird, was einer Zugabe von Weiß entspricht.

Wert: Der Betrag.

**Returns:**
int
### setAmount(int value) {#setAmount-int-}
```
public void setAmount(int value)
```


Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der angibt, wie stark der Farbton verstärkt oder abgeschwächt wird. -100 \\u2264 value < 0 Negative Werte geben an, wie stark der Farbton abgeschwächt wird, was einer Zugabe von Schwarz entspricht. 0 Ein Wert von 0 gibt an, dass die Tönung DARF NICHT geändert werden. 0 < value \\u2264 100 Positive Werte geben an, wie stark der Farbton verstärkt wird, was einer Zugabe von Weiß entspricht.

Wert: Der Betrag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

