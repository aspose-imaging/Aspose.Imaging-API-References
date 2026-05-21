---
title: "EmfPlusDrawBeziers"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusDrawBeziers-posten specificerar ritning av en sekvens av sammanhängande Bézier-kurvor."
type: docs
weight: 17
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawBeziers extends EmfPlusDrawingRecordType
```

EmfPlusDrawBeziers‑posten specificerar ritning av en sekvens av sammanhängande Bezier‑kurvor. Ordningen för Bezier‑datapunkter är startpunkt, kontrollpunkt 1, kontrollpunkt 2 och slutpunkt. För mer information, se [MSDN-DrawBeziers].
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusDrawBeziers(EmfPlusRecord source)](#EmfPlusDrawBeziers-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusDrawBeziers`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCompressed()](#getCompressed--) | Hämtar eller anger ett värde som indikerar om PointData är komprimerad. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Hämtar eller anger ett värde som indikerar om PointData är komprimerad. |
| [getRelative()](#getRelative--) | Hämtar eller anger ett värde som indikerar om PointData är relativt. |
| [setRelative(boolean value)](#setRelative-boolean-) | Hämtar eller anger ett värde som indikerar om PointData är relativt. |
| [getObjectId()](#getObjectId--) | Hämtar eller anger objektidentifieraren. |
| [setObjectId(byte value)](#setObjectId-byte-) | Hämtar eller anger objektidentifieraren. |
| [getPointData()](#getPointData--) | Hämtar eller anger punktdata En array med Count‑punkter som specificerar start‑, slut‑ och kontrollpunkterna för Bezier‑kurvorna. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Hämtar eller anger punktdata En array med Count‑punkter som specificerar start‑, slut‑ och kontrollpunkterna för Bezier‑kurvorna. |
### EmfPlusDrawBeziers(EmfPlusRecord source) {#EmfPlusDrawBeziers-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawBeziers(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusDrawBeziers`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Hämtar eller anger ett värde som indikerar om PointData är komprimerad. Om den är satt specificerar PointData absoluta positioner i koordinatrymden med 16‑bitars heltalskoordinater. Om den är avmarkerad specificerar PointData absoluta positioner i koordinatrymden med 32‑bitars flyttalskoordinater. Obs! Om Relative‑flaggan (nedan) är satt är denna flagga odefinierad och MÅSTE ignoreras.

Värde: `true` om komprimerad; annars `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Hämtar eller anger ett värde som indikerar om PointData är komprimerad. Om den är satt specificerar PointData absoluta positioner i koordinatrymden med 16‑bitars heltalskoordinater. Om den är avmarkerad specificerar PointData absoluta positioner i koordinatrymden med 32‑bitars flyttalskoordinater. Obs! Om Relative‑flaggan (nedan) är satt är denna flagga odefinierad och MÅSTE ignoreras.

Värde: `true` om komprimerad; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Hämtar eller anger ett värde som indikerar om PointData är relativt. Om den är satt specificerar varje element i PointData en plats i koordinatrymden som är relativ till platsen som angavs av föregående element i arrayen. För det första elementet i PointData antas en föregående plats med koordinaterna (0,0). Om den är avmarkerad specificerar PointData absoluta positioner enligt C‑flaggan. Obs! Om denna flagga är satt är C‑flaggan (ovan) odefinierad och MÅSTE ignoreras.

Värde: `true` om relativ; annars `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Hämtar eller anger ett värde som indikerar om PointData är relativt. Om den är satt specificerar varje element i PointData en plats i koordinatrymden som är relativ till platsen som angavs av föregående element i arrayen. För det första elementet i PointData antas en föregående plats med koordinaterna (0,0). Om den är avmarkerad specificerar PointData absoluta positioner enligt C‑flaggan. Obs! Om denna flagga är satt är C‑flaggan (ovan) odefinierad och MÅSTE ignoreras.

Värde: `true` om relativ; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Hämtar eller anger objektidentifieraren. Indexet för ett EmfPlusPen‑objekt (avsnitt 2.2.1.7) i EMF+‑objektabellen för att rita Bezier‑kurvorna. Värdet MÅSTE vara mellan 0 och 63, inklusive.

Värde: Objektidentifieraren.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Hämtar eller anger objektidentifieraren. Indexet för ett EmfPlusPen‑objekt (avsnitt 2.2.1.7) i EMF+‑objektabellen för att rita Bezier‑kurvorna. Värdet MÅSTE vara mellan 0 och 63, inklusive.

Värde: Objektidentifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Hämtar eller anger punktdata En array med Count‑punkter som specificerar start‑, slut‑ och kontrollpunkterna för Bezier‑kurvorna. Slutkoordinaten för en Bezier‑kurva är startkoordinaten för nästa. Kontrollpunkterna används för att skapa Bezier‑effekten. Datatypen i denna array specificeras av Flags‑fältet, enligt följande: Datatyp Betydelse EmfPlusPointR‑objekt (avsnitt 2.2.2.37) Om P‑flaggan är satt i Flags, specificerar punkterna relativa positioner. EmfPlusPointF‑objekt (avsnitt 2.2.2.36) Om P‑ och C‑bitarna är avmarkerade i Flags‑fältet, specificerar punkterna absoluta positioner. EmfPlusPoint‑objekt (avsnitt 2.2.2.35) Om P‑bit är avmarkerad och C‑bit är satt i Flags‑fältet, specificerar punkterna relativa positioner. En Bezier‑kurva passerar inte genom sina kontrollpunkter. Kontrollpunkterna fungerar som

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Hämtar eller anger punktdata En array med Count‑punkter som specificerar start‑, slut‑ och kontrollpunkterna för Bezier‑kurvorna. Slutkoordinaten för en Bezier‑kurva är startkoordinaten för nästa. Kontrollpunkterna används för att skapa Bezier‑effekten. Datatypen i denna array specificeras av Flags‑fältet, enligt följande: Datatyp Betydelse EmfPlusPointR‑objekt (avsnitt 2.2.2.37) Om P‑flaggan är satt i Flags, specificerar punkterna relativa positioner. EmfPlusPointF‑objekt (avsnitt 2.2.2.36) Om P‑ och C‑bitarna är avmarkerade i Flags‑fältet, specificerar punkterna absoluta positioner. EmfPlusPoint‑objekt (avsnitt 2.2.2.35) Om P‑bit är avmarkerad och C‑bit är satt i Flags‑fältet, specificerar punkterna relativa positioner. En Bezier‑kurva passerar inte genom sina kontrollpunkter. Kontrollpunkterna fungerar som

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

