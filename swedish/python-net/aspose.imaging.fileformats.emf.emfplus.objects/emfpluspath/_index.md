---
title: "EmfPlusPath-klass"
type: docs
weight: 490
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---

**Summary:** The EmfPlusPath object specifies a series of line and curve segments that form a graphics path. The<br/>            order for Bezier data points is the start point, control point 1, control point 2, and end point.For<br/>            more information see[MSDN - DrawBeziers].

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPath

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusPath()](#EmfPlusPath__1) | Initierar en ny instans av klassen EmfPlusPath |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| path_point_flags | [EmfPlusPathPointFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/) | r/w | Hämtar eller anger antalet Path-punkter <br/>            Ett 32‑bitars osignerat heltal som specificerar hur punkterna och tillhörande punkttyper som definieras av detta objekt ska tolkas. |
| path_point_types | [EmfPlusBasePointType[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype/) | r/w | Hämtar eller anger en array som specificerar hur punkterna i PathPoints-fältet används för att rita vägen. <br/>            Typen av objekt i denna array anges av R-flaggan i PathPointFlags-fältet |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Hämtar eller anger en array av banpunkter<br/>            En array med PathPointCount punkter som specificerar vägen. Typen av objekt i denna array anges av PathPointFlags-fältet, enligt följande:<br/>            Om P-flaggan är satt, är punkterna relativa positioner som specificeras av EmfPlusPointR-objekt (avsnitt 2.2.2.37).<br/>            Om P-flaggan är rensad och C-flaggan är satt, är punkterna absoluta positioner som specificeras av EmfPlusPoint-objekt (avsnitt 2.2.2.35).<br/>            Om både P- och C-flaggan är rensade, är punkterna absoluta positioner som specificeras av EmfPlusPointF-objekt (avsnitt 2.2.2.36). |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Hämtar eller anger versionen. |


### Constructor: EmfPlusPath() {#EmfPlusPath__1}


```
 EmfPlusPath() 
```

Initierar en ny instans av klassen EmfPlusPath

