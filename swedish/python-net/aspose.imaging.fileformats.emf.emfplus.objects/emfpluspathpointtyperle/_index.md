---
title: "EmfPlusPathPointTypeRle-klass"
type: docs
weight: 530
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---

**Summary:** The EmfPlusPathPointTypeRle object specifies type values associated with points on a graphics path using RLE compression.<br/>             0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1<br/>             B|1|RunCount   | PointType       |<br/>            B (1 bit): If set, the path points are on a Bezier curve.<br/>            If clear, the path points are on a graphics line.<br/>            RunCount (6 bits): The run count, which is the number of path points to be associated with the type in the PointType field.<br/>            PointType (1 byte): An EmfPlusPathPointType object (section 2.2.2.31) that specifies the type to associate with the path points.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointTypeRle

**Inheritance:** EmfPlusBasePointType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusPathPointTypeRle()](#EmfPlusPathPointTypeRle__1) | Initierar en ny instans av EmfPlusPathPointTypeRle-klass |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bezier | bool | r/w | Hämtar eller anger ett värde som indikerar om denna [EmfPlusPathPointTypeRle](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/) är en Bézier.<br/>            Om satt, ligger banpunkterna på en Bézier-kurva.<br/>            Om rensad, ligger banpunkterna på en grafiklinje. |
| data | int | r/w | Hämtar eller anger data. |
| point_type | [EmfPlusPathPointType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype/) | r/w | Hämtar eller anger typen av punkten.<br/>            PointType (1 byte): Ett EmfPlusPathPointType-objekt<br/>            (avsnitt 2.2.2.31) som specificerar typen att associera med banpunkterna. |
| run_count | System.Byte | r/w | Hämtar eller anger körantalet.<br/>            RunCount (6 bit): Körantalet, vilket är antalet ban <br/>            punkter som ska associeras med typen i PointType-fältet. |


### Constructor: EmfPlusPathPointTypeRle() {#EmfPlusPathPointTypeRle__1}


```
 EmfPlusPathPointTypeRle() 
```

Initierar en ny instans av EmfPlusPathPointTypeRle-klass

