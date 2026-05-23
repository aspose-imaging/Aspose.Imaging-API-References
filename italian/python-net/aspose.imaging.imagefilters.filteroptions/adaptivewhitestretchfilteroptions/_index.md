---
title: "Classe AdaptiveWhiteStretchFilterOptions"
type: docs
weight: 10
url: /it/python-net/aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/
---

**Summary:** Provides options for configuring the Adaptive White Stretch filter.<br/>            Allows customization of histogram stretch parameters to enhance the white level<br/>            and improve the readability of faint-text or low-contrast document images.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.AdaptiveWhiteStretchFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale)](#AdaptiveWhiteStretchFilterOptions_is_grayscale_low_percentile_high_percentile_target_white_max_scale_1) | Inizializza una nuova istanza della classe [AdaptiveWhiteStretchFilter](/imaging/python-net/aspose.imaging.imagefilters/adaptivewhitestretchfilter/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| high_percentile | int | r | Ottiene il percentile superiore per il calcolo del punto bianco.<br/>            I valori dei pixel sopra questo percentile sono considerati bianchi durante lo stretching. |
| is_grayscale | bool | r | Ottiene un valore che indica se il filtro opera in modalità scala di grigi. |
| low_percentile | int | r | Ottiene il percentile inferiore per il calcolo del punto nero.<br/>            I valori dei pixel sotto questo percentile sono considerati neri durante lo stretching. |
| max_scale | float | r | Ottiene la scala di luminosità massima consentita.<br/>            Lo stretching effettivo non supererà questo fattore, per evitare un'eccessiva illuminazione. |
| target_white | int | r | Ottiene il valore bianco target che lo stretching mira a raggiungere. |


### Constructor: AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale) {#AdaptiveWhiteStretchFilterOptions_is_grayscale_low_percentile_high_percentile_target_white_max_scale_1}


```
 AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale) 
```

Inizializza una nuova istanza della classe [AdaptiveWhiteStretchFilter](/imaging/python-net/aspose.imaging.imagefilters/adaptivewhitestretchfilter/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| is_grayscale | bool | Indica se il filtro deve operare in modalità scala di grigi. |
| low_percentile | int | Percentile inferiore per il punto nero (es. 10). |
| high_percentile | int | Percentile superiore per il punto bianco (es. 90). |
| target_white | int | Valore bianco target (es. 240). |
| max_scale | float | Scala di luminosità massima consentita (es. 1.7). |

