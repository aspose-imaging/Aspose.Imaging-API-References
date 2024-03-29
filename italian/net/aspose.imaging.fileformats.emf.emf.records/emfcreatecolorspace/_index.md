---
title: EmfCreateColorSpace
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EMR_CREATECOLORSPACE crea un oggetto spazio colore logico da un profilo colore con un nome composto da caratteri ASCII.
type: docs
weight: 3470
url: /it/net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/
---
## EmfCreateColorSpace class

Il record EMR_CREATECOLORSPACE crea un oggetto spazio colore logico da un profilo colore con un nome composto da caratteri ASCII.

```csharp
public sealed class EmfCreateColorSpace : EmfObjectCreationRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfCreateColorSpace](emfcreatecolorspace)(EmfRecord) | Inizializza una nuova istanza di[`EmfCreateColorSpace`](../emfcreatecolorspace) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [IhCS](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/ihcs) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto spazio colore logico nella tabella oggetti EMF (sezione 3.1.1.1). Questo indice DEVE essere salvato in modo che questo oggetto possa essere riutilizzato o modificato. |
| [Lcs](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/lcs) { get; set; } | Ottiene o imposta un oggetto LogColorSpace WMF ([MS-WMF] sezione 2.2.2.11), che può specificare il nome di un profilo colore in caratteri ASCII. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ottiene o imposta la dimensione del record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ottiene o imposta il tipo. |

### Osservazioni

L'oggetto spazio colore logico definito da questo record può essere selezionato nel contesto del dispositivo di riproduzione da un record EMR_SETCOLORSPACE (sezione 2.3.8.7), che definisce lo spazio colore logico da utilizzare in successive operazioni grafiche.

### Guarda anche

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
