---
title: Warp
second_title: Справочник по Aspose.Imaging for .NET API
description: Применяет преобразование деформации заданное прямоугольником и параллелограммом к этомуGraphicsPathaspose.imaging/graphicspath .
type: docs
weight: 180
url: /ru/aspose.imaging/graphicspath/warp/
---
## Warp(PointF[], RectangleF) {#warp}

Применяет преобразование деформации, заданное прямоугольником и параллелограммом, к этому[`GraphicsPath`](../../graphicspath) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| destPoints | PointF[] | Массив[`PointF`](../../pointf) структуры, которые определяют параллелограмм, к которому прямоугольник, заданный*srcRect* трансформируется. Массив может содержать три или четыре элемента. Если массив содержит три элемента, нижний правый угол параллелограмма подразумевается первыми тремя точками. |
| srcRect | RectangleF | А[`RectangleF`](../../rectanglef) который представляет прямоугольник, который преобразуется в параллелограмм, определяемый формулой*destPoints*. |

### Смотрите также

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [GraphicsPath](../../graphicspath)
* пространство имен [Aspose.Imaging](../../graphicspath)
* сборка [Aspose.Imaging](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

Применяет преобразование деформации, заданное прямоугольником и параллелограммом, к этому[`GraphicsPath`](../../graphicspath) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| destPoints | PointF[] | Массив[`PointF`](../../pointf) структуры, которые определяют параллелограмм, к которому прямоугольник, заданный*srcRect* трансформируется. Массив может содержать три или четыре элемента. Если массив содержит три элемента, нижний правый угол параллелограмма подразумевается первыми тремя точками. |
| srcRect | RectangleF | А[`RectangleF`](../../rectanglef) который представляет прямоугольник, который преобразуется в параллелограмм, определяемый формулой*destPoints*. |
| matrix | Matrix | А[`Matrix`](../../matrix) который определяет геометрическое преобразование, применяемое к пути. |

### Смотрите также

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [Matrix](../../matrix)
* class [GraphicsPath](../../graphicspath)
* пространство имен [Aspose.Imaging](../../graphicspath)
* сборка [Aspose.Imaging](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

Применяет преобразование деформации, заданное прямоугольником и параллелограммом, к этому[`GraphicsPath`](../../graphicspath) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| destPoints | PointF[] | Массив[`PointF`](../../pointf) структуры, определяющие параллелограмм, к которому прямоугольник, заданный*srcRect* трансформируется. Массив может содержать три или четыре элемента. Если массив содержит три элемента, нижний правый угол параллелограмма подразумевается первыми тремя точками. |
| srcRect | RectangleF | А[`RectangleF`](../../rectanglef) который представляет прямоугольник, который преобразуется в параллелограмм, определяемый формулой*destPoints*. |
| matrix | Matrix | А[`Matrix`](../../matrix) который определяет геометрическое преобразование, применяемое к пути. |
| warpMode | WarpMode | А[`WarpMode`](../../warpmode) перечисление, указывающее, использует ли эта операция деформации перспективный или билинейный режим. |

### Смотрите также

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [Matrix](../../matrix)
* enum [WarpMode](../../warpmode)
* class [GraphicsPath](../../graphicspath)
* пространство имен [Aspose.Imaging](../../graphicspath)
* сборка [Aspose.Imaging](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

Применяет преобразование деформации, заданное прямоугольником и параллелограммом, к этому[`GraphicsPath`](../../graphicspath) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| destPoints | PointF[] | Массив[`PointF`](../../pointf) структуры, которые определяют параллелограмм, к которому прямоугольник, заданный*srcRect* трансформируется. Массив может содержать три или четыре элемента. Если массив содержит три элемента, нижний правый угол параллелограмма подразумевается первыми тремя точками. |
| srcRect | RectangleF | А[`RectangleF`](../../rectanglef) который представляет прямоугольник, который преобразуется в параллелограмм, определяемый формулой*destPoints*. |
| matrix | Matrix | А[`Matrix`](../../matrix) который определяет геометрическое преобразование, применяемое к пути. |
| warpMode | WarpMode | А[`WarpMode`](../../warpmode) перечисление, указывающее, использует ли эта операция деформации перспективный или билинейный режим. |
| flatness | Single | Значение от 0 до 1, указывающее, насколько плоским будет результирующий путь. Для получения дополнительной информации см.[`Flatten`](../flatten) методы. |

### Смотрите также

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [Matrix](../../matrix)
* enum [WarpMode](../../warpmode)
* class [GraphicsPath](../../graphicspath)
* пространство имен [Aspose.Imaging](../../graphicspath)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
