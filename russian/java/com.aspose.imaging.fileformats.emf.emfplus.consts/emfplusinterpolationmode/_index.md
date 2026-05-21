---
title: "EmfPlusInterpolationMode"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление InterpolationMode определяет способы масштабирования, включая растягивание и сжатие."
type: docs
weight: 29
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusInterpolationMode extends System.Enum
```

Перечисление InterpolationMode определяет способы масштабирования, включая растягивание и сжатие.
## Поля

| Поле | Описание |
| --- | --- |
| [InterpolationModeDefault](#InterpolationModeDefault) | Указывает режим интерполяции по умолчанию, который определяется как InterpolationModeBilinear. |
| [InterpolationModeLowQuality](#InterpolationModeLowQuality) | Указывает режим интерполяции низкого качества, который определяется как InterpolationModeNearestNeighbor. |
| [InterpolationModeHighQuality](#InterpolationModeHighQuality) | Указывает режим интерполяции высокого качества, который определяется как InterpolationModeHighQualityBicubic. |
| [InterpolationModeBilinear](#InterpolationModeBilinear) | Указывает билинейную интерполяцию, которая использует ближайшее 2×2 соседство известных пикселей, окружающих интерполируемый пиксель. |
| [InterpolationModeBicubic](#InterpolationModeBicubic) | Указывает бикубическую интерполяцию, которая использует ближайшее 4x4 соседство известных пикселей вокруг интерполируемого пикселя. |
| [InterpolationModeNearestNeighbor](#InterpolationModeNearestNeighbor) | Указывает интерполяцию ближайшего соседа, которая использует только значение пикселя, ближайшего к интерполируемому пикселю. |
| [InterpolationModeHighQualityBilinear](#InterpolationModeHighQualityBilinear) | Указывает билинейную интерполяцию с предварительной фильтрацией. |
| [InterpolationModeHighQualityBicubic](#InterpolationModeHighQualityBicubic) | Указывает бикубическую интерполяцию с предварительной фильтрацией, которая дает результат наивысшего качества среди этих вариантов. |
### InterpolationModeDefault {#InterpolationModeDefault}
```
public static final byte InterpolationModeDefault
```


Указывает режим интерполяции по умолчанию, который определяется как InterpolationModeBilinear.

### InterpolationModeLowQuality {#InterpolationModeLowQuality}
```
public static final byte InterpolationModeLowQuality
```


Указывает режим интерполяции низкого качества, который определяется как InterpolationModeNearestNeighbor.

### InterpolationModeHighQuality {#InterpolationModeHighQuality}
```
public static final byte InterpolationModeHighQuality
```


Указывает режим интерполяции высокого качества, который определяется как InterpolationModeHighQualityBicubic.

### InterpolationModeBilinear {#InterpolationModeBilinear}
```
public static final byte InterpolationModeBilinear
```


Указывает билинейную интерполяцию, которая использует ближайшее 2x2 соседство известных пикселей вокруг интерполируемого пикселя. Взвешенное среднее этих 4 известных значений пикселей определяет значение, присваиваемое интерполируемому пикселю. Результат выглядит более плавным, чем InterpolationModeNearestNeighbor.

### InterpolationModeBicubic {#InterpolationModeBicubic}
```
public static final byte InterpolationModeBicubic
```


Указывает бикубическую интерполяцию, которая использует ближайшее 4x4 соседство известных пикселей вокруг интерполируемого пикселя. Взвешенное среднее этих 16 известных значений пикселей определяет значение, присваиваемое интерполируемому пикселю. Поскольку известные пиксели находятся на разном расстоянии от интерполируемого пикселя, более близким пикселям присваивается больший вес в расчете. Результат выглядит более плавным, чем InterpolationModeBilinear.

### InterpolationModeNearestNeighbor {#InterpolationModeNearestNeighbor}
```
public static final byte InterpolationModeNearestNeighbor
```


Указывает интерполяцию ближайшего соседа, которая использует только значение пикселя, ближайшего к интерполируемому пикселю. Этот режим просто дублирует или удаляет пиксели, обеспечивая наименее качественный результат среди этих вариантов.

### InterpolationModeHighQualityBilinear {#InterpolationModeHighQualityBilinear}
```
public static final byte InterpolationModeHighQualityBilinear
```


Указывает билинейную интерполяцию с предварительной фильтрацией.

### InterpolationModeHighQualityBicubic {#InterpolationModeHighQualityBicubic}
```
public static final byte InterpolationModeHighQualityBicubic
```


Указывает бикубическую интерполяцию с предварительной фильтрацией, которая дает результат наивысшего качества среди этих вариантов.

