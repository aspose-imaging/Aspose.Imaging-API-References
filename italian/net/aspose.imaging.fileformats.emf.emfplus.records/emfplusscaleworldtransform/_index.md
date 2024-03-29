---
title: EmfPlusScaleWorldTransform
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EmfPlusScaleWorldTransform esegue un ridimensionamento sulla trasformazione dello spazio mondiale corrente.
type: docs
weight: 6260
url: /it/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/
---
## EmfPlusScaleWorldTransform class

Il record EmfPlusScaleWorldTransform esegue un ridimensionamento sulla trasformazione dello spazio mondiale corrente.

```csharp
public sealed class EmfPlusScaleWorldTransform : EmfPlusTerminalServerRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPlusScaleWorldTransform](emfplusscaleworldtransform)(EmfPlusRecord) | Inizializza una nuova istanza di[`EmfPlusScaleWorldTransform`](../emfplusscaleworldtransform) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record a 12 byte. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come deve essere eseguita l'operazione e sulla struttura del record. |
| [PostMultipliedMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/postmultipliedmatrix) { get; } | Ottiene un valore che indica se [postmoltiplicato matrice]. Se impostato, la matrice di trasformazione deve essere post-moltiplicata. Se chiaro, dovrebbe essere premoltiplicato. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ottiene o imposta un numero intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte nell'intero record, inclusi l'intestazione del record a 12 byte ei dati specifici del record. |
| [Sx](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/sx) { get; set; } | Ottiene o imposta un valore a virgola mobile a 32 bit che definisce il fattore di scala orizzontale. Lo scaling viene eseguito costruendo una nuova matrice di trasformazione dai valori dei campi Sx e Sy, come mostrato nella tabella seguente. ------------------ &#x7C; Sx &#x7C; 0 &#x7C; 0 &#x7C; &#x7C; 0 &#x7C; Sx &#x7C; 0 &#x7C; --- Figura 3: Matrice di trasformazione in scala |
| [Sy](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/sy) { get; set; } | Ottiene o imposta un valore a virgola mobile a 32 bit che definisce il fattore di scala verticale. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |

### Guarda anche

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
