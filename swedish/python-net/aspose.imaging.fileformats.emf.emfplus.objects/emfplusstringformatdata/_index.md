---
title: "EmfPlusStringFormatData klass"
type: docs
weight: 660
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/
---

**Summary:** The EmfPlusStringFormatData object specifies tab stops and character positions for a graphics string.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusStringFormatData()](#EmfPlusStringFormatData__1) | Initierar en ny instans av EmfPlusStringFormatData‑klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| char_range | [EmfPlusCharacterRange[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscharacterrange/) | r/w | Hämtar eller anger en valfri array av RangeCount EmfPlusCharacterRange <br/>            objekt som specificerar intervallet av teckenpositioner <br/>            inom en textsträng. Det avgränsande området definieras<br/>            av det displayområde som upptas av en grupp <br/>            tecken specificerade av teckenintervallet.<br/>            Detta fält MUST vara närvarande om värdet för RangeCount<br/>            fältet i EmfPlusStringFormat‑objektet är större än 0. |
| tabb_stopp | float[] | r/w | Hämtar eller anger en valfri array av flyttal som specificerar <br/>            de valfria tabb‑stopp‑positionerna för detta objekt. Varje tabb‑stopp‑värde representerar antalet mellanslag mellan tabb‑stopp eller, för det första tabb‑stoppet, antalet mellanslag mellan början av en textrad och det första tabb‑stoppet. <br/>            Detta fält MUST vara närvarande om värdet för TabStopCount <br/>            fältet i EmpPlusStringFormat‑objektet är större än 0. |


### Constructor: EmfPlusStringFormatData() {#EmfPlusStringFormatData__1}


```
 EmfPlusStringFormatData() 
```

Initierar en ny instans av EmfPlusStringFormatData‑klassen

