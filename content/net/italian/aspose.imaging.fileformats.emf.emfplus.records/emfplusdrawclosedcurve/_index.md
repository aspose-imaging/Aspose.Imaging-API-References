---
title: EmfPlusDrawClosedCurve
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EmfPlusDrawClosedCurve specifica il disegno di una spline cardinale chiusa
type: docs
weight: 5920
url: /it/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---
## EmfPlusDrawClosedCurve class

Il record EmfPlusDrawClosedCurve specifica il disegno di una spline cardinale chiusa

```csharp
public sealed class EmfPlusDrawClosedCurve : EmfPlusDrawingRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPlusDrawClosedCurve](emfplusdrawclosedcurve)(EmfPlusRecord) | Inizializza una nuova istanza di[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve) class. RecordType - Un numero intero senza segno a 16 bit che identifica questo tipo di record come EmfPlusDrawClosedCurve dall'enumerazione RecordType (sezione 2.1.1.1). Il valore DEVE essere 0x4017. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/compressed) { get; set; } | Ottiene o imposta un valore che indica se questo[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve)è compresso. Questo bit indica se il campo PointData specifica dati compressi. Se impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate intere a 16 bit. Se deselezionato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit Nota Se il flag Relativo (sotto) è impostato, questo flag non è definito e DEVE essere ignorato |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record a 12 byte. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come deve essere eseguita l'operazione e sulla struttura del record. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/objectid) { get; set; } | Ottiene o imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella tabella oggetti EMF+ per disegnare la curva chiusa. Il valore DEVE essere da zero a 63, inclusi. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/pointdata) { get; set; } | Ottiene o imposta il punto data Una matrice di punti Conteggio che specificano i punti finali delle linee che definiscono la spline. In una spline cardinale chiusa, la curva continua attraverso l'ultimo punto nell'array PointData e si collega al primo punto nell'array. Il tipo di dati in questo array è specificato dal campo Flags, come segue: Tipo di dati Significato EmfPlusPointR oggetto (sezione 2.2.2.37) Se il flag P è impostato nei Flag, i punti specificano le posizioni relative. Oggetto EmfPlusPointF (sezione 2.2.2.36) Se i bit P e C sono impostati nel campo Flag, i punti specificano posizioni assolute. Oggetto EmfPlusPoint (sezione 2.2.2.35) Se il bit P è azzerato e il bit C è impostato nel campo Flag, i punti specificano le posizioni relative. |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/relative) { get; set; } | Ottiene o imposta un valore che indica se questo[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve)è relativo. Questo bit indica se il campo PointData specifica posizioni relative o assolute. Se impostato, ogni elemento in PointData specifica una posizione nello spazio delle coordinate che è relativa alla posizione specificata dall'elemento precedente nell'array. Nel caso del primo elemento in PointData, si assume una posizione precedente alle coordinate (0,0). Se deselezionato, PointData specifica posizioni assolute in base al flag C. Nota Se questo flag è impostato, il flag Compressed (sopra) non è definito e DEVE essere ignorato |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ottiene o imposta un numero intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte nell'intero record, inclusi l'intestazione del record a 12 byte ei dati specifici del record. |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/tension) { get; set; } | Ottiene o imposta tension Un numero a virgola mobile a 32 bit che specifica quanto strettamente si piega la spline mentre passa attraverso i punti. Un valore di 0 specifica che la spline è una sequenza di linee rette. All'aumentare del valore, la curva diventa più arrotondata. Per ulteriori informazioni, vedere [SPLINE77] e [PETZOLD]. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |

### Guarda anche

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
