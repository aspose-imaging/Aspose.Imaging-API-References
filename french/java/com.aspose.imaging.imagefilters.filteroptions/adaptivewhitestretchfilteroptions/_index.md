---
title: "AdaptiveWhiteStretchFilterOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Fournit des options pour configurer le filtre Adaptive White Stretch."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class AdaptiveWhiteStretchFilterOptions extends FilterOptionsBase
```

Fournit des options pour configurer le filtre Adaptive White Stretch. Permet la personnalisation des paramètres d'étirement de l'histogramme afin d'améliorer le niveau de blanc et la lisibilité des images de documents à texte faible ou à faible contraste.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [AdaptiveWhiteStretchFilterOptions()](#AdaptiveWhiteStretchFilterOptions--) | Initialise une nouvelle instance de la classe AdaptiveWhiteStretchFilter. |
| [AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale)](#AdaptiveWhiteStretchFilterOptions-boolean-int-int-int-float-) | Initialise une nouvelle instance de la classe AdaptiveWhiteStretchFilter. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [isGrayscale()](#isGrayscale--) | Obtient une valeur indiquant si le filtre fonctionne en mode niveaux de gris. |
| [getLowPercentile()](#getLowPercentile--) | Obtient le percentile inférieur pour le calcul du point noir. |
| [getHighPercentile()](#getHighPercentile--) | Obtient le percentile supérieur pour le calcul du point blanc. |
| [getTargetWhite()](#getTargetWhite--) | Obtient la valeur blanche cible que l'étirement vise à atteindre. |
| [getMaxScale()](#getMaxScale--) | Obtient l'échelle de luminosité maximale autorisée. |
### AdaptiveWhiteStretchFilterOptions() {#AdaptiveWhiteStretchFilterOptions--}
```
public AdaptiveWhiteStretchFilterOptions()
```


Initialise une nouvelle instance de la classe AdaptiveWhiteStretchFilter.

### AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale) {#AdaptiveWhiteStretchFilterOptions-boolean-int-int-int-float-}
```
public AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale)
```


Initialise une nouvelle instance de la classe AdaptiveWhiteStretchFilter.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| isGrayscale | boolean | Indique si le filtre doit fonctionner en mode niveaux de gris. |
| lowPercentile | int | Percentile inférieur pour le point noir (par ex. 10). |
| highPercentile | int | Pourcentage supérieur pour le point blanc (par ex. 90). |
| targetWhite | int | Valeur blanche cible (par ex. 240). |
|  | maxScale | float | Échelle de luminosité maximale autorisée (par ex. 1.7). |

--------------------

L'algorithme étire l'histogramme de sorte que le percentile blanc approche `targetWhite`, mais sans dépasser `maxScale` afin d'éviter un éclaircissement excessif. |

### isGrayscale() {#isGrayscale--}
```
public final boolean isGrayscale()
```


Obtient une valeur indiquant si le filtre fonctionne en mode niveaux de gris.

**Returns:**
booléen - une valeur indiquant si le filtre fonctionne en mode niveaux de gris.
### getLowPercentile() {#getLowPercentile--}
```
public final int getLowPercentile()
```


Obtient le percentile inférieur pour le calcul du point noir. Les valeurs de pixel en dessous de ce percentile sont considérées comme noires lors de l'étirement.

**Returns:**
int - le percentile inférieur pour le calcul du point noir.
### getHighPercentile() {#getHighPercentile--}
```
public final int getHighPercentile()
```


Obtient le percentile supérieur pour le calcul du point blanc. Les valeurs de pixel au-dessus de ce percentile sont considérées comme blanches lors de l'étirement.

**Returns:**
int - le percentile supérieur pour le calcul du point blanc.
### getTargetWhite() {#getTargetWhite--}
```
public final int getTargetWhite()
```


Obtient la valeur blanche cible que l'étirement vise à atteindre.

**Returns:**
int - la valeur blanche cible que l'étirement vise à atteindre.
### getMaxScale() {#getMaxScale--}
```
public final float getMaxScale()
```


Obtient l'échelle de luminosité maximale autorisée. L'étirement réel ne dépassera pas ce facteur, afin d'éviter un éclaircissement excessif.

**Returns:**
float - l'échelle de luminosité maximale autorisée.
