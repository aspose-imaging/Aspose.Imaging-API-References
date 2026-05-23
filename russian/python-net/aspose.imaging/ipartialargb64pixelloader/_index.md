---
title: "Класс IPartialArgb64PixelLoader"
type: docs
weight: 5510
url: /ru/python-net/aspose.imaging/ipartialargb64pixelloader/
---

**Summary:** The 64-bit ARGB pixels loader.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IPartialArgb64PixelLoader

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [process64(pixels_rectangle, pixels, start, end)](#process64_pixels_rectangle_pixels_start_end_1) | Обрабатывает загруженные пиксели. |


### Method: process64(pixels_rectangle, pixels, start, end) {#process64_pixels_rectangle_pixels_start_end_1}


```
 process64(pixels_rectangle, pixels, start, end) 
```

Обрабатывает загруженные пиксели.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixels_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник пикселей. |
| пиксели | int[] | 64-битные пиксели ARGB. |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | Точка начала пикселей. Если она не равна (left,top), это означает, что у нас не полный прямоугольник. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | Точка окончания пикселей. Если она не равна (right,bottom), это означает, что у нас не полный прямоугольник. |

