---
title: "Classe EmfPlusBlendFactors"
type: docs
weight: 90
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/
---

**Summary:** The EmfPlusBlendFactors object specifies positions and factors for the blend pattern of a gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendFactors

**Inheritance:** EmfPlusBlendBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusBlendFactors()](#EmfPlusBlendFactors__1) | Initialise une nouvelle instance de la classe EmfPlusBlendFactors |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blend_factors | float[] | r/w | Obtient ou définit un tableau de valeurs à virgule flottante 32 bits PositionCount qui <br/>            spécifient les proportions des couleurs aux positions définies dans le champ BlendPositions. <br/>            Chaque valeur DOIT être un nombre compris entre 0.0 et 1.0 inclus. |
| blend_positions | float[] | r/w | Obtient ou définit les positions de mélange<br/>            Un tableau de valeurs à virgule flottante 32 bits PositionCount<br/>             qui spécifient les proportions de distance le long de la ligne de dégradé.<br/>            Chaque élément DOIT être un nombre compris entre 0.0 et 1.0 inclus. <br/>            Pour un pinceau de dégradé linéaire, 0.0 représente le point de départ <br/>            et 1.0 représente le point d'arrivée. Pour un pinceau de dégradé de chemin, <br/>            0.0 représente le point médian et 1.0 représente un point final |


### Constructor: EmfPlusBlendFactors() {#EmfPlusBlendFactors__1}


```
 EmfPlusBlendFactors() 
```

Initialise une nouvelle instance de la classe EmfPlusBlendFactors

