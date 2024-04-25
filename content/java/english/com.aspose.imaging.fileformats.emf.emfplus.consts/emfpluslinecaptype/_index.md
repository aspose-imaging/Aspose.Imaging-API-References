---
title: EmfPlusLineCapType
second_title: Aspose.Imaging for Java API Reference
description: The LineCapType enumeration defines types of line caps to use at the ends of lines that are drawn with graphics pens.
type: docs
weight: 31
url: /com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusLineCapType extends System.Enum
```

The LineCapType enumeration defines types of line caps to use at the ends of lines that are drawn with graphics pens.

--------------------

Graphics line caps are specified by [EmfPlusPen](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspen) objects (section 2.2.1.7).
## Fields

| Field | Description |
| --- | --- |
| [LineCapTypeFlat](#LineCapTypeFlat) | Specifies a squared-off line cap. |
| [LineCapTypeSquare](#LineCapTypeSquare) | Specifies a square line cap. |
| [LineCapTypeRound](#LineCapTypeRound) | Specifies a circular line cap. |
| [LineCapTypeTriangle](#LineCapTypeTriangle) | Specifies a triangular line cap. |
| [LineCapTypeNoAnchor](#LineCapTypeNoAnchor) | Specifies that the line end is not anchored. |
| [LineCapTypeSquareAnchor](#LineCapTypeSquareAnchor) | Specifies that the line end is anchored with a square line cap. |
| [LineCapTypeRoundAnchor](#LineCapTypeRoundAnchor) | Specifies that the line end is anchored with a circular line cap. |
| [LineCapTypeDiamondAnchor](#LineCapTypeDiamondAnchor) | Specifies that the line end is anchored with a diamond-shaped line cap, which is a square turned at 45 degrees. |
| [LineCapTypeArrowAnchor](#LineCapTypeArrowAnchor) | Specifies that the line end is anchored with an arrowhead shape. |
| [LineCapTypeAnchorMask](#LineCapTypeAnchorMask) | Mask used to check whether a line cap is an anchor cap. |
| [LineCapTypeCustom](#LineCapTypeCustom) | Specifies a custom line cap. |
### LineCapTypeFlat {#LineCapTypeFlat}
```
public static final int LineCapTypeFlat
```


Specifies a squared-off line cap. The end of the line MUST be the last point in the line.

### LineCapTypeSquare {#LineCapTypeSquare}
```
public static final int LineCapTypeSquare
```


Specifies a square line cap. The center of the square MUST be located at the last point in the line. The width of the square is the line width.

### LineCapTypeRound {#LineCapTypeRound}
```
public static final int LineCapTypeRound
```


Specifies a circular line cap. The center of the circle MUST be located at the last point in the line. The diameter of the circle is the line width.

### LineCapTypeTriangle {#LineCapTypeTriangle}
```
public static final int LineCapTypeTriangle
```


Specifies a triangular line cap. The base of the triangle MUST be located at the last point in the line. The base of the triangle is the line width.

### LineCapTypeNoAnchor {#LineCapTypeNoAnchor}
```
public static final int LineCapTypeNoAnchor
```


Specifies that the line end is not anchored.

### LineCapTypeSquareAnchor {#LineCapTypeSquareAnchor}
```
public static final int LineCapTypeSquareAnchor
```


Specifies that the line end is anchored with a square line cap. The center of the square MUST be located at the last point in the line. The height and width of the square are the line width.

### LineCapTypeRoundAnchor {#LineCapTypeRoundAnchor}
```
public static final int LineCapTypeRoundAnchor
```


Specifies that the line end is anchored with a circular line cap. The center of the circle MUST be located at the last point in the line. The circle SHOULD be wider than the line.

### LineCapTypeDiamondAnchor {#LineCapTypeDiamondAnchor}
```
public static final int LineCapTypeDiamondAnchor
```


Specifies that the line end is anchored with a diamond-shaped line cap, which is a square turned at 45 degrees. The center of the diamond MUST be located at the last point in the line. The diamond SHOULD be wider than the line.

### LineCapTypeArrowAnchor {#LineCapTypeArrowAnchor}
```
public static final int LineCapTypeArrowAnchor
```


Specifies that the line end is anchored with an arrowhead shape. The arrowhead point MUST be located at the last point in the line. The arrowhead SHOULD be wider than the line.

### LineCapTypeAnchorMask {#LineCapTypeAnchorMask}
```
public static final int LineCapTypeAnchorMask
```


Mask used to check whether a line cap is an anchor cap.

### LineCapTypeCustom {#LineCapTypeCustom}
```
public static final int LineCapTypeCustom
```


Specifies a custom line cap.

