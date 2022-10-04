---
title: EmfPlusStateRecordType
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: I tipi di record di stato specificano le operazioni sullo stato del contesto del dispositivo di riproduzione.
type: docs
weight: 6430
url: /it/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype/
---
## EmfPlusStateRecordType class

I tipi di record di stato specificano le operazioni sullo stato del contesto del dispositivo di riproduzione.

```csharp
public abstract class EmfPlusStateRecordType : EmfPlusRecord
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record a 12 byte. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come deve essere eseguita l'operazione e sulla struttura del record. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ottiene o imposta un numero intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte nell'intero record, inclusi l'intestazione del record a 12 byte ei dati specifici del record. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |

### Osservazioni

Ciascun contenitore dello stato grafico DEVE essere aggiunto a un array di contenitori grafici salvati. Il contenitore dello stato graphics non viene scritto nel metafile EMF+, quindi il suo formato può essere determinato dall'implementazione .

### Guarda anche

* class [EmfPlusRecord](../emfplusrecord)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->