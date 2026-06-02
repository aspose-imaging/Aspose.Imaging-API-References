---
title: "EmfPlusPathPointTypeRle Classe"
type: docs
weight: 530
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---

**Summary:** The EmfPlusPathPointTypeRle object specifies type values associated with points on a graphics path using RLE compression.<br/>             0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1<br/>             B|1|RunCount   | PointType       |<br/>            B (1 bit): If set, the path points are on a Bezier curve.<br/>            If clear, the path points are on a graphics line.<br/>            RunCount (6 bits): The run count, which is the number of path points to be associated with the type in the PointType field.<br/>            PointType (1 byte): An EmfPlusPathPointType object (section 2.2.2.31) that specifies the type to associate with the path points.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointTypeRle

**Inheritance:** EmfPlusBasePointType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusPathPointTypeRle()](#EmfPlusPathPointTypeRle__1) | Inizializza una nuova istanza della classe EmfPlusPathPointTypeRle |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bezier | bool | r/w | Ottiene o imposta un valore che indica se questo [EmfPlusPathPointTypeRle](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/) è bezier.<br/>            Se impostato, i punti del percorso sono su una curva Bezier.<br/>            Se non impostato, i punti del percorso sono su una linea grafica. |
| dati | int | r/w | Ottiene o imposta i dati. |
| point_type | [EmfPlusPathPointType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype/) | r/w | Ottiene o imposta il tipo del punto.<br/>            PointType (1 byte): Un oggetto EmfPlusPathPointType<br/>            (sezione 2.2.2.31) che specifica il tipo da associare ai punti del percorso. |
| run_count | System.Byte | r/w | Ottiene o imposta il conteggio della sequenza.<br/>            RunCount (6 bit): Il conteggio della sequenza, che è il numero di punti del percorso <br/>            da associare al tipo nel campo PointType. |


### Constructor: EmfPlusPathPointTypeRle() {#EmfPlusPathPointTypeRle__1}


```
 EmfPlusPathPointTypeRle() 
```

Inizializza una nuova istanza della classe EmfPlusPathPointTypeRle

