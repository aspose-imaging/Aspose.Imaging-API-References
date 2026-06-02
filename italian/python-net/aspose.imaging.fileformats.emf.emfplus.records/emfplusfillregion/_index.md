---
title: "Classe EmfPlusFillRegion"
type: docs
weight: 290
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/
---

**Summary:** The EmfPlusFillRegion record specifies filling the interior of a graphics region

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillRegion

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusFillRegion(source)](#EmfPlusFillRegion_source_1) | Inizializza una nuova istanza della classe [EmfPlusFillRegion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Ottiene o imposta l'identificatore del pennello<br/>
            Un intero senza segno a 32 bit che definisce il pennello, il cui contenuto è determinato dal bit S nel campo Flags. |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| is_color | bool | r/w | Ottiene o imposta un valore che indica se questa istanza è un colore.<br/>            Se impostato, BrushId specifica un colore come oggetto EmfPlusARGB (sezione 2.2.2.1). <br/>            Se non impostato, BrushId contiene l'indice di un oggetto EmfPlusBrush (sezione 2.2.1.1) nella tabella degli oggetti EMF+. |
| object_id | System.Byte | r/w | Ottiene o imposta l'identificatore dell'oggetto.<br/>            L'indice dell'oggetto EmfPlusRegion (sezione 2.2.1.8) da riempire, nella<br/>            EMF+ Object Table. Il valore DEVE essere compreso tra 0 e 63, inclusi. |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |


### Constructor: EmfPlusFillRegion(source) {#EmfPlusFillRegion_source_1}


```
 EmfPlusFillRegion(source) 
```

Inizializza una nuova istanza della classe [EmfPlusFillRegion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

