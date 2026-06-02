---
title: "Classe EmfPlusFillPolygon"
type: docs
weight: 270
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---

**Summary:** The EmfPlusFillPolygon record specifies filling the interior of a polygon.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillPolygon

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusFillPolygon(source)](#EmfPlusFillPolygon_source_1) | Inizializza una nuova istanza della classe [EmfPlusFillPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Ottiene o imposta l'identificatore del pennello<br/>            Un intero senza segno a 32 bit che definisce il pennello, il cui contenuto <br/>            è determinato dal bit S nel campo Flags. |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| is_color | bool | r/w | Ottiene o imposta un valore che indica se questa istanza è un colore.<br/>            Se impostato, BrushId specifica un colore come oggetto EmfPlusARGB (sezione 2.2.2.1). <br/>            Se non impostato, BrushId contiene l'indice di un oggetto EmfPlusBrush (sezione 2.2.1.1) nella tabella degli oggetti EMF+. |
| is_compressed | bool | r/w | Ottiene o imposta un valore che indica se questa istanza è compressa.<br/>            Se impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate intere a 16 bit. Se non impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit. |
| is_relative | bool | r/w | Ottiene o imposta un valore che indica se questa istanza è relativa.<br/>            Se impostato, ogni elemento in PointData specifica una posizione nello spazio delle coordinate che è relativa alla posizione specificata dall'elemento precedente <br/>            nell'array. Nel caso del primo elemento in PointData, si assume una posizione precedente alle coordinate (0,0). Se non impostato, PointData specifica <br/>            posizioni assolute secondo il flag C. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Ottiene o imposta i dati dei punti<br/>            Un array di Count punti che definiscono i vertici del poligono. <br/>            I primi due punti dell'array specificano il primo lato del poligono. <br/>            Ogni punto aggiuntivo specifica un nuovo lato, i cui vertici <br/>            includono il punto corrente e il punto precedente. Se l'ultimo punto e il <br/>            primo punto non coincidono, essi specificano l'ultimo lato del poligono. |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |


### Constructor: EmfPlusFillPolygon(source) {#EmfPlusFillPolygon_source_1}


```
 EmfPlusFillPolygon(source) 
```

Inizializza una nuova istanza della classe [EmfPlusFillPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

