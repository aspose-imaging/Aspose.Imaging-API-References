---
title: "Classe EmfPlusDrawString"
type: docs
weight: 190
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---

**Summary:** The EmfPlusDrawString record specifies text output with string formatting

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawString

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusDrawString(source)](#EmfPlusDrawString_source_1) | Inizializza una nuova istanza della classe [EmfPlusDrawString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Ottiene o imposta l'identificatore del pennello<br/>            Un intero senza segno a 32 bit che specifica il pennello, il cui contenuto <br/>            è determinato dal bit S nel campo Flags. Questa definizione è usata <br/>            per dipingere il colore del testo in primo piano; cioè, solo i glifi stessi. |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| format_id | int | r/w | Ottiene o imposta l'identificatore del formato<br/>            Un intero senza segno a 32 bit che specifica l'indice di un oggetto <br/>            EmfPlusStringFormat opzionale (sezione 2.2.1.9) nella Tabella Oggetti EMF+. <br/>            Questo oggetto specifica le informazioni di layout del testo e le manipolazioni di visualizzazione <br/>            da applicare a una stringa. |
| is_color | bool | r/w | Ottiene o imposta un valore che indica se questa istanza è a colori.<br/>            Se impostato, BrushId specifica un colore come oggetto EmfPlusARGB (sezione 2.2.2.1).<br/>            Se non impostato, BrushId contiene l'indice di un oggetto EmfPlusBrush <br/>            (sezione 2.2.1.1) nella Tabella Oggetti EMF+. |
| layout_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Ottiene o imposta il rettangolo di layout<br/>            Un oggetto EmfPlusRectF (sezione 2.2.2.39) che definisce l'area di delimitazione <br/>            della destinazione che riceverà la stringa. |
| length | int | r/w | Ottiene o imposta la lunghezza<br/>            Intero senza segno a 32 bit che specifica il numero di caratteri nella stringa. |
| object_id | System.Byte | r/w | Ottiene o imposta l'identificatore dell'oggetto.<br/>            L'indice di un oggetto EmfPlusFont (sezione 2.2.1.3) nella Tabella Oggetti EMF+ <br/>            per renderizzare il testo. Il valore DEVE essere compreso tra 0 e 63, inclusi. |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| string_data | string | r/w | Ottiene o imposta i dati della stringa<br/>            Un array di caratteri Unicode a 16 bit che specifica la stringa da disegnare. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |


### Constructor: EmfPlusDrawString(source) {#EmfPlusDrawString_source_1}


```
 EmfPlusDrawString(source) 
```

Inizializza una nuova istanza della classe [EmfPlusDrawString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

