---
title: "SplitStreamContainer Klasse"
type: docs
weight: 7330
url: /de/python-net/aspose.imaging/splitstreamcontainer/
---

**Summary:** Represents split stream container which contains the stream and provides stream processing routines.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.SplitStreamContainer

**Inheritance:** StreamContainer

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [SplitStreamContainer(stream)](#SplitStreamContainer_stream_1) | Initialisiert eine neue Instanz der [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) Klasse. |
| [SplitStreamContainer(stream, dispose_stream)](#SplitStreamContainer_stream_dispose_stream_2) | Initialisiert eine neue Instanz der [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) Klasse. |
| [SplitStreamContainer(stream, dispose_stream)](#SplitStreamContainer_stream_dispose_stream_3) | Initialisiert eine neue Instanz der [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [statisch] | int | r | Gibt die Anzahl der Lese- und Schreibbytes beim sequentiellen Lesen an. |
| can_read | bool | r | Gibt einen Wert zurück, der angibt, ob der Stream das Lesen unterstützt. |
| can_seek | bool | r | Gibt einen Wert zurück, der angibt, ob der Stream das Suchen unterstützt. |
| can_write | bool | r | Gibt einen Wert zurück, der angibt, ob der Stream das Schreiben unterstützt. |
| freigegeben | bool | r | Liest einen Wert, der angibt, ob diese Instanz freigegeben ist. |
| is_stream_disposed_on_close | bool | r | Gibt einen Wert zurück, der angibt, ob dieser Stream beim Schließen freigegeben wird. |
| length | int | r/w | Liest oder setzt die Streamlänge in Bytes. Dieser Wert ist kleiner als die  durch die beim Konstruktor von StreamContainer übergebene Startposition des Streams. |
| position | int | r/w | Liest oder setzt die aktuelle Position im Stream. Dieser Wert stellt den Offset von der beim Konstruktor von StreamContainer übergebenen Startposition des Streams dar. |
| Stream | _io.BufferedRandom | r | Liest den Datenstream. |
| sync_root | System.Object | r | Gibt ein Objekt zurück, das verwendet werden kann, um den Zugriff auf die synchronisierte Ressource zu synchronisieren. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_stream(stream, dispose_stream)](#create_from_stream_stream_dispose_stream_1) | Initialisiert eine neue Instanz der [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) Klasse. |
| [create_from_stream_container(stream, dispose_stream)](#create_from_stream_container_stream_dispose_stream_2) | Initialisiert eine neue Instanz der [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) Klasse. |
| flush() | Leert alle Puffer dieses Streams und veranlasst, dass gepufferte Daten in das zugrunde liegende Gerät geschrieben werden. |
| [insert(position, stream, dispose_stream)](#insert_position_stream_dispose_stream_3) | Fügt den Stream-Container an der angegebenen Position ein. |
| [read(buffer, offset, count)](#read_buffer_offset_count_4) | Liest eine Sequenz von Bytes aus dem aktuellen Stream und verschiebt die Position im Stream um die gelesene Anzahl von Bytes. |
| [read(bytes)](#read_bytes_5) | Liest Bytes, um den angegebenen Byte-Puffer zu füllen. |
| [read_byte()](#read_byte__6) | Liest ein Byte aus dem Stream und verschiebt die Position im Stream um ein Byte, oder gibt -1 zurück, wenn das Ende des Streams erreicht ist. |
| [save(destination_stream)](#save_destination_stream_7) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standard-Puffergröße [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) und den Wert des Streams [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_8) | Speichert (kopiert) alle Daten des Streams in den angegebenen Stream. Verwendet den Wert des Streams [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_9) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| [save(file_path)](#save_file_path_10) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standard-Puffergröße [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) und den Wert des Streams [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_11) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet den Wert des Streams [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_12) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| [save_to_stream(destination_stream)](#save_to_stream_destination_stream_13) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standard-Puffergröße [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) und den Wert des Streams [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save_to_stream_with_buf_size(destination_stream, buffer_size)](#save_to_stream_with_buf_size_destination_stream_buffer_size_14) | Speichert (kopiert) alle Daten des Streams in den angegebenen Stream. Verwendet den Wert des Streams [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length)](#save_to_stream_with_buf_size_and_len_destination_stream_buffer_size_length_15) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| [save_with_buf_size(file_path, buffer_size)](#save_with_buf_size_file_path_buffer_size_16) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet den Wert des Streams [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save_with_buf_size_and_len(file_path, buffer_size, length)](#save_with_buf_size_and_len_file_path_buffer_size_length_17) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| [seek(offset, origin)](#seek_offset_origin_18) | Setzt die Position im aktuellen Stream. |
| seek_begin() | Setzt die Stream-Position auf den Anfang des Streams. Dieser Wert stellt den Offset von der beim StreamContainer-Konstruktor übergebenen Startposition des Streams dar. |
| [to_bytes()](#to_bytes__19) | Konvertiert die Stream-Daten in ein int-Array. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_20) | Konvertiert die Stream-Daten in ein int-Array. |
| [write(buffer, offset, count)](#write_buffer_offset_count_21) | Schreibt eine Sequenz von Bytes in den aktuellen Stream und verschiebt die aktuelle Position innerhalb dieses Streams um die Anzahl der geschriebenen Bytes. |
| [write(bytes)](#write_bytes_22) | Schreibt alle angegebenen Bytes in den Stream. |
| [write_byte(value)](#write_byte_value_23) | Schreibt ein Byte an die aktuelle Position im Stream und verschiebt die Position im Stream um ein Byte. |
| [write_to(stream_container)](#write_to_stream_container_24) | Kopiert die enthaltenen Daten in einen anderen [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [write_to(stream_container, length)](#write_to_stream_container_length_25) | Kopiert die enthaltenen Daten in einen anderen [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/). |


### Constructor: SplitStreamContainer(stream) {#SplitStreamContainer_stream_1}


```
 SplitStreamContainer(stream) 
```

Initialisiert eine neue Instanz der [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream. |

### Constructor: SplitStreamContainer(stream, dispose_stream) {#SplitStreamContainer_stream_dispose_stream_2}


```
 SplitStreamContainer(stream, dispose_stream) 
```

Initialisiert eine neue Instanz der [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Daten-Stream. |
| dispose_stream | bool | Wenn auf <c>true</c> gesetzt, wird der Stream freigegeben, wenn der Container freigegeben wird. |

### Constructor: SplitStreamContainer(stream, dispose_stream) {#SplitStreamContainer_stream_dispose_stream_3}


```
 SplitStreamContainer(stream, dispose_stream) 
```

Initialisiert eine neue Instanz der [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Der Daten-Stream. |
| dispose_stream | bool | Wenn auf <c>true</c> gesetzt, wird der Stream freigegeben, wenn der Container freigegeben wird. |

### Method: create_from_stream(stream, dispose_stream)  [static] {#create_from_stream_stream_dispose_stream_1}


```
 create_from_stream(stream, dispose_stream) 
```

Initialisiert eine neue Instanz der [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Daten-Stream. |
| dispose_stream | bool | Wenn auf <c>true</c> gesetzt, wird der Stream freigegeben, wenn der Container freigegeben wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) |  |


### Method: create_from_stream_container(stream, dispose_stream)  [static] {#create_from_stream_container_stream_dispose_stream_2}


```
 create_from_stream_container(stream, dispose_stream) 
```

Initialisiert eine neue Instanz der [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Der Stream-Container. |
| dispose_stream | bool | Wenn auf <c>true</c> gesetzt, wird der Stream freigegeben. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) |  |


### Method: insert(position, stream, dispose_stream) {#insert_position_stream_dispose_stream_3}


```
 insert(position, stream, dispose_stream) 
```

Fügt den Stream-Container an der angegebenen Position ein.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, an die eingefügt wird. |
| stream | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Der Stream-Container, in den eingefügt wird. |
| dispose_stream | bool | Wenn auf <c>true</c> gesetzt, wird der Stream freigegeben. |

### Method: read(buffer, offset, count) {#read_buffer_offset_count_4}


```
 read(buffer, offset, count) 
```

Liest eine Sequenz von Bytes aus dem aktuellen Stream und verschiebt die Position im Stream um die gelesene Anzahl von Bytes.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Puffer | System.Byte | Ein Byte-Array. Wenn diese Methode zurückkehrt, enthält der Puffer das angegebene Byte-Array, wobei die Werte zwischen _offset_ und (_offset_ + _count_ - 1) durch die aus der aktuellen Quelle gelesenen Bytes ersetzt wurden. |
| offset | int | Der nullbasierte Byte-Offset in _buffer_, an dem das Speichern der aus dem aktuellen Stream gelesenen Daten beginnen soll. |
| count | int | Die maximale Anzahl von Bytes, die aus dem aktuellen Stream gelesen werden sollen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die Gesamtzahl der in den Puffer gelesenen Bytes. Diese kann geringer sein als die angeforderte Anzahl von Bytes, wenn nicht genügend Bytes verfügbar sind, oder null (0), wenn das Ende des Streams erreicht wurde. |


### Method: read(bytes) {#read_bytes_5}


```
 read(bytes) 
```

Liest Bytes, um den angegebenen Byte-Puffer zu füllen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Bytes | System.Byte | Die zu füllenden Bytes. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die Anzahl der gelesenen Bytes. Dieser Wert kann kleiner sein als die Anzahl der Bytes im Puffer, wenn nicht genügend Bytes im Stream vorhanden sind. |


### Method: read_byte() {#read_byte__6}


```
 read_byte() 
```

Liest ein Byte aus dem Stream und verschiebt die Position im Stream um ein Byte, oder gibt -1 zurück, wenn das Ende des Streams erreicht ist.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Das vorzeichenlose Byte, das zu einem Int32 umgewandelt wird, oder -1, wenn das Ende des Streams erreicht ist. |


### Method: save(destination_stream) {#save_destination_stream_7}


```
 save(destination_stream) 
```

Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standard-Puffergröße [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) und den Wert des Streams [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Der Stream, in dem die Daten gespeichert werden sollen. |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_8}


```
 save(destination_stream, buffer_size) 
```

Speichert (kopiert) alle Daten des Streams in den angegebenen Stream. Verwendet den Wert des Streams [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Der Stream, in dem die Daten gespeichert werden sollen. |
| buffer_size | int | Der Puffer. |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_9}


```
 save(destination_stream, buffer_size, length) 
```

Speichert (kopiert) die Daten des Streams in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Der Stream, in dem die Daten gespeichert werden sollen. |
| buffer_size | int | Die Puffergröße. |
| length | int | Die Länge der Stream-Daten, die kopiert werden sollen. Standardmäßig wird die Länge auf den Wert von [SplitStreamContainer.length](/imaging/python-net/aspose.imaging/splitstreamcontainer/) gesetzt. |

### Method: save(file_path) {#save_file_path_10}


```
 save(file_path) 
```

Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standard-Puffergröße [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) und den Wert des Streams [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Stream-Daten gespeichert werden sollen. |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_11}


```
 save(file_path, buffer_size) 
```

Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet den Wert des Streams [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Stream-Daten gespeichert werden sollen. |
| buffer_size | int | Die Puffergröße. Standardmäßig wird der Wert [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) verwendet. |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_12}


```
 save(file_path, buffer_size, length) 
```

Speichert (kopiert) die Daten des Streams in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Stream-Daten gespeichert werden sollen. |
| buffer_size | int | Die Puffergröße. Standardmäßig wird der Wert [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) verwendet. |
| length | int | Die Länge der Stream-Daten, die kopiert werden sollen. Standardmäßig wird die Länge auf den Wert von [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) gesetzt. |

### Method: save_to_stream(destination_stream) {#save_to_stream_destination_stream_13}


```
 save_to_stream(destination_stream) 
```

Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standard-Puffergröße [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) und den Wert des Streams [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Der Stream, in dem die Daten gespeichert werden sollen. |

### Method: save_to_stream_with_buf_size(destination_stream, buffer_size) {#save_to_stream_with_buf_size_destination_stream_buffer_size_14}


```
 save_to_stream_with_buf_size(destination_stream, buffer_size) 
```

Speichert (kopiert) alle Daten des Streams in den angegebenen Stream. Verwendet den Wert des Streams [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Der Stream, in dem die Daten gespeichert werden sollen. |
| buffer_size | int | Der Puffer. |

### Method: save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length) {#save_to_stream_with_buf_size_and_len_destination_stream_buffer_size_length_15}


```
 save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length) 
```

Speichert (kopiert) die Daten des Streams in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Der Stream, in dem die Daten gespeichert werden sollen. |
| buffer_size | int | Die Puffergröße. Standardmäßig wird der Wert [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) verwendet. |
| length | int | Die Länge der Stream-Daten, die kopiert werden sollen. Standardmäßig wird die Länge auf den Wert von [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) gesetzt. |

### Method: save_with_buf_size(file_path, buffer_size) {#save_with_buf_size_file_path_buffer_size_16}


```
 save_with_buf_size(file_path, buffer_size) 
```

Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet den Wert des Streams [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Stream-Daten gespeichert werden sollen. |
| buffer_size | int | Die Puffergröße. Standardmäßig wird der Wert [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) verwendet. |

### Method: save_with_buf_size_and_len(file_path, buffer_size, length) {#save_with_buf_size_and_len_file_path_buffer_size_length_17}


```
 save_with_buf_size_and_len(file_path, buffer_size, length) 
```

Speichert (kopiert) die Daten des Streams in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Stream-Daten gespeichert werden sollen. |
| buffer_size | int | Die Puffergröße. Standardmäßig wird der Wert [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) verwendet. |
| length | int | Die Länge der Stream-Daten, die kopiert werden sollen. Standardmäßig wird die Länge auf den Wert von [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) gesetzt. |

### Method: seek(offset, origin) {#seek_offset_origin_18}


```
 seek(offset, origin) 
```

Setzt die Position im aktuellen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| offset | int | Ein Byte-Offset relativ zum Parameter _origin_. Dieser Wert stellt den Abstand von der im Konstruktor von StreamContainer übergebenen Startposition des Streams dar. |
| origin | [SeekOrigin](/imaging/python-net/aspose.imaging/seekorigin/) | Ein Wert des Typs SeekOrigin, der den Referenzpunkt angibt, der zur Ermittlung der neuen Position verwendet wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die neue Position innerhalb des aktuellen Streams. |


### Method: to_bytes() {#to_bytes__19}


```
 to_bytes() 
```

Konvertiert die Stream-Daten in ein int-Array.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Byte | Die Stream-Daten, konvertiert in das int-Array. |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_20}


```
 to_bytes(position, bytes_count) 
```

Konvertiert die Stream-Daten in ein int-Array.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| position | int | Die Position, ab der Bytes gelesen werden sollen. |
| bytes_count | int | Die Anzahl der zu lesenden Bytes. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Byte | Die Stream-Daten, konvertiert in das int-Array. |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_21}


```
 write(buffer, offset, count) 
```

Schreibt eine Sequenz von Bytes in den aktuellen Stream und verschiebt die aktuelle Position innerhalb dieses Streams um die Anzahl der geschriebenen Bytes.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Puffer | System.Byte | Ein Byte-Array. Diese Methode kopiert _count_ Bytes von _buffer_ in den aktuellen Stream. |
| offset | int | Der nullbasierte Byte-Offset in _buffer_, bei dem das Kopieren von Bytes in den aktuellen Stream beginnen soll. |
| count | int | Die Anzahl der Bytes, die in den aktuellen Stream geschrieben werden sollen. |

### Method: write(bytes) {#write_bytes_22}


```
 write(bytes) 
```

Schreibt alle angegebenen Bytes in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Bytes | System.Byte | Die zu schreibenden Bytes. |

### Method: write_byte(value) {#write_byte_value_23}


```
 write_byte(value) 
```

Schreibt ein Byte an die aktuelle Position im Stream und verschiebt die Position im Stream um ein Byte.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Wert | System.Byte | Das Byte, das in den Stream geschrieben werden soll. |

### Method: write_to(stream_container) {#write_to_stream_container_24}


```
 write_to(stream_container) 
```

Kopiert die enthaltenen Daten in einen anderen [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Der Stream-Container, in den kopiert werden soll. |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_25}


```
 write_to(stream_container, length) 
```

Kopiert die enthaltenen Daten in einen anderen [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Der Stream-Container, in den kopiert werden soll. |
| length | int | Die Anzahl der zu schreibenden Bytes. |

