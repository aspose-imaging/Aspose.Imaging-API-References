---
title: "CdrImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "API поддержки векторного формата изображений CorelDRAW CDR является необходимым набором инструментов для разработчиков, работающих с векторной графикой."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.cdr/cdrimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cdr.ICdrImage](../../com.aspose.imaging.fileformats.cdr/icdrimage)
```
public class CdrImage extends VectorMultipageImage implements ICdrImage
```

API для поддержки векторного формата изображений CorelDRAW CDR является необходимым набором инструментов для разработчиков, работающих с векторной графикой. Этот API обеспечивает бесшовную обработку файлов CDR, позволяя хранить и манипулировать различными элементами, такими как текст, линии, формы, изображения, цвета и эффекты. Благодаря своим всесторонним возможностям разработчики могут эффективно работать с векторными представлениями содержимого изображений, обеспечивая точность и гибкость при программном создании и редактировании векторной графики CorelDRAW.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CdrImage(InputStream stream, LoadOptions loadOptions)](#CdrImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Начните работать с классом [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) без усилий, инициализировав новый экземпляр с параметрами stream и loadOptions. |
| [CdrImage(System.IO.Stream stream, LoadOptions loadOptions)](#CdrImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-) | Начните работать с классом [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) без усилий, инициализировав новый экземпляр с параметрами stream и loadOptions. |
## Методы

| Метод | Описание |
| --- | --- |
| [getDefaultPage()](#getDefaultPage--) | Получите страницу по умолчанию изображения с легкостью, используя это удобное свойство. |
| [isCached()](#isCached--) | Легко определите, кэшированы ли данные объекта в данный момент, исключив необходимость чтения данных. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получите битовую глубину изображения без усилий с помощью этого удобного свойства. |
| [getPageCount()](#getPageCount--) | Легко получайте или изменяйте общее количество страниц изображения с помощью этого интуитивного свойства. |
| [getPages()](#getPages--) | Беспрепятственно получите страницы изображения с помощью этого интуитивного свойства. |
| [getCdrDocument()](#getCdrDocument--) | Легко получайте или изменяйте документ CDR, используя это интуитивное свойство. |
| [getFileFormat()](#getFileFormat--) | Легко получайте формат файла изображения с помощью этого интуитивного свойства. |
| [getWidth()](#getWidth--) | Получает ширину изображения. |
| [getHeight()](#getHeight--) | Получает высоту изображения. |
| [cacheData()](#cacheData--) | Легко кэшируйте данные, чтобы предотвратить дополнительную загрузку из исходного источника, используя этот удобный метод. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Настройте цветовую палитру изображения с помощью этого интуитивного метода. |

## Example: The following example shows how to cache all pages of a CDR image.

``` java
String dir = "c:\\temp\\";

// Загрузите изображение из файла CDR.
com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(dir + "sample.cdr");
try {
    // Этот вызов кэширует только страницу по умолчанию.
    image.cacheData();

    // Кэшировать все страницы, чтобы не происходила дополнительная загрузка данных из базового потока.
    for (com.aspose.imaging.fileformats.cdr.CdrImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### CdrImage(InputStream stream, LoadOptions loadOptions) {#CdrImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public CdrImage(InputStream stream, LoadOptions loadOptions)
```


Начните работать с классом [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) без усилий, инициализировав новый экземпляр с параметрами stream и loadOptions. Идеально подходит для разработчиков, ищущих удобный способ загрузки изображений CDR из различных источников данных с возможностью настройки процесса загрузки по необходимости.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Параметры загрузки. |

### CdrImage(System.IO.Stream stream, LoadOptions loadOptions) {#CdrImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-}
```
public CdrImage(System.IO.Stream stream, LoadOptions loadOptions)
```


Начните работать с классом [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) без усилий, инициализировав новый экземпляр с параметрами stream и loadOptions. Идеально подходит для разработчиков, ищущих удобный способ загрузки изображений CDR из различных источников данных с возможностью настройки процесса загрузки по необходимости.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Поток. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Параметры загрузки. |

### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Получите страницу по умолчанию изображения с легкостью, используя это удобное свойство. Идеально подходит для разработчиков, желающих быстро получить доступ к основной странице изображения, обеспечивая эффективную навигацию и управление.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Легко определите, кэшированы ли данные объекта в данный момент, исключив необходимость чтения данных. Идеально подходит для разработчиков, стремящихся оптимизировать производительность, эффективно используя кэшированные данные, обеспечивая более быстрый доступ к информации об объекте.

**Returns:**
boolean — `true`, если данные объекта кэшированы; иначе `false`.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Получите битовую глубину изображения без усилий с помощью этого удобного свойства. Идеально подходит разработчикам, желающим определить уровень детализации или цветовую глубину своих изображений, обеспечивая точную обработку и манипуляцию.

**Returns:**
int — Количество бит на пиксель изображения.
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Легко получайте или изменяйте общее количество страниц изображения с помощью этого интуитивного свойства. Идеально подходит для разработчиков, желающих динамически управлять многостраничными изображениями, обеспечивая эффективную навигацию и манипуляцию содержимым изображения.

**Returns:**
int — количество страниц.
### getPages() {#getPages--}
```
public final Image[] getPages()
```


Получайте страницы изображения без труда с помощью этого интуитивного свойства. Идеально подходит для разработчиков, желающих получать доступ к отдельным страницам в многостраничных изображениях и манипулировать ими, обеспечивая эффективную навигацию и обработку.

**Returns:**
com.aspose.imaging.Image[] — страницы.

**Example: The following example shows how to export a single page of CDR document to PDF.**

``` java
int pageNumber = 0;
String dir = "c:\\aspose.imaging\\java\\issues\\1445'\\";
String inputCdrFileName = dir + "tiger.cdr";
String outputPdfFileName = dir + "tiger.cdr.page" + pageNumber + ".pdf";

com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(inputCdrFileName);
try {
    com.aspose.imaging.Image imagePage = image.getPages()[pageNumber];

    com.aspose.imaging.imageoptions.PdfOptions pdfOptions = new com.aspose.imaging.imageoptions.PdfOptions();
    com.aspose.imaging.imageoptions.CdrRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.CdrRasterizationOptions();
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    rasterizationOptions.setPageWidth(image.getWidth());
    rasterizationOptions.setPageHeight(image.getHeight());

    pdfOptions.setVectorRasterizationOptions(rasterizationOptions);

    imagePage.save(outputPdfFileName, pdfOptions);
}
finally {
    image.close();
}
```

### getCdrDocument() {#getCdrDocument--}
```
public final CdrDocument getCdrDocument()
```


Легко получайте или изменяйте документ CDR, используя это интуитивное свойство. Идеально подходит для разработчиков, желающих получить доступ к документу CDR или изменить его, обеспечивая гибкость и эффективность в их приложениях.

**Returns:**
[CdrDocument](../../com.aspose.imaging.fileformats.cdr.objects/cdrdocument) - the CDR document.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Легко получайте формат файла изображения с помощью этого интуитивного свойства. Идеально подходит для разработчиков, желающих динамически определять формат своих изображений, обеспечивая совместимость и точную обработку в их приложениях.

**Returns:**
long
### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает ширину изображения.

Значение: ширина изображения.

**Returns:**
int — ширина изображения.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Получает высоту изображения.

Значение: высота изображения.

**Returns:**
int — высота изображения.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Легко кэшируйте данные, чтобы предотвратить дополнительную загрузку из исходного источника, используя этот удобный метод. Идеально подходит для разработчиков, стремящихся оптимизировать производительность путем предварительной загрузки данных, обеспечивая более быстрый доступ и более плавную работу их приложений. `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)/[DataStreamSupporter.setDataStreamContainer\_internalized(StreamContainer)](../../com.aspose.imaging/datastreamsupporter\#setDataStreamContainer-internalized-StreamContainer-)).


**Example: The following example shows how to cache all pages of a CDR image.**

``` java
String dir = "c:\\temp\\";

// Загрузите изображение из файла CDR.
com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(dir + "sample.cdr");
try {
    // Этот вызов кэширует только страницу по умолчанию.
    image.cacheData();

    // Кэшировать все страницы, чтобы не происходила дополнительная загрузка данных из базового потока.
    for (com.aspose.imaging.fileformats.cdr.CdrImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Настройте цветовую палитру изображения с помощью этого интуитивного метода. Идеально подходит для разработчиков, желающих динамически применять определённые цветовые схемы или коррекции, обеспечивая точный контроль над визуальным видом их изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Палитра для установки. |
| updateColors | boolean | Если установить значение `true`, цвета будут обновлены в соответствии с новой палитрой; в противном случае индексы цветов останутся неизменными. Обратите внимание, что неизменные индексы могут привести к сбою изображения при загрузке, если некоторые индексы не имеют соответствующих записей в палитре. |

