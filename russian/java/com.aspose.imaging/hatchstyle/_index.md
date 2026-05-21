---
title: "HatchStyle"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Указывает различные шаблоны, доступные для объектов HatchBrush."
type: docs
weight: 54
url: /ru/java/com.aspose.imaging/hatchstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HatchStyle extends System.Enum
```

Указывает различные шаблоны, доступные для объектов `HatchBrush`.
## Поля

| Поле | Описание |
| --- | --- |
| [Horizontal](#Horizontal) | Шаблон из горизонтальных линий. |
| [Min](#Min) | Указывает стиль штриховки Horizontal. |
| [Vertical](#Vertical) | Шаблон из вертикальных линий. |
| [ForwardDiagonal](#ForwardDiagonal) | Шаблон из линий по диагонали от верхнего левого к нижнему правому. |
| [BackwardDiagonal](#BackwardDiagonal) | Шаблон из линий по диагонали от верхнего правого к нижнему левому. |
| [Cross](#Cross) | Указывает пересекающиеся горизонтальные и вертикальные линии. |
| [LargeGrid](#LargeGrid) | Указывает стиль штриховки Cross. |
| [Max](#Max) | Указывает стиль штриховки SolidDiamond. |
| [DiagonalCross](#DiagonalCross) | Шаблон из перекрещивающихся диагональных линий. |
| [Percent05](#Percent05) | Указывает штриховку 5‑процентную. |
| [Percent10](#Percent10) | Указывает штриховку 10‑процентную. |
| [Percent20](#Percent20) | Указывает штриховку 20‑процентную. |
| [Percent25](#Percent25) | Указывает штриховку 25‑процентную. |
| [Percent30](#Percent30) | Указывает штриховку 30‑процентную. |
| [Percent40](#Percent40) | Указывает штриховку 40‑процентную. |
| [Percent50](#Percent50) | Указывает штриховку 50‑процентную. |
| [Percent60](#Percent60) | Указывает штриховку 60 процентов. |
| [Percent70](#Percent70) | Указывает штриховку 70 процентов. |
| [Percent75](#Percent75) | Указывает штриховку 75 процентов. |
| [Percent80](#Percent80) | Указывает штриховку 80 процентов. |
| [Percent90](#Percent90) | Указывает штриховку 90 процентов. |
| [LightDownwardDiagonal](#LightDownwardDiagonal) | Указывает диагональные линии, наклонённые вправо от верхних точек к нижним, расположенные на 50 процентов ближе друг к другу, чем ForwardDiagonal, но без сглаживания. |
| [LightUpwardDiagonal](#LightUpwardDiagonal) | Указывает диагональные линии, наклонённые влево от верхних точек к нижним, расположенные на 50 процентов ближе друг к другу, чем BackwardDiagonal, но без сглаживания. |
| [DarkDownwardDiagonal](#DarkDownwardDiagonal) | Указывает диагональные линии, наклонённые вправо от верхних точек к нижним, расположенные на 50 процентов ближе друг к другу и в два раза шире, чем ForwardDiagonal. |
| [DarkUpwardDiagonal](#DarkUpwardDiagonal) | Указывает диагональные линии, наклонённые влево от верхних точек к нижним, расположенные на 50 процентов ближе друг к другу, чем BackwardDiagonal, и в два раза шире, но линии без сглаживания. |
| [WideDownwardDiagonal](#WideDownwardDiagonal) | Указывает диагональные линии, наклонённые вправо от верхних точек к нижним, имеющие такое же расстояние, как стиль штриховки ForwardDiagonal, и в три раза шире, но без сглаживания. |
| [WideUpwardDiagonal](#WideUpwardDiagonal) | Указывает диагональные линии, наклонённые влево от верхних точек к нижним, имеющие такое же расстояние, как стиль штриховки BackwardDiagonal, и в три раза шире, но без сглаживания. |
| [LightVertical](#LightVertical) | Указывает вертикальные линии, расположенные на 50 процентов ближе друг к другу, чем Vertical. |
| [LightHorizontal](#LightHorizontal) | Указывает горизонтальные линии, расположенные на 50 процентов ближе друг к другу, чем Horizontal. |
| [NarrowVertical](#NarrowVertical) | Указывает вертикальные линии, расположенные на 75 процентов ближе друг к другу, чем стиль штриховки Vertical (или на 25 процентов ближе, чем LightVertical). |
| [NarrowHorizontal](#NarrowHorizontal) | Указывает горизонтальные линии, расположенные на 75 процентов ближе друг к другу, чем стиль штриховки Horizontal (или на 25 процентов ближе, чем LightHorizontal). |
| [DarkVertical](#DarkVertical) | Указывает вертикальные линии, расположенные на 50 процентов ближе друг к другу, чем Vertical, и в два раза шире. |
| [DarkHorizontal](#DarkHorizontal) | Указывает горизонтальные линии, расположенные на 50 процентов ближе друг к другу, чем Horizontal, и в два раза шире, чем Horizontal. |
| [DashedDownwardDiagonal](#DashedDownwardDiagonal) | Указывает пунктирные диагональные линии, наклонённые вправо от верхних точек к нижним. |
| [DashedUpwardDiagonal](#DashedUpwardDiagonal) | Указывает пунктирные диагональные линии, наклонённые влево от верхних точек к нижним. |
| [DashedHorizontal](#DashedHorizontal) | Указывает пунктирные горизонтальные линии. |
| [DashedVertical](#DashedVertical) | Указывает пунктирные вертикальные линии. |
| [SmallConfetti](#SmallConfetti) | Указывает штриховку, имеющую вид конфетти. |
| [LargeConfetti](#LargeConfetti) | Указывает штриховку, имеющую вид конфетти и состоящую из более крупных элементов, чем SmallConfetti. |
| [ZigZag](#ZigZag) | Указывает горизонтальные линии, состоящие из зигзагов. |
| [Wave](#Wave) | Указывает горизонтальные линии, состоящие из тильд. |
| [DiagonalBrick](#DiagonalBrick) | Указывает штриховку, имеющую вид слоистых кирпичей, наклонённых влево от верхних точек к нижним точкам. |
| [HorizontalBrick](#HorizontalBrick) | Указывает штриховку, имеющую вид горизонтально расположенных слоистых кирпичей. |
| [Weave](#Weave) | Указывает штриховку, имеющую вид тканого материала. |
| [Plaid](#Plaid) | Указывает штриховку, имеющую вид клетчатого материала. |
| [Divot](#Divot) | Указывает штриховку, имеющую вид вмятин. |
| [DottedGrid](#DottedGrid) | Указывает горизонтальные и вертикальные линии, каждая из которых состоит из точек и пересекаются. |
| [DottedDiamond](#DottedDiamond) | Указывает прямые и обратные диагональные линии, каждая из которых состоит из точек и пересекаются. |
| [Shingle](#Shingle) | Указывает штриховку, имеющую вид диагонально расположенных черепиц, наклонённых вправо от верхних точек к нижним точкам. |
| [Trellis](#Trellis) | Указывает штриховку, имеющую вид решётки. |
| [Sphere](#Sphere) | Указывает штриховку, имеющую вид соседних друг с другом сфер. |
| [SmallGrid](#SmallGrid) | Указывает горизонтальные и вертикальные линии, которые пересекаются и расположены на 50 % ближе друг к другу, чем стиль штриховки Cross. |
| [SmallCheckerBoard](#SmallCheckerBoard) | Указывает штриховку, имеющую вид шахматной доски. |
| [LargeCheckerBoard](#LargeCheckerBoard) | Указывает штриховку, имеющую вид шахматной доски, квадраты которой вдвое больше, чем у SmallCheckerBoard. |
| [OutlinedDiamond](#OutlinedDiamond) | Указывает прямые и обратные диагональные линии, которые пересекаются, но не сглажены. |
| [SolidDiamond](#SolidDiamond) | Указывает штриховку, имеющую вид шахматной доски, расположенной по диагонали. |
### Horizontal {#Horizontal}
```
public static final int Horizontal
```


Шаблон из горизонтальных линий.

### Min {#Min}
```
public static final int Min
```


Указывает стиль штриховки Horizontal.

### Vertical {#Vertical}
```
public static final int Vertical
```


Шаблон из вертикальных линий.

### ForwardDiagonal {#ForwardDiagonal}
```
public static final int ForwardDiagonal
```


Шаблон из линий по диагонали от верхнего левого к нижнему правому.

### BackwardDiagonal {#BackwardDiagonal}
```
public static final int BackwardDiagonal
```


Шаблон из линий по диагонали от верхнего правого к нижнему левому.

### Cross {#Cross}
```
public static final int Cross
```


Указывает пересекающиеся горизонтальные и вертикальные линии.

### LargeGrid {#LargeGrid}
```
public static final int LargeGrid
```


Указывает стиль штриховки Cross.

### Max {#Max}
```
public static final int Max
```


Указывает стиль штриховки SolidDiamond.

### DiagonalCross {#DiagonalCross}
```
public static final int DiagonalCross
```


Шаблон из перекрещивающихся диагональных линий.

### Percent05 {#Percent05}
```
public static final int Percent05
```


Указывает штриховку 5 %. Соотношение цвета переднего плана к цвету фона составляет 5 : 95.

### Percent10 {#Percent10}
```
public static final int Percent10
```


Указывает штриховку 10 %. Соотношение цвета переднего плана к цвету фона составляет 10 : 90.

### Percent20 {#Percent20}
```
public static final int Percent20
```


Указывает штриховку 20 %. Соотношение цвета переднего плана к цвету фона составляет 20 : 80.

### Percent25 {#Percent25}
```
public static final int Percent25
```


Указывает штриховку 25 %. Соотношение цвета переднего плана к цвету фона составляет 25 : 75.

### Percent30 {#Percent30}
```
public static final int Percent30
```


Указывает штриховку 30 %. Соотношение цвета переднего плана к цвету фона составляет 30 : 70.

### Percent40 {#Percent40}
```
public static final int Percent40
```


Указывает штриховку 40 %. Соотношение цвета переднего плана к цвету фона составляет 40 : 60.

### Percent50 {#Percent50}
```
public static final int Percent50
```


Указывает штриховку 50 %. Соотношение цвета переднего плана к цвету фона составляет 50 : 50.

### Percent60 {#Percent60}
```
public static final int Percent60
```


Указывает штриховку 60 %. Соотношение цвета переднего плана к цвету фона составляет 60 : 40.

### Percent70 {#Percent70}
```
public static final int Percent70
```


Указывает штриховку 70 %. Соотношение цвета переднего плана к цвету фона составляет 70 : 30.

### Percent75 {#Percent75}
```
public static final int Percent75
```


Указывает штриховку 75 %. Соотношение цвета переднего плана к цвету фона составляет 75 : 25.

### Percent80 {#Percent80}
```
public static final int Percent80
```


Указывает штриховку 80 %. Отношение цвета переднего плана к цвету фона составляет 80:100.

### Percent90 {#Percent90}
```
public static final int Percent90
```


Указывает штриховку 90 %. Отношение цвета переднего плана к цвету фона составляет 90:10.

### LightDownwardDiagonal {#LightDownwardDiagonal}
```
public static final int LightDownwardDiagonal
```


Указывает диагональные линии, наклонённые вправо от верхних точек к нижним, расположенные на 50 процентов ближе друг к другу, чем ForwardDiagonal, но без сглаживания.

### LightUpwardDiagonal {#LightUpwardDiagonal}
```
public static final int LightUpwardDiagonal
```


Указывает диагональные линии, наклонённые влево от верхних точек к нижним, расположенные на 50 процентов ближе друг к другу, чем BackwardDiagonal, но без сглаживания.

### DarkDownwardDiagonal {#DarkDownwardDiagonal}
```
public static final int DarkDownwardDiagonal
```


Указывает диагональные линии, наклонённые вправо от верхних точек к нижним, расположенные на 50 % ближе друг к другу и вдвое шире, чем ForwardDiagonal. Этот шаблон штриховки не сглаживается.

### DarkUpwardDiagonal {#DarkUpwardDiagonal}
```
public static final int DarkUpwardDiagonal
```


Указывает диагональные линии, наклонённые влево от верхних точек к нижним, расположенные на 50 процентов ближе друг к другу, чем BackwardDiagonal, и в два раза шире, но линии без сглаживания.

### WideDownwardDiagonal {#WideDownwardDiagonal}
```
public static final int WideDownwardDiagonal
```


Указывает диагональные линии, наклонённые вправо от верхних точек к нижним, имеющие такое же расстояние, как стиль штриховки ForwardDiagonal, и в три раза шире, но без сглаживания.

### WideUpwardDiagonal {#WideUpwardDiagonal}
```
public static final int WideUpwardDiagonal
```


Указывает диагональные линии, наклонённые влево от верхних точек к нижним, имеющие такое же расстояние, как стиль штриховки BackwardDiagonal, и в три раза шире, но без сглаживания.

### LightVertical {#LightVertical}
```
public static final int LightVertical
```


Указывает вертикальные линии, расположенные на 50 процентов ближе друг к другу, чем Vertical.

### LightHorizontal {#LightHorizontal}
```
public static final int LightHorizontal
```


Указывает горизонтальные линии, расположенные на 50 процентов ближе друг к другу, чем Horizontal.

### NarrowVertical {#NarrowVertical}
```
public static final int NarrowVertical
```


Указывает вертикальные линии, расположенные на 75 процентов ближе друг к другу, чем стиль штриховки Vertical (или на 25 процентов ближе, чем LightVertical).

### NarrowHorizontal {#NarrowHorizontal}
```
public static final int NarrowHorizontal
```


Указывает горизонтальные линии, расположенные на 75 процентов ближе друг к другу, чем стиль штриховки Horizontal (или на 25 процентов ближе, чем LightHorizontal).

### DarkVertical {#DarkVertical}
```
public static final int DarkVertical
```


Указывает вертикальные линии, расположенные на 50 процентов ближе друг к другу, чем Vertical, и в два раза шире.

### DarkHorizontal {#DarkHorizontal}
```
public static final int DarkHorizontal
```


Указывает горизонтальные линии, расположенные на 50 процентов ближе друг к другу, чем Horizontal, и в два раза шире, чем Horizontal.

### DashedDownwardDiagonal {#DashedDownwardDiagonal}
```
public static final int DashedDownwardDiagonal
```


Указывает пунктирные диагональные линии, наклонённые вправо от верхних точек к нижним.

### DashedUpwardDiagonal {#DashedUpwardDiagonal}
```
public static final int DashedUpwardDiagonal
```


Указывает пунктирные диагональные линии, наклонённые влево от верхних точек к нижним.

### DashedHorizontal {#DashedHorizontal}
```
public static final int DashedHorizontal
```


Указывает пунктирные горизонтальные линии.

### DashedVertical {#DashedVertical}
```
public static final int DashedVertical
```


Указывает пунктирные вертикальные линии.

### SmallConfetti {#SmallConfetti}
```
public static final int SmallConfetti
```


Указывает штриховку, имеющую вид конфетти.

### LargeConfetti {#LargeConfetti}
```
public static final int LargeConfetti
```


Указывает штриховку, имеющую вид конфетти и состоящую из более крупных элементов, чем SmallConfetti.

### ZigZag {#ZigZag}
```
public static final int ZigZag
```


Указывает горизонтальные линии, состоящие из зигзагов.

### Wave {#Wave}
```
public static final int Wave
```


Указывает горизонтальные линии, состоящие из тильд.

### DiagonalBrick {#DiagonalBrick}
```
public static final int DiagonalBrick
```


Указывает штриховку, имеющую вид слоистых кирпичей, наклонённых влево от верхних точек к нижним точкам.

### HorizontalBrick {#HorizontalBrick}
```
public static final int HorizontalBrick
```


Указывает штриховку, имеющую вид горизонтально расположенных слоистых кирпичей.

### Weave {#Weave}
```
public static final int Weave
```


Указывает штриховку, имеющую вид тканого материала.

### Plaid {#Plaid}
```
public static final int Plaid
```


Указывает штриховку, имеющую вид клетчатого материала.

### Divot {#Divot}
```
public static final int Divot
```


Указывает штриховку, имеющую вид вмятин.

### DottedGrid {#DottedGrid}
```
public static final int DottedGrid
```


Указывает горизонтальные и вертикальные линии, каждая из которых состоит из точек и пересекаются.

### DottedDiamond {#DottedDiamond}
```
public static final int DottedDiamond
```


Указывает прямые и обратные диагональные линии, каждая из которых состоит из точек и пересекаются.

### Shingle {#Shingle}
```
public static final int Shingle
```


Указывает штриховку, имеющую вид диагонально расположенных черепиц, наклонённых вправо от верхних точек к нижним точкам.

### Trellis {#Trellis}
```
public static final int Trellis
```


Указывает штриховку, имеющую вид решётки.

### Sphere {#Sphere}
```
public static final int Sphere
```


Указывает штриховку, имеющую вид соседних друг с другом сфер.

### SmallGrid {#SmallGrid}
```
public static final int SmallGrid
```


Указывает горизонтальные и вертикальные линии, которые пересекаются и расположены на 50 % ближе друг к другу, чем стиль штриховки Cross.

### SmallCheckerBoard {#SmallCheckerBoard}
```
public static final int SmallCheckerBoard
```


Указывает штриховку, имеющую вид шахматной доски.

### LargeCheckerBoard {#LargeCheckerBoard}
```
public static final int LargeCheckerBoard
```


Указывает штриховку, имеющую вид шахматной доски, квадраты которой вдвое больше, чем у SmallCheckerBoard.

### OutlinedDiamond {#OutlinedDiamond}
```
public static final int OutlinedDiamond
```


Указывает прямые и обратные диагональные линии, которые пересекаются, но не сглажены.

### SolidDiamond {#SolidDiamond}
```
public static final int SolidDiamond
```


Указывает штриховку, имеющую вид шахматной доски, расположенной по диагонали.

