---
title: "CompressionMethod"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Definisce il metodo di compressione utilizzato per i dati dell'immagine."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.fileformats.psd/compressionmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CompressionMethod extends System.Enum
```

Definisce il metodo di compressione utilizzato per i dati dell'immagine.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Raw](#Raw) | Nessuna compressione. |
| [RLE](#RLE) | I dati dell'immagine compressi con RLE iniziano con i conteggi dei byte per tutte le linee di scansione (righe \* canali), con ogni conteggio memorizzato come valore a due byte. |
| [ZipWithoutPrediction](#ZipWithoutPrediction) | ZIP senza predizione. |
| [ZipWithPrediction](#ZipWithPrediction) | ZIP con predizione. |
### Raw {#Raw}
```
public static final short Raw
```


Nessuna compressione. I dati dell'immagine sono memorizzati come byte grezzi in ordine planare RGBA. Ciò significa che prima vengono scritti tutti i dati R, poi tutti i dati G, poi tutti i dati B e infine tutti i dati A.

### RLE {#RLE}
```
public static final short RLE
```


I dati dell'immagine compressi con RLE iniziano con i conteggi dei byte per tutte le linee di scansione (righe \* canali), con ogni conteggio memorizzato come valore a due byte. Seguono i dati compressi RLE, con ogni linea di scansione compressa separatamente. La compressione RLE è lo stesso algoritmo di compressione usato dalla routine PackBits della ROM Macintosh e dallo standard TIFF.

### ZipWithoutPrediction {#ZipWithoutPrediction}
```
public static final short ZipWithoutPrediction
```


ZIP senza predizione.

### ZipWithPrediction {#ZipWithPrediction}
```
public static final short ZipWithPrediction
```


ZIP con predizione.

