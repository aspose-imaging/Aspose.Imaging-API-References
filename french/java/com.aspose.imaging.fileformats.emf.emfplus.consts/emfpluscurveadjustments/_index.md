---
title: "EmfPlusCurveAdjustments"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération CurveAdjustments définit les ajustements qui peuvent être appliqués à la courbe de couleur d'une image."
type: docs
weight: 16
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurveadjustments/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusCurveAdjustments extends System.Enum
```

L'énumération CurveAdjustments définit les ajustements qui peuvent être appliqués à la courbe de couleur d'une image.
## Champs

| Champ | Description |
| --- | --- |
| [AdjustExposure](#AdjustExposure) | Spécifie la simulation d'augmentation ou de diminution de l'exposition d'une image. |
| [AdjustDensity](#AdjustDensity) | Spécifie la simulation d'augmentation ou de diminution de la densité d'une image. |
| [AdjustContrast](#AdjustContrast) | Spécifie une augmentation ou une diminution du contraste d'une image. |
| [AdjustHighlight](#AdjustHighlight) | Spécifie une augmentation ou une diminution de la valeur d'un canal de couleur d'une image, si ce canal a déjà une valeur supérieure à la moitié de l'intensité. |
| [AdjustShadow](#AdjustShadow) | Spécifie une augmentation ou une diminution de la valeur d'un canal de couleur d'une image, si ce canal a déjà une valeur inférieure à la moitié de l'intensité. |
| [AdjustMidtone](#AdjustMidtone) | Spécifie un ajustement qui éclaircit ou assombrit une image. |
| [AdjustWhiteSaturation](#AdjustWhiteSaturation) | Spécifie un ajustement de la saturation blanche d'une image, défini comme la valeur maximale dans la plage d'intensités d'un canal de couleur donné, dont la plage est généralement de 0 à 255. |
| [AdjustBlackSaturation](#AdjustBlackSaturation) | Spécifie un ajustement de la saturation noire d'une image, qui correspond à la valeur minimale dans la plage d'intensités d'un canal de couleur donné, généralement de 0 à 255. |
### AdjustExposure {#AdjustExposure}
```
public static final int AdjustExposure
```


Spécifie la simulation d'augmentation ou de diminution de l'exposition d'une image.

### AdjustDensity {#AdjustDensity}
```
public static final int AdjustDensity
```


Spécifie la simulation d'augmentation ou de diminution de la densité d'une image.

### AdjustContrast {#AdjustContrast}
```
public static final int AdjustContrast
```


Spécifie une augmentation ou une diminution du contraste d'une image.

### AdjustHighlight {#AdjustHighlight}
```
public static final int AdjustHighlight
```


Spécifie une augmentation ou une diminution de la valeur d'un canal de couleur d'une image, si ce canal possède déjà une valeur supérieure à la moitié de l'intensité. Cet ajustement peut être utilisé pour augmenter la définition dans les zones claires d'une image sans affecter les zones sombres.

### AdjustShadow {#AdjustShadow}
```
public static final int AdjustShadow
```


Spécifie une augmentation ou une diminution de la valeur d'un canal de couleur d'une image, si ce canal possède déjà une valeur inférieure à la moitié de l'intensité. Cet ajustement peut être utilisé pour augmenter la définition dans les zones sombres d'une image sans affecter les zones claires.

### AdjustMidtone {#AdjustMidtone}
```
public static final int AdjustMidtone
```


Spécifie un ajustement qui éclaircit ou assombrit une image. Les valeurs des canaux de couleur au milieu de la plage d'intensité sont modifiées davantage que celles proches des extrêmes minimum ou maximum. Cet ajustement peut être utilisé pour éclaircir ou assombrir une image sans perdre le contraste entre les parties les plus sombres et les plus claires.

### AdjustWhiteSaturation {#AdjustWhiteSaturation}
```
public static final int AdjustWhiteSaturation
```


Spécifie un ajustement de la saturation blanche d'une image, défini comme la valeur maximale dans la plage d'intensités d'un canal de couleur donné, dont la plage est généralement de 0 à 255.

--------------------

Par exemple, une valeur d'ajustement de saturation blanche de 240 indique que les valeurs des canaux de couleur dans la plage de 0 à 240 sont ajustées de façon à s'étendre sur la plage de 0 à 255, les valeurs supérieures à 240 étant fixées à 255.

### AdjustBlackSaturation {#AdjustBlackSaturation}
```
public static final int AdjustBlackSaturation
```


Spécifie un ajustement de la saturation noire d'une image, qui correspond à la valeur minimale dans la plage d'intensités d'un canal de couleur donné, généralement de 0 à 255.

--------------------

Par exemple, une valeur d'ajustement de saturation noire de 15 indique que les valeurs des canaux de couleur dans la plage de 15 à 255 sont ajustées de façon à s'étendre sur la plage de 0 à 255, les valeurs inférieures à 15 étant fixées à 0.

