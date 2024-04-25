---
title: EmfHeaderExtension2
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Loggetto HeaderExtension2 definisce la seconda estensione dellintestazione del metafile EMF. Aggiunge la capacità di misurare le superfici del dispositivo in micrometri che migliora la risoluzione e la scalabilità dei metafile EMF.
type: docs
weight: 3000
url: /it/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/
---
## EmfHeaderExtension2 class

L'oggetto HeaderExtension2 definisce la seconda estensione dell'intestazione del metafile EMF. Aggiunge la capacità di misurare le superfici del dispositivo in micrometri, che migliora la risoluzione e la scalabilità dei metafile EMF.

```csharp
public sealed class EmfHeaderExtension2 : EmfHeaderObject
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfHeaderExtension2](emfheaderextension2)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bounds) { get; set; } | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica i limiti inclusivi e rettangolari nelle unità del dispositivo del rettangolo più piccolo che può essere disegnato attorno all'immagine memorizzata in il metafile |
| [Bytes](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bytes) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione del metafile, in byte. |
| [Device](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/device) { get; set; } | Ottiene o imposta un oggetto SizeL WMF ([MS-WMF] sezione 2.2.2.22) che specifica la dimensione del dispositivo di riferimento, in pixel |
| [Frame](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/frame) { get; set; } | Ottiene o imposta un oggetto WMF RectL che specifica le dimensioni rettangolari inclusive, in unità di 0,01 millimetri, di un rettangolo che circonda l'immagine archiviata nel metafile |
| [Handles](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/handles) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che specifica il numero di oggetti grafici che verranno utilizzati durante l'elaborazione del metafile |
| [MicrometersX](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/micrometersx) { get; set; } | Ottiene o imposta la dimensione orizzontale a 32 bit del dispositivo di visualizzazione per cui è stata generata l'immagine del metafile, in micrometri |
| [MicrometersY](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/micrometersy) { get; set; } | Ottiene o imposta la dimensione verticale a 32 bit del dispositivo di visualizzazione per cui è stata generata l'immagine del metafile, in micrometri. |
| [Millimeters](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/millimeters) { get; set; } | Ottiene o imposta un oggetto SizeL WMF che specifica la dimensione del dispositivo di riferimento, in millimetri |
| [NDesription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/ndesription) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di caratteri nella matrice che contiene la descrizione del contenuto del metafile. Questo è zero se non c'è una stringa di descrizione. |
| [NPalEntries](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/npalentries) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di voci nella tavolozza del metafile. La tavolozza si trova nel record EMR_EOF |
| [OffDescription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/offdescription) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica l'offset dall'inizio di questo record all'array che contiene la descrizione del contenuto del metafile |
| [Records](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/records) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di record nel metafile |
| [RecordSignature](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/recordsignature) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica la firma del record. Questo DEVE essere ENHMETA_SIGNATURE, dall'enumerazione FormatSignature (sezione 2.1.14). |
| [Reserved](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/reserved) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che DEVE essere 0x0000 e DEVE essere ignorato |
| [Valid](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/valid) { get; } | Ottiene un valore che indica se questo[`EmfHeaderObject`](../emfheaderobject)è valido. |
| [Version](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/version) { get; set; } | Ottiene o imposta la versione (4 byte): un numero intero senza segno a 32 bit che specifica l'interoperabilità del metafile EMF. Questo DOVREBBE essere 0x00010000 |

### Guarda anche

* class [EmfHeaderObject](../emfheaderobject)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
