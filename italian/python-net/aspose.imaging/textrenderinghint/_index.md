---
title: "Enumerazione TextRenderingHint"
type: docs
weight: 11260
url: /it/python-net/aspose.imaging/textrenderinghint/
---

Specifica la qualità del rendering del testo.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.TextRenderingHint

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| ANTI_ALIAS | Ogni carattere è disegnato usando il suo bitmap di glifo antialiasato senza hinting. Qualità migliore grazie all'antialiasing. Le differenze di larghezza del gambo possono essere evidenti perché l'hinting è disattivato. |
| ANTI_ALIAS_GRID_FIT | Ogni carattere viene disegnato usando il suo bitmap del glifo antialiasato con hinting. Qualità molto migliore grazie all'antialiasing, ma a un costo di prestazioni più elevato. |
| CLEAR_TYPE_GRID_FIT | Ogni carattere viene disegnato usando il bitmap del glifo ClearType con hinting. L'impostazione di massima qualità. Utilizzato per sfruttare le funzionalità dei font ClearType. |
| SINGLE_BIT_PER_PIXEL | Ogni carattere viene disegnato usando il bitmap del glifo. L'hinting non è utilizzato. |
| SINGLE_BIT_PER_PIXEL_GRID_FIT | Ogni carattere viene disegnato usando il bitmap del glifo. L'hinting è usato per migliorare l'aspetto dei caratteri su steli e curvature. |
| SYSTEM_DEFAULT | Ogni carattere viene disegnato usando il bitmap del glifo, con il suggerimento di rendering predefinito del sistema. Il testo verrà disegnato utilizzando le impostazioni di smussatura dei font selezionate dall'utente per il sistema. |
