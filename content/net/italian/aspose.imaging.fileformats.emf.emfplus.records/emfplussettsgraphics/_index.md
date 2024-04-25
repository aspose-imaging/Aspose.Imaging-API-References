---
title: EmfPlusSetTsGraphics
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EmfPlusSetTSGraphics specifica lo stato di un contesto di dispositivo grafico per un server terminal.
type: docs
weight: 6410
url: /it/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---
## EmfPlusSetTsGraphics class

Il record EmfPlusSetTSGraphics specifica lo stato di un contesto di dispositivo grafico per un server terminal.

```csharp
public sealed class EmfPlusSetTsGraphics : EmfPlusTerminalServerRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPlusSetTsGraphics](emfplussettsgraphics)(EmfPlusRecord) | Inizializza una nuova istanza di[`EmfPlusSetTsGraphics`](../emfplussettsgraphics) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AntiAliasMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/antialiasmode) { get; set; } | Ottiene o imposta un intero senza segno a 8 bit che specifica la qualità del rendering della linea, incluso il tipo di anti-aliasing della linea. DEVE essere definito nell'enumerazione SmoothingMode (sezione 2.1.1.28). |
| [BasicVgaColors](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/basicvgacolors) { get; } | Ottiene un valore che indica se [colori vga di base]. Se impostato, la tavolozza contiene solo i colori VGA di base. |
| [CompositingMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingmode) { get; set; } | Ottiene o imposta un intero senza segno a 8 bit che specifica in che modo i colori di origine vengono combinati con i colori di sfondo. DEVE essere un valore nell'enumerazione CompositingMode (sezione 2.1.1.5). |
| [CompositingQuality](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingquality) { get; set; } | Ottiene o imposta un numero intero senza segno a 8 bit che specifica il grado di levigatura da applicare a linee, curve e bordi di aree riempite per farle apparire più continue o nettamente definite. DEVE essere un valore nell'enumerazione CompositingQuality (sezione 2.1.1.6). |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che DEVE definire il numero allineato a 32 bit di byte di dati nel campo RecordData che segue. Questo numero non include l'intestazione del record a 12 byte. |
| [FilterType](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/filtertype) { get; set; } | Ottiene o imposta un intero senza segno a 8 bit che specifica come viene eseguito il ridimensionamento, inclusi lo stretching e il restringimento. DEVE essere un valore nell'enumerazione FilterType (sezione 2.1.1.11). |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che contiene informazioni per alcuni record su come deve essere eseguita l'operazione e sulla struttura del record. |
| [HavePalette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/havepalette) { get; } | Ottiene un valore che indica se [avere tavolozza]. Se impostato, questo record contiene un oggetto EmfPlusPalette (sezione 2.2.2.28) nel campo Tavolozza che segue i dati dello stato grafico. |
| [Palette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/palette) { get; set; } | Ottiene o imposta un oggetto EmfPlusPalette facoltativo. |
| [PixelOffset](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/pixeloffset) { get; set; } | Ottiene o imposta un intero senza segno a 8 bit che specifica la qualità complessiva dell'immagine e il processo di rendering del testo. DEVE essere un valore nell'enumerazione PixelOffsetMode (sezione 2.1.1.26). |
| [RenderOriginX](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginx) { get; set; } | Ottiene o imposta un numero intero con segno a 16 bit, che è la coordinata orizzontale dell'origine per il rendering di matrici di mezzitoni e dithering. |
| [RenderOriginY](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginy) { get; set; } | Ottiene o imposta un numero intero con segno a 16 bit, che è la coordinata verticale dell'origine per il rendering di matrici con mezzitoni e dithering. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ottiene o imposta un numero intero senza segno a 32 bit che specifica il numero allineato a 32 bit di byte nell'intero record, inclusi l'intestazione del record a 12 byte ei dati specifici del record. |
| [TextContrast](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textcontrast) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che specifica il valore di correzione gamma utilizzato per il rendering del testo con anti-alias e ClearType. Questo valore DEVE essere compreso tra 0 e 12 inclusi. |
| [TextRenderHint](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textrenderhint) { get; set; } | Ottiene o imposta un intero senza segno a 8 bit che specifica la qualità del rendering di text , incluso il tipo di anti-alias del testo. DEVE essere definito nell'enumerazione TextRenderingHint (sezione 2.1.1.32). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ottiene un intero senza segno a 16 bit che identifica il tipo di record. |
| [WorldToDevice](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/worldtodevice) { get; set; } | Ottiene o imposta un oggetto EmfPlusTransformMatrix a 192 bit (sezione 2.2.2.47) che specifica lo spazio mondiale per le trasformazioni dello spazio del dispositivo. |

### Guarda anche

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
