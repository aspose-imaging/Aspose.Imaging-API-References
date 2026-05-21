---
title: "DataStreamSupporter"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Контейнер потока данных."
type: docs
weight: 39
url: /ru/java/com.aspose.imaging/datastreamsupporter/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public abstract class DataStreamSupporter extends DisposableObject
```

Контейнер потока данных.
## Методы

| Метод | Описание |
| --- | --- |
| [getDataStreamContainer()](#getDataStreamContainer--) | Получает поток данных объекта. |
| [isCached()](#isCached--) | Возвращает значение, указывающее, кэшированы ли данные объекта в данный момент и требуется ли чтение данных. |
| [cacheData()](#cacheData--) | Кеширует данные и гарантирует, что дополнительная загрузка данных из базового `DataStreamSupporter.DataStreamContainer` не будет выполнена. |
| [save()](#save--) | Сохраняет данные объекта в текущий `DataStreamSupporter`. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Сохраняет данные объекта в указанный поток. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Сохраняет данные объекта в указанный поток. |
| [save(String filePath)](#save-java.lang.String-) | Сохраняет данные объекта в указанное файловое расположение. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Сохраняет данные объекта в указанное файловое расположение. |
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Получает поток данных объекта.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - The object's data stream.
### isCached() {#isCached--}
```
public abstract boolean isCached()
```


Возвращает значение, указывающее, кэшированы ли данные объекта в данный момент и требуется ли чтение данных.

**Returns:**
boolean — значение, указывающее, кэшированы ли данные объекта в данный момент и требуется ли чтение данных.
### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


Кеширует данные и гарантирует, что дополнительная загрузка данных из базового `DataStreamSupporter.DataStreamContainer` не будет выполнена.


**Example: The following example shows how image caching affects performance.**
Следующий пример показывает, как кэширование изображений влияет на производительность. Как правило, чтение кэшированных данных происходит быстрее, чем чтение некэшированных данных.
``` java
String dir = "c:\\temp\\";

// Загрузить изображение из PNG‑файла.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Кешировать все данные пикселей, чтобы дополнительная загрузка данных из базового потока не выполнялась
    image.cacheData();

    long startTime = System.currentTimeMillis();

    // Чтение всех пикселей происходит довольно быстро.
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
    for (int y = 0; y < image.getHeight(); y++) {
        for (int x = 0; x < image.getWidth(); x++) {
            int color = rasterImage.getArgb32Pixel(x, y);
        }
    }

    long stopTime = System.currentTimeMillis();
    long elapsedTime = stopTime - startTime;
    System.out.println("Reading all cached pixels took " + elapsedTime + " ms.");
} finally {
    image.dispose();
}

// Загрузить изображение из PNG‑файла
image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    long startTime = System.currentTimeMillis();

    // Чтение всех пикселей не так быстро, как при кэшировании
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
    for (int y = 0; y < image.getHeight(); y++) {
        for (int x = 0; x < image.getWidth(); x++) {
            int color = rasterImage.getArgb32Pixel(x, y);
        }
    }

    long stopTime = System.currentTimeMillis();
    long elapsedTime = stopTime - startTime;
    System.out.println("Reading all pixels without preliminary caching took " + elapsedTime + " ms.");
} finally {
    image.dispose();
}

// Вывод может выглядеть так:
//Чтение всех кэшированных пикселей заняло 2954 мс.
//    java.lang.OutOfMemoryError
//at com.aspose.imaging.internal.G.be.b(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.aB.a(Unknown Source)
//at com.aspose.imaging.RasterImage.a(Unknown Source)
//at com.aspose.imaging.RasterImage.getArgb32Pixel(Unknown Source)
//at com.aspose.examples.ExamplesTest.Test(ExamplesTest.java:58)
```

### save() {#save--}
```
public void save()
```


Сохраняет данные объекта в текущий `DataStreamSupporter`.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Сохраняет данные объекта в указанный поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток, в который сохраняются данные объекта. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Сохраняет данные объекта в указанный поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| файл | java.io.RandomAccessFile | Поток, в который сохраняются данные объекта. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Сохраняет данные объекта в указанное файловое расположение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу, в который сохраняются данные объекта. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Сохраняет данные объекта в указанное файловое расположение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу, в который сохраняются данные объекта. |
| overWrite | boolean | если установлено `true`, перезаписать содержимое файла, иначе будет выполнено добавление. |

