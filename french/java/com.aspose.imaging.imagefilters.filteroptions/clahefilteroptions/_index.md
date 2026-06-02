---
title: "ClaheFilterOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Fournit des options pour configurer le filtre Contrast-Limited Adaptive Histogram Equalization CLAHE."
type: docs
weight: 14
url: /fr/java/com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class ClaheFilterOptions extends FilterOptionsBase
```

Fournit des options pour configurer le filtre Contrast-Limited Adaptive Histogram Equalization (CLAHE).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ClaheFilterOptions()](#ClaheFilterOptions--) |  |
| [ClaheFilterOptions(boolean isGrayscale)](#ClaheFilterOptions-boolean-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal)](#ClaheFilterOptions-boolean-int-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical)](#ClaheFilterOptions-boolean-int-int-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit)](#ClaheFilterOptions-boolean-int-int-double-) | Initialise une nouvelle instance de la classe [ClaheFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions) avec les paramètres spécifiés. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [isGrayscale()](#isGrayscale--) | Obtient une valeur indiquant si le filtre fonctionne en mode niveaux de gris. |
| [getTilesNumberHorizontal()](#getTilesNumberHorizontal--) | Obtient le nombre de tuiles dans la direction horizontale. |
| [getTilesNumberVertical()](#getTilesNumberVertical--) | Obtient le nombre de tuiles dans la direction verticale. |
| [getClipLimit()](#getClipLimit--) | Obtient le seuil de limitation du contraste. |
### ClaheFilterOptions() {#ClaheFilterOptions--}
```
public ClaheFilterOptions()
```


### ClaheFilterOptions(boolean isGrayscale) {#ClaheFilterOptions-boolean-}
```
public ClaheFilterOptions(boolean isGrayscale)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| isGrayscale | boolean |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal) {#ClaheFilterOptions-boolean-int-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| isGrayscale | boolean |  |
| tilesNumberHorizontal | int |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical) {#ClaheFilterOptions-boolean-int-int-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| isGrayscale | boolean |  |
| tilesNumberHorizontal | int |  |
| tilesNumberVertical | int |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit) {#ClaheFilterOptions-boolean-int-int-double-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit)
```


Initialise une nouvelle instance de la classe [ClaheFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions) avec les paramètres spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| isGrayscale | boolean | Indique si le filtre doit fonctionner en mode niveaux de gris. |
| tilesNumberHorizontal | int | Nombre de tuiles horizontalement. La valeur par défaut est 8. |
| tilesNumberVertical | int | Nombre de tuiles verticalement. La valeur par défaut est 8. |
| clipLimit | double | Seuil de limitation du contraste. La valeur par défaut est 4.0. |

### isGrayscale() {#isGrayscale--}
```
public final boolean isGrayscale()
```


Obtient une valeur indiquant si le filtre fonctionne en mode niveaux de gris.

**Returns:**
booléen - une valeur indiquant si le filtre fonctionne en mode niveaux de gris.
### getTilesNumberHorizontal() {#getTilesNumberHorizontal--}
```
public final int getTilesNumberHorizontal()
```


Obtient le nombre de tuiles dans la direction horizontale. Détermine combien de régions l'image est divisée horizontalement pour l'égalisation locale du contraste.

**Returns:**
int - le nombre de tuiles dans la direction horizontale.
### getTilesNumberVertical() {#getTilesNumberVertical--}
```
public final int getTilesNumberVertical()
```


Obtient le nombre de tuiles dans la direction verticale. Détermine combien de régions l'image est divisée verticalement pour l'égalisation locale du contraste.

**Returns:**
int - le nombre de tuiles dans la direction verticale.
### getClipLimit() {#getClipLimit--}
```
public final double getClipLimit()
```


Obtient le seuil de limitation du contraste. Des valeurs plus élevées permettent plus de contraste ; des valeurs plus faibles limitent l'amélioration afin d'éviter l'amplification du bruit.

**Returns:**
double - le seuil de limitation du contraste.
