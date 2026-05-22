---
title: "Classe ClaheFilterOptions"
type: docs
weight: 50
url: /fr/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/
---

**Summary:** Provides options for configuring the Contrast-Limited Adaptive Histogram Equalization (CLAHE) filter.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.ClaheFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit)](#ClaheFilterOptions_is_grayscale_tiles_number_horizontal_tiles_number_vertical_clip_limit_1) | Initialise une nouvelle instance de la classe [ClaheFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/)<br/>            avec les paramètres spécifiés. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| clip_limit | float | r | Obtient le seuil de limitation du contraste.<br/>            Des valeurs plus élevées permettent plus de contraste ; des valeurs plus faibles limitent l'amélioration pour éviter l'amplification du bruit. |
| is_grayscale | bool | r | Obtient une valeur indiquant si le filtre fonctionne en mode niveaux de gris. |
| tiles_number_horizontal | int | r | Obtient le nombre de tuiles dans la direction horizontale.<br/>            Détermine combien de régions l'image est divisée horizontalement pour l'égalisation locale du contraste. |
| tiles_number_vertical | int | r | Obtient le nombre de tuiles dans la direction verticale.<br/>            Détermine combien de régions l'image est divisée verticalement pour l'égalisation locale du contraste. |


### Constructor: ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit) {#ClaheFilterOptions_is_grayscale_tiles_number_horizontal_tiles_number_vertical_clip_limit_1}


```
 ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit) 
```

Initialise une nouvelle instance de la classe [ClaheFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/)<br/>            avec les paramètres spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| is_grayscale | bool | Indique si le filtre doit fonctionner en mode niveaux de gris. |
| tiles_number_horizontal | int | Nombre de tuiles horizontalement. La valeur par défaut est 8. |
| tiles_number_vertical | int | Nombre de tuiles verticalement. La valeur par défaut est 8. |
| clip_limit | float | Seuil de limitation du contraste. La valeur par défaut est 4.0. |

