---
title: "Classe EmfPlusGetDc"
type: docs
weight: 300
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusgetdc/
---

**Summary:** The EmfPlusGetDC record specifies that subsequent EMF records encountered in the metafile SHOULD be processed.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusGetDc

**Inheritance:** EmfPlusControlRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusGetDc(source)](#EmfPlusGetDc_source_1) | Inizializza una nuova istanza della classe [EmfPlusGetDc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusgetdc/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit non utilizzato. Questo campo DOVREBBE essere impostato a zero<br/>            e DEVE essere ignorato al ricevimento. |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |


### Constructor: EmfPlusGetDc(source) {#EmfPlusGetDc_source_1}


```
 EmfPlusGetDc(source) 
```

Inizializza una nuova istanza della classe [EmfPlusGetDc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusgetdc/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

