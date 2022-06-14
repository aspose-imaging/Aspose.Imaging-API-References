---
title: Warp
second_title: Справочник по Aspose.Imaging for .NET API
description: Применяет преобразование деформации определяемое прямоугольником и параллелограммом к этомуGraphicsPathaspose.imaging/graphicspath.
type: docs
weight: 180
url: /ru/net/aspose.imaging/graphicspath/warp/
---
## Warp(PointF[], RectangleF) {#warp}

Применяет преобразование деформации, определяемое прямоугольником и параллелограммом, к этому[`GraphicsPath`](../../graphicspath).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| destPoints | PointF[] | Массив структур[`PointF`](../../pointf), определяющих параллелограмм, к которому прямоугольник, заданный*srcRect*, трансформируется. Массив может содержать три или четыре элемента. Если массив содержит три элемента, нижний правый угол параллелограмма подразумевается первыми тремя точками. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef)который представляет прямоугольник, преобразованный в параллелограмм, определенный*destPoints*. |

### Смотрите также

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [GraphicsPath](../../graphicspath)
* пространство имен [Aspose.Imaging](../../graphicspath)
* сборка [Aspose.Imaging](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

Применяет преобразование деформации, определяемое прямоугольником и параллелограммом, к этому[`GraphicsPath`](../../graphicspath).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| destPoints | PointF[] | Массив структур[`PointF`](../../pointf), определяющих параллелограмм, к которому прямоугольник, заданный*srcRect*, трансформируется. Массив может содержать три или четыре элемента. Если массив содержит три элемента, нижний правый угол параллелограмма подразумевается первыми тремя точками. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef)который представляет прямоугольник, преобразованный в параллелограмм, определенный*destPoints*. |
| matrix | Matrix | A[`Matrix`](../../matrix)который определяет геометрическое преобразование, применяемое к пути. |

### Смотрите также

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [Matrix](../../matrix)
* class [GraphicsPath](../../graphicspath)
* пространство имен [Aspose.Imaging](../../graphicspath)
* сборка [Aspose.Imaging](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

Применяет преобразование деформации, определяемое прямоугольником и параллелограммом, к этому[`GraphicsPath`](../../graphicspath).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| destPoints | PointF[] | Массив структур[`PointF`](../../pointf), определяющий параллелограмм, к которому прямоугольник, заданный*srcRect*, трансформируется. Массив может содержать три или четыре элемента. Если массив содержит три элемента, нижний правый угол параллелограмма подразумевается первыми тремя точками. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef)который представляет прямоугольник, преобразованный в параллелограмм, определенный*destPoints*. |
| matrix | Matrix | A[`Matrix`](../../matrix)который определяет геометрическое преобразование, применяемое к пути. |
| warpMode | WarpMode | A[`WarpMode`](../../warpmode)перечисление, указывающее, использует ли эта операция деформации перспективный или билинейный режим. |

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

Применяет преобразование деформации, определяемое прямоугольником и параллелограммом, к этому[`GraphicsPath`](../../graphicspath).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| destPoints | PointF[] | Массив структур[`PointF`](../../pointf), определяющих параллелограмм, к которому прямоугольник, заданный*srcRect*, трансформируется. Массив может содержать три или четыре элемента. Если массив содержит три элемента, нижний правый угол параллелограмма подразумевается первыми тремя точками. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef)который представляет прямоугольник, преобразованный в параллелограмм, определенный*destPoints*. |
| matrix | Matrix | A[`Matrix`](../../matrix)который определяет геометрическое преобразование, применяемое к пути. |
| warpMode | WarpMode | A[`WarpMode`](../../warpmode)перечисление, указывающее, использует ли эта операция деформации перспективный или билинейный режим. |
| flatness | Single | Значение от 0 до 1, указывающее, насколько плоским является результирующий путь. Дополнительные сведения см. в методах[`Flatten`](../flatten). |

### Смотрите также

* struct [PointF](../../pointf)
* struct [RectangleF](../../rectanglef)
* class [Matrix](../../matrix)
* enum [WarpMode](../../warpmode)
* class [GraphicsPath](../../graphicspath)
* пространство имен [Aspose.Imaging](../../graphicspath)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
