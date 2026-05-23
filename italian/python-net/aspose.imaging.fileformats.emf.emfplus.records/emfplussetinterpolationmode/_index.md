---
title: "EmfPlusSetInterpolationMode Classe"
type: docs
weight: 510
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetinterpolationmode/
---

**Summary:** The EmfPlusSetInterpolationMode record specifies how image scaling, including stretching and shrinking, is performed.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetInterpolationMode

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusSetInterpolationMode(source)](#EmfPlusSetInterpolationMode_source_1) | Inizializza una nuova istanza della classe [EmfPlusSetInterpolationMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetinterpolationmode/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| interpolation_mode | [EmfPlusInterpolationMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/) | r/w | Ottiene o imposta il valore della modalità di interpolazione, dall'enumerazione InterpolationMode (sezione 2.1.1.16). |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |


### Constructor: EmfPlusSetInterpolationMode(source) {#EmfPlusSetInterpolationMode_source_1}


```
 EmfPlusSetInterpolationMode(source) 
```

Inizializza una nuova istanza della classe [EmfPlusSetInterpolationMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetinterpolationmode/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

