---
title: EmfPlusFillPolygon
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EmfPlusFillPolygon specifica il riempimento dellinterno di un poligono.
type: docs
weight: 6100
url: /it/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---
## EmfPlusFillPolygon class

Il record EmfPlusFillPolygon specifica il riempimento dell'interno di un poligono.

```csharp
public sealed class EmfPlusFillPolygon : EmfPlusDrawingRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPlusFillPolygon](emfplusfillpolygon)(EmfPlusRecord) | Inizializza una nuova istanza di[`EmfPlusFillPolygon`](../emfplusfillpolygon) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/brushid) { get; set; } | Ottiene o imposta l'identificatore del pennello Un numero intero senza segno a 32 bit che definisce il pennello, il cui contenuto è determinato dal bit S nel campo Flags. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record a 12 byte. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come deve essere eseguita l'operazione e sulla struttura del record. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/iscolor) { get; set; } | Ottiene o imposta un valore che indica se questa istanza è color. Se impostato, BrushId specifica un colore come oggetto EmfPlusARGB (sezione 2.2.2.1). Se deselezionato, BrushId contiene l'indice di un oggetto EmfPlusBrush (sezione 2.2.1.1) nella tabella oggetti EMF+. |
| [IsCompressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/iscompressed) { get; set; } | Ottiene o imposta un valore che indica se questa istanza è compressa. Se impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate intere a 16 bit. Se deselezionato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate in virgola mobile a 32 bit |
| [IsRelative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/isrelative) { get; set; } | Ottiene o imposta un valore che indica se questa istanza è relativa. Se impostato, ogni elemento in PointData specifica una posizione nello spazio delle coordinate che è relativa alla posizione specificata dall'elemento precedente nella matrice. Nel caso del primo elemento in PointData, si assume una precedente posizione alle coordinate (0,0). Se deselezionato, PointData specifica posizioni assolute in base al flag C |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/pointdata) { get; set; } | Ottiene o imposta il punto data Una matrice di punti Conteggio che definiscono i vertici del poligono. I primi due punti nell'array specificano il primo lato del poligono. Ogni punto aggiuntivo specifica un nuovo lato, i cui vertici includono il punto e il punto precedente. Se l'ultimo punto e il primo punto non coincidono, specificano l'ultimo lato del poligono. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ottiene o imposta un numero intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte nell'intero record, inclusi l'intestazione del record a 12 byte ei dati specifici del record. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |

### Guarda anche

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->