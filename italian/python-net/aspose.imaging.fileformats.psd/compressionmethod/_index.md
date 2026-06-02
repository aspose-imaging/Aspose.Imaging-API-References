---
title: "Enumerazione CompressionMethod"
type: docs
weight: 20
url: /it/python-net/aspose.imaging.fileformats.psd/compressionmethod/
---

Definisce il metodo di compressione utilizzato per i dati dell'immagine.

**Module:** [aspose.imaging.fileformats.psd](/imaging/python-net/aspose.imaging.fileformats.psd/)

**Full Name:** aspose.imaging.fileformats.psd.CompressionMethod

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| RAW | Nessuna compressione. I dati dell'immagine sono memorizzati come byte grezzi in ordine planare RGBA.<br/>            Ciò significa che prima vengono scritti tutti i dati R, poi tutti i dati G, poi tutti i dati B e infine tutti i dati A. |
| RLE | Con compressione RLE i dati dell'immagine iniziano con i conteggi dei byte per tutte le linee di scansione (righe * canali), con ogni<br/>            conteggio memorizzato come valore a due byte. Seguono i dati compressi RLE, con ogni linea di scansione compressa separatamente.<br/>            La compressione RLE è lo stesso algoritmo di compressione utilizzato dalla routine PackBits del ROM Macintosh e dallo standard TIFF. |
| ZIP_WITHOUT_PREDICTION | ZIP senza predizione. |
| ZIP_WITH_PREDICTION | ZIP con predizione. |
