---
title: "Classe EmfPlusBlendColors"
type: docs
weight: 80
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/
---

**Summary:** The EmfPlusBlendColors object specifies positions and colors for the blend pattern of a gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendColors

**Inheritance:** EmfPlusBlendBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusBlendColors()](#EmfPlusBlendColors__1) | Initialise une nouvelle instance de la classe EmfPlusBlendColors |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blend_argb_32_colors | int[] | r/w | Obtient ou définit un tableau de PositionCount objets EmfPlusARGB (section 2.2.1.1) qui <br/>            spécifient les couleurs aux positions définies dans le champ BlendPositions. |
| blend_positions | float[] | r/w | Obtient ou définit les positions de mélange<br/>            Un tableau de valeurs à virgule flottante 32 bits PositionCount<br/>             qui spécifient les proportions de distance le long de la ligne de dégradé.<br/>            Chaque élément DOIT être un nombre compris entre 0.0 et 1.0 inclus. <br/>            Pour un pinceau de dégradé linéaire, 0.0 représente le point de départ <br/>            et 1.0 représente le point d'arrivée. Pour un pinceau de dégradé de chemin, <br/>            0.0 représente le point médian et 1.0 représente un point final |


### Constructor: EmfPlusBlendColors() {#EmfPlusBlendColors__1}


```
 EmfPlusBlendColors() 
```

Initialise une nouvelle instance de la classe EmfPlusBlendColors

