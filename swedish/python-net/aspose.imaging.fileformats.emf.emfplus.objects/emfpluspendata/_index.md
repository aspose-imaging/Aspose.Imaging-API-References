---
title: "EmfPlusPenData-klass"
type: docs
weight: 550
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/
---

**Summary:** The EmfPlusPenData object specifies properties of a graphics pen.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusPenData()](#EmfPlusPenData__1) | Initierar en ny instans av klassen EmfPlusPenData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| optional_data | [EmfPlusPenOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/) | r/w | Hämtar eller anger ett valfritt EmfPlusPenOptionalData-objekt (avsnitt 2.2.2.34) <br/>            som specificerar ytterligare data för pennobjektet. Det specifika <br/>            innehållet i detta fält bestäms av värdet i <br/>            PenDataFlags-fältet. |
| pen_data_flags | [EmfPlusPenDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspendataflags/) | r/w | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar data i <br/>            OptionalData-fältet. Detta värde MÅSTE bestå av PenData-<br/>            flaggor (avsnitt 2.1.2.7). |
| pen_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar mätenheterna <br/>            för pennan. Värdet MÅSTE vara från UnitType‑enumerationen <br/>            (avsnitt 2.1.1.33). |
| pen_width | float | r/w | Hämtar eller anger ett 32‑bitars flyttal som specificerar bredden på <br/>            linjen som pennan ritar i de enheter som anges av PenUnit-<br/>            fältet. Om en bredd på noll anges används ett minimivärde, <br/>            vilket bestäms av enheterna. |


### Constructor: EmfPlusPenData() {#EmfPlusPenData__1}


```
 EmfPlusPenData() 
```

Initierar en ny instans av klassen EmfPlusPenData

