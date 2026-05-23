---
title: "Enumerazione WmfCompression"
type: docs
weight: 70
url: /it/python-net/aspose.imaging.fileformats.wmf.consts/wmfcompression/
---

L'Enumerazione Compression specifica il tipo di compressione per un'immagine bitmap

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfCompression

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| BI_BITFIELDS | Il bitmap non è compresso e la tavola dei colori è composta da tre maschere di colore DWORD che<br/>                specificano rispettivamente le componenti rosso, verde e blu di ogni pixel.<br/>                Questo è valido quando si utilizza bitmap a 16 e 32 bit per pixel. |
| BI_CMYK | L'immagine è in formato CMYK non compresso. |
| BI_CMYKRLE4 | Un formato CMYK che utilizza la compressione RLE per bitmap a 4 bit per pixel.<br/>                La compressione utilizza un formato a 2 byte composto da un byte di conteggio seguito da due indici di colore a lunghezza di word. |
| BI_CMYKRLE8 | Un formato CMYK che utilizza la compressione RLE per bitmap a 8 bit per pixel.<br/>                La compressione utilizza un formato a 2 byte composto da un byte di conteggio seguito da un byte contenente un indice di colore. |
| BI_JPEG | L'immagine è un'immagine JPEG, come specificato in [JFIF]. Questo valore DEVE essere utilizzato solo in alcune operazioni bitmap,<br/>                come il pass-through JPEG. L'applicazione DEVE interrogare il supporto al pass-through,<br/>                poiché non tutti i dispositivi supportano il pass-through JPEG. L'uso di bitmap non RGB PUÒ limitare la portabilità<br/>                del metafile su altri dispositivi. Per esempio, i contesti dispositivo di visualizzazione generalmente non supportano questo pass-through |
| BI_PNG | L'immagine è un'immagine PNG, come specificato in [RFC2083]. Questo valore DEVE essere utilizzato in alcune operazioni bitmap,<br/>                come il pass-through JPEG/PNG. L'applicazione DEVE interrogare il supporto al pass-through, perché non tutti i dispositivi<br/>                supportano il pass-through JPEG/PNG. L'uso di bitmap non RGB PUÒ limitare la portabilità del metafile su altri dispositivi.<br/>                Per esempio, i contesti dispositivo di visualizzazione generalmente non supportano questo pass-through. |
| BI_RGB | Il bitmap è in formato rosso verde blu (RGB) non compresso, che non è compresso e non utilizza maschere di colore. |
| BI_RLE4 | Un formato RGB che utilizza la compressione RLE per bitmap a 4 bit per pixel.<br/>                La compressione utilizza un formato a 2 byte composto da un byte di conteggio seguito da due indici di colore a lunghezza di word |
| BI_RLE8 | Un formato RGB che utilizza la codifica run-length (RLE) per bitmap a 8 bit per pixel.<br/>                La compressione utilizza un formato a 2 byte composto da un byte di conteggio seguito da un byte contenente un indice di colore. |
