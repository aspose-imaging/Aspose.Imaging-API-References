---
title: "Classe EmfPlusFillEllipse"
type: docs
weight: 240
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/
---

**Summary:** The EmfPlusFillEllipse record specifies filling the interior of an ellipse

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillEllipse

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusFillEllipse(source)](#EmfPlusFillEllipse_source_1) | Inizializza una nuova istanza della classe [EmfPlusFillEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Ottiene o imposta l'identificatore del pennello<br/>            Un intero senza segno a 32 bit che specifica il pennello, il cui contenuto<br/>            è determinato dal bit S nel campo Flags. Questa definizione è usata <br/>            per riempire l'interno dell'ellisse. |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| is_color | bool | r/w | Ottiene o imposta un valore che indica se questa istanza è a colori.<br/>            Se impostato, BrushId specifica un colore come oggetto EmfPlusARGB (sezione 2.2.2.1).<br/>            Se non impostato, BrushId contiene l'indice di un oggetto EmfPlusBrush <br/>            (sezione 2.2.1.1) nella Tabella Oggetti EMF+. |
| is_compressed | bool | r/w | Ottiene o imposta un valore che indica se questa istanza è compressa.<br/>            Se impostato, RectData contiene un oggetto EmfPlusRect (sezione 2.2.2.38). <br/>            Se non impostato, RectData contiene un oggetto EmfPlusRectF (sezione 2.2.2.39). |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Ottiene o imposta i dati del rettangolo<br/>            Un oggetto EmfPlusRect o EmfPlusRectF che definisce il riquadro di delimitazione dell'ellisse. |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |


### Constructor: EmfPlusFillEllipse(source) {#EmfPlusFillEllipse_source_1}


```
 EmfPlusFillEllipse(source) 
```

Inizializza una nuova istanza della classe [EmfPlusFillEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

