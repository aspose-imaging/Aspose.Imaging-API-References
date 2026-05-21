---
title: "SplitStreamContainer"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет контейнер разделённого потока, который содержит поток и предоставляет процедуры обработки потока."
type: docs
weight: 108
url: /ru/java/com.aspose.imaging/splitstreamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.StreamContainer](../../com.aspose.imaging/streamcontainer)
```
public class SplitStreamContainer extends StreamContainer
```

Представляет контейнер разделённого потока, который содержит поток и предоставляет процедуры обработки потока.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SplitStreamContainer(InputStream stream)](#SplitStreamContainer-java.io.InputStream-) | Инициализирует новый экземпляр класса `SplitStreamContainer`. |
| [SplitStreamContainer(InputStream stream, boolean disposeStream)](#SplitStreamContainer-java.io.InputStream-boolean-) | Инициализирует новый экземпляр класса `SplitStreamContainer`. |
| [SplitStreamContainer(StreamContainer stream, boolean disposeStream)](#SplitStreamContainer-com.aspose.imaging.StreamContainer-boolean-) | Инициализирует новый экземпляр класса `SplitStreamContainer`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getSyncRoot()](#getSyncRoot--) | Получает объект, который может использоваться для синхронизации доступа к синхронизированному ресурсу. |
| [getPosition()](#getPosition--) | Получает текущую позицию в потоке. |
| [setPosition(long value)](#setPosition-long-) | Устанавливает текущую позицию в потоке. |
| [getLength()](#getLength--) | Получает длину потока в байтах. |
| [setLength(long value)](#setLength-long-) | Устанавливает длину потока в байтах. |
| [canRead()](#canRead--) | Получает значение, указывающее, поддерживает ли поток чтение. |
| [canSeek()](#canSeek--) | Получает значение, указывающее, поддерживает ли поток перемещение. |
| [canWrite()](#canWrite--) | Получает значение, указывающее, поддерживает ли поток запись. |
| [insert(int position, StreamContainer stream, boolean disposeStream)](#insert-int-com.aspose.imaging.StreamContainer-boolean-) | Вставляет контейнер потока в указанную позицию. |
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
### SplitStreamContainer(InputStream stream) {#SplitStreamContainer-java.io.InputStream-}
```
public SplitStreamContainer(InputStream stream)
```


Инициализирует новый экземпляр класса `SplitStreamContainer`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |

### SplitStreamContainer(InputStream stream, boolean disposeStream) {#SplitStreamContainer-java.io.InputStream-boolean-}
```
public SplitStreamContainer(InputStream stream, boolean disposeStream)
```


Инициализирует новый экземпляр класса `SplitStreamContainer`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток данных. |
| disposeStream | boolean | если установить в `true`, поток будет освобождён при освобождении контейнера. |

### SplitStreamContainer(StreamContainer stream, boolean disposeStream) {#SplitStreamContainer-com.aspose.imaging.StreamContainer-boolean-}
```
public SplitStreamContainer(StreamContainer stream, boolean disposeStream)
```


Инициализирует новый экземпляр класса `SplitStreamContainer`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Контейнер потока. |
| disposeStream | boolean | если установить в `true`, освобождает поток. |

### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Получает объект, который может использоваться для синхронизации доступа к синхронизированному ресурсу.

**Returns:**
java.lang.Object - Объект, который может использоваться для синхронизации доступа к синхронизированному ресурсу.
### getPosition() {#getPosition--}
```
public long getPosition()
```


Получает текущую позицию в потоке. Это значение представляет смещение от начальной позиции потока, переданной в конструкторе StreamContainer.

**Returns:**
long - Текущая позиция потока.
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Устанавливает текущую позицию в потоке. Это значение представляет смещение от начальной позиции потока, переданной в конструкторе StreamContainer.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long | Текущая позиция потока. |

### getLength() {#getLength--}
```
public long getLength()
```


Получает длину потока в байтах. Это значение меньше, чем `System.IO.Stream.Length`, на начальную позицию потока, переданную в конструкторе StreamContainer.

**Returns:**
long - Длина потока.
### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Устанавливает длину потока в байтах. Это значение меньше, чем `System.IO.Stream.Length`, на начальную позицию потока, переданную в конструкторе StreamContainer.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long | Длина потока. |

### canRead() {#canRead--}
```
public boolean canRead()
```


Получает значение, указывающее, поддерживает ли поток чтение.

**Returns:**
boolean - `true`, если поток поддерживает чтение; иначе `false`.
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Получает значение, указывающее, поддерживает ли поток перемещение.

**Returns:**
boolean - `true`, если поток поддерживает перемещение; иначе `false`.
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Получает значение, указывающее, поддерживает ли поток запись.

**Returns:**
boolean - `true`, если поток поддерживает запись; иначе `false`.
### insert(int position, StreamContainer stream, boolean disposeStream) {#insert-int-com.aspose.imaging.StreamContainer-boolean-}
```
public void insert(int position, StreamContainer stream, boolean disposeStream)
```


Вставляет контейнер потока в указанную позицию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | int | Позиция для вставки. |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Контейнер потока для вставки. |
| disposeStream | boolean | если установить в `true`, освобождает поток. |

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

