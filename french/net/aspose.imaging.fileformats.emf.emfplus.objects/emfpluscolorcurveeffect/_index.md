---
title: EmfPlusColorCurveEffect
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lobjet ColorCurveEffect spécifie lun des huit ajustements de la courbe de couleur dune image.
type: docs
weight: 5300
url: /fr/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---
## EmfPlusColorCurveEffect class

L'objet ColorCurveEffect spécifie l'un des huit ajustements de la courbe de couleur d'une image.

```csharp
public sealed class EmfPlusColorCurveEffect : EmfPlusImageEffectsObjectType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfPlusColorCurveEffect](emfpluscolorcurveeffect)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [AdjustmentIntensity](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/adjustmentintensity) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie l'intensité de l'ajustement de la courbe the au canal de couleur spécifié par CurveChannel. Les plages de valeurs significatives pour ce champ varient en fonction de la valeur CurveAdjustment, comme suit : Plage de réglage de l'exposition : -255 ≤ valeur &lt; 0 Lorsque la valeur diminue, l'exposition de l'image DEVRAIT diminuer. 0 Une valeur de 0 spécifie que l'exposition NE DOIT PAS changer. 0 &lt; valeur ≤ 255 Lorsque la valeur augmente, l'exposition de l'image DEVRAIT augmenter. Plage de réglage de la densité : -255 ≤ valeur &lt; 0 Lorsque la valeur diminue, la densité de l'image DEVRAIT diminuer , résultant en une image plus sombre. 0 Une valeur de 0 indique que la densité NE DOIT PAS changer. 0 &lt; valeur ≤ 255 Lorsque la valeur augmente, la densité de l'image DEVRAIT augmenter. Plage de réglage du contraste : -100 ≤ valeur &lt; 0 Lorsque la valeur diminue, le contraste de l'image DEVRAIT diminuer. 0 Une valeur de 0 indique que le contraste NE DOIT PAS changer. 0 &lt; valeur ≤ 100 Lorsque la valeur augmente, le contraste de l'image DEVRAIT augmenter e. Plage de réglage de la surbrillance : -100 ≤ valeur &lt; 0 Lorsque la valeur diminue, les zones claires de l'image DEVRAIENT apparaître plus sombres. 0 Une valeur de 0 indique que la surbrillance NE DOIT PAS changer. 0 &lt; valeur ≤ 100 Comme la valeur augmente, les zones claires de l'image DEVRAIENT apparaître plus claires. Plage de réglage des ombres : -100 ≤ valeur &lt; 0 Lorsque la valeur diminue, les zones sombres de l'image DEVRAIENT apparaître plus sombres. 0 Une valeur de 0 indique que le l'ombre NE DOIT PAS changer. 0 &lt; valeur ≤ 100 Lorsque la valeur augmente, les zones sombres de l'image DEVRAIENT apparaître plus claires. Plage de réglage de la saturation des blancs : 0 à 255 Lorsque la valeur augmente, la limite supérieure de la plage de canal de couleur les intensités augmentent. Plage de réglage de la saturation du noir : 0 à 255 À mesure que la valeur augmente, la limite inférieure de la plage des intensités des canaux de couleur augmente. |
| [CurveAdjustment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/curveadjustment) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie l'ajustement de la courbe à appliquer aux couleurs du bitmap. Cette valeur DOIT être définie dans l'énumération CurveAdjustments (section 2.1.1.7). |
| [CurveChannel](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/curvechannel) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le canal de couleur auquel l'ajustement de la courbe s'applique. Cette valeur DOIT être définie dans l'énumération CurveChannel (section 2.1.1.8). |

### Voir également

* class [EmfPlusImageEffectsObjectType](../emfplusimageeffectsobjecttype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
