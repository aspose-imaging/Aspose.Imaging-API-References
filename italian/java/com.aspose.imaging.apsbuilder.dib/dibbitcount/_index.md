---
title: "DibBitCount"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione BitCount specifica il numero di bit che definiscono ogni pixel e il numero massimo di colori in un bitmap indipendente dal dispositivo (DIB)."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.apsbuilder.dib/dibbitcount/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DibBitCount extends System.Enum
```

L'enumerazione BitCount specifica il numero di bit che definiscono ogni pixel e il numero massimo di colori in un bitmap indipendente dal dispositivo (DIB).
## Campi

| Campo | Descrizione |
| --- | --- |
| [BIT_COUNT_0](#BIT-COUNT-0) | Il numero di bit per pixel non è definito. |
| [BIT_COUNT_1](#BIT-COUNT-1) | L'immagine è specificata con due colori. Ogni pixel nel bitmap è rappresentato da un singolo bit. |
| [BIT_COUNT_2](#BIT-COUNT-2) | L'immagine è specificata con un massimo di 16 colori. |
| [BIT_COUNT_3](#BIT-COUNT-3) | L'immagine è specificata con un massimo di 256 colori. |
| [BIT_COUNT_4](#BIT-COUNT-4) | L'immagine è specificata con un massimo di 2^16 colori. |
| [BIT_COUNT_5](#BIT-COUNT-5) | Il bitmap ha un massimo di 2^24 colori e il campo Colors del DIB è NULL. |
| [BIT_COUNT_6](#BIT-COUNT-6) | Il bitmap ha un massimo di 2^24 colori |
### BIT_COUNT_0 {#BIT-COUNT-0}
```
public static final short BIT_COUNT_0
```


Il numero di bit per pixel è indefinito. L'immagine DOVREBBE essere in formato JPEG o PNG. Nessuno di questi formati include una tavola dei colori, quindi questo valore specifica che non è presente alcuna tavola dei colori. Vedi [JFIF] e [RFC2083] per ulteriori informazioni sui formati di compressione JPEG e PNG.

### BIT_COUNT_1 {#BIT-COUNT-1}
```
public static final short BIT_COUNT_1
```


L'immagine è specificata con due colori. Ogni pixel nel bitmap è rappresentato da un singolo bit. Se il bit è a 0, il pixel viene visualizzato con il colore della prima voce nella tavola dei colori; se il bit è a 1, il pixel ha il colore della seconda voce nella tavola.

### BIT_COUNT_2 {#BIT-COUNT-2}
```
public static final short BIT_COUNT_2
```


L'immagine è specificata con un massimo di 16 colori. Ogni pixel nel bitmap è rappresentato da un indice a 4 bit nella tavola dei colori, e ogni byte contiene 2 pixel.

### BIT_COUNT_3 {#BIT-COUNT-3}
```
public static final short BIT_COUNT_3
```


L'immagine è specificata con un massimo di 256 colori. Ogni pixel nel bitmap è rappresentato da un indice a 8 bit nella tavola dei colori, e ogni byte contiene 1 pixel.

### BIT_COUNT_4 {#BIT-COUNT-4}
```
public static final short BIT_COUNT_4
```


L'immagine è specificata con un massimo di 2^16 colori. Ogni pixel nel bitmap è rappresentato da un valore a 16 bit.

### BIT_COUNT_5 {#BIT-COUNT-5}
```
public static final short BIT_COUNT_5
```


Il bitmap ha un massimo di 2^24 colori, e il campo Colors del DIB è NULL. Ogni tripla di 3 byte nell'array bitmap rappresenta le intensità relative di blu, verde e rosso, rispettivamente, per un pixel. La tavola dei colori Colors è usata per ottimizzare i colori utilizzati sui dispositivi basati su palette, e DEVE contenere il numero di voci specificato dal campo ColorUsed dell'oggetto BitmapInfoHeader Object

### BIT_COUNT_6 {#BIT-COUNT-6}
```
public static final short BIT_COUNT_6
```


Il bitmap ha un massimo di 2^24 colori

