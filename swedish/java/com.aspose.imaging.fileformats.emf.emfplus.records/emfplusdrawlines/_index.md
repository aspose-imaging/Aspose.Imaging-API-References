---
title: "EmfPlusDrawLines"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusDrawlLines-posten specificerar ritning av en serie sammanhängande linjer."
type: docs
weight: 24
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawLines extends EmfPlusDrawingRecordType
```

EmfPlusDrawlLines-posten specificerar ritning av en serie sammanhängande linjer.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusDrawLines(EmfPlusRecord source)](#EmfPlusDrawLines-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusDrawLines`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getObjectId()](#getObjectId--) | Hämtar eller anger objektidentifieraren. |
| [setObjectId(byte value)](#setObjectId-byte-) | Hämtar eller anger objektidentifieraren. |
| [getCompressed()](#getCompressed--) | Hämtar eller anger ett värde som indikerar om denna `EmfPlusDrawClosedCurve` är komprimerad. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Hämtar eller anger ett värde som indikerar om denna `EmfPlusDrawClosedCurve` är komprimerad. |
| [getRelative()](#getRelative--) | Hämtar eller anger ett värde som indikerar om denna `EmfPlusDrawClosedCurve` är relativ. |
| [setRelative(boolean value)](#setRelative-boolean-) | Hämtar eller anger ett värde som indikerar om denna `EmfPlusDrawClosedCurve` är relativ. |
| [getClosedShape()](#getClosedShape--) | Hämtar eller anger ett värde som indikerar om [closed shape]. |
| [setClosedShape(boolean value)](#setClosedShape-boolean-) | Hämtar eller anger ett värde som indikerar om [closed shape]. |
| [getPointData()](#getPointData--) | Hämtar eller anger punktdata En array av Count‑punkter som specificerar start- och slutpunkterna för linjerna som ska ritas. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Hämtar eller anger punktdata En array av Count‑punkter som specificerar start- och slutpunkterna för linjerna som ska ritas. |
### EmfPlusDrawLines(EmfPlusRecord source) {#EmfPlusDrawLines-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawLines(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusDrawLines`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Hämtar eller anger objektidentifieraren. Indexet för ett EmfPlusPen‑objekt (avsnitt 2.2.1.7) i EMF+‑objektbordet för att rita linjerna. Värdet MÅSTE vara mellan 0 och 63, inklusive.

Värde: Objektidentifieraren.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Hämtar eller anger objektidentifieraren. Indexet för ett EmfPlusPen‑objekt (avsnitt 2.2.1.7) i EMF+‑objektbordet för att rita linjerna. Värdet MÅSTE vara mellan 0 och 63, inklusive.

Värde: Objektidentifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Hämtar eller anger ett värde som indikerar om detta `EmfPlusDrawClosedCurve` är komprimerat. Denna bit indikerar om PointData‑fältet specificerar komprimerad data. Om den är satt specificerar PointData absoluta positioner i koordinatrymden med 16‑bitars heltalskoordinater. Om den är rensad specificerar PointData absoluta positioner i koordinatrymden med 32‑bitars flyttalskoordinater. Obs! Om Relative‑flaggan (nedan) är satt är denna flagga odefinierad och MÅSTE ignoreras

Värde: `true` om komprimerad; annars `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta `EmfPlusDrawClosedCurve` är komprimerat. Denna bit indikerar om PointData‑fältet specificerar komprimerad data. Om den är satt specificerar PointData absoluta positioner i koordinatrymden med 16‑bitars heltalskoordinater. Om den är rensad specificerar PointData absoluta positioner i koordinatrymden med 32‑bitars flyttalskoordinater. Obs! Om Relative‑flaggan (nedan) är satt är denna flagga odefinierad och MÅSTE ignoreras

Värde: `true` om komprimerad; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Hämtar eller anger ett värde som indikerar om detta `EmfPlusDrawClosedCurve` är relativt. Denna bit indikerar om PointData‑fältet specificerar relativa eller absoluta positioner. Om den är satt specificerar varje element i PointData en position i koordinatrymmen som är relativ till positionen som specificerats av föregående element i arrayen. För det första elementet i PointData antas en föregående position med koordinaterna (0,0). Om den är rensad specificerar PointData absoluta positioner enligt C‑flaggan. Obs! Om denna flagga är satt är Compressed‑flaggan (ovan) odefinierad och MÅSTE ignoreras

Värde: `true` om relativ; annars `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta `EmfPlusDrawClosedCurve` är relativt. Denna bit indikerar om PointData‑fältet specificerar relativa eller absoluta positioner. Om den är satt specificerar varje element i PointData en position i koordinatrymmen som är relativ till positionen som specificerats av föregående element i arrayen. För det första elementet i PointData antas en föregående position med koordinaterna (0,0). Om den är rensad specificerar PointData absoluta positioner enligt C‑flaggan. Obs! Om denna flagga är satt är Compressed‑flaggan (ovan) odefinierad och MÅSTE ignoreras

Värde: `true` om relativ; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getClosedShape() {#getClosedShape--}
```
public boolean getClosedShape()
```


Hämtar eller anger ett värde som indikerar om [closed shape].

Värde: `true` om [closed shape]; annars `false`.

**Returns:**
boolean
### setClosedShape(boolean value) {#setClosedShape-boolean-}
```
public void setClosedShape(boolean value)
```


Hämtar eller anger ett värde som indikerar om [closed shape].

Värde: `true` om [closed shape]; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Hämtar eller anger punktdata En array av Count‑punkter som specificerar start- och slutpunkterna för linjerna som ska ritas.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Hämtar eller anger punktdata En array av Count‑punkter som specificerar start- och slutpunkterna för linjerna som ska ritas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

