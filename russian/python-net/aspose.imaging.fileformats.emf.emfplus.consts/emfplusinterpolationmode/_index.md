---
title: "EmfPlusInterpolationMode Enumeration"
type: docs
weight: 200
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---

Перечисление InterpolationMode определяет способы масштабирования, включая растягивание и сжатие.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusInterpolationMode

## **Members**
| **Имя члена** | **Description** |
| :- | :- |
| INTERPOLATION_MODE_BICUBIC | Указывает на бикубическую интерполяцию, которая использует ближайшее 4×4 соседство известных пикселей вокруг интерполируемого пикселя. Взвешенное среднее этих 16 известных значений пикселей определяет значение, присваиваемое интерполируемому пикселю. Поскольку известные пиксели находятся на разном расстоянии от интерполируемого пикселя, более близкие пиксели получают больший вес в расчёте. Результат выглядит более плавным, чем InterpolationModeBilinear. |
| INTERPOLATION_MODE_BILINEAR | Указывает на билинейную интерполяцию, которая использует ближайшее 2×2 соседство известных пикселей вокруг интерполируемого пикселя. Взвешенное среднее этих 4 известных значений пикселей определяет значение, присваиваемое интерполируемому пикселю. Результат выглядит более плавным, чем InterpolationModeNearestNeighbor. |
| INTERPOLATION_MODE_DEFAULT | Указывает режим интерполяции по умолчанию, который определён как InterpolationModeBilinear. |
| INTERPOLATION_MODE_HIGH_QUALITY | Указывает режим интерполяции высокого качества, который определяется как InterpolationModeHighQualityBicubic. |
| INTERPOLATION_MODE_HIGH_QUALITY_BICUBIC | Указывает бикубическую интерполяцию с предварительной фильтрацией, которая дает результат наивысшего качества среди этих вариантов. |
| INTERPOLATION_MODE_HIGH_QUALITY_BILINEAR | Указывает билинейную интерполяцию с предварительной фильтрацией. |
| INTERPOLATION_MODE_LOW_QUALITY | Указывает режим интерполяции низкого качества, который определяется как InterpolationModeNearestNeighbor. |
| INTERPOLATION_MODE_NEAREST_NEIGHBOR | Указывает интерполяцию ближайшего соседа, которая использует только значение пикселя, ближайшего к интерполируемому пикселю. Этот режим просто дублирует или удаляет пиксели, обеспечивая результат наименьшего качества среди этих вариантов. |
