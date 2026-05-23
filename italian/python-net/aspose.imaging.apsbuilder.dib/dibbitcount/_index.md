---
title: "Enumerazione DibBitCount"
type: docs
weight: 10
url: /it/python-net/aspose.imaging.apsbuilder.dib/dibbitcount/
---

L'enumerazione BitCount specifica il numero di bit che definiscono ogni pixel e<br/>                il numero massimo di colori in una bitmap indipendente dal dispositivo (DIB).

**Module:** [aspose.imaging.apsbuilder.dib](/imaging/python-net/aspose.imaging.apsbuilder.dib/)

**Full Name:** aspose.imaging.apsbuilder.dib.DibBitCount

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| BITCOUNT0 | Il numero di bit per pixel non è definito.<br/>                L'immagine DOVREBBE essere in formato JPEG o PNG.<br/>                Nessuno di questi formati include una tavola dei colori, quindi questo valore<br/>                specifica che non è presente alcuna tavola dei colori. Vedi [JFIF] e [RFC2083]<br/>                per ulteriori informazioni sui formati di compressione JPEG e PNG. |
| BITCOUNT1 | L'immagine è specificata con due colori. Ogni pixel nella bitmap è<br/>                rappresentato da un singolo bit. Se il bit è a 0, il pixel è<br/>                visualizzato con il colore della prima voce nella tavola dei colori;<br/>                se il bit è a 1, il pixel ha il colore della seconda voce nella tavola. |
| BITCOUNT2 | L'immagine è specificata con un massimo di 16 colori.<br/>                Ogni pixel nella bitmap è rappresentato da un indice a 4 bit nella<br/>                tavola dei colori, e ogni byte contiene 2 pixel. |
| BITCOUNT3 | L'immagine è specificata con un massimo di 256 colori.<br/>                Ogni pixel nella bitmap è rappresentato da un indice a 8 bit nella<br/>                tavola dei colori, e ogni byte contiene 1 pixel. |
| BITCOUNT4 | L'immagine è specificata con un massimo di 2^16 colori.<br/>                Ogni pixel nella bitmap è rappresentato da un valore a 16 bit. |
| BITCOUNT5 | La bitmap ha un massimo di 2^24 colori, e il campo Colors del DIB è NULL.<br/>                Ogni tripla di 3 byte nell'array bitmap rappresenta le intensità relative<br/>                di blu, verde e rosso, rispettivamente, per un pixel. La tavola dei colori Colors<br/>                è usata per ottimizzare i colori utilizzati sui dispositivi basati su palette, e DEVE contenere<br/>                il numero di voci specificato dal campo ColorUsed dell'oggetto BitmapInfoHeader Object |
| BITCOUNT6 | La bitmap ha un massimo di 2^24 colori |
