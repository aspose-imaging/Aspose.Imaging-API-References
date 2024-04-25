---
title: HatchStyle
second_title: Aspose.Imaging for Java API Reference
description: Specifies the different patterns available for HatchBrush objects.
type: docs
weight: 54
url: /com.aspose.imaging/hatchstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HatchStyle extends System.Enum
```

Specifies the different patterns available for `HatchBrush` objects.
## Fields

| Field | Description |
| --- | --- |
| [Horizontal](#Horizontal) | A pattern of horizontal lines. |
| [Min](#Min) | Specifies hatch style Horizontal. |
| [Vertical](#Vertical) | A pattern of vertical lines. |
| [ForwardDiagonal](#ForwardDiagonal) | A pattern of lines on a diagonal from upper left to lower right. |
| [BackwardDiagonal](#BackwardDiagonal) | A pattern of lines on a diagonal from upper right to lower left. |
| [Cross](#Cross) | Specifies horizontal and vertical lines that cross. |
| [LargeGrid](#LargeGrid) | Specifies the hatch style Cross. |
| [Max](#Max) | Specifies hatch style SolidDiamond. |
| [DiagonalCross](#DiagonalCross) | A pattern of crisscross diagonal lines. |
| [Percent05](#Percent05) | Specifies a 5-percent hatch. |
| [Percent10](#Percent10) | Specifies a 10-percent hatch. |
| [Percent20](#Percent20) | Specifies a 20-percent hatch. |
| [Percent25](#Percent25) | Specifies a 25-percent hatch. |
| [Percent30](#Percent30) | Specifies a 30-percent hatch. |
| [Percent40](#Percent40) | Specifies a 40-percent hatch. |
| [Percent50](#Percent50) | Specifies a 50-percent hatch. |
| [Percent60](#Percent60) | Specifies a 60-percent hatch. |
| [Percent70](#Percent70) | Specifies a 70-percent hatch. |
| [Percent75](#Percent75) | Specifies a 75-percent hatch. |
| [Percent80](#Percent80) | Specifies a 80-percent hatch. |
| [Percent90](#Percent90) | Specifies a 90-percent hatch. |
| [LightDownwardDiagonal](#LightDownwardDiagonal) | Specifies diagonal lines that slant to the right from top points to bottom points and are spaced 50 percent closer together than ForwardDiagonal, but are not antialiased. |
| [LightUpwardDiagonal](#LightUpwardDiagonal) | Specifies diagonal lines that slant to the left from top points to bottom points and are spaced 50 percent closer together than BackwardDiagonal, but they are not antialiased. |
| [DarkDownwardDiagonal](#DarkDownwardDiagonal) | Specifies diagonal lines that slant to the right from top points to bottom points, are spaced 50 percent closer together than, and are twice the width of ForwardDiagonal. |
| [DarkUpwardDiagonal](#DarkUpwardDiagonal) | Specifies diagonal lines that slant to the left from top points to bottom points, are spaced 50 percent closer together than BackwardDiagonal, and are twice its width, but the lines are not antialiased. |
| [WideDownwardDiagonal](#WideDownwardDiagonal) | Specifies diagonal lines that slant to the right from top points to bottom points, have the same spacing as hatch style ForwardDiagonal, and are triple its width, but are not antialiased. |
| [WideUpwardDiagonal](#WideUpwardDiagonal) | Specifies diagonal lines that slant to the left from top points to bottom points, have the same spacing as hatch style BackwardDiagonal, and are triple its width, but are not antialiased. |
| [LightVertical](#LightVertical) | Specifies vertical lines that are spaced 50 percent closer together than Vertical. |
| [LightHorizontal](#LightHorizontal) | Specifies horizontal lines that are spaced 50 percent closer together than Horizontal. |
| [NarrowVertical](#NarrowVertical) | Specifies vertical lines that are spaced 75 percent closer together than hatch style Vertical (or 25 percent closer together than LightVertical). |
| [NarrowHorizontal](#NarrowHorizontal) | Specifies horizontal lines that are spaced 75 percent closer together than hatch style Horizontal (or 25 percent closer together than LightHorizontal). |
| [DarkVertical](#DarkVertical) | Specifies vertical lines that are spaced 50 percent closer together than Vertical and are twice its width. |
| [DarkHorizontal](#DarkHorizontal) | Specifies horizontal lines that are spaced 50 percent closer together than Horizontal and are twice the width of Horizontal. |
| [DashedDownwardDiagonal](#DashedDownwardDiagonal) | Specifies dashed diagonal lines, that slant to the right from top points to bottom points. |
| [DashedUpwardDiagonal](#DashedUpwardDiagonal) | Specifies dashed diagonal lines, that slant to the left from top points to bottom points. |
| [DashedHorizontal](#DashedHorizontal) | Specifies dashed horizontal lines. |
| [DashedVertical](#DashedVertical) | Specifies dashed vertical lines. |
| [SmallConfetti](#SmallConfetti) | Specifies a hatch that has the appearance of confetti. |
| [LargeConfetti](#LargeConfetti) | Specifies a hatch that has the appearance of confetti, and is composed of larger pieces than SmallConfetti. |
| [ZigZag](#ZigZag) | Specifies horizontal lines that are composed of zigzags. |
| [Wave](#Wave) | Specifies horizontal lines that are composed of tildes. |
| [DiagonalBrick](#DiagonalBrick) | Specifies a hatch that has the appearance of layered bricks that slant to the left from top points to bottom points. |
| [HorizontalBrick](#HorizontalBrick) | Specifies a hatch that has the appearance of horizontally layered bricks. |
| [Weave](#Weave) | Specifies a hatch that has the appearance of a woven material. |
| [Plaid](#Plaid) | Specifies a hatch that has the appearance of a plaid material. |
| [Divot](#Divot) | Specifies a hatch that has the appearance of divots. |
| [DottedGrid](#DottedGrid) | Specifies horizontal and vertical lines, each of which is composed of dots, that cross. |
| [DottedDiamond](#DottedDiamond) | Specifies forward diagonal and backward diagonal lines, each of which is composed of dots, that cross. |
| [Shingle](#Shingle) | Specifies a hatch that has the appearance of diagonally layered shingles that slant to the right from top points to bottom points. |
| [Trellis](#Trellis) | Specifies a hatch that has the appearance of a trellis. |
| [Sphere](#Sphere) | Specifies a hatch that has the appearance of spheres laid adjacent to one another. |
| [SmallGrid](#SmallGrid) | Specifies horizontal and vertical lines that cross and are spaced 50 percent closer together than hatch style Cross. |
| [SmallCheckerBoard](#SmallCheckerBoard) | Specifies a hatch that has the appearance of a checkerboard. |
| [LargeCheckerBoard](#LargeCheckerBoard) | Specifies a hatch that has the appearance of a checkerboard with squares that are twice the size of SmallCheckerBoard. |
| [OutlinedDiamond](#OutlinedDiamond) | Specifies forward diagonal and backward diagonal lines that cross but are not antialiased. |
| [SolidDiamond](#SolidDiamond) | Specifies a hatch that has the appearance of a checkerboard placed diagonally. |
### Horizontal {#Horizontal}
```
public static final int Horizontal
```


A pattern of horizontal lines.

### Min {#Min}
```
public static final int Min
```


Specifies hatch style Horizontal.

### Vertical {#Vertical}
```
public static final int Vertical
```


A pattern of vertical lines.

### ForwardDiagonal {#ForwardDiagonal}
```
public static final int ForwardDiagonal
```


A pattern of lines on a diagonal from upper left to lower right.

### BackwardDiagonal {#BackwardDiagonal}
```
public static final int BackwardDiagonal
```


A pattern of lines on a diagonal from upper right to lower left.

### Cross {#Cross}
```
public static final int Cross
```


Specifies horizontal and vertical lines that cross.

### LargeGrid {#LargeGrid}
```
public static final int LargeGrid
```


Specifies the hatch style Cross.

### Max {#Max}
```
public static final int Max
```


Specifies hatch style SolidDiamond.

### DiagonalCross {#DiagonalCross}
```
public static final int DiagonalCross
```


A pattern of crisscross diagonal lines.

### Percent05 {#Percent05}
```
public static final int Percent05
```


Specifies a 5-percent hatch. The ratio of foreground color to background color is 5:95.

### Percent10 {#Percent10}
```
public static final int Percent10
```


Specifies a 10-percent hatch. The ratio of foreground color to background color is 10:90.

### Percent20 {#Percent20}
```
public static final int Percent20
```


Specifies a 20-percent hatch. The ratio of foreground color to background color is 20:80.

### Percent25 {#Percent25}
```
public static final int Percent25
```


Specifies a 25-percent hatch. The ratio of foreground color to background color is 25:75.

### Percent30 {#Percent30}
```
public static final int Percent30
```


Specifies a 30-percent hatch. The ratio of foreground color to background color is 30:70.

### Percent40 {#Percent40}
```
public static final int Percent40
```


Specifies a 40-percent hatch. The ratio of foreground color to background color is 40:60.

### Percent50 {#Percent50}
```
public static final int Percent50
```


Specifies a 50-percent hatch. The ratio of foreground color to background color is 50:50.

### Percent60 {#Percent60}
```
public static final int Percent60
```


Specifies a 60-percent hatch. The ratio of foreground color to background color is 60:40.

### Percent70 {#Percent70}
```
public static final int Percent70
```


Specifies a 70-percent hatch. The ratio of foreground color to background color is 70:30.

### Percent75 {#Percent75}
```
public static final int Percent75
```


Specifies a 75-percent hatch. The ratio of foreground color to background color is 75:25.

### Percent80 {#Percent80}
```
public static final int Percent80
```


Specifies a 80-percent hatch. The ratio of foreground color to background color is 80:100.

### Percent90 {#Percent90}
```
public static final int Percent90
```


Specifies a 90-percent hatch. The ratio of foreground color to background color is 90:10.

### LightDownwardDiagonal {#LightDownwardDiagonal}
```
public static final int LightDownwardDiagonal
```


Specifies diagonal lines that slant to the right from top points to bottom points and are spaced 50 percent closer together than ForwardDiagonal, but are not antialiased.

### LightUpwardDiagonal {#LightUpwardDiagonal}
```
public static final int LightUpwardDiagonal
```


Specifies diagonal lines that slant to the left from top points to bottom points and are spaced 50 percent closer together than BackwardDiagonal, but they are not antialiased.

### DarkDownwardDiagonal {#DarkDownwardDiagonal}
```
public static final int DarkDownwardDiagonal
```


Specifies diagonal lines that slant to the right from top points to bottom points, are spaced 50 percent closer together than, and are twice the width of ForwardDiagonal. This hatch pattern is not antialiased.

### DarkUpwardDiagonal {#DarkUpwardDiagonal}
```
public static final int DarkUpwardDiagonal
```


Specifies diagonal lines that slant to the left from top points to bottom points, are spaced 50 percent closer together than BackwardDiagonal, and are twice its width, but the lines are not antialiased.

### WideDownwardDiagonal {#WideDownwardDiagonal}
```
public static final int WideDownwardDiagonal
```


Specifies diagonal lines that slant to the right from top points to bottom points, have the same spacing as hatch style ForwardDiagonal, and are triple its width, but are not antialiased.

### WideUpwardDiagonal {#WideUpwardDiagonal}
```
public static final int WideUpwardDiagonal
```


Specifies diagonal lines that slant to the left from top points to bottom points, have the same spacing as hatch style BackwardDiagonal, and are triple its width, but are not antialiased.

### LightVertical {#LightVertical}
```
public static final int LightVertical
```


Specifies vertical lines that are spaced 50 percent closer together than Vertical.

### LightHorizontal {#LightHorizontal}
```
public static final int LightHorizontal
```


Specifies horizontal lines that are spaced 50 percent closer together than Horizontal.

### NarrowVertical {#NarrowVertical}
```
public static final int NarrowVertical
```


Specifies vertical lines that are spaced 75 percent closer together than hatch style Vertical (or 25 percent closer together than LightVertical).

### NarrowHorizontal {#NarrowHorizontal}
```
public static final int NarrowHorizontal
```


Specifies horizontal lines that are spaced 75 percent closer together than hatch style Horizontal (or 25 percent closer together than LightHorizontal).

### DarkVertical {#DarkVertical}
```
public static final int DarkVertical
```


Specifies vertical lines that are spaced 50 percent closer together than Vertical and are twice its width.

### DarkHorizontal {#DarkHorizontal}
```
public static final int DarkHorizontal
```


Specifies horizontal lines that are spaced 50 percent closer together than Horizontal and are twice the width of Horizontal.

### DashedDownwardDiagonal {#DashedDownwardDiagonal}
```
public static final int DashedDownwardDiagonal
```


Specifies dashed diagonal lines, that slant to the right from top points to bottom points.

### DashedUpwardDiagonal {#DashedUpwardDiagonal}
```
public static final int DashedUpwardDiagonal
```


Specifies dashed diagonal lines, that slant to the left from top points to bottom points.

### DashedHorizontal {#DashedHorizontal}
```
public static final int DashedHorizontal
```


Specifies dashed horizontal lines.

### DashedVertical {#DashedVertical}
```
public static final int DashedVertical
```


Specifies dashed vertical lines.

### SmallConfetti {#SmallConfetti}
```
public static final int SmallConfetti
```


Specifies a hatch that has the appearance of confetti.

### LargeConfetti {#LargeConfetti}
```
public static final int LargeConfetti
```


Specifies a hatch that has the appearance of confetti, and is composed of larger pieces than SmallConfetti.

### ZigZag {#ZigZag}
```
public static final int ZigZag
```


Specifies horizontal lines that are composed of zigzags.

### Wave {#Wave}
```
public static final int Wave
```


Specifies horizontal lines that are composed of tildes.

### DiagonalBrick {#DiagonalBrick}
```
public static final int DiagonalBrick
```


Specifies a hatch that has the appearance of layered bricks that slant to the left from top points to bottom points.

### HorizontalBrick {#HorizontalBrick}
```
public static final int HorizontalBrick
```


Specifies a hatch that has the appearance of horizontally layered bricks.

### Weave {#Weave}
```
public static final int Weave
```


Specifies a hatch that has the appearance of a woven material.

### Plaid {#Plaid}
```
public static final int Plaid
```


Specifies a hatch that has the appearance of a plaid material.

### Divot {#Divot}
```
public static final int Divot
```


Specifies a hatch that has the appearance of divots.

### DottedGrid {#DottedGrid}
```
public static final int DottedGrid
```


Specifies horizontal and vertical lines, each of which is composed of dots, that cross.

### DottedDiamond {#DottedDiamond}
```
public static final int DottedDiamond
```


Specifies forward diagonal and backward diagonal lines, each of which is composed of dots, that cross.

### Shingle {#Shingle}
```
public static final int Shingle
```


Specifies a hatch that has the appearance of diagonally layered shingles that slant to the right from top points to bottom points.

### Trellis {#Trellis}
```
public static final int Trellis
```


Specifies a hatch that has the appearance of a trellis.

### Sphere {#Sphere}
```
public static final int Sphere
```


Specifies a hatch that has the appearance of spheres laid adjacent to one another.

### SmallGrid {#SmallGrid}
```
public static final int SmallGrid
```


Specifies horizontal and vertical lines that cross and are spaced 50 percent closer together than hatch style Cross.

### SmallCheckerBoard {#SmallCheckerBoard}
```
public static final int SmallCheckerBoard
```


Specifies a hatch that has the appearance of a checkerboard.

### LargeCheckerBoard {#LargeCheckerBoard}
```
public static final int LargeCheckerBoard
```


Specifies a hatch that has the appearance of a checkerboard with squares that are twice the size of SmallCheckerBoard.

### OutlinedDiamond {#OutlinedDiamond}
```
public static final int OutlinedDiamond
```


Specifies forward diagonal and backward diagonal lines that cross but are not antialiased.

### SolidDiamond {#SolidDiamond}
```
public static final int SolidDiamond
```


Specifies a hatch that has the appearance of a checkerboard placed diagonally.

