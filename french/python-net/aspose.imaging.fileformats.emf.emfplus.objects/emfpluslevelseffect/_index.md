---
title: "Classe EmfPlusLevelsEffect"
type: docs
weight: 420
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---

**Summary:** The LevelsEffect object specifies adjustments to the highlights, midtones, and shadows of an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLevelsEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusLevelsEffect()](#EmfPlusLevelsEffect__1) | Initialise une nouvelle instance de la classe EmfPlusLevelsEffect |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| mise en évidence | int | r/w | Obtient ou définit le spécifie combien éclaircir les hautes lumières d'une image. Les valeurs du canal couleur à l'extrémité supérieure de la plage d'intensité sont modifiées davantage que les valeurs proches du milieu ou des extrémités basses, ce qui signifie qu'une image peut être éclaircie sans perdre le contraste entre les parties plus sombres de l'image.<br/>            0 ≤ value &lt; Spécifie que les hautes lumières avec un pourcentage d'intensité supérieur à ce seuil DOIVENT être augmentées.<br/>            100 Spécifie que les hautes lumières NE DOIVENT PAS changer. |
| mid_tone | int | r/w | Obtient ou définit le spécifie combien éclaircir ou assombrir les tons moyens d'une image. Les valeurs du canal couleur au milieu de la plage d'intensité sont modifiées davantage que les valeurs proches des extrémités hautes ou basses, ce qui signifie qu'une image peut être éclaircie ou assombrie sans perdre le contraste entre les parties les plus sombres et les plus claires de l'image.<br/>            -100 ≤ value &lt; 0 Spécifie que les tons moyens sont rendus plus sombres.<br/>            0 Spécifie que les tons moyens NE DOIVENT PAS changer.<br/>            0 &lt; value ≤ 100 Spécifie que les tons moyens sont rendus plus clairs. |
| shadow | int | r/w | Obtient ou définit le spécifie combien assombrir les ombres d'une image. Les valeurs du canal couleur à l'extrémité basse de la plage d'intensité sont modifiées davantage que les valeurs proches du milieu ou des extrémités hautes, ce qui signifie qu'une image peut être assombrie sans perdre le contraste entre les parties plus claires de l'image.<br/>            0 Spécifie que les ombres NE DOIVENT PAS changer.<br/>            0 &lt; value ≤ 100<br/>            Spécifie que les ombres avec un pourcentage d'intensité inférieur à ce seuil sont rendues plus sombres. |


### Constructor: EmfPlusLevelsEffect() {#EmfPlusLevelsEffect__1}


```
 EmfPlusLevelsEffect() 
```

Initialise une nouvelle instance de la classe EmfPlusLevelsEffect

