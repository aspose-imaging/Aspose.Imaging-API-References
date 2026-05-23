---
title: "SplitStreamContainer Classe"
type: docs
weight: 7330
url: /it/python-net/aspose.imaging/splitstreamcontainer/
---

**Summary:** Represents split stream container which contains the stream and provides stream processing routines.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.SplitStreamContainer

**Inheritance:** StreamContainer

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [SplitStreamContainer(stream)](#SplitStreamContainer_stream_1) | Inizializza una nuova istanza della classe [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/). |
| [SplitStreamContainer(stream, dispose_stream)](#SplitStreamContainer_stream_dispose_stream_2) | Inizializza una nuova istanza della classe [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/). |
| [SplitStreamContainer(stream, dispose_stream)](#SplitStreamContainer_stream_dispose_stream_3) | Inizializza una nuova istanza della classe [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [static] | int | r | Specifica il conteggio dei byte di lettura e scrittura durante la lettura sequenziale. |
| can_read | bool | r | Restituisce un valore che indica se lo stream supporta la lettura. |
| can_seek | bool | r | Restituisce un valore che indica se lo stream supporta lo spostamento. |
| can_write | bool | r | Restituisce un valore che indica se lo stream supporta la scrittura. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata eliminata. |
| is_stream_disposed_on_close | bool | r | Restituisce un valore che indica se questo stream viene eliminato alla chiusura. |
| length | int | r/w | Ottiene o imposta la lunghezza dello stream in byte. Questo valore è inferiore al  dalla posizione iniziale dello stream passata nel costruttore di StreamContainer. |
| position | int | r/w | Ottiene o imposta la posizione corrente all'interno dello stream. Questo valore rappresenta lo scostamento dalla posizione iniziale dello stream passata nel costruttore di StreamContainer. |
| stream | _io.BufferedRandom | r | Restituisce lo stream di dati. |
| sync_root | System.Object | r | Restituisce un oggetto che può essere usato per sincronizzare l'accesso alla risorsa sincronizzata. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_stream(stream, dispose_stream)](#create_from_stream_stream_dispose_stream_1) | Inizializza una nuova istanza della classe [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/). |
| [create_from_stream_container(stream, dispose_stream)](#create_from_stream_container_stream_dispose_stream_2) | Inizializza una nuova istanza della classe [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/). |
| flush() | Cancella tutti i buffer per questo stream e provoca la scrittura di tutti i dati memorizzati nel dispositivo sottostante. |
| [insert(position, stream, dispose_stream)](#insert_position_stream_dispose_stream_3) | Inserisce il contenitore di stream nella posizione specificata. |
| [read(buffer, offset, count)](#read_buffer_offset_count_4) | Legge una sequenza di byte dallo stream corrente e avanza la posizione all'interno dello stream del numero di byte letti. |
| [read(bytes)](#read_bytes_5) | Legge byte per riempire il buffer di byte specificato. |
| [read_byte()](#read_byte__6) | Legge un byte dallo stream e avanza la posizione all'interno dello stream di un byte, oppure restituisce -1 se è alla fine dello stream. |
| [save(destination_stream)](#save_destination_stream_7) | Salva (copia) i dati del flusso nello stream specificato. Usa la dimensione predefinita del buffer [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) e il valore del flusso [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_8) | Salva (copia) tutti i dati del flusso nello stream specificato. Usa il valore del flusso [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_9) | Salva (copia) i dati del flusso nello stream specificato. |
| [save(file_path)](#save_file_path_10) | Salva (copia) i dati del flusso nello stream specificato. Usa la dimensione predefinita del buffer [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) e il valore del flusso [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_11) | Salva (copia) i dati del flusso nello stream specificato. Usa il valore del flusso [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_12) | Salva (copia) i dati del flusso nello stream specificato. |
| [save_to_stream(destination_stream)](#save_to_stream_destination_stream_13) | Salva (copia) i dati del flusso nello stream specificato. Usa la dimensione predefinita del buffer [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) e il valore del flusso [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save_to_stream_with_buf_size(destination_stream, buffer_size)](#save_to_stream_with_buf_size_destination_stream_buffer_size_14) | Salva (copia) tutti i dati del flusso nello stream specificato. Usa il valore del flusso [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length)](#save_to_stream_with_buf_size_and_len_destination_stream_buffer_size_length_15) | Salva (copia) i dati del flusso nello stream specificato. |
| [save_with_buf_size(file_path, buffer_size)](#save_with_buf_size_file_path_buffer_size_16) | Salva (copia) i dati del flusso nello stream specificato. Usa il valore del flusso [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save_with_buf_size_and_len(file_path, buffer_size, length)](#save_with_buf_size_and_len_file_path_buffer_size_length_17) | Salva (copia) i dati del flusso nello stream specificato. |
| [seek(offset, origin)](#seek_offset_origin_18) | Imposta la posizione all'interno del flusso corrente. |
| seek_begin() | Imposta la posizione del flusso all'inizio del flusso. Questo valore rappresenta lo scostamento dalla posizione iniziale del flusso passata nel costruttore di StreamContainer. |
| [to_bytes()](#to_bytes__19) | Converte i dati del flusso in un array di interi. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_20) | Converte i dati del flusso in un array di interi. |
| [write(buffer, offset, count)](#write_buffer_offset_count_21) | Scrive una sequenza di byte nello stream corrente e avanza la posizione corrente all'interno di questo stream del numero di byte scritti. |
| [write(bytes)](#write_bytes_22) | Scrive tutti i byte specificati nello stream. |
| [write_byte(value)](#write_byte_value_23) | Scrive un byte nella posizione corrente dello stream e avanza la posizione all'interno dello stream di un byte. |
| [write_to(stream_container)](#write_to_stream_container_24) | Copia i dati contenuti in un altro [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [write_to(stream_container, length)](#write_to_stream_container_length_25) | Copia i dati contenuti in un altro [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/). |


### Constructor: SplitStreamContainer(stream) {#SplitStreamContainer_stream_1}


```
 SplitStreamContainer(stream) 
```

Inizializza una nuova istanza della classe [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Lo stream. |

### Constructor: SplitStreamContainer(stream, dispose_stream) {#SplitStreamContainer_stream_dispose_stream_2}


```
 SplitStreamContainer(stream, dispose_stream) 
```

Inizializza una nuova istanza della classe [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso di dati. |
| dispose_stream | bool | se impostato su <c>true</c> lo stream verrà eliminato quando il contenitore viene eliminato. |

### Constructor: SplitStreamContainer(stream, dispose_stream) {#SplitStreamContainer_stream_dispose_stream_3}


```
 SplitStreamContainer(stream, dispose_stream) 
```

Inizializza una nuova istanza della classe [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Il flusso di dati. |
| dispose_stream | bool | se impostato su <c>true</c> lo stream verrà eliminato quando il contenitore viene eliminato. |

### Method: create_from_stream(stream, dispose_stream)  [static] {#create_from_stream_stream_dispose_stream_1}


```
 create_from_stream(stream, dispose_stream) 
```

Inizializza una nuova istanza della classe [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso di dati. |
| dispose_stream | bool | se impostato su <c>true</c> lo stream verrà eliminato quando il contenitore viene eliminato. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) |  |


### Method: create_from_stream_container(stream, dispose_stream)  [static] {#create_from_stream_container_stream_dispose_stream_2}


```
 create_from_stream_container(stream, dispose_stream) 
```

Inizializza una nuova istanza della classe [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Il contenitore dello stream. |
| dispose_stream | bool | se impostato su <c>true</c> elimina lo stream. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) |  |


### Method: insert(position, stream, dispose_stream) {#insert_position_stream_dispose_stream_3}


```
 insert(position, stream, dispose_stream) 
```

Inserisce il contenitore di stream nella posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione in cui inserire. |
| stream | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Il contenitore di stream da inserire. |
| dispose_stream | bool | se impostato su <c>true</c> elimina lo stream. |

### Method: read(buffer, offset, count) {#read_buffer_offset_count_4}


```
 read(buffer, offset, count) 
```

Legge una sequenza di byte dallo stream corrente e avanza la posizione all'interno dello stream del numero di byte letti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| buffer | System.Byte | Un array di byte. Quando questo metodo restituisce, il buffer contiene l'array di byte specificato con i valori compresi tra _offset_ e (_offset_ + _count_ - 1) sostituiti dai byte letti dalla sorgente corrente. |
| offset | int | L'offset di byte basato su zero in _buffer_ a partire dal quale iniziare a memorizzare i dati letti dallo stream corrente. |
| count | int | Il numero massimo di byte da leggere dallo stream corrente. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il numero totale di byte letti nel buffer. Questo può essere inferiore al numero di byte richiesti se tali byte non sono attualmente disponibili, o zero (0) se è stato raggiunto la fine dello stream. |


### Method: read(bytes) {#read_bytes_5}


```
 read(bytes) 
```

Legge byte per riempire il buffer di byte specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| byte | System.Byte | I byte da riempire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il numero di byte letti. Questo valore può essere inferiore al numero di byte nel buffer se non ci sono abbastanza byte nello stream. |


### Method: read_byte() {#read_byte__6}


```
 read_byte() 
```

Legge un byte dallo stream e avanza la posizione all'interno dello stream di un byte, oppure restituisce -1 se è alla fine dello stream.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il byte senza segno convertito in un Int32, o -1 se si è alla fine del flusso. |


### Method: save(destination_stream) {#save_destination_stream_7}


```
 save(destination_stream) 
```

Salva (copia) i dati del flusso nello stream specificato. Usa la dimensione predefinita del buffer [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) e il valore del flusso [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Il flusso in cui salvare i dati. |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_8}


```
 save(destination_stream, buffer_size) 
```

Salva (copia) tutti i dati del flusso nello stream specificato. Usa il valore del flusso [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Il flusso in cui salvare i dati. |
| buffer_size | int | Il buffer. |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_9}


```
 save(destination_stream, buffer_size, length) 
```

Salva (copia) i dati del flusso nello stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Il flusso in cui salvare i dati. |
| buffer_size | int | La dimensione del buffer. |
| length | int | La lunghezza dei dati del flusso da copiare. Per impostazione predefinita la lunghezza è impostata al valore di [SplitStreamContainer.length](/imaging/python-net/aspose.imaging/splitstreamcontainer/). |

### Method: save(file_path) {#save_file_path_10}


```
 save(file_path) 
```

Salva (copia) i dati del flusso nello stream specificato. Usa la dimensione predefinita del buffer [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) e il valore del flusso [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso del file in cui salvare i dati del flusso. |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_11}


```
 save(file_path, buffer_size) 
```

Salva (copia) i dati del flusso nello stream specificato. Usa il valore del flusso [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso del file in cui salvare i dati del flusso. |
| buffer_size | int | La dimensione del buffer. Per impostazione predefinita viene usato il valore [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_12}


```
 save(file_path, buffer_size, length) 
```

Salva (copia) i dati del flusso nello stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso del file in cui salvare i dati del flusso. |
| buffer_size | int | La dimensione del buffer. Per impostazione predefinita viene usato il valore [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |
| length | int | La lunghezza dei dati del flusso da copiare. Per impostazione predefinita la lunghezza è impostata al valore di [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save_to_stream(destination_stream) {#save_to_stream_destination_stream_13}


```
 save_to_stream(destination_stream) 
```

Salva (copia) i dati del flusso nello stream specificato. Usa la dimensione predefinita del buffer [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) e il valore del flusso [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Il flusso in cui salvare i dati. |

### Method: save_to_stream_with_buf_size(destination_stream, buffer_size) {#save_to_stream_with_buf_size_destination_stream_buffer_size_14}


```
 save_to_stream_with_buf_size(destination_stream, buffer_size) 
```

Salva (copia) tutti i dati del flusso nello stream specificato. Usa il valore del flusso [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Il flusso in cui salvare i dati. |
| buffer_size | int | Il buffer. |

### Method: save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length) {#save_to_stream_with_buf_size_and_len_destination_stream_buffer_size_length_15}


```
 save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length) 
```

Salva (copia) i dati del flusso nello stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Il flusso in cui salvare i dati. |
| buffer_size | int | La dimensione del buffer. Per impostazione predefinita viene usato il valore [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |
| length | int | La lunghezza dei dati del flusso da copiare. Per impostazione predefinita la lunghezza è impostata al valore di [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save_with_buf_size(file_path, buffer_size) {#save_with_buf_size_file_path_buffer_size_16}


```
 save_with_buf_size(file_path, buffer_size) 
```

Salva (copia) i dati del flusso nello stream specificato. Usa il valore del flusso [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso del file in cui salvare i dati del flusso. |
| buffer_size | int | La dimensione del buffer. Per impostazione predefinita viene usato il valore [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save_with_buf_size_and_len(file_path, buffer_size, length) {#save_with_buf_size_and_len_file_path_buffer_size_length_17}


```
 save_with_buf_size_and_len(file_path, buffer_size, length) 
```

Salva (copia) i dati del flusso nello stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso del file in cui salvare i dati del flusso. |
| buffer_size | int | La dimensione del buffer. Per impostazione predefinita viene usato il valore [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |
| length | int | La lunghezza dei dati del flusso da copiare. Per impostazione predefinita la lunghezza è impostata al valore di [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: seek(offset, origin) {#seek_offset_origin_18}


```
 seek(offset, origin) 
```

Imposta la posizione all'interno del flusso corrente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| offset | int | Una compensazione in byte relativa al parametro _origin_. Questo valore rappresenta lo spostamento dalla posizione iniziale del flusso passata nel costruttore di StreamContainer. |
| origin | [SeekOrigin](/imaging/python-net/aspose.imaging/seekorigin/) | Un valore di tipo SeekOrigin che indica il punto di riferimento usato per ottenere la nuova posizione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | La nuova posizione all'interno del flusso corrente. |


### Method: to_bytes() {#to_bytes__19}


```
 to_bytes() 
```

Converte i dati del flusso in un array di interi.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Byte | I dati del flusso convertiti in un array di interi. |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_20}


```
 to_bytes(position, bytes_count) 
```

Converte i dati del flusso in un array di interi.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | int | La posizione da cui iniziare a leggere i byte. |
| bytes_count | int | Il conteggio dei byte da leggere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Byte | I dati del flusso convertiti in un array di interi. |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_21}


```
 write(buffer, offset, count) 
```

Scrive una sequenza di byte nello stream corrente e avanza la posizione corrente all'interno di questo stream del numero di byte scritti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| buffer | System.Byte | Un array di byte. Questo metodo copia _count_ byte da _buffer_ al flusso corrente. |
| offset | int | La compensazione in byte basata su zero in _buffer_ a partire dalla quale iniziare a copiare i byte nel flusso corrente. |
| count | int | Il numero di byte da scrivere nel flusso corrente. |

### Method: write(bytes) {#write_bytes_22}


```
 write(bytes) 
```

Scrive tutti i byte specificati nello stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| byte | System.Byte | I byte da scrivere. |

### Method: write_byte(value) {#write_byte_value_23}


```
 write_byte(value) 
```

Scrive un byte nella posizione corrente dello stream e avanza la posizione all'interno dello stream di un byte.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| valore | System.Byte | Il byte da scrivere nel flusso. |

### Method: write_to(stream_container) {#write_to_stream_container_24}


```
 write_to(stream_container) 
```

Copia i dati contenuti in un altro [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Il contenitore del flusso in cui copiare. |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_25}


```
 write_to(stream_container, length) 
```

Copia i dati contenuti in un altro [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Il contenitore del flusso in cui copiare. |
| length | int | Il conteggio dei byte da scrivere. |

