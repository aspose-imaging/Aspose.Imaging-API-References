---
title: EmfPlusDrawPath
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EmfPlusDrawPath specifica il disegno di un percorso grafico.
type: docs
weight: 5990
url: /it/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/
---
## EmfPlusDrawPath class

Il record EmfPlusDrawPath specifica il disegno di un percorso grafico.

```csharp
public sealed class EmfPlusDrawPath : EmfPlusDrawingRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPlusDrawPath](emfplusdrawpath)(EmfPlusRecord) | Inizializza una nuova istanza di[`EmfPlusDrawPath`](../emfplusdrawpath) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record a 12 byte. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come deve essere eseguita l'operazione e sulla struttura del record. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/objectid) { get; set; } | Ottiene o imposta l'identificatore dell'oggetto. L'indice dell'oggetto EmfPlusPath (sezione 2.2.1.6) da disegnare, nella tabella degli oggetti EMF+ . Il valore DEVE essere da zero a 63, inclusi. |
| [PenId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/penid) { get; set; } | Ottiene o imposta l'identificatore di penna Un numero intero senza segno a 32 bit che specifica un indice nella tabella oggetti EMF+ per un oggetto EmfPlusPen (sezione 2.2.1.7) da utilizzare per disegnare EmfPlusPath. Il valore DEVE essere da zero a 63, incluso |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ottiene o imposta un numero intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte nell'intero record, inclusi l'intestazione del record a 12 byte ei dati specifici del record. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |

### Guarda anche

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->