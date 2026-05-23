---
title: "Enumerazione EmfPlusTextRenderingHint"
type: docs
weight: 430
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/
---

L'enumerazione TextRenderingHint definisce i tipi di hinting del testo e anti-aliasing, che influenzano la qualità del rendering del testo.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusTextRenderingHint

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| TEXT_RENDERING_HINT_ANTIALIAS | Specifica che ogni carattere di testo viene disegnato usando il suo bitmap di glifo anti-aliasing senza hinting. Una migliore qualità deriva dall'anti-aliasing, ma le differenze di larghezza del tratto POTREBBERO essere evidenti perché l'hinting è disattivato. |
| TEXT_RENDERING_HINT_ANTIALIAS_GRID_FIT | Specifica che ogni carattere di testo DEVE essere disegnato usando il suo bitmap di glifo anti-aliasing con smoothing. Il rendering è di alta qualità grazie all'anti-aliasing, ma comporta un costo di prestazioni più elevato. |
| TEXT_RENDERING_HINT_CLEAR_TYPE_GRID_FIT | Specifica che ogni carattere di testo DEVE essere disegnato usando il suo bitmap di glifo ClearType con smoothing. Questa è l'impostazione di hinting testuale di massima qualità, utilizzata per sfruttare le funzionalità dei font ClearType. |
| TEXT_RENDERING_HINT_SINGLE_BIT_PER_PIXEL | Specifica che ogni carattere di testo DEVE essere disegnato usando il suo bitmap di glifo. Lo smoothing non viene utilizzato. |
| TEXT_RENDERING_HINT_SINGLE_BIT_PER_PIXEL_GRID_FIT | Specifica che ogni carattere di testo DEVE essere disegnato usando il suo bitmap del glifo. Lo smoothing POTREBBE essere usato per migliorare l'aspetto dei tratti e della curvatura dei glifi dei caratteri. |
| TEXT_RENDERING_HINT_SYSTEM_DEFAULT | Specifica che ogni carattere di testo DEVE essere disegnato usando le impostazioni di smoothing dei font configurate nel sistema operativo. |
