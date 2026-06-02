---
title: "StreamSource"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет потоковый источник."
type: docs
weight: 13
url: /ru/java/com.aspose.imaging.sources/streamsource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source)
```
public final class StreamSource extends Source
```

Представляет потоковый источник.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [StreamSource(System.IO.Stream stream)](#StreamSource-com.aspose.ms.System.IO.Stream-) | Инициализирует новый экземпляр класса `StreamSource`. |
| [StreamSource(InputStream stream)](#StreamSource-java.io.InputStream-) | Инициализирует новый экземпляр класса `StreamSource`. |
| [StreamSource(byte[] data)](#StreamSource-byte---) | Инициализирует новый экземпляр класса `StreamSource`. |
| [StreamSource(ByteBuffer buffer)](#StreamSource-java.nio.ByteBuffer-) | Инициализирует новый экземпляр класса `StreamSource`. |
| [StreamSource()](#StreamSource--) | Инициализирует новый экземпляр класса `StreamSource` с нулевым потоком. |
| [StreamSource(RandomAccessFile file)](#StreamSource-java.io.RandomAccessFile-) | Инициализирует новый экземпляр класса `StreamSource`. |
| [StreamSource(RandomAccessFile file, boolean disposeStream)](#StreamSource-java.io.RandomAccessFile-boolean-) | Инициализирует новый экземпляр класса `StreamSource`. |
| [StreamSource(System.IO.Stream stream, boolean disposeStream)](#StreamSource-com.aspose.ms.System.IO.Stream-boolean-) | Инициализирует новый экземпляр класса `StreamSource`. |
| [StreamSource(InputStream stream, boolean disposeStream)](#StreamSource-java.io.InputStream-boolean-) | Инициализирует новый экземпляр класса `StreamSource`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getStream()](#getStream--) | Получает поток. |
| [getDisposeStream()](#getDisposeStream--) | Получает значение, указывающее, следует ли освобождать поток каждый раз, когда освобождается контейнер. |
| [getStreamContainer()](#getStreamContainer--) | Получает контейнер потока. |

## Example: This example demonstrates how to use StreamSource to create a new Image file (a JPEG type)

``` java

//Создаёт экземпляр JpegOptions и задаёт его различные свойства
com.aspose.imaging.imageoptions.JpegOptions jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();

//Создайте экземпляр System.IO.Stream
java.io.InputStream stream = new java.io.FileInputStream("C:\\temp\\sample.jpeg");

// Определите свойство source для экземпляра JpegOptions
// Второй логический параметр определяет, будет ли поток освобождён после выхода из области видимости
jpegOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream, true));

// Создаёт экземпляр Image и вызывает метод Create, передавая JpegOptions в качестве параметра, чтобы инициализировать объект Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(jpegOptions, 500, 500);
try {
    // Выполните некоторую обработку изображения
} finally {
    image.dispose();
}
```

### StreamSource(System.IO.Stream stream) {#StreamSource-com.aspose.ms.System.IO.Stream-}
```
public StreamSource(System.IO.Stream stream)
```


Инициализирует новый экземпляр класса `StreamSource`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Поток для открытия. |

### StreamSource(InputStream stream) {#StreamSource-java.io.InputStream-}
```
public StreamSource(InputStream stream)
```


Инициализирует новый экземпляр класса `StreamSource`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток для открытия. |

### StreamSource(byte[] data) {#StreamSource-byte---}
```
public StreamSource(byte[] data)
```


Инициализирует новый экземпляр класса `StreamSource`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Массив байтов, в котором хранится изображение |

### StreamSource(ByteBuffer buffer) {#StreamSource-java.nio.ByteBuffer-}
```
public StreamSource(ByteBuffer buffer)
```


Инициализирует новый экземпляр класса `StreamSource`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | java.nio.ByteBuffer | Буфер ByteBuffer для хранения изображения |

### StreamSource() {#StreamSource--}
```
public StreamSource()
```


Инициализирует новый экземпляр класса `StreamSource` с нулевым потоком. Этот конструктор позволяет создавать новые изображения без входного потока, изображения хранятся только в памяти.

### StreamSource(RandomAccessFile file) {#StreamSource-java.io.RandomAccessFile-}
```
public StreamSource(RandomAccessFile file)
```


Инициализирует новый экземпляр класса `StreamSource`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| файл | java.io.RandomAccessFile | Файл для открытия. |

### StreamSource(RandomAccessFile file, boolean disposeStream) {#StreamSource-java.io.RandomAccessFile-boolean-}
```
public StreamSource(RandomAccessFile file, boolean disposeStream)
```


Инициализирует новый экземпляр класса `StreamSource`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| файл | java.io.RandomAccessFile | Файл для открытия. |
| disposeStream | boolean | если установить `true`, поток будет освобождён. |

### StreamSource(System.IO.Stream stream, boolean disposeStream) {#StreamSource-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamSource(System.IO.Stream stream, boolean disposeStream)
```


Инициализирует новый экземпляр класса `StreamSource`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Поток |
| disposeStream | boolean | если установить `true`, поток будет освобождён. |

### StreamSource(InputStream stream, boolean disposeStream) {#StreamSource-java.io.InputStream-boolean-}
```
public StreamSource(InputStream stream, boolean disposeStream)
```


Инициализирует новый экземпляр класса `StreamSource`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток для открытия. |
| disposeStream | boolean | если установить `true`, поток будет освобождён. |

### getStream() {#getStream--}
```
public System.IO.Stream getStream()
```


Получает поток.

**Returns:**
com.aspose.ms.System.IO.Stream - Поток.
### getDisposeStream() {#getDisposeStream--}
```
public boolean getDisposeStream()
```


Получает значение, указывающее, следует ли освобождать поток каждый раз, когда освобождается контейнер.

**Returns:**
boolean - `true`, если поток следует освобождать; иначе `false`.
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Получает контейнер потока.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

Используйте с осторожностью. После получения вам потребуется освободить контейнер потока.
