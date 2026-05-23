---
title: "StretchMode Enumerazione"
type: docs
weight: 10
url: /it/python-net/aspose.imaging.fileformats.wmf.consts/stretchmode/
---

L'Enumerazione [StretchMode](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/stretchmode/) specifica la modalità di stretching del bitmap,<br/>                che definisce come il sistema combina righe o colonne<br/>                di un bitmap con i pixel esistenti.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.StretchMode

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| BLACK_ON_WHITE | Esegue un'operazione Boolean AND utilizzando i valori di colore per i<br/>                pixel eliminati ed esistenti. Se il bitmap è un bitmap monocromatico<br/>                questa modalità preserva i pixel neri a spese dei pixel bianchi<br/>                pixels |
| COLOR_ON_COLOR | Elimina i pixel. Questa modalità elimina tutte le linee di pixel eliminate<br/>                senza cercare di preservare le loro informazioni. |
| HALF_TONE | Mappa i pixel dal rettangolo di origine in blocchi di pixel nel<br/>                rettangolo di destinazione. Il colore medio sul blocco di destinazione<br/>                dei pixel approssima il colore dei pixel di origine. |
| WHITE_ON_BLACK | Esegue un'operazione Boolean OR usando i valori di colore per i pixel<br/>                eliminati ed esistenti. Se il bitmap è monocromatico<br/>                questa modalità conserva i pixel bianchi a spese dei pixel neri<br/>                . |
