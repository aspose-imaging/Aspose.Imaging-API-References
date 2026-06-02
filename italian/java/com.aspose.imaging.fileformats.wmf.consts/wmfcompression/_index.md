---
title: "WmfCompression"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione Compression specifica il tipo di compressione per un'immagine bitmap."
type: docs
weight: 16
url: /it/java/com.aspose.imaging.fileformats.wmf.consts/wmfcompression/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfCompression extends System.Enum
```

L'enumerazione Compression specifica il tipo di compressione per un'immagine bitmap.
## Campi

| Campo | Descrizione |
| --- | --- |
| [BI_RGB](#BI-RGB) | Il bitmap è in formato rosso verde blu (RGB) non compresso, che non è compresso e non utilizza maschere di colore. |
| [BI_RLE8](#BI-RLE8) | Un formato RGB che utilizza la compressione run-length encoding (RLE) per bitmap a 8 bit per pixel. |
| [BI_RLE4](#BI-RLE4) | Un formato RGB che utilizza la compressione RLE per bitmap a 4 bit per pixel. |
| [BI_BITFIELDS](#BI-BITFIELDS) | Il bitmap non è compresso e la tavola dei colori è composta da tre maschere di colore DWORD che specificano, rispettivamente, i componenti rosso, verde e blu di ciascun pixel. |
| [BI_JPEG](#BI-JPEG) | L'immagine è un'immagine JPEG, come specificato in [JFIF]. |
| [BI_PNG](#BI-PNG) | L'immagine è un'immagine PNG, come specificato in [RFC2083]. |
| [BI_CMYK](#BI-CMYK) | L'immagine è in formato CMYK non compresso. |
| [BI_CMYKRLE8](#BI-CMYKRLE8) | Un formato CMYK che utilizza la compressione RLE per bitmap a 8 bit per pixel. |
| [BI_CMYKRLE4](#BI-CMYKRLE4) | Un formato CMYK che utilizza la compressione RLE per bitmap a 4 bit per pixel. |
### BI_RGB {#BI-RGB}
```
public static final int BI_RGB
```


Il bitmap è in formato rosso verde blu (RGB) non compresso, che non è compresso e non utilizza maschere di colore.

### BI_RLE8 {#BI-RLE8}
```
public static final int BI_RLE8
```


Un formato RGB che utilizza la compressione run-length encoding (RLE) per bitmap a 8 bit per pixel. La compressione usa un formato a 2 byte composto da un byte di conteggio seguito da un byte contenente un indice di colore.

### BI_RLE4 {#BI-RLE4}
```
public static final int BI_RLE4
```


Un formato RGB che utilizza la compressione RLE per bitmap a 4 bit per pixel. La compressione usa un formato a 2 byte composto da un byte di conteggio seguito da due indici di colore a lunghezza word.

### BI_BITFIELDS {#BI-BITFIELDS}
```
public static final int BI_BITFIELDS
```


Il bitmap non è compresso e la tavola dei colori è composta da tre maschere di colore DWORD che specificano, rispettivamente, i componenti rosso, verde e blu di ciascun pixel. Questo è valido quando usato con bitmap a 16 e 32 bit per pixel.

### BI_JPEG {#BI-JPEG}
```
public static final int BI_JPEG
```


L'immagine è un'immagine JPEG, come specificato in [JFIF]. Questo valore DOVREBBE essere usato solo in alcune operazioni bitmap, come il pass-through JPEG. L'applicazione DEVE interrogare il supporto al pass-through, poiché non tutti i dispositivi supportano il pass-through JPEG. L'uso di bitmap non RGB PUÒ limitare la portabilità del metafile su altri dispositivi. Per esempio, i contesti dispositivo di visualizzazione generalmente non supportano questo pass-through

### BI_PNG {#BI-PNG}
```
public static final int BI_PNG
```


L'immagine è un'immagine PNG, come specificato in [RFC2083]. Questo valore DOVREBBE essere usato solo in alcune operazioni bitmap, come il pass-through JPEG/PNG. L'applicazione DEVE interrogare il supporto al pass-through, perché non tutti i dispositivi supportano il pass-through JPEG/PNG. L'uso di bitmap non RGB PUÒ limitare la portabilità del metafile su altri dispositivi. Per esempio, i contesti dispositivo di visualizzazione generalmente non supportano questo pass-through.

### BI_CMYK {#BI-CMYK}
```
public static final int BI_CMYK
```


L'immagine è in formato CMYK non compresso.

### BI_CMYKRLE8 {#BI-CMYKRLE8}
```
public static final int BI_CMYKRLE8
```


Un formato CMYK che utilizza la compressione RLE per bitmap a 8 bit per pixel. La compressione usa un formato a 2 byte composto da un byte di conteggio seguito da un byte contenente un indice di colore.

### BI_CMYKRLE4 {#BI-CMYKRLE4}
```
public static final int BI_CMYKRLE4
```


Un formato CMYK che utilizza la compressione RLE per bitmap a 4 bit per pixel. La compressione usa un formato a 2 byte composto da un byte di conteggio seguito da due indici di colore a lunghezza word.

