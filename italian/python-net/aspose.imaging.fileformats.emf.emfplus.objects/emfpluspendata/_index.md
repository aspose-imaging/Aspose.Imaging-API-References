---
title: "Classe EmfPlusPenData"
type: docs
weight: 550
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/
---

**Summary:** The EmfPlusPenData object specifies properties of a graphics pen.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusPenData()](#EmfPlusPenData__1) | Inizializza una nuova istanza della classe EmfPlusPenData |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| optional_data | [EmfPlusPenOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/) | r/w | Ottiene o imposta l'oggetto opzionale EmfPlusPenOptionalData (sezione 2.2.2.34) <br/>            che specifica dati aggiuntivi per l'oggetto penna. Il contenuto specifico <br/>            di questo campo è determinato dal valore del <br/>            campo PenDataFlags. |
| pen_data_flags | [EmfPlusPenDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspendataflags/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica i dati nel campo <br/>            OptionalData. Questo valore DEVE essere composto dai flag PenData <br/>            (sezione 2.1.2.7). |
| pen_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica le unità di misura <br/>            per la penna. Il valore DEVE appartenere all'enumerazione UnitType <br/>            (sezione 2.1.1.33). |
| pen_width | float | r/w | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la larghezza della <br/>            linea tracciata dalla penna nelle unità specificate dal campo PenUnit <br/>            . Se viene specificata una larghezza zero, viene utilizzato un valore minimo, <br/>            determinato dalle unità. |


### Constructor: EmfPlusPenData() {#EmfPlusPenData__1}


```
 EmfPlusPenData() 
```

Inizializza una nuova istanza della classe EmfPlusPenData

