---
title: "EmfPlusBlurEffect"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das BlurEffect-Objekt gibt eine Verringerung des Unterschieds in der Intensität zwischen Pixeln in einem Bild an."
type: docs
weight: 19
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusBlurEffect extends EmfPlusImageEffectsObjectType
```

Das BlurEffect-Objekt gibt eine Verringerung des Unterschieds in der Intensität zwischen Pixeln in einem Bild an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusBlurEffect()](#EmfPlusBlurEffect--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Liest oder schreibt eine 32‑Bit‑Gleitkommazahl, die den Unschärferadius in Pixeln angibt und bestimmt, wie viele Pixel bei der Berechnung des neuen Werts eines gegebenen Pixels einbezogen werden. |
| [setBlurRadius(float value)](#setBlurRadius-float-) | Liest oder schreibt eine 32‑Bit‑Gleitkommazahl, die den Unschärferadius in Pixeln angibt und bestimmt, wie viele Pixel bei der Berechnung des neuen Werts eines gegebenen Pixels einbezogen werden. |
| [getExpandEdge()](#getExpandEdge--) | Liest oder schreibt einen 32‑Bit‑Booleschen Wert, der angibt, ob das Bitmap um einen Betrag erweitert wird, der dem Wert von BlurRadius entspricht, um weiche Kanten zu erzeugen. |
| [setExpandEdge(boolean value)](#setExpandEdge-boolean-) | Liest oder schreibt einen 32‑Bit‑Booleschen Wert, der angibt, ob das Bitmap um einen Betrag erweitert wird, der dem Wert von BlurRadius entspricht, um weiche Kanten zu erzeugen. |
### EmfPlusBlurEffect() {#EmfPlusBlurEffect--}
```
public EmfPlusBlurEffect()
```


### getBlurRadius() {#getBlurRadius--}
```
public float getBlurRadius()
```


Liest oder schreibt eine 32‑Bit‑Gleitkommazahl, die den Unschärferadius in Pixeln angibt und bestimmt, wie viele Pixel bei der Berechnung des neuen Werts eines gegebenen Pixels einbezogen werden. Dieser Wert MUSS im Bereich 0,0 bis 255,0 liegen.

**Returns:**
float
### setBlurRadius(float value) {#setBlurRadius-float-}
```
public void setBlurRadius(float value)
```


Liest oder schreibt eine 32‑Bit‑Gleitkommazahl, die den Unschärferadius in Pixeln angibt und bestimmt, wie viele Pixel bei der Berechnung des neuen Werts eines gegebenen Pixels einbezogen werden. Dieser Wert MUSS im Bereich 0,0 bis 255,0 liegen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getExpandEdge() {#getExpandEdge--}
```
public boolean getExpandEdge()
```


Liest oder schreibt einen 32‑Bit‑Booleschen Wert, der angibt, ob das Bitmap um einen Betrag erweitert wird, der dem Wert von BlurRadius entspricht, um weiche Kanten zu erzeugen. Dieser Wert MUSS einer der folgenden sein: FALSE 0x00000000 Die Größe des Bitmaps DARF NICHT geändert werden, und seine weichen Kanten SOLLTEN auf die Größe von BlurRadius beschnitten werden. TRUE 0x00000001 Die Größe des Bitmaps SOLLTE um einen Betrag erweitert werden, der dem BlurRadius entspricht, um weiche Kanten zu erzeugen.

**Returns:**
boolean
### setExpandEdge(boolean value) {#setExpandEdge-boolean-}
```
public void setExpandEdge(boolean value)
```


Liest oder schreibt einen 32‑Bit‑Booleschen Wert, der angibt, ob das Bitmap um einen Betrag erweitert wird, der dem Wert von BlurRadius entspricht, um weiche Kanten zu erzeugen. Dieser Wert MUSS einer der folgenden sein: FALSE 0x00000000 Die Größe des Bitmaps DARF NICHT geändert werden, und seine weichen Kanten SOLLTEN auf die Größe von BlurRadius beschnitten werden. TRUE 0x00000001 Die Größe des Bitmaps SOLLTE um einen Betrag erweitert werden, der dem BlurRadius entspricht, um weiche Kanten zu erzeugen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

