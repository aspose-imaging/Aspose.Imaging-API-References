---
title: "EmfPlusFilterType"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die FilterType-Aufzählung definiert Typen von Filteralgorithmen, die zur Verbesserung von Text‑ und Grafikqualität sowie zur Bilddarstellung verwendet werden können."
type: docs
weight: 22
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusFilterType extends System.Enum
```

Die FilterType-Aufzählung definiert Typen von Filteralgorithmen, die zur Verbesserung von Text‑ und Grafikqualität sowie zur Bilddarstellung verwendet werden können.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [FilterTypeNone](#FilterTypeNone) | Gibt an, dass keine Filterung durchgeführt wird. |
| [FilterTypePoint](#FilterTypePoint) | Gibt an, dass jeder Zielpixel durch Abtasten des nächstgelegenen Pixels aus dem Quellbild berechnet wird. |
| [FilterTypeLinear](#FilterTypeLinear) | Gibt an, dass lineare Interpolation mittels des gewichteten Durchschnitts eines 2x2‑Pixel‑Bereichs um das Quellpixel herum durchgeführt wird. |
| [FilterTypeTriangle](#FilterTypeTriangle) | Gibt an, dass jeder Pixel im Quellbild gleichmäßig zum Zielbild beiträgt. |
| [FilterTypeBox](#FilterTypeBox) | Gibt einen Box-Filter-Algorithmus an, bei dem jeder Zielpixel durch Mittelung eines Rechtecks von Quellpixeln berechnet wird. |
| [FilterTypePyramidalQuad](#FilterTypePyramidalQuad) | Gibt an, dass ein 4‑Sample‑Zelt‑Filter verwendet wird. |
| [FilterTypeGaussianQuad](#FilterTypeGaussianQuad) | Gibt an, dass ein 4‑Sample‑Gauß‑Filter verwendet wird, der einen Unschärfeeffekt auf ein Bild erzeugt. |
### FilterTypeNone {#FilterTypeNone}
```
public static final byte FilterTypeNone
```


Gibt an, dass keine Filterung durchgeführt wird.

### FilterTypePoint {#FilterTypePoint}
```
public static final byte FilterTypePoint
```


Gibt an, dass jeder Zielpixel durch Abtasten des nächstgelegenen Pixels aus dem Quellbild berechnet wird.

### FilterTypeLinear {#FilterTypeLinear}
```
public static final byte FilterTypeLinear
```


Gibt an, dass lineare Interpolation mittels des gewichteten Durchschnitts eines 2x2‑Pixel‑Bereichs um das Quellpixel herum durchgeführt wird.

### FilterTypeTriangle {#FilterTypeTriangle}
```
public static final byte FilterTypeTriangle
```


Gibt an, dass jeder Pixel im Quellbild gleichmäßig zum Zielbild beiträgt. Dies ist der langsamste der Filteralgorithmen.

### FilterTypeBox {#FilterTypeBox}
```
public static final byte FilterTypeBox
```


Gibt einen Boxfilter-Algorithmus an, bei dem jedes Zielpixel durch Mittelung eines Rechtecks von Quellpixeln berechnet wird. Dieser Algorithmus ist nur beim Verkleinern der Größe eines Bildes nützlich.

### FilterTypePyramidalQuad {#FilterTypePyramidalQuad}
```
public static final byte FilterTypePyramidalQuad
```


Gibt an, dass ein 4‑Sample‑Zelt‑Filter verwendet wird.

### FilterTypeGaussianQuad {#FilterTypeGaussianQuad}
```
public static final byte FilterTypeGaussianQuad
```


Gibt an, dass ein 4‑Sample‑Gauß‑Filter verwendet wird, der einen Unschärfeeffekt auf ein Bild erzeugt.

