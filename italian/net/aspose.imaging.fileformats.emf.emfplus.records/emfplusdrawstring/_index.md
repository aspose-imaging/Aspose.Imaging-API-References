---
title: EmfPlusDrawString
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EmfPlusDrawString specifica loutput di testo con formattazione stringa
type: docs
weight: 6020
url: /it/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---
## EmfPlusDrawString class

Il record EmfPlusDrawString specifica l'output di testo con formattazione stringa

```csharp
public sealed class EmfPlusDrawString : EmfPlusDrawingRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPlusDrawString](emfplusdrawstring)(EmfPlusRecord) | Inizializza una nuova istanza di[`EmfPlusDrawString`](../emfplusdrawstring) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/brushid) { get; set; } | Ottiene o imposta l'identificatore del pennello Un numero intero senza segno a 32 bit che specifica il pennello, il cui contenuto è determinato dal bit S nel campo Flags. Questa definizione viene utilizzata per dipingere il colore del testo in primo piano; cioè, solo i glifi stessi. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record a 12 byte. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come deve essere eseguita l'operazione e sulla struttura del record. |
| [FormatId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/formatid) { get; set; } | Ottiene o imposta l'identificatore di formato Un numero intero senza segno a 32 bit che specifica l'indice di un oggetto EmfPlusStringFormat facoltativo (sezione 2.2.1.9) nella tabella oggetti EMF+. Questo oggetto specifica le informazioni sul layout del testo e le manipolazioni di visualizzazione da applicare a una stringa |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/iscolor) { get; set; } | Ottiene o imposta un valore che indica se questa istanza è color. Se impostato, BrushId specifica un colore come oggetto EmfPlusARGB (sezione 2.2.2.1). Se deselezionato, BrushId contiene l'indice di un oggetto EmfPlusBrush (sezione 2.2.1.1). ) nella tabella oggetti EMF+. |
| [LayoutRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/layoutrect) { get; set; } | Ottiene o imposta il layout rect Un oggetto EmfPlusRectF (sezione 2.2.2.39) che definisce l'area di delimitazione della destinazione che riceverà la stringa |
| [Length](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/length) { get; set; } | Ottiene o imposta il valore intero senza segno a 32 bit length che specifica il numero di caratteri nella stringa. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/objectid) { get; set; } | Ottiene o imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusFont (sezione 2.2.1.3) nella tabella oggetti EMF+ per il rendering del testo. Il valore DEVE essere da zero a 63, inclusi. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ottiene o imposta un numero intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte nell'intero record, inclusi l'intestazione del record a 12 byte ei dati specifici del record. |
| [StringData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/stringdata) { get; set; } | Ottiene o imposta la stringa data Una matrice di caratteri Unicode a 16 bit che specifica la stringa da disegnare |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |

### Guarda anche

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
