---
title: "AutoWhiteBalanceFilterOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Tillhandahåller konfigurationsalternativ för Auto White Balance‑filtret."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class AutoWhiteBalanceFilterOptions extends FilterOptionsBase
```

Tillhandahåller konfigurationsalternativ för Auto White Balance-filtret. Tillåter justering av parametrar för kontrastutsträckning och kanalskalning för att förbättra utseendet på digitala bilder.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [AutoWhiteBalanceFilterOptions()](#AutoWhiteBalanceFilterOptions--) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile)](#AutoWhiteBalanceFilterOptions-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile)](#AutoWhiteBalanceFilterOptions-int-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue)](#AutoWhiteBalanceFilterOptions-int-int-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale)](#AutoWhiteBalanceFilterOptions-int-int-int-float-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset)](#AutoWhiteBalanceFilterOptions-int-int-int-float-int-) | Initierar en ny instans av klassen [AutoWhiteBalanceFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTargetHighPercentile()](#getTargetHighPercentile--) | Hämtar mål‑höga percentilen för kontrastutsträckning. |
| [getTargetValue()](#getTargetValue--) | Hämtar mål‑värdet för den höga percentilen. |
| [getMaxScale()](#getMaxScale--) | Hämtar den maximala skalningsfaktorn för varje kanal. |
| [getLowPercentile()](#getLowPercentile--) | Den låga percentilen för svartpunkt, används för mörksskydd (standard: 3). |
| [getProtectedDarkOffset()](#getProtectedDarkOffset--) | Offset från låg percentil under vilken mörka pixlar inte sträcks (skydd). |
### AutoWhiteBalanceFilterOptions() {#AutoWhiteBalanceFilterOptions--}
```
public AutoWhiteBalanceFilterOptions()
```


### AutoWhiteBalanceFilterOptions(int lowPercentile) {#AutoWhiteBalanceFilterOptions-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lowPercentile | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile) {#AutoWhiteBalanceFilterOptions-int-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue) {#AutoWhiteBalanceFilterOptions-int-int-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |
| targetValue | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale) {#AutoWhiteBalanceFilterOptions-int-int-int-float-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |
| targetValue | int |  |
| maxScale | float |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset) {#AutoWhiteBalanceFilterOptions-int-int-int-float-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset)
```


Initierar en ny instans av klassen [AutoWhiteBalanceFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lowPercentile | int | Den låga percentilen för svartpunkt, används för mörksskydd (standard: 3). |
| targetHighPercentile | int | Mål‑höga percentilen för kontrastutsträckning (standard 97). |
| targetValue | int | Målvärdet för den höga percentilen (standard 255). |
| maxScale | float | Den maximala skalningsfaktorn för varje kanal (standard 1.4f). |
| protectedDarkOffset | int | Offset från låg percentil under vilken mörka pixlar inte sträcks (skydd). |

### getTargetHighPercentile() {#getTargetHighPercentile--}
```
public final int getTargetHighPercentile()
```


Hämtar den målade höga percentilen för kontrastutsträckning. Bestämmer vilken ljusstyrkepercentil som kommer att mappas till målvärdet.

**Returns:**
int – den målade höga percentilen för kontrastutsträckning.
### getTargetValue() {#getTargetValue--}
```
public final int getTargetValue()
```


Hämtar målvärdet för den höga percentilen. Detta värde kommer att användas som vit referens för kontrastutsträckning.

**Returns:**
int – målvärdet för den höga percentilen.
### getMaxScale() {#getMaxScale--}
```
public final float getMaxScale()
```


Hämtar den maximala skalningsfaktorn för varje kanal. Begränsar förstärkningen av någon kanal för att undvika överdrivna färgskiftningar.

**Returns:**
float – den maximala skalningsfaktorn för varje kanal.
### getLowPercentile() {#getLowPercentile--}
```
public final int getLowPercentile()
```


Den låga percentilen för svartpunkt, används för mörksskydd (standard: 3).

**Returns:**
int
### getProtectedDarkOffset() {#getProtectedDarkOffset--}
```
public final int getProtectedDarkOffset()
```


Offset från låg percentil under vilken mörka pixlar inte sträcks (skydd).

**Returns:**
int
