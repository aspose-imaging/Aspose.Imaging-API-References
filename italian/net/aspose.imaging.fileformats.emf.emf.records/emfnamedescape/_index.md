---
title: EmfNamedEscape
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record MR_NAMEDESCAPE trasmette informazioni arbitrarie a un driver della stampante specificato.
type: docs
weight: 3860
url: /it/net/aspose.imaging.fileformats.emf.emf.records/emfnamedescape/
---
## EmfNamedEscape class

Il record MR_NAMEDESCAPE trasmette informazioni arbitrarie a un driver della stampante specificato.

```csharp
public sealed class EmfNamedEscape : EmfEscapeRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfNamedEscape](emfnamedescape)(EmfRecord) | Inizializza una nuova istanza di[`EmfNamedEscape`](../emfnamedescape) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CjDriver](../../aspose.imaging.fileformats.emf.emf.records/emfnamedescape/cjdriver) { get; set; } | Ottiene o imposta Un numero intero senza segno a 32 bit che specifica il numero di byte nel campo DriverName . Questo valore DEVE essere un numero pari. |
| [CjIn](../../aspose.imaging.fileformats.emf.emf.records/emfnamedescape/cjin) { get; set; } | Ottiene o imposta Un numero intero senza segno a 32 bit che specifica il numero di byte da passare al driver della stampante. |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfnamedescape/data) { get; set; } | Ottiene o imposta i dati da passare al driver della stampante. DEVONO essere cjIn byte disponibili. |
| [DriverName](../../aspose.imaging.fileformats.emf.emf.records/emfnamedescape/drivername) { get; set; } | Ottiene o imposta Una stringa di caratteri Unicode a 16 bit che specifica il nome del driver della stampante che riceverà i dati. Questo valore DEVE essere cjDriver lungo byte e DEVE essere terminato con un carattere nullo. |
| [IEscape](../../aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype/iescape) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica l'escape del driver della stampante in execute. Questo DEVE essere uno dei valori nell'enumerazione WMF MetafileEscapes ([MSWMF] sezione 2.1.1.17). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ottiene o imposta la dimensione del record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ottiene o imposta il tipo. |

### Guarda anche

* class [EmfEscapeRecordType](../emfescaperecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->