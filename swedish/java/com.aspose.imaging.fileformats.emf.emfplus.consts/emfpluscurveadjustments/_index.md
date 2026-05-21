---
title: "EmfPlusCurveAdjustments"
second_title: "Aspose.Imaging för Java API-referens"
description: "CurveAdjustments‑enumerationen definierar justeringar som kan tillämpas på bildens färgkurva."
type: docs
weight: 16
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurveadjustments/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusCurveAdjustments extends System.Enum
```

CurveAdjustments‑enumerationen definierar justeringar som kan tillämpas på bildens färgkurva.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [AdjustExposure](#AdjustExposure) | Anger simuleringen av att öka eller minska exponeringen av en bild. |
| [AdjustDensity](#AdjustDensity) | Anger simuleringen av att öka eller minska densiteten i en bild. |
| [AdjustContrast](#AdjustContrast) | Anger en ökning eller minskning av kontrasten i en bild. |
| [AdjustHighlight](#AdjustHighlight) | Anger en ökning eller minskning av värdet för en färgkanal i en bild, om den kanalen redan har ett värde som är över halva intensiteten. |
| [AdjustShadow](#AdjustShadow) | Anger en ökning eller minskning av värdet för en färgkanal i en bild, om den kanalen redan har ett värde som är under halva intensiteten. |
| [AdjustMidtone](#AdjustMidtone) | Anger en justering som ljusar upp eller mörkar en bild. |
| [AdjustWhiteSaturation](#AdjustWhiteSaturation) | Specificerar en justering av den vita mättnaden i en bild, definierad som det maximala värdet i intensitetsintervallet för en given färgkanal, vars intervall vanligtvis är 0 till 255. |
| [AdjustBlackSaturation](#AdjustBlackSaturation) | Specificerar en justering av den svarta mättnaden i en bild, vilket är det minsta värdet i intensitetsintervallet för en given färgkanal, vilket vanligtvis är 0 till 255. |
### AdjustExposure {#AdjustExposure}
```
public static final int AdjustExposure
```


Anger simuleringen av att öka eller minska exponeringen av en bild.

### AdjustDensity {#AdjustDensity}
```
public static final int AdjustDensity
```


Anger simuleringen av att öka eller minska densiteten i en bild.

### AdjustContrast {#AdjustContrast}
```
public static final int AdjustContrast
```


Anger en ökning eller minskning av kontrasten i en bild.

### AdjustHighlight {#AdjustHighlight}
```
public static final int AdjustHighlight
```


Specificerar en ökning eller minskning av värdet för en färgkanal i en bild, om den kanalen redan har ett värde som är över halva intensiteten. Denna justering kan användas för att öka definitionen i de ljusa områdena i en bild utan att påverka de mörka områdena.

### AdjustShadow {#AdjustShadow}
```
public static final int AdjustShadow
```


Specificerar en ökning eller minskning av värdet för en färgkanal i en bild, om den kanalen redan har ett värde som är under halva intensiteten. Denna justering kan användas för att öka definitionen i de mörka områdena i en bild utan att påverka de ljusa områdena.

### AdjustMidtone {#AdjustMidtone}
```
public static final int AdjustMidtone
```


Specificerar en justering som ljusar upp eller mörkar en bild. Färgkanalvärden i mitten av intensitetsintervallet ändras mer än färgkanalvärden nära de minsta eller största intensitetstopparna. Denna justering kan användas för att ljusa upp eller mörka en bild utan att förlora kontrasten mellan de mörkaste och ljusaste delarna av bilden.

### AdjustWhiteSaturation {#AdjustWhiteSaturation}
```
public static final int AdjustWhiteSaturation
```


Specificerar en justering av den vita mättnaden i en bild, definierad som det maximala värdet i intensitetsintervallet för en given färgkanal, vars intervall vanligtvis är 0 till 255.

--------------------

Till exempel specificerar ett justeringsvärde för vit mättnad på 240 att färgkanalvärden i intervallet 0 till 240 justeras så att de sprids över intervallet 0 till 255, med färgkanalvärden större än 240 satta till 255.

### AdjustBlackSaturation {#AdjustBlackSaturation}
```
public static final int AdjustBlackSaturation
```


Specificerar en justering av den svarta mättnaden i en bild, vilket är det minsta värdet i intensitetsintervallet för en given färgkanal, vilket vanligtvis är 0 till 255.

--------------------

Till exempel specificerar ett justeringsvärde för svart mättnad på 15 att färgkanalvärden i intervallet 15 till 255 justeras så att de sprids över intervallet 0 till 255, med färgkanalvärden mindre än 15 satta till 0.

