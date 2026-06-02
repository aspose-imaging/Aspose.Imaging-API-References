---
title: "Classe EmfPlusSetClipPath"
type: docs
weight: 460
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/
---

**Summary:** The EmfPlusSetClipPath record combines the current clipping region with a graphics path.<br/>            The new current clipping region is set to the result of the CombineMode operation.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetClipPath

**Inheritance:** EmfPlusClippingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusSetClipPath(source)](#EmfPlusSetClipPath_source_1) | Inizializza una nuova istanza della classe [EmfPlusSetClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| cm | [EmfPlusCombineMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscombinemode/) | r/w | Ottiene o imposta il CM (4 bit): Specifica l'operazione logica per combinare due regioni. Vedi l'enumerazione<br/>            CombineMode (sezione 2.1.1.4) per i significati dei valori. |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| object_id | System.Byte | r/w | Ottiene o imposta l'indice di un oggetto EmfPlusPath (sezione 2.2.1.6) nella tabella degli oggetti EMF+<br/>            . Il valore DEVE essere compreso tra 0 e 63, inclusi. |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |


### Constructor: EmfPlusSetClipPath(source) {#EmfPlusSetClipPath_source_1}


```
 EmfPlusSetClipPath(source) 
```

Inizializza una nuova istanza della classe [EmfPlusSetClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

