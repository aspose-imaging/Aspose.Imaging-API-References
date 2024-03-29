---
title: EmfSetColorSpace
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EMR_SETCOLORSPACE definisce loggetto spazio colore logico corrente per le operazioni grafiche.
type: docs
weight: 4320
url: /it/net/aspose.imaging.fileformats.emf.emf.records/emfsetcolorspace/
---
## EmfSetColorSpace class

Il record EMR_SETCOLORSPACE definisce l'oggetto spazio colore logico corrente per le operazioni grafiche.

```csharp
public sealed class EmfSetColorSpace : EmfObjectManipulationRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfSetColorSpace](emfsetcolorspace)(EmfRecord) | Inizializza una nuova istanza di[`EmfSetColorSpace`](../emfsetcolorspace) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [IhCS](../../aspose.imaging.fileformats.emf.emf.records/emfsetcolorspace/ihcs) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice di un oggetto dello spazio colore logico nella tabella oggetti EMF (sezione 3.1.1.1). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ottiene o imposta la dimensione del record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ottiene o imposta il tipo. |

### Osservazioni

L'oggetto spazio colore logico definito da questo record DEVE essere utilizzato nelle operazioni di disegno che sono specificate dai record EMF successivi, fino a quando un oggetto spazio colore logico diverso non viene specificato da un altro record EMR_SETCOLORSPACE, oppure l'oggetto viene rimosso da un record EMR_DELETECOLORSPACE .

### Guarda anche

* class [EmfObjectManipulationRecordType](../emfobjectmanipulationrecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
