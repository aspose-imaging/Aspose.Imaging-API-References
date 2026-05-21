---
title: "EmfPlusColorCurveEffect"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet ColorCurveEffect spécifie l'un des huit ajustements de la courbe de couleur d'une image."
type: docs
weight: 27
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorCurveEffect extends EmfPlusImageEffectsObjectType
```

L'objet ColorCurveEffect spécifie l'un des huit ajustements de la courbe de couleur d'une image.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusColorCurveEffect()](#EmfPlusColorCurveEffect--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCurveAdjustment()](#getCurveAdjustment--) | Obtient ou définit un entier non signé 32 bits qui spécifie l'ajustement de courbe à appliquer aux couleurs du bitmap. |
| [setCurveAdjustment(int value)](#setCurveAdjustment-int-) | Obtient ou définit un entier non signé 32 bits qui spécifie l'ajustement de courbe à appliquer aux couleurs du bitmap. |
| [getCurveChannel()](#getCurveChannel--) | Obtient ou définit un entier non signé 32 bits qui spécifie le canal de couleur auquel l'ajustement de courbe s'applique. |
| [setCurveChannel(int value)](#setCurveChannel-int-) | Obtient ou définit un entier non signé 32 bits qui spécifie le canal de couleur auquel l'ajustement de courbe s'applique. |
| [getAdjustmentIntensity()](#getAdjustmentIntensity--) | Obtient ou définit un entier signé 32 bits qui spécifie l'intensité de l'ajustement de courbe pour le canal de couleur spécifié par CurveChannel. |
| [setAdjustmentIntensity(int value)](#setAdjustmentIntensity-int-) | Obtient ou définit un entier signé 32 bits qui spécifie l'intensité de l'ajustement de courbe pour le canal de couleur spécifié par CurveChannel. |
### EmfPlusColorCurveEffect() {#EmfPlusColorCurveEffect--}
```
public EmfPlusColorCurveEffect()
```


### getCurveAdjustment() {#getCurveAdjustment--}
```
public int getCurveAdjustment()
```


Obtient ou définit un entier non signé 32 bits qui spécifie l'ajustement de courbe à appliquer aux couleurs du bitmap. Cette valeur DOIT être définie dans l'énumération CurveAdjustments (section 2.1.1.7).

**Returns:**
int
### setCurveAdjustment(int value) {#setCurveAdjustment-int-}
```
public void setCurveAdjustment(int value)
```


Obtient ou définit un entier non signé 32 bits qui spécifie l'ajustement de courbe à appliquer aux couleurs du bitmap. Cette valeur DOIT être définie dans l'énumération CurveAdjustments (section 2.1.1.7).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCurveChannel() {#getCurveChannel--}
```
public int getCurveChannel()
```


Obtient ou définit un entier non signé 32 bits qui spécifie le canal de couleur auquel l'ajustement de courbe s'applique. Cette valeur DOIT être définie dans l'énumération CurveChannel (section 2.1.1.8).

**Returns:**
int
### setCurveChannel(int value) {#setCurveChannel-int-}
```
public void setCurveChannel(int value)
```


Obtient ou définit un entier non signé 32 bits qui spécifie le canal de couleur auquel l'ajustement de courbe s'applique. Cette valeur DOIT être définie dans l'énumération CurveChannel (section 2.1.1.8).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getAdjustmentIntensity() {#getAdjustmentIntensity--}
```
public int getAdjustmentIntensity()
```


Obtient ou définit un entier signé 32 bits qui spécifie l'intensité de l'ajustement de courbe pour le canal de couleur spécifié par CurveChannel. Les plages de valeurs significatives pour ce champ varient selon la valeur de CurveAdjustment, comme suit : Plage d'ajustement de l'exposition : -255 \\u2264 valeur < 0 À mesure que la valeur diminue, l'exposition de l'image DOIT diminuer. 0 Une valeur de 0 indique que l'exposition NE DOIT PAS changer. 0 < valeur \\u2264 255 À mesure que la valeur augmente, l'exposition de l'image DOIT augmenter. Plage d'ajustement de la densité : -255 \\u2264 valeur < 0 À mesure que la valeur diminue, la densité de l'image DOIT diminuer, ce qui donne une image plus sombre. 0 Une valeur de 0 indique que la densité NE DOIT PAS changer. 0 < valeur \\u2264 255 À mesure que la valeur augmente, la densité de l'image DOIT augmenter. Plage d'ajustement du contraste : -100 \\u2264 valeur < 0 À mesure que la valeur diminue, le contraste de l'image DOIT diminuer. 0 Une valeur de 0 indique que le contraste NE DOIT PAS changer. 0 < valeur \\u2264 100 À mesure que la valeur augmente, le contraste de l'image DOIT augmenter. Plage d'ajustement des hautes lumières : -100 \\u2264 valeur < 0 À mesure que la valeur diminue, les zones claires de l'image DOIVENT apparaître plus sombres. 0 Une valeur de 0 indique que les hautes lumières NE DOIVENT PAS changer. 0 < valeur \\u2264 100 À mesure que la valeur augmente, les zones claires de l'image DOIVENT apparaître plus claires. Plage d'ajustement des ombres : -100 \\u2264 valeur < 0 À mesure que la valeur diminue, les zones sombres de l'image DOIVENT apparaître plus sombres. 0 Une valeur de 0 indique que les ombres NE DOIVENT PAS changer. 0 < valeur \\u2264 100 À mesure que la valeur augmente, les zones sombres de l'image DOIVENT apparaître plus claires. Plage d'ajustement de la saturation blanche : 0 \\u2014 255 À mesure que la valeur augmente, la limite supérieure de la plage d'intensités du canal de couleur augmente. Plage d'ajustement de la saturation noire : 0 \\u2014 255 À mesure que la valeur augmente, la limite inférieure de la plage d'intensités du canal de couleur augmente.

**Returns:**
int
### setAdjustmentIntensity(int value) {#setAdjustmentIntensity-int-}
```
public void setAdjustmentIntensity(int value)
```


Obtient ou définit un entier signé 32 bits qui spécifie l'intensité de l'ajustement de courbe pour le canal de couleur spécifié par CurveChannel. Les plages de valeurs significatives pour ce champ varient selon la valeur de CurveAdjustment, comme suit : Plage d'ajustement de l'exposition : -255 \\u2264 valeur < 0 À mesure que la valeur diminue, l'exposition de l'image DOIT diminuer. 0 Une valeur de 0 indique que l'exposition NE DOIT PAS changer. 0 < valeur \\u2264 255 À mesure que la valeur augmente, l'exposition de l'image DOIT augmenter. Plage d'ajustement de la densité : -255 \\u2264 valeur < 0 À mesure que la valeur diminue, la densité de l'image DOIT diminuer, ce qui donne une image plus sombre. 0 Une valeur de 0 indique que la densité NE DOIT PAS changer. 0 < valeur \\u2264 255 À mesure que la valeur augmente, la densité de l'image DOIT augmenter. Plage d'ajustement du contraste : -100 \\u2264 valeur < 0 À mesure que la valeur diminue, le contraste de l'image DOIT diminuer. 0 Une valeur de 0 indique que le contraste NE DOIT PAS changer. 0 < valeur \\u2264 100 À mesure que la valeur augmente, le contraste de l'image DOIT augmenter. Plage d'ajustement des hautes lumières : -100 \\u2264 valeur < 0 À mesure que la valeur diminue, les zones claires de l'image DOIVENT apparaître plus sombres. 0 Une valeur de 0 indique que les hautes lumières NE DOIVENT PAS changer. 0 < valeur \\u2264 100 À mesure que la valeur augmente, les zones claires de l'image DOIVENT apparaître plus claires. Plage d'ajustement des ombres : -100 \\u2264 valeur < 0 À mesure que la valeur diminue, les zones sombres de l'image DOIVENT apparaître plus sombres. 0 Une valeur de 0 indique que les ombres NE DOIVENT PAS changer. 0 < valeur \\u2264 100 À mesure que la valeur augmente, les zones sombres de l'image DOIVENT apparaître plus claires. Plage d'ajustement de la saturation blanche : 0 \\u2014 255 À mesure que la valeur augmente, la limite supérieure de la plage d'intensités du canal de couleur augmente. Plage d'ajustement de la saturation noire : 0 \\u2014 255 À mesure que la valeur augmente, la limite inférieure de la plage d'intensités du canal de couleur augmente.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

