---
title: EmfPlusFillClosedCurve
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EmfPlusFillClosedCurve specifica il riempimento dellinterno di una spline cardinale chiusa
type: docs
weight: 6060
url: /it/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---
## EmfPlusFillClosedCurve class

Il record EmfPlusFillClosedCurve specifica il riempimento dell'interno di una spline cardinale chiusa

```csharp
public sealed class EmfPlusFillClosedCurve : EmfPlusDrawingRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPlusFillClosedCurve](emfplusfillclosedcurve)(EmfPlusRecord) | Inizializza una nuova istanza di[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/brushid) { get; set; } | Ottiene o imposta l'identificatore del pennello Un numero intero senza segno a 32 bit che specifica EmfPlusBrush, il cui contenuto è determinato dal bit S nel campo Flags. Questo pennello viene utilizzato per riempire l'interno della spline cardinale chiusa. |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/compressed) { get; set; } | Ottiene o imposta un valore che indica se questo[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve)è compresso. Questo bit indica se il campo PointData specifica dati compressi. Se impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate intere a 16 bit. Se deselezionato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit. ---------------------- Un riempimento "tortuosa" l'operazione riempie le aree secondo la regola della "parità pari-dispari". Secondo questa regola, un punto di prova può essere determinato all'interno o all'esterno di una curva chiusa come segue: Disegna una linea dal punto di prova a un punto che è distante dalla curva. Se quella linea attraversa la curva un numero dispari di volte, il punto del test è all'interno della curva; in caso contrario, il punto di test è al di fuori della curva. --------------------- Un'operazione di riempimento "alternativo" riempie le aree secondo la regola "diverso da zero" . Secondo questa regola, un punto di prova può essere determinato all'interno o all'esterno di una curva chiusa come segue: Disegna una linea da un punto di prova a un punto che è distante dalla curva. Contare il numero di volte in cui la curva attraversa la linea di test da sinistra a destra e contare il numero di volte in cui la curva attraversa la linea di test da destra a sinistra. Se questi due numeri sono uguali, il punto di test è fuori dalla curva; in caso contrario, il punto di test è all'interno della curva. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record a 12 byte. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come deve essere eseguita l'operazione e sulla struttura del record. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/iscolor) { get; set; } | Ottiene o imposta un valore che indica se questa istanza è color. Se impostato, BrushId specifica un colore come oggetto EmfPlusARGB (sezione 2.2.2.1). Se deselezionato, BrushId contiene l'indice di un oggetto EmfPlusBrush (sezione 2.2.1.1). ) nella tabella oggetti EMF+. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/pointdata) { get; set; } | Ottiene o imposta il punto data Una matrice di punti Conteggio che specificano i punti finali delle linee che definiscono la spline. In una spline cardinale chiusa, la curva continua attraverso l'ultimo punto dell'array PointData e si collega al primo punto dell'array |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/relative) { get; set; } | Ottiene o imposta un valore che indica se questo[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve) è relativo. Questo bit indica se il campo PointData specifica posizioni relative o assolute. Se impostato, ogni elemento in PointData specifica una posizione nello spazio delle coordinate che è rispetto alla posizione specificata dall'elemento precedente nell'array. Nel caso del primo elemento in PointData, si assume una posizione precedente alle coordinate (0,0). Se azzerato, PointData specifica posizioni assolute in base al flag C. Nota Se questo flag è impostato, il flag C (sopra) non è definito e DEVE essere ignorato. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ottiene o imposta un numero intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte nell'intero record, inclusi l'intestazione del record a 12 byte ei dati specifici del record. |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/tension) { get; set; } | Ottiene o imposta tension Un valore a virgola mobile a 32 bit che specifica quanto strettamente si piega la spline mentre passa attraverso i punti. Un valore di 0,0 specifica che la spline è una sequenza di linee diritte . All'aumentare del valore, la curva diventa più arrotondata. Per ulteriori informazioni, vedi [SPLINE77] e [PETZOLD]. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |
| [Winding](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/winding) { get; set; } | Ottiene o imposta un valore che indica se questo[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve)is winding. Questo bit indica come eseguire l'operazione di riempimento. Se impostato, il riempimento è un riempimento "winding". Se è chiaro, il riempimento è un riempimento "alternativo". |

### Guarda anche

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
