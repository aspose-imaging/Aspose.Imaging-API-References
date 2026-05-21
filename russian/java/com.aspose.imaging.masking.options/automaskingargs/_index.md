---
title: "AutoMaskingArgs"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет аргументы, указанные для автоматических методов маскирования"
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.masking.options/automaskingargs/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.masking.options.IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

Представляет аргументы, указанные для автоматических методов маскирования
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getNumberOfObjects()](#getNumberOfObjects--) | Получает количество объектов, на которое следует разделить исходное изображение (необязательно), значение по умолчанию — 2 (объект и фон). |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | Устанавливает количество объектов, на которое следует разделить исходное изображение (необязательно), значение по умолчанию — 2 (объект и фон). |
| [getObjectsRectangles()](#getObjectsRectangles--) | Получает прямоугольники объектов, принадлежащие разделённым объектам (необязательно). |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.imaging.Rectangle---) | Устанавливает прямоугольники объектов, принадлежащие разделённым объектам (необязательно). |
| [getObjectsPoints()](#getObjectsPoints--) | Получает точки, принадлежащие разделённым объектам (необязательно) NumberOfObjects координаты, принадлежащие NumberOfObjects объектам исходного изображения. |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.imaging.Point-----) | Устанавливает точки, принадлежащие разделённым объектам (необязательно) NumberOfObjects координаты, принадлежащие NumberOfObjects объектам исходного изображения. |
| [getOrphanedPoints()](#getOrphanedPoints--) | Получает точки, которые больше не принадлежат ни одному объекту (необязательно). |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.imaging.Point---) | Устанавливает точки, которые больше не принадлежат ни одному объекту (необязательно). |
| [getPrecision()](#getPrecision--) | Получает точность метода сегментации (необязательно). |
| [setPrecision(double value)](#setPrecision-double-) | Устанавливает точность метода сегментации (необязательно). |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | Получает максимальное количество итераций. |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | Устанавливает максимальное количество итераций. |

## Example: This example shows how to decompose a raster image into multiple images using image masking and the K-means segmentation algorithm.
Этот пример показывает, как разложить растровое изображение на несколько изображений с использованием маскирования изображения и алгоритма сегментации K-средних. Маскирование изображения — это техника обработки изображений, используемая для разделения фона и объектов на переднем плане.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Blue hills.png");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // Установите количество кластеров (разделённых объектов). Значение по умолчанию — 2: объект переднего плана и фон.
    args.setNumberOfObjects(3);

    // Установите максимальное количество итераций.
    args.setMaxIterationNumber(50);

    // Установите точность метода сегментации (необязательно)
    args.setPrecision(1);

    // Каждый кластер (сегмент) будет сохранён в отдельный PNG‑файл.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Используйте кластеризацию K‑средних.
    // Кластеризация K‑средних позволяет разделить изображение на несколько независимых кластеров (сегментов).
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.KMeans);
    maskingOptions.setDecompose(true);
    maskingOptions.setArgs(args);

    // Цвет фона будет оранжевым.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Создайте экземпляр класса ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Разделите исходное изображение на несколько кластеров (сегментов).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);
    try
    {
        // Получите изображения из результата маскирования и сохраните их в PNG.
        for (int i = 0; i < maskingResults.getLength(); i++) {
            final IMaskingLayer resultsItem = maskingResults.get_Item(i);
            String outputFileName = String.format("Blue hills.Segment%s.png", resultsItem.getObjectNumber());
            Image resultImage = resultsItem.getImage();
            try {
                resultImage.save(dir + outputFileName);
            } finally {
                resultImage.close();
            }
        }
    }
    finally
    {
        maskingResults.close();
    }
} finally {
    image.close();
}
```


## Example: This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method.
Этот пример показывает, как задать предложения для алгоритма маскирования изображения с целью повышения точности метода сегментации (кластеризации). Маскирование изображения — это техника обработки изображений, используемая для разделения фона и объектов на переднем плане.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // Предложение №1.
    // Визуально проанализируйте изображение и задайте область интереса. Результат сегментации будет включать только объекты, полностью находящиеся внутри этой области.
    args.setObjectsRectangles(new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(86, 6, 270, 364),
            });

    // Предложение №2.
    // Визуально проанализировать изображение и установить точки, принадлежащие отдельным объектам.
    args.setObjectsPoints(new com.aspose.imaging.Point[][]
            {
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(103, 326)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(280, 43)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(319, 86)},
            });

    // Каждый кластер (сегмент) будет сохранён в отдельный PNG‑файл.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Использовать кластеризацию GraphCut.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // Цвет фона будет оранжевым.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Создайте экземпляр класса ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Разделите исходное изображение на несколько кластеров (сегментов).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // Получите изображения из результата маскирования и сохраните их в PNG.
        for (int i = 0; i < maskingResults.getLength(); i++) {
            String outputFileName = String.format("Gorilla.Segment%s.png", maskingResults.get_Item(i).getObjectNumber());
            Image resultImage = maskingResults.get_Item(i).getImage();
            try {
                resultImage.save(dir + outputFileName);
            } finally {
                resultImage.close();
            }
        }
    }
    finally
    {
        maskingResults.close();
    }
} finally {
    image.close();
}
```


## Example: Using a segment mask to speed up the segmentation process

``` java
// Параметры экспорта маскирования
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Использовать кластеризацию GraphCut.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// Фоновый цвет будет прозрачным.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getTransparent());
maskingOptions.setExportOptions(exportOptions);

String dir = "c:\\temp\\";
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
try
{
    com.aspose.imaging.Size imageSize = image.getSize();

    // Уменьшение размера изображения для ускорения процесса сегментации
    image.resizeHeightProportionally(600, com.aspose.imaging.ResizeType.HighQualityResample);

    // Создайте экземпляр класса ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Разделите исходное изображение на несколько кластеров (сегментов).
    com.aspose.imaging.masking.result.MaskingResult maskingResult = masking.decompose(maskingOptions);
    try
    {
        // Получение маски переднего плана
        com.aspose.imaging.RasterImage foregroundMask = maskingResult.get_Item(1).getMask();
        try
        {
            // Увеличьте размер маски до размера оригинального изображения
            foregroundMask.resize(imageSize.getWidth(), imageSize.getHeight(), com.aspose.imaging.ResizeType.NearestNeighbourResample);

            // Применение маски к оригинальному изображению для получения сегмента переднего плана
            com.aspose.imaging.RasterImage originImage = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
            try
            {
                com.aspose.imaging.masking.ImageMasking.applyMask(originImage, foregroundMask, maskingOptions);
                originImage.save(dir + "BigImage_foreground.png", exportOptions);
            }
            finally
            {
                originImage.close();
            }
        }
        finally
        {
            foregroundMask.close();
        }
    }
    finally
    {
        maskingResult.close();
    }
}
finally
{
    image.close();
}
```


## Example: Saving the masking session to a file for long sessions, as well as for the possibility of resuming the session in another environment.

``` java
String dir = "c:\\temp\\";
String sessionBackupFile = dir + "session.bak";

// Параметры экспорта маскирования
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Использовать кластеризацию GraphCut.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// Цвет фона будет оранжевым.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
maskingOptions.setExportOptions(exportOptions);

// Запуск сеанса в первый раз и сохранение в файл
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // Создайте экземпляр класса ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    com.aspose.imaging.masking.IMaskingSession session = masking.createSession(maskingOptions);
    try
    {
        com.aspose.imaging.masking.result.MaskingResult maskingResult = session.decompose();
        try
        {
            com.aspose.imaging.RasterImage segmentImage = maskingResult.get_Item(1).getImage();
            try
            {
                segmentImage.save(dir + "step1.png");
            }
            finally
            {
                segmentImage.close();
            }
        }
        finally
        {
            maskingResult.close();
        }

        session.save(sessionBackupFile);
    }
    finally
    {
        session.dispose();
    }
}
finally
{
    image.close();
}

// Возобновление сеанса маскирования из файла
com.aspose.imaging.RasterImage image2 = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // Создайте экземпляр класса ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image2);

    com.aspose.imaging.masking.IMaskingSession session = masking.loadSession(sessionBackupFile);
    try
    {
        com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

        // Визуально проанализировать изображение и установить точки, принадлежащие отдельным объектам.
        args.setObjectsPoints(new Point[][]
                {
                        new Point[]
                                {
                                        new Point(0, 0), new Point(0, 1), new Point(1, 0),
                                        new Point(1, 1), new Point(2, 0), new Point(2, 1),
                                        new Point(3, 0), new Point(3, 1)
                                },
                });
        com.aspose.imaging.masking.result.MaskingResult maskingResult = session.improveDecomposition(args);
        try
        {
            // Явная передача параметров экспорта, поскольку они не сериализуемы
            maskingResult.MaskingOptions.setExportOptions(exportOptions);

            com.aspose.imaging.RasterImage segmentImage = maskingResult.get_Item(1).getImage();
            try
            {
                segmentImage.save(dir + "step2.png");
            }
            finally
            {
                segmentImage.close();
            }
        }
        finally
        {
            maskingResult.close();
        }
    }
    finally
    {
        session.dispose();
    }
}
finally
{
    image2.close();
}
```

### AutoMaskingArgs() {#AutoMaskingArgs--}
```
public AutoMaskingArgs()
```


### getNumberOfObjects() {#getNumberOfObjects--}
```
public final int getNumberOfObjects()
```


Получает количество объектов, на которое следует разделить исходное изображение (необязательно), значение по умолчанию — 2 (объект и фон).

Значение: количество объектов.

**Returns:**
int — количество объектов, на которое следует разделить исходное изображение (необязательно), значение по умолчанию — 2 (объект и фон).
### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


Устанавливает количество объектов, на которое следует разделить исходное изображение (необязательно), значение по умолчанию — 2 (объект и фон).

Значение: количество объектов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | количество объектов, на которое следует разделить исходное изображение (необязательно), значение по умолчанию — 2 (объект и фон). |

### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


Получает прямоугольники объектов, принадлежащие разделённым объектам (необязательно). Этот параметр используется для повышения точности метода сегментации.

Значение: прямоугольники объектов.

**Returns:**
com.aspose.imaging.Rectangle[] — прямоугольники объектов, принадлежащие разделённым объектам (необязательно).
### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.imaging.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


Устанавливает прямоугольники объектов, принадлежащие разделённым объектам (необязательно). Этот параметр используется для повышения точности метода сегментации.

Значение: прямоугольники объектов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) | прямоугольники объектов, принадлежащие разделённым объектам (необязательно). |

### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


Получает точки, принадлежащие разделённым объектам (необязательно) NumberOfObjects координаты, принадлежащие NumberOfObjects объектам исходного изображения. Этот параметр используется для повышения точности метода сегментации.

Значение: точки объектов.

**Returns:**
com.aspose.imaging.Point[][] — точки, принадлежащие разделённым объектам (необязательно) NumberOfObjects координаты, принадлежащие NumberOfObjects объектам исходного изображения.
### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.imaging.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


Устанавливает точки, принадлежащие отдельным объектам (необязательно) NumberOfObjects координаты, принадлежащие NumberOfObjects объектам исходного изображения. Этот параметр используется для повышения точности метода сегментации.

Значение: точки объектов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) | точки, принадлежащие отдельным объектам (необязательно) NumberOfObjects координаты, принадлежащие NumberOfObjects объектам исходного изображения. |

### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


Получает точки, которые больше не принадлежат ни одному объекту (необязательно). Этот параметр используется только в случае повторной сегментации.

Значение: Оси́роченные точки.

**Returns:**
com.aspose.imaging.Point[] — точки, которые больше не принадлежат ни одному объекту (необязательно).
### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.imaging.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


Устанавливает точки, которые больше не принадлежат ни одному объекту (необязательно). Этот параметр используется только в случае повторной сегментации.

Значение: Оси́роченные точки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) | точки, которые больше не принадлежат ни одному объекту (необязательно). |

### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


Получает точность метода сегментации (необязательно).

Значение: Точность метода сегментации (необязательно).

**Returns:**
double — точность метода сегментации (необязательно).
### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


Устанавливает точность метода сегментации (необязательно).

Значение: Точность метода сегментации (необязательно).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | точность метода сегментации (необязательно). |

### getMaxIterationNumber() {#getMaxIterationNumber--}
```
public final int getMaxIterationNumber()
```


Получает максимальное количество итераций.

Значение: Максимальное максимальное количество итераций.

**Returns:**
int — максимальное количество итераций.
### setMaxIterationNumber(int value) {#setMaxIterationNumber-int-}
```
public final void setMaxIterationNumber(int value)
```


Устанавливает максимальное количество итераций.

Значение: Максимальное максимальное количество итераций.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | максимальное количество итераций. |

