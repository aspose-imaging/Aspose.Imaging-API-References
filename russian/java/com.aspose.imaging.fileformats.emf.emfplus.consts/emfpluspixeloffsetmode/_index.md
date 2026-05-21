---
title: "EmfPlusPixelOffsetMode"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление PixelOffsetMode определяет, как смещаются пиксели, указывая компромисс между скоростью отрисовки и качеством."
type: docs
weight: 44
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPixelOffsetMode extends System.Enum
```

Перечисление PixelOffsetMode определяет, как смещаются пиксели, что задаёт компромисс между скоростью рендеринга и качеством.
## Поля

| Поле | Описание |
| --- | --- |
| [PixelOffsetModeDefault](#PixelOffsetModeDefault) | Пиксели центрированы на целочисленных координатах, обеспечивая большую скорость за счёт качества. |
| [PixelOffsetModeHighSpeed](#PixelOffsetModeHighSpeed) | Пиксели центрированы на целочисленных координатах, как в случае PixelOffsetModeNone. |
| [PixelOffsetModeHighQuality](#PixelOffsetModeHighQuality) | Пиксели центрированы на полуцелочисленных координатах, как в случае PixelOffsetModeHalf. |
| [PixelOffsetModeNone](#PixelOffsetModeNone) | Пиксели центрированы в начале координат, что означает, что пиксель охватывает область от -0.5 до 0.5 по обеим осям x и y, а его центр находится в точке (0,0). |
| [PixelOffsetModeHalf](#PixelOffsetModeHalf) | Пиксели центрированы на полуцелочисленных координатах, что означает, что пиксель охватывает область от 0 до 1 по обеим осям x и y, а его центр находится в точке (0.5,0.5). |
### PixelOffsetModeDefault {#PixelOffsetModeDefault}
```
public static final byte PixelOffsetModeDefault
```


Пиксели центрированы на целочисленных координатах, обеспечивая большую скорость за счёт качества.

### PixelOffsetModeHighSpeed {#PixelOffsetModeHighSpeed}
```
public static final byte PixelOffsetModeHighSpeed
```


Пиксели центрированы на целочисленных координатах, как в случае PixelOffsetModeNone. Указана более высокая скорость за счёт качества.

### PixelOffsetModeHighQuality {#PixelOffsetModeHighQuality}
```
public static final byte PixelOffsetModeHighQuality
```


Пиксели центрированы на полуцелочисленных координатах, как в случае PixelOffsetModeHalf. Указано более высокое качество за счёт скорости.

### PixelOffsetModeNone {#PixelOffsetModeNone}
```
public static final byte PixelOffsetModeNone
```


Пиксели центрированы в начале координат, что означает, что пиксель охватывает область от -0.5 до 0.5 по обеим осям x и y, а его центр находится в точке (0,0).

### PixelOffsetModeHalf {#PixelOffsetModeHalf}
```
public static final byte PixelOffsetModeHalf
```


Пиксели центрированы на полуцелочисленных координатах, что означает, что пиксель охватывает область от 0 до 1 по обеим осям x и y, а его центр находится в точке (0.5,0.5). Смещение пикселей при отрисовке может улучшить качество рендеринга за счёт снижения скорости рендеринга.

