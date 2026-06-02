---
title: "GifImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "API формата графического обмена GIF предоставляет разработчикам универсальные инструменты для обработки сжатых растровых изображений и анимированных GIF."
type: docs
weight: 13
url: /ru/java/com.aspose.imaging.fileformats.gif/gifimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), com.aspose.fileformats.core.interfaces.IInterlaced
```
public final class GifImage extends RasterCachedMultipageImage implements IMultipageImageExt, IInterlaced
```

API формата графического обмена (GIF) предоставляет разработчикам универсальные инструменты для обработки сжатых растровых изображений и анимированных GIF. Предлагает такие возможности, как работа с метаданными XMP, настройка цветовой палитры, управление фоновым и прозрачным цветом, настройка непрозрачности, изменение размера, обрезка, применение фильтров, коррекция гаммы, регулировка контрастности, преобразование в градации серого и конвертация в другие форматы. Этот API обеспечивает бесшовную манипуляцию и улучшение GIF‑изображений для широкого спектра приложений.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-) | Создайте новый объект [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) с указанными параметрами для первого кадра и глобальной палитры. |
| [GifImage(GifFrameBlock firstFrame)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-) | Создание GIF‑изображений становится простым с конструктором [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage). |
| [GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-boolean-byte-byte-byte-boolean-) | Начните без усилий с конструктором [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage). |
## Методы

| Метод | Описание |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Получите формат файла без усилий с помощью этого свойства. |
| [hasTrailer()](#hasTrailer--) | Управляйте наличием трейлера в ваших GIF‑файлах с помощью этого свойства. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Управляйте наличием трейлера в ваших GIF‑файлах с помощью этого свойства. |
| [isPaletteSorted()](#isPaletteSorted--) | Контролируйте сортировку палитры в ваших GIF‑изображениях, используя это свойство. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Контролируйте сортировку палитры в ваших GIF‑изображениях, используя это свойство. |
| [getLoopsCount()](#getLoopsCount--) | Получайте количество повторов без усилий с помощью этого свойства. |
| [setLoopsCount(int value)](#setLoopsCount-int-) | Получайте количество повторов без усилий с помощью этого свойства. |
| [getPaletteColorResolutionBits()](#getPaletteColorResolutionBits--) | Управляйте разрешением цветов палитры ваших GIF‑изображений с помощью этого свойства. |
| [setPaletteColorResolutionBits(byte value)](#setPaletteColorResolutionBits-byte-) | Управляйте разрешением цветов палитры ваших GIF‑изображений с помощью этого свойства. |
| [getPageCount()](#getPageCount--) | Получайте общее количество страниц, содержащихся в изображении, с помощью этого простого свойства. |
| [getPages()](#getPages--) | Получайте доступ к страницам изображения через это удобное свойство, позволяющее беспрепятственно перемещаться и манипулировать отдельными страницами по мере необходимости. |
| [getBlocks()](#getBlocks--) | Получайте доступ к GIF‑блокам без проблем с помощью этого свойства, облегчая простое извлечение и манипуляцию базовыми структурами данных изображения. |
| [isInterlaced()](#isInterlaced--) | Определяет, является ли изображение чересстрочным, влияя на его отображение при загрузке. |
| [getOriginalOptions()](#getOriginalOptions--) | Получайте параметры, основанные на оригинальных настройках файла, что критически важно для поддержания точности и согласованности при обработке и манипуляции изображениями. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Бесшовно добавляйте новую страницу в существующее изображение, улучшая его содержимое и расширяя охват. |
| [getActiveFrame()](#getActiveFrame--) | Управляйте и манипулируйте кадрами с помощью этого свойства, обеспечивая плавную навигацию и изменение активного кадра в GIF‑изображении. |
| [setActiveFrame(GifFrameBlock value)](#setActiveFrame-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-) | Управляйте и манипулируйте кадрами с помощью этого свойства, обеспечивая плавную навигацию и изменение активного кадра в GIF‑изображении. |
| [getBackgroundColor()](#getBackgroundColor--) | Управляйте цветом фона GIF‑изображения с помощью этого свойства. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Управляйте цветом фона GIF‑изображения с помощью этого свойства. |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Контролируйте индекс цвета фона GIF‑изображения, используя это свойство. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Контролируйте индекс цвета фона GIF‑изображения, используя это свойство. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Управляйте соотношением сторон пикселя GIF‑изображения с помощью этого свойства. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Управляйте соотношением сторон пикселя GIF‑изображения с помощью этого свойства. |
| [hasTransparentColor()](#hasTransparentColor--) | Определите, содержит ли активный кадр GIF‑изображения прозрачный цвет. |
| [getTransparentColor()](#getTransparentColor--) | Получите прозрачный цвет активного кадра в GIF‑изображении. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Определите, содержит ли активный кадр GIF‑изображения прозрачный цвет. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Это свойство определяет, содержит ли GIF‑изображение цвет фона. |
| [getImageOpacity()](#getImageOpacity--) | Получайте непрозрачность активного кадра в изображении, предоставляя информацию об уровне его прозрачности. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Изменяет размер этого экземпляра [Image](../../com.aspose.imaging/image). |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Изменяет размер этого экземпляра [Image](../../com.aspose.imaging/image). |
| [resizeFullFrame(int newWidth, int newHeight, int resizeType)](#resizeFullFrame-int-int-int-) | Изменение размера изображения с учётом всех кадров каждой страницы в GIF, тем самым предотвращая появление возможных артефактов. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Выполняйте вращение, отражение или оба действия исключительно над активным кадром. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Применяйте дизеринг к текущему изображению. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Обрезайте изображение, используя указанный прямоугольный участок. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Повышайте качество изображения, применяя гамма‑коррекцию. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Применяйте конкретный фильтр к назначенной области изображения, улучшая её визуальное качество или изменяя внешний вид по желанию. |
| [setFrameTime(int time)](#setFrameTime-int-) | Регулирует длительность каждого кадра в миллисекундах, обеспечивая согласованное время воспроизведения во всей последовательности изображений. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Регулирует яркость изображения в соответствии с указанным параметром `brightness`. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Регулирует контраст изображения, усиливая или уменьшая разницу в яркости между пикселями. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Гамма‑коррекция изображения применяет нелинейную настройку значений пикселей, усиливая или уменьшая яркость в зависимости от указанных коэффициентов для красного, зелёного и синего каналов. |
| [grayscale()](#grayscale--) | Преобразование изображения в его градационную (оттенки серого) форму переводит цветное изображение в черно‑белый вариант, удаляя цветовую информацию при сохранении яркости. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Бинаризация изображения с предопределённым порогом преобразует градационное или цветное изображение в бинарное, где каждый пиксель классифицируется как чёрный или белый в зависимости от того, превышает ли его интенсивность заданный порог. |
| [binarizeOtsu()](#binarizeOtsu--) | Бинаризация изображения с использованием пороговой обработки Оцу — это метод, позволяющий автоматически определить оптимальное значение порога для преобразования градационного изображения в бинарное. |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли с интегральным порогом — это метод преобразования градационного изображения в бинарное. |
| [orderBlocks()](#orderBlocks--) | Упорядочивание блоков GIF в соответствии со спецификацией GIF обеспечивает правильную структуру GIF и соответствие стандарту. |
| [clearBlocks()](#clearBlocks--) | Очистка всех блоков GIF удаляет любые существующие данные, хранящиеся в изображении. |
| [insertBlock(int index, IGifBlock block)](#insertBlock-int-com.aspose.imaging.fileformats.gif.IGifBlock-) | Вставка нового блока GIF позволяет добавить пользовательские данные в определённое место изображения. |
| [addBlock(IGifBlock block)](#addBlock-com.aspose.imaging.fileformats.gif.IGifBlock-) | Добавление нового блока GIF позволяет включить дополнительные данные в изображение. |
| [removeBlock(IGifBlock block)](#removeBlock-com.aspose.imaging.fileformats.gif.IGifBlock-) | Удаление блока GIF удаляет определённые данные из изображения, предоставляя возможность очистить или изменить структуру изображения. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | Пропорциональное изменение размера сохраняет соотношение сторон изображения при корректировке его размеров, гарантируя, что изображение не будет выглядеть растянутым или искажённым. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Этот метод вращает изображение вокруг его центральной точки. |

## Example: This example shows how to create a GIF image and save it to a file.

``` java
String dir = "c:\\temp\\";

// Создайте блок кадра GIF размером 100×100 пикселей.
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
try {
    // Заполните весь блок красным цветом.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(firstBlock);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    gr.fillRectangle(brush, firstBlock.getBounds());

    com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
    try {
        gifImage.save(dir + "output.gif");
    } finally {
        gifImage.dispose();
    }
} finally {
    firstBlock.dispose();
}
```


## Example: Create multipage GIF image using single page raster images.

``` java
static void main(String[] args)
{
    // Загрузить кадры
    RasterImage[] frames = loadFrames("Animation frames");

    // Создать GIF‑изображение, используя первый кадр
    try (GifImage image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // Добавьте кадры в GIF‑изображение с помощью метода AddPage
        for (int index = 1; index < frames.length; index++)
        {
            image.addPage(frames[index]);
        }

        // Сохранить GIF‑изображение
        image.save("Multipage.gif");
    }

    // освободить ресурсы
    for (RasterImage frame : frames)
    {
        frame.close();
    }
}

private static RasterImage[] loadFrames(String directory)
{
    LinkedList<RasterImage> list = new LinkedList<RasterImage>();
    String[] fileList = new File(directory).list();
    if (fileList != null)
    {
        for (String filePath : fileList)
        {
            list.add((RasterImage) Image.load(filePath));
        }
    }
                
    return list.toArray(new RasterImage[0]);
}
```


## Example: Export of part of animation from GIF image based on time interval.

``` java
try (Image image = Image.load("Animation.gif"))
{
    GifOptions options = new GifOptions();
    options.setFullFrame(true);
    final MultiPageOptions multiPageOptions = new MultiPageOptions();
    multiPageOptions.setMode(MultiPageMode.TimeInterval);
    multiPageOptions.setTimeInterval(new TimeInterval(0, 400));
    options.setMultiPageOptions(multiPageOptions);

    image.save("PartOfAnimation.gif", options);
}
```

### GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-}
```
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)
```


Инициализируйте новый объект [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) с указанными параметрами для первого кадра и глобальной палитры. Начните быстро управлять GIF‑изображениями, обеспечивая точное представление с настраиваемыми параметрами для оптимальных результатов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | Первый кадр, с которым инициализируется GIF‑изображение. |
| globalPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Глобальная палитра для использования. Обратите внимание, что если оба `firstFrame` и `globalPalette` равны null, будет использована палитра по умолчанию. |

### GifImage(GifFrameBlock firstFrame) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-}
```
public GifImage(GifFrameBlock firstFrame)
```


Создание GIF‑изображений становится простым с конструктором [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage). Достаточно указать параметр firstFrame, и вы погрузитесь в мир динамичной визуальной коммуникации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | Первый кадр, с которым инициализируется GIF‑изображение. |

### GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-boolean-byte-byte-byte-boolean-}
```
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer)
```


Начните работу без усилий с конструктором [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage). С помощью этого простого метода вы сможете легко создавать анимированные GIF‑файлы. Просто передайте firstFrame, globalPalette, paletteColorResolution, aspectRatio и другие параметры — и вы будете готовы оживить свои визуальные материалы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | Первый кадр, с которым инициализируется GIF‑изображение. |
| globalPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Глобальная палитра для использования. Обратите внимание, что если оба `firstFrame` и `globalPalette` равны null, будет использована палитра по умолчанию. |
| isPaletteSorted | boolean | если установить `true`, палитра будет отсортирована. Обратите внимание, что параметр используется, когда `globalPalette` не равен null. |
| paletteColorResolution | byte | Разрешение цвета палитры. Обратите внимание, что параметр используется, когда `globalPalette` не равен null. |
| paletteBackgroundColorIndex | byte | Индекс фонового цвета палитры. |
| aspectRatio | byte | Соотношение сторон. |
| hasTrailer | boolean | если установить `true`, у GIF‑изображения будет трейлер, иначе в конце потока трейлер не будет записан. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Получите формат файла без труда с помощью этого свойства. Это ваш основной источник для определения формата ваших файлов. Бесшовно интегрированный в ваш рабочий процесс, он предоставляет важную информацию без каких‑либо затруднений.

**Returns:**
long
### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Управляйте наличием трейлера в ваших GIF‑файлах с помощью этого свойства. Независимо от того, нужно ли проверить наличие трейлера или задать его присутствие, это свойство упрощает процесс. Держите свои GIF‑файлы структурированными и соответствующими стандартам с этой интуитивной функцией.

**Returns:**
boolean - `true` если у GIF есть трейлер; иначе `false`.
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Управляйте наличием трейлера в ваших GIF‑файлах с помощью этого свойства. Независимо от того, нужно ли проверить наличие трейлера или задать его присутствие, это свойство упрощает процесс. Держите свои GIF‑файлы структурированными и соответствующими стандартам с этой интуитивной функцией.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | `true` если у GIF есть трейлер; иначе `false`. |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Контролируйте сортировку палитры в ваших GIF‑изображениях с помощью этого свойства. Независимо от того, нужно ли проверить, отсортирована ли палитра, или задать поведение сортировки, это свойство предоставляет простой способ управления организацией палитры в GIF‑файлах.

**Returns:**
boolean - `true`, если палитра отсортирована; иначе `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Контролируйте сортировку палитры в ваших GIF‑изображениях с помощью этого свойства. Независимо от того, нужно ли проверить, отсортирована ли палитра, или задать поведение сортировки, это свойство предоставляет простой способ управления организацией палитры в GIF‑файлах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | `true`, если палитра отсортирована; иначе `false`. |

### getLoopsCount() {#getLoopsCount--}
```
public int getLoopsCount()
```


Получите количество повторов без усилий с помощью этого свойства. Если ваше GIF‑изображение содержит информацию о циклах, это свойство предоставляет быстрый доступ к числу повторов, позволяя беспрепятственно управлять поведением зацикливания в GIF‑файлах.

**Returns:**
int - Количество циклов или 1 (значение по умолчанию)
### setLoopsCount(int value) {#setLoopsCount-int-}
```
public void setLoopsCount(int value)
```


Получите количество повторов без усилий с помощью этого свойства. Если ваше GIF‑изображение содержит информацию о циклах, это свойство предоставляет быстрый доступ к числу повторов, позволяя беспрепятственно управлять поведением зацикливания в GIF‑файлах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Количество циклов или 1 (значение по умолчанию) |

### getPaletteColorResolutionBits() {#getPaletteColorResolutionBits--}
```
public byte getPaletteColorResolutionBits()
```


Управляйте разрешением цвета палитры ваших GIF‑изображений с помощью этого свойства. Регулируйте количество бит, используемых для представления цветов в палитре, обеспечивая тонкий контроль над глубиной цвета и качеством изображения.

**Returns:**
byte - Биты разрешения цвета палитры.
### setPaletteColorResolutionBits(byte value) {#setPaletteColorResolutionBits-byte-}
```
public void setPaletteColorResolutionBits(byte value)
```


Управляйте разрешением цвета палитры ваших GIF‑изображений с помощью этого свойства. Регулируйте количество бит, используемых для представления цветов в палитре, обеспечивая тонкий контроль над глубиной цвета и качеством изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte | Биты разрешения цвета палитры. |

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Получите общее количество страниц, содержащихся в изображении, с помощью этого простого свойства. Идеально подходит для быстрой оценки объёма содержимого изображения.

**Returns:**
int — количество страниц.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Получайте доступ к страницам изображения через это удобное свойство, позволяющее беспрепятственно перемещаться и манипулировать отдельными страницами по мере необходимости.

**Returns:**
com.aspose.imaging.Image[] — страницы.
### getBlocks() {#getBlocks--}
```
public IGifBlock[] getBlocks()
```


Получайте доступ к GIF‑блокам без проблем с помощью этого свойства, облегчая простое извлечение и манипуляцию базовыми структурами данных изображения.

**Returns:**
com.aspose.imaging.fileformats.gif.IGifBlock[] - GIF‑блоки.
### isInterlaced() {#isInterlaced--}
```
public boolean isInterlaced()
```


Определяет, является ли изображение чересстрочным, влияя на его отображение при загрузке. Это свойство предоставляет информацию о поведении рендеринга изображения, что важно для оптимизации стратегий загрузки и улучшения общего опыта просмотра.

**Returns:**
boolean - `true`, если данный экземпляр изображения чересстрочен; иначе `false`.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Получите параметры, основанные на настройках исходного файла, которые критически важны для поддержания точности и согласованности при обработке и манипуляции изображениями. Этот метод позволяет бесшовно интегрировать параметры, специфичные для файла, в последующие операции, обеспечивая точную визуализацию и соблюдение присущих изображению характеристик. Это может помочь сохранить глубину цвета и другие параметры оригинального изображения без изменений. Например, если мы загружаем черно‑белое PNG‑изображение с 1 битом на пиксель и затем сохраняем его с помощью метода [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-), будет получено PNG‑изображение с 8‑битным цветом. Чтобы избежать этого и сохранить PNG‑изображение с 1‑битным цветом, используйте этот метод для получения соответствующих параметров сохранения и передайте их в метод [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) в качестве второго параметра.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Бесшовно внедрите новую страницу в существующее изображение, улучшая его содержимое и расширяя охват. Этот метод дополняет коллекции изображений дополнительным контентом, способствуя креативности и гибкости в управлении и композиции изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | Страница для добавления. |


**Example: Create multipage GIF image using single page raster images.**

``` java
static void main(String[] args)
{
    // Загрузить кадры
    RasterImage[] frames = loadFrames("Animation frames");

    // Создать GIF‑изображение, используя первый кадр
    try (GifImage image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // Добавьте кадры в GIF‑изображение с помощью метода AddPage
        for (int index = 1; index < frames.length; index++)
        {
            image.addPage(frames[index]);
        }

        // Сохранить GIF‑изображение
        image.save("Multipage.gif");
    }

    // освободить ресурсы
    for (RasterImage frame : frames)
    {
        frame.close();
    }
}

private static RasterImage[] loadFrames(String directory)
{
    LinkedList<RasterImage> list = new LinkedList<RasterImage>();
    String[] fileList = new File(directory).list();
    if (fileList != null)
    {
        for (String filePath : fileList)
        {
            list.add((RasterImage) Image.load(filePath));
        }
    }
                
    return list.toArray(new RasterImage[0]);
}
```

### getActiveFrame() {#getActiveFrame--}
```
public GifFrameBlock getActiveFrame()
```


Управляйте и манипулируйте кадрами с помощью этого свойства, обеспечивая плавную навигацию и изменение активного кадра в GIF‑изображении.

**Returns:**
[GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) - the active frame.

**Example: The following example shows how to remove all blocks from a GIF image.**

``` java
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }

    System.out.println("Clear all the blocks");
    gifImage.clearBlocks();

    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}

// Вывод выглядит так:
// Размер активного кадра: { Width = 100, Height = 100}
// Очистить все блоки
// Активный кадр не установлен
```

### setActiveFrame(GifFrameBlock value) {#setActiveFrame-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-}
```
public void setActiveFrame(GifFrameBlock value)
```


Управляйте и манипулируйте кадрами с помощью этого свойства, обеспечивая плавную навигацию и изменение активного кадра в GIF‑изображении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | активный кадр. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Управляйте цветом фона GIF‑изображения с помощью этого свойства. Вы можете установить или получить цвет фона, чтобы обеспечить согласованность и улучшить визуальную привлекательность.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Управляйте цветом фона GIF‑изображения с помощью этого свойства. Вы можете установить или получить цвет фона, чтобы обеспечить согласованность и улучшить визуальную привлекательность.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | цвет фона. |

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Контролируйте индекс цвета фона GIF‑изображения с помощью этого свойства. Установите или получите индекс, чтобы поддерживать согласованность или достичь желаемых визуальных эффектов.

**Returns:**
byte - индекс цвета фона.
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Контролируйте индекс цвета фона GIF‑изображения с помощью этого свойства. Установите или получите индекс, чтобы поддерживать согласованность или достичь желаемых визуальных эффектов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte | индекс цвета фона. |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Управляйте соотношением сторон пикселя GIF‑изображения с помощью этого свойства. Установите или получите соотношение, чтобы обеспечить точную отрисовку и сохранить визуальную достоверность.

**Returns:**
byte - соотношение сторон пикселя.
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Управляйте соотношением сторон пикселя GIF‑изображения с помощью этого свойства. Установите или получите соотношение, чтобы обеспечить точную отрисовку и сохранить визуальную достоверность.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte | соотношение сторон пикселя. |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Определите, содержит ли активный кадр GIF‑изображения прозрачный цвет. Это свойство предоставляет удобный способ проверки прозрачности в изображении.

**Returns:**
boolean - значение, указывающее, имеет ли активный кадр прозрачный цвет.
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Получите прозрачный цвет активного кадра GIF‑изображения. Это свойство позволяет получить доступ к конкретному цвету, назначенному прозрачным в текущем активном кадре.

**Returns:**
[Color](../../com.aspose.imaging/color) - active frame transparent color.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Определите, содержит ли активный кадр GIF‑изображения прозрачный цвет. Это свойство предоставляет удобный способ проверки прозрачности в изображении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, имеет ли активный кадр прозрачный цвет. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Это свойство определяет, содержит ли GIF‑изображение цвет фона. Если true, это указывает, что изображение включает цвет фона.

**Returns:**
boolean - значение, указывающее, имеет ли изображение цвет фона.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Получите непрозрачность активного кадра в изображении, получая представление об уровне его прозрачности. Это свойство особенно полезно для понимания степени прозрачности или непрозрачности активного кадра в изображении.

Значение непрозрачности от 0.0 (полностью прозрачный) до 1.0 (полностью непрозрачный).

**Returns:**
float - непрозрачность этого изображения (активный кадр).
### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Изменяет размер этого экземпляра [Image](../../com.aspose.imaging/image).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| resizeType | int | Тип изменения размера. |


**Example: This example loads a GIF image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.gif.GifImage image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Увеличить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Уменьшить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Увеличить в 2 раза с использованием билинейного ресэмплинга.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Уменьшить в 2 раза с использованием билинейного ресэмплинга.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Изменяет размер этого экземпляра [Image](../../com.aspose.imaging/image).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Настройки. |


**Example: This example loads a GIF image and resizes it using various resizing settings.**

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

// Метод Евклида
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Уменьшить в 2 раза с помощью адаптивного пересэмплинга.
    gifImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Сохранить в PNG
    gifImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeFullFrame(int newWidth, int newHeight, int resizeType) {#resizeFullFrame-int-int-int-}
```
public void resizeFullFrame(int newWidth, int newHeight, int resizeType)
```


Изменение размера изображения с учётом всех кадров каждой страницы в GIF, что предотвращает появление потенциальных артефактов. Этот метод необходим для сохранения целостности и качества изображения, особенно при работе с анимированными GIF‑файлами или последовательностями кадров.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| resizeType | int | Тип изменения размера. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Выполнить вращение, отражение или оба действия только над активным кадром. Эта операция применяет преобразования исключительно к текущему активному кадру изображения, сохраняя целостность остальных кадров в последовательности.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rotateFlipType | int | Тип вращения и отражения. |


**Example: This example loads a GIF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java

// Вспомогательный класс, используемый в основном примере ниже.
class Utils {
    // Вспомогательный метод для получения строкового представления формата файла.
    public String getRotateFlipTypeString(int rotateFlipType) {
        if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipNone) {
            return "RotateNoneFlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipNone) {
            return "Rotate90FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipNone) {
            return "Rotate180FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipNone) {
            return "Rotate270FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipX) {
            return "RotateNoneFlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipX) {
            return "Rotate90FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipX) {
            return "Rotate180FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipX) {
            return "Rotate270FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipY) {
            return "RotateNoneFlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipY) {
            return "Rotate90FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipY) {
            return "Rotate180FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipY) {
            return "Rotate270FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipXY) {
            return "RotateNoneFlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipXY) {
            return "Rotate90FlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipXY) {
            return "Rotate180FlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipXY) {
            return "Rotate270FlipXY";
        } else {
            return "UNDEFINED";
        }
    }
}

// Вот основной пример
Utils utils = new Utils();

String dir = "c:\\temp\\";

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // Поверните, отразите и сохраните в выходной файл.
    com.aspose.imaging.fileformats.gif.GifImage image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + utils.getRotateFlipTypeString(rotateFlipType) + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Применить дизеринг к текущему изображению. Этот процесс улучшает качество изображения, уменьшая цветовые полосы и улучшая переходы цветов, что приводит к более плавному виду.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ditheringMethod | int | Метод дизеринга. |
| bitsCount | int | Окончательное количество бит для дизеринга. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Пользовательская палитра для дизеринга. |


**Example: The following example loads a GIF image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Выполнить пороговое дизеринг с использованием 4-битовой цветовой палитры, содержащей 16 цветов.
    // Чем больше указано бит, тем выше качество и тем больше размер выходного изображения.
    // Обратите внимание, что в данный момент поддерживаются только 1-битовые, 4-битовые и 8-битовые палитры.
    gifImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    gifImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Выполнить дизеринг Флойда с использованием 1-битовой цветовой палитры, содержащей только 2 цвета — черный и белый.
    // Чем больше указано бит, тем выше качество и тем больше размер выходного изображения.
    // Обратите внимание, что в данный момент поддерживаются только 1-битовые, 4-битовые и 8-битовые палитры.
    gifImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    gifImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Обрезать изображение, используя заданную прямоугольную область. Эта операция удаляет внешнюю часть изображения, оставляя только выбранный регион, определённый прямоугольником.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник. |


**Example: The following example crops a GIF image.**
В следующем примере изображение GIF обрезается. Область обрезки указывается через Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Обрежьте изображение. Область обрезки — прямоугольный центральный участок изображения.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            gifImage.getWidth() / 4,
            gifImage.getHeight() / 4,
            gifImage.getWidth() / 2,
            gifImage.getHeight() / 2);
    gifImage.crop(area);

    // Сохраните обрезанное изображение в PNG
    gifImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Повысить качество изображения, применив гамма‑коррекцию. Этот метод регулирует цветовую гамму изображения для достижения оптимальной визуальной чёткости. Он изменяет значение гаммы каждого пикселя, что приводит к улучшенной передаче цветов и общему виду изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| гамма | float | Коэффициент гаммы для красного, зелёного и синего каналов |


**Example: The following example performs gamma-correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Установите коэффициент гаммы для красного, зелёного и синего каналов.
    gifImage.adjustGamma(2.5f);
    gifImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Применить определённый фильтр к заданной области изображения, улучшая её визуальное качество или изменяя внешний вид по желанию. Этот метод избирательно обрабатывает пиксели внутри определённого прямоугольника, позволяя выполнять целенаправленные корректировки, сохраняя целостность окружающих данных изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Параметры. |


**Example: The following example applies various types of filters to a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Примените медианный фильтр с размером прямоугольника 5 ко всему изображению.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    gifImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Примените билатеральный сглаживающий фильтр с размером ядра 5 ко всему изображению.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    gifImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Примените гауссов фильтр размытия с радиусом 5 и значением sigma 4.0 ко всему изображению.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Примените фильтр Гаусса-Винера с радиусом 5 и значением smooth 4.0 ко всему изображению.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Примените фильтр движения Винера с длиной 5, значением smooth 4.0 и углом 90,0 градусов ко всему изображению.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    gifImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Примените фильтр резкости с размером ядра 5 и значением sigma 4.0 ко всему изображению.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### setFrameTime(int time) {#setFrameTime-int-}
```
public void setFrameTime(int time)
```


Регулирует длительность каждого кадра в миллисекундах, обеспечивая согласованное время воспроизведения всей последовательности изображений. Этот метод одинаково задаёт время отображения для каждого кадра, позволяя точно контролировать скорость анимации. Изменение этого значения сбросит задержку для всех кадров.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| время | int | Время длительности кадра в миллисекундах. |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Регулирует яркость изображения в соответствии с указанным параметром `brightness`. Этот метод равномерно изменяет яркость всего изображения, усиливая или уменьшая общую светимость для достижения желаемого эффекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightness | int | Значение яркости. |


**Example: The following example performs brightness correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Установите значение яркости. Допустимые значения яркости находятся в диапазоне [-255, 255].
    gifImage.adjustBrightness(50);
    gifImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Регулирует контраст изображения, усиливая или уменьшая разницу в яркости между пикселями. Этот метод изменяет общий тональный диапазон изображения, делая тёмные области темнее, а светлые — светлее, улучшая визуальную чёткость и детали.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| contrast | float | Значение контрастности (в диапазоне [-100; 100]) |


**Example: The following example performs contrast correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Установите значение контрастности. Допустимые значения контрастности находятся в диапазоне [-100f, 100f].
    gifImage.adjustContrast(50f);
    gifImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Гамма‑коррекция изображения применяет нелинейную настройку значений пикселей, усиливая или уменьшая яркость в зависимости от указанных коэффициентов для красного, зелёного и синего каналов. Этот метод помогает точно настроить цветовой баланс и светимость изображения, улучшая его общий вид и визуальное качество.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| gammaRed | float | Коэффициент гаммы для красного канала |
| gammaGreen | float | Коэффициент гаммы для зелёного канала |
| gammaBlue | float | Коэффициент гаммы для синего канала |


**Example: The following example performs gamma-correction of a GIF image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Установите отдельные коэффициенты гаммы для красного, зелёного и синего каналов.
    gifImage.adjustGamma(1.5f, 2.5f, 3.5f);
    gifImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


Преобразование изображения в его градационную (оттенки серого) форму переводит цветное изображение в черно‑серый вариант, удаляя цветовую информацию при сохранении светимости. Этот процесс упрощает изображение до оттенков серого, делая его пригодным для различных применений, таких как печать, обработка документов и анализ в градациях серого.


**Example: The following example transforms a colored GIF image to its grayscale representation.**
В следующем примере цветное GIF‑изображение преобразуется в градационную форму. Градационные изображения состоят исключительно из оттенков серого и содержат только информацию о интенсивности.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    gifImage.grayscale();
    gifImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Бинаризация изображения с предопределённым порогом преобразует градационное или цветное изображение в бинарное, где каждый пиксель классифицируется как чёрный или белый в зависимости от того, превышает ли его интенсивность заданный порог.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | byte | Значение порога. Если соответствующее серое значение пикселя больше порога, ему будет присвоено значение 255, иначе — 0. |


**Example: The following example binarizes a GIF image with the predefined threshold.**
В следующем примере GIF‑изображение бинаризуется с предопределённым порогом. Бинарные изображения содержат только 2 цвета — чёрный и белый.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage djvuImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Бинаризуйте изображение с пороговым значением 127.
    // Если соответствующее серое значение пикселя больше 127, ему будет присвоено значение 255, иначе 0.
    djvuImage.binarizeFixed((byte) 127);
    djvuImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Бинаризация изображения с пороговой обработкой Оцу — метод, используемый для автоматического определения оптимального порогового значения при преобразовании градационного изображения в бинарное. Алгоритм пороговой обработки Оцу вычисляет порог, минимизирующий внутриклассовую дисперсию интенсивностей пикселей в двух полученных классах (передний план и фон). Эта техника особенно полезна, когда оптимальное пороговое значение неизвестно и должно определяться адаптивно на основе гистограммы изображения.


**Example: The following example binarizes a GIF image with Otsu thresholding.**
В следующем примере GIF‑изображение бинаризуется с пороговой обработкой Оцу. Бинарные изображения содержат только 2 цвета — чёрный и белый.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Бинаризуйте изображение с пороговой обработкой Оцу.
    gifImage.binarizeOtsu();
    gifImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли с интегральным изображением — метод преобразования градационного изображения в бинарное. Этот алгоритм вычисляет локальный порог для каждого пикселя на основе средней интенсивности окружающих пикселей в заданном окне. Адаптивно регулируя порог в зависимости от локальных интенсивностей пикселей, метод Брэдли эффективно справляется с вариациями освещения и контраста по всему изображению.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightnessDifference | double | Разница яркости между пикселем и средним значением окна s × s пикселей, центрированного вокруг этого пикселя. |

### orderBlocks() {#orderBlocks--}
```
public void orderBlocks()
```


Упорядочивание блоков GIF в соответствии со спецификацией GIF обеспечивает правильную структуру GIF и соответствие стандарту. Этот процесс включает размещение блоков в правильной последовательности, определённой спецификацией. Кроме того, может потребоваться удаление некоторых экземпляров [GifGraphicsControlBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock), не необходимых для окончательной компоновки. Соблюдая спецификацию GIF, полученное изображение будет корректно построено и совместимо с приложениями для просмотра GIF.

### clearBlocks() {#clearBlocks--}
```
public void clearBlocks()
```


Очистка всех блоков GIF удаляет любые существующие данные, хранящиеся в изображении. Эта операция эффективно сбрасывает изображение в пустое состояние, удаляя все ранее добавленные блоки. Используйте этот метод, когда необходимо начать с чистого листа для создания или изменения GIF‑изображения.


**Example: The following example shows how to remove all blocks from a GIF image.**

``` java
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }

    System.out.println("Clear all the blocks");
    gifImage.clearBlocks();

    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}

// Вывод выглядит так:
// Размер активного кадра: { Width = 100, Height = 100}
// Очистить все блоки
// Активный кадр не установлен
```

### insertBlock(int index, IGifBlock block) {#insertBlock-int-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void insertBlock(int index, IGifBlock block)
```


Вставка нового блока GIF позволяет добавить пользовательские данные в определённую позицию внутри изображения. Этот метод даёт возможность разместить пользовательские блоки в нужном месте GIF‑изображения, обеспечивая гибкость в организации и структуре данных изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Элемент с нулевой индексацией, в котором будет вставлен блок. |
| block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | Блок GIF для добавления. |

### addBlock(IGifBlock block) {#addBlock-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void addBlock(IGifBlock block)
```


Добавление нового блока GIF позволяет включить дополнительные данные в изображение. Этот метод позволяет добавить пользовательские блоки к GIF‑изображению, которые могут содержать различные типы информации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | Блок GIF для добавления. |


**Example: The following example shows how to compose an animated GIF image from individual GIF blocks.**

``` java
String dir = "c:\\temp\\";

// Создать GIF‑изображение размером 100 × 100 пикселей.
// Первый блок по умолчанию полностью черный.
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    // Первый круг красный
    com.aspose.imaging.brushes.SolidBrush brush1 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    // Второй круг чёрный
    com.aspose.imaging.brushes.SolidBrush brush2 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getBlack());

    // Постепенно увеличивайте угол красной дуги.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock block = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);

        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(block);
        gr.fillPie(brush1, block.getBounds(), 0, angle);

        gifImage.addBlock(block);
    }

    // Постепенно увеличивайте угол чёрной дуги и стирайте красную дугу.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock block = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);

        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(block);
        gr.fillPie(brush2, block.getBounds(), 0, angle);
        gr.fillPie(brush1, block.getBounds(), angle, 360 - angle);

        gifImage.addBlock(block);
    }

    gifImage.save(dir + "animated_radar.gif");
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}
```

### removeBlock(IGifBlock block) {#removeBlock-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void removeBlock(IGifBlock block)
```


Удаление блока GIF удаляет определённые данные из изображения, предоставляя возможность очистить или изменить структуру изображения. Этот метод позволяет удалить нежелательные или ненужные блоки, оптимизируя GIF‑изображение для эффективного хранения. Используйте эту функцию, чтобы устранить устаревшую информацию из изображения, сохраняя его целостность и качество.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | Блок для удаления. |

--------------------

Примечание: не забудьте вызвать Dispose для блока, если вы не собираетесь добавлять его в другое GifImage. |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public void resizeProportional(int newWidth, int newHeight, int resizeType)
```


Пропорциональное изменение размера сохраняет соотношение сторон изображения при корректировке его размеров, гарантируя, что изображение не будет выглядеть растянутым или искажённым. Этот метод изменяет размер изображения пропорционально, масштабируя как ширину, так и высоту одинаковым коэффициентом. Пропорциональное изменение размера будет масштабировать каждый кадр согласно отношению `newWidth`/width и `newHeight`/height.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| resizeType | int | Тип изменения размера. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Этот метод вращает изображение вокруг его центральной точки. Указывая угол поворота, вы можете вращать изображение по часовой стрелке или против неё, чтобы достичь нужной ориентации. Такое вращение помогает скорректировать представление или выравнивание изображения без искажения его содержимого.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения в градусах. Положительные значения вращают по часовой стрелке. |
| resizeProportionally | boolean | если установить `true`, размер вашего изображения будет изменён в соответствии с проекциями повернутого прямоугольника (угловых точек); в противном случае размеры останутся неизменными, и будет вращено только `` содержимое изображения. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Цвет фона. |

