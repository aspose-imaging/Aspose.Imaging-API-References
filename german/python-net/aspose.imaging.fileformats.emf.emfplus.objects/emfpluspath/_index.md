---
title: "EmfPlusPath Klasse"
type: docs
weight: 490
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---

**Summary:** The EmfPlusPath object specifies a series of line and curve segments that form a graphics path. The<br/>            order for Bezier data points is the start point, control point 1, control point 2, and end point.For<br/>            more information see[MSDN - DrawBeziers].

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPath

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusPath()](#EmfPlusPath__1) | Initialisiert eine neue Instanz der Klasse EmfPlusPath |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| path_point_flags | [EmfPlusPathPointFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/) | r/w | Liest oder setzt die Anzahl der Pfadpunkte <br/>            Ein 32‑Bit vorzeichenloser Integer, der angibt, wie die Punkte und zugehörigen Punkttypen, die von diesem Objekt definiert werden, zu interpretieren sind. |
| path_point_types | [EmfPlusBasePointType[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype/) | r/w | Liest oder schreibt ein Array, das festlegt, wie die Punkte im Feld PathPoints verwendet werden, um den Pfad zu zeichnen. <br/>            Der Typ der Objekte in diesem Array wird durch das R‑Flag im Feld PathPointFlags angegeben. |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Liest oder schreibt ein Array von Pfadpunkten<br/>            Ein Array von PathPointCount Punkten, die den Pfad festlegen. Der Typ der Objekte in diesem Array wird durch das Feld PathPointFlags wie folgt angegeben:<br/>            Ist das P‑Flag gesetzt, sind die Punkte relative Positionen, die durch EmfPlusPointR‑Objekte (Abschnitt 2.2.2.37) angegeben werden.<br/>            Ist das P‑Flag nicht gesetzt und das C‑Flag gesetzt, sind die Punkte absolute Positionen, die durch EmfPlusPoint‑Objekte (Abschnitt 2.2.2.35) angegeben werden.<br/>            Sind sowohl das P‑Flag als auch das C‑Flag nicht gesetzt, sind die Punkte absolute Positionen, die durch EmfPlusPointF‑Objekte (Abschnitt 2.2.2.36) angegeben werden. |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Liest oder setzt die Version. |


### Constructor: EmfPlusPath() {#EmfPlusPath__1}


```
 EmfPlusPath() 
```

Initialisiert eine neue Instanz der Klasse EmfPlusPath

