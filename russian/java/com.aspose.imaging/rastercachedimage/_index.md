---
title: "RasterCachedImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет растровое изображение, поддерживающее операции растровой графики."
type: docs
weight: 89
url: /ru/java/com.aspose.imaging/rastercachedimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage)
```
public abstract class RasterCachedImage extends RasterImage
```

Представляет растровое изображение, поддерживающее операции растровой графики. Это изображение кэширует данные пикселей при необходимости.
## Методы

| Метод | Описание |
| --- | --- |
| [isCached()](#isCached--) | Возвращает значение, указывающее, кэшированы ли данные изображения в данный момент. |
| [cacheData()](#cacheData--) | Кеширует данные и гарантирует, что дополнительная загрузка данных из базового `DataStreamSupporter.DataStreamContainer` не будет выполнена. |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | Смешивает данный экземпляр изображения с изображением `overlay`. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Изменяет размер изображения. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Изменяет размер изображения. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Поворачивает, отражает или одновременно поворачивает и отражает изображение. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Поворачивает изображение вокруг центра. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Обрезка изображения. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Выполняет дизеринг текущего изображения. |
| [grayscale()](#grayscale--) | Преобразование изображения в его градации серого |
| [normalizeHistogram()](#normalizeHistogram--) | Нормализует гистограмму изображения \\u2014 корректирует значения пикселей, чтобы использовать весь доступный диапазон. |
| [autoBrightnessContrast()](#autoBrightnessContrast--) | Выполняет автоматическую адаптивную нормализацию яркости и контрастности для всего изображения. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Бинаризация изображения с предопределённым порогом |
| [binarizeOtsu()](#binarizeOtsu--) | Бинаризация изображения с порогом Оцу |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном изображении |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном изображении |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Регулировка яркости изображения. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Контрастирование изображения |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Гамма‑коррекция изображения. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Гамма‑коррекция изображения. |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | Встраивает цифровую подпись, основанную на предоставленном пароле, в изображение с помощью стеганографии. |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | Вычисляет процентное сходство между извлечёнными данными и оригинальным паролем. |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | Выполняет быструю проверку, определяющую, подписано ли изображение цифровой подписью, используя предоставленный пароль и порог. |

## Example: The following example transforms a colored raster cached image to its grayscale representation.
В следующем примере цветное растровое кешированное изображение преобразуется в его градацию серого. Изображения в градациях серого состоят исключительно из оттенков серого и содержат только информацию о интенсивности.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    rasterImage.grayscale();
    rasterImage.save(dir + "sample.Grayscale.png");
} finally {
    image.dispose();
}
```

### isCached() {#isCached--}
```
public boolean isCached()
```


Возвращает значение, указывающее, кэшированы ли данные изображения в данный момент.

**Returns:**
boolean — `true`, если данные изображения кешированы; иначе `false`.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Кеширует данные и гарантирует, что дополнительная загрузка данных из базового `DataStreamSupporter.DataStreamContainer` не будет выполнена.


**Example: The following example shows how raster image caching affects performance.**
В следующем примере показано, как кеширование растровых изображений влияет на производительность. Как правило, чтение кешированных данных происходит быстрее, чем чтение некешированных данных.
``` java
String dir = "c:\\temp\\";

// Загрузить изображение из PNG‑файла.
com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Кешировать все данные пикселей, чтобы дополнительная загрузка данных из базового потока не выполнялась
    image.cacheData();

    long startTime = System.currentTimeMillis();

    // Чтение всех пикселей происходит довольно быстро.
    for (int y = 0; y < image.getHeight(); y++) {
        for (int x = 0; x < image.getWidth(); x++) {
            int color = image.getArgb32Pixel(x, y);
        }
    }

    long stopTime = System.currentTimeMillis();
    long elapsedMilliseconds = stopTime - startTime;
    System.out.println("Reading all cached pixels took " + elapsedMilliseconds + " ms.");
} finally {
    image.dispose();
}

// Загрузить изображение из PNG‑файла
image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    long startTime = System.currentTimeMillis();

    // Чтение всех пикселей не так быстро, как при кэшировании
    for (int y = 0; y < image.getHeight(); y++) {
        for (int x = 0; x < image.getWidth(); x++) {
            int color = image.getArgb32Pixel(x, y);
        }
    }

    long stopTime = System.currentTimeMillis();
    long elapsedMilliseconds = stopTime - startTime;
    System.out.println("Reading all pixels without preliminary caching took " + elapsedMilliseconds + " ms.");
} finally {
    image.dispose();
}

// Вывод может выглядеть так:
//Чтение всех кэшированных пикселей заняло 2923 мс.
//    java.lang.OutOfMemoryError
//at com.aspose.imaging.internal.G.be.b(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.aB.a(Unknown Source)
//at com.aspose.imaging.RasterImage.a(Unknown Source)
//at com.aspose.imaging.RasterImage.getArgb32Pixel(Unknown Source)
//at com.aspose.examples.ExamplesTest.Test(ExamplesTest.java:54)
```

### blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-}
```
public void blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)
```


Смешивает данный экземпляр изображения с изображением `overlay`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | Исходная точка смешения фонового изображения. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | Наложенное изображение. |
| overlayArea | [Rectangle](../../com.aspose.imaging/rectangle) | Область наложения. |
| overlayAlpha | byte | Прозрачность наложения. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Изменяет размер изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| resizeType | int | Тип изменения размера. |


**Example: This example loads a raster cached image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Увеличить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Уменьшить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Увеличить в 2 раза с использованием билинейного ресэмплинга.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Уменьшить в 2 раза с использованием билинейного ресэмплинга.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Изменяет размер изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Настройки изменения размера. |


**Example: This example loads a raster cached image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// Адаптивный алгоритм, основанный на взвешенной и смешанной рациональной функции и интерполяции lanczos3.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// Небольшой прямоугольный фильтр
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// Количество цветов в палитре.
resizeSettings.setEntriesCount(256);

// Квантование цветов не используется
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// Эвклидов метод
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Уменьшить в 2 раза с помощью адаптивного пересэмплинга.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);
    image.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Поворачивает, отражает или одновременно поворачивает и отражает изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rotateFlipType | int | Тип вращающего отражения. |


**Example: This example loads a raster cached image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

// Это вспомогательный класс.
class LocalHelper {
    // Получает строковое представление типа вращающего отражения.
    public String rotateFlipTypeToString(int rotateFilpType) {
        switch (rotateFilpType) {
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipNone:
                return "RotateNoneFlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipNone:
                return "Rotate90FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipNone:
                return "Rotate180FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipNone:
                return "Rotate270FlipNone";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipX:
                return "RotateNoneFlipX";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipX:
                return "Rotate90FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipX:
                return "Rotate180FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipX:
                return "Rotate270FlipX";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipY:
                return "RotateNoneFlipY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipY:
                return "Rotate90FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipY:
                return "Rotate180FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipY:
                return "Rotate270FlipY";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipXY:
                return "RotateNoneFlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipXY:
                return "Rotate90FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipXY:
                return "Rotate180FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipXY:
                return "Rotate270FlipXY";
            default:
                throw new java.lang.IllegalArgumentException("rotateFlipType");
        }
    }
}

// Вот основной пример
int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

LocalHelper localHelper = new LocalHelper();
for (int rotateFlipType : rotateFlipTypes) {
    // Поверните, отразите и сохраните в выходной файл.
    com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + localHelper.rotateFlipTypeToString(rotateFlipType) + ".bmp");
    } finally {
        image.dispose();
    }
}
```

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Поворачивает изображение вокруг центра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения в градусах. Положительные значения вращают по часовой стрелке. |
| resizeProportionally | boolean | Если установить `true`, размер вашего изображения будет изменён в соответствии с проекциями вращённого прямоугольника (угловых точек); в противном случае размеры останутся неизменными, и будет вращено только внутреннее содержимое изображения. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Цвет фона. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Обрезка изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник. |


**Example: The following example crops a raster cached image.**
В следующем примере происходит обрезка растрового кэшированного изображения. Область обрезки указывается через com.aspose.imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Обрежьте изображение. Область обрезки — прямоугольный центральный участок изображения.
    int width = rasterImage.getWidth();
    int height = rasterImage.getHeight();
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(width / 4, height / 4, width / 2, height / 2);
    rasterImage.crop(area);

    // Сохраните обрезанное изображение в PNG
    rasterImage.save(dir + "sample.Crop.png");
} finally {
    image.dispose();
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Выполняет дизеринг текущего изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ditheringMethod | int | Метод дизеринга. |
| bitsCount | int | Окончательное количество бит для дизеринга. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Пользовательская палитра для дизеринга. |

### grayscale() {#grayscale--}
```
public void grayscale()
```


Преобразование изображения в его градации серого


**Example: The following example transforms a colored raster cached image to its grayscale representation.**
В следующем примере цветное растровое кешированное изображение преобразуется в его градацию серого. Изображения в градациях серого состоят исключительно из оттенков серого и содержат только информацию о интенсивности.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    rasterImage.grayscale();
    rasterImage.save(dir + "sample.Grayscale.png");
} finally {
    image.dispose();
}
```

### normalizeHistogram() {#normalizeHistogram--}
```
public void normalizeHistogram()
```


Нормализует гистограмму изображения \\u2014 корректирует значения пикселей, чтобы использовать весь доступный диапазон.

### autoBrightnessContrast() {#autoBrightnessContrast--}
```
public void autoBrightnessContrast()
```


Выполняет автоматическую адаптивную нормализацию яркости и контрастности для всего изображения.

--------------------

> ```
> // Example usage in image pre-processing:
>  image.AutoBrightnessContrast();
> ```

--------------------

Этот метод применяет конвейер продвинутых адаптивных фильтров (CLAHE, adaptive white stretch, and auto white balance) для улучшения визуального качества изображения за счёт повышения контрастности, локальной яркости и точности цветов.

`**Filter pipeline:**`

1.  Contrast-Limited Adaptive Histogram Equalization (CLAHE) \u2013 улучшает локальный контраст и усиливает слабые детали.
2.  Adaptive White Stretch \u2013 повышает эффективный уровень белого, защищая тёмные детали.
3.  Auto White Balance \u2013 корректирует цветовые оттенки, балансируя гистограммы каналов.

`**Note:**`

 *  
 *  

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Бинаризация изображения с предопределённым порогом

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | byte | Значение порога. Если соответствующее серое значение пикселя больше порога, ему будет присвоено значение 255, иначе — 0. |


**Example: The following example binarizes a raster cached image with the predefined threshold.**
В следующем примере растровое кэшированное изображение бинаризуется с предопределённым порогом. Бинаризованные изображения содержат только 2 цвета - чёрный и белый.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Бинаризуйте изображение с пороговым значением 127.
    // Если соответствующее серое значение пикселя больше 127, ему будет присвоено значение 255, иначе 0.
    rasterImage.binarizeFixed((byte) 127);
    rasterImage.save(dir + "sample.BinarizeFixed.png");
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Бинаризация изображения с порогом Оцу


**Example: The following example binarizes a raster cached image with Otsu thresholding.**
В следующем примере происходит бинаризация растрового кэшированного изображения с пороговой обработкой Оцу. Бинаризованные изображения содержат только 2 цвета — чёрный и белый.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Бинаризуйте изображение с пороговой обработкой Оцу.
    rasterImage.binarizeOtsu();
    rasterImage.save(dir + "sample.BinarizeOtsu.png");
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном изображении

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightnessDifference | double | Разница яркости между пикселем и средним значением окна s × s пикселей, центрированного вокруг этого пикселя. |
| windowSize | int | Размер окна s × s пикселей, центрированного вокруг этого пикселя. |


**Example: The following example binarizes a raster cached image with Bradley's adaptive thresholding algorithm with the specified window size.**
В следующем примере происходит бинаризация растрового кэшированного изображения с адаптивным пороговым алгоритмом Брэдли с указанным размером окна. Бинаризованные изображения содержат только 2 цвета — чёрный и белый.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Бинаризуйте изображение с разницей яркости 5.
    // Яркость — это разница между пикселем и средним значением окна 10 × 10 пикселей, центрированного вокруг этого пикселя.
    rasterImage.binarizeBradley(5, 10);
    rasterImage.save(dir + "sample.BinarizeBradley5_10x10.png");
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном изображении

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightnessDifference | double | Разница яркости между пикселем и средним значением окна s × s пикселей, центрированного вокруг этого пикселя. |


**Example: The following example binarizes a raster cached image with Bradley's adaptive thresholding algorithm.**
В следующем примере происходит бинаризация растрового кэшированного изображения с адаптивным пороговым алгоритмом Брэдли. Бинаризованные изображения содержат только 2 цвета — чёрный и белый.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Бинаризуйте изображение с разницей яркости 5.
    // Яркость — это разница между пикселем и средним значением окна s × s пикселей, центрированного вокруг этого пикселя.
    // Размер окна будет калиброван автоматически.
    rasterImage.binarizeBradley(5);
    rasterImage.save(dir + "sample.BinarizeBradley5.png");
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Регулировка яркости изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightness | int | Значение яркости. |


**Example: The following example performs brightness correction of a raster cached image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Установите значение яркости. Допустимые значения яркости находятся в диапазоне [-255, 255].
    rasterImage.adjustBrightness(50);
    rasterImage.save(dir + "sample.AdjustBrightness.png");
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Контрастирование изображения

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| contrast | float | Значение контрастности (в диапазоне [-100; 100]) |


**Example: The following example performs contrast correction of a raster cached image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Установите значение контрастности. Допустимые значения контрастности находятся в диапазоне [-100f, 100f].
    rasterImage.adjustContrast(50);
    rasterImage.save(dir + "sample.AdjustContrast.png");
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Гамма‑коррекция изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| gammaRed | float | Коэффициент гаммы для красного канала |
| gammaGreen | float | Коэффициент гаммы для зелёного канала |
| gammaBlue | float | Коэффициент гаммы для синего канала |


**Example: The following example performs gamma-correction of a raster cached image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Установите отдельные коэффициенты гаммы для красного, зелёного и синего каналов.
    rasterImage.adjustGamma(1.5f, 2.5f, 3.5f);
    rasterImage.save(dir + "sample.AdjustGamma.png");
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Гамма‑коррекция изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| гамма | float | Коэффициент гаммы для красного, зелёного и синего каналов |


**Example: The following example performs gamma-correction of a raster cached image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Установите коэффициент гаммы для красного, зелёного и синего каналов.
    rasterImage.adjustGamma(2.5f);
    rasterImage.save(dir + "sample.AdjustGamma.png");
} finally {
    image.dispose();
}
```

### embedDigitalSignature(String password) {#embedDigitalSignature-java.lang.String-}
```
public void embedDigitalSignature(String password)
```


Встраивает цифровую подпись, основанную на предоставленном пароле, в изображение с помощью стеганографии.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| пароль | java.lang.String | Пароль, используемый для генерации данных цифровой подписи |


**Example: The example shows how to embed digital signature based on provided password into image pixel data.**

``` java
String imageFilePath = "ball.png";
String password = "veryStr0ngPassword";
try (Image image = Image.load(imageFilePath))
{
    image.embedDigitalSignature(password);
    image.save(outputPath);
}
```

### analyzePercentageDigitalSignature(String password) {#analyzePercentageDigitalSignature-java.lang.String-}
```
public int analyzePercentageDigitalSignature(String password)
```


Вычисляет процентное сходство между извлечёнными данными и оригинальным паролем.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| пароль | java.lang.String | Пароль, используемый для извлечения встроенных данных. |

**Returns:**
int - Значение процента схожести.
### isDigitalSigned(String password, int percentageThreshold) {#isDigitalSigned-java.lang.String-int-}
```
public boolean isDigitalSigned(String password, int percentageThreshold)
```


Выполняет быструю проверку, определяющую, подписано ли изображение цифровой подписью, используя предоставленный пароль и порог.

--------------------

Этот метод обеспечивает самое быстрое обнаружение, используя `GetSignPercentage`. Как только извлечённые данные достигают указанного порога, дальнейшие шаги извлечения, направленные на повышение точности обнаружения, пропускаются.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| пароль | java.lang.String | Пароль для проверки подписи. |
| percentageThreshold | int | Порог (в процентах)[0-100], определяющий, считается ли изображение подписанным. Если не указано, будет применён порог по умолчанию (`75`). |

**Returns:**
boolean - True, если изображение подписано, иначе false.
