---
title: "ResizeType"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Указывает тип изменения размера."
type: docs
weight: 97
url: /ru/java/com.aspose.imaging/resizetype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResizeType extends System.Enum
```

Указывает тип изменения размера.
## Поля

| Поле | Описание |
| --- | --- |
| [None](#None) | Пиксели не сохраняются во время операции изменения размера. |
| [LeftTopToLeftTop](#LeftTopToLeftTop) | Левая верхняя точка нового изображения будет совпадать с левой верхней точкой оригинального изображения. |
| [RightTopToRightTop](#RightTopToRightTop) | Правая верхняя точка нового изображения будет совпадать с правой верхней точкой оригинального изображения. |
| [RightBottomToRightBottom](#RightBottomToRightBottom) | Правая нижняя точка нового изображения будет совпадать с правой нижней точкой оригинального изображения. |
| [LeftBottomToLeftBottom](#LeftBottomToLeftBottom) | Левая нижняя точка нового изображения будет совпадать с левой нижней точкой оригинального изображения. |
| [CenterToCenter](#CenterToCenter) | Центр нового изображения будет совпадать с центром оригинального изображения. |
| [LanczosResample](#LanczosResample) | Пересэмплирование с использованием алгоритма Ланцоша с a=3. |
| [NearestNeighbourResample](#NearestNeighbourResample) | Пересэмплирование с использованием алгоритма ближайшего соседа. |
| [AdaptiveResample](#AdaptiveResample) | Пересэмплирование с использованием адаптивного алгоритма, основанного на взвешенной и смешанной рациональной функции и алгоритмах интерполяции lanczos3. |
| [BilinearResample](#BilinearResample) | Пересэмплирование с использованием билинейной интерполяции. |
| [HighQualityResample](#HighQualityResample) | Высококачественное пересэмплирование |
| [CatmullRom](#CatmullRom) | Метод кубической интерполяции Catmull-Rom. |
| [CubicConvolution](#CubicConvolution) | Метод кубической конволюционной интерполяции |
| [CubicBSpline](#CubicBSpline) | Метод кубической интерполяции CubicBSpline |
| [Mitchell](#Mitchell) | Метод кубической интерполяции Mitchell |
| [SinC](#SinC) | Метод кубической интерполяции Sinc (Lanczos3) |
| [Bell](#Bell) | Метод интерполяции Bell |

## Example: This example loads an image and resizes it using various resizing methods.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Увеличить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Уменьшить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Увеличить в 2 раза с использованием билинейного ресэмплинга.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Уменьшить в 2 раза с использованием билинейного ресэмплинга.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```


## Example: Resize image using specific Resize Type.

``` java
try (Image image = Image.load("Photo.jpg"))
{
    image.resize(640, 480, ResizeType.CatmullRom);
    image.save("ResizedPhoto.jpg");

    image.resize(1024, 768, ResizeType.CubicConvolution);
    image.save("ResizedPhoto2.jpg");

    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    resizeSettings.setMode(ResizeType.CubicBSpline);
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);

    image.resize(800, 800, resizeSettings);
    image.save("ResizedPhoto3.jpg");
}
```

### None {#None}
```
public static final int None
```


Пиксели не сохраняются во время операции изменения размера.

### LeftTopToLeftTop {#LeftTopToLeftTop}
```
public static final int LeftTopToLeftTop
```


Левая верхняя точка нового изображения будет совпадать с левой верхней точкой оригинального изображения. Обрезка будет выполнена при необходимости.

### RightTopToRightTop {#RightTopToRightTop}
```
public static final int RightTopToRightTop
```


Правая верхняя точка нового изображения будет совпадать с правой верхней точкой оригинального изображения. Обрезка будет выполнена при необходимости.

### RightBottomToRightBottom {#RightBottomToRightBottom}
```
public static final int RightBottomToRightBottom
```


Правая нижняя точка нового изображения будет совпадать с правой нижней точкой оригинального изображения. Обрезка будет выполнена при необходимости.

### LeftBottomToLeftBottom {#LeftBottomToLeftBottom}
```
public static final int LeftBottomToLeftBottom
```


Левая нижняя точка нового изображения будет совпадать с левой нижней точкой оригинального изображения. Обрезка будет выполнена при необходимости.

### CenterToCenter {#CenterToCenter}
```
public static final int CenterToCenter
```


Центр нового изображения будет совпадать с центром оригинального изображения. Обрезка будет выполнена при необходимости.

### LanczosResample {#LanczosResample}
```
public static final int LanczosResample
```


Пересэмплирование с использованием алгоритма Ланцоша с a=3.

### NearestNeighbourResample {#NearestNeighbourResample}
```
public static final int NearestNeighbourResample
```


Пересэмплирование с использованием алгоритма ближайшего соседа.

### AdaptiveResample {#AdaptiveResample}
```
public static final int AdaptiveResample
```


Пересэмплирование с использованием адаптивного алгоритма, основанного на взвешенной и смешанной рациональной функции и алгоритмах интерполяции lanczos3.

### BilinearResample {#BilinearResample}
```
public static final int BilinearResample
```


Пересэмплирование с использованием билинейной интерполяции. Предварительная фильтрация изображения допускается для удаления шума перед пересэмплированием, при необходимости.

### HighQualityResample {#HighQualityResample}
```
public static final int HighQualityResample
```


Высококачественное пересэмплирование

### CatmullRom {#CatmullRom}
```
public static final int CatmullRom
```


Метод кубической интерполяции Catmull-Rom.

### CubicConvolution {#CubicConvolution}
```
public static final int CubicConvolution
```


Метод кубической конволюционной интерполяции

### CubicBSpline {#CubicBSpline}
```
public static final int CubicBSpline
```


Метод кубической интерполяции CubicBSpline

### Mitchell {#Mitchell}
```
public static final int Mitchell
```


Метод кубической интерполяции Mitchell

### SinC {#SinC}
```
public static final int SinC
```


Метод кубической интерполяции Sinc (Lanczos3)

### Bell {#Bell}
```
public static final int Bell
```


Метод интерполяции Bell

