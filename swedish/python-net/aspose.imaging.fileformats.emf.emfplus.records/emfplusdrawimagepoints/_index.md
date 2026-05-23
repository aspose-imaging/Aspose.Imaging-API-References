---
title: "EmfPlusDrawImagePoints-klass"
type: docs
weight: 140
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---

**Summary:** The EmfPlusDrawImagePoints record specifies drawing a scaled image inside a parallelogram.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawImagePoints

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawImagePoints(source)](#EmfPlusDrawImagePoints_source_1) | Initierar en ny instans av klassen [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| applying_an_effect | bool | r/w | Hämtar eller anger ett värde som indikerar om [applying an effect].<br/>            Denna bit indikerar att rendering av bilden inkluderar att applicera en effekt.<br/>            Om den är satt måste ett objekt av klassen Effect ha specificerats i en tidigare<br/>            EmfPlusSerializableObject-post (avsnitt 2.3.5.2). |
| komprimerad | bool | r/w | Hämtar eller anger ett värde som indikerar om PointData är komprimerad.<br/>            Denna bit indikerar om PointData-fältet specificerar komprimerad data.<br/>            Om den är satt specificerar PointData absoluta positioner i koordinatrymden med 16‑bitars heltal<br/>            koordinater. Om den är rensad specificerar PointData absoluta positioner i koordinatrymden med<br/>            32‑bitars flyttalskoordinater.<br/>            Obs! Om P‑flaggan (nedan) är satt är denna flagga odefinierad och MÅSTE ignoreras. |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| image_attributes_id | int | r/w | Hämtar eller anger ett 32‑bitars osignerat heltal som innehåller indexet för den<br/>            valfria EmfPlusImageAttributes-objektet (avsnitt 2.2.1.5) i EMF+ Object Table. |
| object_id | System.Byte | r/w | Hämtar eller anger objektidentifieraren.<br/>            Indexet för ett EmfPlusImage-objekt (avsnitt 2.2.1.4) i EMF+<br/>            Object Table, som specificerar bilden som ska renderas. Värdet MÅSTE vara mellan 0 och 63, inklusive. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Hämtar eller anger en array av Count-punkter som specificerar tre punkter i ett parallellogram.<br/>            De tre punkterna representerar övre vänstra, övre högra och nedre vänstra hörnet av<br/>            parallellogrammet. Den fjärde punkten i parallellogrammet extrapoleras från de första tre. Den<br/>            del av bilden som specificeras av SrcRect-fältet BÖR ha skalnings- och skevnings‑transformeringar<br/>            tillämpade om nödvändigt för att passa in i parallellogrammet. |
| relative | bool | r/w | Hämtar eller anger ett värde som indikerar om detta [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/) är relativt.<br/>            Denna bit indikerar om PointData-fältet specificerar relativa eller absoluta positioner.<br/>            Om den är satt specificerar varje element i PointData en position i koordinatrymden som är<br/>            relativ till positionen som specificerats av föregående element i arrayen. I fallet med det<br/>            första elementet i PointData antas en föregående position med koordinaterna (0,0). Om den är rensad,<br/>            specificerar PointData absoluta positioner enligt C‑flaggan.<br/>            Obs! Om denna flagga är satt är C‑flaggan (ovan) odefinierad och MÅSTE ignoreras. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Hämtar eller anger ett EmfPlusRectF-objekt (avsnitt 2.2.2.39) som definierar en del av bilden som ska renderas. |
| src_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Hämtar eller anger ett 32‑bitars signerat heltal som definierar enheterna för SrcRect-fältet. Det MÅSTE<br/>            vara värdet UnitPixel i UnitType‑uppräkningen (avsnitt 2.1.1.33). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusDrawImagePoints(source) {#EmfPlusDrawImagePoints_source_1}


```
 EmfPlusDrawImagePoints(source) 
```

Initierar en ny instans av klassen [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/) class.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

