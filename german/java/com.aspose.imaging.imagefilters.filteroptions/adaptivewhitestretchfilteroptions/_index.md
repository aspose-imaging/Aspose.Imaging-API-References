---
title: "AdaptiveWhiteStretchFilterOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Bietet Optionen zur Konfiguration des Adaptive White Stretch-Filters."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class AdaptiveWhiteStretchFilterOptions extends FilterOptionsBase
```

Stellt Optionen zur Konfiguration des Adaptive White Stretch filters bereit. Ermöglicht die Anpassung von Histogramm‑Dehnungsparametern, um den Weißwert zu erhöhen und die Lesbarkeit von schwachem Text oder kontrastarmen Dokumenten zu verbessern.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [AdaptiveWhiteStretchFilterOptions()](#AdaptiveWhiteStretchFilterOptions--) | Initialisiert eine neue Instanz der AdaptiveWhiteStretchFilter‑Klasse. |
| [AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale)](#AdaptiveWhiteStretchFilterOptions-boolean-int-int-int-float-) | Initialisiert eine neue Instanz der AdaptiveWhiteStretchFilter‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isGrayscale()](#isGrayscale--) | Gibt einen Wert zurück, der angibt, ob der Filter im Graustufenmodus arbeitet. |
| [getLowPercentile()](#getLowPercentile--) | Gibt das untere Perzentil für die Berechnung des Schwarzpunkts zurück. |
| [getHighPercentile()](#getHighPercentile--) | Gibt das obere Perzentil für die Berechnung des Weißpunkts zurück. |
| [getTargetWhite()](#getTargetWhite--) | Gibt den Ziel‑Weißwert zurück, den die Dehnung erreichen soll. |
| [getMaxScale()](#getMaxScale--) | Gibt die maximal zulässige Helligkeitsskala zurück. |
### AdaptiveWhiteStretchFilterOptions() {#AdaptiveWhiteStretchFilterOptions--}
```
public AdaptiveWhiteStretchFilterOptions()
```


Initialisiert eine neue Instanz der AdaptiveWhiteStretchFilter‑Klasse.

### AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale) {#AdaptiveWhiteStretchFilterOptions-boolean-int-int-int-float-}
```
public AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale)
```


Initialisiert eine neue Instanz der AdaptiveWhiteStretchFilter‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isGrayscale | boolean | Gibt an, ob der Filter im Graustufenmodus arbeiten soll. |
| lowPercentile | int | Unteres Perzentil für den Schwarzpunkt (z. B. 10). |
| highPercentile | int | Oberes Perzentil für den Weißpunkt (z. B. 90). |
| targetWhite | int | Zielwert für Weiß (z. B. 240). |
|  | maxScale | float | Maximal zulässige Helligkeitsskala (z. B. 1.7). |

--------------------

Der Algorithmus dehnt das Histogramm so, dass das weiße Perzentil `targetWhite` annähert, jedoch `maxScale` nicht überschreitet, um Überbelichtung zu vermeiden. |

### isGrayscale() {#isGrayscale--}
```
public final boolean isGrayscale()
```


Gibt einen Wert zurück, der angibt, ob der Filter im Graustufenmodus arbeitet.

**Returns:**
boolean – ein Wert, der angibt, ob der Filter im Graustufenmodus arbeitet.
### getLowPercentile() {#getLowPercentile--}
```
public final int getLowPercentile()
```


Liefert das untere Perzentil für die Berechnung des Schwarzpunkts. Pixelwerte unter diesem Perzentil werden beim Dehnen als Schwarz betrachtet.

**Returns:**
int - das untere Perzentil für die Berechnung des Schwarzpunkts.
### getHighPercentile() {#getHighPercentile--}
```
public final int getHighPercentile()
```


Liefert das obere Perzentil für die Berechnung des Weißpunkts. Pixelwerte über diesem Perzentil werden beim Dehnen als Weiß betrachtet.

**Returns:**
int - das obere Perzentil für die Berechnung des Weißpunkts.
### getTargetWhite() {#getTargetWhite--}
```
public final int getTargetWhite()
```


Gibt den Ziel‑Weißwert zurück, den die Dehnung erreichen soll.

**Returns:**
int - der Zielwert für Weiß, den das Dehnen erreichen soll.
### getMaxScale() {#getMaxScale--}
```
public final float getMaxScale()
```


Liefert die maximal zulässige Helligkeitsskala. Das tatsächliche Dehnen wird diesen Faktor nicht überschreiten, um Überbelichtung zu vermeiden.

**Returns:**
float - die maximal zulässige Helligkeitsskala.
