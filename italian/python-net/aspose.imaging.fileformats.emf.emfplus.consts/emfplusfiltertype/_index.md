---
title: "Enumerazione EmfPlusFilterType"
type: docs
weight: 140
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/
---

L'enumerazione FilterType definisce i tipi di algoritmi di filtraggio che possono essere utilizzati per il miglioramento della qualità del testo e della grafica e per il rendering delle immagini.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusFilterType

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| FILTER_TYPE_BOX | Specifica un algoritmo di filtro a scatola, in cui ogni pixel di destinazione viene calcolato mediando un rettangolo di pixel sorgente. Questo algoritmo è utile solo quando si riduce le dimensioni di un'immagine. |
| FILTER_TYPE_GAUSSIAN_QUAD | Specifica che viene utilizzato un filtro gaussiano a 4 campioni, che crea un effetto di sfocatura su un'immagine. |
| FILTER_TYPE_LINEAR | Specifica che viene eseguita un'interpolazione lineare usando la media ponderata di un'area 2x2 di pixel intorno al pixel sorgente. |
| FILTER_TYPE_NONE | Specifica che il filtraggio non viene eseguito. |
| FILTER_TYPE_POINT | Specifica che ogni pixel di destinazione viene calcolato campionando il pixel più vicino dell'immagine sorgente. |
| FILTER_TYPE_PYRAMIDAL_QUAD | Specifica che viene utilizzato un filtro a tenda a 4 campioni. |
| FILTER_TYPE_TRIANGLE | Specifica che ogni pixel dell'immagine sorgente contribuisce in modo uguale all'immagine di destinazione. Questo è il più lento degli algoritmi di filtraggio. |
