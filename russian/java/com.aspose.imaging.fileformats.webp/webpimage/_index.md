---
title: "WebPImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Манипулируйте растровыми изображениями WebP с помощью нашего API, используя его современные возможности как для без потерь, так и для сжатия с потерями, обеспечивая оптимальное качество изображения при уменьшенных размерах файлов."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.fileformats.webp/webpimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public final class WebPImage extends RasterCachedMultipageImage implements IMultipageImageExt, IMetadataContainer
```

Манипулируйте растровыми изображениями WebP с помощью нашего API, используя его современные возможности как для без потерь, так и для сжатия с потерями, обеспечивая оптимальное качество изображения при уменьшенных размерах файлов. Беспрепятственно обрабатывайте расширенные форматы файлов, анимацию и альфа‑каналы, одновременно легко изменяя размеры, пропорционально масштабируя, обрезая, вращая, применяя фильтры, регулируя параметры изображения и конвертируя в другие форматы изображений для универсальной оптимизации веб‑изображений.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WebPImage(InputStream stream)](#WebPImage-java.io.InputStream-) | Создайте новый экземпляр класса [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), инициализированный из предоставленного источника потока. |
| [WebPImage(InputStream stream, LoadOptions loadOptions)](#WebPImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Создайте новый экземпляр класса [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) с использованием потока и указанных параметров загрузки, обеспечивая универсальную работу с данными изображений WebP. |
| [WebPImage(String path)](#WebPImage-java.lang.String-) | Создайте новый экземпляр класса [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), инициализированный из предоставленного файлового источника. |
| [WebPImage(String path, LoadOptions loadOptions)](#WebPImage-java.lang.String-com.aspose.imaging.LoadOptions-) | Создайте новый экземпляр класса [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) с использованием файла и указанных параметров загрузки, обеспечивая гибкую работу с данными изображений WebP. |
| [WebPImage(RasterImage rasterImage)](#WebPImage-com.aspose.imaging.RasterImage-) | Создайте новый экземпляр класса [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), инициализированный из предоставленного объекта rasterImage. |
| [WebPImage(RasterImage rasterImage, LoadOptions loadOptions)](#WebPImage-com.aspose.imaging.RasterImage-com.aspose.imaging.LoadOptions-) | Создайте новый экземпляр класса [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) с использованием объекта rasterImage и указанных параметров загрузки, позволяя гибко работать с данными изображения. |
| [WebPImage(int width, int height, WebPOptions options)](#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-) | Создайте новый экземпляр класса [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) с пустым изображением заданных ширины и высоты. |
| [WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)](#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-com.aspose.imaging.LoadOptions-) | Создайте новый экземпляр класса [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) с пустым изображением и указанными параметрами загрузки. |
## Методы

| Метод | Описание |
| --- | --- |
| [getOptions()](#getOptions--) | Получайте или изменяйте параметры, связанные с указанным свойством, обеспечивая тонкую настройку поведения и настроек. |
| [getPages()](#getPages--) | Получите доступ к блокам WebP внутри изображения, позволяя детально изучать или изменять базовую структуру блоков. |
| [getPageCount()](#getPageCount--) | Получите общее количество страниц в указанном документе, облегчая эффективную навигацию и управление многостраничным содержимым. |
| [getFileFormat()](#getFileFormat--) | Получите значение формата файла, связанного с изображением, предоставляющее информацию о формате, в котором хранится изображение. |
| [hasAlpha()](#hasAlpha--) | Определите, содержит ли изображение альфа‑канал, указывающий наличие информации о прозрачности. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Добавьте новую страницу к изображению, расширяя его содержимое и позволяя добавить дополнительные визуальные элементы. |
| [addBlock(IFrame block)](#addBlock-com.aspose.imaging.fileformats.webp.IFrame-) | Вставьте новый блок WebP в изображение, обогащая его содержимое и облегчая продвинутую обработку изображения. |
| [clearBlocks()](#clearBlocks--) | Очистите все существующие блоки WebP из изображения, обеспечивая чистый лист для последующих изменений или добавлений. |
| [insertBlock(int index, IFrame block)](#insertBlock-int-com.aspose.imaging.fileformats.webp.IFrame-) | Вставьте новый блок WebP в указанную позицию внутри изображения, обеспечивая точный контроль над последовательностью блоков. |
| [removeBlock(IFrame block)](#removeBlock-com.aspose.imaging.fileformats.webp.IFrame-) | Удалите указанный блок WebP из изображения, облегчая эффективное управление структурой данных изображения. |
| [getOriginalOptions()](#getOriginalOptions--) | Получает параметры, основанные на настройках оригинального файла. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Поверните изображение вокруг его центра на указанный угол, одновременно пропорционально изменив его размер и применив заданные параметры цвета фона. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Измените размер изображения, корректируя его размеры при сохранении пропорций. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Пропорционально измените ширину изображения, сохраняя его соотношение сторон. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Пропорционально измените высоту изображения, сохраняя его соотношение сторон для согласованного масштабирования. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Примените вращение, отражение или обе операции исключительно к активному кадру внутри изображения. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Выполните дизеринг текущего изображения, чтобы уменьшить полосы цвета и улучшить визуальное качество. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Обрежьте изображение, используя указанный прямоугольный регион, удаляя нежелательные части и сохраняя нужный контент. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Обрежьте изображение, применяя сдвиги слева, справа, сверху и снизу, эффективно выбирая область интереса внутри изображения. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Выполните бинаризацию изображения, используя предопределённое значение порога, преобразуя его в бинарное изображение, где пиксели классифицируются как передний план или фон в зависимости от их интенсивности относительно порога. |
| [binarizeOtsu()](#binarizeOtsu--) | Выполните бинаризацию изображения, используя метод пороговой обработки Оцу, автоматически определяя оптимальное значение порога на основе гистограммы изображения. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Примените бинаризацию к изображению, используя адаптивный алгоритм пороговой обработки Брэдли с интегральным порогом изображения. |
| [grayscale()](#grayscale--) | Примените бинаризацию к изображению, используя адаптивный алгоритм пороговой обработки Брэдли с интегральным порогом изображения. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Примените гамма‑коррекцию к изображению, регулируя интенсивность пикселей для достижения желаемой яркости и цветового баланса. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Выполните гамма‑коррекцию изображения, используя отдельные коэффициенты для красного, зелёного и синего каналов, позволяя точно настраивать цветовой баланс и контраст. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Реализуйте настройку `brightness` для изображения, позволяя изменять общий уровень яркости. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Увеличьте контраст [Image](../../com.aspose.imaging/image), усиливая различия между светлыми и тёмными областями. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Отфильтруйте содержимое в указанном прямоугольнике, применяя заданный фильтр обработки изображения для улучшения или изменения выбранной области. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Измените размер изображения в соответствии с указанными настройками, обеспечивая точный контроль над размерами, соотношением сторон и поведением масштабирования. |

## Example: This example shows how to load a WebP image from a file and save it to PNG.

``` java
String dir = "c:\\temp\\";

// Загрузите WebP‑изображение из файла.
com.aspose.imaging.fileformats.webp.WebPImage webPImage = new com.aspose.imaging.fileformats.webp.WebPImage(dir + "test.webp");
try {
    // Сохранить в PNG
    // Обратите внимание, что только активный кадр будет сохранён в PNG, поскольку PNG не поддерживает многократные страницы.
    webPImage.save(dir + "test.output.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    webPImage.dispose();
}
```

### WebPImage(InputStream stream) {#WebPImage-java.io.InputStream-}
```
public WebPImage(InputStream stream)
```


Создайте новый экземпляр класса [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), инициализированный из предоставленного потока. Используйте этот конструктор для бесшовного создания объектов WebP‑изображения непосредственно из потоков, обеспечивая эффективную работу и манипуляцию данными WebP‑изображения в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | WebP‑изображение из потока. |

### WebPImage(InputStream stream, LoadOptions loadOptions) {#WebPImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public WebPImage(InputStream stream, LoadOptions loadOptions)
```


Создайте новый экземпляр класса [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), используя поток и указанные параметры загрузки, облегчая гибкую работу с данными WebP‑изображения. Включите этот конструктор для бесшовной инициализации объектов WebP‑изображения из потоков с возможностью настройки параметров загрузки по мере необходимости в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | WebP‑изображение из потока. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Параметры загрузки. |

### WebPImage(String path) {#WebPImage-java.lang.String-}
```
public WebPImage(String path)
```


Создайте новый экземпляр класса [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), инициализированный из предоставленного файла. Используйте этот конструктор для бесшовного создания объектов WebP‑изображения непосредственно из файлов, упрощая процесс загрузки и манипуляции данными WebP‑изображения в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь к файлу WebP‑изображения |

### WebPImage(String path, LoadOptions loadOptions) {#WebPImage-java.lang.String-com.aspose.imaging.LoadOptions-}
```
public WebPImage(String path, LoadOptions loadOptions)
```


Создайте новый экземпляр класса [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), используя файл и указанные параметры загрузки, обеспечивая гибкую работу с данными WebP‑изображения. Используйте этот конструктор для бесшовной инициализации объектов WebP‑изображения из файлов с настройкой параметров загрузки в соответствии с требованиями вашего приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь к файлу WebP‑изображения |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Параметры загрузки. |

### WebPImage(RasterImage rasterImage) {#WebPImage-com.aspose.imaging.RasterImage-}
```
public WebPImage(RasterImage rasterImage)
```


Создайте новый экземпляр класса [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), инициализированный из предоставленного объекта rasterImage. Этот конструктор позволяет бесшовно преобразовывать растровые изображения в формат WebP, обеспечивая эффективную работу и манипуляцию данными изображения в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Растровое изображение. |

### WebPImage(RasterImage rasterImage, LoadOptions loadOptions) {#WebPImage-com.aspose.imaging.RasterImage-com.aspose.imaging.LoadOptions-}
```
public WebPImage(RasterImage rasterImage, LoadOptions loadOptions)
```


Создайте новый экземпляр класса [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), используя объект rasterImage и указанные параметры загрузки, обеспечивая гибкую работу с данными изображения. Используйте этот конструктор для бесшовной инициализации объектов WebP‑изображения из растровых изображений с настройкой параметров загрузки в соответствии с требованиями вашего приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Растровое изображение. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Параметры загрузки. |

### WebPImage(int width, int height, WebPOptions options) {#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-}
```
public WebPImage(int width, int height, WebPOptions options)
```


Создайте новый экземпляр класса [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) с пустым изображением заданных ширины и высоты. Этот конструктор позволяет создавать пустые WebP‑изображения, предоставляя основу для последующей обработки изображений и генерации контента в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина изображения |
| height | int | Высота изображения. |
| options | [WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) | Параметры. |

### WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions) {#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-com.aspose.imaging.LoadOptions-}
```
public WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)
```


Создайте новый экземпляр класса [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) с пустым изображением и указанными параметрами загрузки. Этот конструктор позволяет инициализировать WebP‑изображения с настраиваемыми параметрами загрузки, обеспечивая гибкость при создании и обработке изображений в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина изображения |
| height | int | Высота изображения. |
| options | [WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) | Параметры. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Параметры загрузки. |

### getOptions() {#getOptions--}
```
public WebPOptions getOptions()
```


Получайте или изменяйте параметры, связанные с указанным свойством, обеспечивая точную настройку поведения и настроек. Используйте это свойство для бесшовного доступа и управления конфигурируемыми параметрами, облегчая гибкое управление и оптимизацию в функциональности вашего приложения.

**Returns:**
[WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) - the options.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Получите доступ к блокам WebP внутри изображения, позволяя детально изучать или изменять базовую структуру блоков. Используйте это свойство для анализа или изменения отдельных блоков данных WebP‑изображения, облегчая продвинутые методы обработки изображений в вашем приложении.

**Returns:**
com.aspose.imaging.Image[]
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Получите общее количество страниц в указанном документе, облегчая эффективную навигацию и управление многостраничным содержимым. Внедрите эту функцию для улучшения пользовательского опыта, обеспечивая бесшовный доступ к полной структуре документа.

**Returns:**
int — количество страниц.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Получите значение формата файла, связанного с изображением, предоставляющее информацию о формате, в котором изображение хранится. Используйте это свойство для определения формата файла изображения, облегчая проверки совместимости и обработку, специфичную для формата, в вашем приложении.

**Returns:**
long — значение формата файла
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Определите, содержит ли изображение альфа‑канал, указывающий наличие информации о прозрачности. Используйте это свойство, чтобы узнать, включает ли изображение прозрачность, обеспечивая корректную обработку операций, связанных с альфа‑каналом, в вашем приложении.

**Returns:**
boolean — `true`, если присутствует альфа-канал.

**Example: The following example loads a WEBP image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";
String fileName = dir + "sample.webp";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Если активный кадр TIFF содержит альфа-канал, то всё изображение TIFF считается имеющим альфа-канал.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, webpImage.getRawDataFormat(), webpImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.webp.IFrame frame : webpImage.getBlocks()) {
        if (frame instanceof com.aspose.imaging.fileformats.webp.WebPFrameBlock) {
            com.aspose.imaging.fileformats.webp.WebPFrameBlock frameBlock = (com.aspose.imaging.fileformats.webp.WebPFrameBlock) frame;
            System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", i++, frameBlock.getRawDataFormat(), frameBlock.hasAlpha());
        }
    }
} finally {
    image.dispose();
}

// Вывод может выглядеть так:
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, использованные каналы: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, использованные каналы: 1, HasAlpha=False
```

### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Добавьте новую страницу к изображению, расширяя его содержимое и размещая дополнительные визуальные элементы. Интегрируйте этот метод для упрощения динамического управления страницами в вашем приложении, обеспечивая бесшовное создание и расширение многостраничных документов или изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | Страница для добавления. |

### addBlock(IFrame block) {#addBlock-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void addBlock(IFrame block)
```


Внедрите новый блок WebP в изображение, обогатив его содержимое и упростив продвинутую обработку изображений. Интегрируйте этот метод для динамического улучшения структуры и сложности данных изображения WebP в вашем приложении, обеспечивая точный контроль и оптимизацию рендеринга изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | Блок Webp для добавления. |


**Example: This example shows how to create a multi-frame animated WebP image with the specified options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.WebPOptions createOptions = new com.aspose.imaging.imageoptions.WebPOptions();
createOptions.setLossless(true);
createOptions.setQuality(100f);
createOptions.setAnimBackgroundColor((long) com.aspose.imaging.Color.getGray().toArgb());

// Стандартный кадр плюс 36 + 36 дополнительных кадров.
createOptions.setAnimLoopCount(36 + 36 + 1);

// Создайте изображение WebP размером 100×100 пикселей.
com.aspose.imaging.fileformats.webp.WebPImage webPImage = new com.aspose.imaging.fileformats.webp.WebPImage(100, 100, createOptions);
try {
    // Первый круг красный
    com.aspose.imaging.brushes.SolidBrush brush1 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    // Второй круг чёрный
    com.aspose.imaging.brushes.SolidBrush brush2 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getBlack());

    // Постепенно увеличивайте угол красной дуги.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.webp.WebPFrameBlock block = new com.aspose.imaging.fileformats.webp.WebPFrameBlock(100, 100);
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(block);
        graphics.fillPie(brush1, block.getBounds(), 0, angle);

        webPImage.addBlock(block);
    }

    // Постепенно увеличивайте угол чёрной дуги и стирайте красную дугу.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.webp.WebPFrameBlock block = new com.aspose.imaging.fileformats.webp.WebPFrameBlock(100, 100);

        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(block);
        graphics.fillPie(brush2, block.getBounds(), 0, angle);
        graphics.fillPie(brush1, block.getBounds(), angle, 360 - angle);

        webPImage.addBlock(block);
    }

    // Сохранить в файл WebP
    webPImage.save(dir + "output.webp");
} finally {
    webPImage.dispose();
}
```

### clearBlocks() {#clearBlocks--}
```
public void clearBlocks()
```


Очистите все существующие блоки WebP из изображения, обеспечивая чистый лист для последующих изменений или добавлений. Используйте этот метод для эффективного сброса структуры блоков в данных изображения WebP, гарантируя оптимальное управление и организацию содержимого изображения в вашем приложении.

### insertBlock(int index, IFrame block) {#insertBlock-int-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void insertBlock(int index, IFrame block)
```


Вставьте новый блок WebP в указанном индексе изображения, обеспечивая точный контроль над последовательностью блоков. Интегрируйте этот метод для бесшовного добавления дополнительных блоков WebP в структуру данных изображения, способствуя продвинутой обработке и оптимизации изображений в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Элемент с нулевой индексацией, в который будет вставлен `block`. |
| block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | Блок Webp для добавления. |

### removeBlock(IFrame block) {#removeBlock-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void removeBlock(IFrame block)
```


Удалите указанный блок WebP из изображения, обеспечивая эффективное управление структурой данных изображения. Используйте этот метод для упрощения процессов обработки изображений, устраняя ненужные блоки или компоненты в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | Блок для удаления. |

--------------------

Примечание: не забудьте вызвать Dispose у `block`, если вы не собираетесь добавлять его в другой WebPImage. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Получает параметры на основе настроек оригинального файла. Это может быть полезно для сохранения глубины цвета и других параметров оригинального изображения без изменений. Например, если мы загружаем чёрно‑белое PNG‑изображение с 1 битом на пиксель и затем сохраняем его с помощью метода [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\\#save-String-), будет получено PNG‑изображение с 8‑битами на пиксель. Чтобы избежать этого и сохранить PNG‑изображение с 1‑битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их методу [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\\#save-String--ImageOptionsBase-) в качестве второго параметра.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Поверните изображение вокруг его центра на заданный угол, одновременно пропорционально изменяя его размер и применяя указанные параметры фонового цвета. Включите этот метод в ваш процесс обработки изображений для получения точных преобразований с настраиваемыми цветовыми фонами, обеспечивая оптимальное визуальное представление в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения в градусах. Положительные значения вращают по часовой стрелке. |
| resizeProportionally | boolean | если установить `true`, размер вашего изображения будет изменён в соответствии с проекциями повернутого прямоугольника (угловых точек); в противном случае размеры останутся неизменными, и будет вращено только `` содержимое изображения. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Цвет фона. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Измените размер изображения, корректируя его размеры при сохранении пропорций. Интегрируйте этот метод в ваш процесс обработки изображений для динамического масштабирования изображений под различные требования отображения или хранения в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| resizeType | int | Тип изменения размера. |


**Example: This example loads a WEBP image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.webp.WebPImage image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Увеличить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Уменьшить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Увеличить в 2 раза с использованием билинейного ресэмплинга.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Уменьшить в 2 раза с использованием билинейного ресэмплинга.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Пропорционально измените ширину изображения, сохраняя его пропорции. Интегрируйте этот метод в ваш процесс обработки изображений для динамического изменения размеров изображений с постоянными пропорциями, обеспечивая оптимальное отображение или хранение в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| resizeType | int | Тип масштабирования. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Пропорционально измените высоту изображения, сохраняя его пропорции для согласованного масштабирования. Интегрируйте этот метод в ваш процесс обработки изображений для динамического изменения размеров изображений с одинаковыми пропорциями, обеспечивая оптимальное отображение или хранение в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newHeight | int | Новая высота. |
| resizeType | int | Тип масштабирования. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Применяйте вращение, отражение или обе операции исключительно к активному кадру изображения. Интегрируйте этот метод в ваш процесс обработки изображений для точного управления отдельными кадрами, повышая гибкость и контроль над трансформациями кадров в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rotateFlipType | int | Тип вращения и отражения. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Выполните дизеринг текущего изображения, чтобы уменьшить цветовые полосы и улучшить визуальное качество. Интегрируйте этот метод в ваш процесс обработки изображений для более плавных переходов между цветами и улучшения общего внешнего вида изображения в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ditheringMethod | int | Метод дизеринга. |
| bitsCount | int | Окончательное количество бит для дизеринга. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Пользовательская палитра для дизеринга. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Обрежьте изображение, используя указанный прямоугольный регион, удаляя нежелательные части и сохраняя нужное содержимое. Интегрируйте этот метод в ваш процесс обработки изображений для точного извлечения и фокусировки на конкретных областях интереса в изображении, улучшая чёткость и композицию для различных приложений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Обрежьте изображение, применяя сдвиги слева, справа, сверху и снизу, эффективно выбирая область интереса в изображении. Используйте этот метод для динамического извлечения нужных частей изображения, одновременно корректируя его композицию и фокус в соответствии с требованиями вашего приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| leftShift | int | Левый сдвиг. |
| rightShift | int | Правый сдвиг. |
| topShift | int | Верхний сдвиг. |
| bottomShift | int | Нижний сдвиг. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Выполните бинаризацию изображения, используя предопределённое пороговое значение, преобразуя его в бинарное изображение, где пиксели классифицируются как передний план или фон в зависимости от их интенсивности относительно порога. Интегрируйте этот метод в ваш процесс обработки изображений для облегчения задач сегментации и извлечения признаков, повышая точность и эффективность последующего анализа в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | byte | Пороговое значение. Если соответствующее серое значение пикселя больше порога, ему будет присвоено значение (byte)255, иначе 0. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Выполните бинаризацию изображения с использованием метода пороговой обработки Оцу, автоматически определяя оптимальное значение порога на основе гистограммы изображения. Интегрируйте этот метод в ваш рабочий процесс обработки изображений, чтобы достичь эффективной сегментации и извлечения признаков, повышая точность и надёжность задач анализа изображений в вашем приложении.

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Примените бинаризацию к изображению с использованием адаптивного алгоритма пороговой обработки Брэдли и интегрального изображения. Этот метод динамически вычисляет локальные пороги на основе соседства пикселей изображения, повышая адаптивность к различным условиям освещения и обеспечивая надёжную сегментацию для последующих задач обработки в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightnessDifference | double | Разница яркости между пикселем и средним значением окна s × s пикселей, центрированного вокруг этого пикселя. |
| windowSize | int | Размер окна s × s пикселей, центрированного вокруг этого пикселя. |

### grayscale() {#grayscale--}
```
public void grayscale()
```


Примените бинаризацию к изображению с использованием адаптивного алгоритма пороговой обработки Брэдли и интегрального изображения. Этот метод динамически вычисляет локальные пороги на основе соседства пикселей изображения, повышая адаптивность к различным условиям освещения и обеспечивая надёжную сегментацию для последующих задач обработки в вашем приложении.

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Примените гамма‑коррекцию к изображению, регулируя интенсивность пикселей для достижения желаемой яркости и цветового баланса. Включите этот метод в ваш рабочий процесс обработки изображений, чтобы улучшить визуальное качество и повысить точность последующего анализа или отображения в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| гамма | float | Коэффициент гаммы для красного, зелёного и синего каналов |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Выполните гамма‑коррекцию изображения, используя отдельные коэффициенты для красного, зелёного и синего каналов, что позволяет точно настраивать цветовой баланс и контраст. Интегрируйте этот метод в конвейер обработки изображений, чтобы получить точный контроль над отображением цветов и повысить визуальную достоверность в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| gammaRed | float | Коэффициент гаммы для красного канала |
| gammaGreen | float | Коэффициент гаммы для зелёного канала |
| gammaBlue | float | Коэффициент гаммы для синего канала |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Реализуйте регулировку `brightness` для изображения, позволяя изменять общий уровень яркости. Включите этот метод в ваш конвейер обработки изображений, чтобы улучшить видимость и повысить визуальное качество изображений в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightness | int | Значение яркости. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Увеличьте контрастность [Image](../../com.aspose.imaging/image), усиливая различия между светлыми и тёмными областями. Интегрируйте этот метод в ваш рабочий процесс обработки изображений, чтобы улучшить визуальную чёткость и общее качество изображения в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| contrast | float | Значение контрастности (в диапазоне [-100; 100]) |

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Отфильтруйте содержимое в указанном прямоугольнике, применяя заданный фильтр обработки изображений для улучшения или изменения выбранного региона. Интегрируйте этот метод в ваш процесс манипуляции изображениями, чтобы достичь целевых улучшений или трансформаций в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Параметры. |


**Example: The following example applies various types of filters to a WEBP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Примените медианный фильтр с размером прямоугольника 5 ко всему изображению.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    webpImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Примените билатеральный сглаживающий фильтр с размером ядра 5 ко всему изображению.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    webpImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Примените гауссов фильтр размытия с радиусом 5 и значением sigma 4.0 ко всему изображению.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Примените фильтр Гаусса-Винера с радиусом 5 и значением smooth 4.0 ко всему изображению.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Примените фильтр движения Винера с длиной 5, значением smooth 4.0 и углом 90,0 градусов ко всему изображению.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    webpImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Примените фильтр резкости с размером ядра 5 и значением sigma 4.0 ко всему изображению.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Измените размер изображения в соответствии с указанными настройками, обеспечивая точный контроль над размерами, соотношением сторон и поведением масштабирования. Интегрируйте этот метод в ваш рабочий процесс обработки изображений, чтобы выполнить индивидуальные операции изменения размера, соответствующие конкретным требованиям вашего приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Настройки изменения размера. |

