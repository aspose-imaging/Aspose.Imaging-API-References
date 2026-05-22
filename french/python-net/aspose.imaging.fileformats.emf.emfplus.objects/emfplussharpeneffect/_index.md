---
title: "EmfPlusSharpenEffect Classe"
type: docs
weight: 630
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplussharpeneffect/
---

**Summary:** The SharpenEffect object specifies an increase in the difference in intensity between pixels in an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusSharpenEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSharpenEffect()](#EmfPlusSharpenEffect__1) | Initialise une nouvelle instance de la classe EmfPlusSharpenEffect |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| amount | float | r/w | Obtient ou définit un nombre à virgule flottante de 32 bits qui spécifie la différence d'intensité<br/>            entre un pixel donné et les pixels environnants.<br/>            0 indique que le renforcement NE DOIT PAS être effectué.<br/>            0 &lt; valeur ≤ 100<br/>            À mesure que cette valeur augmente, la différence d'intensité entre les pixels DEVRAIT<br/>            augmenter. |
| rayon | float | r/w | Obtient ou définit un nombre à virgule flottante de 32 bits qui spécifie le rayon de netteté en pixels,<br/>            ce qui détermine le nombre de pixels impliqués dans le calcul de la nouvelle valeur d'un pixel donné.<br/>            À mesure que cette valeur augmente, le nombre de pixels impliqués dans le calcul augmente, et le<br/>            bitmap résultant DOIT devenir plus net. |


### Constructor: EmfPlusSharpenEffect() {#EmfPlusSharpenEffect__1}


```
 EmfPlusSharpenEffect() 
```

Initialise une nouvelle instance de la classe EmfPlusSharpenEffect

