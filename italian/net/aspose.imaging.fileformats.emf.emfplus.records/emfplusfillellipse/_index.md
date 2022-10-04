---
title: EmfPlusFillEllipse
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EmfPlusFillEllipse specifica il riempimento dellinterno di unellisse
type: docs
weight: 6070
url: /it/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/
---
## EmfPlusFillEllipse class

Il record EmfPlusFillEllipse specifica il riempimento dell'interno di un'ellisse

```csharp
public sealed class EmfPlusFillEllipse : EmfPlusDrawingRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPlusFillEllipse](emfplusfillellipse)(EmfPlusRecord) | Inizializza una nuova istanza di[`EmfPlusFillEllipse`](../emfplusfillellipse) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/brushid) { get; set; } | Ottiene o imposta l'identificatore del pennello Un numero intero senza segno a 32 bit che specifica il pennello, il cui contenuto è determinato dal bit S nel campo Flags. Questa definizione viene utilizzata per riempire l'interno dell'ellisse |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record a 12 byte. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come deve essere eseguita l'operazione e sulla struttura del record. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/iscolor) { get; set; } | Ottiene o imposta un valore che indica se questa istanza è color. Se impostato, BrushId specifica un colore come oggetto EmfPlusARGB (sezione 2.2.2.1). Se deselezionato, BrushId contiene l'indice di un oggetto EmfPlusBrush (sezione 2.2.1.1). ) nella tabella oggetti EMF+. |
| [IsCompressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/iscompressed) { get; set; } | Ottiene o imposta un valore che indica se questa istanza è compressa. Se impostato, RectData contiene un oggetto EmfPlusRect (sezione 2.2.2.38). Se azzerato, RectData contiene un oggetto EmfPlusRectF (sezione 2.2.2.39). |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/rectdata) { get; set; } | Ottiene o imposta i dati corretti Un oggetto EmfPlusRect o EmfPlusRectF che definisce il riquadro di delimitazione dell'ellisse |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ottiene o imposta un numero intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte nell'intero record, inclusi l'intestazione del record a 12 byte ei dati specifici del record. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |

### Guarda anche

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->