---
title: "DitheringMethod"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Метод дизеринга."
type: docs
weight: 41
url: /ru/java/com.aspose.imaging/ditheringmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DitheringMethod extends System.Enum
```

Метод дизеринга.
## Поля

| Поле | Описание |
| --- | --- |
| [ThresholdDithering](#ThresholdDithering) | Пороговое дизеринг. |
| [FloydSteinbergDithering](#FloydSteinbergDithering) | Дизеринг Флойда-Стейнберга. |

## Example: The following example loads a raster image and performs threshold and floyd dithering using different palette depth.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Выполнить пороговое дизеринг с использованием 4-битовой цветовой палитры, содержащей 16 цветов.
    // Чем больше указано бит, тем выше качество и тем больше размер выходного изображения.
    // Обратите внимание, что в данный момент поддерживаются только 1-битовые, 4-битовые и 8-битовые палитры.
    rasterImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4);

    rasterImage.save(dir + "sample.ThresholdDithering4.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Выполнить дизеринг Флойда с использованием 1-битовой цветовой палитры, содержащей только 2 цвета — черный и белый.
    // Чем больше указано бит, тем выше качество и тем больше размер выходного изображения.
    // Обратите внимание, что в данный момент поддерживаются только 1-битовые, 4-битовые и 8-битовые палитры.
    rasterImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1);

    rasterImage.save(dir + "sample.FloydSteinbergDithering1.png");
} finally {
    image.dispose();
}
```

### ThresholdDithering {#ThresholdDithering}
```
public static final int ThresholdDithering
```


Пороговое дизеринг. Самый простой и быстрый алгоритм дизеринга.

### FloydSteinbergDithering {#FloydSteinbergDithering}
```
public static final int FloydSteinbergDithering
```


Алгоритм Флойда-Стейнберга. Более сложный алгоритм дизеринга, использующий значения интенсивности ближайших соседей.

