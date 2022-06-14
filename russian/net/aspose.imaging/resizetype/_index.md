---
title: ResizeType
second_title: Справочник по Aspose.Imaging for .NET API
description: Указывает тип изменения размера.
type: docs
weight: 10870
url: /ru/net/aspose.imaging/resizetype/
---
## ResizeType enumeration

Указывает тип изменения размера.

```csharp
public enum ResizeType
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| None | `0` | Пиксели не сохраняются при изменении размера. |
| LeftTopToLeftTop | `1` | Левая верхняя точка нового изображения совпадет с левой верхней точкой исходного изображения. Обрезка произойдет, если потребуется. |
| RightTopToRightTop | `2` | Правая верхняя точка нового изображения совпадет с правой верхней точкой исходного изображения. Обрезка произойдет, если потребуется. |
| RightBottomToRightBottom | `3` | Правая нижняя точка нового изображения совпадет с правой нижней точкой исходного изображения. Обрезка произойдет, если потребуется. |
| LeftBottomToLeftBottom | `4` | Левая нижняя точка нового изображения совпадет с левой нижней точкой исходного изображения. Обрезка произойдет, если потребуется. |
| CenterToCenter | `5` | Центр нового изображения совпадет с центром исходного изображения. Обрезка произойдет, если потребуется. |
| LanczosResample | `6` | Повторная выборка с использованием алгоритма Ланцоша с a=3. |
| NearestNeighbourResample | `7` | Повторная выборка с использованием алгоритма ближайшего соседа. |
| AdaptiveResample | `8` | Повторная выборка с использованием адаптивного алгоритма, основанного на взвешенной и смешанной рациональной функции и алгоритмах интерполяции lanczos3. |
| BilinearResample | `9` | Передискретизация с использованием билинейной интерполяции. Предварительная фильтрация изображения разрешена для удаления шума перед повторной выборкой, когда это необходимо |
| HighQualityResample | `10` | Высококачественный ресемпл |
| CatmullRom | `11` | Метод кубической интерполяции Катмулла-Рома. |
| CubicConvolution | `12` | Метод интерполяции Cubic Convolution |
| CubicBSpline | `13` | Метод кубической интерполяции CubicBSpline |
| Mitchell | `14` | Метод кубической интерполяции Митчелла |
| SinC | `15` | Метод кубической интерполяции Sinc (Lanczos3) |
| Bell | `16` | Метод интерполяции Белла |

### Примеры

Изменение размера изображения с использованием определенного типа изменения размера.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
     // Масштабирование в 2 раза с использованием передискретизации ближайших соседей.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Масштабирование в 2 раза с использованием передискретизации ближайших соседей.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "downsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
     // Увеличение в 2 раза с использованием билинейной передискретизации.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
     // Уменьшить масштаб в 2 раза, используя билинейную передискретизацию.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "downsample.bilinear.gif");
}
```

В этом примере загружается изображение и изменяется его размер с использованием различных методов изменения размера.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
     // Масштабирование в 2 раза с использованием передискретизации ближайших соседей.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Масштабирование в 2 раза с использованием передискретизации ближайших соседей.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "downsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
     // Увеличение в 2 раза с использованием билинейной передискретизации.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
     // Уменьшить масштаб в 2 раза, используя билинейную передискретизацию.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "downsample.bilinear.gif");
}
```

### Смотрите также

* пространство имен [Aspose.Imaging](../../aspose.imaging)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
