---
title: "Classe EmfPlusDrawPath"
type: docs
weight: 160
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/
---

**Summary:** The EmfPlusDrawPath record specifies drawing a graphics path.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawPath

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusDrawPath(source)](#EmfPlusDrawPath_source_1) | Inizializza una nuova istanza della classe [EmfPlusDrawPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| object_id | System.Byte | r/w | Ottiene o imposta l'identificatore dell'oggetto.<br/>            L'indice dell'oggetto EmfPlusPath (sezione 2.2.1.6) da disegnare, nella<br/>            EMF+ Object Table. Il valore DEVE essere compreso tra 0 e 63, inclusi. |
| pen_id | int | r/w | Ottiene o imposta l'identificatore della penna<br/>            Un intero senza segno a 32 bit che specifica un indice nella EMF+ Object Table<br/>            per un oggetto EmfPlusPen (sezione 2.2.1.7) da utilizzare per disegnare l'EmfPlusPath.<br/>            Il valore DEVE essere compreso tra 0 e 63, inclusi |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |


### Constructor: EmfPlusDrawPath(source) {#EmfPlusDrawPath_source_1}


```
 EmfPlusDrawPath(source) 
```

Inizializza una nuova istanza della classe [EmfPlusDrawPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

