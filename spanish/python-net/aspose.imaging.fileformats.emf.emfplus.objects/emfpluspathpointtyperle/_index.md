---
title: "EmfPlusPathPointTypeRle Clase"
type: docs
weight: 530
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---

**Summary:** The EmfPlusPathPointTypeRle object specifies type values associated with points on a graphics path using RLE compression.<br/>             0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1<br/>             B|1|RunCount   | PointType       |<br/>            B (1 bit): If set, the path points are on a Bezier curve.<br/>            If clear, the path points are on a graphics line.<br/>            RunCount (6 bits): The run count, which is the number of path points to be associated with the type in the PointType field.<br/>            PointType (1 byte): An EmfPlusPathPointType object (section 2.2.2.31) that specifies the type to associate with the path points.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointTypeRle

**Inheritance:** EmfPlusBasePointType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusPathPointTypeRle()](#EmfPlusPathPointTypeRle__1) | Inicializa una nueva instancia de la clase EmfPlusPathPointTypeRle |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bezier | bool | r/w | Obtiene o establece un valor que indica si este [EmfPlusPathPointTypeRle](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/) es bezier.<br/>            Si está establecido, los puntos de la ruta están en una curva Bezier.<br/>            Si está despejado, los puntos de la ruta están en una línea gráfica. |
| datos | int | r/w | Obtiene o establece los datos. |
| point_type | [EmfPlusPathPointType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype/) | r/w | Obtiene o establece el tipo del punto.<br/>            PointType (1 byte): Un objeto EmfPlusPathPointType<br/>            (section 2.2.2.31) que especifica el tipo a asociar con los puntos de la ruta. |
| run_count | System.Byte | r/w | Obtiene o establece el recuento de ejecución.<br/>            RunCount (6 bits): El recuento de ejecución, que es el número de puntos de ruta <br/>            que se asociarán con el tipo en el campo PointType. |


### Constructor: EmfPlusPathPointTypeRle() {#EmfPlusPathPointTypeRle__1}


```
 EmfPlusPathPointTypeRle() 
```

Inicializa una nueva instancia de la clase EmfPlusPathPointTypeRle

