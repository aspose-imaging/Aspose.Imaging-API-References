---
title: "EmfPlusDrawArc-klass"
type: docs
weight: 70
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---

**Summary:** The EmfPlusDrawArc record specifies drawing the arc of an ellipse.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawArc

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawArc(source)](#EmfPlusDrawArc_source_1) | Initierar en ny instans av klassen [EmfPlusDrawArc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Hämtar eller anger storleken på data.<br/> Ett 32-bitars osignerat heltal som specificerar det 32-bitars justerade antalet<br/> byte av recordspecifik data som följer.<br/> För denna rekordtyp måste värdet vara ett av följande:<br/> 0x00000010 Om C‑biten är satt i Flag-fältet.<br/> 0x00000018 Om C‑biten är rensad i Flag-fältet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| object_id | System.Byte | r/w | Hämtar eller anger objektidentifieraren.<br/> Indexet för ett EmfPlusPen-objekt (avsnitt 2.2.1.7) i EMF+‑objektabellen för att rita bågen. Värdet MÅSTE vara mellan 0 och 63, inklusive. |
| rect_float | bool | r/w | Hämtar eller anger ett värde som indikerar om data innehåller <br/> EmfPlusRectF- eller EmfPlusRect-poster<br/> Denna bit visar om data i RectData‑fältet är komprimerad.<br/> Om satt innehåller RectData ett EmfPlusRect‑objekt (avsnitt 2.2.2.38).<br/> Om rensad innehåller RectData ett EmfPlusRectF‑objekt (avsnitt 2.2.2.39). |
| rectangle_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Hämtar eller anger rektangeldata<br/> Antingen ett EmfPlusRect- eller EmfPlusRectF‑objekt som definierar den omgivande rutan<br/> för ellipsen som är kollinear med bågen. Denna rektangel definierar<br/> position, storlek och form på bågen. Objektets typ i detta fält anges<br/> av värdet i Flag‑fältet. |
| storlek | int | r/w | Hämtar eller anger storleken.<br/> Ett 32-bitars osignerat heltal som specificerar det 32-bitars justerade antalet<br/> byte i hela rekordet, inklusive 12‑byte rekordhuvudet och<br/> recordspecifik data. För denna rekordtyp måste värdet vara ett av följande:<br/> 0x0000001C Om C‑biten är satt i Flag‑fältet.<br/> 0x00000024 Om C‑biten är rensad i Flag‑fältet. |
| start_angle | float | r/w | Hämtar eller anger startvinkeln<br/> Ett 32-bitars icke‑negativt flyttal som specificerar vinkeln mellan<br/> x‑axeln och startpunkten för bågen. Alla värden är tillåtna,<br/> men det MÅSTE tolkas modulo 360, där resultatet används i intervallet<br/> 0,0 inklusive till 360,0 exklusive. |
| sweep_angle | float | r/w | Hämtar eller anger svepvinkeln<br/> Ett 32-bitars flyttal som specificerar omfattningen av den båg som ska ritas,<br/> som en vinkel i grader mätt från startpunkten definierad av<br/> StartAngle‑värdet. Alla värden är tillåtna, men det MÅSTE begränsas till -360,0<br/> till 360,0 inklusive. Ett positivt värde indikerar att svepet definieras i<br/> medurs riktning, och ett negativt värde indikerar att svepet definieras i<br/> moturs riktning. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusDrawArc(source) {#EmfPlusDrawArc_source_1}


```
 EmfPlusDrawArc(source) 
```

Initierar en ny instans av klassen [EmfPlusDrawArc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

