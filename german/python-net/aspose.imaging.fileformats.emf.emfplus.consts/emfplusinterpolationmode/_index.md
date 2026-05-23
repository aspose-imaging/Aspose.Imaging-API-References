---
title: "EmfPlusInterpolationMode Aufzählung"
type: docs
weight: 200
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---

Die InterpolationMode-Aufzählung definiert Methoden zur Skalierung, einschließlich Dehnung und Verkleinerung.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusInterpolationMode

## **Members**
| **Member name** | **Beschreibung** |
| :- | :- |
| INTERPOLATION_MODE_BICUBIC | Gibt bicubische Interpolation an, die das nächstgelegene 4x4‑Nachbarschafts‑Raster bekannter Pixel um das interpolierte Pixel verwendet. Der gewichtete Mittelwert dieser 16 bekannten Pixelwerte bestimmt den Wert, der dem interpolierten Pixel zugewiesen wird. Da die bekannten Pixel wahrscheinlich unterschiedliche Abstände zum interpolierten Pixel haben, erhalten näherliegende Pixel ein höheres Gewicht bei der Berechnung. Das Ergebnis wirkt glatter als InterpolationModeBilinear. |
| INTERPOLATION_MODE_BILINEAR | Gibt bilineare Interpolation an, die das nächstgelegene 2x2‑Nachbarschafts‑Raster bekannter Pixel um das interpolierte Pixel verwendet. Der gewichtete Mittelwert dieser 4 bekannten Pixelwerte bestimmt den Wert, der dem interpolierten Pixel zugewiesen wird. Das Ergebnis wirkt glatter als InterpolationModeNearestNeighbor. |
| INTERPOLATION_MODE_DEFAULT | Gibt den Standardinterpolationsmodus an, der als InterpolationModeBilinear definiert ist. |
| INTERPOLATION_MODE_HIGH_QUALITY | Gibt einen hochqualitativen Interpolationsmodus an, der als InterpolationModeHighQualityBicubic definiert ist. |
| INTERPOLATION_MODE_HIGH_QUALITY_BICUBIC | Gibt eine bikubische Interpolation mit Vorfilterung an, die das qualitativ hochwertigste Ergebnis unter diesen Optionen liefert. |
| INTERPOLATION_MODE_HIGH_QUALITY_BILINEAR | Gibt eine bilineare Interpolation mit Vorfilterung an. |
| INTERPOLATION_MODE_LOW_QUALITY | Gibt einen niedrigqualitativen Interpolationsmodus an, der als InterpolationModeNearestNeighbor definiert ist. |
| INTERPOLATION_MODE_NEAREST_NEIGHBOR | Gibt eine Nearest-Neighbor-Interpolation an, die nur den Wert des Pixels verwendet, das dem interpolierten Pixel am nächsten liegt. Dieser Modus dupliziert oder entfernt einfach Pixel und erzeugt das qualitativ niedrigste Ergebnis unter diesen Optionen. |
