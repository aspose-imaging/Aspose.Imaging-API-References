---
title: EmfSetIcmProfileA
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EMR_SETICMPROFILEA specifica un profilo colore in un file con un nome composto da caratteri ASCII  per loutput grafico.
type: docs
weight: 4350
url: /it/net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/
---
## EmfSetIcmProfileA class

Il record EMR_SETICMPROFILEA specifica un profilo colore in un file con un nome composto da caratteri ASCII , per l'output grafico.

```csharp
public sealed class EmfSetIcmProfileA : EmfStateRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfSetIcmProfileA](emfseticmprofilea)(EmfRecord) | Inizializza una nuova istanza di[`EmfSetIcmProfileA`](../emfseticmprofilea) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CbData](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/cbdata) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati del profilo colore, se esso è contenuto nel campo Dati. |
| [CbName](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/cbname) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di byte nel nome ASCII del profilo colore desiderato. |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/data) { get; set; } | Ottiene o imposta un array di dimensioni (cbName + cbData) in byte, che specifica il nome ASCII e i dati grezzi del profilo colore desiderato. |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/dwflags) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che contiene i flag del profilo colore. |
| [Name](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/name) { get; } | Ottiene il nome |
| [RawData](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/rawdata) { get; } | Ottiene i dati grezzi |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ottiene o imposta la dimensione del record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ottiene o imposta il tipo. |

### Guarda anche

* class [EmfStateRecordType](../emfstaterecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
