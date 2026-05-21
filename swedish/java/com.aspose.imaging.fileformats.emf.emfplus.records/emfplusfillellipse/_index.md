---
title: "EmfPlusFillEllipse"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusFillEllipse-posten specificerar fyllning av insidan av en ellips."
type: docs
weight: 33
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillEllipse extends EmfPlusDrawingRecordType
```

EmfPlusFillEllipse-posten specificerar fyllning av insidan av en ellips.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusFillEllipse(EmfPlusRecord source)](#EmfPlusFillEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusFillEllipse`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isColor()](#isColor--) | Hämtar eller anger ett värde som indikerar om denna instans är färg. |
| [setColor(boolean value)](#setColor-boolean-) | Hämtar eller anger ett värde som indikerar om denna instans är färg. |
| [isCompressed()](#isCompressed--) | Hämtar eller anger ett värde som indikerar om denna instans är komprimerad. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Hämtar eller anger ett värde som indikerar om denna instans är komprimerad. |
| [getBrushId()](#getBrushId--) | Hämtar eller anger penselidentifieraren Ett 32-bitars osignerat heltal som specificerar penseln, vars innehåll bestäms av S‑biten i Flags‑fältet. |
| [setBrushId(int value)](#setBrushId-int-) | Hämtar eller anger penselidentifieraren Ett 32-bitars osignerat heltal som specificerar penseln, vars innehåll bestäms av S‑biten i Flags‑fältet. |
| [getRectData()](#getRectData--) | Hämtar eller anger rektangulär data Antingen ett EmfPlusRect‑ eller EmfPlusRectF‑objekt som definierar den omgivande rutan för ellipsen |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Hämtar eller anger rektangulär data Antingen ett EmfPlusRect‑ eller EmfPlusRectF‑objekt som definierar den omgivande rutan för ellipsen |
### EmfPlusFillEllipse(EmfPlusRecord source) {#EmfPlusFillEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillEllipse(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusFillEllipse`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Hämtar eller anger ett värde som indikerar om denna instans är färg. Om satt specificerar BrushId en färg som ett EmfPlusARGB‑objekt (avsnitt 2.2.2.1). Om rensad innehåller BrushId indexet för ett EmfPlusBrush‑objekt (avsnitt 2.2.1.1) i EMF+‑objektabellen.

Värde: `true` om denna instans är färg; annars `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Hämtar eller anger ett värde som indikerar om denna instans är färg. Om satt specificerar BrushId en färg som ett EmfPlusARGB‑objekt (avsnitt 2.2.2.1). Om rensad innehåller BrushId indexet för ett EmfPlusBrush‑objekt (avsnitt 2.2.1.1) i EMF+‑objektabellen.

Värde: `true` om denna instans är färg; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### isCompressed() {#isCompressed--}
```
public boolean isCompressed()
```


Hämtar eller anger ett värde som indikerar om denna instans är komprimerad. Om den är satt innehåller RectData ett EmfPlusRect‑objekt (avsnitt 2.2.2.38). Om den är avmarkerad innehåller RectData ett EmfPlusRectF‑objekt (avsnitt 2.2.2.39).

Värde: `true` om denna instans är komprimerad; annars `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Hämtar eller anger ett värde som indikerar om denna instans är komprimerad. Om den är satt innehåller RectData ett EmfPlusRect‑objekt (avsnitt 2.2.2.38). Om den är avmarkerad innehåller RectData ett EmfPlusRectF‑objekt (avsnitt 2.2.2.39).

Värde: `true` om denna instans är komprimerad; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Hämtar eller anger penselidentifieraren Ett 32‑bitars osignerat heltal som specificerar penseln, vars innehåll bestäms av S‑biten i Flags‑fältet. Denna definition används för att fylla ellipsens inre.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Hämtar eller anger penselidentifieraren Ett 32‑bitars osignerat heltal som specificerar penseln, vars innehåll bestäms av S‑biten i Flags‑fältet. Denna definition används för att fylla ellipsens inre.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Hämtar eller anger rektangulär data Antingen ett EmfPlusRect‑ eller EmfPlusRectF‑objekt som definierar den omgivande rutan för ellipsen

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Hämtar eller anger rektangulär data Antingen ett EmfPlusRect‑ eller EmfPlusRectF‑objekt som definierar den omgivande rutan för ellipsen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

