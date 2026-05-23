---
title: "EmfPlusOffsetClip Classe"
type: docs
weight: 350
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/
---

**Summary:** The EmfPlusOffsetClip record applies a translation transform on the current clipping region for the world space.<br/>            The new current clipping region is set to the result of the translation transform.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusOffsetClip

**Inheritance:** EmfPlusClippingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusOffsetClip(source)](#EmfPlusOffsetClip_source_1) | Inizializza una nuova istanza della classe [EmfPlusOffsetClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| dx | float | r/w | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica lo spostamento orizzontale per la traslazione. |
| dy | float | r/w | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica lo spostamento verticale per la traslazione. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |


### Constructor: EmfPlusOffsetClip(source) {#EmfPlusOffsetClip_source_1}


```
 EmfPlusOffsetClip(source) 
```

Inizializza una nuova istanza della classe [EmfPlusOffsetClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

