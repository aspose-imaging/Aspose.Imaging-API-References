---
title: "AdaptiveWhiteStretchFilterOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Tillhandahåller alternativ för att konfigurera Adaptive White Stretch‑filtret."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class AdaptiveWhiteStretchFilterOptions extends FilterOptionsBase
```

Tillhandahåller alternativ för att konfigurera filtret Adaptive White Stretch. Tillåter anpassning av histogramutsträckningsparametrar för att förbättra vitnivån och öka läsbarheten för svagt text eller lågkontrastdokumentbilder.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [AdaptiveWhiteStretchFilterOptions()](#AdaptiveWhiteStretchFilterOptions--) | Initierar en ny instans av klassen AdaptiveWhiteStretchFilter. |
| [AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale)](#AdaptiveWhiteStretchFilterOptions-boolean-int-int-int-float-) | Initierar en ny instans av klassen AdaptiveWhiteStretchFilter. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isGrayscale()](#isGrayscale--) | Hämtar ett värde som indikerar om filtret körs i gråskala. |
| [getLowPercentile()](#getLowPercentile--) | Hämtar den lägre percentilen för beräkning av svartpunkt. |
| [getHighPercentile()](#getHighPercentile--) | Hämtar den högre percentilen för beräkning av vitpunkt. |
| [getTargetWhite()](#getTargetWhite--) | Hämtar det målade vita värdet som utspridningen syftar till att uppnå. |
| [getMaxScale()](#getMaxScale--) | Hämtar den maximalt tillåtna ljusstyrkeskalan. |
### AdaptiveWhiteStretchFilterOptions() {#AdaptiveWhiteStretchFilterOptions--}
```
public AdaptiveWhiteStretchFilterOptions()
```


Initierar en ny instans av klassen AdaptiveWhiteStretchFilter.

### AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale) {#AdaptiveWhiteStretchFilterOptions-boolean-int-int-int-float-}
```
public AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale)
```


Initierar en ny instans av klassen AdaptiveWhiteStretchFilter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isGrayscale | boolean | Indikerar om filtret ska köras i gråskala. |
| lowPercentile | int | Lägre percentil för svartpunkt (t.ex. 10). |
| highPercentile | int | Övre percentil för vitpunkt (t.ex. 90). |
| targetWhite | int | Målvärde för vitpunkt (t.ex. 240). |
|  | maxScale | float | Maximalt tillåten ljusstyrkeskala (t.ex. 1.7). |

--------------------

Algoritmen sträcker histogrammet så att den vita percentilen närmar sig `targetWhite`, men utan att överskrida `maxScale` för att undvika överdriven ljusstyrka. |

### isGrayscale() {#isGrayscale--}
```
public final boolean isGrayscale()
```


Hämtar ett värde som indikerar om filtret körs i gråskala.

**Returns:**
boolean - ett värde som indikerar om filtret körs i gråskala.
### getLowPercentile() {#getLowPercentile--}
```
public final int getLowPercentile()
```


Hämtar den lägre percentilen för beräkning av svartpunkt. Pixlar med värden under denna percentil betraktas som svarta under sträckning.

**Returns:**
int - den lägre percentilen för beräkning av svartpunkt.
### getHighPercentile() {#getHighPercentile--}
```
public final int getHighPercentile()
```


Hämtar den övre percentilen för beräkning av vitpunkt. Pixlar med värden över denna percentil betraktas som vita under sträckning.

**Returns:**
int - den övre percentilen för beräkning av vitpunkt.
### getTargetWhite() {#getTargetWhite--}
```
public final int getTargetWhite()
```


Hämtar det målade vita värdet som utspridningen syftar till att uppnå.

**Returns:**
int - målvärdet för vit som sträckningen syftar till att uppnå.
### getMaxScale() {#getMaxScale--}
```
public final float getMaxScale()
```


Hämtar den maximalt tillåtna ljusstyrkeskalan. Den faktiska sträckningen kommer inte att överskrida denna faktor, för att undvika överdriven ljusstyrka.

**Returns:**
float - den maximalt tillåtna ljusstyrkeskalan.
