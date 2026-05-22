---
title: "AutoWhiteBalanceFilterOptions Classe"
type: docs
weight: 20
url: /fr/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/
---

**Summary:** Provides configuration options for the Auto White Balance filter.<br/>            Allows tuning of contrast stretching parameters and channel scaling<br/>            to improve the appearance of digital images.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.AutoWhiteBalanceFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset)](#AutoWhiteBalanceFilterOptions_low_percentile_target_high_percentile_target_value_max_scale_protected_dark_offset_1) | Initialise une nouvelle instance de la classe [AutoWhiteBalanceFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| low_percentile | int | r | Le percentile bas pour le point noir, utilisé pour la protection des tons sombres (par défaut : 3). |
| max_scale | float | r | Obtient le facteur d'échelle maximal pour chaque canal.<br/>            Limite l'amplification de tout canal afin d'éviter des décalages de couleur excessifs. |
| protected_dark_offset | int | r | Décalage depuis le percentile bas en dessous duquel les pixels sombres ne sont pas étirés (protection). |
| target_high_percentile | int | r | Obtient le percentile élevé cible pour l'étirement du contraste.<br/>            Détermine quel percentile de luminosité sera mappé à la valeur cible. |
| target_value | int | r | Obtient la valeur cible pour le percentile élevé.<br/>            Cette valeur sera utilisée comme référence blanche pour l'étirement du contraste. |


### Constructor: AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset) {#AutoWhiteBalanceFilterOptions_low_percentile_target_high_percentile_target_value_max_scale_protected_dark_offset_1}


```
 AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset) 
```

Initialise une nouvelle instance de la classe [AutoWhiteBalanceFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| low_percentile | int | Le percentile bas pour le point noir, utilisé pour la protection des tons sombres (par défaut : 3). |
| target_high_percentile | int | Le percentile élevé cible pour l'étirement du contraste (par défaut 97). |
| target_value | int | La valeur cible pour le percentile élevé (par défaut 255). |
| max_scale | float | Le facteur d'échelle maximal pour chaque canal (par défaut 1.4f). |
| protected_dark_offset | int | Décalage depuis le percentile bas en dessous duquel les pixels sombres ne sont pas étirés (protection). |

