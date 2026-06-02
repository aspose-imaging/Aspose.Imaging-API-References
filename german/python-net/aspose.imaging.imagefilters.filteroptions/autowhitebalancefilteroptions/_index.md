---
title: "AutoWhiteBalanceFilterOptions Klasse"
type: docs
weight: 20
url: /de/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/
---

**Summary:** Provides configuration options for the Auto White Balance filter.<br/>            Allows tuning of contrast stretching parameters and channel scaling<br/>            to improve the appearance of digital images.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.AutoWhiteBalanceFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset)](#AutoWhiteBalanceFilterOptions_low_percentile_target_high_percentile_target_value_max_scale_protected_dark_offset_1) | Initialisiert eine neue Instanz der [AutoWhiteBalanceFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| low_percentile | int | r | Das niedrige Perzentil für den Schwarzpunkt, verwendet zum Schutz dunkler Bereiche (Standard: 3). |
| max_scale | float | r | Liest den maximalen Skalierungsfaktor für jeden Kanal.<br/>            Beschränkt die Verstärkung eines Kanals, um übermäßige Farbverschiebungen zu vermeiden. |
| protected_dark_offset | int | r | Offset vom niedrigen Perzentil, unterhalb dessen dunkle Pixel nicht gedehnt werden (Schutz). |
| target_high_percentile | int | r | Ermittelt das Ziel‑hohe Perzentil für den Kontraststretch.<br/>            Bestimmt, welches Helligkeits‑Perzentil auf den Zielwert abgebildet wird. |
| target_value | int | r | Ermittelt den Zielwert für das hohe Perzentil.<br/>            Dieser Wert wird als weiße Referenz für den Kontraststretch verwendet. |


### Constructor: AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset) {#AutoWhiteBalanceFilterOptions_low_percentile_target_high_percentile_target_value_max_scale_protected_dark_offset_1}


```
 AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset) 
```

Initialisiert eine neue Instanz der [AutoWhiteBalanceFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| low_percentile | int | Das niedrige Perzentil für den Schwarzpunkt, verwendet zum Schutz dunkler Bereiche (Standard: 3). |
| target_high_percentile | int | Das Ziel‑hohe Perzentil für den Kontraststretch (Standardwert 97). |
| target_value | int | Der Zielwert für das hohe Perzentil (Standardwert 255). |
| max_scale | float | Der maximale Skalierungsfaktor für jeden Kanal (Standardwert 1.4f). |
| protected_dark_offset | int | Offset vom niedrigen Perzentil, unterhalb dessen dunkle Pixel nicht gedehnt werden (Schutz). |

