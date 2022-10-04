---
title: EmfPlusInterpolationMode
second_title: Aspose.Imaging für .NET-API-Referenz
description: Die InterpolationMode-Enumeration definiert Methoden zur Skalierung einschließlich Dehnung und Verkleinerung.
type: docs
weight: 4870
url: /de/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---
## EmfPlusInterpolationMode enumeration

Die InterpolationMode-Enumeration definiert Methoden zur Skalierung, einschließlich Dehnung und Verkleinerung.

```csharp
public enum EmfPlusInterpolationMode : byte
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| InterpolationModeDefault | `0` | Gibt den Standard-Interpolationsmodus an, der als InterpolationModeBilinear definiert ist. |
| InterpolationModeLowQuality | `1` | Gibt einen Interpolationsmodus niedriger Qualität an, der als InterpolationModeNearestNeighbor definiert ist. |
| InterpolationModeHighQuality | `2` | Gibt einen hochwertigen Interpolationsmodus an, der als InterpolationModeHighQualityBicubic definiert ist. |
| InterpolationModeBilinear | `3` | Gibt die bilineare Interpolation an, die die nächste 2x2-Nachbarschaft bekannter Pixel verwendet, die das interpolierte Pixel umgeben. Der gewichtete Durchschnitt dieser 4 bekannten Pixelwerte bestimmt den Wert, der dem interpolierten Pixel zuzuweisen ist. Das Ergebnis sieht glatter aus als InterpolationModeNearestNeighbor. |
| InterpolationModeBicubic | `4` | Gibt die bikubische Interpolation an, die die nächste 4x4-Nachbarschaft bekannter Pixel verwendet, die das interpolierte Pixel umgeben. Der gewichtete Durchschnitt dieser 16 bekannten Pixelwerte bestimmt den Wert, der dem interpolierten Pixel zuzuweisen ist. Da sich die bekannten Pixel wahrscheinlich in unterschiedlichen Abständen von dem interpolierten Pixel befinden, erhalten näher liegende Pixel bei der Berechnung ein höheres Gewicht. Das Ergebnis sieht glatter aus als InterpolationModeBilinear. |
| InterpolationModeNearestNeighbor | `5` | Gibt die Nearest-Neighbor-Interpolation an, die nur den Wert des Pixels verwendet, das dem interpolierten Pixel am nächsten liegt. Dieser Modus dupliziert oder entfernt einfach Pixel und erzeugt das Ergebnis mit der niedrigsten Qualität unter diesen Optionen. |
| InterpolationModeHighQualityBilinear | `6` | Gibt die bilineare Interpolation mit Vorfilterung an. |
| InterpolationModeHighQualityBicubic | `7` | Gibt die bikubische Interpolation mit Vorfilterung an, die unter diesen Optionen das qualitativ hochwertigste Ergebnis liefert. |

### Siehe auch

* namensraum [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->