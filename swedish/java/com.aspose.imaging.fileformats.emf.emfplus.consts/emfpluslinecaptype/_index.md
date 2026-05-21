---
title: "EmfPlusLineCapType"
second_title: "Aspose.Imaging för Java API-referens"
description: "LineCapType‑enumerationen definierar typer av linjekapslar att använda vid ändarna på linjer som ritas med grafikpennor."
type: docs
weight: 31
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusLineCapType extends System.Enum
```

LineCapType‑enumerationen definierar typer av linjekapslar att använda vid ändarna på linjer som ritas med grafikpennor.

--------------------

Grafiklinjekappar specificeras av [EmfPlusPen](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspen) objekt (avsnitt 2.2.1.7).
## Fält

| Fält | Beskrivning |
| --- | --- |
| [LineCapTypeFlat](#LineCapTypeFlat) | Anger en fyrkantig linjekap. |
| [LineCapTypeSquare](#LineCapTypeSquare) | Anger en fyrkantig linjespets. |
| [LineCapTypeRound](#LineCapTypeRound) | Anger en cirkulär linjekap. |
| [LineCapTypeTriangle](#LineCapTypeTriangle) | Anger en triangulär linjespets. |
| [LineCapTypeNoAnchor](#LineCapTypeNoAnchor) | Anger att linjeänden inte är förankrad. |
| [LineCapTypeSquareAnchor](#LineCapTypeSquareAnchor) | Anger att linjeänden är förankrad med en fyrkantig linjekap. |
| [LineCapTypeRoundAnchor](#LineCapTypeRoundAnchor) | Anger att linjeänden är förankrad med en cirkulär linjekap. |
| [LineCapTypeDiamondAnchor](#LineCapTypeDiamondAnchor) | Anger att linjeänden är förankrad med en rombformad linjekap, som är en fyrkant vriden 45 grader. |
| [LineCapTypeArrowAnchor](#LineCapTypeArrowAnchor) | Anger att linjeänden är förankrad med en pilspetsform. |
| [LineCapTypeAnchorMask](#LineCapTypeAnchorMask) | Mask som används för att kontrollera om en linjekap är en förankringskap. |
| [LineCapTypeCustom](#LineCapTypeCustom) | Anger en anpassad linjekap. |
### LineCapTypeFlat {#LineCapTypeFlat}
```
public static final int LineCapTypeFlat
```


Anger en fyrkantig linjekap. Linjeänden MÅSTE vara den sista punkten i linjen.

### LineCapTypeSquare {#LineCapTypeSquare}
```
public static final int LineCapTypeSquare
```


Anger en fyrkantig linjekap. Centrum av fyrkanten MÅSTE ligga på den sista punkten i linjen. Bredden på fyrkanten är linjebredden.

### LineCapTypeRound {#LineCapTypeRound}
```
public static final int LineCapTypeRound
```


Anger en cirkulär linjekap. Centrum av cirkeln MÅSTE ligga på den sista punkten i linjen. Diametern på cirkeln är linjebredden.

### LineCapTypeTriangle {#LineCapTypeTriangle}
```
public static final int LineCapTypeTriangle
```


Anger en triangulär linjekap. Basen av triangeln MÅSTE ligga på den sista punkten i linjen. Basen av triangeln är linjebredden.

### LineCapTypeNoAnchor {#LineCapTypeNoAnchor}
```
public static final int LineCapTypeNoAnchor
```


Anger att linjeänden inte är förankrad.

### LineCapTypeSquareAnchor {#LineCapTypeSquareAnchor}
```
public static final int LineCapTypeSquareAnchor
```


Anger att linjeänden är förankrad med en fyrkantig linjekap. Centrum av fyrkanten MÅSTE ligga på den sista punkten i linjen. Höjden och bredden på fyrkanten är linjebredden.

### LineCapTypeRoundAnchor {#LineCapTypeRoundAnchor}
```
public static final int LineCapTypeRoundAnchor
```


Anger att linjeänden är förankrad med en cirkulär linjekap. Centrum av cirkeln MÅSTE ligga på den sista punkten i linjen. Cirkeln BÖR vara bredare än linjen.

### LineCapTypeDiamondAnchor {#LineCapTypeDiamondAnchor}
```
public static final int LineCapTypeDiamondAnchor
```


Anger att linjeänden är förankrad med en rombformad linjekap, som är en fyrkant vriden 45 grader. Centrum av romben MÅSTE ligga på den sista punkten i linjen. Romben BÖR vara bredare än linjen.

### LineCapTypeArrowAnchor {#LineCapTypeArrowAnchor}
```
public static final int LineCapTypeArrowAnchor
```


Anger att linjeänden är förankrad med en pilspetsform. Pilspetsens spets MÅSTE ligga på den sista punkten i linjen. Pilspetsen BÖR vara bredare än linjen.

### LineCapTypeAnchorMask {#LineCapTypeAnchorMask}
```
public static final int LineCapTypeAnchorMask
```


Mask som används för att kontrollera om en linjekap är en förankringskap.

### LineCapTypeCustom {#LineCapTypeCustom}
```
public static final int LineCapTypeCustom
```


Anger en anpassad linjekap.

