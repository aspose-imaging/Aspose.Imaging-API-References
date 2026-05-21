---
title: "EmfPlusFillPolygon"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusFillPolygon-posten specificerar fyllning av insidan av en polygon."
type: docs
weight: 36
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPolygon extends EmfPlusDrawingRecordType
```

EmfPlusFillPolygon-posten specificerar fyllning av insidan av en polygon.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusFillPolygon(EmfPlusRecord source)](#EmfPlusFillPolygon-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusFillPolygon`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isColor()](#isColor--) | Hämtar eller anger ett värde som indikerar om denna instans är färg. |
| [setColor(boolean value)](#setColor-boolean-) | Hämtar eller anger ett värde som indikerar om denna instans är färg. |
| [isCompressed()](#isCompressed--) | Hämtar eller anger ett värde som indikerar om denna instans är komprimerad. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Hämtar eller anger ett värde som indikerar om denna instans är komprimerad. |
| [isRelative()](#isRelative--) | Hämtar eller anger ett värde som indikerar om denna instans är relativ. |
| [setRelative(boolean value)](#setRelative-boolean-) | Hämtar eller anger ett värde som indikerar om denna instans är relativ. |
| [getBrushId()](#getBrushId--) | Hämtar eller anger borstidentifieraren Ett 32-bitars osignerat heltal som definierar borsten, vars innehåll bestäms av S‑biten i Flag‑fältet. |
| [setBrushId(int value)](#setBrushId-int-) | Hämtar eller anger borstidentifieraren Ett 32-bitars osignerat heltal som definierar borsten, vars innehåll bestäms av S‑biten i Flag‑fältet. |
| [getPointData()](#getPointData--) | Hämtar eller anger punktdata En matris av Count‑punkter som definierar polygonens hörn. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Hämtar eller anger punktdata En matris av Count‑punkter som definierar polygonens hörn. |
### EmfPlusFillPolygon(EmfPlusRecord source) {#EmfPlusFillPolygon-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPolygon(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusFillPolygon`.

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


Hämtar eller anger ett värde som indikerar om den här instansen är komprimerad. Om satt anger PointData absoluta positioner i koordinatrymden med 16-bitars heltalskoordinater. Om avmarkerad anger PointData absoluta positioner i koordinatrymden med 32-bitars flyttalskoordinater.

Värde: `true` om denna instans är komprimerad; annars `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Hämtar eller anger ett värde som indikerar om den här instansen är komprimerad. Om satt anger PointData absoluta positioner i koordinatrymden med 16-bitars heltalskoordinater. Om avmarkerad anger PointData absoluta positioner i koordinatrymden med 32-bitars flyttalskoordinater.

Värde: `true` om denna instans är komprimerad; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### isRelative() {#isRelative--}
```
public boolean isRelative()
```


Hämtar eller anger ett värde som indikerar om den här instansen är relativ. Om satt specificerar varje element i PointData en plats i koordinatrymden som är relativ till platsen som anges av föregående element i arrayen. För det första elementet i PointData antas en föregående plats med koordinaterna (0,0). Om avmarkerad anger PointData absoluta positioner enligt C‑flaggan.

Värde: `true` om den här instansen är relativ; annars `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Hämtar eller anger ett värde som indikerar om den här instansen är relativ. Om satt specificerar varje element i PointData en plats i koordinatrymden som är relativ till platsen som anges av föregående element i arrayen. För det första elementet i PointData antas en föregående plats med koordinaterna (0,0). Om avmarkerad anger PointData absoluta positioner enligt C‑flaggan.

Värde: `true` om den här instansen är relativ; annars `false`.

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

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Hämtar eller anger punktdata En array med Count punkter som definierar polygonens hörn. De två första punkterna i arrayen anger den första sidan av polygonen. Varje ytterligare punkt anger en ny sida, vars hörn inkluderar punkten och föregående punkt. Om den sista punkten och den första punkten inte sammanfaller, anger de den sista sidan av polygonen.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Hämtar eller anger punktdata En array med Count punkter som definierar polygonens hörn. De två första punkterna i arrayen anger den första sidan av polygonen. Varje ytterligare punkt anger en ny sida, vars hörn inkluderar punkten och föregående punkt. Om den sista punkten och den första punkten inte sammanfaller, anger de den sista sidan av polygonen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

