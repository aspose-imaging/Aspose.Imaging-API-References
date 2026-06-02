---
title: "Classe EmfPlusTintEffect"
type: docs
weight: 700
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustinteffect/
---

**Summary:** The TintEffect object specifies an addition of black or white to a specified hue in an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTintEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusTintEffect()](#EmfPlusTintEffect__1) | Initialise une nouvelle instance de la classe EmfPlusTintEffect |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| amount | int | r/w | Obtient ou définit un entier signé de 32 bits qui indique dans quelle mesure la teinte est renforcée ou affaiblie.<br/>            -100 ≤ valeur &lt; 0<br/>            Les valeurs négatives indiquent dans quelle mesure la teinte est affaiblie, ce qui équivaut à<br/>            l'ajout de noir.<br/>            0 Une valeur de 0 indique que la teinte NE DOIT PAS changer.<br/>            0 &lt; valeur ≤ 100<br/>            Les valeurs positives indiquent dans quelle mesure la teinte est renforcée, ce qui équivaut à<br/>            l'ajout de blanc. |
| teinte | int | r/w | Obtient ou définit un entier signé de 32 bits qui indique la teinte à laquelle l'effet de teinte est appliqué.<br/>            -180 ≤ valeur &lt; 0 <br/>            La couleur à une rotation anti-horaire spécifiée de la roue des couleurs, en partant<br/>            du bleu.<br/>            0 Une valeur de 0 indique la couleur bleue sur la roue des couleurs.<br/>            0 &lt; valeur ≤ 180<br/>            La couleur à une rotation horaire spécifiée de la roue des couleurs, en partant du bleu |


### Constructor: EmfPlusTintEffect() {#EmfPlusTintEffect__1}


```
 EmfPlusTintEffect() 
```

Initialise une nouvelle instance de la classe EmfPlusTintEffect

