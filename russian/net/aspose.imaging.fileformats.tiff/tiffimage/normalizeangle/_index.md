---
title: NormalizeAngle
second_title: Справочник по Aspose.Imaging for .NET API
description: Нормализует угол. Этот метод применим к отсканированным текстовым документам чтобы избавиться от перекоса сканирования. Этот метод используетGetSkewAngleaspose.imaging/rasterimage/getskewangleиRotateaspose.imaging.fileformats.tiff/tiffimage/rotateметоды.
type: docs
weight: 300
url: /ru/net/aspose.imaging.fileformats.tiff/tiffimage/normalizeangle/
---
## TiffImage.NormalizeAngle method

Нормализует угол. Этот метод применим к отсканированным текстовым документам, чтобы избавиться от перекоса сканирования. Этот метод использует[`GetSkewAngle`](../../../aspose.imaging/rasterimage/getskewangle)и[`Rotate`](../rotate)методы.

```csharp
public override void NormalizeAngle(bool resizeProportionally, Color backgroundColor)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| resizeProportionally | Boolean | если установлено` true` у вас будет ваше изображение размер изменяется в соответствии с проекциями повернутого прямоугольника (угловые точки), в другом случае размеры остаются нетронутыми, и поворачивается только внутреннее содержимое изображения. |
| backgroundColor | Color | Цвет фона. |

### Смотрите также

* struct [Color](../../../aspose.imaging/color)
* class [TiffImage](../../tiffimage)
* пространство имен [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->