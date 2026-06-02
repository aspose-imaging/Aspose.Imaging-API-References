---
title: "Classe EmfPlusComment"
type: docs
weight: 50
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/
---

**Summary:** The EmfPlusComment record specifies arbitrary private data.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusComment

**Inheritance:** EmfPlusRecord

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusComment(source)](#EmfPlusComment_source_1) | Inizializza una nuova istanza della classe [EmfPlusComment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit non utilizzato. Questo campo DOVREBBE essere impostato a zero<br/>            e DEVE essere ignorato al ricevimento. |
| private_data | System.Byte | r/w | Ottiene o imposta un array di byte di lunghezza DataSize contenente dati privati.<br/>            byte di dati specifici del record che seguono. |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |


### Constructor: EmfPlusComment(source) {#EmfPlusComment_source_1}


```
 EmfPlusComment(source) 
```

Inizializza una nuova istanza della classe [EmfPlusComment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

