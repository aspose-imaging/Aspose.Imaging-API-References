---
title: "Classe ClaheFilterOptions"
type: docs
weight: 50
url: /it/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/
---

**Summary:** Provides options for configuring the Contrast-Limited Adaptive Histogram Equalization (CLAHE) filter.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.ClaheFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit)](#ClaheFilterOptions_is_grayscale_tiles_number_horizontal_tiles_number_vertical_clip_limit_1) | Inizializza una nuova istanza della classe [ClaheFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/)<br/>            con i parametri specificati. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| clip_limit | float | r | Ottiene la soglia di limitazione del contrasto.<br/>            Valori più alti consentono più contrasto; valori più bassi limitano il miglioramento per evitare l'amplificazione del rumore. |
| is_grayscale | bool | r | Ottiene un valore che indica se il filtro opera in modalità scala di grigi. |
| tiles_number_horizontal | int | r | Restituisce il numero di tile nella direzione orizzontale.<br/>            Determina quante regioni l'immagine è divisa orizzontalmente per l'eguaglianza del contrasto locale. |
| tiles_number_vertical | int | r | Restituisce il numero di tile nella direzione verticale.<br/>            Determina quante regioni l'immagine è divisa verticalmente per l'eguaglianza del contrasto locale. |


### Constructor: ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit) {#ClaheFilterOptions_is_grayscale_tiles_number_horizontal_tiles_number_vertical_clip_limit_1}


```
 ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit) 
```

Inizializza una nuova istanza della classe [ClaheFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/)<br/>            con i parametri specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| is_grayscale | bool | Indica se il filtro deve operare in modalità scala di grigi. |
| tiles_number_horizontal | int | Numero di tile orizzontalmente. Il valore predefinito è 8. |
| tiles_number_vertical | int | Numero di tile verticalmente. Il valore predefinito è 8. |
| clip_limit | float | Soglia di limitazione del contrasto. Il valore predefinito è 4.0. |

