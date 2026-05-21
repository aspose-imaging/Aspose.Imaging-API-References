---
title: "StreamContainer"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет контейнер потока, который содержит поток и предоставляет процедуры обработки потока."
type: docs
weight: 109
url: /ru/java/com.aspose.imaging/streamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class StreamContainer extends DisposableObject implements ISynchronizable
```

Представляет контейнер потока, который содержит поток и предоставляет процедуры обработки потока.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [StreamContainer(InputStream stream)](#StreamContainer-java.io.InputStream-) | Инициализирует новый экземпляр класса `StreamContainer`. |
| [StreamContainer(System.IO.Stream stream)](#StreamContainer-com.aspose.ms.System.IO.Stream-) | Инициализирует новый экземпляр класса `StreamContainer`. |
| [StreamContainer(InputStream stream, boolean disposeStream)](#StreamContainer-java.io.InputStream-boolean-) | Инициализирует новый экземпляр класса `StreamContainer`. |
| [StreamContainer(System.IO.Stream stream, boolean disposeStream)](#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-) | Инициализирует новый экземпляр класса `StreamContainer`. |
## Поля

| Поле | Описание |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | Указывает количество байтов для чтения и записи при последовательном чтении. |
## Методы

| Метод | Описание |
| --- | --- |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.imaging.StreamContainer-) | Выполняет явное преобразование из `com.aspose.imaging.StreamContainer` в `System.IO.Stream`. |
| [getSyncRoot()](#getSyncRoot--) | Получает объект, который может использоваться для синхронизации доступа к синхронизированному ресурсу. |
| [getPosition()](#getPosition--) | Получает или задает текущую позицию в потоке. |
| [setPosition(long value)](#setPosition-long-) | Получает или задает текущую позицию в потоке. |
| [getStream()](#getStream--) | Получает поток данных. |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | Получает значение, указывающее, будет ли поток освобожден при закрытии. |
| [getLength()](#getLength--) | Получает или задает длину потока в байтах. |
| [setLength(long value)](#setLength-long-) | Получает или задает длину потока в байтах. |
| [canRead()](#canRead--) | Получает значение, указывающее, поддерживает ли поток чтение. |
| [canSeek()](#canSeek--) | Получает значение, указывающее, поддерживает ли поток перемещение. |
| [canWrite()](#canWrite--) | Получает значение, указывающее, поддерживает ли поток запись. |
| [flush()](#flush--) | Очищает все буферы этого потока и заставляет любые буферизованные данные записаться в базовое устройство. |
| [write(byte[] bytes)](#write-byte---) | Записывает все указанные байты в поток. |
| [writeByte(byte value)](#writeByte-byte-) | Записывает байт в текущую позицию потока и перемещает позицию в потоке на один байт вперёд. |
| [read(byte[] bytes)](#read-byte---) | Читает байты, заполняя указанный буфер байтов. |
| [toBytes()](#toBytes--) | Преобразует данные потока в массив `byte`. |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | Преобразует данные потока в массив `byte`. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | Читает последовательность байтов из текущего потока и перемещает позицию в потоке на количество прочитанных байтов. |
| [readByte()](#readByte--) | Читает один байт из потока и перемещает позицию в потоке на один байт, либо возвращает -1, если достигнут конец потока. |
| [seek(long offset, int origin)](#seek-long-int-) | Устанавливает позицию в текущем потоке. |
| [seekBegin()](#seekBegin--) | Устанавливает позицию потока в начало потока. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | Записывает последовательность байтов в текущий поток и перемещает текущую позицию в этом потоке на количество записанных байтов. |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | Сохраняет (копирует) данные потока в указанный поток. |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | Сохраняет (копирует) все данные потока в указанный поток. |
| [save(OutputStream destinationStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | Сохраняет (копирует) данные потока в указанный поток. |
| [save(String filePath)](#save-java.lang.String-) | Сохраняет (копирует) данные потока в указанный поток. |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | Сохраняет (копирует) данные потока в указанный поток. |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | Сохраняет (копирует) данные потока в указанный поток. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.imaging.StreamContainer-) | Копирует содержащиеся данные в другой `StreamContainer`. |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.imaging.StreamContainer-long-) | Копирует содержащиеся данные в другой `StreamContainer`. |
### StreamContainer(InputStream stream) {#StreamContainer-java.io.InputStream-}
```
public StreamContainer(InputStream stream)
```


Инициализирует новый экземпляр класса `StreamContainer`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |

### StreamContainer(System.IO.Stream stream) {#StreamContainer-com.aspose.ms.System.IO.Stream-}
```
public StreamContainer(System.IO.Stream stream)
```


Инициализирует новый экземпляр класса `StreamContainer`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Поток. |

### StreamContainer(InputStream stream, boolean disposeStream) {#StreamContainer-java.io.InputStream-boolean-}
```
public StreamContainer(InputStream stream, boolean disposeStream)
```


Инициализирует новый экземпляр класса `StreamContainer`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток данных. |
| disposeStream | boolean | если установить в `true`, поток будет освобождён при освобождении контейнера. |

### StreamContainer(System.IO.Stream stream, boolean disposeStream) {#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamContainer(System.IO.Stream stream, boolean disposeStream)
```


Инициализирует новый экземпляр класса `StreamContainer`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Поток данных. |
| disposeStream | boolean | если установить в `true`, поток будет освобождён при освобождении контейнера. |

### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


Указывает количество байтов для чтения и записи при последовательном чтении.

### to_Stream(StreamContainer streamContainer) {#to-Stream-com.aspose.imaging.StreamContainer-}
```
public static System.IO.Stream to_Stream(StreamContainer streamContainer)
```


Выполняет явное преобразование из `com.aspose.imaging.StreamContainer` в `System.IO.Stream`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Контейнер потока. |

**Returns:**
com.aspose.ms.System.IO.Stream — результат преобразования.
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Получает объект, который может использоваться для синхронизации доступа к синхронизированному ресурсу.

Значение: Объект, который может использоваться для синхронизации доступа к синхронизируемому ресурсу.

**Returns:**
java.lang.Object
### getPosition() {#getPosition--}
```
public long getPosition()
```


Получает или задает текущую позицию в потоке. Это значение представляет смещение от начальной позиции потока, переданной в конструкторе StreamContainer.

Значение: Текущая позиция потока.

**Returns:**
long
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Получает или задает текущую позицию в потоке. Это значение представляет смещение от начальной позиции потока, переданной в конструкторе StreamContainer.

Значение: Текущая позиция потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getStream() {#getStream--}
```
public InputStream getStream()
```


Получает поток данных.

Значение: Поток данных.

**Returns:**
java.io.InputStream
### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


Получает значение, указывающее, будет ли поток освобожден при закрытии.

Значение: `true`, если поток освобождается при закрытии; иначе `false`.

**Returns:**
boolean
### getLength() {#getLength--}
```
public long getLength()
```


Получает или задает длину потока в байтах. Это значение меньше, чем Stream\#getLength().getLength(), на начальную позицию потока, переданную в конструкторе StreamContainer.

Значение: Длина потока.

**Returns:**
long
### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Получает или задает длину потока в байтах. Это значение меньше, чем Stream\#getLength().getLength(), на начальную позицию потока, переданную в конструкторе StreamContainer.

Значение: Длина потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### canRead() {#canRead--}
```
public boolean canRead()
```


Получает значение, указывающее, поддерживает ли поток чтение.

Значение: `true`, если поток поддерживает чтение; иначе `false`.

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Получает значение, указывающее, поддерживает ли поток перемещение.

Значение: `true`, если поток поддерживает перемещение; иначе `false`.

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Получает значение, указывающее, поддерживает ли поток запись.

Значение: `true`, если поток поддерживает запись; в противном случае `false`.

**Returns:**
boolean
### flush() {#flush--}
```
public void flush()
```


Очищает все буферы этого потока и заставляет любые буферизованные данные записаться в базовое устройство.

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


Записывает все указанные байты в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| байты | byte[] | Байты для записи. |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


Записывает байт в текущую позицию потока и перемещает позицию в потоке на один байт вперёд.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte | Байт для записи в поток. |

### read(byte[] bytes) {#read-byte---}
```
public int read(byte[] bytes)
```


Читает байты, заполняя указанный буфер байтов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| байты | byte[] | Байты для заполнения. |

**Returns:**
int - Количество прочитанных байтов. Это значение может быть меньше количества байтов в буфере, если в потоке недостаточно байтов.
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


Преобразует данные потока в массив `byte`.

**Returns:**
byte[] - Данные потока, преобразованные в массив `byte`.
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


Преобразует данные потока в массив `byte`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | long | Позиция, с которой начинать чтение байтов. |
| bytesCount | long | Количество байтов для чтения. |

**Returns:**
byte[] - Данные потока, преобразованные в массив `byte`.
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


Читает последовательность байтов из текущего потока и перемещает позицию в потоке на количество прочитанных байтов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | byte[] | Массив байтов. После возврата этого метода буфер содержит указанный массив байтов, где значения между `offset` и (`offset` + `count` - 1) заменены байтами, прочитанными из текущего источника. |
| offset | int | Нулевое байтовое смещение в `buffer`, с которого начинать сохранять данные, прочитанные из текущего потока. |
| count | int | Максимальное количество байтов, которое может быть прочитано из текущего потока. |

**Returns:**
int - Общее количество байтов, прочитанных в буфер. Это может быть меньше запрошенного количества байтов, если их в данный момент недоступно, или равно нулю (0), если достигнут конец потока.
### readByte() {#readByte--}
```
public int readByte()
```


Читает один байт из потока и перемещает позицию в потоке на один байт, либо возвращает -1, если достигнут конец потока.

**Returns:**
int - Беззнаковый байт, приведённый к Int32, или -1, если достигнут конец потока.
### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


Устанавливает позицию в текущем потоке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| offset | long | Байтовое смещение относительно параметра `origin`. Это значение представляет смещение от начальной позиции потока, переданной в конструктор StreamContainer. |
| origin | int | Значение типа `System.IO.SeekOrigin`, указывающее точку отсчёта, используемую для получения новой позиции. |

**Returns:**
long - Новая позиция внутри текущего потока.
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


Устанавливает позицию потока в начало потока. Это значение представляет смещение от начальной позиции потока, переданной в конструктор StreamContainer.

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


Записывает последовательность байтов в текущий поток и перемещает текущую позицию в этом потоке на количество записанных байтов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | byte[] | Массив байтов. Этот метод копирует `count` байтов из `buffer` в текущий поток. |
| offset | int | Нулевое байтовое смещение в `buffer`, с которого начинать копировать байты в текущий поток. |
| count | int | Количество байтов, которое будет записано в текущий поток. |

### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию `ReadWriteBytesCount` и значение `Length` потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Поток, в который сохраняются данные. |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


Сохраняет (копирует) все данные потока в указанный поток. Использует значение `Length` потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Поток, в который сохраняются данные. |
| bufferSize | int | Буфер. |

### save(OutputStream destinationStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream destinationStream, int bufferSize, long length)
```


Сохраняет (копирует) данные потока в указанный поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Поток, в который сохраняются данные. |
| bufferSize | int | Размер буфера. По умолчанию используется значение `ReadWriteBytesCount`. |
| length | long | Длина данных потока для копирования. По умолчанию длина устанавливается в значение `Length`. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию `ReadWriteBytesCount` и значение `Length` потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу, в который сохраняются данные потока. |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


Сохраняет (копирует) данные потока в указанный поток. Использует значение `Length` потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу, в который сохраняются данные потока. |
| bufferSize | int | Размер буфера. По умолчанию используется значение `ReadWriteBytesCount`. |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


Сохраняет (копирует) данные потока в указанный поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу, в который сохраняются данные потока. |
| bufferSize | int | Размер буфера. По умолчанию используется значение `ReadWriteBytesCount`. |
| length | long | Длина данных потока для копирования. По умолчанию длина устанавливается в значение `Length`. |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.imaging.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


Копирует содержащиеся данные в другой `StreamContainer`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Контейнер потока, в который копировать. |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.imaging.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


Копирует содержащиеся данные в другой `StreamContainer`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Контейнер потока, в который копировать. |
| length | long | Количество байтов для записи. |

