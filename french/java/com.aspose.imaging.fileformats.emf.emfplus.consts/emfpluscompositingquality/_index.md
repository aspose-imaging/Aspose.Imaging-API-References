---
title: "EmfPlusCompositingQuality"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération CompositingQuality définit les niveaux de qualité pour la création d'images composites"
type: docs
weight: 15
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusCompositingQuality extends System.Enum
```

L'énumération CompositingQuality définit les niveaux de qualité pour la création d'images composites
## Champs

| Champ | Description |
| --- | --- |
| [CompositingQualityDefault](#CompositingQualityDefault) | Aucune correction gamma n'est effectuée. |
| [CompositingQualityHighSpeed](#CompositingQualityHighSpeed) | Aucune correction gamma n'est effectuée. |
| [CompositingQualityHighQuality](#CompositingQualityHighQuality) | La correction gamma est effectuée. |
| [CompositingQualityGammaCorrected](#CompositingQualityGammaCorrected) | Activez la correction gamma pour un compositing de meilleure qualité avec une vitesse réduite. |
| [CompositingQualityAssumeLinear](#CompositingQualityAssumeLinear) | Aucune correction gamma n'est effectuée ; cependant, l'utilisation de valeurs linéaires donne une meilleure qualité que la valeur par défaut avec une vitesse légèrement réduite. |
### CompositingQualityDefault {#CompositingQualityDefault}
```
public static final byte CompositingQualityDefault
```


Aucune correction gamma n'est effectuée. La correction gamma contrôle la luminosité et le contraste globaux d'une image. Sans correction gamma, les images composites peuvent apparaître trop claires ou trop sombres.

### CompositingQualityHighSpeed {#CompositingQualityHighSpeed}
```
public static final byte CompositingQualityHighSpeed
```


Aucune correction gamma n'est effectuée. La vitesse de compositing est privilégiée au détriment de la qualité. En termes de résultat, il n'y a aucune différence entre cette valeur et CompositingQualityDefault.

### CompositingQualityHighQuality {#CompositingQualityHighQuality}
```
public static final byte CompositingQualityHighQuality
```


La correction gamma est effectuée. La qualité du compositing est privilégiée au détriment de la vitesse.

### CompositingQualityGammaCorrected {#CompositingQualityGammaCorrected}
```
public static final byte CompositingQualityGammaCorrected
```


Activez la correction gamma pour un compositing de meilleure qualité avec une vitesse réduite. En termes de résultat, il n'y a aucune différence entre cette valeur et CompositingQualityHighQuality.

### CompositingQualityAssumeLinear {#CompositingQualityAssumeLinear}
```
public static final byte CompositingQualityAssumeLinear
```


Aucune correction gamma n'est effectuée ; cependant, l'utilisation de valeurs linéaires donne une meilleure qualité que la valeur par défaut avec une vitesse légèrement réduite.

