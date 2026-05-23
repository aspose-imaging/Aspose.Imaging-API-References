---
title: "Classe EmfPlusHeader"
type: docs
weight: 310
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---

**Summary:** The EmfPlusHeader record specifies the start of EMF+ data in the metafile.<br/>            The EmfPlusHeader record MUST be embedded in an EMF EMR_COMMENT_EMFPLUS record,<br/>             which MUST be the record immediately following the EMF header in the metafile. <br/>            The EMR_COMMENT_EMFPLUS record is specified in [MS-EMF] section 2.3.3.2.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusHeader

**Inheritance:** EmfPlusControlRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusHeader(source)](#EmfPlusHeader_source_1) | Inizializza una nuova istanza della classe [EmfPlusHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di<br/>            byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record di 12 byte. |
| dual_mode | bool | r/w | Ottiene o imposta un valore che indica se [dual mode].<br/>            Se impostato, questo flag indica che questo metafile è "dual-mode", il che significa<br/>            che contiene due insiemi di record, ciascuno dei quali specifica completamente <br/>            il contenuto grafico. Se non impostato, il contenuto grafico è specificato dai record EMF+ <br/>            e, eventualmente, dai record EMF preceduti da un record EmfPlusGetDC. <br/>            Se questo flag è impostato, i record EMF da soli DOVREBBERO essere sufficienti a definire il <br/>            contenuto grafico. Si noti che, indipendentemente dal fatto che il flag "dual-mode" sia impostato o meno, alcuni <br/>            record EMF sono sempre presenti, ovvero i record di controllo EMF e i record EMF <br/>            che contengono record EMF+. I record di controllo EMF sono specificati in [MS-EMF] <br/>            sezione 2.3.4. |
| emf_plus_flags | int | r/w | Ottiene o imposta i flag EMF plus.<br/>            Un intero senza segno a 32 bit che contiene informazioni su come è stato registrato questo metafile.<br/>            se il 31° bit del campo è impostato, questo flag indica che il metafile è stato registrato con <br/>            un contesto di dispositivo di riferimento per un display video. Se non impostato, il metafile è stato registrato con<br/>            un contesto di dispositivo di riferimento per una stampante. |
| flag | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come<br/>            l'operazione deve essere eseguita e sulla struttura del record. |
| is_valid | bool | r | Ottiene un valore che indica se questa istanza è valida. |
| logical_dpi_x | int | r/w | Ottiene o imposta il dpi logico x.<br/>            Un intero senza segno a 32 bit che specifica la risoluzione orizzontale per la quale il metafile <br/>            è stato registrato, in unità di pixel per pollice. |
| logical_dpi_y | int | r/w | Ottiene o imposta il dpi logico y.<br/>            Un intero senza segno a 32 bit che specifica la risoluzione verticale per la quale il metafile <br/>            è stato registrato, in unità di linee per pollice. |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte<br/>            nell'intero record, includendo l'intestazione del record di 12 byte e i dati specifici del record. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Ottiene o imposta la versione.<br/>            Un oggetto EmfPlusGraphicsVersion (sezione 2.2.2.19) che specifica la versione della grafica del sistema operativo<br/>            utilizzata per creare questo metafile. |
| video_display | bool | r/w | Ottiene o imposta un valore che indica se il display video.<br/>            se impostato, questo flag indica che il metafile è stato registrato con un contesto di dispositivo di riferimento per un display video. Se non impostato, il metafile è stato registrato con un contesto di dispositivo di riferimento per una stampante. |


### Constructor: EmfPlusHeader(source) {#EmfPlusHeader_source_1}


```
 EmfPlusHeader(source) 
```

Inizializza una nuova istanza della classe [EmfPlusHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La sorgente. |

