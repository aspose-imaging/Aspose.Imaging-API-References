---
title: EmfPlusRotateWorldTransform
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EmfPlusRotateWorldTransform esegue una rotazione sulla trasformazione dello spazio mondiale corrente.
type: docs
weight: 6240
url: /it/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/
---
## EmfPlusRotateWorldTransform class

Il record EmfPlusRotateWorldTransform esegue una rotazione sulla trasformazione dello spazio mondiale corrente.

```csharp
public sealed class EmfPlusRotateWorldTransform : EmfPlusTerminalServerRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPlusRotateWorldTransform](emfplusrotateworldtransform)(EmfPlusRecord) | Inizializza una nuova istanza di[`EmfPlusRotateWorldTransform`](../emfplusrotateworldtransform) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Angle](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/angle) { get; set; } | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica l'angolo di rotazione in gradi. L'operazione viene eseguita costruendo una nuova matrice di trasformazione dal diagramma seguente: ------------ ---------------------- &#x7C; sin(Angolo) &#x7C; cos(Angolo) &#x7C; 0 &#x7C; &#x7C; cos(Angolo) &#x7C; sin(Angolo) &#x7C; 0 &#x7C; ---------------------------------- Figura 2: Matrice di trasformazione di rotazione L'attuale trasformazione dello spazio mondiale viene moltiplicata da questa matrice, e il risultato diventa la nuova trasformazione dello spazio mondiale attuale. Il campo Flags determina l'ordine di moltiplicazione. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record a 12 byte. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come deve essere eseguita l'operazione e sulla struttura del record. |
| [PostMultipliedMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/postmultipliedmatrix) { get; } | Ottiene un valore che indica se [postmoltiplicato matrice]. Se impostato, la matrice di trasformazione deve essere postmoltiplicata. Se chiaro, dovrebbe essere premoltiplicato. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ottiene o imposta un numero intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte nell'intero record, inclusi l'intestazione del record a 12 byte ei dati specifici del record. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |

### Guarda anche

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
