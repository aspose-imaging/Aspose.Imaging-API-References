---
title: "Classe EmfPlusPathPointTypeRle"
type: docs
weight: 530
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---

**Summary:** The EmfPlusPathPointTypeRle object specifies type values associated with points on a graphics path using RLE compression.<br/>             0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1<br/>             B|1|RunCount   | PointType       |<br/>            B (1 bit): If set, the path points are on a Bezier curve.<br/>            If clear, the path points are on a graphics line.<br/>            RunCount (6 bits): The run count, which is the number of path points to be associated with the type in the PointType field.<br/>            PointType (1 byte): An EmfPlusPathPointType object (section 2.2.2.31) that specifies the type to associate with the path points.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointTypeRle

**Inheritance:** EmfPlusBasePointType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusPathPointTypeRle()](#EmfPlusPathPointTypeRle__1) | Initialise une nouvelle instance de la classe EmfPlusPathPointTypeRle |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bezier | bool | r/w | Obtient ou définit une valeur indiquant si ce [EmfPlusPathPointTypeRle](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/) est une courbe de Bézier.<br/>            Si défini, les points du chemin sont sur une courbe de Bézier.<br/>            Si non défini, les points du chemin sont sur une ligne graphique. |
| données | int | r/w | Obtient ou définit les données. |
| point_type | [EmfPlusPathPointType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype/) | r/w | Obtient ou définit le type du point.<br/>            PointType (1 octet) : un objet EmfPlusPathPointType<br/>            (section 2.2.2.31) qui spécifie le type à associer aux points du chemin. |
| run_count | System.Byte | r/w | Obtient ou définit le nombre d'exécutions.<br/>            RunCount (6 bits) : le nombre d'exécutions, qui correspond au nombre de points du chemin <br/>            à associer au type dans le champ PointType. |


### Constructor: EmfPlusPathPointTypeRle() {#EmfPlusPathPointTypeRle__1}


```
 EmfPlusPathPointTypeRle() 
```

Initialise une nouvelle instance de la classe EmfPlusPathPointTypeRle

