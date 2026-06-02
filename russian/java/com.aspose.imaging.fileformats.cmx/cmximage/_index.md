---
title: "CmxImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "API для Corel Metafile Exchange CMX формата векторных изображений с поддержкой описаний метаданных является комплексным решением для разработчиков, работающих с файлами CMX."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.cmx/cmximage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.ICmxImage](../../com.aspose.imaging.fileformats.cmx/icmximage)
```
public class CmxImage extends VectorMultipageImage implements ICmxImage
```

API для Corel Metafile Exchange (CMX) формата векторных изображений с поддержкой описаний метаданных является комплексным решением для разработчиков, работающих с файлами CMX. Этот API обеспечивает бесшовную загрузку изображений CMX, извлечение метаданных, таких как количество бит на пиксель, размеры объектов и многое другое. С дополнительными функциями, такими как изменение размера, вращение, установка палитр и конвертация в другие форматы, этот API позволяет разработчикам эффективно манипулировать и настраивать векторные изображения CMX в соответствии с их конкретными требованиями к приложению.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CmxImage(StreamContainer streamContainer, LoadOptions loadOptions)](#CmxImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Начните работать с классом [CmxImage](../../com.aspose.imaging.fileformats.cmx/cmximage) без проблем, инициализируя новый экземпляр с параметрами streamContainer и loadOptions. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Получите формат файла изображения без усилий с помощью этого удобного свойства. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получите битовую глубину изображения без усилий с помощью этого удобного свойства. |
| [getDefaultPage()](#getDefaultPage--) | Без усилий получите страницу по умолчанию изображения с помощью этого интуитивного свойства. |
| [isCached()](#isCached--) | Определите, кэшированы ли данные объекта в данный момент, исключив необходимость чтения данных. |
| [getWidthF()](#getWidthF--) | Получите ширину объекта в дюймах с помощью этого интуитивного свойства. |
| [getHeightF()](#getHeightF--) | Без усилий получите высоту объекта, измеренную в дюймах, с помощью этого удобного свойства. |
| [getDocument()](#getDocument--) | Без усилий получите CMX‑документ с помощью этого интуитивного свойства. |
| [getCmxPage()](#getCmxPage--) | Без усилий получите страницу CMX изображения с помощью этого интуитивного свойства. |
| [getPageCount()](#getPageCount--) | Получите общее количество страниц изображения с помощью этого интуитивного свойства. |
| [getPages()](#getPages--) | Беспрепятственно получите страницы изображения с помощью этого интуитивного свойства. |
| [cacheData()](#cacheData--) | Кешируйте данные, чтобы предотвратить дополнительную загрузку из базового источника [DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter) с помощью этого удобного метода. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Настройте цветовую палитру изображения с помощью этого интуитивного метода. |

## Example: The following example shows how to cache all pages of a CMX image.

``` java
String dir = "c:\\temp\\";

// Загрузить изображение из файла CMX.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // Этот вызов кэширует только страницу по умолчанию.
    image.cacheData();

    // Кэшировать все страницы, чтобы не происходила дополнительная загрузка данных из базового потока.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### CmxImage(StreamContainer streamContainer, LoadOptions loadOptions) {#CmxImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public CmxImage(StreamContainer streamContainer, LoadOptions loadOptions)
```


Начните работать с классом [CmxImage](../../com.aspose.imaging.fileformats.cmx/cmximage) без проблем, инициализируя новый экземпляр с параметрами streamContainer и loadOptions. Идеально подходит разработчикам, ищущим удобный способ загрузки CMX‑изображений из различных источников данных с возможностью настройки процесса загрузки по мере необходимости.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Контейнер потока. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Параметры загрузки. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Получите формат файла изображения без усилий с помощью этого удобного свойства. Идеально подходит разработчикам, желающим динамически определять формат своих изображений, обеспечивая совместимость и точную обработку в их приложениях.

**Returns:**
long - Формат файла [FileFormat.Cmx](../../com.aspose.imaging/fileformat\#Cmx)
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Получите битовую глубину изображения без усилий с помощью этого удобного свойства. Идеально подходит разработчикам, желающим определить уровень детализации или цветовую глубину своих изображений, обеспечивая точную обработку и манипуляцию.

**Returns:**
int — Количество бит на пиксель изображения.
### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Без усилий получите страницу по умолчанию изображения с помощью этого интуитивного свойства. Идеально подходит разработчикам, которым нужен быстрый доступ к основной странице изображения, обеспечивая эффективную навигацию и управление.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Определите, кэшированы ли данные объекта в данный момент, исключив необходимость чтения данных. Идеально подходит разработчикам, стремящимся оптимизировать производительность за счёт эффективного использования кэшированных данных, обеспечивая более быстрый доступ к информации об объекте.

**Returns:**
boolean — `true`, если данные объекта кэшированы; иначе `false`.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Получите ширину объекта в дюймах с помощью этого интуитивного свойства. Идеально подходит разработчикам, которым нужны точные измерения объектов в их приложениях, обеспечивая точную компоновку и представление.

**Returns:**
float - Ширина объекта в дюймах.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Без усилий получите высоту объекта, измеренную в дюймах, с помощью этого удобного свойства. Идеально подходит разработчикам, которым нужна точная информация о размерах для эффективной компоновки и представления в их приложениях.

**Returns:**
float - Высота объекта в дюймах.
### getDocument() {#getDocument--}
```
public final CmxDocument getDocument()
```


Без усилий получите CMX‑документ с помощью этого интуитивного свойства. Идеально подходит разработчикам, желающим получить доступ к CMX‑изображениям или изменить их, обеспечивая гибкость и эффективность в их приложениях.

**Returns:**
[CmxDocument](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxdocument) - The CMX document.
### getCmxPage() {#getCmxPage--}
```
public final CmxPage getCmxPage()
```


Без усилий получите страницу CMX изображения с помощью этого интуитивного свойства. Идеально подходит разработчикам, которым нужен быстрый доступ к отдельным страницам в CMX‑изображениях, обеспечивая эффективную навигацию и управление.

**Returns:**
[CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) - The CMX page.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Получите общее количество страниц изображения с помощью этого интуитивного свойства. Идеально подходит для разработчиков, желающих динамически управлять многостраничными изображениями, обеспечивая эффективную навигацию и манипуляцию содержимым изображения.

**Returns:**
int — количество страниц.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Получайте страницы изображения без труда с помощью этого интуитивного свойства. Идеально подходит для разработчиков, желающих получать доступ к отдельным страницам в многостраничных изображениях и манипулировать ими, обеспечивая эффективную навигацию и обработку.

**Returns:**
com.aspose.imaging.Image[] — страницы.

**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// Загрузить изображение из файла CMX.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // Этот вызов кэширует только страницу по умолчанию.
    image.cacheData();

    // Кэшировать все страницы, чтобы не происходила дополнительная загрузка данных из базового потока.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


Кешируйте данные, чтобы предотвратить дополнительную загрузку из базового источника [DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter) с помощью этого удобного метода. Идеально подходит для разработчиков, стремящихся оптимизировать производительность за счёт предварительной загрузки данных, обеспечивая более быстрый доступ и более плавную работу их приложений.


**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// Загрузить изображение из файла CMX.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // Этот вызов кэширует только страницу по умолчанию.
    image.cacheData();

    // Кэшировать все страницы, чтобы не происходила дополнительная загрузка данных из базового потока.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
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

