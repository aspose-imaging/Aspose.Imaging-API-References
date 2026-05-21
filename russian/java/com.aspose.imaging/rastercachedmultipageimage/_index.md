---
title: "RasterCachedMultipageImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Растровое многостраничное изображение"
type: docs
weight: 90
url: /ru/java/com.aspose.imaging/rastercachedmultipageimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImage](../../com.aspose.imaging/imultipageimage)
```
public abstract class RasterCachedMultipageImage extends RasterCachedImage implements IMultipageImage
```

Растровое многостраничное изображение
## Методы

| Метод | Описание |
| --- | --- |
| [getHeight()](#getHeight--) | Получает высоту изображения. |
| [getWidth()](#getWidth--) | Получает ширину изображения. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получает количество бит на пиксель изображения. |
| [isCached()](#isCached--) | Возвращает значение, указывающее, кэшированы ли данные изображения в данный момент. |
| [hasAlpha()](#hasAlpha--) | Получает значение, указывающее, имеет ли этот экземпляр альфа‑канал. |
| [hasTransparentColor()](#hasTransparentColor--) | Получает значение, указывающее, имеет ли изображение прозрачный цвет. |
| [getImageOpacity()](#getImageOpacity--) | Получает непрозрачность этого изображения. |
| [getBackgroundColor()](#getBackgroundColor--) | Получает значение фонового цвета. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Устанавливает значение фонового цвета. |
| [getMetadata()](#getMetadata--) | Получает данные XMP из кадра. |
| [getPageExportingAction()](#getPageExportingAction--) | Получает действие экспорта страницы. |
| [setPageExportingAction(PageExportingAction value)](#setPageExportingAction-com.aspose.imaging.PageExportingAction-) | Устанавливает действие экспорта страницы. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Регулировка `brightness` изображения. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | [Image](../../com.aspose.imaging/image) контрастирование |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Гамма‑коррекция изображения. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Гамма‑коррекция изображения. |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | Смешивает данный экземпляр изображения с изображением `overlay`. |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | Встраивает цифровую подпись, основанную на предоставленном пароле, в каждую страницу изображения. |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | Вычисляет процентное сходство между извлечёнными данными и оригинальным паролем. |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | Выполняет быструю проверку, определяющую, подписано ли изображение цифровой подписью, используя предоставленный пароль и порог. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Бинаризация изображения с предопределённым порогом |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном изображении |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном изображении |
| [binarizeOtsu()](#binarizeOtsu--) | Бинаризация изображения с порогом Оцу |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Обрезка изображения. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Обрезает изображение со сдвигами. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Выполняет дизеринг текущего изображения. |
| [grayscale()](#grayscale--) | Преобразование изображения в его градации серого |
| [normalizeHistogram()](#normalizeHistogram--) | Нормализует гистограмму изображения \\u2014 корректирует значения пикселей, чтобы использовать весь доступный диапазон. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | `RasterCachedMultipageImage.rotate` изображение вокруг центра. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Поворачивает, отражает или одновременно поворачивает и отражает все страницы. |
| [rotateFlipAll(int rotateFlip)](#rotateFlipAll-int-) | Поворачивает и отражает все. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Изменяет размер изображения. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Изменяет размер изображения. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Изменяет ширину пропорционально. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Изменяет ширину пропорционально. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное альфа-значение, чтобы сохранить плавные края. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное альфа-значение, чтобы сохранить плавные края. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Фильтрует указанный прямоугольник. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | Нормализует угол. |
| [cacheData()](#cacheData--) | Кеширует данные приватно. |

## Example: The following example shows batch conversion before saving (exporting) Tiff images.

``` java
String fileName = "10MB_Tif.tif";
String inputFileName = fileName;

String outputFileNameTif = "output.tif";

//Реализована возможность пакетного преобразования перед сохранением (экспортом) TIFF‑изображений.

try(com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(inputFileName))
{
    // Установить пакетную операцию для страниц
    tiffImage.setPageExportingAction(new PageExportingAction()
    {
        @Override
        public void invoke(int pageIndex, Image page)
        {
            // Запускает сборку мусора, чтобы избежать ненужного накопления мусора от предыдущих страниц.
            System.gc();

            ((com.aspose.imaging.RasterImage) page).rotate(90);
        }
    });

    tiffImage.save(outputFileNameTif);

    /* Attention! In batch mode all pages will be released in this line!
     If you want to further perform operations on the original image, you should reload it from the source to another instance. */
}
```

### getHeight() {#getHeight--}
```
public int getHeight()
```


Получает высоту изображения.

Значение: высота изображения.

**Returns:**
int — высота изображения.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает ширину изображения.

Значение: ширина изображения.

**Returns:**
int — ширина изображения.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Получает количество бит на пиксель изображения.

Значение: количество бит на пиксель изображения.

**Returns:**
int — количество бит на пиксель изображения.
### isCached() {#isCached--}
```
public boolean isCached()
```


Возвращает значение, указывающее, кэшированы ли данные изображения в данный момент.

Значение: `true`, если данные изображения кешированы; иначе `false`.

**Returns:**
boolean — значение, указывающее, кешированы ли в данный момент данные изображения.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Получает значение, указывающее, имеет ли этот экземпляр альфа‑канал.

Значение: `true`, если у этого экземпляра есть альфа‑канал; иначе `false`.

**Returns:**
boolean — значение, указывающее, есть ли у этого экземпляра альфа‑канал.
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Получает значение, указывающее, имеет ли изображение прозрачный цвет.

--------------------

Эта реализация проверяет значение `RasterImage.HasTransparentColor`([RasterImage.hasTransparentColor](../../com.aspose.imaging/rasterimage\#hasTransparentColor)/[RasterImage.setTransparentColor(boolean)](../../com.aspose.imaging/rasterimage\#setTransparentColor-boolean-)) свойства `DefaultPage`(\#getDefaultPage\_internalized.getDefaultPage\_internalized).

**Returns:**
boolean — значение, указывающее, имеет ли изображение прозрачный цвет.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Получает непрозрачность этого изображения.

Значение: значение непрозрачности от 0.0 (полностью прозрачное) до 1.0 (полностью непрозрачное).

**Returns:**
float - непрозрачность этого изображения.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Получает значение фонового цвета.

**Returns:**
[Color](../../com.aspose.imaging/color) - a value for the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Устанавливает значение фонового цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | значение для цвета фона. |

### getMetadata() {#getMetadata--}
```
public ImageMetadata getMetadata()
```


Получает данные XMP из кадра.

Значение: обёртка данных пакета XMP

**Returns:**
[ImageMetadata](../../com.aspose.imaging.metadata/imagemetadata) - XMP data from frame.
### getPageExportingAction() {#getPageExportingAction--}
```
public PageExportingAction getPageExportingAction()
```


Получает действие экспорта страницы. Обратите внимание, что установка этого метода автоматически освободит ресурсы страницы после его выполнения. Он будет выполнен непосредственно перед сохранением каждой страницы.

Значение: действие экспорта страницы.

**Returns:**
[PageExportingAction](../../com.aspose.imaging/pageexportingaction) - the page exporting action.
### setPageExportingAction(PageExportingAction value) {#setPageExportingAction-com.aspose.imaging.PageExportingAction-}
```
public void setPageExportingAction(PageExportingAction value)
```


Устанавливает действие экспорта страницы. Обратите внимание, что установка этого метода автоматически освободит ресурсы страницы после его выполнения. Он будет выполнен непосредственно перед сохранением каждой страницы.

Значение: действие экспорта страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PageExportingAction](../../com.aspose.imaging/pageexportingaction) | действие экспорта страницы. |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Регулировка `brightness` изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightness | int | Значение яркости. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


[Image](../../com.aspose.imaging/image) contrasting

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| contrast | float | Значение контрастности (в диапазоне [-100; 100]) |

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

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Гамма‑коррекция изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| гамма | float | Коэффициент гаммы для красного, зелёного и синего каналов |

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

### embedDigitalSignature(String password) {#embedDigitalSignature-java.lang.String-}
```
public void embedDigitalSignature(String password)
```


Встраивает цифровую подпись, основанную на предоставленном пароле, в каждую страницу изображения.

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

--------------------

Из‑за многостраничных изображений результат представляет рассчитанный `MIDDLE AVERAGED signing percentage`

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

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| пароль | java.lang.String | Пароль для проверки подписи. |
|  | percentageThreshold | int | Порог (в процентах)[0-100], определяющий, считается ли изображение подписанным. Если не указано, будет применён порог по умолчанию (`75`). |

--------------------

Этот метод обеспечивает самое быстрое обнаружение, используя `GetSignPercentage`. Как только извлечённые данные достигают указанного порога, дальнейшие шаги извлечения, направленные на повышение точности обнаружения, пропускаются.

Результат будет `true` только если все страницы многостраничного изображения распознаны как подписанные; в противном случае изображение считается неподписанным. |

**Returns:**
boolean - True, если изображение подписано, иначе false.
### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Бинаризация изображения с предопределённым порогом

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | byte | Значение порога. Если соответствующее серое значение пикселя больше порога, ему будет присвоено значение 255, иначе — 0. |

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

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном изображении

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightnessDifference | double | Разница яркости между пикселем и средним значением окна s × s пикселей, центрированного вокруг этого пикселя. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Бинаризация изображения с порогом Оцу

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Обрезка изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Обрезает изображение со сдвигами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| leftShift | int | Левый сдвиг. |
| rightShift | int | Правый сдвиг. |
| topShift | int | Верхний сдвиг. |
| bottomShift | int | Нижний сдвиг. |

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

### normalizeHistogram() {#normalizeHistogram--}
```
public void normalizeHistogram()
```


Нормализует гистограмму изображения \\u2014 корректирует значения пикселей, чтобы использовать весь доступный диапазон.

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


`RasterCachedMultipageImage.rotate` изображение вокруг центра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения в градусах. Положительные значения вращают по часовой стрелке. |
| resizeProportionally | boolean | если установить `true`, размер вашего изображения будет изменён в соответствии с проекциями повернутого прямоугольника (угловых точек); в противном случае размеры останутся неизменными, и будет вращено только `` содержимое изображения. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Цвет фона. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Поворачивает, отражает или одновременно поворачивает и отражает все страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rotateFlipType | int | Тип вращения и отражения. |

### rotateFlipAll(int rotateFlip) {#rotateFlipAll-int-}
```
public void rotateFlipAll(int rotateFlip)
```


Поворачивает и отражает все.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rotateFlip | int | Поворот и отражение. |

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

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Изменяет ширину пропорционально.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| resizeType | int | Тип масштабирования. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Изменяет ширину пропорционально.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newHeight | int | Новая высота. |
| resizeType | int | Тип масштабирования. |

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

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа, чтобы сохранить плавные края. Примечание: если использовать её на изображениях без прозрачности, все цвета будут заменены одним цветом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorArgb | int | Значение ARGB нового цвета, которым заменяются непрозрачные цвета. |

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

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Нормализует угол. Этот метод применим к отсканированным текстовым документам для устранения искажённого сканирования. Этот метод использует методы [RasterImage.getSkewAngle](../../com.aspose.imaging/rasterimage\#getSkewAngle) и [RasterImage.rotate(float, boolean, Color)](../../com.aspose.imaging/rasterimage\#rotate-float--boolean--Color-).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| resizeProportionally | boolean | Если установить `true`, размер вашего изображения будет изменён в соответствии с проекциями вращённого прямоугольника (угловых точек); в противном случае размеры останутся неизменными, и будет вращено только внутреннее содержимое изображения. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Цвет фона. |

### cacheData() {#cacheData--}
```
public void cacheData()
```


Кеширует данные приватно.

