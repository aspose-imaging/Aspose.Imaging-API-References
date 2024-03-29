---
title: EmfPolyTextOutW
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EMR_POLYTEXTOUTW disegna una o più stringhe di testo Unicode utilizzando il font e i colori del testo correnti.
type: docs
weight: 4070
url: /it/net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/
---
## EmfPolyTextOutW class

Il record EMR_POLYTEXTOUTW disegna una o più stringhe di testo Unicode utilizzando il font e i colori del testo correnti.

```csharp
public sealed class EmfPolyTextOutW : EmfDrawingRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPolyTextOutW](emfpolytextoutw#constructor)() | Inizializza una nuova istanza di[`EmfPolyTextOutW`](../emfpolytextoutw) classe. |
| [EmfPolyTextOutW](emfpolytextoutw#constructor_1)(EmfRecord) | Inizializza una nuova istanza di[`EmfPolyTextOutW`](../emfpolytextoutw) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/bounds) { get; set; } | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19), che specifica il rettangolo di delimitazione in unità di dispositivo. |
| [ExScale](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/exscale) { get; set; } | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la scala X dalle unità della pagina a unità di .01 mm se la modalità grafica è GM_COMPATIBLE. |
| [EyScale](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/eyscale) { get; set; } | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la scala Y dalle unità di pagina a unità di .01 mm se la modalità grafica è GM_COMPATIBLE. |
| [IGraphicsMode](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/igraphicsmode) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità grafica corrente, dall'enumerazione GraphicsMode (sezione 2.1.16). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ottiene o imposta la dimensione del record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ottiene o imposta il tipo. |
| [WEmrText](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/wemrtext) { get; set; } | Ottiene o imposta una matrice di oggetti EmrText (sezione 2.2.5) che specificano le stringhe di output in caratteri Unicode UTF16-LE a 16 bit, con attributi di testo e valori di spaziatura. Il numero di oggetti EmrText è specificato da cStrings. |

### Osservazioni

I colori del carattere e del testo utilizzati per l'output sono specificati dalle proprietà nello stato corrente del contesto del dispositivo di riproduzione . EMR_POLYTEXTOUTW DOVREBBE essere emulato con una serie di record EMR_EXTTEXTOUTW (sezione 2.3.5.7), uno per stringa.

### Guarda anche

* class [EmfDrawingRecordType](../emfdrawingrecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
