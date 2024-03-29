---
title: EmfPlusDrawBeziers
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EmfPlusDrawBeziers specifica il disegno di una sequenza di curve di Bezier collegate. Lordine dei punti dati Bezier è il punto iniziale il punto di controllo 1 il punto di controllo 2 e il punto finale. Per ulteriori informazioni vedere MSDN-DrawBeziers.
type: docs
weight: 5910
url: /it/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---
## EmfPlusDrawBeziers class

Il record EmfPlusDrawBeziers specifica il disegno di una sequenza di curve di Bezier collegate. L'ordine dei punti dati Bezier è il punto iniziale, il punto di controllo 1, il punto di controllo 2 e il punto finale. Per ulteriori informazioni, vedere [MSDN-DrawBeziers].

```csharp
public sealed class EmfPlusDrawBeziers : EmfPlusDrawingRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPlusDrawBeziers](emfplusdrawbeziers)(EmfPlusRecord) | Inizializza una nuova istanza di[`EmfPlusDrawBeziers`](../emfplusdrawbeziers) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/compressed) { get; set; } | Ottiene o imposta un valore che indica se PointData è compresso. Se impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate intere a 16 bit. Se chiaro, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit. Nota Se è impostato il flag Relativo (sotto), questo flag non è definito e DEVE essere ignorato. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record a 12 byte. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come deve essere eseguita l'operazione e sulla struttura del record. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/objectid) { get; set; } | Ottiene o imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella tabella degli oggetti EMF+ per disegnare le curve di Bezier. Il valore DEVE essere da zero a 63, inclusi. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/pointdata) { get; set; } | Ottiene o imposta i dati del punto Una matrice di punti di conteggio che specificano i punti di inizio, fine e controllo delle curve di Bezier. La coordinata finale di una curva di Bezier è la coordinata iniziale della successiva. I punti di controllo vengono utilizzati per produrre l'effetto Bezier. Il tipo di dati in questo array è specificato dal campo Flag, come segue: Tipo di dati Significato Oggetto EmfPlusPointR (sezione 2.2.2.37) Se il flag P è impostato nei Flag , i punti specificano le posizioni relative. Oggetto EmfPlusPointF (sezione 2.2.2.36) Se i bit P e C sono liberi nel campo Flag, i punti specificano le posizioni assolute. Oggetto EmfPlusPoint (sezione 2.2.2.35) Se il bit P è azzerato e il bit C è impostato nel campo Flag, i punti specificano le posizioni relative. Una curva di Bezier non passa attraverso i suoi punti di controllo. I punti di controllo agiscono come |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/relative) { get; set; } | Ottiene o imposta un valore che indica se PointData è relativo. Se impostato, ogni elemento in PointData specifica una posizione nello spazio delle coordinate relativa alla posizione specificata dall'elemento precedente nella matrice. Nel caso del primo elemento in PointData, si assume una posizione precedente alle coordinate (0,0). Se chiaro, PointData specifica posizioni assolute in base a rispetto al flag C. Nota Se questo flag è impostato, il flag C (sopra) non è definito e DEVE essere ignorato. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ottiene o imposta un numero intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte nell'intero record, inclusi l'intestazione del record a 12 byte ei dati specifici del record. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |

### Guarda anche

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
