---
title: "Classe EmfPlusPath"
type: docs
weight: 490
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---

**Summary:** The EmfPlusPath object specifies a series of line and curve segments that form a graphics path. The<br/>            order for Bezier data points is the start point, control point 1, control point 2, and end point.For<br/>            more information see[MSDN - DrawBeziers].

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPath

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusPath()](#EmfPlusPath__1) | Inizializza una nuova istanza della classe EmfPlusPath |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| path_point_flags | [EmfPlusPathPointFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/) | r/w | Ottiene o imposta il conteggio dei punti del percorso <br/>            Un intero senza segno a 32 bit che specifica come interpretare i punti e i tipi di punto associati definiti da questo oggetto |
| path_point_types | [EmfPlusBasePointType[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype/) | r/w | Ottiene o imposta un array che specifica come i punti nel campo PathPoints sono usati per disegnare il percorso. <br/>            Il tipo di oggetti in questo array è specificato dal flag R nel campo PathPointFlags |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Ottiene o imposta un array di punti del percorso<br/>            Un array di PathPointCount punti che specificano il percorso. Il tipo di oggetti in questo array è specificato dal campo PathPointFlags, come segue:<br/>            Se il flag P è impostato, i punti sono posizioni relative specificate da oggetti EmfPlusPointR (sezione 2.2.2.37).<br/>            Se il flag P non è impostato e il flag C è impostato, i punti sono posizioni assolute specificate da oggetti EmfPlusPoint (sezione 2.2.2.35).<br/>            Se il flag P non è impostato e il flag C non è impostato, i punti sono posizioni assolute specificate da oggetti EmfPlusPointF (sezione 2.2.2.36). |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Ottiene o imposta la versione. |


### Constructor: EmfPlusPath() {#EmfPlusPath__1}


```
 EmfPlusPath() 
```

Inizializza una nuova istanza della classe EmfPlusPath

