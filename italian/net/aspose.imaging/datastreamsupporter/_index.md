---
title: DataStreamSupporter
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il contenitore del flusso di dati.
type: docs
weight: 810
url: /it/net/aspose.imaging/datastreamsupporter/
---
## DataStreamSupporter class

Il contenitore del flusso di dati.

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Ottiene il flusso di dati dell'oggetto. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| abstract [IsCached](../../aspose.imaging/datastreamsupporter/iscached) { get; } | Ottiene un valore che indica se i dati dell'oggetto sono attualmente memorizzati nella cache e non è richiesta la lettura dei dati. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| abstract [CacheData](../../aspose.imaging/datastreamsupporter/cachedata)() | Memorizza i dati nella cache e garantisce che nessun ulteriore caricamento dei dati venga eseguito dal sottostante[`DataStreamContainer`](./datastreamcontainer) . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina l'istanza corrente. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save#save)() | Salva i dati dell'oggetto nella corrente[`DataStreamSupporter`](../datastreamsupporter) . |
| [Save](../../aspose.imaging/datastreamsupporter/save#save_1)(Stream) | Salva i dati dell'oggetto nel flusso specificato. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save#save_2)(string) | Salva i dati dell'oggetto nella posizione del file specificata. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save#save_3)(string, bool) | Salva i dati dell'oggetto nella posizione del file specificata. |

### Guarda anche

* class [DisposableObject](../disposableobject)
* spazio dei nomi [Aspose.Imaging](../../aspose.imaging)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
