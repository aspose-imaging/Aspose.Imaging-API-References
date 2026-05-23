---
title: "StreamContainer Sınıfı"
type: docs
weight: 7340
url: /tr/python-net/aspose.imaging/streamcontainer/
---

**Summary:** Represents stream container which contains the stream and provides stream processing routines.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.StreamContainer

**Inheritance:** DisposableObject

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [StreamContainer(stream)](#StreamContainer_stream_1) | Yeni bir [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) sınıfı örneği başlatır. |
| [StreamContainer(stream, dispose_stream)](#StreamContainer_stream_dispose_stream_2) | Yeni bir [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [static] | int | r | Sıralı okuma sırasında okuma ve yazma bayt sayısını belirtir. |
| can_read | bool | r | Akışın okuma desteği olup olmadığını gösteren bir değer alır. |
| can_seek | bool | r | Akışın konumlandırma desteği olup olmadığını gösteren bir değer alır. |
| can_write | bool | r | Akışın yazma desteği olup olmadığını gösteren bir değer alır. |
| dağıtıldı | bool | r | Bu örneğin dağıtılıp dağıtılmadığını gösteren bir değer alır. |
| is_stream_disposed_on_close | bool | r | Bu akışın kapatıldığında serbest bırakılıp bırakılmadığını gösteren bir değer alır. |
| length | int | r/w | Akış uzunluğunu bayt cinsinden alır veya ayarlar. Bu değer, StreamContainer yapıcısına geçirilen başlangıç akış konumu tarafından ...'den daha azdır. |
| position | int | r/w | Akış içindeki geçerli konumu alır veya ayarlar. Bu değer, StreamContainer yapıcısına geçirilen başlangıç akış konumundan ofseti temsil eder. |
| akış | _io.BufferedRandom | r | Veri akışını alır. |
| sync_root | System.Object | r | Senkronize edilmiş kaynağa erişimi senkronize etmek için kullanılabilecek bir nesneyi alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| flush() | Bu akış için tüm tamponları temizler ve tamponlanmış verilerin alt cihazına yazılmasını sağlar. |
| [read(buffer, offset, count)](#read_buffer_offset_count_1) | Mevcut akıştan bir bayt dizisi okur ve okunan bayt sayısı kadar akış içindeki konumu ilerletir. |
| [read(bytes)](#read_bytes_2) | Belirtilen bayt tamponunu doldurmak için baytları okur. |
| [read_byte()](#read_byte__3) | Akıştan bir bayt okur ve konumu bir bayt ilerletir; akışın sonundaysa -1 döndürür. |
| [save(destination_stream)](#save_destination_stream_4) | Belirtilen akışa akışın verilerini kaydeder (kopyalar). Varsayılan tampon boyutu [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) ve akış [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) değeri kullanılır. |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_5) | Belirtilen akışa akışın tüm verilerini kaydeder (kopyalar). Akış [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) değeri kullanılır. |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_6) | Belirtilen akışa akışın verilerini kaydeder (kopyalar). |
| [save(file_path)](#save_file_path_7) | Belirtilen akışa akışın verilerini kaydeder (kopyalar). Varsayılan tampon boyutu [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) ve akış [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) değeri kullanılır. |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_8) | Belirtilen akışa akışın verilerini kaydeder (kopyalar). Akış [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) değeri kullanılır. |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_9) | Belirtilen akışa akışın verilerini kaydeder (kopyalar). |
| [save_to_stream(destination_stream)](#save_to_stream_destination_stream_10) | Belirtilen akışa akışın verilerini kaydeder (kopyalar). Varsayılan tampon boyutu [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) ve akış [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) değeri kullanılır. |
| [save_to_stream_with_buf_size(destination_stream, buffer_size)](#save_to_stream_with_buf_size_destination_stream_buffer_size_11) | Belirtilen akışa akışın tüm verilerini kaydeder (kopyalar). Akış [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) değeri kullanılır. |
| [save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length)](#save_to_stream_with_buf_size_and_len_destination_stream_buffer_size_length_12) | Belirtilen akışa akışın verilerini kaydeder (kopyalar). |
| [save_with_buf_size(file_path, buffer_size)](#save_with_buf_size_file_path_buffer_size_13) | Belirtilen akışa akışın verilerini kaydeder (kopyalar). Akış [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) değeri kullanılır. |
| [save_with_buf_size_and_len(file_path, buffer_size, length)](#save_with_buf_size_and_len_file_path_buffer_size_length_14) | Belirtilen akışa akışın verilerini kaydeder (kopyalar). |
| [seek(offset, origin)](#seek_offset_origin_15) | Geçerli akış içindeki konumu ayarlar. |
| seek_begin() | Akış konumunu akışın başına ayarlar. Bu değer, StreamContainer yapıcısına geçirilen başlangıç akış konumundan ofseti temsil eder. |
| [to_bytes()](#to_bytes__16) | Akış verilerini int dizisine dönüştürür. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_17) | Akış verilerini int dizisine dönüştürür. |
| [write(buffer, offset, count)](#write_buffer_offset_count_18) | Bir bayt dizisini geçerli akışa yazar ve bu akıştaki geçerli konumu yazılan bayt sayısı kadar ilerletir. |
| [write(bytes)](#write_bytes_19) | Belirtilen tüm baytları akışa yazar. |
| [write_byte(value)](#write_byte_value_20) | Akıştaki geçerli konuma bir bayt yazar ve akıştaki konumu bir bayt ilerletir. |
| [write_to(stream_container)](#write_to_stream_container_21) | İçerilen verileri başka bir [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) içine kopyalar. |
| [write_to(stream_container, length)](#write_to_stream_container_length_22) | İçerilen verileri başka bir [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) içine kopyalar. |


### Constructor: StreamContainer(stream) {#StreamContainer_stream_1}


```
 StreamContainer(stream) 
```

Yeni bir [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Akış. |

### Constructor: StreamContainer(stream, dispose_stream) {#StreamContainer_stream_dispose_stream_2}


```
 StreamContainer(stream, dispose_stream) 
```

Yeni bir [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Veri akışı. |
| dispose_stream | bool | eğer <c>true</c> olarak ayarlanırsa, konteyner atıldığında akış da serbest bırakılır. |

### Method: read(buffer, offset, count) {#read_buffer_offset_count_1}


```
 read(buffer, offset, count) 
```

Mevcut akıştan bir bayt dizisi okur ve okunan bayt sayısı kadar akış içindeki konumu ilerletir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| tampon | System.Byte | Bir bayt dizisi. Bu yöntem döndüğünde, tampon belirtilen bayt dizisini içerir ve _offset_ ile (_offset_ + _count_ - 1) arasındaki değerler geçerli kaynaktan okunan baytlarla değiştirilir. |
| offset | int | Geçerli akıştan okunan verileri saklamaya başlanacak _buffer_ içindeki sıfır tabanlı bayt ofseti. |
| count | int | Geçerli akıştan okunacak azami bayt sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Tampona okunan toplam bayt sayısı. Bu değer, istenen bayt sayısından az olabilir eğer o kadar bayt şu anda mevcut değilse, ya da akışın sonuna ulaşılmışsa sıfır (0) olabilir. |


### Method: read(bytes) {#read_bytes_2}


```
 read(bytes) 
```

Belirtilen bayt tamponunu doldurmak için baytları okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| baytlar | System.Byte | Doldurulacak baytlar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Okunan bayt sayısı. Bu değer, akışta yeterli bayt yoksa tampondaki bayt sayısından az olabilir. |


### Method: read_byte() {#read_byte__3}


```
 read_byte() 
```

Akıştan bir bayt okur ve konumu bir bayt ilerletir; akışın sonundaysa -1 döndürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Akışın sonunda ise -1, aksi takdirde unsigned byte Int32'e dönüştürülür. |


### Method: save(destination_stream) {#save_destination_stream_4}


```
 save(destination_stream) 
```

Belirtilen akışa akışın verilerini kaydeder (kopyalar). Varsayılan tampon boyutu [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) ve akış [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) değeri kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Verilerin kaydedileceği akış. |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_5}


```
 save(destination_stream, buffer_size) 
```

Belirtilen akışa akışın tüm verilerini kaydeder (kopyalar). Akış [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) değeri kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Verilerin kaydedileceği akış. |
| tampon_boyutu | int | Arabellek. |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_6}


```
 save(destination_stream, buffer_size, length) 
```

Belirtilen akışa akışın verilerini kaydeder (kopyalar).

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Verilerin kaydedileceği akış. |
| buffer_size | int | Arabellek boyutu. Varsayılan olarak [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) değeri kullanılır. |
| length | int | Kopyalanacak akış veri uzunluğu. Varsayılan olarak uzunluk, [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) değerine ayarlanır. |

### Method: save(file_path) {#save_file_path_7}


```
 save(file_path) 
```

Belirtilen akışa akışın verilerini kaydeder (kopyalar). Varsayılan tampon boyutu [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) ve akış [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) değeri kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Akış verisinin kaydedileceği dosya yolu. |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_8}


```
 save(file_path, buffer_size) 
```

Belirtilen akışa akışın verilerini kaydeder (kopyalar). Akış [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) değeri kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Akış verisinin kaydedileceği dosya yolu. |
| buffer_size | int | Arabellek boyutu. Varsayılan olarak [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) değeri kullanılır. |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_9}


```
 save(file_path, buffer_size, length) 
```

Belirtilen akışa akışın verilerini kaydeder (kopyalar).

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Akış verisinin kaydedileceği dosya yolu. |
| buffer_size | int | Arabellek boyutu. Varsayılan olarak [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) değeri kullanılır. |
| length | int | Kopyalanacak akış veri uzunluğu. Varsayılan olarak uzunluk, [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) değerine ayarlanır. |

### Method: save_to_stream(destination_stream) {#save_to_stream_destination_stream_10}


```
 save_to_stream(destination_stream) 
```

Belirtilen akışa akışın verilerini kaydeder (kopyalar). Varsayılan tampon boyutu [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) ve akış [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) değeri kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Verilerin kaydedileceği akış. |

### Method: save_to_stream_with_buf_size(destination_stream, buffer_size) {#save_to_stream_with_buf_size_destination_stream_buffer_size_11}


```
 save_to_stream_with_buf_size(destination_stream, buffer_size) 
```

Belirtilen akışa akışın tüm verilerini kaydeder (kopyalar). Akış [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) değeri kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Verilerin kaydedileceği akış. |
| tampon_boyutu | int | Arabellek. |

### Method: save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length) {#save_to_stream_with_buf_size_and_len_destination_stream_buffer_size_length_12}


```
 save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length) 
```

Belirtilen akışa akışın verilerini kaydeder (kopyalar).

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Verilerin kaydedileceği akış. |
| buffer_size | int | Arabellek boyutu. Varsayılan olarak [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) değeri kullanılır. |
| length | int | Kopyalanacak akış veri uzunluğu. Varsayılan olarak uzunluk, [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) değerine ayarlanır. |

### Method: save_with_buf_size(file_path, buffer_size) {#save_with_buf_size_file_path_buffer_size_13}


```
 save_with_buf_size(file_path, buffer_size) 
```

Belirtilen akışa akışın verilerini kaydeder (kopyalar). Akış [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) değeri kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Akış verisinin kaydedileceği dosya yolu. |
| buffer_size | int | Arabellek boyutu. Varsayılan olarak [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) değeri kullanılır. |

### Method: save_with_buf_size_and_len(file_path, buffer_size, length) {#save_with_buf_size_and_len_file_path_buffer_size_length_14}


```
 save_with_buf_size_and_len(file_path, buffer_size, length) 
```

Belirtilen akışa akışın verilerini kaydeder (kopyalar).

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Akış verisinin kaydedileceği dosya yolu. |
| buffer_size | int | Arabellek boyutu. Varsayılan olarak [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) değeri kullanılır. |
| length | int | Kopyalanacak akış veri uzunluğu. Varsayılan olarak uzunluk, [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) değerine ayarlanır. |

### Method: seek(offset, origin) {#seek_offset_origin_15}


```
 seek(offset, origin) 
```

Geçerli akış içindeki konumu ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| offset | int | _origin_ parametresine göre bir byte ofseti. Bu değer, StreamContainer yapıcısına geçirilen başlangıç akış konumundan ofseti temsil eder. |
| origin | [SeekOrigin](/imaging/python-net/aspose.imaging/seekorigin/) | Yeni konumu elde etmek için kullanılan referans noktasını belirten SeekOrigin tipinde bir değer. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Mevcut akış içindeki yeni konum. |


### Method: to_bytes() {#to_bytes__16}


```
 to_bytes() 
```

Akış verilerini int dizisine dönüştürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Byte | int dizisine dönüştürülmüş akış verisi. |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_17}


```
 to_bytes(position, bytes_count) 
```

Akış verilerini int dizisine dönüştürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| position | int | Byte'ların okunmaya başlanacağı konum. |
| bytes_count | int | Okunacak byte sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Byte | int dizisine dönüştürülmüş akış verisi. |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_18}


```
 write(buffer, offset, count) 
```

Bir bayt dizisini geçerli akışa yazar ve bu akıştaki geçerli konumu yazılan bayt sayısı kadar ilerletir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| tampon | System.Byte | Byte dizisi. Bu yöntem, _buffer_'dan mevcut akışa _count_ byte kopyalar. |
| offset | int | Mevcut akışa byte kopyalamaya başlanacak _buffer_'daki sıfır tabanlı byte ofseti. |
| count | int | Mevcut akışa yazılacak byte sayısı. |

### Method: write(bytes) {#write_bytes_19}


```
 write(bytes) 
```

Belirtilen tüm baytları akışa yazar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| baytlar | System.Byte | Yazılacak byte'lar. |

### Method: write_byte(value) {#write_byte_value_20}


```
 write_byte(value) 
```

Akıştaki geçerli konuma bir bayt yazar ve akıştaki konumu bir bayt ilerletir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| değer | System.Byte | Akışa yazılacak byte. |

### Method: write_to(stream_container) {#write_to_stream_container_21}


```
 write_to(stream_container) 
```

İçerilen verileri başka bir [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) içine kopyalar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Kopyalanacak akış konteyneri. |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_22}


```
 write_to(stream_container, length) 
```

İçerilen verileri başka bir [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) içine kopyalar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Kopyalanacak akış konteyneri. |
| length | int | Yazılacak byte sayısı. |

