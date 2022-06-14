---
title: FillClosedCurve
second_title: Справочник по Aspose.Imaging for .NET API
description: Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой определяемой массивом структурPointFaspose.imaging/pointf. Этот метод использует натяжение по умолчанию 05 иAlternateрежим заполнения.
type: docs
weight: 340
url: /ru/net/aspose.imaging/graphics/fillclosedcurve/
---
## FillClosedCurve(Brush, PointF[]) {#fillclosedcurve}

Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой, определяемой массивом структур[`PointF`](../../pointf). Этот метод использует натяжение по умолчанию 0,5 иAlternateрежим заполнения.

```csharp
public void FillClosedCurve(Brush brush, PointF[] points)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush)который определяет характеристики заливки. |
| points | PointF[] | Массив структур[`PointF`](../../pointf), определяющих сплайн. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush*равно null. -или- *points*равно null. |

### Смотрите также

* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

---

## FillClosedCurve(Brush, PointF[], FillMode) {#fillclosedcurve_1}

Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой, заданной массивом структур[`PointF`](../../pointf)с использованием указанного режима заполнения . Этот метод использует натяжение по умолчанию 0,5.

```csharp
public void FillClosedCurve(Brush brush, PointF[] points, FillMode fillmode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush)который определяет характеристики заливки. |
| points | PointF[] | Массив структур[`PointF`](../../pointf), определяющих сплайн. |
| fillmode | FillMode | Член перечисления[`FillMode`](../../fillmode), которое определяет способ заполнения кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush*равно null. -или- *points*равно null. |

### Смотрите также

* class [Brush](../../brush)
* struct [PointF](../../pointf)
* enum [FillMode](../../fillmode)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

---

## FillClosedCurve(Brush, PointF[], FillMode, float) {#fillclosedcurve_2}

Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой, заданной массивом структур[`PointF`](../../pointf)с использованием указанного режима заполнения и напряжение.

```csharp
public void FillClosedCurve(Brush brush, PointF[] points, FillMode fillmode, float tension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | Brush | A[`Brush`](../../brush)определяет характеристики заливки. |
| points | PointF[] | Массив структур[`PointF`](../../pointf), определяющих сплайн. |
| fillmode | FillMode | Член перечисления[`FillMode`](../../fillmode), которое определяет способ заполнения кривой. |
| tension | Single | Значение больше или равное 0,0F, определяющее натяжение кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush*равно null. -или- *points*равно null. |

### Смотрите также

* class [Brush](../../brush)
* struct [PointF](../../pointf)
* enum [FillMode](../../fillmode)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

---

## FillClosedCurve(Brush, Point[]) {#fillclosedcurve_3}

Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой, определяемой массивом структур[`Point`](../../point). Этот метод использует натяжение по умолчанию 0,5 иAlternateрежим заполнения.

```csharp
public void FillClosedCurve(Brush brush, Point[] points)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush)который определяет характеристики заливки. |
| points | Point[] | Массив структур[`Point`](../../point), определяющих сплайн. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush*равно null. -или- *points*равно null. |

### Смотрите также

* class [Brush](../../brush)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

---

## FillClosedCurve(Brush, Point[], FillMode) {#fillclosedcurve_4}

Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой, заданной массивом структур[`Point`](../../point)с использованием указанного режима заполнения . Этот метод использует натяжение по умолчанию 0,5.

```csharp
public void FillClosedCurve(Brush brush, Point[] points, FillMode fillmode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush)который определяет характеристики заливки. |
| points | Point[] | Массив структур[`Point`](../../point), определяющих сплайн. |
| fillmode | FillMode | Член перечисления[`FillMode`](../../fillmode), которое определяет способ заполнения кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush*равно null. -или- *points*равно null. |

### Смотрите также

* class [Brush](../../brush)
* struct [Point](../../point)
* enum [FillMode](../../fillmode)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

---

## FillClosedCurve(Brush, Point[], FillMode, float) {#fillclosedcurve_5}

Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой, заданной массивом структур[`Point`](../../point)с использованием указанного режима заполнения и напряжение.

```csharp
public void FillClosedCurve(Brush brush, Point[] points, FillMode fillmode, float tension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush)который определяет характеристики заливки. |
| points | Point[] | Массив структур[`Point`](../../point), определяющих сплайн. |
| fillmode | FillMode | Член перечисления[`FillMode`](../../fillmode), которое определяет способ заполнения кривой. |
| tension | Single | Значение больше или равное 0,0F, определяющее натяжение кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush*равно null. -или- *points*равно null. |

### Смотрите также

* class [Brush](../../brush)
* struct [Point](../../point)
* enum [FillMode](../../fillmode)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
