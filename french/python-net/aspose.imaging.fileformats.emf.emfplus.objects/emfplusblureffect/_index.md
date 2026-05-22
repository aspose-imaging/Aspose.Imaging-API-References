---
title: "EmfPlusBlurEffect Classe"
type: docs
weight: 100
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---

**Summary:** The BlurEffect object specifies a decrease in the difference in intensity between pixels in an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlurEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusBlurEffect()](#EmfPlusBlurEffect__1) | Initialise une nouvelle instance de la classe EmfPlusBlurEffect |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blur_radius | float | r/w | Obtient ou définit un nombre à virgule flottante 32 bits qui spécifie le rayon du flou en pixels,<br/>            ce qui détermine le nombre de pixels impliqués dans le calcul de la nouvelle valeur d'un pixel donné.<br/>            Cette valeur DOIT être dans la plage de 0.0 à 255.0. |
| expand_edge | bool | r/w | Obtient ou définit une valeur booléenne 32 bits qui indique si le bitmap s'étend d'une quantité égale à la valeur du BlurRadius pour produire des bords doux. Cette valeur DOIT être<br/>            l'une des suivantes :<br/>            FALSE<br/>            0x00000000<br/>            La taille du bitmap NE DOIT PAS changer, et ses bords doux DEVRAIENT être découpés à<br/>            la taille du BlurRadius.<br/>            TRUE<br/>            0x00000001<br/>            La taille du bitmap DEVRAIT s'étendre d'une quantité égale au BlurRadius pour<br/>            produire des bords doux. |


### Constructor: EmfPlusBlurEffect() {#EmfPlusBlurEffect__1}


```
 EmfPlusBlurEffect() 
```

Initialise une nouvelle instance de la classe EmfPlusBlurEffect

