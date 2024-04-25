---
title: EmfAlphaBlend
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EMR_ALPHABLEND specifica un trasferimento a blocchi di pixel da una bitmap di origine a un rettangolo di destinazione  inclusi i dati di trasparenza alfa in base a unoperazione di fusione specificata.
type: docs
weight: 3200
url: /it/aspose.imaging.fileformats.emf.emf.records/emfalphablend/
---
## EmfAlphaBlend class

Il record EMR_ALPHABLEND specifica un trasferimento a blocchi di pixel da una bitmap di origine a un rettangolo di destinazione , inclusi i dati di trasparenza alfa, in base a un'operazione di fusione specificata.

```csharp
public sealed class EmfAlphaBlend : EmfBitmapRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfAlphaBlend](emfalphablend)(EmfRecord) | Inizializza una nuova istanza di[`EmfAlphaBlend`](../emfalphablend) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BkSrcArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/bksrcargb32color) { get; set; } | Ottiene o imposta un oggetto ColorRef WMF ([MS-WMF] sezione 2.2.2.8 che specifica il colore di sfondo della bitmap di origine. |
| [BlendFunction](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/blendfunction) { get; set; } | Ottiene o imposta una struttura che specifica le operazioni di fusione per le bitmap di origine e di destinazione |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/bounds) { get; set; } | Ottiene o imposta un oggetto RectL WMF ([MS-WMF] sezione 2.2.2.19) che definisce il rettangolo di delimitazione della destinazione in unità dispositivo. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cxdest) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di destinazione. Questo valore DEVE essere maggiore di zero. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cxsrc) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di origine. Questo valore DEVE essere maggiore di zero. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cydest) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di destinazione. Questo valore DEVE essere maggiore di zero. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cysrc) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di origine. Questo valore DEVE essere maggiore di zero. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ottiene o imposta la dimensione del record |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/sourcebitmap) { get; set; } | Ottiene o imposta un buffer contenente la bitmap di origine, che non deve essere contigua alla parte fissa del record EMR_ALPHABLEND. Di conseguenza, i campi in questo buffer che sono etichettati "UndefinedSpace" sono opzionali e DEVONO essere ignorati. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ottiene o imposta il tipo. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/usagesrc) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tabella dei colori nell'intestazione della bitmap di origine. Questo valore DEVE essere nell'enumerazione DIBColors (sezione 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/xdest) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x logica dell'angolo superiore sinistro del rettangolo di destinazione. |
| [XformSr](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/xformsr) { get; set; } | Ottiene o imposta un oggetto XForm (sezione 2.2.28) che specifica una trasformazione da spazio globale a spazio pagina da applicare alla bitmap di origine. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/xsrc) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x logica dell'angolo in alto a sinistra del rettangolo di origine. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/ydest) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y logica dell'angolo superiore sinistro del rettangolo di destinazione. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/ysrc) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y logica dell'angolo superiore sinistro del rettangolo di origine. |

### Guarda anche

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
