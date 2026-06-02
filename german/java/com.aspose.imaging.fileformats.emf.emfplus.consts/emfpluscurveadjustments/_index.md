---
title: "EmfPlusCurveAdjustments"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Aufzählung CurveAdjustments definiert Anpassungen, die auf die Farbkurve eines Bildes angewendet werden können."
type: docs
weight: 16
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurveadjustments/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusCurveAdjustments extends System.Enum
```

Die Aufzählung CurveAdjustments definiert Anpassungen, die auf die Farbkurve eines Bildes angewendet werden können.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [AdjustExposure](#AdjustExposure) | Gibt die Simulation der Erhöhung oder Verringerung der Belichtung eines Bildes an. |
| [AdjustDensity](#AdjustDensity) | Gibt die Simulation der Erhöhung oder Verringerung der Dichte eines Bildes an. |
| [AdjustContrast](#AdjustContrast) | Gibt eine Erhöhung oder Verringerung des Kontrasts eines Bildes an. |
| [AdjustHighlight](#AdjustHighlight) | Gibt eine Erhöhung oder Verringerung des Wertes eines Farbkanals eines Bildes an, wenn dieser Kanal bereits einen Wert über der halben Intensität hat. |
| [AdjustShadow](#AdjustShadow) | Gibt eine Erhöhung oder Verringerung des Wertes eines Farbkanals eines Bildes an, wenn dieser Kanal bereits einen Wert unter der halben Intensität hat. |
| [AdjustMidtone](#AdjustMidtone) | Gibt eine Anpassung an, die ein Bild aufhellt oder abdunkelt. |
| [AdjustWhiteSaturation](#AdjustWhiteSaturation) | Gibt eine Anpassung der Weißsättigung eines Bildes an, definiert als den Maximalwert im Intensitätsbereich eines bestimmten Farbkanals, dessen Bereich typischerweise 0 bis 255 beträgt. |
| [AdjustBlackSaturation](#AdjustBlackSaturation) | Gibt eine Anpassung der Schwarzsättigung eines Bildes an, die den Minimalwert im Intensitätsbereich eines bestimmten Farbkanals darstellt, der typischerweise 0 bis 255 beträgt. |
### AdjustExposure {#AdjustExposure}
```
public static final int AdjustExposure
```


Gibt die Simulation der Erhöhung oder Verringerung der Belichtung eines Bildes an.

### AdjustDensity {#AdjustDensity}
```
public static final int AdjustDensity
```


Gibt die Simulation der Erhöhung oder Verringerung der Dichte eines Bildes an.

### AdjustContrast {#AdjustContrast}
```
public static final int AdjustContrast
```


Gibt eine Erhöhung oder Verringerung des Kontrasts eines Bildes an.

### AdjustHighlight {#AdjustHighlight}
```
public static final int AdjustHighlight
```


Gibt eine Erhöhung oder Verringerung des Wertes eines Farbkanals eines Bildes an, wenn dieser Kanal bereits einen Wert über der halben Intensität hat. Diese Anpassung kann verwendet werden, um die Definition in den hellen Bereichen eines Bildes zu erhöhen, ohne die dunklen Bereiche zu beeinflussen.

### AdjustShadow {#AdjustShadow}
```
public static final int AdjustShadow
```


Gibt eine Erhöhung oder Verringerung des Wertes eines Farbkanals eines Bildes an, wenn dieser Kanal bereits einen Wert unterhalb der halben Intensität hat. Diese Anpassung kann verwendet werden, um die Definition in den dunklen Bereichen eines Bildes zu erhöhen, ohne die hellen Bereiche zu beeinflussen.

### AdjustMidtone {#AdjustMidtone}
```
public static final int AdjustMidtone
```


Gibt eine Anpassung an, die ein Bild aufhellt oder abdunkelt. Farbkanalwerte in der Mitte des Intensitätsbereichs werden stärker verändert als Farbkanalwerte nahe den minimalen oder maximalen Intensitätsgrenzen. Diese Anpassung kann verwendet werden, um ein Bild aufzuhellen oder abzudunkeln, ohne den Kontrast zwischen den dunkelsten und hellsten Bildbereichen zu verlieren.

### AdjustWhiteSaturation {#AdjustWhiteSaturation}
```
public static final int AdjustWhiteSaturation
```


Gibt eine Anpassung der Weißsättigung eines Bildes an, definiert als den Maximalwert im Intensitätsbereich eines bestimmten Farbkanals, dessen Bereich typischerweise 0 bis 255 beträgt.

--------------------

Beispielsweise gibt ein Weißsättigungs-Anpassungswert von 240 an, dass Farbkanalwerte im Bereich von 0 bis 240 so angepasst werden, dass sie sich über den Bereich von 0 bis 255 erstrecken, wobei Farbkanalwerte über 240 auf 255 gesetzt werden.

### AdjustBlackSaturation {#AdjustBlackSaturation}
```
public static final int AdjustBlackSaturation
```


Gibt eine Anpassung der Schwarzsättigung eines Bildes an, die den Minimalwert im Intensitätsbereich eines bestimmten Farbkanals darstellt, der typischerweise 0 bis 255 beträgt.

--------------------

Beispielsweise gibt ein Schwarzsättigungs-Anpassungswert von 15 an, dass Farbkanalwerte im Bereich von 15 bis 255 so angepasst werden, dass sie sich über den Bereich von 0 bis 255 erstrecken, wobei Farbkanalwerte unter 15 auf 0 gesetzt werden.

