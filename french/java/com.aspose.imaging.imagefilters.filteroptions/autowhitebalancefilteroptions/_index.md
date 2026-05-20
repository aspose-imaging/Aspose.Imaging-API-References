---
title: "AutoWhiteBalanceFilterOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Fournit des options de configuration pour le filtre Auto White Balance."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class AutoWhiteBalanceFilterOptions extends FilterOptionsBase
```

Fournit des options de configuration pour le filtre Auto White Balance. Permet d'ajuster les paramètres d'étirement du contraste et le redimensionnement des canaux afin d'améliorer l'apparence des images numériques.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [AutoWhiteBalanceFilterOptions()](#AutoWhiteBalanceFilterOptions--) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile)](#AutoWhiteBalanceFilterOptions-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile)](#AutoWhiteBalanceFilterOptions-int-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue)](#AutoWhiteBalanceFilterOptions-int-int-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale)](#AutoWhiteBalanceFilterOptions-int-int-int-float-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset)](#AutoWhiteBalanceFilterOptions-int-int-int-float-int-) | Initialise une nouvelle instance de la classe [AutoWhiteBalanceFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTargetHighPercentile()](#getTargetHighPercentile--) | Obtient le percentile haut cible pour l'étirement du contraste. |
| [getTargetValue()](#getTargetValue--) | Obtient la valeur cible pour le percentile haut. |
| [getMaxScale()](#getMaxScale--) | Obtient le facteur d'échelle maximal pour chaque canal. |
| [getLowPercentile()](#getLowPercentile--) | Le percentile bas pour le point noir, utilisé pour la protection contre les zones sombres (par défaut : 3). |
| [getProtectedDarkOffset()](#getProtectedDarkOffset--) | Décalage à partir du percentile bas en dessous duquel les pixels sombres ne sont pas étirés (protection). |
### AutoWhiteBalanceFilterOptions() {#AutoWhiteBalanceFilterOptions--}
```
public AutoWhiteBalanceFilterOptions()
```


### AutoWhiteBalanceFilterOptions(int lowPercentile) {#AutoWhiteBalanceFilterOptions-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lowPercentile | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile) {#AutoWhiteBalanceFilterOptions-int-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue) {#AutoWhiteBalanceFilterOptions-int-int-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |
| targetValue | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale) {#AutoWhiteBalanceFilterOptions-int-int-int-float-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |
| targetValue | int |  |
| maxScale | float |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset) {#AutoWhiteBalanceFilterOptions-int-int-int-float-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset)
```


Initialise une nouvelle instance de la classe [AutoWhiteBalanceFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lowPercentile | int | Le percentile bas pour le point noir, utilisé pour la protection contre les zones sombres (par défaut : 3). |
| targetHighPercentile | int | Le percentile haut cible pour l'étirement du contraste (par défaut : 97). |
| targetValue | int | La valeur cible pour le percentile élevé (par défaut 255). |
| maxScale | float | Le facteur d'échelle maximal pour chaque canal (par défaut 1.4f). |
| protectedDarkOffset | int | Décalage à partir du percentile bas en dessous duquel les pixels sombres ne sont pas étirés (protection). |

### getTargetHighPercentile() {#getTargetHighPercentile--}
```
public final int getTargetHighPercentile()
```


Obtient le percentile élevé cible pour l'étirement du contraste. Détermine quel percentile de luminosité sera mappé à la valeur cible.

**Returns:**
int - le percentile élevé cible pour l'étirement du contraste.
### getTargetValue() {#getTargetValue--}
```
public final int getTargetValue()
```


Obtient la valeur cible pour le percentile élevé. Cette valeur sera utilisée comme référence blanche pour l'étirement du contraste.

**Returns:**
int - la valeur cible pour le percentile élevé.
### getMaxScale() {#getMaxScale--}
```
public final float getMaxScale()
```


Obtient le facteur d'échelle maximal pour chaque canal. Restreint l'amplification de tout canal afin d'éviter des changements de couleur excessifs.

**Returns:**
float - le facteur d'échelle maximal pour chaque canal.
### getLowPercentile() {#getLowPercentile--}
```
public final int getLowPercentile()
```


Le percentile bas pour le point noir, utilisé pour la protection contre les zones sombres (par défaut : 3).

**Returns:**
int
### getProtectedDarkOffset() {#getProtectedDarkOffset--}
```
public final int getProtectedDarkOffset()
```


Décalage à partir du percentile bas en dessous duquel les pixels sombres ne sont pas étirés (protection).

**Returns:**
int
