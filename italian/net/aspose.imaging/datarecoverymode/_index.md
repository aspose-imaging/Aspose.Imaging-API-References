---
title: DataRecoveryMode
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: La modalità di recupero dati.
type: docs
weight: 800
url: /it/net/aspose.imaging/datarecoverymode/
---
## DataRecoveryMode enumeration

La modalità di recupero dati.

```csharp
public enum DataRecoveryMode
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | Non è implicito il recupero dei dati. Ogni volta che il formato del file ha dei dati danneggiati, viene generata l'eccezione appropriata. |
| ConsistentRecover | `1` | La modalità di ripristino coerente tenta di recuperare tutti i dati purché il danneggiamento non rompa il formato del file e consenta un'ulteriore elaborazione corretta. |
| MaximalRecover | `2` | La modalità di recupero massimo recupera tutti i dati anche se il formato del file ha una struttura danneggiata e un'ulteriore elaborazione potrebbe produrre effetti incustoditi. |

### Guarda anche

* spazio dei nomi [Aspose.Imaging](../../aspose.imaging)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->