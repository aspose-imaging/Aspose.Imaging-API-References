---
title: "EmfPlusFillRects"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusFillRects-posten specificerar fyllning av insidan av en serie rektanglar."
type: docs
weight: 37
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillRects extends EmfPlusDrawingRecordType
```

EmfPlusFillRects-posten specificerar fyllning av insidan av en serie rektanglar.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusFillRects(EmfPlusRecord source)](#EmfPlusFillRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusFillRects`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isColor()](#isColor--) | Hämtar eller anger ett värde som indikerar om denna instans är färg. |
| [setColor(boolean value)](#setColor-boolean-) | Hämtar eller anger ett värde som indikerar om denna instans är färg. |
| [getCompressed()](#getCompressed--) | Hämtar eller anger ett värde som indikerar om detta `EmfPlusFillRects` är komprimerat. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Hämtar eller anger ett värde som indikerar om detta `EmfPlusFillRects` är komprimerat. |
| [getBrushId()](#getBrushId--) | Hämtar eller anger borstidentifieraren Ett 32-bitars osignerat heltal som definierar borsten, vars innehåll bestäms av S‑biten i Flag‑fältet. |
| [setBrushId(int value)](#setBrushId-int-) | Hämtar eller anger borstidentifieraren Ett 32-bitars osignerat heltal som definierar borsten, vars innehåll bestäms av S‑biten i Flag‑fältet. |
| [getRectData()](#getRectData--) | Hämtar eller anger rektangeldata. En array av antingen EmfPlusRect- eller EmfPlusRectF-objekt med längden Count som definierar rektangeldata. |
| [setRectData(RectangleF[] value)](#setRectData-com.aspose.imaging.RectangleF---) | Hämtar eller anger rektangeldata. En array av antingen EmfPlusRect- eller EmfPlusRectF-objekt med längden Count som definierar rektangeldata. |
### EmfPlusFillRects(EmfPlusRecord source) {#EmfPlusFillRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillRects(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusFillRects`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Hämtar eller anger ett värde som indikerar om den här instansen är färg. Om satt anger BrushId en färg som ett EmfPlusARGB‑objekt (avsnitt 2.2.2.1). Om avmarkerad innehåller BrushId indexet för ett EmfPlusBrush‑objekt (avsnitt 2.2.1.1) i EMF+‑objektabellen.

Värde: `true` om denna instans är färg; annars `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Hämtar eller anger ett värde som indikerar om den här instansen är färg. Om satt anger BrushId en färg som ett EmfPlusARGB‑objekt (avsnitt 2.2.2.1). Om avmarkerad innehåller BrushId indexet för ett EmfPlusBrush‑objekt (avsnitt 2.2.1.1) i EMF+‑objektabellen.

Värde: `true` om denna instans är färg; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Hämtar eller anger ett värde som indikerar om detta `EmfPlusFillRects` är komprimerat. Om satt innehåller RectData ett EmfPlusRect-objekt (avsnitt 2.2.2.38). Om rensat innehåller RectData ett EmfPlusRectF-objekt (avsnitt 2.2.2.39) objekt.

Värde: `true` om komprimerad; annars `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta `EmfPlusFillRects` är komprimerat. Om satt innehåller RectData ett EmfPlusRect-objekt (avsnitt 2.2.2.38). Om rensat innehåller RectData ett EmfPlusRectF-objekt (avsnitt 2.2.2.39) objekt.

Värde: `true` om komprimerad; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Hämtar eller anger borstidentifieraren Ett 32-bitars osignerat heltal som definierar borsten, vars innehåll bestäms av S‑biten i Flag‑fältet.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Hämtar eller anger borstidentifieraren Ett 32-bitars osignerat heltal som definierar borsten, vars innehåll bestäms av S‑biten i Flag‑fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getRectData() {#getRectData--}
```
public RectangleF[] getRectData()
```


Hämtar eller anger rektangeldata. En array av antingen EmfPlusRect- eller EmfPlusRectF-objekt med längden Count som definierar rektangeldata.

**Returns:**
com.aspose.imaging.RectangleF[]
### setRectData(RectangleF[] value) {#setRectData-com.aspose.imaging.RectangleF---}
```
public void setRectData(RectangleF[] value)
```


Hämtar eller anger rektangeldata. En array av antingen EmfPlusRect- eller EmfPlusRectF-objekt med längden Count som definierar rektangeldata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF\[\]](../../com.aspose.imaging/rectanglef) |  |

