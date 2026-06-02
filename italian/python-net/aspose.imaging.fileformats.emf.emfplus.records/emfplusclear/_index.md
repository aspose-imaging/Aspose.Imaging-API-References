---
title: "Classe EmfPlusClear"
type: docs
weight: 30
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusclear/
---

**Summary:** The EmfPlusClear record clears the output coordinate space and initializes it with a background color and transparency

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClear

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusClear(source)](#EmfPlusClear_source_1) | Inizializza una nuova istanza della classe [EmfPlusClear](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusclear/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| argb_32_color | int | r/w | Ottiene o imposta il colore.<br/>            Un oggetto EmfPlusARGB (sezione 2.2.2.1) che definisce il colore da utilizzare per dipingere lo schermo. Tutti i colori sono specificati in [IEC-RGB], salvo diversa indicazione. |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |


### Constructor: EmfPlusClear(source) {#EmfPlusClear_source_1}


```
 EmfPlusClear(source) 
```

Inizializza una nuova istanza della classe [EmfPlusClear](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusclear/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

