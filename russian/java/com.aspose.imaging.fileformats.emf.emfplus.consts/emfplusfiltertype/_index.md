---
title: "EmfPlusFilterType"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление FilterType определяет типы алгоритмов фильтрации, которые могут использоваться для улучшения качества текста и графики и рендеринга изображений."
type: docs
weight: 22
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusFilterType extends System.Enum
```

Перечисление FilterType определяет типы алгоритмов фильтрации, которые могут использоваться для улучшения качества текста и графики и рендеринга изображений.
## Поля

| Поле | Описание |
| --- | --- |
| [FilterTypeNone](#FilterTypeNone) | Указывает, что фильтрация не выполняется. |
| [FilterTypePoint](#FilterTypePoint) | Указывает, что каждый пиксель назначения вычисляется путем выборки ближайшего пикселя из исходного изображения. |
| [FilterTypeLinear](#FilterTypeLinear) | Указывает, что линейная интерполяция выполняется с использованием взвешенного среднего области 2×2 пикселей, окружающих исходный пиксель. |
| [FilterTypeTriangle](#FilterTypeTriangle) | Указывает, что каждый пиксель исходного изображения вносит одинаковый вклад в изображение назначения. |
| [FilterTypeBox](#FilterTypeBox) | Указывает алгоритм коробочного фильтра, при котором каждый пиксель назначения вычисляется путем усреднения прямоугольника исходных пикселей. |
| [FilterTypePyramidalQuad](#FilterTypePyramidalQuad) | Указывает, что используется тент‑фильтр с 4‑образцами. |
| [FilterTypeGaussianQuad](#FilterTypeGaussianQuad) | Указывает, что используется гауссов фильтр с 4‑образцами, который создает эффект размытия изображения. |
### FilterTypeNone {#FilterTypeNone}
```
public static final byte FilterTypeNone
```


Указывает, что фильтрация не выполняется.

### FilterTypePoint {#FilterTypePoint}
```
public static final byte FilterTypePoint
```


Указывает, что каждый пиксель назначения вычисляется путем выборки ближайшего пикселя из исходного изображения.

### FilterTypeLinear {#FilterTypeLinear}
```
public static final byte FilterTypeLinear
```


Указывает, что линейная интерполяция выполняется с использованием взвешенного среднего области 2×2 пикселей, окружающих исходный пиксель.

### FilterTypeTriangle {#FilterTypeTriangle}
```
public static final byte FilterTypeTriangle
```


Указывает, что каждый пиксель исходного изображения вносит одинаковый вклад в изображение назначения. Это самый медленный из алгоритмов фильтрации.

### FilterTypeBox {#FilterTypeBox}
```
public static final byte FilterTypeBox
```


Указывает алгоритм фильтрации коробкой, при котором каждый пиксель назначения вычисляется путем усреднения прямоугольника исходных пикселей. Этот алгоритм полезен только при уменьшении размера изображения.

### FilterTypePyramidalQuad {#FilterTypePyramidalQuad}
```
public static final byte FilterTypePyramidalQuad
```


Указывает, что используется тент‑фильтр с 4‑образцами.

### FilterTypeGaussianQuad {#FilterTypeGaussianQuad}
```
public static final byte FilterTypeGaussianQuad
```


Указывает, что используется гауссов фильтр с 4‑образцами, который создает эффект размытия изображения.

