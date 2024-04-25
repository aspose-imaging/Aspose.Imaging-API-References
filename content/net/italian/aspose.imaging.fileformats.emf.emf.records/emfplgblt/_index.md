---
title: EmfPlgBlt
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EMR_PLGBLT specifica un trasferimento a blocchi di pixel da una bitmap di origine a un parallelogramma di destinazione con lapplicazione di una bitmap di maschera a colori.
type: docs
weight: 3950
url: /it/aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---
## EmfPlgBlt class

Il record EMR_PLGBLT specifica un trasferimento a blocchi di pixel da una bitmap di origine a un parallelogramma di destinazione, con l'applicazione di una bitmap di maschera a colori.

```csharp
public sealed class EmfPlgBlt : EmfBitmapRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPlgBlt](emfplgblt)(EmfRecord) | Inizializza una nuova istanza di[`EmfPlgBlt`](../emfplgblt) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AptlDest](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/aptldest) { get; set; } | Ottiene o imposta una matrice di tre oggetti WMF PointL ([MS-WMF] sezione 2.2.2.15) che specifica tre angoli di un'area di destinazione del parallelogramma per il trasferimento a blocchi. L'angolo superiore sinistro del rettangolo di origine è mappato al primo punto in questa matrice, l'angolo in alto a destra al secondo punto e l'angolo in basso a sinistra al terzo punto. L'angolo inferiore destro del rettangolo di origine viene mappato al quarto punto implicito nel parallelogramma , che viene calcolato dai primi tre punti (A, B e C) trattandoli come vettori . D = B + C A |
| [BkSrcArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/bksrcargb32color) { get; set; } | Ottiene o imposta un oggetto ColorRef WMF ([MS-WMF] sezione 2.2.2.8) che specifica il colore di sfondo della bitmap di origine. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/bounds) { get; set; } | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che definisce il rettangolo di delimitazione , in unità dispositivo, per l'output nella destinazione. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/cxsrc) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di origine. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/cysrc) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di origine. |
| [MaskBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/maskbitmap) { get; set; } | Ottiene o imposta un buffer contenente la bitmap della maschera, che non deve essere contigua alla parte fissa del record EMR_PLGBLT o tra loro. Di conseguenza, i campi in questo buffer che sono etichettati "UndefinedSpace" sono opzionali e DEVONO essere ignorati. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ottiene o imposta la dimensione del record |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/sourcebitmap) { get; set; } | Ottiene o imposta un buffer contenente la bitmap di origine, che non deve essere contigua alla parte fissa del record EMR_PLGBLT o tra loro. Di conseguenza, i campi in questo buffer che sono etichettati "UndefinedSpace" sono opzionali e DEVONO essere ignorati. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ottiene o imposta il tipo. |
| [UsageMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/usagemask) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tabella dei colori nell'intestazione della bitmap della maschera. Questo valore DEVE essere nell'enumerazione DIBColors. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/usagesrc) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tabella dei colori nell'intestazione della bitmap di origine. Questo valore DEVE essere nell'enumerazione DIBColors |
| [XFormSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xformsrc) { get; set; } | Ottiene o imposta un oggetto XForm (sezione 2.2.28) che specifica una trasformazione da spazio globale a spazio pagina da applicare alla bitmap di origine. |
| [XMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xmask) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x logica dell'angolo superiore sinistro della bitmap della maschera. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xsrc) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x logica dell'angolo in alto a sinistra del rettangolo di origine. |
| [YMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/ymask) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y logica dell'angolo superiore sinistro della bitmap della maschera. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/ysrc) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y logica dell'angolo superiore sinistro del rettangolo di origine. |

### Guarda anche

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
