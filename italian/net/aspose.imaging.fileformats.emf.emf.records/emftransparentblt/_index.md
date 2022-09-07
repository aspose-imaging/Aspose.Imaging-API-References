---
title: EmfTransparentBlt
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EMR_TRANSPARENTBLT specifica un trasferimento a blocchi di pixel da una bitmap di origine a un rettangolo di destinazione  trattando un colore specificato come trasparente allungando o comprimendo loutput per adattarlo alle dimensioni della destinazione se necessario
type: docs
weight: 4640
url: /it/net/aspose.imaging.fileformats.emf.emf.records/emftransparentblt/
---
## EmfTransparentBlt class

Il record EMR_TRANSPARENTBLT specifica un trasferimento a blocchi di pixel da una bitmap di origine a un rettangolo di destinazione , trattando un colore specificato come trasparente, allungando o comprimendo l'output per adattarlo alle dimensioni della destinazione, se necessario

```csharp
public sealed class EmfTransparentBlt : EmfBitmapRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfTransparentBlt](emftransparentblt)(EmfRecord) | Inizializza una nuova istanza di[`EmfTransparentBlt`](../emftransparentblt) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/bounds) { get; set; } | Ottiene o imposta un oggetto RectL WMF ([MS-WMF] sezione 2.2.2.19) che definisce il rettangolo di delimitazione della destinazione in unità dispositivo. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cxdest) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di destinazione. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cxsrc) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di origine. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cydest) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di destinazione. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cysrc) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di origine. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ottiene o imposta la dimensione del record |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/sourcebitmap) { get; set; } | Ottiene o imposta un buffer contenente la bitmap di origine, che non deve essere contigua alla parte fissa del record EMR_TRANSPARENTBLT. Di conseguenza, i campi in questo buffer che sono etichettati "UndefinedSpace" sono opzionali e DEVONO essere ignorati. |
| [SrcBkArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/srcbkargb32color) { get; set; } | Ottiene o imposta un oggetto ColorRef WMF che specifica il colore di sfondo della bitmap di origine. |
| [TransparentArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/transparentargb32color) { get; set; } | Ottiene o imposta un oggetto ColorRef WMF ([MS-WMF] sezione 2.2.2.8) che specifica il colore nella bitmap di origine da trattare come trasparente. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ottiene o imposta il tipo. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/usagesrc) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tabella dei colori nell'intestazione della bitmap di origine. Questo valore DEVE essere nell'enumerazione DIBColors (sezione 2.1.9) |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xdest) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x logica dell'angolo superiore sinistro del rettangolo di destinazione. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xformsrc) { get; set; } | Ottiene o imposta un oggetto XForm (sezione 2.2.28) che specifica una trasformazione da spazio globale a spazio pagina da applicare alla bitmap di origine. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xsrc) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x logica dell'angolo in alto a sinistra del rettangolo di origine. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/ydest) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y logica dell'angolo superiore sinistro del rettangolo di destinazione. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/ysrc) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y logica dell'angolo superiore sinistro del rettangolo di origine. |

### Guarda anche

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
