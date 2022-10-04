---
title: EmfExtCreatePen
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EMR_EXTCREATEPEN definisce una penna logica estesa per le operazioni grafiche. È possibile specificare un DIB opzionale da utilizzare come stile di linea.
type: docs
weight: 3630
url: /it/net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/
---
## EmfExtCreatePen class

Il record EMR_EXTCREATEPEN definisce una penna logica estesa per le operazioni grafiche. È possibile specificare un DIB opzionale da utilizzare come stile di linea.

```csharp
public sealed class EmfExtCreatePen : EmfObjectCreationRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfExtCreatePen](emfextcreatepen#constructor)() | Inizializza una nuova istanza di[`EmfExtCreatePen`](../emfextcreatepen) classe. |
| [EmfExtCreatePen](emfextcreatepen#constructor_1)(EmfRecord) | Inizializza una nuova istanza di[`EmfExtCreatePen`](../emfextcreatepen) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BitmapBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/bitmapbuffer) { get; set; } | Ottiene o imposta un buffer opzionale contenente un DIB compresso sotto forma di oggetto WMF DeviceIndependentBitmap ([MS-WMF] sezione 2.2.2.9). Non è necessario che sia contiguo con la parte fissa del record EMR_EXTCREATEPEN |
| [Elp](../../aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/elp) { get; set; } | Ottiene o imposta un oggetto LogPenEx (sezione 2.2.20) che specifica una penna logica estesa con attributi che includono un array di stili di linea opzionale. |
| [IhPen](../../aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/ihpen) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto penna logica estesa nella tabella oggetti EMF (sezione 3.1.1.1). Questo indice DEVE essere salvato in modo che questo oggetto possa essere riutilizzato o modificato. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ottiene o imposta la dimensione del record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ottiene o imposta il tipo. |

### Guarda anche

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->