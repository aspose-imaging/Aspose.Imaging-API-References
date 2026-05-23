---
title: "Перечисление EmfPlusPixelOffsetMode"
type: docs
weight: 350
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/
---

Перечисление PixelOffsetMode определяет способ смещения пикселей, что задаёт компромисс между скоростью рендеринга и качеством.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusPixelOffsetMode

## **Members**
| **Имя члена** | **Description** |
| :- | :- |
| PIXEL_OFFSET_MODE_DEFAULT | Пиксели центрированы на целочисленных координатах, предпочтение отдается скорости над качеством. |
| PIXEL_OFFSET_MODE_HALF | Пиксели центрированы на полуцелочисленных координатах, что означает, что пиксель покрывает область от 0 до 1 по обеим осям x и y, а его центр находится в точке (0.5,0.5). Смещение пикселей во время рендеринга позволяет улучшить качество изображения за счёт снижения скорости рендеринга. |
| PIXEL_OFFSET_MODE_HIGH_QUALITY | Пиксели центрированы на полуцелочисленных координатах, как и в случае PixelOffsetModeHalf. Указано более высокое качество за счёт снижения скорости. |
| PIXEL_OFFSET_MODE_HIGH_SPEED | Пиксели центрированы на целочисленных координатах, как и в случае PixelOffsetModeNone. Указана более высокая скорость за счёт снижения качества. |
| PIXEL_OFFSET_MODE_NONE | Пиксели центрированы в начале координат, что означает, что пиксель покрывает область от -0.5 до 0.5 по обеим осям x и y, а его центр находится в точке (0,0). |
