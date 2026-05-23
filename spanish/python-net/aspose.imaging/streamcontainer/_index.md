---
title: "Clase StreamContainer"
type: docs
weight: 7340
url: /es/python-net/aspose.imaging/streamcontainer/
---

**Summary:** Represents stream container which contains the stream and provides stream processing routines.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.StreamContainer

**Inheritance:** DisposableObject

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [StreamContainer(stream)](#StreamContainer_stream_1) | Inicializa una nueva instancia de la clase [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [StreamContainer(stream, dispose_stream)](#StreamContainer_stream_dispose_stream_2) | Inicializa una nueva instancia de la clase [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [static] | int | r | Especifica la cantidad de bytes de lectura y escritura al leer secuencialmente. |
| can_read | bool | r | Obtiene un valor que indica si la secuencia admite lectura. |
| can_seek | bool | r | Obtiene un valor que indica si la secuencia admite búsqueda. |
| can_write | bool | r | Obtiene un valor que indica si la secuencia admite escritura. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está disposed. |
| is_stream_disposed_on_close | bool | r | Obtiene un valor que indica si esta secuencia se elimina al cerrarse. |
| length | int | r/w | Obtiene o establece la longitud de la secuencia en bytes. Este valor es menor que el  por la posición inicial de la secuencia pasada en el constructor de StreamContainer. |
| position | int | r/w | Obtiene o establece la posición actual dentro de la secuencia. Este valor representa el desplazamiento desde la posición inicial de la secuencia pasada en el constructor de StreamContainer. |
| flujo | _io.BufferedRandom | r | Obtiene la secuencia de datos. |
| sync_root | System.Object | r | Obtiene un objeto que puede usarse para sincronizar el acceso al recurso sincronizado. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| flush() | Borra todos los búferes de esta secuencia y hace que cualquier dato almacenado en búfer se escriba en el dispositivo subyacente. |
| [read(buffer, offset, count)](#read_buffer_offset_count_1) | Lee una secuencia de bytes de la secuencia actual y avanza la posición dentro de la secuencia en la cantidad de bytes leídos. |
| [read(bytes)](#read_bytes_2) | Lee bytes para llenar el búfer de bytes especificado. |
| [read_byte()](#read_byte__3) | Lee un byte de la secuencia y avanza la posición dentro de la secuencia en un byte, o devuelve -1 si está al final de la secuencia. |
| [save(destination_stream)](#save_destination_stream_4) | Guarda (copia) los datos del flujo en el flujo especificado. Utiliza el tamaño de búfer predeterminado [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) y el valor del flujo [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_5) | Guarda (copia) todos los datos del flujo en el flujo especificado. Utiliza el valor del flujo [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_6) | Guarda (copia) los datos del flujo en el flujo especificado. |
| [save(file_path)](#save_file_path_7) | Guarda (copia) los datos del flujo en el flujo especificado. Utiliza el tamaño de búfer predeterminado [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) y el valor del flujo [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_8) | Guarda (copia) los datos del flujo en el flujo especificado. Utiliza el valor del flujo [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_9) | Guarda (copia) los datos del flujo en el flujo especificado. |
| [save_to_stream(destination_stream)](#save_to_stream_destination_stream_10) | Guarda (copia) los datos del flujo en el flujo especificado. Utiliza el tamaño de búfer predeterminado [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) y el valor del flujo [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save_to_stream_with_buf_size(destination_stream, buffer_size)](#save_to_stream_with_buf_size_destination_stream_buffer_size_11) | Guarda (copia) todos los datos del flujo en el flujo especificado. Utiliza el valor del flujo [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length)](#save_to_stream_with_buf_size_and_len_destination_stream_buffer_size_length_12) | Guarda (copia) los datos del flujo en el flujo especificado. |
| [save_with_buf_size(file_path, buffer_size)](#save_with_buf_size_file_path_buffer_size_13) | Guarda (copia) los datos del flujo en el flujo especificado. Utiliza el valor del flujo [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save_with_buf_size_and_len(file_path, buffer_size, length)](#save_with_buf_size_and_len_file_path_buffer_size_length_14) | Guarda (copia) los datos del flujo en el flujo especificado. |
| [seek(offset, origin)](#seek_offset_origin_15) | Establece la posición dentro del flujo actual. |
| seek_begin() | Establece la posición del flujo al comienzo del mismo. Este valor representa el desplazamiento desde la posición inicial del flujo pasada en el constructor de StreamContainer. |
| [to_bytes()](#to_bytes__16) | Convierte los datos del flujo a una matriz de enteros. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_17) | Convierte los datos del flujo a una matriz de enteros. |
| [write(buffer, offset, count)](#write_buffer_offset_count_18) | Escribe una secuencia de bytes en el flujo actual y avanza la posición actual dentro de este flujo en la cantidad de bytes escritos. |
| [write(bytes)](#write_bytes_19) | Escribe todos los bytes especificados en el flujo. |
| [write_byte(value)](#write_byte_value_20) | Escribe un byte en la posición actual del flujo y avanza la posición dentro del flujo en un byte. |
| [write_to(stream_container)](#write_to_stream_container_21) | Copia los datos contenidos a otro [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [write_to(stream_container, length)](#write_to_stream_container_length_22) | Copia los datos contenidos a otro [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/). |


### Constructor: StreamContainer(stream) {#StreamContainer_stream_1}


```
 StreamContainer(stream) 
```

Inicializa una nueva instancia de la clase [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo. |

### Constructor: StreamContainer(stream, dispose_stream) {#StreamContainer_stream_dispose_stream_2}


```
 StreamContainer(stream, dispose_stream) 
```

Inicializa una nueva instancia de la clase [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo de datos. |
| dispose_stream | bool | si se establece en <c>true</c> el flujo se eliminará cuando se elimine el contenedor. |

### Method: read(buffer, offset, count) {#read_buffer_offset_count_1}


```
 read(buffer, offset, count) 
```

Lee una secuencia de bytes de la secuencia actual y avanza la posición dentro de la secuencia en la cantidad de bytes leídos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| búfer | System.Byte | Una matriz de bytes. Cuando este método devuelve, el búfer contiene la matriz de bytes especificada con los valores entre _offset_ y (_offset_ + _count_ - 1) reemplazados por los bytes leídos de la fuente actual. |
| offset | int | El desplazamiento de byte basado en cero en _buffer_ en el que comenzar a almacenar los datos leídos del flujo actual. |
| count | int | El número máximo de bytes que se leerán del flujo actual. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El número total de bytes leídos en el búfer. Esto puede ser menor que el número de bytes solicitados si no hay tantos bytes disponibles actualmente, o cero (0) si se ha alcanzado el final del flujo. |


### Method: read(bytes) {#read_bytes_2}


```
 read(bytes) 
```

Lee bytes para llenar el búfer de bytes especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| bytes | System.Byte | Los bytes a rellenar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El número de bytes leídos. Este valor puede ser menor que el número de bytes en el búfer si no hay suficientes bytes en el flujo. |


### Method: read_byte() {#read_byte__3}


```
 read_byte() 
```

Lee un byte de la secuencia y avanza la posición dentro de la secuencia en un byte, o devuelve -1 si está al final de la secuencia.

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El byte sin signo convertido a Int32, o -1 si está al final del flujo. |


### Method: save(destination_stream) {#save_destination_stream_4}


```
 save(destination_stream) 
```

Guarda (copia) los datos del flujo en el flujo especificado. Utiliza el tamaño de búfer predeterminado [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) y el valor del flujo [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | El flujo donde guardar los datos. |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_5}


```
 save(destination_stream, buffer_size) 
```

Guarda (copia) todos los datos del flujo en el flujo especificado. Utiliza el valor del flujo [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | El flujo donde guardar los datos. |
| buffer_size | int | El búfer. |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_6}


```
 save(destination_stream, buffer_size, length) 
```

Guarda (copia) los datos del flujo en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | El flujo donde guardar los datos. |
| buffer_size | int | El tamaño del búfer. Por defecto se usa el valor de [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |
| length | int | La longitud de los datos del flujo a copiar. Por defecto, la longitud se establece al valor de [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save(file_path) {#save_file_path_7}


```
 save(file_path) 
```

Guarda (copia) los datos del flujo en el flujo especificado. Utiliza el tamaño de búfer predeterminado [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) y el valor del flujo [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar los datos del flujo. |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_8}


```
 save(file_path, buffer_size) 
```

Guarda (copia) los datos del flujo en el flujo especificado. Utiliza el valor del flujo [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar los datos del flujo. |
| buffer_size | int | El tamaño del búfer. Por defecto se usa el valor de [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_9}


```
 save(file_path, buffer_size, length) 
```

Guarda (copia) los datos del flujo en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar los datos del flujo. |
| buffer_size | int | El tamaño del búfer. Por defecto se usa el valor de [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |
| length | int | La longitud de los datos del flujo a copiar. Por defecto, la longitud se establece al valor de [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save_to_stream(destination_stream) {#save_to_stream_destination_stream_10}


```
 save_to_stream(destination_stream) 
```

Guarda (copia) los datos del flujo en el flujo especificado. Utiliza el tamaño de búfer predeterminado [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) y el valor del flujo [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | El flujo donde guardar los datos. |

### Method: save_to_stream_with_buf_size(destination_stream, buffer_size) {#save_to_stream_with_buf_size_destination_stream_buffer_size_11}


```
 save_to_stream_with_buf_size(destination_stream, buffer_size) 
```

Guarda (copia) todos los datos del flujo en el flujo especificado. Utiliza el valor del flujo [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | El flujo donde guardar los datos. |
| buffer_size | int | El búfer. |

### Method: save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length) {#save_to_stream_with_buf_size_and_len_destination_stream_buffer_size_length_12}


```
 save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length) 
```

Guarda (copia) los datos del flujo en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | El flujo donde guardar los datos. |
| buffer_size | int | El tamaño del búfer. Por defecto se usa el valor de [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |
| length | int | La longitud de los datos del flujo a copiar. Por defecto, la longitud se establece al valor de [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save_with_buf_size(file_path, buffer_size) {#save_with_buf_size_file_path_buffer_size_13}


```
 save_with_buf_size(file_path, buffer_size) 
```

Guarda (copia) los datos del flujo en el flujo especificado. Utiliza el valor del flujo [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar los datos del flujo. |
| buffer_size | int | El tamaño del búfer. Por defecto se usa el valor de [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save_with_buf_size_and_len(file_path, buffer_size, length) {#save_with_buf_size_and_len_file_path_buffer_size_length_14}


```
 save_with_buf_size_and_len(file_path, buffer_size, length) 
```

Guarda (copia) los datos del flujo en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar los datos del flujo. |
| buffer_size | int | El tamaño del búfer. Por defecto se usa el valor de [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |
| length | int | La longitud de los datos del flujo a copiar. Por defecto, la longitud se establece al valor de [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: seek(offset, origin) {#seek_offset_origin_15}


```
 seek(offset, origin) 
```

Establece la posición dentro del flujo actual.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| offset | int | Un desplazamiento de byte relativo al parámetro _origin_. Este valor representa el desplazamiento desde la posición inicial del flujo pasada en el constructor de StreamContainer. |
| origin | [SeekOrigin](/imaging/python-net/aspose.imaging/seekorigin/) | Un valor del tipo SeekOrigin que indica el punto de referencia usado para obtener la nueva posición. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | La nueva posición dentro del flujo actual. |


### Method: to_bytes() {#to_bytes__16}


```
 to_bytes() 
```

Convierte los datos del flujo a una matriz de enteros.

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Byte | Los datos del flujo convertidos al array de int. |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_17}


```
 to_bytes(position, bytes_count) 
```

Convierte los datos del flujo a una matriz de enteros.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición desde la cual comenzar a leer bytes. |
| bytes_count | int | La cantidad de bytes a leer. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Byte | Los datos del flujo convertidos al array de int. |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_18}


```
 write(buffer, offset, count) 
```

Escribe una secuencia de bytes en el flujo actual y avanza la posición actual dentro de este flujo en la cantidad de bytes escritos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| búfer | System.Byte | Una matriz de bytes. Este método copia _count_ bytes de _buffer_ al flujo actual. |
| offset | int | El desplazamiento de byte basado en cero en _buffer_ en el que comenzar a copiar bytes al flujo actual. |
| count | int | El número de bytes que se escribirán en el flujo actual. |

### Method: write(bytes) {#write_bytes_19}


```
 write(bytes) 
```

Escribe todos los bytes especificados en el flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| bytes | System.Byte | Los bytes a escribir. |

### Method: write_byte(value) {#write_byte_value_20}


```
 write_byte(value) 
```

Escribe un byte en la posición actual del flujo y avanza la posición dentro del flujo en un byte.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| valor | System.Byte | El byte a escribir en el flujo. |

### Method: write_to(stream_container) {#write_to_stream_container_21}


```
 write_to(stream_container) 
```

Copia los datos contenidos a otro [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | El contenedor de flujo al que copiar. |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_22}


```
 write_to(stream_container, length) 
```

Copia los datos contenidos a otro [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | El contenedor de flujo al que copiar. |
| length | int | La cantidad de bytes a escribir. |

