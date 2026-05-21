---
title: "EmfPlusDrawCurve"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusDrawCurve-posten specificerar ritning av en kardinal spline OBS ObjectID 1 byte Index för ett EmfPlusPen-objekt avsnitt 2.2.1.7 i EMF-objektabellen för att rita kurvan."
type: docs
weight: 19
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawCurve extends EmfPlusDrawingRecordType
```

EmfPlusDrawCurve-posten specificerar ritning av en kardinal spline OBS: ObjectID (1 byte): Index för ett EmfPlusPen-objekt (avsnitt 2.2.1.7) i EMF+-objektabellen för att rita kurvan. Värdet MÅSTE vara 0 till 63, inklusive.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusDrawCurve(EmfPlusRecord source)](#EmfPlusDrawCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusDrawCurve`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCompressed()](#getCompressed--) | Hämtar eller anger ett värde som indikerar om denna `EmfPlusDrawClosedCurve` är komprimerad. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Hämtar eller anger ett värde som indikerar om denna `EmfPlusDrawClosedCurve` är komprimerad. |
| [getObjectId()](#getObjectId--) | Hämtar eller anger objektidentifieraren. |
| [setObjectId(byte value)](#setObjectId-byte-) | Hämtar eller anger objektidentifieraren. |
| [getTension()](#getTension--) | Hämtar eller anger spänningen, ett 32‑bitars flyttal som specificerar hur hårt splinen böjer sig när den passerar genom punkterna. |
| [setTension(float value)](#setTension-float-) | Hämtar eller anger spänningen, ett 32‑bitars flyttal som specificerar hur hårt splinen böjer sig när den passerar genom punkterna. |
| [getNumSegments()](#getNumSegments--) | Hämtar eller anger segmentantalet En 32-bit osignerad heltal som specificerar antalet linjesegment som utgör spline:n. |
| [setNumSegments(int value)](#setNumSegments-int-) | Hämtar eller anger segmentantalet En 32-bit osignerad heltal som specificerar antalet linjesegment som utgör spline:n. |
| [getPointData()](#getPointData--) | Hämtar eller anger en array av antingen 32-bitars signerade heltal eller 32-bitars flyttal med längden Count som definierar koordinatvärden för ändpunkterna på linjerna som ska ritas. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Hämtar eller anger en array av antingen 32-bitars signerade heltal eller 32-bitars flyttal med längden Count som definierar koordinatvärden för ändpunkterna på linjerna som ska ritas. |
### EmfPlusDrawCurve(EmfPlusRecord source) {#EmfPlusDrawCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawCurve(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusDrawCurve`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

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

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Hämtar eller anger objektidentifieraren. Index för ett EmfPlusPen-objekt (avsnitt 2.2.1.7) i EMF+-objektabellen för att rita kurvan. Värdet MÅSTE vara 0 till 63, inklusive.

Värde: Objektidentifieraren.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Hämtar eller anger objektidentifieraren. Index för ett EmfPlusPen-objekt (avsnitt 2.2.1.7) i EMF+-objektabellen för att rita kurvan. Värdet MÅSTE vara 0 till 63, inklusive.

Värde: Objektidentifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getTension() {#getTension--}
```
public float getTension()
```


Hämtar eller anger spänningen. Ett 32‑bitars flyttal som anger hur kraftigt splinen böjer sig när den passerar genom punkterna. Ett värde på 0 anger att splinen är en sekvens av raka linjer. När värdet ökar blir kurvan mer rundad. För mer information, se [SPLINE77] och [PETZOLD].

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Hämtar eller anger spänningen. Ett 32‑bitars flyttal som anger hur kraftigt splinen böjer sig när den passerar genom punkterna. Ett värde på 0 anger att splinen är en sekvens av raka linjer. När värdet ökar blir kurvan mer rundad. För mer information, se [SPLINE77] och [PETZOLD].

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getNumSegments() {#getNumSegments--}
```
public int getNumSegments()
```


Hämtar eller anger segmentantalet En 32-bit osignerad heltal som specificerar antalet linjesegment som utgör spline:n.

**Returns:**
int
### setNumSegments(int value) {#setNumSegments-int-}
```
public void setNumSegments(int value)
```


Hämtar eller anger segmentantalet En 32-bit osignerad heltal som specificerar antalet linjesegment som utgör spline:n.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Hämtar eller anger en array av antingen 32-bitars signerade heltal eller 32-bitars flyttal med längden Count som definierar koordinatvärden för ändpunkterna på linjerna som ska ritas.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Hämtar eller anger en array av antingen 32-bitars signerade heltal eller 32-bitars flyttal med längden Count som definierar koordinatvärden för ändpunkterna på linjerna som ska ritas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

