---
title: "EmfPlusRedEyeCorrectionEffect"
second_title: "Aspose.Imaging för Java API-referens"
description: "RedEyeCorrectionEffect-objektet specificerar områden i en bild som en rödögonkorrigering tillämpas på."
type: docs
weight: 67
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusredeyecorrectioneffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusRedEyeCorrectionEffect extends EmfPlusImageEffectsObjectType
```

RedEyeCorrectionEffect-objektet specificerar områden i en bild som en rödögonkorrigering tillämpas på.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusRedEyeCorrectionEffect()](#EmfPlusRedEyeCorrectionEffect--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getNumberOfAreas()](#getNumberOfAreas--) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar antalet rektanglar i Areas‑fältet. |
| [setNumberOfAreas(int value)](#setNumberOfAreas-int-) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar antalet rektanglar i Areas‑fältet. |
| [getAreas()](#getAreas--) | Hämtar eller anger en array av NumberOfAreas WMF RectL-objekt, specificerade i [MS-WMF] sektion 2.2.2.19. |
| [setAreas(Rectangle[] value)](#setAreas-com.aspose.imaging.Rectangle---) | Hämtar eller anger en array av NumberOfAreas WMF RectL-objekt, specificerade i [MS-WMF] sektion 2.2.2.19. |
### EmfPlusRedEyeCorrectionEffect() {#EmfPlusRedEyeCorrectionEffect--}
```
public EmfPlusRedEyeCorrectionEffect()
```


### getNumberOfAreas() {#getNumberOfAreas--}
```
public int getNumberOfAreas()
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar antalet rektanglar i Areas‑fältet.

Värde: Antalet områden.

**Returns:**
int
### setNumberOfAreas(int value) {#setNumberOfAreas-int-}
```
public void setNumberOfAreas(int value)
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar antalet rektanglar i Areas‑fältet.

Värde: Antalet områden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getAreas() {#getAreas--}
```
public Rectangle[] getAreas()
```


Hämtar eller anger en array av NumberOfAreas WMF RectL-objekt, specificerade i [MS-WMF] avsnitt 2.2.2.19. Varje rektangel anger ett område av bitmap-bilden som red-eye-korrektureffekten SKA tillämpas på.

Värde: Områdena.

**Returns:**
com.aspose.imaging.Rectangle[]
### setAreas(Rectangle[] value) {#setAreas-com.aspose.imaging.Rectangle---}
```
public void setAreas(Rectangle[] value)
```


Hämtar eller anger en array av NumberOfAreas WMF RectL-objekt, specificerade i [MS-WMF] avsnitt 2.2.2.19. Varje rektangel anger ett område av bitmap-bilden som red-eye-korrektureffekten SKA tillämpas på.

Värde: Områdena.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

