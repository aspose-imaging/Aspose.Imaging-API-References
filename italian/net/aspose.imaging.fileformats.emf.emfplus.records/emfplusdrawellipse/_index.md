---
title: EmfPlusDrawEllipse
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EmfPlusDrawEllipse specifica il disegno di unellisse.
type: docs
weight: 5950
url: /it/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/
---
## EmfPlusDrawEllipse class

Il record EmfPlusDrawEllipse specifica il disegno di un'ellisse.

```csharp
public sealed class EmfPlusDrawEllipse : EmfPlusDrawingRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPlusDrawEllipse](emfplusdrawellipse)(EmfPlusRecord) | Inizializza una nuova istanza di[`EmfPlusDrawEllipse`](../emfplusdrawellipse) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/compressed) { get; set; } | Ottiene o imposta un valore che indica se PointData è compresso. Se impostato, RectData contiene un oggetto EmfPlusRect (sezione 2.2.2.38). Se azzerato, RectData contiene un oggetto EmfPlusRectF (sezione 2.2.2.39). |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record a 12 byte. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come deve essere eseguita l'operazione e sulla struttura del record. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/objectid) { get; set; } | Ottiene o imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella tabella oggetti EMF+ per disegnare l'ellisse. Il valore DEVE essere da zero a 63, inclusi. |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/rectdata) { get; set; } | Ottiene o imposta il rettangolo data Un oggetto EmfPlusRect o EmfPlusRectF che definisce il riquadro di delimitazione dell'ellisse. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ottiene o imposta un numero intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte nell'intero record, inclusi l'intestazione del record a 12 byte ei dati specifici del record. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |

### Guarda anche

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->