---
title: "EmfPlusFillPie"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusFillPie-posten specificerar fyllning av ett avsnitt av insidan av en ellips."
type: docs
weight: 35
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPie extends EmfPlusDrawingRecordType
```

EmfPlusFillPie-posten specificerar fyllning av ett avsnitt av insidan av en ellips.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusFillPie(EmfPlusRecord source)](#EmfPlusFillPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusFillPie`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCompressed()](#getCompressed--) | Hämtar eller anger ett värde som indikerar om PointData är komprimerad. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Hämtar eller anger ett värde som indikerar om PointData är komprimerad. |
| [isColor()](#isColor--) | Hämtar eller anger ett värde som indikerar om denna instans är färg. |
| [setColor(boolean value)](#setColor-boolean-) | Hämtar eller anger ett värde som indikerar om denna instans är färg. |
| [getStartAngle()](#getStartAngle--) | Hämtar eller anger startvinkeln. Ett 32‑bitars, icke‑negativt flyttal som specificerar vinkeln mellan x‑axeln och startpunkten för pajbiten. |
| [setStartAngle(float value)](#setStartAngle-float-) | Hämtar eller anger startvinkeln. Ett 32‑bitars, icke‑negativt flyttal som specificerar vinkeln mellan x‑axeln och startpunkten för pajbiten. |
| [getSweepAngle()](#getSweepAngle--) | Hämtar eller anger svepvinkeln. Ett 32‑bitars flyttal som specificerar omfattningen av den båge som definierar den pajbit som ska ritas, som en vinkel i grader mätt från startpunkten som definieras av StartAngle‑värdet. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Hämtar eller anger svepvinkeln. Ett 32‑bitars flyttal som specificerar omfattningen av den båge som definierar den pajbit som ska ritas, som en vinkel i grader mätt från startpunkten som definieras av StartAngle‑värdet. |
| [getRectData()](#getRectData--) | Hämtar eller anger rektangeldata. Antingen ett EmfPlusRect‑ eller EmfPlusRectF‑objekt som definierar den omgivande lådan för ellipsen som innehåller pajbiten. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Hämtar eller anger rektangeldata. Antingen ett EmfPlusRect‑ eller EmfPlusRectF‑objekt som definierar den omgivande lådan för ellipsen som innehåller pajbiten. |
| [getBrushId()](#getBrushId--) | Hämtar eller anger borstidentifieraren Ett 32-bitars osignerat heltal som definierar borsten, vars innehåll bestäms av S‑biten i Flag‑fältet. |
| [setBrushId(int value)](#setBrushId-int-) | Hämtar eller anger borstidentifieraren Ett 32-bitars osignerat heltal som definierar borsten, vars innehåll bestäms av S‑biten i Flag‑fältet. |
### EmfPlusFillPie(EmfPlusRecord source) {#EmfPlusFillPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPie(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusFillPie`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Hämtar eller anger ett värde som indikerar om PointData är komprimerad. Om satt innehåller RectData ett EmfPlusRect‑objekt (avsnitt 2.2.2.38). Om rensad innehåller RectData ett EmfPlusRectF‑objekt (avsnitt 2.2.2.39).

Värde: `true` om komprimerad; annars `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Hämtar eller anger ett värde som indikerar om PointData är komprimerad. Om satt innehåller RectData ett EmfPlusRect‑objekt (avsnitt 2.2.2.38). Om rensad innehåller RectData ett EmfPlusRectF‑objekt (avsnitt 2.2.2.39).

Värde: `true` om komprimerad; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Hämtar eller anger startvinkeln. Ett 32‑bitars, icke‑negativt flyttal som specificerar vinkeln mellan x‑axeln och startpunkten för pajbiten. Alla värden är tillåtna, men det MÅSTE tolkas modulo 360, så att resultatet ligger i intervallet 0,0 inklusive till 360,0 exklusive.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Hämtar eller anger startvinkeln. Ett 32‑bitars, icke‑negativt flyttal som specificerar vinkeln mellan x‑axeln och startpunkten för pajbiten. Alla värden är tillåtna, men det MÅSTE tolkas modulo 360, så att resultatet ligger i intervallet 0,0 inklusive till 360,0 exklusive.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Hämtar eller anger svepvinkeln. Ett 32‑bitars flyttal som specificerar omfattningen av den båge som definierar den pajbit som ska ritas, som en vinkel i grader mätt från startpunkten som definieras av StartAngle‑värdet. Alla värden är tillåtna, men det MÅSTE begränsas till -360,0 till 360,0 inklusive. Ett positivt värde indikerar att svepet definieras i medurs riktning, och ett negativt värde indikerar att svepet definieras i moturs riktning.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Hämtar eller anger svepvinkeln. Ett 32‑bitars flyttal som specificerar omfattningen av den båge som definierar den pajbit som ska ritas, som en vinkel i grader mätt från startpunkten som definieras av StartAngle‑värdet. Alla värden är tillåtna, men det MÅSTE begränsas till -360,0 till 360,0 inklusive. Ett positivt värde indikerar att svepet definieras i medurs riktning, och ett negativt värde indikerar att svepet definieras i moturs riktning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Hämtar eller anger rektangeldata. Antingen ett EmfPlusRect‑ eller EmfPlusRectF‑objekt som definierar den omgivande lådan för ellipsen som innehåller pajbiten. Denna rektangel definierar positionen, storleken och formen på pajen. Objektets typ i detta fält anges av värdet i Flags‑fältet.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Hämtar eller anger rektangeldata. Antingen ett EmfPlusRect‑ eller EmfPlusRectF‑objekt som definierar den omgivande lådan för ellipsen som innehåller pajbiten. Denna rektangel definierar positionen, storleken och formen på pajen. Objektets typ i detta fält anges av värdet i Flags‑fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

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

