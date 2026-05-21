---
title: "EmfPlusDrawClosedCurve"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusDrawClosedCurve-posten specificerar ritning av en sluten kardinal spline."
type: docs
weight: 18
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawClosedCurve extends EmfPlusDrawingRecordType
```

EmfPlusDrawClosedCurve-posten specificerar ritning av en sluten kardinal spline.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusDrawClosedCurve(EmfPlusRecord source)](#EmfPlusDrawClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusDrawClosedCurve`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getObjectId()](#getObjectId--) | Hämtar eller anger objektidentifieraren. |
| [setObjectId(byte value)](#setObjectId-byte-) | Hämtar eller anger objektidentifieraren. |
| [getCompressed()](#getCompressed--) | Hämtar eller anger ett värde som indikerar om denna `EmfPlusDrawClosedCurve` är komprimerad. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Hämtar eller anger ett värde som indikerar om denna `EmfPlusDrawClosedCurve` är komprimerad. |
| [getRelative()](#getRelative--) | Hämtar eller anger ett värde som indikerar om denna `EmfPlusDrawClosedCurve` är relativ. |
| [setRelative(boolean value)](#setRelative-boolean-) | Hämtar eller anger ett värde som indikerar om denna `EmfPlusDrawClosedCurve` är relativ. |
| [getTension()](#getTension--) | Hämtar eller anger spänningen, ett 32‑bitars flyttal som specificerar hur hårt splinen böjer sig när den passerar genom punkterna. |
| [setTension(float value)](#setTension-float-) | Hämtar eller anger spänningen, ett 32‑bitars flyttal som specificerar hur hårt splinen böjer sig när den passerar genom punkterna. |
| [getPointData()](#getPointData--) | Hämtar eller anger punktdata En array av Count‑punkter som specificerar ändpunkterna för linjerna som definierar splinen. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Hämtar eller anger punktdata En array av Count‑punkter som specificerar ändpunkterna för linjerna som definierar splinen. |
### EmfPlusDrawClosedCurve(EmfPlusRecord source) {#EmfPlusDrawClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawClosedCurve(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusDrawClosedCurve`. RecordType – ett 16‑bitars osignerat heltal som identifierar denna posttyp som EmfPlusDrawClosedCurve från uppräkningen RecordType (avsnitt 2.1.1.1). Värdet MÅSTE vara 0x4017.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Hämtar eller anger objektidentifieraren. Indexet för ett EmfPlusPen-objekt (avsnitt 2.2.1.7) i EMF+ Object Table för att rita den slutna kurvan. Värdet MÅSTE vara mellan 0 och 63, inklusive.

Värde: Objektidentifieraren.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Hämtar eller anger objektidentifieraren. Indexet för ett EmfPlusPen-objekt (avsnitt 2.2.1.7) i EMF+ Object Table för att rita den slutna kurvan. Värdet MÅSTE vara mellan 0 och 63, inklusive.

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

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Hämtar eller anger punktdata. En array med Count‑punkter som specificerar ändpunkterna för linjerna som definierar splinen. I en sluten kardinal‑spline fortsätter kurvan genom den sista punkten i PointData‑arrayen och ansluter till den första punkten i arrayen. Datatypen i denna array anges av Flags‑fältet, enligt följande: Datatyp Betydelse EmfPlusPointR‑objekt (avsnitt 2.2.2.37) Om P‑flaggan är satt i Flags, anger punkterna relativa positioner. EmfPlusPointF‑objekt (avsnitt 2.2.2.36) Om P‑ och C‑bitarna är satta i Flags‑fältet, anger punkterna absoluta positioner. EmfPlusPoint‑objekt (avsnitt 2.2.2.35) Om P‑biten är rensad och C‑biten är satt i Flags‑fältet, anger punkterna relativa positioner.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Hämtar eller anger punktdata. En array med Count‑punkter som specificerar ändpunkterna för linjerna som definierar splinen. I en sluten kardinal‑spline fortsätter kurvan genom den sista punkten i PointData‑arrayen och ansluter till den första punkten i arrayen. Datatypen i denna array anges av Flags‑fältet, enligt följande: Datatyp Betydelse EmfPlusPointR‑objekt (avsnitt 2.2.2.37) Om P‑flaggan är satt i Flags, anger punkterna relativa positioner. EmfPlusPointF‑objekt (avsnitt 2.2.2.36) Om P‑ och C‑bitarna är satta i Flags‑fältet, anger punkterna absoluta positioner. EmfPlusPoint‑objekt (avsnitt 2.2.2.35) Om P‑biten är rensad och C‑biten är satt i Flags‑fältet, anger punkterna relativa positioner.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

