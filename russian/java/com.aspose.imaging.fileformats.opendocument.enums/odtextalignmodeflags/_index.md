---
title: "OdTextAlignModeFlags"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Флаги режима выравнивания текста в открытом документе"
type: docs
weight: 14
url: /ru/java/com.aspose.imaging.fileformats.opendocument.enums/odtextalignmodeflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class OdTextAlignModeFlags extends System.Enum
```

Флаги режима выравнивания текста в открытом документе
## Поля

| Поле | Описание |
| --- | --- |
| [Noupdatecp](#Noupdatecp) | Позиция рисования в контексте устройства воспроизведения НЕ ДОЛЖНА обновляться после каждого вызова вывода текста. |
| [Left](#Left) | Опорная точка ДОЛЖНА находиться на левом крае ограничивающего прямоугольника. |
| [Top](#Top) | Опорная точка ДОЛЖНА находиться на верхнем крае ограничивающего прямоугольника. |
| [Updatecp](#Updatecp) | Позиция рисования в контексте устройства воспроизведения ДОЛЖНА обновляться после каждого вызова вывода текста. |
| [Right](#Right) | Опорная точка ДОЛЖНА находиться на правом крае ограничивающего прямоугольника. |
| [Center](#Center) | Опорная точка ДОЛЖНА быть выровнена по горизонтали с центром ограничивающего прямоугольника. |
| [Justify](#Justify) | Текст должен быть выровнен так, чтобы каждая строка абзаца имела одинаковую длину. |
| [Bottom](#Bottom) | Опорная точка ДОЛЖНА находиться на нижнем крае ограничивающего прямоугольника. |
| [Baseline](#Baseline) | Опорная точка ДОЛЖНА находиться на базовой линии текста. |
| [Rtlreading](#Rtlreading) | Текст ДОЛЖЕН располагаться в порядке чтения справа налево, вместо стандартного порядка слева направо. |
| [Horizontal](#Horizontal) | Represents Horizontal text align sets (Left | Right | Центр) |
| [Vertical](#Vertical) | Represents Vertical text align sets (Top | Bottom | Базовая линия) |
### Noupdatecp {#Noupdatecp}
```
public static final int Noupdatecp
```


Позиция рисования в контексте устройства воспроизведения НЕ ДОЛЖНА обновляться после каждого вызова вывода текста. Опорная точка ДОЛЖНА передаваться функции вывода текста.

### Left {#Left}
```
public static final int Left
```


Опорная точка ДОЛЖНА находиться на левом крае ограничивающего прямоугольника.

### Top {#Top}
```
public static final int Top
```


Опорная точка ДОЛЖНА находиться на верхнем крае ограничивающего прямоугольника.

### Updatecp {#Updatecp}
```
public static final int Updatecp
```


Позиция рисования в контексте устройства воспроизведения ДОЛЖНА обновляться после каждого вызова вывода текста. Она ДОЛЖНА использоваться в качестве опорной точки.

### Right {#Right}
```
public static final int Right
```


Опорная точка ДОЛЖНА находиться на правом крае ограничивающего прямоугольника.

### Center {#Center}
```
public static final int Center
```


Опорная точка ДОЛЖНА быть выровнена по горизонтали с центром ограничивающего прямоугольника.

### Justify {#Justify}
```
public static final int Justify
```


Текст должен быть выровнен так, чтобы каждая строка абзаца имела одинаковую длину.

### Bottom {#Bottom}
```
public static final int Bottom
```


Опорная точка ДОЛЖНА находиться на нижнем крае ограничивающего прямоугольника.

### Baseline {#Baseline}
```
public static final int Baseline
```


Опорная точка ДОЛЖНА находиться на базовой линии текста.

### Rtlreading {#Rtlreading}
```
public static final int Rtlreading
```


Текст ДОЛЖЕН располагаться в порядке чтения справа налево, вместо стандартного порядка слева направо. Это ДОЛЖНО применяться только тогда, когда шрифт, определённый в контексте устройства воспроизведения, является либо еврейским, либо арабским.

### Horizontal {#Horizontal}
```
public static final int Horizontal
```


Представляет наборы горизонтального выравнивания текста (Left | Right | Center)

### Vertical {#Vertical}
```
public static final int Vertical
```


Представляет наборы вертикального выравнивания текста (Top | Bottom | Baseline)

