---
title: "Класс IPartialPixelLoader"
type: docs
weight: 5520
url: /ru/python-net/aspose.imaging/ipartialpixelloader/
---

**Summary:** Conforms to the pixels loaded partially.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IPartialPixelLoader

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [process(pixels_rectangle, pixels, start, end)](#process_pixels_rectangle_pixels_start_end_1) | Обрабатывает загруженные пиксели. |


### Method: process(pixels_rectangle, pixels, start, end) {#process_pixels_rectangle_pixels_start_end_1}


```
 process(pixels_rectangle, pixels, start, end) 
```

Обрабатывает загруженные пиксели.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixels_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник пикселей. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Пиксели. |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | Точка начала пикселей. Если она не равна (left,top), это означает, что у нас не полный прямоугольник. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | Точка окончания пикселей. Если она не равна (right,bottom), это означает, что у нас не полный прямоугольник. |

