---
title: "Класс FileStreamContainer"
type: docs
weight: 4810
url: /ru/python-net/aspose.imaging/filestreamcontainer/
---

**Summary:** Helper for file stream processing.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.FileStreamContainer

**Inheritance:** StreamContainer

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [static] | int | r | Указывает количество байтов для чтения и записи при последовательном чтении. |
| can_read | bool | r | Возвращает значение, указывающее, поддерживает ли поток чтение. |
| can_seek | bool | r | Возвращает значение, указывающее, поддерживает ли поток перемещение. |
| can_write | bool | r | Возвращает значение, указывающее, поддерживает ли поток запись. |
| disposed | bool | r | Получает значение, указывающее, удалён ли этот экземпляр. |
| file_path | string | r | Получает путь к файлу. |
| is_created | bool | r | Получает значение, указывающее, был ли поток создан явно. |
| is_stream_disposed_on_close | bool | r | Возвращает значение, указывающее, будет ли этот поток освобождён при закрытии. |
| is_temporal | bool | r/w | Получает или задает значение, указывающее, является ли поток временным. |
| length | int | r/w | Получает или задаёт длину потока в байтах. Это значение меньше, чем позиция начала потока, переданная в конструкторе StreamContainer. |
| position | int | r/w | Получает или задаёт текущую позицию в потоке. Это значение представляет смещение от начальной позиции потока, переданной в конструкторе StreamContainer. |
| поток | _io.BufferedRandom | r | Возвращает поток данных. |
| sync_root | System.Object | r | Возвращает объект, который можно использовать для синхронизации доступа к синхронизированному ресурсу. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_file_stream(file_location, is_temporal)](#create_file_stream_file_location_is_temporal_1) | Создаёт новый файловый поток. |
| flush() | Очищает все буферы этого потока и заставляет любые буферизованные данные записаться в подлежащие устройство. |
| [open_file_stream(file_location)](#open_file_stream_file_location_2) | Открывает существующий файловый поток. Если файловый поток не существует, выбрасывается соответствующее исключение. |
| [read(buffer, offset, count)](#read_buffer_offset_count_3) | Читает последовательность байтов из текущего потока и перемещает позицию в потоке на количество прочитанных байтов. |
| [read(bytes)](#read_bytes_4) | Читает байты, заполняя указанный буфер байтов. |
| [read_byte()](#read_byte__5) | Читает один байт из потока и перемещает позицию в потоке на один байт, либо возвращает -1, если достигнут конец потока. |
| [save(destination_stream)](#save_destination_stream_6) | Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) и значение потока [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_7) | Сохраняет (копирует) все данные потока в указанный поток. Использует значение потока [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_8) | Сохраняет (копирует) данные потока в указанный поток. |
| [save(file_path)](#save_file_path_9) | Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) и значение потока [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_10) | Сохраняет (копирует) данные потока в указанный поток. Использует значение потока [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_11) | Сохраняет (копирует) данные потока в указанный поток. |
| [save_to_stream(destination_stream)](#save_to_stream_destination_stream_12) | Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) и значение потока [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save_to_stream_with_buf_size(destination_stream, buffer_size)](#save_to_stream_with_buf_size_destination_stream_buffer_size_13) | Сохраняет (копирует) все данные потока в указанный поток. Использует значение потока [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length)](#save_to_stream_with_buf_size_and_len_destination_stream_buffer_size_length_14) | Сохраняет (копирует) данные потока в указанный поток. |
| [save_with_buf_size(file_path, buffer_size)](#save_with_buf_size_file_path_buffer_size_15) | Сохраняет (копирует) данные потока в указанный поток. Использует значение потока [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save_with_buf_size_and_len(file_path, buffer_size, length)](#save_with_buf_size_and_len_file_path_buffer_size_length_16) | Сохраняет (копирует) данные потока в указанный поток. |
| [seek(offset, origin)](#seek_offset_origin_17) | Устанавливает позицию в текущем потоке. |
| seek_begin() | Устанавливает позицию потока в начало потока. Это значение представляет смещение от начальной позиции потока, переданной в конструкторе StreamContainer. |
| [to_bytes()](#to_bytes__18) | Преобразует данные потока в массив int. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_19) | Преобразует данные потока в массив int. |
| [write(buffer, offset, count)](#write_buffer_offset_count_20) | Записывает последовательность байтов в текущий поток и перемещает текущую позицию в этом потоке на количество записанных байтов. |
| [write(bytes)](#write_bytes_21) | Записывает все указанные байты в поток. |
| [write_byte(value)](#write_byte_value_22) | Записывает байт в текущую позицию потока и перемещает позицию в потоке на один байт. |
| [write_to(stream_container)](#write_to_stream_container_23) | Копирует содержащиеся данные в другой [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [write_to(stream_container, length)](#write_to_stream_container_length_24) | Копирует содержащиеся данные в другой [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/). |


### Method: create_file_stream(file_location, is_temporal)  [static] {#create_file_stream_file_location_is_temporal_1}


```
 create_file_stream(file_location, is_temporal) 
```

Создаёт новый файловый поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_location | string | Расположение файла. |
| is_temporal | bool | Если установлено значение <c>true</c>, контейнер файлового потока является временным. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FileStreamContainer](/imaging/python-net/aspose.imaging/filestreamcontainer/) | Контейнер файлового потока. |


### Method: open_file_stream(file_location)  [static] {#open_file_stream_file_location_2}


```
 open_file_stream(file_location) 
```

Открывает существующий файловый поток. Если файловый поток не существует, выбрасывается соответствующее исключение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_location | string | Расположение файла. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FileStreamContainer](/imaging/python-net/aspose.imaging/filestreamcontainer/) | Контейнер файлового потока. |


### Method: read(buffer, offset, count) {#read_buffer_offset_count_3}


```
 read(buffer, offset, count) 
```

Читает последовательность байтов из текущего потока и перемещает позицию в потоке на количество прочитанных байтов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| буфер | System.Byte | Массив байтов. После возврата этого метода буфер содержит указанный массив байтов, где значения между _offset_ и (_offset_ + _count_ - 1) заменены байтами, прочитанными из текущего источника. |
| offset | int | Нулевой байтовый смещение в _buffer_, с которого начинать сохранять данные, прочитанные из текущего потока. |
| count | int | Максимальное количество байтов, которое будет прочитано из текущего потока. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Общее количество байтов, прочитанных в буфер. Оно может быть меньше запрошенного количества байтов, если столько байтов в данный момент недоступно, или равно нулю (0), если достигнут конец потока. |


### Method: read(bytes) {#read_bytes_4}


```
 read(bytes) 
```

Читает байты, заполняя указанный буфер байтов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| байты | System.Byte | Байты для заполнения. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Количество прочитанных байтов. Это значение может быть меньше количества байтов в буфере, если в потоке недостаточно байтов. |


### Method: read_byte() {#read_byte__5}


```
 read_byte() 
```

Читает один байт из потока и перемещает позицию в потоке на один байт, либо возвращает -1, если достигнут конец потока.

**Returns**

| Тип | Описание |
| :- | :- |
| int | Беззнаковый байт, приведённый к Int32, или -1, если достигнут конец потока. |


### Method: save(destination_stream) {#save_destination_stream_6}


```
 save(destination_stream) 
```

Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) и значение потока [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Поток, в который сохраняются данные. |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_7}


```
 save(destination_stream, buffer_size) 
```

Сохраняет (копирует) все данные потока в указанный поток. Использует значение потока [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Поток, в который сохраняются данные. |
| размер_буфера | int | Буфер. |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_8}


```
 save(destination_stream, buffer_size, length) 
```

Сохраняет (копирует) данные потока в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Поток, в который сохраняются данные. |
| buffer_size | int | Размер буфера. По умолчанию используется значение [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |
| length | int | Длина данных потока для копирования. По умолчанию длина устанавливается в значение [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save(file_path) {#save_file_path_9}


```
 save(file_path) 
```

Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) и значение потока [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу, в который сохраняются данные потока. |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_10}


```
 save(file_path, buffer_size) 
```

Сохраняет (копирует) данные потока в указанный поток. Использует значение потока [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу, в который сохраняются данные потока. |
| buffer_size | int | Размер буфера. По умолчанию используется значение [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_11}


```
 save(file_path, buffer_size, length) 
```

Сохраняет (копирует) данные потока в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу, в который сохраняются данные потока. |
| buffer_size | int | Размер буфера. По умолчанию используется значение [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |
| length | int | Длина данных потока для копирования. По умолчанию длина устанавливается в значение [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save_to_stream(destination_stream) {#save_to_stream_destination_stream_12}


```
 save_to_stream(destination_stream) 
```

Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) и значение потока [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Поток, в который сохраняются данные. |

### Method: save_to_stream_with_buf_size(destination_stream, buffer_size) {#save_to_stream_with_buf_size_destination_stream_buffer_size_13}


```
 save_to_stream_with_buf_size(destination_stream, buffer_size) 
```

Сохраняет (копирует) все данные потока в указанный поток. Использует значение потока [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Поток, в который сохраняются данные. |
| размер_буфера | int | Буфер. |

### Method: save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length) {#save_to_stream_with_buf_size_and_len_destination_stream_buffer_size_length_14}


```
 save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length) 
```

Сохраняет (копирует) данные потока в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Поток, в который сохраняются данные. |
| buffer_size | int | Размер буфера. По умолчанию используется значение [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |
| length | int | Длина данных потока для копирования. По умолчанию длина устанавливается в значение [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save_with_buf_size(file_path, buffer_size) {#save_with_buf_size_file_path_buffer_size_15}


```
 save_with_buf_size(file_path, buffer_size) 
```

Сохраняет (копирует) данные потока в указанный поток. Использует значение потока [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу, в который сохраняются данные потока. |
| buffer_size | int | Размер буфера. По умолчанию используется значение [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save_with_buf_size_and_len(file_path, buffer_size, length) {#save_with_buf_size_and_len_file_path_buffer_size_length_16}


```
 save_with_buf_size_and_len(file_path, buffer_size, length) 
```

Сохраняет (копирует) данные потока в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу, в который сохраняются данные потока. |
| buffer_size | int | Размер буфера. По умолчанию используется значение [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |
| length | int | Длина данных потока для копирования. По умолчанию длина устанавливается в значение [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: seek(offset, origin) {#seek_offset_origin_17}


```
 seek(offset, origin) 
```

Устанавливает позицию в текущем потоке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| offset | int | Смещение в байтах относительно параметра _origin_. Это значение представляет смещение от начальной позиции потока, переданной в конструкторе StreamContainer. |
| origin | [SeekOrigin](/imaging/python-net/aspose.imaging/seekorigin/) | Значение типа SeekOrigin, указывающее точку отсчёта, используемую для получения новой позиции. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Новая позиция в текущем потоке. |


### Method: to_bytes() {#to_bytes__18}


```
 to_bytes() 
```

Преобразует данные потока в массив int.

**Returns**

| Тип | Описание |
| :- | :- |
| System.Byte | Данные потока, преобразованные в массив int. |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_19}


```
 to_bytes(position, bytes_count) 
```

Преобразует данные потока в массив int.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция, с которой начинать чтение байтов. |
| bytes_count | int | Количество байтов для чтения. |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Byte | Данные потока, преобразованные в массив int. |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_20}


```
 write(buffer, offset, count) 
```

Записывает последовательность байтов в текущий поток и перемещает текущую позицию в этом потоке на количество записанных байтов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| буфер | System.Byte | Массив байтов. Этот метод копирует _count_ байтов из _buffer_ в текущий поток. |
| offset | int | Нулевое байтовое смещение в _buffer_, с которого начинать копирование байтов в текущий поток. |
| count | int | Количество байтов, которое будет записано в текущий поток. |

### Method: write(bytes) {#write_bytes_21}


```
 write(bytes) 
```

Записывает все указанные байты в поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| байты | System.Byte | Байты для записи. |

### Method: write_byte(value) {#write_byte_value_22}


```
 write_byte(value) 
```

Записывает байт в текущую позицию потока и перемещает позицию в потоке на один байт.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| значение | System.Byte | Байт для записи в поток. |

### Method: write_to(stream_container) {#write_to_stream_container_23}


```
 write_to(stream_container) 
```

Копирует содержащиеся данные в другой [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Контейнер потока, в который копировать. |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_24}


```
 write_to(stream_container, length) 
```

Копирует содержащиеся данные в другой [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Контейнер потока, в который копировать. |
| length | int | Количество байтов для записи. |

