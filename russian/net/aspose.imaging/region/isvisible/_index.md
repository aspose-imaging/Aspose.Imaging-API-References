---
title: IsVisible
second_title: Справочник по Aspose.Imaging for .NET API
description: Проверяет содержится ли указанная точка в этомRegionaspose.imaging/region.
type: docs
weight: 90
url: /ru/net/aspose.imaging/region/isvisible/
---
## IsVisible(float, float) {#isvisible_11}

Проверяет, содержится ли указанная точка в этом[`Region`](../../region).

```csharp
public bool IsVisible(float x, float y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Single | X-координата точки для проверки. |
| y | Single | Y-координата проверяемой точки. |

### Возвращаемое значение

Истинно, когда указанная точка содержится в этом[`Region`](../../region); в противном случае ложно.

### Смотрите также

* class [Region](../../region)
* пространство имен [Aspose.Imaging](../../region)
* сборка [Aspose.Imaging](../../../)

---

## IsVisible(PointF) {#isvisible_2}

Проверяет, содержится ли указанная структура[`PointF`](../../pointf)в этомОбласть,край.

```csharp
public bool IsVisible(PointF point)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| point | PointF | Тестируемая структура[`PointF`](../../pointf). |

### Возвращаемое значение

true, когда*point*содержится в этом[`Region`](../../region); в противном случае ложно.

### Смотрите также

* struct [PointF](../../pointf)
* class [Region](../../region)
* пространство имен [Aspose.Imaging](../../region)
* сборка [Aspose.Imaging](../../../)

---

## IsVisible(float, float, Graphics) {#isvisible_12}

Проверяет, содержится ли указанная точка в этом[`Region`](../../region)при рисовании с использованием указанного[`Graphics`](../../graphics).

```csharp
public bool IsVisible(float x, float y, Graphics g)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Single | X-координата точки для проверки. |
| y | Single | Y-координата проверяемой точки. |
| g | Graphics | A[`Graphics`](../../graphics)который представляет графический контекст. |

### Возвращаемое значение

Истинно, когда указанная точка содержится в этом[`Region`](../../region); в противном случае ложно.

### Смотрите также

* class [Graphics](../../graphics)
* class [Region](../../region)
* пространство имен [Aspose.Imaging](../../region)
* сборка [Aspose.Imaging](../../../)

---

## IsVisible(PointF, Graphics) {#isvisible_3}

Проверяет, содержится ли указанная структура[`PointF`](../../pointf)в этом[`Region`](../../region)при рисовании с использованием указанного[`Graphics`](../../graphics).

```csharp
public bool IsVisible(PointF point, Graphics g)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| point | PointF | Тестируемая структура[`PointF`](../../pointf). |
| g | Graphics | A[`Graphics`](../../graphics)который представляет графический контекст. |

### Возвращаемое значение

true, когда*point*содержится в этом[`Region`](../../region); в противном случае ложно.

### Смотрите также

* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* class [Region](../../region)
* пространство имен [Aspose.Imaging](../../region)
* сборка [Aspose.Imaging](../../../)

---

## IsVisible(float, float, float, float) {#isvisible_13}

Проверяет, содержится ли какая-либо часть указанного прямоугольника в этом[`Region`](../../region).

```csharp
public bool IsVisible(float x, float y, float width, float height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Single | Координата x левого верхнего угла прямоугольника для проверки. |
| y | Single | Y-координата левого верхнего угла прямоугольника для проверки. |
| width | Single | Ширина тестируемого прямоугольника. |
| height | Single | Высота тестируемого прямоугольника. |

### Возвращаемое значение

true, когда любая часть указанного прямоугольника содержится внутри этого[`Region`](../../region)объект; в противном случае ложно.

### Смотрите также

* class [Region](../../region)
* пространство имен [Aspose.Imaging](../../region)
* сборка [Aspose.Imaging](../../../)

---

## IsVisible(RectangleF) {#isvisible_6}

Проверяет, содержится ли какая-либо часть указанной структуры[`RectangleF`](../../rectanglef)внутри этойРегион.

```csharp
public bool IsVisible(RectangleF rect)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | RectangleF | Тестируемая структура[`RectangleF`](../../rectanglef). |

### Возвращаемое значение

true, если какая-либо часть*rect*содержится внутри этогоРегион; в противном случае ложно.

### Смотрите также

* struct [RectangleF](../../rectanglef)
* class [Region](../../region)
* пространство имен [Aspose.Imaging](../../region)
* сборка [Aspose.Imaging](../../../)

---

## IsVisible(float, float, float, float, Graphics) {#isvisible_14}

Проверяет, содержится ли какая-либо часть указанного прямоугольника в этом[`Region`](../../region)при рисовании с использованием указанного[`Graphics`](../../graphics).

```csharp
public bool IsVisible(float x, float y, float width, float height, Graphics g)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Single | Координата x левого верхнего угла прямоугольника для проверки. |
| y | Single | Y-координата левого верхнего угла прямоугольника для проверки. |
| width | Single | Ширина тестируемого прямоугольника. |
| height | Single | Высота тестируемого прямоугольника. |
| g | Graphics | A[`Graphics`](../../graphics)который представляет графический контекст. |

### Возвращаемое значение

true, когда любая часть указанного прямоугольника содержится внутри этого[`Region`](../../region); в противном случае ложно.

### Смотрите также

* class [Graphics](../../graphics)
* class [Region](../../region)
* пространство имен [Aspose.Imaging](../../region)
* сборка [Aspose.Imaging](../../../)

---

## IsVisible(RectangleF, Graphics) {#isvisible_7}

Проверяет, содержится ли какая-либо часть указанной структуры[`RectangleF`](../../rectanglef)внутри этой[`Region`](../../region)при рисовании с использованием указанного[`Graphics`](../../graphics).

```csharp
public bool IsVisible(RectangleF rect, Graphics g)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | RectangleF | Тестируемая структура[`RectangleF`](../../rectanglef). |
| g | Graphics | A[`Graphics`](../../graphics)который представляет графический контекст. |

### Возвращаемое значение

true, когда*rect*содержится в этом[`Region`](../../region); в противном случае ложно.

### Смотрите также

* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* class [Region](../../region)
* пространство имен [Aspose.Imaging](../../region)
* сборка [Aspose.Imaging](../../../)

---

## IsVisible(int, int, Graphics) {#isvisible_8}

Проверяет, содержится ли указанная точка в этом объекте[`Region`](../../region)при рисовании с использованием указанного[`Graphics`](../../graphics)объект.

```csharp
public bool IsVisible(int x, int y, Graphics g)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Int32 | X-координата точки для проверки. |
| y | Int32 | Y-координата проверяемой точки. |
| g | Graphics | A[`Graphics`](../../graphics)который представляет графический контекст. |

### Возвращаемое значение

true, когда указанная точка содержится в этом[`Region`](../../region); в противном случае ложно.

### Смотрите также

* class [Graphics](../../graphics)
* class [Region](../../region)
* пространство имен [Aspose.Imaging](../../region)
* сборка [Aspose.Imaging](../../../)

---

## IsVisible(Point) {#isvisible}

Проверяет, содержится ли указанная структура[`Point`](../../point)в этомОбласть,край.

```csharp
public bool IsVisible(Point point)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| point | Point | Тестируемая структура[`Point`](../../point). |

### Возвращаемое значение

true, когда*point*содержится в этом[`Region`](../../region); в противном случае ложно.

### Смотрите также

* struct [Point](../../point)
* class [Region](../../region)
* пространство имен [Aspose.Imaging](../../region)
* сборка [Aspose.Imaging](../../../)

---

## IsVisible(Point, Graphics) {#isvisible_1}

Проверяет, содержится ли указанная структура[`Point`](../../point)в этом[`Region`](../../region)при рисовании с использованием указанного[`Graphics`](../../graphics).

```csharp
public bool IsVisible(Point point, Graphics g)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| point | Point | Тестируемая структура[`Point`](../../point). |
| g | Graphics | A[`Graphics`](../../graphics)который представляет графический контекст. |

### Возвращаемое значение

true, когда*point*содержится в этом[`Region`](../../region); в противном случае ложно.

### Смотрите также

* struct [Point](../../point)
* class [Graphics](../../graphics)
* class [Region](../../region)
* пространство имен [Aspose.Imaging](../../region)
* сборка [Aspose.Imaging](../../../)

---

## IsVisible(int, int, int, int) {#isvisible_9}

Проверяет, содержится ли какая-либо часть указанного прямоугольника в этом[`Region`](../../region).

```csharp
public bool IsVisible(int x, int y, int width, int height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Int32 | Координата x левого верхнего угла прямоугольника для проверки. |
| y | Int32 | Y-координата левого верхнего угла прямоугольника для проверки. |
| width | Int32 | Ширина тестируемого прямоугольника. |
| height | Int32 | Высота тестируемого прямоугольника. |

### Возвращаемое значение

true, когда любая часть указанного прямоугольника содержится внутри этого[`Region`](../../region); в противном случае ложно.

### Смотрите также

* class [Region](../../region)
* пространство имен [Aspose.Imaging](../../region)
* сборка [Aspose.Imaging](../../../)

---

## IsVisible(Rectangle) {#isvisible_4}

Проверяет, содержится ли какая-либо часть указанной структуры[`Rectangle`](../../rectangle)внутри этойРегион.

```csharp
public bool IsVisible(Rectangle rect)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Тестируемая структура[`Rectangle`](../../rectangle). |

### Возвращаемое значение

Этот метод возвращает true, когда какая-либо часть*rect*содержится внутри этого[`Region`](../../region); в противном случае ложно.

### Смотрите также

* struct [Rectangle](../../rectangle)
* class [Region](../../region)
* пространство имен [Aspose.Imaging](../../region)
* сборка [Aspose.Imaging](../../../)

---

## IsVisible(int, int, int, int, Graphics) {#isvisible_10}

Проверяет, содержится ли какая-либо часть указанного прямоугольника в этом[`Region`](../../region)при рисовании с использованием указанного[`Graphics`](../../graphics).

```csharp
public bool IsVisible(int x, int y, int width, int height, Graphics g)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Int32 | Координата x левого верхнего угла прямоугольника для проверки. |
| y | Int32 | Y-координата левого верхнего угла прямоугольника для проверки. |
| width | Int32 | Ширина тестируемого прямоугольника. |
| height | Int32 | Высота тестируемого прямоугольника. |
| g | Graphics | A[`Graphics`](../../graphics)который представляет графический контекст. |

### Возвращаемое значение

true, когда любая часть указанного прямоугольника содержится внутри этого[`Region`](../../region); в противном случае ложно.

### Смотрите также

* class [Graphics](../../graphics)
* class [Region](../../region)
* пространство имен [Aspose.Imaging](../../region)
* сборка [Aspose.Imaging](../../../)

---

## IsVisible(Rectangle, Graphics) {#isvisible_5}

Проверяет, содержится ли какая-либо часть указанной структуры[`Rectangle`](../../rectangle)внутри этой[`Region`](../../region)при рисовании с использованием указанного[`Graphics`](../../graphics).

```csharp
public bool IsVisible(Rectangle rect, Graphics g)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Тестируемая структура[`Rectangle`](../../rectangle). |
| g | Graphics | A[`Graphics`](../../graphics)который представляет графический контекст. |

### Возвращаемое значение

true, если какая-либо часть*rect*содержится внутри этогоИзображения; в противном случае ложно.

### Смотрите также

* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* class [Region](../../region)
* пространство имен [Aspose.Imaging](../../region)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
