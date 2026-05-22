---
title: "EmfPlusColorCurveEffect Class"
type: docs
weight: 180
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---

**Summary:** The ColorCurveEffect object specifies one of eight adjustments to the color curve of an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusColorCurveEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusColorCurveEffect()](#EmfPlusColorCurveEffect__1) | Initialise une nouvelle instance de la classe EmfPlusColorCurveEffect |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| adjustment_intensity | int | r/w | Obtient ou définit un entier signé 32 bits qui spécifie l'intensité de l'ajustement de la courbe au canal couleur spécifié par CurveChannel. Les plages de valeurs significatives pour ce champ varient selon la valeur de CurveAdjustment, comme suit :<br/>            Plage d'ajustement de l'exposition :<br/>            -255 ≤ value &lt; 0 À mesure que la valeur diminue, l'exposition de l'image DOIT diminuer.<br/>            0 Une valeur de 0 spécifie que l'exposition NE DOIT PAS changer.<br/>            0 &lt; value ≤ 255 À mesure que la valeur augmente, l'exposition de l'image DOIT augmenter.<br/>            Plage d'ajustement de la densité :<br/>            -255 ≤ value &lt; 0<br/>            À mesure que la valeur diminue, la densité de l'image DOIT diminuer, entraînant une image plus sombre.<br/>            0 Une valeur de 0 spécifie que la densité NE DOIT PAS changer.<br/>            0 &lt; value ≤ 255<br/>            À mesure que la valeur augmente, la densité de l'image DOIT augmenter.<br/>            Plage d'ajustement du contraste :<br/>            -100 ≤ value &lt; 0 À mesure que la valeur diminue, le contraste de l'image DOIT diminuer.<br/>            0 Une valeur de 0 spécifie que le contraste NE DOIT PAS changer.<br/>            0 &lt; value ≤ 100 À mesure que la valeur augmente, le contraste de l'image DOIT augmenter.<br/>            Plage d'ajustement des hautes lumières :<br/>            -100 ≤ value &lt; 0 À mesure que la valeur diminue, les zones claires de l'image DOIVENT apparaître plus sombres.<br/>            0 Une valeur de 0 spécifie que les hautes lumières NE DOIVENT PAS changer.<br/>            0 &lt; value ≤ 100 À mesure que la valeur augmente, les zones claires de l'image DOIVENT apparaître plus claires.<br/>            Plage d'ajustement des ombres :<br/>            -100 ≤ value &lt; 0 À mesure que la valeur diminue, les zones sombres de l'image DOIVENT apparaître plus sombres.<br/>            0 Une valeur de 0 spécifie que les ombres NE DOIVENT PAS changer.<br/>            0 &lt; value ≤ 100 À mesure que la valeur augmente, les zones sombres de l'image DOIVENT apparaître plus claires.<br/>            Plage d'ajustement de la saturation blanche :<br/>            0 — 255 À mesure que la valeur augmente, la limite supérieure de la plage d'intensités du canal couleur augmente.<br/>            Plage d'ajustement de la saturation noire :<br/>            0 — 255 À mesure que la valeur augmente, la limite inférieure de la plage d'intensités du canal couleur augmente. |
| curve_adjustment | [EmfPlusCurveAdjustments](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurveadjustments/) | r/w | Obtient ou définit un entier non signé 32 bits qui spécifie l'ajustement de la courbe à appliquer aux couleurs du bitmap. Cette valeur DOIT être définie dans l'énumération CurveAdjustments (section 2.1.1.7). |
| curve_channel | [EmfPlusCurveChannel](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurvechannel/) | r/w | Obtient ou définit un entier non signé 32 bits qui spécifie le canal couleur auquel l'ajustement de la courbe s'applique. Cette valeur DOIT être définie dans l'énumération CurveChannel (section 2.1.1.8). |


### Constructor: EmfPlusColorCurveEffect() {#EmfPlusColorCurveEffect__1}


```
 EmfPlusColorCurveEffect() 
```

Initialise une nouvelle instance de la classe EmfPlusColorCurveEffect

