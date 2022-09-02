---
title: EmfMaskBlt
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EMR_MASKBLT specifica un trasferimento a blocchi di pixel da una bitmap di origine a un rettangolo di destinazione opzionalmente in combinazione con un pattern di pennello e con lapplicazione di una bitmap maschera di colore in base alle operazioni raster in primo piano e sullo sfondo specificate.
type: docs
weight: 3800
url: /it/net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---
## EmfMaskBlt class

Il record EMR_MASKBLT specifica un trasferimento a blocchi di pixel da una bitmap di origine a un rettangolo di destinazione, opzionalmente in combinazione con un pattern di pennello e con l'applicazione di una bitmap maschera di colore, in base alle operazioni raster in primo piano e sullo sfondo specificate.

```csharp
public sealed class EmfMaskBlt : EmfBitmapRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfMaskBlt](emfmaskblt)(EmfRecord) | Inizializza una nuova istanza di[`EmfMaskBlt`](../emfmaskblt) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Argb32BkColorSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/argb32bkcolorsrc) { get; set; } | Ottiene o imposta un oggetto ColorRef WMF ([MS-WMF] sezione 2.2.2.8 che specifica il colore di sfondo della bitmap di origine. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/bounds) { get; set; } | Ottiene o imposta un oggetto RectL WMF ([MS-WMF] sezione 2.2.2.19) che definisce il rettangolo di delimitazione della destinazione in unità dispositivo. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/cxdest) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di destinazione. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/cydest) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di destinazione. |
| [MaskBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/maskbitmap) { get; set; } | Ottiene o imposta un buffer contenente le bitmap della maschera, che non devono essere contigue con la parte fissa del record EMR_MASKBLT o tra loro . Di conseguenza, i campi in questo buffer che sono etichettati "UndefinedSpace" sono facoltativi e DEVE essere ignorato. |
| [Rop4](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/rop4) { get; set; } | Ottiene o imposta un'operazione raster quaternaria, che specifica le operazioni raster ternarie per i colori di primo piano e di sfondo di una bitmap. Questi valori definiscono come i dati colore di il rettangolo di origine devono essere combinati con i dati colore del rettangolo di destinazione. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ottiene o imposta la dimensione del record |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/sourcebitmap) { get; set; } | Ottiene o imposta un buffer contenente le bitmap di origine, che non devono essere contigue con la parte fissa del record EMR_MASKBLT o tra loro . Di conseguenza, i campi in questo buffer che sono etichettati "UndefinedSpace" sono facoltativi e DEVE essere ignorato. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ottiene o imposta il tipo. |
| [UsageMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/usagemask) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tabella dei colori nell'intestazione della bitmap della maschera. Questo valore DEVE essere nell'enumerazione DIBColors. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/usagesrc) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tabella dei colori nell'intestazione della bitmap di origine. Questo valore DEVE essere nell'enumerazione DIBColors (sezione 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xdest) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x logica dell'angolo superiore sinistro del rettangolo di destinazione. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xformsrc) { get; set; } | Ottiene o imposta un oggetto XForm (sezione 2.2.28) che specifica una trasformazione da spazio globale a spazio pagina da applicare alla bitmap di origine. |
| [XMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xmask) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x logica dell'angolo superiore sinistro della bitmap della maschera. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xsrc) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x logica dell'angolo in alto a sinistra del rettangolo di origine. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ydest) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y logica dell'angolo superiore sinistro del rettangolo di destinazione. |
| [YMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ymask) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y logica dell'angolo superiore sinistro della bitmap della maschera. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ysrc) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y logica dell'angolo superiore sinistro del rettangolo di origine. |

### Guarda anche

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
