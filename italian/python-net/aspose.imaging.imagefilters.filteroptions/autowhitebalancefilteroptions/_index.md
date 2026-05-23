---
title: "Classe AutoWhiteBalanceFilterOptions"
type: docs
weight: 20
url: /it/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/
---

**Summary:** Provides configuration options for the Auto White Balance filter.<br/>            Allows tuning of contrast stretching parameters and channel scaling<br/>            to improve the appearance of digital images.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.AutoWhiteBalanceFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset)](#AutoWhiteBalanceFilterOptions_low_percentile_target_high_percentile_target_value_max_scale_protected_dark_offset_1) | Inizializza una nuova istanza della classe [AutoWhiteBalanceFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| low_percentile | int | r | Il percentile basso per il punto nero, usato per la protezione delle zone scure (predefinito: 3). |
| max_scale | float | r | Ottiene il fattore di scala massimo per ogni canale.<br/>            Limita l'amplificazione di qualsiasi canale per evitare spostamenti di colore eccessivi. |
| protected_dark_offset | int | r | Offset dal percentile basso al di sotto del quale i pixel scuri non vengono allungati (protezione). |
| target_high_percentile | int | r | Ottiene il percentile alto target per lo stretching del contrasto.<br/>            Determina quale percentile di luminosità sarà mappato al valore target. |
| target_value | int | r | Ottiene il valore target per il percentile alto.<br/>            Questo valore sarà usato come riferimento bianco per lo stretching del contrasto. |


### Constructor: AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset) {#AutoWhiteBalanceFilterOptions_low_percentile_target_high_percentile_target_value_max_scale_protected_dark_offset_1}


```
 AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset) 
```

Inizializza una nuova istanza della classe [AutoWhiteBalanceFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| low_percentile | int | Il percentile basso per il punto nero, usato per la protezione delle zone scure (predefinito: 3). |
| target_high_percentile | int | Il percentile alto target per lo stretching del contrasto (predefinito 97). |
| target_value | int | Il valore target per il percentile alto (predefinito 255). |
| max_scale | float | Il fattore di scala massimo per ogni canale (predefinito 1.4f). |
| protected_dark_offset | int | Offset dal percentile basso al di sotto del quale i pixel scuri non vengono allungati (protezione). |

