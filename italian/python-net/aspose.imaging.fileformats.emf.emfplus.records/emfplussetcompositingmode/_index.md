---
title: "Classe EmfPlusSetCompositingMode"
type: docs
weight: 490
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/
---

**Summary:** The EmfPlusSetCompositingMode record specifies how source colors are combined with background colors.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetCompositingMode

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusSetCompositingMode(source)](#EmfPlusSetCompositingMode_source_1) | Inizializza una nuova istanza della classe [EmfPlusSetCompositingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| compositing_mode | [EmfPlusCompositingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingmode/) | r/w | Ottiene o imposta il valore della modalità di composizione, dall'enumerazione CompositingMode<br/>            (sezione 2.1.1.5). La composizione può essere espressa come lo stato del blending alfa,<br/>            che può essere attivo o inattivo. |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |


### Constructor: EmfPlusSetCompositingMode(source) {#EmfPlusSetCompositingMode_source_1}


```
 EmfPlusSetCompositingMode(source) 
```

Inizializza una nuova istanza della classe [EmfPlusSetCompositingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

