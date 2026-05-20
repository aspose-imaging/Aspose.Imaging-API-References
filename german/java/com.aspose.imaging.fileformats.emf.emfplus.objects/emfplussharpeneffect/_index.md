---
title: "EmfPlusSharpenEffect"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das SharpenEffect-Objekt gibt eine Erhöhung des Unterschieds in der Intensität zwischen Pixeln eines Bildes an."
type: docs
weight: 72
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplussharpeneffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusSharpenEffect extends EmfPlusImageEffectsObjectType
```

Das SharpenEffect-Objekt gibt eine Erhöhung des Unterschieds in der Intensität zwischen Pixeln eines Bildes an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusSharpenEffect()](#EmfPlusSharpenEffect--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRadius()](#getRadius--) | Liest oder setzt eine 32‑Bit-Gleitkommazahl, die den Schärferadius in Pixeln angibt und bestimmt, wie viele Pixel bei der Berechnung des neuen Werts eines bestimmten Pixels einbezogen werden. |
| [setRadius(float value)](#setRadius-float-) | Liest oder setzt eine 32‑Bit-Gleitkommazahl, die den Schärferadius in Pixeln angibt und bestimmt, wie viele Pixel bei der Berechnung des neuen Werts eines bestimmten Pixels einbezogen werden. |
| [getAmount()](#getAmount--) | Liest oder setzt eine 32‑Bit-Gleitkommazahl, die den Unterschied in der Intensität zwischen einem bestimmten Pixel und den umgebenden Pixeln angibt. |
| [setAmount(float value)](#setAmount-float-) | Liest oder setzt eine 32‑Bit-Gleitkommazahl, die den Unterschied in der Intensität zwischen einem bestimmten Pixel und den umgebenden Pixeln angibt. |
### EmfPlusSharpenEffect() {#EmfPlusSharpenEffect--}
```
public EmfPlusSharpenEffect()
```


### getRadius() {#getRadius--}
```
public float getRadius()
```


Liest oder setzt eine 32‑Bit-Gleitkommazahl, die den Schärferadius in Pixeln angibt und bestimmt, wie viele Pixel bei der Berechnung des neuen Werts eines bestimmten Pixels einbezogen werden. Wenn dieser Wert steigt, erhöht sich die Anzahl der in die Berechnung einbezogenen Pixel, und das resultierende Bitmap SOLLTE schärfer werden.

Wert: Der Radius.

**Returns:**
float
### setRadius(float value) {#setRadius-float-}
```
public void setRadius(float value)
```


Liest oder setzt eine 32‑Bit-Gleitkommazahl, die den Schärferadius in Pixeln angibt und bestimmt, wie viele Pixel bei der Berechnung des neuen Werts eines bestimmten Pixels einbezogen werden. Wenn dieser Wert steigt, erhöht sich die Anzahl der in die Berechnung einbezogenen Pixel, und das resultierende Bitmap SOLLTE schärfer werden.

Wert: Der Radius.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getAmount() {#getAmount--}
```
public float getAmount()
```


Liest oder setzt eine 32‑Bit-Gleitkommazahl, die den Unterschied in der Intensität zwischen einem bestimmten Pixel und den umgebenden Pixeln angibt. 0 gibt an, dass keine Schärfung DURCHGEFÜHRT WERDEN DARF. 0 < Wert \\u2264 100 Wenn dieser Wert steigt, sollte der Unterschied in der Intensität zwischen den Pixeln ZUVERSTÄNDIG zunehmen.

Wert: Der Betrag.

**Returns:**
float
### setAmount(float value) {#setAmount-float-}
```
public void setAmount(float value)
```


Liest oder setzt eine 32‑Bit-Gleitkommazahl, die den Unterschied in der Intensität zwischen einem bestimmten Pixel und den umgebenden Pixeln angibt. 0 gibt an, dass keine Schärfung DURCHGEFÜHRT WERDEN DARF. 0 < Wert \\u2264 100 Wenn dieser Wert steigt, sollte der Unterschied in der Intensität zwischen den Pixeln ZUVERSTÄNDIG zunehmen.

Wert: Der Betrag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

