---
title: "Classe EmfPlusFillRects"
type: docs
weight: 280
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/
---

**Summary:** The EmfPlusFillRects record specifies filling the interiors of a series of rectangles

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillRects

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusFillRects(source)](#EmfPlusFillRects_source_1) | Inizializza una nuova istanza della classe [EmfPlusFillRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Ottiene o imposta l'identificatore del pennello<br/>
            Un intero senza segno a 32 bit che definisce il pennello, il cui contenuto è determinato dal bit S nel campo Flags. |
| compressed | bool | r/w | Ottiene o imposta un valore che indica se questo [EmfPlusFillRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/) è compresso.<br/>
            Se impostato, RectData contiene un oggetto EmfPlusRect (sezione 2.2.2.38). Se non impostato, RectData
             contiene un oggetto EmfPlusRectF (sezione 2.2.2.39). |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| is_color | bool | r/w | Ottiene o imposta un valore che indica se questa istanza è un colore.<br/>
            Se impostato, BrushId specifica un colore come oggetto EmfPlusARGB (sezione 2.2.2.1).<br/>
            Se non impostato, BrushId contiene l'indice di un oggetto EmfPlusBrush (sezione 2.2.1.1) nella tabella degli oggetti EMF+. |
| rect_data | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Ottiene o imposta i dati del rettangolo<br/>
            Un array di oggetti EmfPlusRect o EmfPlusRectF della lunghezza Count che definisce i dati del rettangolo. |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |


### Constructor: EmfPlusFillRects(source) {#EmfPlusFillRects_source_1}


```
 EmfPlusFillRects(source) 
```

Inizializza una nuova istanza della classe [EmfPlusFillRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

