---
title: "EmfPlusInterpolationMode"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération InterpolationMode définit les méthodes d'effectuer un redimensionnement, y compris l'étirement et la réduction."
type: docs
weight: 29
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusInterpolationMode extends System.Enum
```

L'énumération InterpolationMode définit les méthodes d'effectuer le redimensionnement, y compris l'étirement et la réduction.
## Champs

| Champ | Description |
| --- | --- |
| [InterpolationModeDefault](#InterpolationModeDefault) | Spécifie le mode d'interpolation par défaut, défini comme InterpolationModeBilinear. |
| [InterpolationModeLowQuality](#InterpolationModeLowQuality) | Spécifie un mode d'interpolation de basse qualité, défini comme InterpolationModeNearestNeighbor. |
| [InterpolationModeHighQuality](#InterpolationModeHighQuality) | Spécifie un mode d'interpolation de haute qualité, défini comme InterpolationModeHighQualityBicubic. |
| [InterpolationModeBilinear](#InterpolationModeBilinear) | Spécifie l'interpolation bilinéaire, qui utilise le voisinage 2x2 le plus proche des pixels connus entourant le pixel interpolé. |
| [InterpolationModeBicubic](#InterpolationModeBicubic) | Spécifie l'interpolation bicubique, qui utilise le voisinage le plus proche de 4x4 pixels connus entourant le pixel interpolé. |
| [InterpolationModeNearestNeighbor](#InterpolationModeNearestNeighbor) | Spécifie l'interpolation du plus proche voisin, qui n'utilise que la valeur du pixel le plus proche du pixel interpolé. |
| [InterpolationModeHighQualityBilinear](#InterpolationModeHighQualityBilinear) | Spécifie l'interpolation bilinéaire avec préfiltrage. |
| [InterpolationModeHighQualityBicubic](#InterpolationModeHighQualityBicubic) | Spécifie l'interpolation bicubique avec préfiltrage, qui produit le résultat de la plus haute qualité parmi ces options. |
### InterpolationModeDefault {#InterpolationModeDefault}
```
public static final byte InterpolationModeDefault
```


Spécifie le mode d'interpolation par défaut, défini comme InterpolationModeBilinear.

### InterpolationModeLowQuality {#InterpolationModeLowQuality}
```
public static final byte InterpolationModeLowQuality
```


Spécifie un mode d'interpolation de basse qualité, défini comme InterpolationModeNearestNeighbor.

### InterpolationModeHighQuality {#InterpolationModeHighQuality}
```
public static final byte InterpolationModeHighQuality
```


Spécifie un mode d'interpolation de haute qualité, défini comme InterpolationModeHighQualityBicubic.

### InterpolationModeBilinear {#InterpolationModeBilinear}
```
public static final byte InterpolationModeBilinear
```


Spécifie l'interpolation bilinéaire, qui utilise le voisinage le plus proche de 2x2 pixels connus entourant le pixel interpolé. La moyenne pondérée de ces 4 valeurs de pixels connus détermine la valeur à attribuer au pixel interpolé. Le résultat apparaît plus lisse que InterpolationModeNearestNeighbor.

### InterpolationModeBicubic {#InterpolationModeBicubic}
```
public static final byte InterpolationModeBicubic
```


Spécifie l'interpolation bicubique, qui utilise le voisinage le plus proche de 4x4 pixels connus entourant le pixel interpolé. La moyenne pondérée de ces 16 valeurs de pixels connus détermine la valeur à attribuer au pixel interpolé. Comme les pixels connus sont susceptibles d'être à des distances variables du pixel interpolé, les pixels les plus proches reçoivent un poids plus élevé dans le calcul. Le résultat apparaît plus lisse que InterpolationModeBilinear.

### InterpolationModeNearestNeighbor {#InterpolationModeNearestNeighbor}
```
public static final byte InterpolationModeNearestNeighbor
```


Spécifie l'interpolation du plus proche voisin, qui n'utilise que la valeur du pixel le plus proche du pixel interpolé. Ce mode duplique simplement ou supprime des pixels, produisant le résultat de la plus basse qualité parmi ces options.

### InterpolationModeHighQualityBilinear {#InterpolationModeHighQualityBilinear}
```
public static final byte InterpolationModeHighQualityBilinear
```


Spécifie l'interpolation bilinéaire avec préfiltrage.

### InterpolationModeHighQualityBicubic {#InterpolationModeHighQualityBicubic}
```
public static final byte InterpolationModeHighQualityBicubic
```


Spécifie l'interpolation bicubique avec préfiltrage, qui produit le résultat de la plus haute qualité parmi ces options.

