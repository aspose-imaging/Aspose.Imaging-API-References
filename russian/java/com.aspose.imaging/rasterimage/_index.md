---
title: "RasterImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет растровое изображение, поддерживающее операции растровой графики."
type: docs
weight: 91
url: /ru/java/com.aspose.imaging/rasterimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image)

**All Implemented Interfaces:**
[com.aspose.imaging.IRasterImageArgb32PixelLoader](../../com.aspose.imaging/irasterimageargb32pixelloader), com.aspose.internal.IPixelsSaver, [com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public abstract class RasterImage extends Image implements IRasterImageArgb32PixelLoader, IPixelsSaver, IHasXmpData
```

Представляет растровое изображение, поддерживающее операции растровой графики.
## Методы

| Метод | Описание |
| --- | --- |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Получает или задает значение, указывающее, должны ли компоненты изображения быть предварительно умноженными. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Получает или задает значение, указывающее, должны ли компоненты изображения быть предварительно умноженными. |
| [getUseRawData()](#getUseRawData--) | Получает или задает значение, указывающее, использовать ли загрузку необработанных данных, когда она доступна. |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Получает или задает значение, указывающее, использовать ли загрузку необработанных данных, когда она доступна. |
| [getUpdateXmpData()](#getUpdateXmpData--) | Получает или задает значение, указывающее, обновлять ли метаданные XMP. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Получает или задает значение, указывающее, обновлять ли метаданные XMP. |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Получает или задает индексированный конвертер цветов |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-) | Получает или задает индексированный конвертер цветов |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Получает или задает пользовательский конвертер цветов |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.imaging.IColorConverter-) | Получает или задает пользовательский конвертер цветов |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Получает или задает запасной индекс, используемый, когда индекс палитры выходит за пределы |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Получает или задает запасной индекс, используемый, когда индекс палитры выходит за пределы |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [isUsePalette()](#isUsePalette--) | Получает значение, указывающее, используется ли палитра изображения. |
| [getRawDataFormat()](#getRawDataFormat--) | Получает формат необработанных данных. |
| [getRawLineSize()](#getRawLineSize--) | Получает размер строки необработанных данных в байтах. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Получает значение, указывающее, доступна ли загрузка необработанных данных. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Получает или задает горизонтальное разрешение, в пикселях на дюйм, этого `RasterImage`. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Получает или задает горизонтальное разрешение, в пикселях на дюйм, этого `RasterImage`. |
| [getVerticalResolution()](#getVerticalResolution--) | Получает или задает вертикальное разрешение, в пикселях на дюйм, этого `RasterImage`. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Получает или задает вертикальное разрешение, в пикселях на дюйм, этого `RasterImage`. |
| [hasTransparentColor()](#hasTransparentColor--) | Получает значение, указывающее, имеет ли данный экземпляр [RasterImage](../../com.aspose.imaging/rasterimage) прозрачный цвет. |
| [hasAlpha()](#hasAlpha--) | Получает значение, указывающее, имеет ли этот экземпляр альфа‑канал. |
| [getTransparentColor()](#getTransparentColor--) | Получает прозрачный цвет изображения. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Задает значение, указывающее, имеет ли данный экземпляр [RasterImage](../../com.aspose.imaging/rasterimage) прозрачный цвет. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Получает прозрачный цвет изображения. |
| [getImageOpacity()](#getImageOpacity--) | Получает непрозрачность этого изображения. |
| [removeMetadata()](#removeMetadata--) | Удаляет метаданные этого экземпляра изображения, устанавливая значение `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) в `null`. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Получает дату и время последней модификации изображения ресурса. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | Выполняет дизеринг текущего изображения. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Выполняет дизеринг текущего изображения. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-) | Получает массив пикселей по умолчанию, используя частичный загрузчик пикселей. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialRawDataLoader-com.aspose.imaging.RawDataSettings-) | Получает массив необработанных данных по умолчанию, используя частичный загрузчик пикселей. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.imaging.Rectangle-) | Получает массив 32‑битных ARGB‑пикселей по умолчанию. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-) | Получает массив необработанных данных по умолчанию. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Получает 32‑битный ARGB‑пиксель изображения. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Получает пиксель изображения. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Устанавливает 32‑битный ARGB‑пиксель изображения для указанной позиции. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.imaging.Color-) | Устанавливает пиксель изображения для указанной позиции. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Читает всю строку сканирования по указанному индексу строки сканирования. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Читает всю строку сканирования по указанному индексу строки сканирования. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.imaging.Color---) | Записывает всю строку сканирования в указанный индекс строки сканирования. |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Записывает всю строку сканирования в указанный индекс строки сканирования. |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-) | Частично загружает 32‑битные ARGB‑пиксели пакетами. |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-) | Частично загружает пиксели пакетами. |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.imaging.Rectangle-) | Загружает 32‑битные ARGB‑пиксели. |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.imaging.Rectangle-) | Загружает 64‑битные ARGB‑пиксели. |
| [loadPartialArgb64Pixels(Rectangle rectangle, IPartialArgb64PixelLoader partialPixelLoader)](#loadPartialArgb64Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb64PixelLoader-) | Частично загружает 64‑битные ARGB‑пиксели пакетами. |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.imaging.Rectangle-) | Загружает пиксели. |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.imaging.Rectangle-) | Загружает пиксели в формате CMYK. |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.imaging.Rectangle-) | Загружает пиксели в формате CMYK. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-) | Загружает необработанные данные изображения, используя механизм частичной обработки. |
| [loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-) | Загружает необработанные данные. |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-) | Сохраняет необработанные данные. |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.imaging.Rectangle-int---) | Сохраняет 32‑битные ARGB‑пиксели. |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.imaging.Rectangle-com.aspose.imaging.Color---) | Сохраняет пиксели. |
| [toBitmap()](#toBitmap--) | Преобразует растровое изображение в bitmap. |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.CmykColor---) | Сохраняет пиксели. |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.imaging.Rectangle-int---) | Сохраняет пиксели. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Устанавливает разрешение для этого `RasterImage`. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Устанавливает палитру изображения. |
| [autoRotate()](#autoRotate--) | Автоматически вращает изображение на основе данных ориентации, извлечённых из метаданных Exif. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Изменяет размер изображения с расширенными параметрами. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Поворачивает изображение вокруг центра. |
| [rotate(float angle)](#rotate-float-) | Поворачивает изображение вокруг центра. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Бинаризация изображения с предопределённым порогом |
| [binarizeOtsu()](#binarizeOtsu--) | Бинаризация изображения с порогом Оцу |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном изображении |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном изображении |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-) | Смешивает данный экземпляр изображения с изображением `overlay`. |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | Смешивает данный экземпляр изображения с изображением `overlay`. |
| [blend(Point origin, RasterImage overlay)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-) | Смешивает этот экземпляр изображения с `overlay` при альфа == 255. |
| [blend(Point origin, RasterImage overlay, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-byte-) | Смешивает этот экземпляр изображения с `overlay`. |
| [grayscale()](#grayscale--) | Преобразование изображения в его градации серого |
| [normalizeHistogram()](#normalizeHistogram--) | Нормализует гистограмму изображения \\u2014 корректирует значения пикселей, чтобы использовать весь доступный диапазон. |
| [autoBrightnessContrast()](#autoBrightnessContrast--) | Автоматическая адаптивная нормализация яркости и контраста для всего изображения. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Регулировка яркости изображения. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Контрастирование изображения |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | Встраивает цифровую подпись, основанную на предоставленном пароле, в изображение с помощью стеганографии. |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | Вычисляет процентное сходство между извлечёнными данными и оригинальным паролем. |
| [isDigitalSigned(String password)](#isDigitalSigned-java.lang.String-) | Выполняет быструю проверку, определяющую, подписано ли изображение цифровой подписью, используя предоставленный пароль и порог. |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | Выполняет быструю проверку, определяющую, подписано ли изображение цифровой подписью, используя предоставленный пароль и порог. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Гамма‑коррекция изображения. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Гамма‑коррекция изображения. |
| [getSkewAngle()](#getSkewAngle--) | Получает угол наклона. |
| [normalizeAngle()](#normalizeAngle--) | Нормализует угол. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | Нормализует угол. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Фильтрует указанный прямоугольник. |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.imaging.Color-byte-com.aspose.imaging.Color-) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное альфа-значение, чтобы сохранить плавные края. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное альфа-значение, чтобы сохранить плавные края. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.imaging.Color-) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное альфа-значение, чтобы сохранить плавные края. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное альфа-значение, чтобы сохранить плавные края. |

## Example: This example shows how to load pixel information in an array of colors, manipulates the array and set it back to the image.

``` java
String dir = "c:\\temp\\";

// Создайте экземпляр GifOptions и задайте его различные свойства, включая свойство Source
com.aspose.imaging.imageoptions.GifOptions gifOptions = new com.aspose.imaging.imageoptions.GifOptions();
gifOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "output.gif", false));

// Создать экземпляр Image
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(gifOptions, 500, 500);
try {
    // Получите пиксели изображения, указав область как границу изображения
    com.aspose.imaging.Color[] pixels = image.loadPixels(image.getBounds());

    // Итерируйте массив и задавайте цвет альтернативного индексированного пикселя
    for (int index = 0; index < pixels.length; index++) {
        if (index % 2 == 0) {
            // Установите цвет индексированного пикселя в жёлтый
            pixels[index] = com.aspose.imaging.Color.getYellow();
        } else {
            // Установите цвет индексированного пикселя в синий
            pixels[index] = com.aspose.imaging.Color.getBlue();
        }
    }

    // Примените изменения пикселей к изображению
    image.savePixels(image.getBounds(), pixels);

    // Сохранить все изменения.
    image.save();
} finally {
    image.dispose();
}
```

### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Получает или задает значение, указывающее, должны ли компоненты изображения быть предварительно умноженными.

**Returns:**
boolean - `true`, если компоненты изображения должны быть предварительно умножены; иначе `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Получает или задает значение, указывающее, должны ли компоненты изображения быть предварительно умноженными.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | `true`, если компоненты изображения должны быть предварительно умножены; иначе `false`. |


**Example: The following example creates a new raster image, saves the specified semi-transparent pixels, then loads those pixels and gets final colors in the premultiplied form.**

``` java
int imageWidth = 3;
int imageHeight = 2;

com.aspose.imaging.Color[] colors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.fromArgb(127, 255, 0, 0),
                com.aspose.imaging.Color.fromArgb(127, 0, 255, 0),
                com.aspose.imaging.Color.fromArgb(127, 0, 0, 255),
                com.aspose.imaging.Color.fromArgb(127, 255, 255, 0),
                com.aspose.imaging.Color.fromArgb(127, 255, 0, 255),
                com.aspose.imaging.Color.fromArgb(127, 0, 255, 255),
        };

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, imageWidth, imageHeight);
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Сохранить пиксели для всего изображения.
    rasterImage.savePixels(rasterImage.getBounds(), colors);

    // Пиксели хранятся в оригинальном изображении в непреумноженной форме.
    // Необходимо явно указать соответствующую опцию, чтобы получить преумноженные цветовые компоненты.
    // Преумноженные цветовые компоненты вычисляются по формулам:
    // red = original_red * alpha / 255;
    // green = original_green * alpha / 255;
    // blue = original_blue * alpha / 255;
    rasterImage.setPremultiplyComponents(true);
    com.aspose.imaging.Color[] premultipliedColors = rasterImage.loadPixels(rasterImage.getBounds());

    for (int i = 0; i < colors.length; i++) {
        System.out.println("Original color: " + colors[i].toString());
        System.out.println("Premultiplied color: " + premultipliedColors[i].toString());
    }
} finally {
    image.dispose();
}
```

### getUseRawData() {#getUseRawData--}
```
public boolean getUseRawData()
```


Получает или задает значение, указывающее, использовать ли загрузку необработанных данных, когда она доступна.

**Returns:**
boolean - `true`, если использовать загрузку необработанных данных, когда она доступна; иначе `false`.
### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


Получает или задает значение, указывающее, использовать ли загрузку необработанных данных, когда она доступна.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | `true`, если использовать загрузку необработанных данных, когда она доступна; иначе `false`. |

### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


Получает или задает значение, указывающее, обновлять ли метаданные XMP.

**Returns:**
boolean - `true`, если обновлять метаданные XMP; иначе `false`.
### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


Получает или задает значение, указывающее, обновлять ли метаданные XMP.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | `true`, если обновлять метаданные XMP; иначе `false`. |

### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


Получает или задает индексированный конвертер цветов

**Returns:**
[IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) - The indexed color converter
### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


Получает или задает индексированный конвертер цветов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) | Индексированный конвертер цветов |

### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


Получает или задает пользовательский конвертер цветов

**Returns:**
[IColorConverter](../../com.aspose.imaging/icolorconverter) - The custom color converter
### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.imaging.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


Получает или задает пользовательский конвертер цветов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.imaging/icolorconverter) | Пользовательский конвертер цветов |

### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


Получает или задает запасной индекс, используемый, когда индекс палитры выходит за пределы

**Returns:**
int - Запасной индекс, используемый, когда индекс палитры выходит за пределы
### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


Получает или задает запасной индекс, используемый, когда индекс палитры выходит за пределы

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Запасной индекс, используемый, когда индекс палитры выходит за пределы |

### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


Получает текущие настройки необработанных данных. Обратите внимание, что при использовании этих настроек данные загружаются без конвертации.

**Returns:**
[RawDataSettings](../../com.aspose.imaging/rawdatasettings)
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Получает значение, указывающее, используется ли палитра изображения.

Значение: `true`, если палитра используется в изображении; иначе `false`.

**Returns:**
boolean — значение, указывающее, используется ли палитра изображения.
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Получает формат необработанных данных.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.

**Example: The following example loads raster images and prints information about raw data format and alpha channel.**

``` java

// Файлы изображений для загрузки.
String[] fileNames = new String[]
        {
                "c:\\temp\\sample.bmp",
                "c:\\temp\\alpha.png",
        };

for (String fileName : fileNames) {
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
    try {
        com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
        System.out.println(
                "ImageFile=" + fileName +
                        " FileFormat=" + rasterImage.getRawDataFormat() +
                        " HasAlpha=" + rasterImage.hasAlpha());
    } finally {
        image.dispose();
    }
}

// Вывод может выглядеть так:
// ImageFile=c:\temp\sample.bmp FileFormat=Rgb24Bpp, used channels: 8,8,8 HasAlpha=false
// ImageFile=c:\temp\alpha.png FileFormat=RGBA32Bpp, used channels: 8,8,8,8 HasAlpha=true
```

### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Получает размер строки необработанных данных в байтах.

**Returns:**
int - Размер необработанной строки в байтах.
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


Получает значение, указывающее, доступна ли загрузка необработанных данных.

**Returns:**
boolean - `true`, если загрузка этих необработанных данных доступна; иначе `false`.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Получает или задает горизонтальное разрешение, в пикселях на дюйм, этого `RasterImage`.

**Returns:**
double - Горизонтальное разрешение.

Примечание: по умолчанию это значение всегда равно 96, поскольку разные платформы не могут вернуть разрешение экрана. Вы можете рассмотреть возможность использования метода SetResolution для обновления обоих значений разрешения одним вызовом.

**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Получить горизонтальное и вертикальное разрешение изображения
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Используйте метод SetResolution для обновления обоих значений разрешения одним вызовом.
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // Вывод может выглядеть так:
    // Горизонтальное разрешение, в пикселях на дюйм: 300.0
    // Вертикальное разрешение, в пикселях на дюйм: 300.0
    // Установить значения разрешения в 96 dpi
    // Горизонтальное разрешение, в пикселях на дюйм: 96.0
    // Вертикальное разрешение, в пикселях на дюйм: 96.0
} finally {
    image.dispose();
}
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Получает или задает горизонтальное разрешение, в пикселях на дюйм, этого `RasterImage`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | double | Горизонтальное разрешение. |

Примечание: по умолчанию это значение всегда равно 96, поскольку разные платформы не могут вернуть разрешение экрана. Вы можете рассмотреть возможность использования метода SetResolution для обновления обоих значений разрешения одним вызовом. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Получает или задает вертикальное разрешение, в пикселях на дюйм, этого `RasterImage`.

**Returns:**
double - Вертикальное разрешение.

Примечание: по умолчанию это значение всегда равно 96, поскольку разные платформы не могут вернуть разрешение экрана. Вы можете рассмотреть возможность использования метода SetResolution для обновления обоих значений разрешения одним вызовом.

**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Получить горизонтальное и вертикальное разрешение изображения
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Используйте метод SetResolution для обновления обоих значений разрешения одним вызовом.
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // Вывод может выглядеть так:
    // Горизонтальное разрешение, в пикселях на дюйм: 300.0
    // Вертикальное разрешение, в пикселях на дюйм: 300.0
    // Установить значения разрешения в 96 dpi
    // Горизонтальное разрешение, в пикселях на дюйм: 96.0
    // Вертикальное разрешение, в пикселях на дюйм: 96.0
} finally {
    image.dispose();
}
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Получает или задает вертикальное разрешение, в пикселях на дюйм, этого `RasterImage`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | double | Вертикальное разрешение. |

Примечание: по умолчанию это значение всегда равно 96, поскольку разные платформы не могут вернуть разрешение экрана. Вы можете рассмотреть возможность использования метода SetResolution для обновления обоих значений разрешения одним вызовом. |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Получает значение, указывающее, имеет ли данный экземпляр [RasterImage](../../com.aspose.imaging/rasterimage) прозрачный цвет.

--------------------

Базовая реализация фактически возвращает ``, если она не переопределена в конкретной реализации, поддерживающей эту функцию. Это свойство в основном используется [FileFormat.Apng](../../com.aspose.imaging/fileformat\#Apng), [FileFormat.Png](../../com.aspose.imaging/fileformat\#Png), [FileFormat.Gif](../../com.aspose.imaging/fileformat\#Gif), [FileFormat.Tga](../../com.aspose.imaging/fileformat\#Tga) для установки прозрачного цвета, если изображение не поддерживает прозрачность через альфа-канал.

**Returns:**
boolean - значение, указывающее, имеет ли данный экземпляр [RasterImage](../../com.aspose.imaging/rasterimage) прозрачный цвет.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Получает значение, указывающее, имеет ли этот экземпляр альфа‑канал.

**Returns:**
boolean - `true`, если у этого экземпляра есть альфа; в противном случае `false`.

**Example: The following example loads raster images and prints information about raw data format and alpha channel.**

``` java

// Файлы изображений для загрузки.
String[] fileNames = new String[]
        {
                "c:\\temp\\sample.bmp",
                "c:\\temp\\alpha.png",
        };

for (String fileName : fileNames) {
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
    try {
        com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
        System.out.println(
                "ImageFile=" + fileName +
                        " FileFormat=" + rasterImage.getRawDataFormat() +
                        " HasAlpha=" + rasterImage.hasAlpha());
    } finally {
        image.dispose();
    }
}

// Вывод может выглядеть так:
// ImageFile=c:\temp\sample.bmp FileFormat=Rgb24Bpp, used channels: 8,8,8 HasAlpha=false
// ImageFile=c:\temp\alpha.png FileFormat=RGBA32Bpp, used channels: 8,8,8,8 HasAlpha=true
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Получает прозрачный цвет изображения.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Задает значение, указывающее, имеет ли данный экземпляр [RasterImage](../../com.aspose.imaging/rasterimage) прозрачный цвет.

--------------------

Базовая реализация фактически возвращает ``, если она не переопределена в конкретной реализации, поддерживающей эту функцию. Это свойство в основном используется [FileFormat.Apng](../../com.aspose.imaging/fileformat\#Apng), [FileFormat.Png](../../com.aspose.imaging/fileformat\#Png), [FileFormat.Gif](../../com.aspose.imaging/fileformat\#Gif), [FileFormat.Tga](../../com.aspose.imaging/fileformat\#Tga) для установки прозрачного цвета, если изображение не поддерживает прозрачность через альфа-канал.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, имеет ли данный экземпляр [RasterImage](../../com.aspose.imaging/rasterimage) прозрачный цвет. |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Получает прозрачный цвет изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Получает непрозрачность этого изображения.

**Returns:**
float - Значение непрозрачности от 0.0 (полностью прозрачно) до 1.0 (полностью непрозрачно).
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Удаляет метаданные этого экземпляра изображения, устанавливая значение `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) в `null`.

### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Получает дату и время последнего изменения ресурсного изображения. Этот метод предоставляет ценные метаданные, позволяющие пользователям эффективно отслеживать и управлять обновлениями файла изображения. Получая эту информацию, пользователи могут обеспечить целостность и актуальность своих графических ресурсов, способствуя принятию обоснованных решений относительно использования и обслуживания изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| useDefault | boolean | если установлено в `true`, использует информацию из FileInfo в качестве значения по умолчанию. |

**Returns:**
java.util.Date - Дата и время последнего изменения ресурсного изображения.
### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


Выполняет дизеринг текущего изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ditheringMethod | int | Метод дизеринга. |
| bitsCount | int | Окончательное количество бит для дизеринга. |


**Example: The following example loads a raster image and performs threshold and floyd dithering using different palette depth.**

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

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public abstract void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Выполняет дизеринг текущего изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ditheringMethod | int | Метод дизеринга. |
| bitsCount | int | Окончательное количество бит для дизеринга. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Пользовательская палитра для дизеринга. |

### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Получает массив пикселей по умолчанию, используя частичный загрузчик пикселей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник, для которого получаются пиксели. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader) | Частичный загрузчик пикселей. |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialRawDataLoader-com.aspose.imaging.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


Получает массив необработанных данных по умолчанию, используя частичный загрузчик пикселей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник, для которого получаются пиксели. |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | Частичный загрузчик необработанных данных. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Настройки необработанных данных. |

### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


Получает массив 32‑битных ARGB‑пикселей по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник, для которого получаются пиксели. |

**Returns:**
int[] - Массив пикселей по умолчанию.
### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


Получает массив необработанных данных по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник, для которого получаются необработанные данные. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Настройки необработанных данных. |

**Returns:**
byte[] — массив необработанных данных по умолчанию.
### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


Получает 32‑битный ARGB‑пиксель изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |

**Returns:**
int — 32‑битный ARGB‑пиксель для указанного положения.

**Example: The following example loads a raster image and obtains the color of an arbitrary pixel represented as a 32-bit integer value.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Получить целочисленное представление цвета пикселя в левом верхнем углу изображения.
    int color = rasterImage.getArgb32Pixel(0, 0);

    // Чтобы получить значения отдельных компонентов цвета, сдвиньте значение цвета на соответствующее количество битов.
    int alpha = (color >> 24) & 0xff;
    int red = (color >> 16) & 0xff;
    int green = (color >> 8) & 0xff;
    int blue = (color >> 0) & 0xff;

    System.out.println("The color of the pixel(0,0) is A=" + alpha + ",R=" + red + ",G=" + green + ",B=" + blue);
} finally {
    image.dispose();
}

// Вывод может выглядеть так:
// Цвет пикселя (0,0) — A=255,R=0,G=0,B=0.
```

### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


Получает пиксель изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The pixel color for the specified location.

**Example: The following example loads a raster image and obtains the color of an arbitrary pixel.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Получить цвет пикселя в левом верхнем углу изображения.
    com.aspose.imaging.Color color = rasterImage.getPixel(0, 0);

    // Получить значения отдельных компонентов цвета.
    int alpha = color.getA();
    int red = color.getR();
    int green = color.getG();
    int blue = color.getB();

    System.out.println("The color of the pixel(0,0) is A=" + alpha + ",R=" + red + ",G=" + green + ",B=" + blue);
} finally {
    image.dispose();
}
```

### setArgb32Pixel(int x, int y, int argb32Color) {#setArgb32Pixel-int-int-int-}
```
public void setArgb32Pixel(int x, int y, int argb32Color)
```


Устанавливает 32‑битный ARGB‑пиксель изображения для указанной позиции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |
| argb32Color | int | 32‑битный ARGB‑пиксель для указанной позиции. |


**Example: The following example loads a raster image, and sets the color of an arbitrary pixel.**

``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Устанавливает цвет пикселя в левом верхнем углу.
    rasterImage.setArgb32Pixel(0, 0, com.aspose.imaging.Color.getAqua().toArgb());

    // Другой способ — передать экземпляр com.aspose.imaging.Color напрямую.
    rasterImage.setPixel(0, 0, com.aspose.imaging.Color.getAqua());
} finally {
    image.dispose();
}
```

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.imaging.Color-}
```
public void setPixel(int x, int y, Color color)
```


Устанавливает пиксель изображения для указанной позиции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |
| color | [Color](../../com.aspose.imaging/color) | Цвет пикселя для указанной позиции. |


**Example: The following example loads a raster image, and sets the color of an arbitrary pixel.**

``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Устанавливает цвет пикселя в левом верхнем углу.
    rasterImage.setArgb32Pixel(0, 0, com.aspose.imaging.Color.getAqua().toArgb());

    // Другой способ — передать экземпляр com.aspose.imaging.Color напрямую.
    rasterImage.setPixel(0, 0, com.aspose.imaging.Color.getAqua());
} finally {
    image.dispose();
}
```

### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


Читает всю строку сканирования по указанному индексу строки сканирования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scanLineIndex | int | Нулевой индекс строки сканирования. |

**Returns:**
com.aspose.imaging.Color[] — массив значений цветов пикселей строки сканирования.
### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


Читает всю строку сканирования по указанному индексу строки сканирования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scanLineIndex | int | Нулевой индекс строки сканирования. |

**Returns:**
int[] — массив 32‑битных ARGB‑значений цветов строки сканирования.
### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.imaging.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


Записывает всю строку сканирования в указанный индекс строки сканирования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scanLineIndex | int | Нулевой индекс строки сканирования. |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | Массив цветов пикселей для записи. |

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


Записывает всю строку сканирования в указанный индекс строки сканирования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scanLineIndex | int | Нулевой индекс строки сканирования. |
| argb32Pixels | int[] | Массив 32‑битных ARGB‑цветов для записи. |

### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Частично загружает 32‑битные ARGB‑пиксели пакетами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Желаемый прямоугольник. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader) | Загрузчик 32‑битных ARGB‑пикселей. |


**Example: The following example shows how to load and process pixels of a raster image using your own partial processor.**
В следующем примере показано, как загружать и обрабатывать пиксели растрового изображения с использованием собственного частичного процессора. Например, рассмотрим задачу подсчёта полностью прозрачных пикселей изображения. Чтобы подсчитать прозрачные пиксели с помощью механизма частичной загрузки, вводится отдельный класс TransparentArgb32PixelCounter, реализующий com.aspose.imaging.IPartialArgb32PixelLoader.
``` java

// Сначала реализуйте com.aspose.imaging.IPartialArgb32PixelLoader, чтобы подсчитать все полностью прозрачные пиксели.
/** Counts the number of fully transparent pixels with alpha channel value of 0. */
class TransparentArgb32PixelCounter implements com.aspose.imaging.IPartialArgb32PixelLoader {
    /**
     * The number of fully transparent pixels.
     */
    private int count;

    /**
     * Gets the number of fully transparent pixels.
     */
    public int getCount() {
        return this.count;
    }

    /**
     * <p>Processes the loaded pixels. This method is called back every time when a new portion of pixels is loaded.</p>                 *
     *
     * @param pixelsRectangle The pixels rectangle.
     * @param pixels          The 32-bit ARGB pixels.
     * @param start           The start pixels point.
     * @param end             The end pixels point.
     */
    public void process(com.aspose.imaging.Rectangle pixelsRectangle, int[] pixels, com.aspose.imaging.Point start, com.aspose.imaging.Point end) {
        for (int pixel : pixels) {
            int alpha = (pixel >> 24) & 0xff;
            if (alpha == 0) {
                this.count++;
            }
        }
    }
}

// Вот пример использования счётчика.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Создайте экземпляр com.aspose.imaging.IPartialArgb32PixelLoader и передайте его в com.aspose.imaging.RasterImage.LoadPartialArgb32Pixels
    TransparentArgb32PixelCounter counter = new TransparentArgb32PixelCounter();

    // Загрузите пиксели для всего изображения. Любая прямоугольная часть изображения может быть указана в качестве первого параметра метода com.aspose.imaging.RasterImage.loadPartialArgb32Pixels.
    rasterImage.loadPartialArgb32Pixels(rasterImage.getBounds(), counter);

    System.out.println("The number of fully transparent pixels is " + counter.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// Вывод может выглядеть так:
// Количество полностью прозрачных пикселей равно 55157
// Общее количество пикселей равно 120400
```

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


Частично загружает пиксели пакетами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Желаемый прямоугольник. |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.imaging/ipartialpixelloader) | Загрузчик пикселей. |


**Example: The following example shows how to load and process pixels of a raster image using your own partial processor.**
Следующий пример показывает, как загрузить и обработать пиксели растрового изображения, используя ваш собственный частичный процессор. Например, рассмотрим задачу подсчёта полностью прозрачных пикселей изображения. Для подсчёта прозрачных пикселей с использованием механизма частичной загрузки вводится отдельный класс TransparentPixelCounter, реализующий com.aspose.imaging.IPartialPixelLoader.
``` java

// Сначала реализуйте com.aspose.imaging.IPartialPixelLoader, чтобы подсчитать все полностью прозрачные пиксели.
/** Counts the number of fully transparent pixels with alpha channel value of 0. */
class TransparentPixelCounter implements com.aspose.imaging.IPartialPixelLoader {
    /**
     * The number of fully transparent pixels.
     */
    private int count;

    /**
     * Gets the number of fully transparent pixels.
     */
    public int getCount() {
        return this.count;
    }

    /**
     * <p>Processes the loaded pixels. This method is called back every time when a new portion of pixels is loaded.</p>
     *
     * @param pixelsRectangle The pixels rectangle.
     * @param pixels          The 32-bit ARGB pixels.
     * @param start           The start pixels point.
     * @param end             The end pixels point.
     */
    public void process(com.aspose.imaging.Rectangle pixelsRectangle, com.aspose.imaging.Color[] pixels, com.aspose.imaging.Point start, com.aspose.imaging.Point end) {
        for (com.aspose.imaging.Color pixel : pixels) {
            if (pixel.getA() == 0) {
                this.count++;
            }
        }
    }
}

// Вот пример использования счётчика.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Создайте экземпляр com.aspose.imaging.IPartialPixelLoader и передайте его в com.aspose.imaging.RasterImage.loadPartialPixels
    TransparentPixelCounter counter = new TransparentPixelCounter();

    // Загрузите пиксели для всего изображения. Любая прямоугольная часть изображения может быть указана в качестве первого параметра метода com.aspose.imaging.RasterImage.loadPartialPixels.
    rasterImage.loadPartialPixels(rasterImage.getBounds(), counter);

    System.out.println("The number of fully transparent pixels is " + counter.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// Вывод может выглядеть так:
// Количество полностью прозрачных пикселей равно 55157
// Общее количество пикселей равно 120400
```

### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


Загружает 32‑битные ARGB‑пиксели.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник, из которого загружаются пиксели. |

**Returns:**
int[] — массив загруженных 32‑битных ARGB пикселей.

**Example: The following example shows how to load and process pixels of a raster image.**
Следующий пример показывает, как загрузить и обработать пиксели растрового изображения. Пиксели представлены 32‑битными целочисленными значениями. Например, рассмотрим задачу подсчёта полностью прозрачных пикселей изображения.
``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Загрузите пиксели для всего изображения. Любая прямоугольная часть изображения может быть указана в качестве параметра метода com.aspose.imaging.RasterImage.loadArgb32Pixels.
    int[] pixels = rasterImage.loadArgb32Pixels(rasterImage.getBounds());

    int count = 0;
    for (int pixel : pixels) {
        int alpha = (pixel >> 24) & 0xff;
        if (alpha == 0) {
            count++;
        }
    }

    System.out.println("The number of fully transparent pixels is " + count);
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}
```

### loadArgb64Pixels(Rectangle rectangle) {#loadArgb64Pixels-com.aspose.imaging.Rectangle-}
```
public long[] loadArgb64Pixels(Rectangle rectangle)
```


Загружает 64‑битные ARGB‑пиксели.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник, из которого загружаются пиксели. |

**Returns:**
long[] — массив загруженных 64‑битных ARGB пикселей.

**Example: The following example shows how to load and process pixels of a raster image.**
Следующий пример показывает, как загрузить и обработать пиксели растрового изображения. Пиксели представлены 64‑битными целочисленными значениями. Например, рассмотрим задачу подсчёта полностью прозрачных пикселей изображения.
``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\16rgba.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Загрузите пиксели для всего изображения. Любая прямоугольная часть изображения может быть указана в качестве параметра метода com.aspose.imaging.RasterImage.loadArgb64Pixels.
    // Обратите внимание, что само изображение должно иметь 16 бит на образец, поскольку com.aspose.imaging.RasterImage.loadArgb64Pixels не работает с 8‑битными образцами.
    // Чтобы работать с 8‑битными образцами, пожалуйста, используйте проверенный метод com.aspose.imaging.RasterImage.loadArgb32Pixels.
    long[] pixels = rasterImage.loadArgb64Pixels(rasterImage.getBounds());

    int count = 0;
    for (long pixel : pixels) {
        // Обратите внимание, что все цветовые компоненты, включая альфа, представлены 16‑битными значениями, поэтому их допустимый диапазон — [0, 63535].
        long alpha = (pixel >> 48) & 0xffff;
        if (alpha == 0) {
            count++;
        }
    }

    System.out.println("The number of fully transparent pixels is " + count);
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}
```

### loadPartialArgb64Pixels(Rectangle rectangle, IPartialArgb64PixelLoader partialPixelLoader) {#loadPartialArgb64Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb64PixelLoader-}
```
public final void loadPartialArgb64Pixels(Rectangle rectangle, IPartialArgb64PixelLoader partialPixelLoader)
```


Частично загружает 64‑битные ARGB‑пиксели пакетами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Желаемый прямоугольник. |
| partialPixelLoader | [IPartialArgb64PixelLoader](../../com.aspose.imaging/ipartialargb64pixelloader) | 64‑битный загрузчик ARGB пикселей. |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.imaging.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


Загружает пиксели.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник, из которого загружаются пиксели. |

**Returns:**
com.aspose.imaging.Color[] — массив загруженных пикселей.

**Example: The following example shows how to load and process pixels of a raster image.**
Следующий пример показывает, как загрузить и обработать пиксели растрового изображения. Например, рассмотрим задачу подсчёта полностью прозрачных пикселей изображения.
``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Загрузите пиксели для всего изображения. Любая прямоугольная часть изображения может быть указана в качестве параметра метода Aspose.Imaging.RasterImage.LoadPixels.
    com.aspose.imaging.Color[] pixels = rasterImage.loadPixels(rasterImage.getBounds());

    int count = 0;
    for (com.aspose.imaging.Color pixel : pixels) {
        if (pixel.getA() == 0) {
            count++;
        }
    }

    System.out.println("The number of fully transparent pixels is " + count);
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}
```

### loadCmykPixels(Rectangle rectangle) {#loadCmykPixels-com.aspose.imaging.Rectangle-}
```
public CmykColor[] loadCmykPixels(Rectangle rectangle)
```


Загружает пиксели в формате CMYK. Этот метод устарел. Пожалуйста, используйте более эффективный метод `loadCmyk32Pixels(Rectangle)`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник, из которого загружаются пиксели. |

**Returns:**
com.aspose.imaging.CmykColor[] - Загруженный массив пикселей CMYK.
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


Загружает пиксели в формате CMYK.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник, из которого загружаются пиксели. |

**Returns:**
int[] - Загруженные пиксели CMYK представлены в виде 32‑битных целочисленных значений.
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Загружает необработанные данные изображения, используя механизм частичной обработки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Желаемая прямоугольная область изображения, из которой загружать данные. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Настройки необработанных данных. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | Загрузчик необработанных данных. |


**Example: The following example shows how to extract pixels from the raw image data using RawDataSettings.**
В следующем примере показано, как извлекать пиксели из необработанных данных изображения с помощью RawDataSettings. Например, рассмотрим задачу подсчёта полностью прозрачных пикселей изображения.
``` java

// Сначала реализуйте счётчик. В случае необработанных данных счётчик может выглядеть так:
/** Counts the number of fully transparent pixels with alpha channel value of 0. */
class TransparentPixelRawDataCounter implements com.aspose.imaging.IPartialRawDataLoader {
    /**
     * The number of fully transparent pixels.
     */
    private int count;

    /**
     * The raw data settings of the loaded image.
     */
    private com.aspose.imaging.RawDataSettings rawDataSettings;

    /**
     * Gets the number of fully transparent pixels.
     */
    public int getCount() {
        return this.count;
    }

    /**
     * <p>Initializes a new instance of the <see TransparentPixelRawDataCounter /> class.</p>
     *
     * @param settings The raw data settings allow to extract color components from raw data.
     */
    public TransparentPixelRawDataCounter(com.aspose.imaging.RawDataSettings settings) {
        this.rawDataSettings = settings;
        this.count = 0;
    }

    /**
     * <p>Processes the loaded raw data. This method is called back every time when a new portion of raw data is loaded.</p>
     *
     * @param dataRectangle The raw data rectangle.
     * @param data          The raw data.
     * @param start         The start data point.
     * @param end           The end data point.
     */
    public void process(com.aspose.imaging.Rectangle dataRectangle, byte[] data, com.aspose.imaging.Point start, com.aspose.imaging.Point end)// throws java.lang.Exception
    {
        int[] channelBits = this.rawDataSettings.getPixelDataFormat().getChannelBits();

        // Здесь рассматриваются только простые форматы, чтобы упростить код.
        // Рассмотрим только изображения с 8 битами на образец.
        for (int i = 0; i < channelBits.length; i++) {
            if (channelBits[i] != 8) {
                throw new java.lang.UnsupportedOperationException();
            }
        }

        switch (this.rawDataSettings.getPixelDataFormat().getPixelFormat()) {
            case com.aspose.imaging.PixelFormat.Rgb:
            case com.aspose.imaging.PixelFormat.Bgr: {
                if (channelBits.length == 4) {
                    // ARGB
                    for (int i = 0; i < data.length; i += 4) {
                        // Канал альфа хранится последним, после цветовых компонентов.
                        if (data[i + 3] == 0) {
                            this.count++;
                        }
                    }
                }
            }
            break;

            case com.aspose.imaging.PixelFormat.Grayscale: {
                if (channelBits.length == 2) {
                    // Оттенки серого с альфа-каналом
                    for (int i = 0; i < data.length; i += 2) {
                        // Канал альфа хранится последним, после цветовых компонентов.
                        if (data[i + 1] == 0) {
                            this.count++;
                        }
                    }
                }
            }
            break;

            default:
                throw new java.lang.IllegalArgumentException("PixelFormat");
        }
    }

    /**
     * <p>Processes the loaded raw data. This method is called back every time when a new portion of raw data is loaded.</p>                 *
     *
     * @param dataRectangle The raw data rectangle.
     * @param data          The raw data.
     * @param start         The start data point.
     * @param end           The end data point.
     * @param loadOptions   The load options.
     */
    public void process(com.aspose.imaging.Rectangle dataRectangle, byte[] data, com.aspose.imaging.Point start, com.aspose.imaging.Point end, com.aspose.imaging.LoadOptions loadOptions) {
        this.process(dataRectangle, data, start, end);
    }
}

// Вот основной пример использования счётчика
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
    com.aspose.imaging.RawDataSettings settings = rasterImage.getRawDataSettings();

    TransparentPixelRawDataCounter rawDataLoader = new TransparentPixelRawDataCounter(settings);

    // Загрузите пиксели для всего изображения. Любую прямоугольную часть изображения можно указать в качестве параметра метода Aspose.Imaging.RasterImage.LoadRawData.
    rasterImage.loadRawData(rasterImage.getBounds(), settings, rawDataLoader);

    System.out.println("The number of fully transparent pixels is " + rawDataLoader.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// Вывод может выглядеть так:
// Количество полностью прозрачных пикселей равно 55157
// Общее количество пикселей равно 120400
```

### loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Загружает необработанные данные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник, из которого загружать необработанные данные. |
| dstImageBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Границы целевого изображения. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Настройки необработанных данных, используемые для загруженных данных. Обратите внимание, что если данные не в указанном формате, будет выполнено их преобразование. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | Загрузчик необработанных данных. |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


Сохраняет необработанные данные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Необработанные данные. |
| Начальное смещение необработанных данных dataOffset. | int | Начальное смещение необработанных данных. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник необработанных данных. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Настройки необработанных данных, в которых находятся данные. |

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.imaging.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


Сохраняет 32‑битные ARGB‑пиксели.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник, в который сохранять пиксели. |
| пиксели | int[] | 32‑битный массив пикселей ARGB. |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
В следующем примере центральная область растрового изображения заполняется чёрными пикселями с помощью метода com.aspose.imaging.RasterImage.saveArgb32Pixels.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Черный квадрат
    int[] pixels = new int[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getBlack().toArgb();
    }

    // Нарисуйте черный квадрат в центре изображения.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(rasterImage.getWidth() / 4, rasterImage.getHeight() / 4, rasterImage.getWidth() / 2, rasterImage.getHeight() / 2);
    rasterImage.saveArgb32Pixels(area, pixels);

    rasterImage.save(dir + "sample.SaveArgb32Pixels.png");
} finally {
    image.dispose();
}
```

### savePixels(Rectangle rectangle, Color[] pixels) {#savePixels-com.aspose.imaging.Rectangle-com.aspose.imaging.Color---}
```
public void savePixels(Rectangle rectangle, Color[] pixels)
```


Сохраняет пиксели.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник, в который сохранять пиксели. |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | Массив пикселей. |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
В следующем примере центральная область растрового изображения заполняется черными пикселями с использованием метода com.aspose.imaging.RasterImage.savePixels.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Черный квадрат
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getBlack();
    }

    // Нарисуйте черный квадрат в центре изображения.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(rasterImage.getWidth() / 4, rasterImage.getHeight() / 4, rasterImage.getWidth() / 2, rasterImage.getHeight() / 2);
    rasterImage.savePixels(area, pixels);

    rasterImage.save(dir + "sample.SavePixels.png");
} finally {
    image.dispose();
}
```

### toBitmap() {#toBitmap--}
```
public BufferedImage toBitmap()
```


Преобразует растровое изображение в bitmap.

**Returns:**
java.awt.image.BufferedImage - Битмап

**Example: The following example converts a BMP image to a native Java bitmap.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;
    java.awt.image.BufferedImage bitmap = bmpImage.toBitmap();

    // Обработайте нативный битмап Java.
} finally {
    image.dispose();
}
```

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


Сохраняет пиксели. Этот метод устарел. Пожалуйста, используйте более эффективный метод `saveCmyk32Pixels(Rectangle, int[])`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник, в который сохранять пиксели. |
| pixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | Массив CMYK‑пикселей. |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.imaging.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


Сохраняет пиксели.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник, в который сохранять пиксели. |
| пиксели | int[] | CMYK‑пиксели представлены в виде 32‑битных целочисленных значений. |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
В следующем примере центральная область растрового изображения заполняется черными пикселями с использованием метода com.aspose.imaging.RasterImage.saveCmyk32Pixels.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Получите целочисленное представление черного цвета в цветовом пространстве CMYK.
    int blackCmyk = com.aspose.imaging.CmykColorHelper.toCmyk(com.aspose.imaging.Color.getBlack());

    // Черный квадрат.
    int[] pixels = new int[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = blackCmyk;
    }

    // Нарисуйте черный квадрат в центре изображения.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(rasterImage.getWidth() / 4, rasterImage.getHeight() / 4, rasterImage.getWidth() / 2, rasterImage.getHeight() / 2);
    rasterImage.saveCmyk32Pixels(area, pixels);

    rasterImage.save(dir + "sample.SaveCmyk32Pixels.png");
} finally {
    image.dispose();
}
```

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Устанавливает разрешение для этого `RasterImage`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dpiX | double | Горизонтальное разрешение, в точках на дюйм, `RasterImage`. |
| dpiY | double | Вертикальное разрешение, в точках на дюйм, `RasterImage`. |


**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Получить горизонтальное и вертикальное разрешение изображения
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Используйте метод SetResolution для обновления обоих значений разрешения одним вызовом.
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // Вывод может выглядеть так:
    // Горизонтальное разрешение, в пикселях на дюйм: 300.0
    // Вертикальное разрешение, в пикселях на дюйм: 300.0
    // Установить значения разрешения в 96 dpi
    // Горизонтальное разрешение, в пикселях на дюйм: 96.0
    // Вертикальное разрешение, в пикселях на дюйм: 96.0
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Устанавливает палитру изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Палитра для установки. |
| updateColors | boolean | Если установить значение `true`, цвета будут обновлены в соответствии с новой палитрой; в противном случае индексы цветов останутся неизменными. Обратите внимание, что неизменные индексы могут привести к сбою изображения при загрузке, если некоторые индексы не имеют соответствующих записей в палитре. |

### autoRotate() {#autoRotate--}
```
public final void autoRotate()
```


Автоматически вращает изображение на основе данных ориентации, извлечённых из метаданных Exif. Этот метод гарантирует правильное отображение изображений, улучшая пользовательский опыт и устраняя необходимость ручных корректировок. Анализируя информацию Exif, изображение поворачивается соответствующим образом, обеспечивая бесшовный просмотр на разных платформах и устройствах. Такой автоматический процесс вращения упрощает работу с изображениями и повышает общую удобство использования, особенно при работе с большими партиями изображений с различными ориентациями.

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Изменяет размер изображения с расширенными параметрами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Настройки изменения размера. |

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

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Поворачивает изображение вокруг центра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения в градусах. Положительные значения вращают по часовой стрелке. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Бинаризация изображения с предопределённым порогом

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | byte | Значение порога. Если соответствующее серое значение пикселя больше порога, ему будет присвоено значение 255, иначе — 0. |


**Example: The following example binarizes a raster image with the predefined threshold.**
В следующем примере растровое изображение бинаризуется с использованием предопределённого порога. Бинаризованные изображения содержат только 2 цвета — чёрный и белый.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

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


**Example: The following example binarizes a raster image with Otsu thresholding.**
В следующем примере растровое изображение бинаризуется с помощью пороговой обработки Оцу. Бинаризованные изображения содержат только 2 цвета — чёрный и белый.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Бинаризуйте изображение с пороговой обработкой Оцу.
    rasterImage.binarizeOtsu();
    rasterImage.save(dir + "sample.BinarizeOtsu.png");
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


**Example: The following example binarizes a raster image with Bradley's adaptive thresholding algorithm with the specified window size.**
В следующем примере растровое изображение бинаризуется с использованием адаптивного порогового алгоритма Брэдли с указанным размером окна. Бинаризованные изображения содержат только 2 цвета — чёрный и белый.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Бинаризуйте изображение с разницей яркости 5. Яркость определяется как разница между пикселем и средним значением 10 × 10 окна пикселей, центрированного вокруг этого пикселя.
    rasterImage.binarizeBradley(5, 10);
    rasterImage.save(dir + "sample.BinarizeBradley5_10x10.png");
} finally {
    image.dispose();
}
```

### blend(Point origin, RasterImage overlay, Rectangle overlayArea) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-}
```
public final void blend(Point origin, RasterImage overlay, Rectangle overlayArea)
```


Смешивает данный экземпляр изображения с изображением `overlay`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | Исходная точка смешения фонового изображения. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | Наложенное изображение. |
| overlayArea | [Rectangle](../../com.aspose.imaging/rectangle) | Область наложения. |

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

### blend(Point origin, RasterImage overlay) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-}
```
public final void blend(Point origin, RasterImage overlay)
```


Смешивает этот экземпляр изображения с `overlay` при альфа == 255.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | Исходная точка смешения фонового изображения. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | Наложение. |

### blend(Point origin, RasterImage overlay, byte overlayAlpha) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-byte-}
```
public final void blend(Point origin, RasterImage overlay, byte overlayAlpha)
```


Смешивает этот экземпляр изображения с `overlay`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | Исходная точка смешения фонового изображения. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | Наложение. |
| overlayAlpha | byte | Прозрачность наложения. |

### grayscale() {#grayscale--}
```
public void grayscale()
```


Преобразование изображения в его градации серого


**Example: The following example transforms a colored raster image to its grayscale representation.**
В следующем примере цветное растровое изображение преобразуется в градацию серого. Изображения в градациях серого состоят исключительно из оттенков серого и содержат только информацию о интенсивности.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

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


Автоматическая адаптивная нормализация яркости и контраста для всего изображения.

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Регулировка яркости изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightness | int | Значение яркости. |


**Example: The following example performs brightness correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

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


**Example: The following example performs contrast correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Установите значение контрастности. Допустимые значения контрастности находятся в диапазоне [-100f, 100f].
    rasterImage.adjustContrast(50);
    rasterImage.save(dir + "sample.AdjustContrast.png");
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
### isDigitalSigned(String password) {#isDigitalSigned-java.lang.String-}
```
public boolean isDigitalSigned(String password)
```


Выполняет быструю проверку, определяющую, подписано ли изображение цифровой подписью, используя предоставленный пароль и порог.

--------------------

Этот метод обеспечивает самое быстрое обнаружение, используя `GetSignPercentage`. Как только извлечённые данные достигают указанного порога, дальнейшие шаги извлечения, направленные на повышение точности обнаружения, пропускаются.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| пароль | java.lang.String | Пароль для проверки подписи. |

**Returns:**
boolean - True, если изображение подписано, иначе false.
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


**Example: The following example performs gamma-correction of an image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

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


**Example: The following example performs gamma-correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Установите коэффициент гаммы для красного, зелёного и синего каналов.
    rasterImage.adjustGamma(2.5f);
    rasterImage.save(dir + "sample.AdjustGamma.png");
} finally {
    image.dispose();
}
```

### getSkewAngle() {#getSkewAngle--}
```
public final float getSkewAngle()
```


Получает угол наклона. Этот метод применим к отсканированным текстовым документам для определения угла наклона при сканировании.

**Returns:**
float — угол наклона в градусах.
### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


Нормализует угол. Этот метод применим к отсканированным текстовым документам, чтобы избавиться от искажённого сканирования. Этот метод использует \#getSkewAngle.getSkewAngle и методы [Image.rotate(float)](../../com.aspose.imaging/image\#rotate-float-).

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Нормализует угол. Этот метод применим к отсканированным текстовым документам, чтобы избавиться от искажённого сканирования. Этот метод использует \#getSkewAngle.getSkewAngle и методы \#rotate(float, boolean, Color).rotate(float, boolean, Color).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| resizeProportionally | boolean | Если установить `true`, размер вашего изображения будет изменён в соответствии с проекциями вращённого прямоугольника (угловых точек); в противном случае размеры останутся неизменными, и будет вращено только внутреннее содержимое изображения. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Цвет фона. |


**Example: Skew is an artifact that might appear during document scanning process when the text/images of the document get rotated at a slight angle.**
Искажение (skew) — это артефакт, который может появиться во время процесса сканирования документа, когда текст/изображения документа поворачиваются под небольшим углом. Это может иметь различные причины, но самая распространённая — смещение листа во время сканирования. Поэтому дескейв (deskew) — это процесс обнаружения и исправления этой проблемы в отсканированных файлах (т.е. bitmap), так что дескейв‑документы будут иметь текст/изображения, правильно и горизонтально выровненные.
``` java
String dir = "c:\\aspose.imaging\\issues\\java\\1461\\";

String inputFilePath = dir + "skewed.png";
String outputFilePath = dir + "skewed.out.png";

// Избавьтесь от искажённого сканирования с параметрами по умолчанию
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(inputFilePath);
try {
    // Дескейв
    image.normalizeAngle(false /*do not resize*/, com.aspose.imaging.Color.getLightGray() /*background color*/);
    image.save(outputFilePath);
} finally {
    image.close();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Фильтрует указанный прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Параметры. |


**Example: The following example applies various types of filters to a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Примените медианный фильтр с размером прямоугольника 5 ко всему изображению.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    rasterImage.save(dir + "sample.MedianFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Примените билатеральный сглаживающий фильтр с размером ядра 5 ко всему изображению.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    rasterImage.save(dir + "sample.BilateralSmoothingFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Примените гауссов фильтр размытия с радиусом 5 и значением sigma 4.0 ко всему изображению.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussianBlurFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Примените фильтр Гаусса-Винера с радиусом 5 и значением smooth 4.0 ко всему изображению.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Примените фильтр движения Винера с длиной 5, значением smooth 4.0 и углом 90,0 градусов ко всему изображению.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.save(dir + "sample.MotionWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Примените фильтр резкости с размером ядра 5 и значением sigma 4.0 ко всему изображению.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.SharpenFilter.png");
} finally {
    image.dispose();
}
```

### replaceColor(Color oldColor, byte oldColorDiff, Color newColor) {#replaceColor-com.aspose.imaging.Color-byte-com.aspose.imaging.Color-}
```
public void replaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```


Заменяет один цвет другим с допустимой разницей и сохраняет исходное альфа-значение, чтобы сохранить плавные края.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.imaging/color) | Старый цвет, который будет заменён. |
| oldColorDiff | byte | Допустимая разница в старом цвете, позволяющая расширить заменённый тон цвета. |
| newColor | [Color](../../com.aspose.imaging/color) | Новый цвет, которым заменяется старый цвет. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Заменяет один цвет другим с допустимой разницей и сохраняет исходное альфа-значение, чтобы сохранить плавные края.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| oldColorArgb | int | Значение ARGB старого цвета, которое будет заменено. |
| oldColorDiff | byte | Допустимая разница в старом цвете, позволяющая расширить заменённый тон цвета. |
| newColorArgb | int | Значение ARGB нового цвета, которым заменяется старый цвет. |

### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.imaging.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа, чтобы сохранить плавные края. Примечание: если использовать её на изображениях без прозрачности, все цвета будут заменены одним цветом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.imaging/color) | Новый цвет, которым заменяются непрозрачные цвета. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа, чтобы сохранить плавные края. Примечание: если использовать её на изображениях без прозрачности, все цвета будут заменены одним цветом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorArgb | int | Значение ARGB нового цвета, которым заменяются непрозрачные цвета. |

