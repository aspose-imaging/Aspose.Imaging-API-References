---
title: "EmfPlusFilterType"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération FilterType définit les types d'algorithmes de filtrage pouvant être utilisés pour l'amélioration de la qualité du texte et des graphiques ainsi que le rendu d'images."
type: docs
weight: 22
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusFilterType extends System.Enum
```

L'énumération FilterType définit les types d'algorithmes de filtrage pouvant être utilisés pour l'amélioration de la qualité du texte et des graphiques ainsi que le rendu d'images.
## Champs

| Champ | Description |
| --- | --- |
| [FilterTypeNone](#FilterTypeNone) | Spécifie qu'aucun filtrage n'est effectué. |
| [FilterTypePoint](#FilterTypePoint) | Spécifie que chaque pixel de destination est calculé en échantillonnant le pixel le plus proche de l'image source. |
| [FilterTypeLinear](#FilterTypeLinear) | Spécifie qu'une interpolation linéaire est effectuée en utilisant la moyenne pondérée d'une zone de 2 x 2 pixels entourant le pixel source. |
| [FilterTypeTriangle](#FilterTypeTriangle) | Spécifie que chaque pixel de l'image source contribue de manière égale à l'image de destination. |
| [FilterTypeBox](#FilterTypeBox) | Spécifie un algorithme de filtre boîte, dans lequel chaque pixel de destination est calculé en moyennant un rectangle de pixels source. |
| [FilterTypePyramidalQuad](#FilterTypePyramidalQuad) | Spécifie qu'un filtre tente à 4 échantillons est utilisé. |
| [FilterTypeGaussianQuad](#FilterTypeGaussianQuad) | Spécifie qu'un filtre gaussien à 4 échantillons est utilisé, ce qui crée un effet de flou sur une image. |
### FilterTypeNone {#FilterTypeNone}
```
public static final byte FilterTypeNone
```


Spécifie qu'aucun filtrage n'est effectué.

### FilterTypePoint {#FilterTypePoint}
```
public static final byte FilterTypePoint
```


Spécifie que chaque pixel de destination est calculé en échantillonnant le pixel le plus proche de l'image source.

### FilterTypeLinear {#FilterTypeLinear}
```
public static final byte FilterTypeLinear
```


Spécifie qu'une interpolation linéaire est effectuée en utilisant la moyenne pondérée d'une zone de 2 x 2 pixels entourant le pixel source.

### FilterTypeTriangle {#FilterTypeTriangle}
```
public static final byte FilterTypeTriangle
```


Spécifie que chaque pixel de l'image source contribue de manière égale à l'image de destination. C'est le plus lent des algorithmes de filtrage.

### FilterTypeBox {#FilterTypeBox}
```
public static final byte FilterTypeBox
```


Spécifie un algorithme de filtre à boîte, dans lequel chaque pixel de destination est calculé en moyennant un rectangle de pixels source. Cet algorithme n'est utile que lors de la réduction de la taille d'une image.

### FilterTypePyramidalQuad {#FilterTypePyramidalQuad}
```
public static final byte FilterTypePyramidalQuad
```


Spécifie qu'un filtre tente à 4 échantillons est utilisé.

### FilterTypeGaussianQuad {#FilterTypeGaussianQuad}
```
public static final byte FilterTypeGaussianQuad
```


Spécifie qu'un filtre gaussien à 4 échantillons est utilisé, ce qui crée un effet de flou sur une image.

