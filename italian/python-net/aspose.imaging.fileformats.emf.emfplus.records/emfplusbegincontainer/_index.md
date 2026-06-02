---
title: "EmfPlusBeginContainer Classe"
type: docs
weight: 10
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/
---

**Summary:** The EmfPlusBeginContainer record opens a new graphics state container and specifies a transform for it.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusBeginContainer

**Inheritance:** EmfPlusStateRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusBeginContainer(source)](#EmfPlusBeginContainer_source_1) | Inizializza una nuova istanza della classe [EmfPlusBeginContainer](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/) |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| dest_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Ottiene o imposta un oggetto EmfPlusRectF (sezione 2.2.2.39) che, insieme a SrcRect, specifica<br/> una trasformazione per il contenitore. Questa trasformazione produce SrcRect quando applicata a DestRect. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| page_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r | Ottiene l'unità della pagina. |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Ottiene o imposta un rettangolo EmfPlusRectF che, insieme a DestRect, specifica una trasformazione<br/> per il contenitore. Questa trasformazione produce SrcRect quando applicata a DestRect. |
| stack_index | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica un indice da associare al<br/>            contenitore di stato grafico. L'indice DEVE essere referenziato da un successivo<br/>            record EmfPlusEndContainer (sezione 2.3.7.3) per chiudere il contenitore di stato grafico. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |


### Constructor: EmfPlusBeginContainer(source) {#EmfPlusBeginContainer_source_1}


```
 EmfPlusBeginContainer(source) 
```

Inizializza una nuova istanza della classe [EmfPlusBeginContainer](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/)

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

