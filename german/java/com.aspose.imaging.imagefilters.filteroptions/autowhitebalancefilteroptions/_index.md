---
title: "AutoWhiteBalanceFilterOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Bietet Konfigurationsoptionen für den Auto White Balance-Filter."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class AutoWhiteBalanceFilterOptions extends FilterOptionsBase
```

Stellt Konfigurationsoptionen für den Auto White Balance-Filter bereit. Ermöglicht die Feinabstimmung von Kontrastdehnungsparametern und Kanalskalierung, um das Erscheinungsbild digitaler Bilder zu verbessern.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [AutoWhiteBalanceFilterOptions()](#AutoWhiteBalanceFilterOptions--) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile)](#AutoWhiteBalanceFilterOptions-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile)](#AutoWhiteBalanceFilterOptions-int-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue)](#AutoWhiteBalanceFilterOptions-int-int-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale)](#AutoWhiteBalanceFilterOptions-int-int-int-float-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset)](#AutoWhiteBalanceFilterOptions-int-int-int-float-int-) | Initialisiert eine neue Instanz der [AutoWhiteBalanceFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions)-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTargetHighPercentile()](#getTargetHighPercentile--) | Ermittelt das Ziel‑hohe Perzentil für die Kontrastdehnung. |
| [getTargetValue()](#getTargetValue--) | Ermittelt den Zielwert für das hohe Perzentil. |
| [getMaxScale()](#getMaxScale--) | Ermittelt den maximalen Skalierungsfaktor für jeden Kanal. |
| [getLowPercentile()](#getLowPercentile--) | Das niedrige Perzentil für den Schwarzpunkt, verwendet zum Dunkelschutz (Standard: 3). |
| [getProtectedDarkOffset()](#getProtectedDarkOffset--) | Versatz vom niedrigen Perzentil, unterhalb dessen dunkle Pixel nicht gedehnt werden (Schutz). |
### AutoWhiteBalanceFilterOptions() {#AutoWhiteBalanceFilterOptions--}
```
public AutoWhiteBalanceFilterOptions()
```


### AutoWhiteBalanceFilterOptions(int lowPercentile) {#AutoWhiteBalanceFilterOptions-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lowPercentile | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile) {#AutoWhiteBalanceFilterOptions-int-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue) {#AutoWhiteBalanceFilterOptions-int-int-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |
| targetValue | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale) {#AutoWhiteBalanceFilterOptions-int-int-int-float-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |
| targetValue | int |  |
| maxScale | float |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset) {#AutoWhiteBalanceFilterOptions-int-int-int-float-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset)
```


Initialisiert eine neue Instanz der [AutoWhiteBalanceFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions)-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lowPercentile | int | Das niedrige Perzentil für den Schwarzpunkt, verwendet zum Dunkelschutz (Standard: 3). |
| targetHighPercentile | int | Das Ziel‑hohe Perzentil für die Kontrastdehnung (Standard 97). |
| targetValue | int | Der Zielwert für das hohe Perzentil (Standardwert 255). |
| maxScale | float | Der maximale Skalierungsfaktor für jeden Kanal (Standardwert 1.4f). |
| protectedDarkOffset | int | Versatz vom niedrigen Perzentil, unterhalb dessen dunkle Pixel nicht gedehnt werden (Schutz). |

### getTargetHighPercentile() {#getTargetHighPercentile--}
```
public final int getTargetHighPercentile()
```


Gibt das Ziel‑hohe Perzentil für die Kontrastdehnung zurück. Bestimmt, welches Helligkeits‑Perzentil auf den Zielwert abgebildet wird.

**Returns:**
int - das Ziel‑hohe Perzentil für die Kontrastdehnung.
### getTargetValue() {#getTargetValue--}
```
public final int getTargetValue()
```


Gibt den Zielwert für das hohe Perzentil zurück. Dieser Wert wird als weiße Referenz für die Kontrastdehnung verwendet.

**Returns:**
int - der Zielwert für das hohe Perzentil.
### getMaxScale() {#getMaxScale--}
```
public final float getMaxScale()
```


Gibt den maximalen Skalierungsfaktor für jeden Kanal zurück. Beschränkt die Verstärkung jedes Kanals, um übermäßige Farbverschiebungen zu vermeiden.

**Returns:**
float - der maximale Skalierungsfaktor für jeden Kanal.
### getLowPercentile() {#getLowPercentile--}
```
public final int getLowPercentile()
```


Das niedrige Perzentil für den Schwarzpunkt, verwendet zum Dunkelschutz (Standard: 3).

**Returns:**
int
### getProtectedDarkOffset() {#getProtectedDarkOffset--}
```
public final int getProtectedDarkOffset()
```


Versatz vom niedrigen Perzentil, unterhalb dessen dunkle Pixel nicht gedehnt werden (Schutz).

**Returns:**
int
