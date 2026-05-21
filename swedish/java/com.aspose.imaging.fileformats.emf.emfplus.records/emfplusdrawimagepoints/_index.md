---
title: "EmfPlusDrawImagePoints"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusDrawImagePoints-posten specificerar ritning av en skalad bild inuti ett parallellogram."
type: docs
weight: 23
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawImagePoints extends EmfPlusDrawingRecordType
```

EmfPlusDrawImagePoints-posten specificerar ritning av en skalad bild inuti ett parallellogram.

En EmfPlusImage kan ange antingen en bitmap eller en metafil. Färger i en bild kan manipuleras under rendering. De kan korrigeras, mörkas, ljusas och tas bort.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusDrawImagePoints(EmfPlusRecord source)](#EmfPlusDrawImagePoints-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusDrawImagePoints`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCompressed()](#getCompressed--) | Hämtar eller anger ett värde som indikerar om PointData är komprimerad. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Hämtar eller anger ett värde som indikerar om PointData är komprimerad. |
| [getObjectId()](#getObjectId--) | Hämtar eller anger objektidentifieraren. |
| [setObjectId(byte value)](#setObjectId-byte-) | Hämtar eller anger objektidentifieraren. |
| [getApplyingAnEffect()](#getApplyingAnEffect--) | Hämtar eller anger ett värde som indikerar om [applying an effect]. |
| [setApplyingAnEffect(boolean value)](#setApplyingAnEffect-boolean-) | Hämtar eller anger ett värde som indikerar om [applying an effect]. |
| [getRelative()](#getRelative--) | Hämtar eller anger ett värde som indikerar om detta `EmfPlusDrawImagePoints` är relativt. |
| [setRelative(boolean value)](#setRelative-boolean-) | Hämtar eller anger ett värde som indikerar om detta `EmfPlusDrawImagePoints` är relativt. |
| [getImageAttributesId()](#getImageAttributesId--) | Hämtar eller anger ett 32-bitars osignerat heltal som innehåller indexet för det valfria EmfPlusImageAttributes-objektet (sektion 2.2.1.5) i EMF+ Object Table. |
| [setImageAttributesId(int value)](#setImageAttributesId-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som innehåller indexet för det valfria EmfPlusImageAttributes-objektet (sektion 2.2.1.5) i EMF+ Object Table. |
| [getSrcUnit()](#getSrcUnit--) | Hämtar eller anger ett 32-bitars signerat heltal som definierar enheterna för SrcRect-fältet. |
| [setSrcUnit(int value)](#setSrcUnit-int-) | Hämtar eller anger ett 32-bitars signerat heltal som definierar enheterna för SrcRect-fältet. |
| [getSrcRect()](#getSrcRect--) | Hämtar eller anger ett EmfPlusRectF-objekt (sektion 2.2.2.39) som definierar en del av bilden som ska renderas. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | Hämtar eller anger ett EmfPlusRectF-objekt (sektion 2.2.2.39) som definierar en del av bilden som ska renderas. |
| [getPointData()](#getPointData--) | Hämtar eller anger en array av Count-punkter som specificerar tre punkter av ett parallellogram. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Hämtar eller anger en array av Count-punkter som specificerar tre punkter av ett parallellogram. |
### EmfPlusDrawImagePoints(EmfPlusRecord source) {#EmfPlusDrawImagePoints-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawImagePoints(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusDrawImagePoints`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Hämtar eller anger ett värde som indikerar om PointData är komprimerat. Denna bit indikerar om PointData-fältet specificerar komprimerad data. Om den är satt specificerar PointData absoluta positioner i koordinatrymden med 16-bitars heltalskoordinater. Om den är rensad specificerar PointData absoluta positioner i koordinatrymden med 32-bitars flyttalskoordinater. Obs! Om P-flaggan (nedan) är satt är denna flagga odefinierad och MÅSTE ignoreras.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Hämtar eller anger ett värde som indikerar om PointData är komprimerat. Denna bit indikerar om PointData-fältet specificerar komprimerad data. Om den är satt specificerar PointData absoluta positioner i koordinatrymden med 16-bitars heltalskoordinater. Om den är rensad specificerar PointData absoluta positioner i koordinatrymden med 32-bitars flyttalskoordinater. Obs! Om P-flaggan (nedan) är satt är denna flagga odefinierad och MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Hämtar eller anger objektidentifieraren. Indexet för ett EmfPlusImage-objekt (sektion 2.2.1.4) i EMF+ Object Table, som specificerar bilden som ska renderas. Värdet MÅSTE vara mellan 0 och 63, inklusive.

Värde: Objektidentifieraren.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Hämtar eller anger objektidentifieraren. Indexet för ett EmfPlusImage-objekt (sektion 2.2.1.4) i EMF+ Object Table, som specificerar bilden som ska renderas. Värdet MÅSTE vara mellan 0 och 63, inklusive.

Värde: Objektidentifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getApplyingAnEffect() {#getApplyingAnEffect--}
```
public boolean getApplyingAnEffect()
```


Hämtar eller anger ett värde som indikerar om [applying an effect]. Denna bit indikerar att rendering av bilden inkluderar att applicera en effekt. Om den är satt måste ett objekt av klassen Effect ha specificerats i en tidigare EmfPlusSerializableObject-post (avsnitt 2.3.5.2).

Värde: `true` om [applying an effect]; annars `false`.

**Returns:**
boolean
### setApplyingAnEffect(boolean value) {#setApplyingAnEffect-boolean-}
```
public void setApplyingAnEffect(boolean value)
```


Hämtar eller anger ett värde som indikerar om [applying an effect]. Denna bit indikerar att rendering av bilden inkluderar att applicera en effekt. Om den är satt måste ett objekt av klassen Effect ha specificerats i en tidigare EmfPlusSerializableObject-post (avsnitt 2.3.5.2).

Värde: `true` om [applying an effect]; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Hämtar eller anger ett värde som indikerar om detta `EmfPlusDrawImagePoints` är relativt. Denna bit indikerar om fältet PointData specificerar relativa eller absoluta positioner. Om den är satt specificerar varje element i PointData en plats i koordinatrymden som är relativ till platsen som angavs av föregående element i arrayen. För det första elementet i PointData antas en föregående plats med koordinaterna (0,0). Om den är avmarkerad specificerar PointData absoluta positioner enligt C‑flaggan. Obs! Om denna flagga är satt är C‑flaggan (ovan) odefinierad och MÅSTE ignoreras.

Värde: `true` om relativ; annars `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta `EmfPlusDrawImagePoints` är relativt. Denna bit indikerar om fältet PointData specificerar relativa eller absoluta positioner. Om den är satt specificerar varje element i PointData en plats i koordinatrymden som är relativ till platsen som angavs av föregående element i arrayen. För det första elementet i PointData antas en föregående plats med koordinaterna (0,0). Om den är avmarkerad specificerar PointData absoluta positioner enligt C‑flaggan. Obs! Om denna flagga är satt är C‑flaggan (ovan) odefinierad och MÅSTE ignoreras.

Värde: `true` om relativ; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getImageAttributesId() {#getImageAttributesId--}
```
public int getImageAttributesId()
```


Hämtar eller anger ett 32-bitars osignerat heltal som innehåller indexet för det valfria EmfPlusImageAttributes-objektet (sektion 2.2.1.5) i EMF+ Object Table.

Värde: Bildattributens identifierare.

**Returns:**
int
### setImageAttributesId(int value) {#setImageAttributesId-int-}
```
public void setImageAttributesId(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som innehåller indexet för det valfria EmfPlusImageAttributes-objektet (sektion 2.2.1.5) i EMF+ Object Table.

Värde: Bildattributens identifierare.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSrcUnit() {#getSrcUnit--}
```
public int getSrcUnit()
```


Hämtar eller anger ett 32‑bitars signerat heltal som definierar enheterna för SrcRect‑fältet. Det MÅSTE vara värdet UnitPixel i uppräkningen UnitType (avsnitt 2.1.1.33).

Värde: Källenheten.

**Returns:**
int
### setSrcUnit(int value) {#setSrcUnit-int-}
```
public void setSrcUnit(int value)
```


Hämtar eller anger ett 32‑bitars signerat heltal som definierar enheterna för SrcRect‑fältet. Det MÅSTE vara värdet UnitPixel i uppräkningen UnitType (avsnitt 2.1.1.33).

Värde: Källenheten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


Hämtar eller anger ett EmfPlusRectF-objekt (sektion 2.2.2.39) som definierar en del av bilden som ska renderas.

Värde: Källrektangeln.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


Hämtar eller anger ett EmfPlusRectF-objekt (sektion 2.2.2.39) som definierar en del av bilden som ska renderas.

Värde: Källrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Hämtar eller anger en array med Count‑punkter som specificerar tre punkter i ett parallellogram. De tre punkterna representerar det övre vänstra, övre högra och nedre vänstra hörnet av parallellogrammet. Den fjärde punkten i parallellogrammet extrapoleras från de tre första. Den del av bilden som anges av SrcRect‑fältet BÖR ha skalnings‑ och skevningstransformeringar tillämpade om det behövs för att passa in i parallellogrammet.

Värde: Punktdata.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Hämtar eller anger en array med Count‑punkter som specificerar tre punkter i ett parallellogram. De tre punkterna representerar det övre vänstra, övre högra och nedre vänstra hörnet av parallellogrammet. Den fjärde punkten i parallellogrammet extrapoleras från de tre första. Den del av bilden som anges av SrcRect‑fältet BÖR ha skalnings‑ och skevningstransformeringar tillämpade om det behövs för att passa in i parallellogrammet.

Värde: Punktdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

