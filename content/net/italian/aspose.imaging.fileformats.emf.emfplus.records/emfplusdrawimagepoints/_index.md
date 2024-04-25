---
title: EmfPlusDrawImagePoints
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EmfPlusDrawImagePoints specifica il disegno di unimmagine in scala allinterno di un parallelogramma.
type: docs
weight: 5970
url: /it/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---
## EmfPlusDrawImagePoints class

Il record EmfPlusDrawImagePoints specifica il disegno di un'immagine in scala all'interno di un parallelogramma.

```csharp
public sealed class EmfPlusDrawImagePoints : EmfPlusDrawingRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPlusDrawImagePoints](emfplusdrawimagepoints)(EmfPlusRecord) | Inizializza una nuova istanza di[`EmfPlusDrawImagePoints`](../emfplusdrawimagepoints) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ApplyingAnEffect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/applyinganeffect) { get; set; } | Ottiene o imposta un valore che indica se [applicando un effetto]. Questo bit indica che il rendering dell'immagine include l'applicazione di un effetto. Se impostato, un oggetto della classe Effect DEVE essere stato specificato in un record EmfPlusSerializableObject precedente (sezione 2.3.5.2). |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/compressed) { get; set; } | Ottiene o imposta un valore che indica se PointData è compresso. Questo bit indica se il campo PointData specifica dati compressi. Se impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate intere a 16 bit . Se chiaro, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit. Nota Se è impostato il flag P (sotto), questo flag non è definito e DEVE essere ignorato. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record a 12 byte. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come deve essere eseguita l'operazione e sulla struttura del record. |
| [ImageAttributesId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/imageattributesid) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che contiene l'indice dell'oggetto EmfPlusImageAttributes facoltativo (sezione 2.2.1.5) nella tabella oggetti EMF+. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/objectid) { get; set; } | Ottiene o imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusImage (sezione 2.2.1.4) nella tabella degli oggetti EMF+ , che specifica l'immagine di cui eseguire il rendering. Il valore DEVE essere da zero a 63, inclusi. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/pointdata) { get; set; } | Ottiene o imposta una matrice di punti Conteggio che specificano tre punti di un parallelogramma. I tre punti rappresentano gli angoli superiore sinistro, superiore destro e inferiore sinistro del parallelogramma. Il quarto punto del parallelogramma è estrapolato dai primi tre. La porzione dell'immagine specificata dal campo SrcRect DOVREBBE avere trasformazioni di ridimensionamento e taglio applicate se necessario per adattarsi all'interno del parallelogramma. |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/relative) { get; set; } | Ottiene o imposta un valore che indica se questo[`EmfPlusDrawImagePoints`](../emfplusdrawimagepoints)è relativo. Questo bit indica se il campo PointData specifica posizioni relative o assolute. Se impostato, ogni elemento in PointData specifica una posizione nello spazio delle coordinate che è rispetto alla posizione specificata dall'elemento precedente nell'array. Nel caso del primo elemento in PointData, si assume una posizione precedente alle coordinate (0,0). Se chiaro, PointData specifica posizioni assolute in base al flag C. Nota Se questo flag è impostato, il flag C (sopra) non è definito e DEVE essere ignorato. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ottiene o imposta un numero intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte nell'intero record, inclusi l'intestazione del record a 12 byte ei dati specifici del record. |
| [SrcRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/srcrect) { get; set; } | Ottiene o imposta un oggetto EmfPlusRectF (sezione 2.2.2.39) che definisce una parte dell'immagine da renderizzare. |
| [SrcUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/srcunit) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che definisce le unità del campo SrcRect. DEVE essere il valore UnitPixel dell'enumerazione UnitType (sezione 2.1.1.33). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |

### Osservazioni

Un EmfPlusImage può specificare una bitmap o un metafile. I colori in un'immagine possono essere manipolati durante il rendering. Possono essere corretti, scuriti, schiariti e rimossi.

### Guarda anche

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
