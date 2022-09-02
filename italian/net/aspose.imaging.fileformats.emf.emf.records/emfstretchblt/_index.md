---
title: EmfStretchBlt
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EMR_STRETCHBLT specifica un trasferimento a blocchi di pixel da una bitmap di origine a un rettangolo di destinazione  opzionalmente in combinazione con un pattern di pennello secondo unoperazione raster specificata allungando o comprimendo loutput per adattarlo alle dimensioni della destinazione se necessario .
type: docs
weight: 4590
url: /it/net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/
---
## EmfStretchBlt class

Il record EMR_STRETCHBLT specifica un trasferimento a blocchi di pixel da una bitmap di origine a un rettangolo di destinazione , opzionalmente in combinazione con un pattern di pennello, secondo un'operazione raster specificata, allungando o comprimendo l'output per adattarlo alle dimensioni della destinazione, se necessario .

```csharp
public sealed class EmfStretchBlt : EmfBitmapRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfStretchBlt](emfstretchblt#constructor)() | Inizializza una nuova istanza di[`EmfStretchBlt`](../emfstretchblt) classe. |
| [EmfStretchBlt](emfstretchblt#constructor_1)(EmfRecord) | Inizializza una nuova istanza di[`EmfStretchBlt`](../emfstretchblt) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Argb32BkColorSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/argb32bkcolorsrc) { get; set; } | Ottiene o imposta un oggetto ColorRef WMF ([MS-WMF] sezione 2.2.2.8 che specifica il colore di sfondo della bitmap di origine. |
| [BitBltRasterOperation](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/bitbltrasteroperation) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica il codice dell'operazione raster . Questo codice definisce come combinare i dati del colore del rettangolo di origine con i dati del colore del rettangolo di destinazione e, facoltativamente, un motivo a pennello, per ottenere il colore finale |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/bounds) { get; set; } | Ottiene o imposta un oggetto RectL WMF ([MS-WMF] sezione 2.2.2.19) che definisce il rettangolo di delimitazione della destinazione in unità dispositivo. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cxdest) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di destinazione. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cxsrc) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di origine. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cydest) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di destinazione. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cysrc) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di origine. |
| [DestRect](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/destrect) { get; set; } | Ottiene o imposta il valore dest. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ottiene o imposta la dimensione del record |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/sourcebitmap) { get; set; } | Ottiene o imposta un buffer contenente la bitmap di origine, che non deve essere contigua alla parte fissa del record EMR_STRETCHBLT. Di conseguenza, i campi in questo buffer che sono etichettati "UndefinedSpace" sono opzionali e DEVONO essere ignorati. |
| [SrcRect](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/srcrect) { get; set; } | Ottiene o imposta la sorgente rect. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ottiene o imposta il tipo. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/usagesrc) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tabella dei colori nell'intestazione della bitmap di origine. Questo valore DEVE essere nell'enumerazione DIBColors (sezione 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xdest) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x logica dell'angolo superiore sinistro del rettangolo di destinazione. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xformsrc) { get; set; } | Ottiene o imposta un oggetto XForm (sezione 2.2.28) che specifica una trasformazione da spazio globale a spazio pagina da applicare alla bitmap di origine. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xsrc) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x logica dell'angolo in alto a sinistra del rettangolo di origine. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/ydest) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y logica dell'angolo superiore sinistro del rettangolo di destinazione. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/ysrc) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y logica dell'angolo superiore sinistro del rettangolo di origine. |

### Guarda anche

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
