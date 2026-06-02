---
title: "EmfPlusInterpolationMode"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die InterpolationMode‑Aufzählung definiert Methoden zur Durchführung von Skalierungen, einschließlich Dehnung und Schrumpfung."
type: docs
weight: 29
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusInterpolationMode extends System.Enum
```

Die InterpolationMode-Aufzählung definiert Methoden zur Durchführung von Skalierungen, einschließlich Dehnung und Schrumpfung.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [InterpolationModeDefault](#InterpolationModeDefault) | Gibt den Standardinterpolationsmodus an, der als InterpolationModeBilinear definiert ist. |
| [InterpolationModeLowQuality](#InterpolationModeLowQuality) | Gibt einen interpolationsmodus von niedriger Qualität an, der als InterpolationModeNearestNeighbor definiert ist. |
| [InterpolationModeHighQuality](#InterpolationModeHighQuality) | Gibt einen interpolationsmodus von hoher Qualität an, der als InterpolationModeHighQualityBicubic definiert ist. |
| [InterpolationModeBilinear](#InterpolationModeBilinear) | Gibt bilineare Interpolation an, die das nächstgelegene 2 × 2‑Nachbarschafts‑Pixelfeld bekannter Pixel um das interpolierte Pixel verwendet. |
| [InterpolationModeBicubic](#InterpolationModeBicubic) | Gibt die bikubische Interpolation an, die die nächstgelegene 4x4‑Nachbarschaft bekannter Pixel um das interpolierte Pixel verwendet. |
| [InterpolationModeNearestNeighbor](#InterpolationModeNearestNeighbor) | Gibt die nächstgelegene Nachbarinterpolation an, die nur den Wert des Pixels verwendet, das dem interpolierten Pixel am nächsten liegt. |
| [InterpolationModeHighQualityBilinear](#InterpolationModeHighQualityBilinear) | Gibt die bilineare Interpolation mit Vorfilterung an. |
| [InterpolationModeHighQualityBicubic](#InterpolationModeHighQualityBicubic) | Gibt die bikubische Interpolation mit Vorfilterung an, die das qualitativ hochwertigste Ergebnis unter diesen Optionen liefert. |
### InterpolationModeDefault {#InterpolationModeDefault}
```
public static final byte InterpolationModeDefault
```


Gibt den Standardinterpolationsmodus an, der als InterpolationModeBilinear definiert ist.

### InterpolationModeLowQuality {#InterpolationModeLowQuality}
```
public static final byte InterpolationModeLowQuality
```


Gibt einen interpolationsmodus von niedriger Qualität an, der als InterpolationModeNearestNeighbor definiert ist.

### InterpolationModeHighQuality {#InterpolationModeHighQuality}
```
public static final byte InterpolationModeHighQuality
```


Gibt einen interpolationsmodus von hoher Qualität an, der als InterpolationModeHighQualityBicubic definiert ist.

### InterpolationModeBilinear {#InterpolationModeBilinear}
```
public static final byte InterpolationModeBilinear
```


Gibt die bilineare Interpolation an, die die nächstgelegene 2x2‑Nachbarschaft bekannter Pixel um das interpolierte Pixel verwendet. Der gewichtete Mittelwert dieser 4 bekannten Pixelwerte bestimmt den dem interpolierten Pixel zuzuweisenden Wert. Das Ergebnis sieht glatter aus als InterpolationModeNearestNeighbor.

### InterpolationModeBicubic {#InterpolationModeBicubic}
```
public static final byte InterpolationModeBicubic
```


Gibt die bikubische Interpolation an, die die nächstgelegene 4x4‑Nachbarschaft bekannter Pixel um das interpolierte Pixel verwendet. Der gewichtete Mittelwert dieser 16 bekannten Pixelwerte bestimmt den dem interpolierten Pixel zuzuweisenden Wert. Da die bekannten Pixel wahrscheinlich unterschiedliche Abstände zum interpolierten Pixel haben, erhalten näherliegende Pixel ein höheres Gewicht bei der Berechnung. Das Ergebnis sieht glatter aus als InterpolationModeBilinear.

### InterpolationModeNearestNeighbor {#InterpolationModeNearestNeighbor}
```
public static final byte InterpolationModeNearestNeighbor
```


Gibt die nächstgelegene Nachbarinterpolation an, die nur den Wert des Pixels verwendet, das dem interpolierten Pixel am nächsten liegt. Dieser Modus dupliziert oder entfernt einfach Pixel und liefert das qualitativ niedrigste Ergebnis unter diesen Optionen.

### InterpolationModeHighQualityBilinear {#InterpolationModeHighQualityBilinear}
```
public static final byte InterpolationModeHighQualityBilinear
```


Gibt die bilineare Interpolation mit Vorfilterung an.

### InterpolationModeHighQualityBicubic {#InterpolationModeHighQualityBicubic}
```
public static final byte InterpolationModeHighQualityBicubic
```


Gibt die bikubische Interpolation mit Vorfilterung an, die das qualitativ hochwertigste Ergebnis unter diesen Optionen liefert.

