---
title: "EmfPlusRedEyeCorrectionEffect"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das RedEyeCorrectionEffect-Objekt gibt Bereiche eines Bildes an, auf die eine Rote-Augen-Korrektur angewendet wird."
type: docs
weight: 67
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusredeyecorrectioneffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusRedEyeCorrectionEffect extends EmfPlusImageEffectsObjectType
```

Das RedEyeCorrectionEffect-Objekt gibt Bereiche eines Bildes an, auf die eine Rote-Augen-Korrektur angewendet wird.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusRedEyeCorrectionEffect()](#EmfPlusRedEyeCorrectionEffect--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getNumberOfAreas()](#getNumberOfAreas--) | Ruft den 32‑Bit‑vorzeichenbehafteten Integer ab oder legt ihn fest, der die Anzahl der Rechtecke im Feld Areas angibt. |
| [setNumberOfAreas(int value)](#setNumberOfAreas-int-) | Ruft den 32‑Bit‑vorzeichenbehafteten Integer ab oder legt ihn fest, der die Anzahl der Rechtecke im Feld Areas angibt. |
| [getAreas()](#getAreas--) | Ruft ein Array von NumberOfAreas WMF RectL‑Objekten ab oder legt es fest, das in [MS-WMF] Abschnitt 2.2.2.19 angegeben ist. |
| [setAreas(Rectangle[] value)](#setAreas-com.aspose.imaging.Rectangle---) | Ruft ein Array von NumberOfAreas WMF RectL‑Objekten ab oder legt es fest, das in [MS-WMF] Abschnitt 2.2.2.19 angegeben ist. |
### EmfPlusRedEyeCorrectionEffect() {#EmfPlusRedEyeCorrectionEffect--}
```
public EmfPlusRedEyeCorrectionEffect()
```


### getNumberOfAreas() {#getNumberOfAreas--}
```
public int getNumberOfAreas()
```


Ruft den 32‑Bit‑vorzeichenbehafteten Integer ab oder legt ihn fest, der die Anzahl der Rechtecke im Feld Areas angibt.

Wert: Die Anzahl der Bereiche.

**Returns:**
int
### setNumberOfAreas(int value) {#setNumberOfAreas-int-}
```
public void setNumberOfAreas(int value)
```


Ruft den 32‑Bit‑vorzeichenbehafteten Integer ab oder legt ihn fest, der die Anzahl der Rechtecke im Feld Areas angibt.

Wert: Die Anzahl der Bereiche.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getAreas() {#getAreas--}
```
public Rectangle[] getAreas()
```


Liest oder setzt das Array von NumberOfAreas WMF RectL-Objekten, angegeben in [MS-WMF] Abschnitt 2.2.2.19. Jedes Rechteck gibt einen Bereich des Bitmap-Bildes an, auf den der Rote-Augen-Korrektureffekt ANGEWENDET WERDEN SOLLTE.

Wert: Die Bereiche.

**Returns:**
com.aspose.imaging.Rectangle[]
### setAreas(Rectangle[] value) {#setAreas-com.aspose.imaging.Rectangle---}
```
public void setAreas(Rectangle[] value)
```


Liest oder setzt das Array von NumberOfAreas WMF RectL-Objekten, angegeben in [MS-WMF] Abschnitt 2.2.2.19. Jedes Rechteck gibt einen Bereich des Bitmap-Bildes an, auf den der Rote-Augen-Korrektureffekt ANGEWENDET WERDEN SOLLTE.

Wert: Die Bereiche.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

