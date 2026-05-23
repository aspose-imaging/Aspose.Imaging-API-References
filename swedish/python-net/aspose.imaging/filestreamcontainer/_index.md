---
title: "FileStreamContainer klass"
type: docs
weight: 4810
url: /sv/python-net/aspose.imaging/filestreamcontainer/
---

**Summary:** Helper for file stream processing.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.FileStreamContainer

**Inheritance:** StreamContainer

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [statisk] | int | r | Anger antalet läs- och skrivbyte vid sekventiell läsning. |
| can_read | bool | r | Hämtar ett värde som indikerar om strömmen stödjer läsning. |
| can_seek | bool | r | Hämtar ett värde som indikerar om strömmen stödjer sökning. |
| can_write | bool | r | Hämtar ett värde som indikerar om strömmen stödjer skrivning. |
| disposed | bool | r | Hämtar ett värde som indikerar om den här instansen är frigjord. |
| file_path | string | r | Hämtar filsökvägen. |
| is_created | bool | r | Hämtar ett värde som indikerar om strömmen skapades explicit. |
| is_stream_disposed_on_close | bool | r | Hämtar ett värde som indikerar om denna ström avyttras vid stängning. |
| is_temporal | bool | r/w | Hämtar eller anger ett värde som indikerar om strömmen är temporär. |
| length | int | r/w | Hämtar eller anger strömlängden i byte. Detta värde är mindre än  av startpositionen för strömmen som skickas in i StreamContainer-konstruktorn. |
| position | int | r/w | Hämtar eller anger den aktuella positionen i strömmen. Detta värde representerar offset från startpositionen för strömmen som skickas in i StreamContainer-konstruktorn. |
| ström | _io.BufferedRandom | r | Hämtar datastreamen. |
| sync_root | System.Object | r | Hämtar ett objekt som kan användas för att synkronisera åtkomst till den synkroniserade resursen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_file_stream(file_location, is_temporal)](#create_file_stream_file_location_is_temporal_1) | Skapar en ny filström. |
| flush() | Rensar alla buffertar för denna ström och får all buffrad data att skrivas till den underliggande enheten. |
| [open_file_stream(file_location)](#open_file_stream_file_location_2) | Öppnar en befintlig filström. Om filströmmen inte finns kastas lämpligt undantag. |
| [read(buffer, offset, count)](#read_buffer_offset_count_3) | Läser en sekvens av byte från den aktuella strömmen och förflyttar positionen i strömmen med antalet lästa byte. |
| [read(bytes)](#read_bytes_4) | Läser byte för att fylla den angivna byte-bufferten. |
| [read_byte()](#read_byte__5) | Läser ett byte från strömmen och förflyttar positionen i strömmen med ett byte, eller returnerar -1 om man är i slutet av strömmen. |
| [save(destination_stream)](#save_destination_stream_6) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) och strömvärdet [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_7) | Sparar (kopierar) all strömmens data till den angivna strömmen. Använder strömvärdet [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_8) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| [save(file_path)](#save_file_path_9) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) och strömvärdet [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_10) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder strömvärdet [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_11) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| [save_to_stream(destination_stream)](#save_to_stream_destination_stream_12) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) och strömvärdet [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save_to_stream_with_buf_size(destination_stream, buffer_size)](#save_to_stream_with_buf_size_destination_stream_buffer_size_13) | Sparar (kopierar) all strömmens data till den angivna strömmen. Använder strömvärdet [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length)](#save_to_stream_with_buf_size_and_len_destination_stream_buffer_size_length_14) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| [save_with_buf_size(file_path, buffer_size)](#save_with_buf_size_file_path_buffer_size_15) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder strömvärdet [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save_with_buf_size_and_len(file_path, buffer_size, length)](#save_with_buf_size_and_len_file_path_buffer_size_length_16) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| [seek(offset, origin)](#seek_offset_origin_17) | Ställer in positionen i den aktuella strömmen. |
| seek_begin() | Ställer in strömmens position till början av strömmen. Detta värde representerar förskjutning från startpositionen för strömmen som skickas in i StreamContainer‑konstruktorn. |
| [to_bytes()](#to_bytes__18) | Konverterar strömmens data till en int‑array. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_19) | Konverterar strömmens data till en int‑array. |
| [write(buffer, offset, count)](#write_buffer_offset_count_20) | Skriver en sekvens av byte till den aktuella strömmen och flyttar den aktuella positionen i denna ström framåt med antalet skrivna byte. |
| [write(bytes)](#write_bytes_21) | Skriver alla angivna byte till strömmen. |
| [write_byte(value)](#write_byte_value_22) | Skriver ett byte till den aktuella positionen i strömmen och flyttar positionen i strömmen framåt med ett byte. |
| [write_to(stream_container)](#write_to_stream_container_23) | Kopierar det innehållande data till en annan [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [write_to(stream_container, length)](#write_to_stream_container_length_24) | Kopierar det innehållande data till en annan [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/). |


### Method: create_file_stream(file_location, is_temporal)  [static] {#create_file_stream_file_location_is_temporal_1}


```
 create_file_stream(file_location, is_temporal) 
```

Skapar en ny filström.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_location | string | Filens plats. |
| is_temporal | bool | Om den är inställd på <c>true</c> är filströmbehållaren temporär. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FileStreamContainer](/imaging/python-net/aspose.imaging/filestreamcontainer/) | Filströmbehållaren. |


### Method: open_file_stream(file_location)  [static] {#open_file_stream_file_location_2}


```
 open_file_stream(file_location) 
```

Öppnar en befintlig filström. Om filströmmen inte finns kastas lämpligt undantag.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_location | string | Filens plats. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FileStreamContainer](/imaging/python-net/aspose.imaging/filestreamcontainer/) | Filströmbehållaren. |


### Method: read(buffer, offset, count) {#read_buffer_offset_count_3}


```
 read(buffer, offset, count) 
```

Läser en sekvens av byte från den aktuella strömmen och förflyttar positionen i strömmen med antalet lästa byte.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| buffer | System.Byte | En array av byte. När denna metod returnerar innehåller bufferten den angivna byte‑arrayen med värdena mellan _offset_ och (_offset_ + _count_ - 1) ersatta av de byte som lästs från den aktuella källan. |
| offset | int | Det nollbaserade byte‑offsetet i _buffer_ där lagringen av data som lästs från den aktuella strömmen ska börja. |
| count | int | Det maximala antalet byte som ska läsas från den aktuella strömmen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Det totala antalet byte som lästs in i bufferten. Detta kan vara mindre än antalet begärda byte om så många byte för närvarande inte är tillgängliga, eller noll (0) om slutet av strömmen har nåtts. |


### Method: read(bytes) {#read_bytes_4}


```
 read(bytes) 
```

Läser byte för att fylla den angivna byte-bufferten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| byte | System.Byte | Byte att fylla. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Antalet lästa byte. Detta värde kan vara mindre än antalet byte i bufferten om det inte finns tillräckligt med byte i strömmen. |


### Method: read_byte() {#read_byte__5}


```
 read_byte() 
```

Läser ett byte från strömmen och förflyttar positionen i strömmen med ett byte, eller returnerar -1 om man är i slutet av strömmen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Den osignerade byten kastas till en Int32, eller -1 om den är i slutet av strömmen. |


### Method: save(destination_stream) {#save_destination_stream_6}


```
 save(destination_stream) 
```

Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) och strömvärdet [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Strömmen att spara data till. |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_7}


```
 save(destination_stream, buffer_size) 
```

Sparar (kopierar) all strömmens data till den angivna strömmen. Använder strömvärdet [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Strömmen att spara data till. |
| buffer_size | int | Bufferten. |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_8}


```
 save(destination_stream, buffer_size, length) 
```

Sparar (kopierar) strömmens data till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Strömmen att spara data till. |
| buffer_size | int | Buffertens storlek. Som standard används värdet [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |
| length | int | Strömdatas längd att kopiera. Som standard är längden satt till värdet för [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save(file_path) {#save_file_path_9}


```
 save(file_path) 
```

Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) och strömvärdet [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen att spara strömdatan till. |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_10}


```
 save(file_path, buffer_size) 
```

Sparar (kopierar) strömmens data till den angivna strömmen. Använder strömvärdet [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen att spara strömdatan till. |
| buffer_size | int | Buffertens storlek. Som standard används värdet [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_11}


```
 save(file_path, buffer_size, length) 
```

Sparar (kopierar) strömmens data till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen att spara strömdatan till. |
| buffer_size | int | Buffertens storlek. Som standard används värdet [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |
| length | int | Strömdatas längd att kopiera. Som standard är längden satt till värdet för [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save_to_stream(destination_stream) {#save_to_stream_destination_stream_12}


```
 save_to_stream(destination_stream) 
```

Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) och strömvärdet [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Strömmen att spara data till. |

### Method: save_to_stream_with_buf_size(destination_stream, buffer_size) {#save_to_stream_with_buf_size_destination_stream_buffer_size_13}


```
 save_to_stream_with_buf_size(destination_stream, buffer_size) 
```

Sparar (kopierar) all strömmens data till den angivna strömmen. Använder strömvärdet [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Strömmen att spara data till. |
| buffer_size | int | Bufferten. |

### Method: save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length) {#save_to_stream_with_buf_size_and_len_destination_stream_buffer_size_length_14}


```
 save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length) 
```

Sparar (kopierar) strömmens data till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Strömmen att spara data till. |
| buffer_size | int | Buffertens storlek. Som standard används värdet [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |
| length | int | Strömdatas längd att kopiera. Som standard är längden satt till värdet för [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save_with_buf_size(file_path, buffer_size) {#save_with_buf_size_file_path_buffer_size_15}


```
 save_with_buf_size(file_path, buffer_size) 
```

Sparar (kopierar) strömmens data till den angivna strömmen. Använder strömvärdet [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen att spara strömdatan till. |
| buffer_size | int | Buffertens storlek. Som standard används värdet [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save_with_buf_size_and_len(file_path, buffer_size, length) {#save_with_buf_size_and_len_file_path_buffer_size_length_16}


```
 save_with_buf_size_and_len(file_path, buffer_size, length) 
```

Sparar (kopierar) strömmens data till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen att spara strömdatan till. |
| buffer_size | int | Buffertens storlek. Som standard används värdet [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |
| length | int | Strömdatas längd att kopiera. Som standard är längden satt till värdet för [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: seek(offset, origin) {#seek_offset_origin_17}


```
 seek(offset, origin) 
```

Ställer in positionen i den aktuella strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| offset | int | En byteoffset relativt _origin_-parametern. Detta värde representerar offset från startpositionen för strömmen som skickas in i StreamContainer-konstruktorn. |
| origin | [SeekOrigin](/imaging/python-net/aspose.imaging/seekorigin/) | Ett värde av typen SeekOrigin som indikerar referenspunkten som används för att erhålla den nya positionen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Den nya positionen inom den aktuella strömmen. |


### Method: to_bytes() {#to_bytes__18}


```
 to_bytes() 
```

Konverterar strömmens data till en int‑array.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Byte | Strömdatan konverterad till int‑arrayen. |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_19}


```
 to_bytes(position, bytes_count) 
```

Konverterar strömmens data till en int‑array.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | int | Positionen att börja läsa bytes från. |
| bytes_count | int | Antalet bytes att läsa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Byte | Strömdatan konverterad till int‑arrayen. |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_20}


```
 write(buffer, offset, count) 
```

Skriver en sekvens av byte till den aktuella strömmen och flyttar den aktuella positionen i denna ström framåt med antalet skrivna byte.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| buffer | System.Byte | En array av bytes. Denna metod kopierar _count_ bytes från _buffer_ till den aktuella strömmen. |
| offset | int | Den nollbaserade byteoffseten i _buffer_ där kopieringen av bytes till den aktuella strömmen ska börja. |
| count | int | Antalet bytes som ska skrivas till den aktuella strömmen. |

### Method: write(bytes) {#write_bytes_21}


```
 write(bytes) 
```

Skriver alla angivna byte till strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| byte | System.Byte | Bytes att skriva. |

### Method: write_byte(value) {#write_byte_value_22}


```
 write_byte(value) 
```

Skriver ett byte till den aktuella positionen i strömmen och flyttar positionen i strömmen framåt med ett byte.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| värde | System.Byte | Byte att skriva till strömmen. |

### Method: write_to(stream_container) {#write_to_stream_container_23}


```
 write_to(stream_container) 
```

Kopierar det innehållande data till en annan [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Strömbehållaren att kopiera till. |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_24}


```
 write_to(stream_container, length) 
```

Kopierar det innehållande data till en annan [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Strömbehållaren att kopiera till. |
| length | int | Antalet bytes att skriva. |

