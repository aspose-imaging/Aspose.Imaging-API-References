---
title: "EmfEpsData klass"
type: docs
weight: 50
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.objects/emfepsdata/
---

**Summary:** The EpsData object is a container for EPS data

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfEpsData

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfEpsData()](#EmfEpsData__1) | Initierar en ny instans av EmfEpsData‑klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| points | [EmfPoint28To4[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpoint28to4/) | r/w | Hämtar eller anger en array med tre Point28_4‑objekt (avsnitt 2.2.23) som definierar <br/>            koordinaterna för utdata‑parallellogrammet med 28,4‑bits FIX‑notation. |
| post_script_data | System.Byte | r/w | Hämtar eller anger en bytearray med PostScript-data. Längden på denna array kan <br/>            beräknas från SizeData-fältet. Dessa data KAN användas för att rendera en bild. |
| size_data | int | r/w | Hämtar eller anger ett 32‑bit osignerat heltal som specificerar den totala storleken på detta objekt, i byte |
| version | int | r/w | Hämtar eller anger ett 32‑bit osignerat heltal som specificerar PostScript-språknivån. Detta <br/>            värde MÅSTE vara 0x00000001 |


### Constructor: EmfEpsData() {#EmfEpsData__1}


```
 EmfEpsData() 
```

Initierar en ny instans av EmfEpsData‑klassen

