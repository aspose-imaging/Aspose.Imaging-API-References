---
title: "StretchMode"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление указывает режим растягивания битмапа, который определяет, как система комбинирует строки или столбцы битмапа с существующими пикселями."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.wmf.consts/stretchmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StretchMode extends System.Enum
```

Перечисление [StretchMode](../../com.aspose.imaging.fileformats.wmf.consts/stretchmode) указывает режим растягивания битмапа, который определяет, как система комбинирует строки или столбцы битмапа с существующими пикселями.
## Поля

| Поле | Описание |
| --- | --- |
| [BlackOnWhite](#BlackOnWhite) | Выполняет логическую операцию И, используя цветовые значения для удалённых и существующих пикселей. |
| [WhiteOnBlack](#WhiteOnBlack) | Выполняет логическую операцию ИЛИ, используя цветовые значения для удалённых и существующих пикселей. |
| [ColorOnColor](#ColorOnColor) | Удаляет пиксели. |
| [HalfTone](#HalfTone) | Отображает пиксели из исходного прямоугольника в блоки пикселей в целевом прямоугольнике. |
### BlackOnWhite {#BlackOnWhite}
```
public static final int BlackOnWhite
```


Выполняет логическую операцию И, используя цветовые значения для удалённых и существующих пикселей. Если битмап является монохромным, этот режим сохраняет чёрные пиксели за счёт белых пикселей.

### WhiteOnBlack {#WhiteOnBlack}
```
public static final int WhiteOnBlack
```


Выполняет логическую операцию ИЛИ, используя цветовые значения для удалённых и существующих пикселей. Если битмап является монохромным, этот режим сохраняет белые пиксели за счёт чёрных пикселей.

### ColorOnColor {#ColorOnColor}
```
public static final int ColorOnColor
```


Удаляет пиксели. Этот режим удаляет все устранённые линии пикселей, не пытаясь сохранять их информацию.

### HalfTone {#HalfTone}
```
public static final int HalfTone
```


Отображает пиксели из исходного прямоугольника в блоки пикселей в целевом прямоугольнике. Средний цвет блока целевых пикселей приближён к цвету исходных пикселей.

