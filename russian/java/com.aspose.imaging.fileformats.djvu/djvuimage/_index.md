---
title: "DjvuImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Класс документа DjVu поддерживает графический файловый формат и обеспечивает бесшовное управление отсканированными документами и книгами, объединяя текст, рисунки, изображения и фотографии в едином формате."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.djvu/djvuimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)
```
public final class DjvuImage extends RasterCachedMultipageImage
```

Класс документа DjVu поддерживает графический файловый формат и обеспечивает бесшовное управление отсканированными документами и книгами, объединяя текст, рисунки, изображения и фотографии в едином формате. Поддерживая многополосные операции, вы можете эффективно получать уникальные идентификаторы документов, подсчитывать страницы, устанавливать активные страницы и извлекать конкретные страницы документа. Благодаря функциям изменения размера, вращения, дизеринга, обрезки, преобразования в градации серого, коррекции гаммы, настройкам и применению фильтров, этот класс позволяет точно манипулировать и улучшать изображения DjVu, удовлетворяя разнообразные потребности приложений с лёгкостью и точностью.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DjvuImage(InputStream stream)](#DjvuImage-java.io.InputStream-) | Начните работу с изображениями DjVu, инициализировав новый экземпляр класса [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage), используя параметр Stream. |
| [DjvuImage(InputStream stream, LoadOptions loadOptions)](#DjvuImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Начните работу с изображениями DjVu без проблем с помощью этого конструктора, который инициализирует новый экземпляр класса [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage), используя параметры Stream и LoadOptions. |
| [DjvuImage(System.IO.Stream stream, LoadOptions loadOptions)](#DjvuImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-) | Начните работу с изображениями DjVu без проблем с помощью этого конструктора, который инициализирует новый экземпляр класса [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage), используя параметры Stream и LoadOptions. |
## Поля

| Поле | Описание |
| --- | --- |
| [PropertyChanged](#PropertyChanged) | Происходит, когда значение свойства изменяется. |
## Методы

| Метод | Описание |
| --- | --- |
| [loadDocument(InputStream stream)](#loadDocument-java.io.InputStream-) | Загрузите ваш документ DjVu с помощью этого метода. |
| [loadDocument(InputStream stream, LoadOptions loadOptions)](#loadDocument-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Загружает документ. |
| [getIdentifier()](#getIdentifier--) | Получает уникальный идентификатор документа |
| [getPageCount()](#getPageCount--) | Получите общее количество страниц в вашей коллекции DjVu‑изображений с помощью этого свойства. |
| [getPages()](#getPages--) | Получите доступ к отдельным страницам вашей коллекции DjVu‑изображений с помощью этого свойства. |
| [getDjvuPages()](#getDjvuPages--) | Быстро получите все страницы, содержащиеся в вашем DjVu‑документе, используя это свойство. |
| [getActivePage()](#getActivePage--) | Перемещайтесь по вашему DjVu‑документу, получая или задавая текущую активную страницу с помощью этого свойства. |
| [setActivePage(DjvuPage value)](#setActivePage-com.aspose.imaging.fileformats.djvu.DjvuPage-) | Перемещайтесь по вашему DjVu‑документу, получая или задавая текущую активную страницу с помощью этого свойства. |
| [getFirstPage()](#getFirstPage--) | Получите доступ к первой странице вашего DjVu‑документа с этим свойством. |
| [getLastPage()](#getLastPage--) | Получите последнюю страницу вашего DjVu‑документа, используя это свойство. |
| [getNextPage()](#getNextPage--) | Перемещайтесь по вашему DjVu‑документу, получая следующую страницу с этим удобным свойством. |
| [getPreviousPage()](#getPreviousPage--) | Быстро перемещайтесь назад в вашем DjVu‑документе при просмотре или обработке, получая предыдущую страницу с этим удобным свойством. |
| [getFileFormat()](#getFileFormat--) | Получите информацию о формате файла, связанного с вашим DjVu‑изображением. |
| [hasAlpha()](#hasAlpha--) | Быстро определите, содержит ли ваш DjVu‑файл альфа‑канал. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Поверните изображение вокруг его центра с помощью метода Rotate класса RasterCachedMultipageImage. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Измените размер изображения с помощью метода `Resize`, предоставляющего простой и эффективный способ регулировать размеры ваших изображений в соответствии с вашими требованиями. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Метод `ResizeWidthProportionally` предлагает удобное решение для изменения ширины вашего изображения при сохранении его пропорций. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Метод `ResizeHeightProportionally` позволяет изменить высоту вашего изображения, сохраняя его пропорции. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Метод `RotateFlip` предоставляет универсальные возможности манипуляции вашим изображением, позволяя вращать, отражать или выполнять обе операции над активным кадром независимо. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Функция "Dither" применяет эффект дизеринга к вашему изображению, улучшая его визуальное качество за счёт снижения полосатости и улучшения переходов цветов. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | "Crop" обрезает ваше изображение, позволяя сосредоточиться на конкретных деталях или удалить нежелательные элементы, улучшая композицию и визуальное воздействие. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Обрезка со сдвигами позволяет точно настроить положение и размеры обрезанной области внутри изображения. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Бинаризация с предопределённым порогом упрощает сложные изображения до бинарных представлений, где пиксели классифицируются как чёрные или белые в зависимости от их интенсивности относительно указанного порогового значения. |
| [binarizeOtsu()](#binarizeOtsu--) | Бинаризация с использованием порогового метода Оцу — это техника, автоматически вычисляющая оптимальное пороговое значение на основе гистограммы изображения. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Бинаризация с использованием адаптивного порогового алгоритма Брэдли с интегральным изображением — метод, вычисляющий локальный порог для каждого пикселя на основе локального соседства. |
| [grayscale()](#grayscale--) | Преобразование в градации серого переводит изображение в чёрно‑белое представление, где интенсивность каждого пикселя представлена одним значением от чёрного до белого. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Гамма‑коррекция, специально для каналов красного, зелёного и синего, подразумевает отдельную настройку яркости каждого цветового компонента. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Гамма‑коррекция применяется к изображению с настраиваемыми параметрами для каналов красного, зелёного и синего, позволяя точно регулировать цветовой баланс и яркость. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Отрегулируйте `brightness` изображения, используя указанный параметр, обеспечивая контроль над уровнями яркости для оптимальной визуальной чёткости. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Улучшите контраст [Image](../../com.aspose.imaging/image), чтобы повысить визуальную чёткость и выделить детали с помощью этого метода, который регулирует разницу яркости между светлыми и тёмными областями. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Примените фильтры к указанной прямоугольной области изображения, чтобы улучшить или изменить его внешний вид. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Измените размер изображения до указанных ширины и высоты, при необходимости применяя дополнительные настройки. |
| [cacheData()](#cacheData--) | Кешируйте данные локально, чтобы оптимизировать производительность и уменьшить необходимость повторного получения данных из внешних источников. |

## Example: This example shows how to load a DJVU image from a file stream.

``` java
String dir = "c:\\temp\\";

// Загрузите изображение DJVU из файлового потока.
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
try {
    // Сохраните каждую страницу как отдельное PNG‑изображение.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
        // Сгенерируйте имя файла на основе номера страницы.
        String fileName = String.format("sample.%s.png", djvuPage.getPageNumber());
        djvuPage.save(dir + fileName, new com.aspose.imaging.imageoptions.PngOptions());
    }
} finally {
    djvuImage.dispose();
    stream.close();
}
```

### DjvuImage(InputStream stream) {#DjvuImage-java.io.InputStream-}
```
public DjvuImage(InputStream stream)
```


Начните работу с изображениями DjVu, инициализируя новый экземпляр класса [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) с параметром Stream. Идеально подходит для разработчиков, желающих бесшовно интегрировать обработку DjVu‑изображений в свои проекты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |

### DjvuImage(InputStream stream, LoadOptions loadOptions) {#DjvuImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public DjvuImage(InputStream stream, LoadOptions loadOptions)
```


Начните работу с изображениями DjVu без проблем с помощью этого конструктора, который инициализирует новый экземпляр класса [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) с параметрами Stream и LoadOptions. Идеально подходит для разработчиков, желающих точный контроль над параметрами загрузки DjVu‑изображений при сохранении простоты и эффективности.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого загружать. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Параметры загрузки. |

### DjvuImage(System.IO.Stream stream, LoadOptions loadOptions) {#DjvuImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-}
```
public DjvuImage(System.IO.Stream stream, LoadOptions loadOptions)
```


Начните работу с изображениями DjVu без проблем с помощью этого конструктора, который инициализирует новый экземпляр класса [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) с параметрами Stream и LoadOptions. Идеально подходит для разработчиков, желающих точный контроль над параметрами загрузки DjVu‑изображений при сохранении простоты и эффективности.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Поток, из которого загружать. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Параметры загрузки. |

### PropertyChanged {#PropertyChanged}
```
public final StdEvent<System.ComponentModel.PropertyChangedEventArgs> PropertyChanged
```


Происходит, когда значение свойства изменяется.

### loadDocument(InputStream stream) {#loadDocument-java.io.InputStream-}
```
public static DjvuImage loadDocument(InputStream stream)
```


Загрузите ваш DjVu‑документ с помощью этого метода. Упростите процесс, быстро получая доступ к DjVu‑файлам и импортируя их в приложение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) - Loaded djvu document
### loadDocument(InputStream stream, LoadOptions loadOptions) {#loadDocument-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static DjvuImage loadDocument(InputStream stream, LoadOptions loadOptions)
```


Загружает документ.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Параметры загрузки. |

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) - Loaded djvu document
### getIdentifier() {#getIdentifier--}
```
public int getIdentifier()
```


Получает уникальный идентификатор документа

**Returns:**
int — Идентификатор.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Получите общее количество страниц в вашей коллекции DjVu‑изображений с помощью этого свойства. Идеально для быстрой оценки объёма вашего документа или книги в формате DjVu. Повышайте эффективность рабочего процесса с точной информацией о количестве страниц.

**Returns:**
int — Количество страниц.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Получите доступ к отдельным страницам вашей коллекции DjVu‑изображений с помощью этого свойства. Упростите навигацию и манипуляцию вашим документом или книгой в формате DjVu, получая каждую страницу напрямую. Повышайте эффективность рабочего процесса с лёгким получением страниц.

**Returns:**
com.aspose.imaging.Image[] — Страницы.

**Example: This example shows how to load a DJVU image from a file stream.**

``` java
String dir = "c:\\temp\\";

// Загрузите изображение DJVU из файлового потока.
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
try {
    // Сохраните каждую страницу как отдельное PNG‑изображение.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
        // Сгенерируйте имя файла на основе номера страницы.
        String fileName = String.format("sample.%s.png", djvuPage.getPageNumber());
        djvuPage.save(dir + fileName, new com.aspose.imaging.imageoptions.PngOptions());
    }
} finally {
    djvuImage.dispose();
    stream.close();
}
```

### getDjvuPages() {#getDjvuPages--}
```
public DjvuPage[] getDjvuPages()
```


Быстро получите все страницы, содержащиеся в вашем DjVu‑документе, используя это свойство. Упростите процесс обработки документов, легко получая доступ к отдельным страницам в DjVu‑файлах и управляя ими. Повышайте эффективность и оптимизируйте задачи с удобным получением страниц.

**Returns:**
com.aspose.imaging.fileformats.djvu.DjvuPage[] — Страницы.
### getActivePage() {#getActivePage--}
```
public DjvuPage getActivePage()
```


Перемещайтесь по вашему DjVu‑документу, получая или задавая текущую активную страницу с помощью этого свойства. Бесшовно переключайтесь между страницами, чтобы сосредоточиться на конкретном содержимом и улучшить опыт просмотра документа.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage)

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Загрузите изображение DJVU из файлового потока.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//Вывод может выглядеть так:
//Общее количество страниц: 2
//Номер активной страницы:    1
//Номер первой страницы:     1
//Номер последней страницы:      2
//--------------------------------------------------
//Номер страницы:     1
//Размер страницы:       { Width = 2481, Height = 3508}
//Исходный формат страницы: RgbIndexed1Bpp, использовано каналов: 1
//--------------------------------------------------
//Номер страницы:     2
//Размер страницы:       { Width = 2481, Height = 3508}
//Исходный формат страницы: RgbIndexed1Bpp, использовано каналов: 1
```

### setActivePage(DjvuPage value) {#setActivePage-com.aspose.imaging.fileformats.djvu.DjvuPage-}
```
public void setActivePage(DjvuPage value)
```


Перемещайтесь по вашему DjVu‑документу, получая или задавая текущую активную страницу с помощью этого свойства. Бесшовно переключайтесь между страницами, чтобы сосредоточиться на конкретном содержимом и улучшить опыт просмотра документа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) | Активная страница. |

### getFirstPage() {#getFirstPage--}
```
public DjvuPage getFirstPage()
```


Получите первую страницу вашего DjVu‑документа с помощью этого свойства. Быстро получите начальную страницу, чтобы эффективно начать просмотр или обработку документа.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The first page.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Загрузите изображение DJVU из файлового потока.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//Вывод может выглядеть так:
//Общее количество страниц: 2
//Номер активной страницы:    1
//Номер первой страницы:     1
//Номер последней страницы:      2
//--------------------------------------------------
//Номер страницы:     1
//Размер страницы:       { Width = 2481, Height = 3508}
//Исходный формат страницы: RgbIndexed1Bpp, использовано каналов: 1
//--------------------------------------------------
//Номер страницы:     2
//Размер страницы:       { Width = 2481, Height = 3508}
//Исходный формат страницы: RgbIndexed1Bpp, использовано каналов: 1
```

### getLastPage() {#getLastPage--}
```
public DjvuPage getLastPage()
```


Получите последнюю страницу вашего DjVu‑документа с помощью этого свойства. Быстро получите финальную страницу для просмотра или обработки без усилий.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The last page.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Загрузите изображение DJVU из файлового потока.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//Вывод может выглядеть так:
//Общее количество страниц: 2
//Номер активной страницы:    1
//Номер первой страницы:     1
//Номер последней страницы:      2
//--------------------------------------------------
//Номер страницы:     1
//Размер страницы:       { Width = 2481, Height = 3508}
//Исходный формат страницы: RgbIndexed1Bpp, использовано каналов: 1
//--------------------------------------------------
//Номер страницы:     2
//Размер страницы:       { Width = 2481, Height = 3508}
//Исходный формат страницы: RgbIndexed1Bpp, использовано каналов: 1
```

### getNextPage() {#getNextPage--}
```
public DjvuPage getNextPage()
```


Перемещайтесь по вашему DjVu‑документу, получая следующую страницу с помощью этого удобного свойства. Быстро продвигайтесь вперёд в задачах просмотра или обработки документа.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The next page.
### getPreviousPage() {#getPreviousPage--}
```
public DjvuPage getPreviousPage()
```


Быстро перемещайтесь назад в задачах просмотра или обработки DjVu‑документа, получая предыдущую страницу с помощью этого удобного свойства. Эффективно навигируйте по документу без труда.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The previous page.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Получите информацию о формате файла, связанного с вашим DjVu‑изображением. Быстро определите формат файла для бесшовной интеграции в ваш рабочий процесс.

**Returns:**
long
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Быстро определите, содержит ли ваш DjVu‑изображение альфа‑канал. Упростите рабочий процесс, проверяя наличие информации о прозрачности в ваших изображениях.

**Returns:**
boolean - Имеет альфа‑канал.
### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Поверните изображение вокруг его центра с помощью метода Rotate класса RasterCachedMultipageImage. Эта удобная функция позволяет легко регулировать ориентацию изображений, сохраняя их центральное положение, улучшая возможности манипулирования изображениями.

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


Измените размер изображения с помощью метода \`Resize\`, предоставляющего простой и эффективный способ корректировать размеры ваших изображений в соответствии с вашими требованиями. Эта универсальная функциональность позволяет легко масштабировать изображения до нужного размера, повышая их пригодность на различных платформах и в приложениях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| resizeType | int | Тип изменения размера. |


**Example: This example loads a DJVU image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Увеличить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Уменьшить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Увеличить в 2 раза с использованием билинейного ресэмплинга.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
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


Метод \`ResizeWidthProportionally\` предлагает удобное решение для изменения ширины вашего изображения при сохранении его пропорций. Пропорционально изменяя ширину, вы можете обеспечить визуальную привлекательность и согласованность изображений на разных устройствах и экранах, повышая их универсальность и пригодность в различных контекстах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| resizeType | int | Тип масштабирования. |


**Example: This example loads a DJVU image and resizes it proportionally using various resizing methods.**
В этом примере загружается изображение DJVU и пропорционально изменяется его размер с использованием различных методов масштабирования. Указывается только ширина, высота рассчитывается автоматически.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Увеличить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Уменьшить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Увеличить в 2 раза с использованием билинейного ресэмплинга.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Уменьшить в 2 раза с использованием билинейного ресэмплинга.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Метод \`ResizeHeightProportionally\` позволяет изменить высоту вашего изображения, сохраняя его пропорции. Это гарантирует, что изображение сохраняет свои соотношения, предотвращая искажения и сохраняя визуальную целостность. Независимо от того, оптимизируете ли вы изображения для веб-страниц, мобильных приложений или печатных материалов, этот метод обеспечивает наилучший вид ваших изображений на разных платформах и устройствах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newHeight | int | Новая высота. |
| resizeType | int | Тип масштабирования. |


**Example: This example loads a DJVU image and resizes it proportionally using various resizing methods.**
В этом примере загружается изображение DJVU и пропорционально изменяется его размер с использованием различных методов масштабирования. Указывается только высота, ширина рассчитывается автоматически.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Увеличить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Уменьшить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Увеличить в 2 раза с использованием билинейного ресэмплинга.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Уменьшить в 2 раза с использованием билинейного ресэмплинга.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Метод \`RotateFlip\` предлагает разнообразные варианты манипуляций с изображением, позволяя независимо вращать, отражать или выполнять обе операции над активным кадром. Независимо от того, редактируете ли вы фотографии, создаёте графику или улучшаете цифровое искусство, этот метод обеспечивает точный контроль над ориентацией и композицией ваших изображений, гарантируя соответствие вашему творческому замыслу с лёгкостью и эффективностью.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rotateFlipType | int | Тип поворота и отражения. |


**Example: This example loads a DJVU image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
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
    com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + rotateFlipType + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Функция "Dither" применяет эффект дизеринга к вашему изображению, улучшая его визуальное качество за счёт снижения полосатости и улучшения переходов цветов. Независимо от того, работаете ли вы над цифровым искусством, фотографией или проектами графического дизайна, эта функция придаёт изображениям профессиональный вид, делая их более плавными и изысканными.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ditheringMethod | int | Метод дизеринга. |
| bitsCount | int | Окончательное количество бит для дизеринга. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Пользовательская палитра для дизеринга. |


**Example: The following example loads a DJVU image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage dicomImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Выполнить пороговое дизеринг с использованием 4-битовой цветовой палитры, содержащей 16 цветов.
    // Чем больше указано бит, тем выше качество и тем больше размер выходного изображения.
    // Обратите внимание, что в данный момент поддерживаются только 1-битовые, 4-битовые и 8-битовые палитры.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage dicomImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Выполнить дизеринг Флойда с использованием 1-битовой цветовой палитры, содержащей только 2 цвета — черный и белый.
    // Чем больше указано бит, тем выше качество и тем больше размер выходного изображения.
    // Обратите внимание, что в данный момент поддерживаются только 1-битовые, 4-битовые и 8-битовые палитры.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


"Crop" обрезает ваше изображение, позволяя сосредоточиться на конкретных деталях или удалить нежелательные элементы, улучшая композицию и визуальное воздействие. Независимо от того, подгоняете ли вы фотографии для социальных сетей, создаёте баннеры для сайта или разрабатываете печатные материалы, этот инструмент помогает точно и ясно улучшать ваши изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник. |


**Example: The following example crops a DJVU image.**
В следующем примере изображение DJVU обрезается. Область обрезки указывается через Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Обрежьте изображение. Область обрезки — прямоугольный центральный участок изображения.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            djvuImage.getWidth() / 4, djvuImage.getHeight() / 4, djvuImage.getWidth() / 2, djvuImage.getHeight() / 2);
    djvuImage.crop(area);

    // Сохраните обрезанное изображение в PNG
    djvuImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Обрезка со сдвигами позволяет точно регулировать положение и размеры обрезаемой области внутри изображения. Эта функция незаменима для уточнения композиций, выравнивания элементов и акцентирования точек фокуса в визуальном материале. Включив сдвиги в процесс обрезки, вы можете достичь пиксельной точности и тонко настроить кадрирование изображений с лёгкостью.

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


Бинаризация с предопределённым порогом упрощает сложные изображения до бинарных представлений, где пиксели классифицируются как чёрные или белые в зависимости от их интенсивности относительно заданного порогового значения. Эта техника часто используется в обработке изображений для повышения чёткости, упрощения анализа и подготовки изображений к дальнейшим этапам обработки, таким как оптическое распознавание символов (OCR). Применяя фиксированный порог, вы можете быстро преобразовать градации серого в бинарную форму, делая их легче интерпретируемыми и позволяя извлекать значимую информацию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | byte | Значение порога. Если соответствующее серое значение пикселя больше порога, ему будет присвоено значение 255, иначе — 0. |


**Example: The following example binarizes a DJVU image with the predefined threshold.**
В следующем примере изображение DJVU бинаризуется с предопределённым порогом. Бинарные изображения содержат только 2 цвета — чёрный и белый.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

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


Бинаризация с использованием пороговой обработки по Оцу — это техника, автоматически вычисляющая оптимальное пороговое значение на основе гистограммы изображения. Она разделяет изображение на передний план и фон, минимизируя внутриклассовую дисперсию. Метод Оцу широко применяется для сегментации изображений в бинарную форму, особенно когда распределение интенсивностей пикселей бимодально или мультимодально. Такой подход полезен для задач, таких как обнаружение объектов, сегментация изображений и извлечение признаков, где точное разграничение между передним планом и фоном имеет решающее значение.


**Example: The following example binarizes a DJVU image with Otsu thresholding.**
В следующем примере изображение DJVU бинаризуется с пороговой обработкой по Оцу. Бинарные изображения содержат только 2 цвета — чёрный и белый.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Бинаризуйте изображение с пороговой обработкой Оцу.
    djvuImage.binarizeOtsu();
    djvuImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Бинаризация с использованием адаптивного порогового алгоритма Брэдли и пороговой обработки интегрального изображения — это метод, вычисляющий локальный порог для каждого пикселя на основе локального соседства. Он адаптируется к изменениям освещённости по всему изображению, что делает его подходящим для изображений с неравномерным освещением. Вычисляя порог с помощью интегральных изображений, метод эффективно обрабатывает большие области, что позволяет применять его в реальном времени. Эта техника часто используется в обработке документов, OCR (оптическое распознавание символов) и задачах сегментации изображений, где точная бинаризация необходима для последующего анализа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightnessDifference | double | Разница яркости между пикселем и средним значением окна s × s пикселей, центрированного вокруг этого пикселя. |
| windowSize | int | Размер окна s × s пикселей, центрированного вокруг этого пикселя. |


**Example: The following example binarizes a DJVU image with Bradley's adaptive thresholding algorithm with the specified window size.**
В следующем примере изображение DJVU бинаризуется с адаптивным пороговым алгоритмом Брэдли при указанном размере окна. Бинарные изображения содержат только 2 цвета — чёрный и белый.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Бинаризуйте изображение с разницей яркости 5. Яркость определяется как разница между пикселем и средним значением 10 × 10 окна пикселей, центрированного вокруг этого пикселя.
    djvuImage.binarizeBradley(5, 10);
    djvuImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


Преобразование в градации серого переводит изображение в чёрно‑белое представление, где интенсивность каждого пикселя задаётся одним значением от чёрного до белого. Этот процесс удаляет цветовую информацию, создавая монохромное изображение. Изображения в градациях серого часто используются в приложениях, где цвет не нужен или предпочтительна простота, например при сканировании документов, печати и некоторых типах анализа изображений.


**Example: The following example transforms a colored DJVU image to its grayscale representation.**
В следующем примере цветное изображение DJVU преобразуется в его градацию серого. Изображения в градациях серого состоят исключительно из оттенков серого и содержат только информацию об интенсивности.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    djvuImage.grayscale();
    djvuImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Гамма‑коррекция, специально для каналов красного, зелёного и синего, подразумевает отдельную настройку яркости каждого цветового компонента. Применяя разные коэффициенты гаммы к каналам RGB, вы можете точно настроить общую яркость и контраст изображения. Эта техника обеспечивает точное воспроизведение цветов и улучшает визуальное качество изображения на разных дисплейных устройствах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| гамма | float | Коэффициент гаммы для красного, зелёного и синего каналов |


**Example: The following example performs gamma-correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Установите коэффициент гаммы для красного, зелёного и синего каналов.
    djvuImage.adjustGamma(2.5f);
    djvuImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Гамма‑коррекция применяется к изображению с настраиваемыми параметрами для каналов красного, зелёного и синего, позволяя точно регулировать цветовой баланс и яркость. Этот метод повышает качество изображения, тонко настраивая представление цветов и обеспечивая оптимальную визуализацию на разных дисплейных устройствах. Регулировка значений гаммы для отдельных каналов улучшает цветовой баланс и визуальную привлекательность.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| gammaRed | float | Коэффициент гаммы для красного канала |
| gammaGreen | float | Коэффициент гаммы для зелёного канала |
| gammaBlue | float | Коэффициент гаммы для синего канала |


**Example: The following example performs gamma-correction of a DJVU image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Установите отдельные коэффициенты гаммы для красного, зелёного и синего каналов.
    djvuImage.adjustGamma(1.5f, 2.5f, 3.5f);
    djvuImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Отрегулируйте `brightness` изображения, используя указанный параметр, предоставляя контроль над уровнем яркости для оптимальной визуальной чёткости. Этот метод повышает или уменьшает общую яркость изображения, позволяя выполнять точные настройки для достижения желаемых световых эффектов. Модулируя яркость, пользователи могут оптимизировать видимость изображения и улучшить воспроизведение деталей, улучшая восприятие.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightness | int | Значение яркости. |


**Example: The following example performs brightness correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Установите значение яркости. Допустимые значения яркости находятся в диапазоне [-255, 255].
    djvuImage.adjustBrightness(50);
    djvuImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Улучшите контраст [Image](../../com.aspose.imaging/image), чтобы повысить визуальную чёткость и выделить детали с помощью этого метода, который регулирует разницу яркости между светлыми и тёмными областями. Точно настраивая уровни контраста, пользователи могут получить более яркие и выразительные изображения, улучшая общую качество и максимизируя видимость деталей. Эта настройка помогает раскрыть тонкие нюансы цвета и текстуры, создавая более динамичные и визуально привлекательные изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| contrast | float | Значение контрастности (в диапазоне [-100; 100]) |


**Example: The following example performs contrast correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Установите значение контрастности. Допустимые значения контрастности находятся в диапазоне [-100f, 100f].
    djvuImage.adjustContrast(50f);
    djvuImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Примените фильтры к указанной прямоугольной области изображения, чтобы улучшить или изменить его внешний вид. Нацеливая конкретные регионы, этот метод позволяет выполнять точные настройки, такие как размытие, резкость или применение художественных эффектов, для достижения желаемого визуального результата. Точная настройка фильтров в выбранных областях даёт пользователям возможность кастомизировать эстетику изображения, улучшать чёткость и создавать художественные эффекты, соответствующие их предпочтениям.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Параметры. |


**Example: The following example applies various types of filters to a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Примените медианный фильтр с размером прямоугольника 5 ко всему изображению.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    djvuImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Примените билатеральный сглаживающий фильтр с размером ядра 5 ко всему изображению.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    djvuImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Примените гауссов фильтр размытия с радиусом 5 и значением sigma 4.0 ко всему изображению.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Примените фильтр Гаусса-Винера с радиусом 5 и значением smooth 4.0 ко всему изображению.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Примените фильтр движения Винера с длиной 5, значением smooth 4.0 и углом 90,0 градусов ко всему изображению.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    djvuImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Примените фильтр резкости с размером ядра 5 и значением sigma 4.0 ко всему изображению.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Измените размер изображения до указанных ширины и высоты, при необходимости применяя дополнительные настройки. Этот метод позволяет пользователям корректировать размеры изображения, сохраняя желаемые свойства, такие как соотношение сторон, качество изображения и параметры сжатия. Предоставляя гибкость в параметрах изменения размера, пользователи могут адаптировать изображение под конкретные требования и оптимизировать его внешний вид для различных приложений и платформ.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Настройки изменения размера. |


**Example: This example loads a DJVU image and resizes it using various resizing settings.**

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

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Уменьшить в 2 раза с помощью адаптивного пересэмплинга.
    djvuImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Сохранить в PNG
    djvuImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


Кешируйте данные локально, чтобы оптимизировать производительность и уменьшить необходимость повторного получения данных из внешних источников. Такой подход также помогает экономить ресурсы, особенно в сценариях, где доступ к данным частый или ресурсы ограничены.


**Example: The following example shows how to cache all pages of a DJVU image.**

``` java
String dir = "c:\\temp\\";

// Загрузите изображение из файла DJVU.
com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Этот вызов кэширует все страницы, чтобы не происходила дополнительная загрузка данных из базового потока данных.
    image.cacheData();

    // Или вы можете кэшировать страницы по отдельности.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

