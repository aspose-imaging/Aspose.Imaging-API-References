---
title: EmfPlusHeader
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EmfPlusHeader specifica linizio dei dati EMF nel metafile. Il record EmfPlusHeader DEVE essere incorporato in un record EMF EMR_COMMENT_EMFPLUS che DEVE essere il record immediatamente successivo allintestazione EMF nel metafile. Il record EMR_COMMENT_EMFPLUS è specificato nella sezione MS-EMF 2.3.3.2.
type: docs
weight: 6140
url: /it/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---
## EmfPlusHeader class

Il record EmfPlusHeader specifica l'inizio dei dati EMF+ nel metafile. Il record EmfPlusHeader DEVE essere incorporato in un record EMF EMR_COMMENT_EMFPLUS, che DEVE essere il record immediatamente successivo all'intestazione EMF nel metafile. Il record EMR_COMMENT_EMFPLUS è specificato nella sezione [MS-EMF] 2.3.3.2.

```csharp
public sealed class EmfPlusHeader : EmfPlusControlRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPlusHeader](emfplusheader)(EmfPlusRecord) | Inizializza una nuova istanza di[`EmfPlusHeader`](../emfplusheader) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record a 12 byte. |
| [DualMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/dualmode) { get; set; } | Ottiene o imposta un valore che indica se [modalità doppia]. Se impostato, questo flag indica che questo metafile è "modalità doppia", il che significa che contiene due set di record, ognuno dei quali specifica completamente il contenuto grafico. Se è deselezionato, il contenuto grafico è specificato dai record EMF+ e possibilmente dai record EMF preceduti da un record EmfPlusGetDC. Se questo flag è impostato, i record EMF da soli DOVREBBE essere sufficienti per definire il contenuto grafico . Si noti che indipendentemente dal fatto che il flag "dual-mode" sia impostato o meno, alcuni record EMF sono sempre presenti, ovvero record di controllo EMF e record EMF che contengono record EMF+. I record di controllo EMF sono specificati in [MS-EMF] sezione 2.3.4. |
| [EmfPlusFlags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/emfplusflags) { get; set; } | Ottiene o imposta i flag EMF plus. Un numero intero senza segno a 32 bit che contiene informazioni su come è stato registrato questo metafile. se è impostato il 31° bit del campo, questo flag indica che il metafile è stato registrato con un riferimento contesto del dispositivo per una visualizzazione video. Se deselezionato, il metafile è stato registrato con un contesto di dispositivo di riferimento per una stampante. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come deve essere eseguita l'operazione e sulla struttura del record. |
| [IsValid](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/isvalid) { get; } | Ottiene un valore che indica se questa istanza è valida. |
| [LogicalDpiX](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/logicaldpix) { get; set; } | Ottiene o imposta il dpi logico x. Un numero intero senza segno a 32 bit che specifica la risoluzione orizzontale per la quale è stato registrato il metafile , in unità di pixel per pollice. |
| [LogicalDpiY](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/logicaldpiy) { get; set; } | Ottiene o imposta il dpi logico y. Un numero intero senza segno a 32 bit che specifica la risoluzione verticale per cui è stato registrato il metafile , in unità di righe per pollice |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ottiene o imposta un numero intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte nell'intero record, inclusi l'intestazione del record a 12 byte ei dati specifici del record. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/version) { get; set; } | Ottiene o imposta la versione. Un oggetto EmfPlusGraphicsVersion (sezione 2.2.2.19) che specifica la versione della grafica di sistema operativa utilizzata per creare questo metafile. |
| [VideoDisplay](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/videodisplay) { get; set; } | Ottiene o imposta un valore che indica se la visualizzazione video. se impostata, questo flag indica che il metafile è stato registrato con un contesto di riferimento device per una visualizzazione video. Se deselezionato, il metafile è stato registrato con un contesto device di riferimento per una stampante. |

### Guarda anche

* class [EmfPlusControlRecordType](../emfpluscontrolrecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
