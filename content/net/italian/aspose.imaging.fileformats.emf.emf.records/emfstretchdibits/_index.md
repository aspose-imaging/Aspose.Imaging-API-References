---
title: EmfStretchDiBits
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il record EMR_STRETCHDIBITS specifica un trasferimento a blocchi di pixel da una bitmap di origine a un rettangolo di destinazione  opzionalmente in combinazione con un pattern di pennello secondo unoperazione raster specificata allungando o comprimendo loutput per adattarlo alle dimensioni della destinazione se necessario.
type: docs
weight: 4600
url: /it/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---
## EmfStretchDiBits class

Il record EMR_STRETCHDIBITS specifica un trasferimento a blocchi di pixel da una bitmap di origine a un rettangolo di destinazione , opzionalmente in combinazione con un pattern di pennello, secondo un'operazione raster specificata, allungando o comprimendo l'output per adattarlo alle dimensioni della destinazione, se necessario.

```csharp
public sealed class EmfStretchDiBits : EmfBitmapRecordType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfStretchDiBits](emfstretchdibits)(EmfRecord) | Inizializza una nuova istanza di[`EmfStretchDiBits`](../emfstretchdibits) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BitBltRasterOperation](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/bitbltrasteroperation) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica un codice di un'operazione raster. Questi codici definiscono come combinare i dati del colore del rettangolo di origine con i dati del colore del rettangolo di destinazione e, opzionalmente, un motivo a pennello, per ottenere il colore finale. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/bounds) { get; set; } | Ottiene o imposta un oggetto RectL WMF ([MS-WMF] sezione 2.2.2.19) che definisce il rettangolo di delimitazione della destinazione in unità dispositivo. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cxdest) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di destinazione. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cxsrc) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza in pixel del rettangolo di origine. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cydest) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di destinazione. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cysrc) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza in pixel del rettangolo di origine. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ottiene o imposta la dimensione del record |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/sourcebitmap) { get; set; } | Ottiene o imposta un buffer contenente la bitmap di origine, che non deve essere contigua alla parte fissa del record EMR_STRETCHDIBITS. Di conseguenza, i campi in questo buffer che sono etichettati "UndefinedSpace" sono opzionali e DEVONO essere ignorati. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ottiene o imposta il tipo. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/usagesrc) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tabella dei colori nell'intestazione della bitmap di origine. Questo valore DEVE essere nell'enumerazione DIBColors (sezione 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/xdest) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x logica dell'angolo superiore sinistro del rettangolo di destinazione. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/xsrc) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x in pixel dell'angolo superiore sinistro del rettangolo di origine. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/ydest) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y logica dell'angolo superiore sinistro del rettangolo di destinazione. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/ysrc) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y in pixel dell'angolo superiore sinistro del rettangolo di origine. |

### Osservazioni

Questo record supporta immagini sorgente nei formati JPEG e PNG. Il campo Compressione nell'intestazione bitmap di origine specifica il formato dell'immagine. Se i segni dei campi di altezza e larghezza di origine e destinazione differiscono, questo record specifica una copia speculare della bitmap di origine nella destinazione. Cioè, se cxSrc e cxDest hanno segni diversi, viene specificata un'immagine speculare della bitmap di origine lungo l'asse x. Se cySrc e cyDest hanno segni diversi, viene specificata un'immagine speculare della bitmap di origine lungo l'asse y.

### Guarda anche

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
