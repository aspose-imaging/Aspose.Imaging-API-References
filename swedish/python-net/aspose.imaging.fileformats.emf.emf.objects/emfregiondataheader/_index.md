---
title: "EmfRegionDataHeader klass"
type: docs
weight: 250
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/
---

**Summary:** The RegionDataHeader object describes the properties of a RegionData object.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfRegionDataHeader()](#EmfRegionDataHeader__1) | Initierar en ny instans av klassen EmfRegionDataHeader |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger ett 128-bitars WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19), som specificerar <br/>            regionens gränser. |
| count_rects | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet rektanglar i denna region. |
| rgn_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på bufferten för rektanglar i byte. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på detta objekt i byte. Detta MÅSTE vara 0x00000020. |
| typ | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar regiontypen. Detta BÖR vara <br/>            RDH_RECTANGLES (0x00000001). |


### Constructor: EmfRegionDataHeader() {#EmfRegionDataHeader__1}


```
 EmfRegionDataHeader() 
```

Initierar en ny instans av klassen EmfRegionDataHeader

