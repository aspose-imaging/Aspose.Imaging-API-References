---
title: "EmfPlusPathPointTypeRle Klasse"
type: docs
weight: 530
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---

**Summary:** The EmfPlusPathPointTypeRle object specifies type values associated with points on a graphics path using RLE compression.<br/>             0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1<br/>             B|1|RunCount   | PointType       |<br/>            B (1 bit): If set, the path points are on a Bezier curve.<br/>            If clear, the path points are on a graphics line.<br/>            RunCount (6 bits): The run count, which is the number of path points to be associated with the type in the PointType field.<br/>            PointType (1 byte): An EmfPlusPathPointType object (section 2.2.2.31) that specifies the type to associate with the path points.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointTypeRle

**Inheritance:** EmfPlusBasePointType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusPathPointTypeRle()](#EmfPlusPathPointTypeRle__1) | Initialisiert eine neue Instanz der EmfPlusPathPointTypeRle Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bezier | bool | r/w | Liest oder setzt einen Wert, der angibt, ob dieses [EmfPlusPathPointTypeRle](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/) ein Bezier ist.<br/>            Wenn gesetzt, liegen die Pfadpunkte auf einer Bézierkurve.<br/>            Wenn nicht gesetzt, liegen die Pfadpunkte auf einer Grafiklinie. |
| Daten | int | r/w | Liest oder setzt die Daten. |
| point_type | [EmfPlusPathPointType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype/) | r/w | Liest oder setzt den Typ des Punktes.<br/>            PointType (1 Byte): Ein EmfPlusPathPointType-Objekt<br/>            (Abschnitt 2.2.2.31) das den Typ angibt, der den Pfadpunkten zugeordnet werden soll. |
| run_count | System.Byte | r/w | Liest oder setzt die Laufanzahl.<br/>            RunCount (6 Bits): Die Laufanzahl, die die Anzahl der Pfad <br/>            Punkte angibt, die dem Typ im PointType-Feld zugeordnet werden. |


### Constructor: EmfPlusPathPointTypeRle() {#EmfPlusPathPointTypeRle__1}


```
 EmfPlusPathPointTypeRle() 
```

Initialisiert eine neue Instanz der EmfPlusPathPointTypeRle Klasse

