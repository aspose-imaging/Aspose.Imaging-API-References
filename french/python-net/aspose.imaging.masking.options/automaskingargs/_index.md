---
title: "AutoMaskingArgs Classe"
type: docs
weight: 20
url: /fr/python-net/aspose.imaging.masking.options/automaskingargs/
---

**Summary:** Represents the arguments that are specified for automated masking methods

**Module:** [aspose.imaging.masking.options](/imaging/python-net/aspose.imaging.masking.options/)

**Full Name:** aspose.imaging.masking.options.AutoMaskingArgs

**Inheritance:** IMaskingArgs

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [AutoMaskingArgs()](#AutoMaskingArgs__1) | Initialise une nouvelle instance de la classe AutoMaskingArgs |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| max_iteration_number | int | r/w | Obtient ou définit le nombre maximal d'itérations. |
| number_of_objects | int | r/w | Obtient ou définit le nombre d'objets<br/>            pour séparer l'image initiale en (optionnel), la valeur par défaut est 2 (objet et arrière-plan). |
| objects_points | [Point[][]](/imaging/python-net/aspose.imaging/point[]/) | r/w | Obtient ou définit les points qui appartiennent aux objets séparés (optionnel)<br/>            coordonnées NumberOfObjects qui appartiennent aux objets NumberOfObjects de l'image initiale.<br/>            Ce paramètre est utilisé pour augmenter la précision de la méthode de segmentation. |
| objects_rectangles | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit les rectangles des objets qui appartiennent aux objets séparés (optionnel).<br/>            Ce paramètre est utilisé pour augmenter la précision de la méthode de segmentation. |
| orphaned_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Obtient ou définit les points qui n'appartiennent plus à aucun objet (optionnel).<br/>            Ce paramètre n'est utilisé que dans le cas d'une re-segmentation. |
| precision | float | r/w | Obtient ou définit la précision de la méthode de segmentation (optionnel). |


### Constructor: AutoMaskingArgs() {#AutoMaskingArgs__1}


```
 AutoMaskingArgs() 
```

Initialise une nouvelle instance de la classe AutoMaskingArgs

