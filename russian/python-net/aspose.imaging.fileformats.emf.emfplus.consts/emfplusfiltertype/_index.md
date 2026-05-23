---
title: "EmfPlusFilterType Перечисление"
type: docs
weight: 140
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/
---

Перечисление FilterType определяет типы алгоритмов фильтрации, которые могут использоваться для улучшения качества текста и графики и рендеринга изображений.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusFilterType

## **Members**
| **Имя члена** | **Description** |
| :- | :- |
| FILTER_TYPE_BOX | Указывает алгоритм коробочного фильтра, при котором каждый пиксель назначения вычисляется усреднением прямоугольника исходных пикселей. Этот алгоритм полезен только при уменьшении размера изображения. |
| FILTER_TYPE_GAUSSIAN_QUAD | Указывает, что используется 4‑образцовый гауссов фильтр, создающий эффект размытия изображения. |
| FILTER_TYPE_LINEAR | Указывает, что линейная интерполяция выполняется с использованием взвешенного среднего области 2×2 пикселей, окружающих исходный пиксель. |
| FILTER_TYPE_NONE | Указывает, что фильтрация не выполняется. |
| FILTER_TYPE_POINT | Указывает, что каждый пиксель назначения вычисляется выборкой ближайшего пикселя из исходного изображения. |
| FILTER_TYPE_PYRAMIDAL_QUAD | Указывает, что используется 4‑образцовый тент‑фильтр. |
| FILTER_TYPE_TRIANGLE | Указывает, что каждый пиксель исходного изображения вносит одинаковый вклад в изображение назначения. Это самый медленный из алгоритмов фильтрации. |
