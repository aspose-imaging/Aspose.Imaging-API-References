---
title: DibBitCount
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Lenumerazione BitCount specifica il numero di bit che definiscono ogni pixel e il numero massimo di colori in una bitmap indipendente dal dispositivo DIB.
type: docs
weight: 30
url: /it/net/aspose.imaging.apsbuilder.dib/dibbitcount/
---
## DibBitCount enumeration

L'enumerazione BitCount specifica il numero di bit che definiscono ogni pixel e il numero massimo di colori in una bitmap indipendente dal dispositivo (DIB).

```csharp
public enum DibBitCount : short
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Bitcount0 | `0` | Il numero di bit per pixel non è definito. L'immagine DOVREBBE essere in formato JPEG o PNG. Nessuno di questi formati include una tabella dei colori, quindi questo valore specifica che non è presente alcuna tabella dei colori. Vedere [JFIF] e [RFC2083] per ulteriori informazioni sui formati di compressione JPEG e PNG. |
| Bitcount1 | `1` | L'immagine è specificata con due colori. Ogni pixel nella bitmap è rappresentato da un singolo bit. Se il bit è chiaro, il pixel è visualizzato con il colore della prima voce nella tabella colori; se il bit è impostato, il pixel ha il colore della seconda voce nella tabella. |
| Bitcount2 | `4` | L'immagine è specificata con un massimo di 16 colori. Ogni pixel nella bitmap è rappresentato da un indice a 4 bit nella tabella dei colori e ogni byte contiene 2 pixel. |
| Bitcount3 | `8` | L'immagine è specificata con un massimo di 256 colori. Ogni pixel nella bitmap è rappresentato da un indice a 8 bit nella tabella dei colori e ogni byte contiene 1 pixel. |
| Bitcount4 | `16` | L'immagine è specificata con un massimo di 2^16 colori. Ogni pixel nella bitmap è rappresentato da un valore a 16 bit |
| Bitcount5 | `24` | La bitmap ha un massimo di 2^24 colori e il campo Colori di DIB è NULL. Ogni tripletta di 3 byte nell'array bitmap rappresenta le intensità relative di blu, verde e rosso, rispettivamente, per un pixel. La tabella colori Colors viene utilizzata per ottimizzare i colori utilizzati sui dispositivi basati su tavolozza e DEVE contenere il numero di voci specificato dal campo ColorUsed dell'oggetto BitmapInfoHeader |
| Bitcount6 | `32` | La bitmap ha un massimo di 2^24 colori |

### Guarda anche

* spazio dei nomi [Aspose.Imaging.ApsBuilder.Dib](../../aspose.imaging.apsbuilder.dib)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->