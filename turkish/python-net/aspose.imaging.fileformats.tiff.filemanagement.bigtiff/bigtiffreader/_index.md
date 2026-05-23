---
title: "BigTiffReader Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/
---

**Summary:** The little endian BigTiff reader.

**Module:** [aspose.imaging.fileformats.tiff.filemanagement.bigtiff](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/)

**Full Name:** aspose.imaging.fileformats.tiff.filemanagement.bigtiff.BigTiffReader

**Inheritance:** TiffStreamReader

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [BigTiffReader(data)](#BigTiffReader_data_1) | Yeni bir [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/) sınıf örneği başlatır. |
| [BigTiffReader(data, start_index)](#BigTiffReader_data_start_index_2) | Yeni bir [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/) sınıf örneği başlatır. |
| [BigTiffReader(data, start_index, data_length)](#BigTiffReader_data_start_index_data_length_3) | Yeni bir [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/) sınıf örneği başlatır. |
| [BigTiffReader(stream_container)](#BigTiffReader_stream_container_4) | Yeni bir [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/) sınıf örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| length | int | r | Okuyucu uzunluğunu alır. |
| throw_exceptions | bool | r/w | İstisnaların hatalı veri işleme (akışa okuma veya yazma) sırasında atılıp atılmayacağını gösteren bir değeri alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | Akıştan bayt değerleri dizisini okur. |
| [read_bytes(position, count)](#read_bytes_position_count_2) | Akıştan işaretsiz bayt değerleri dizisini okur. |
| [read_double(position)](#read_double_position_3) | Akıştan tek bir double değer okur. |
| [read_double_array(position, count)](#read_double_array_position_count_4) | Akıştan double değerleri dizisini okur. |
| [read_float(position)](#read_float_position_5) | Akıştan tek bir float değer okur. |
| [read_float_array(position, count)](#read_float_array_position_count_6) | Akıştan float değerleri dizisini okur. |
| [read_long(position)](#read_long_position_7) | Akıştan işaretsiz uzun değer okur. |
| [read_long_array(position, count)](#read_long_array_position_count_8) | Akıştan ulong değerleri dizisini okur. |
| [read_rational(position)](#read_rational_position_9) | Akıştan tek bir rasyonel sayı değeri okur. |
| [read_rational_array(position, count)](#read_rational_array_position_count_10) | Akıştan rasyonel değerleri dizisini okur. |
| [read_s_byte(position)](#read_s_byte_position_11) | Akıştan işaretli bayt verilerini okur. |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_12) | Akıştan işaretli bayt değerleri dizisini okur. |
| [read_s_int(position)](#read_s_int_position_13) | Akıştan işaretli tamsayı değeri okur. |
| [read_s_int_array(position, count)](#read_s_int_array_position_count_14) | Akıştan işaretli tamsayı değerleri dizisini okur. |
| [read_s_rational(position)](#read_s_rational_position_15) | Akıştan tek bir işaretli rasyonel sayı değeri okur. |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_16) | Akıştan işaretli rasyonel değerleri dizisini okur. |
| [read_s_short(position)](#read_s_short_position_17) | Akıştan işaretli kısa değeri oku. |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_18) | Akıştan işaretli kısa değerler dizisini okur. |
| [read_u_int(position)](#read_u_int_position_19) | Akıştan işaretsiz tamsayı değerini oku. |
| [read_u_int_array(position, count)](#read_u_int_array_position_count_20) | Akıştan işaretsiz tamsayı değerleri dizisini okur. |
| [read_u_long(position)](#read_u_long_position_21) | Akıştan işaretsiz uzun değer okur. |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_22) | Akıştan ulong değerleri dizisini okur. |
| [read_u_short(position)](#read_u_short_position_23) | Akıştan işaretsiz kısa değeri oku. |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_24) | Akıştan işaretsiz tamsayı değerleri dizisini okur. |
| [to_stream_container(start_position)](#to_stream_container_start_position_25) | Temel veriyi akış konteynerine dönüştürür. |


### Constructor: BigTiffReader(data) {#BigTiffReader_data_1}


```
 BigTiffReader(data) 
```

Yeni bir [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/) sınıf örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| veri | System.Byte | Bayt dizisi verisi. |

### Constructor: BigTiffReader(data, start_index) {#BigTiffReader_data_start_index_2}


```
 BigTiffReader(data, start_index) 
```

Yeni bir [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/) sınıf örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| veri | System.Byte | Bayt dizisi verisi. |
| start_index | int |  _data_ içindeki başlangıç indeksi. |

### Constructor: BigTiffReader(data, start_index, data_length) {#BigTiffReader_data_start_index_data_length_3}


```
 BigTiffReader(data, start_index, data_length) 
```

Yeni bir [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/) sınıf örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| veri | System.Byte | Bayt dizisi verisi. |
| start_index | int |  _data_ içindeki başlangıç indeksi. |
| data_length | int | Verinin uzunluğu. |

### Constructor: BigTiffReader(stream_container) {#BigTiffReader_stream_container_4}


```
 BigTiffReader(stream_container) 
```

Yeni bir [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/) sınıf örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Akış kapsayıcısı. |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


```
 read_bytes(array, array_index, position, count) 
```

Akıştan bayt değerleri dizisini okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| array | System.Byte | Doldurulacak dizi. |
| array_index | int | Değerleri koymaya başlanacak dizi indeksi. |
| position | int | Okunacak akış konumu. |
| count | int | Okunacak öğe sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Bayt değerleri dizisi. |


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


```
 read_bytes(position, count) 
```

Akıştan işaretsiz bayt değerleri dizisini okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| position | int | Okunacak konum. |
| count | int | Öğe sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Byte | İşaretsiz bayt değerleri dizisi. |


### Method: read_double(position) {#read_double_position_3}


```
 read_double(position) 
```

Akıştan tek bir double değer okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| position | int | Okunacak konum. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| float | Tek double değer. |


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


```
 read_double_array(position, count) 
```

Akıştan double değerleri dizisini okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| position | int | Okunacak konum. |
| count | int | Öğe sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| float[] | Double değerleri dizisi. |


### Method: read_float(position) {#read_float_position_5}


```
 read_float(position) 
```

Akıştan tek bir float değer okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| position | int | Okunacak konum. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| float | Tek float değer. |


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


```
 read_float_array(position, count) 
```

Akıştan float değerleri dizisini okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| position | int | Okunacak konum. |
| count | int | Öğe sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| float[] | Float değerleri dizisi. |


### Method: read_long(position) {#read_long_position_7}


```
 read_long(position) 
```

Akıştan işaretsiz uzun değer okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| position | int | Okunacak konum. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | İşaretsiz kısa değer. |


### Method: read_long_array(position, count) {#read_long_array_position_count_8}


```
 read_long_array(position, count) 
```

Akıştan ulong değerleri dizisini okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| position | int | Okunacak konum. |
| count | int | Öğe sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | ulong dizisi. |


### Method: read_rational(position) {#read_rational_position_9}


```
 read_rational(position) 
```

Akıştan tek bir rasyonel sayı değeri okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| position | int | Okunacak konum. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | rasyonel sayı. |


### Method: read_rational_array(position, count) {#read_rational_array_position_count_10}


```
 read_rational_array(position, count) 
```

Akıştan rasyonel değerleri dizisini okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| position | int | Okunacak konum. |
| count | int | Öğe sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | rasyonel değerlerin dizisi. |


### Method: read_s_byte(position) {#read_s_byte_position_11}


```
 read_s_byte(position) 
```

Akıştan işaretli bayt verilerini okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| position | int | Okunacak konum. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.SByte | işaretli bayt değeri. |


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_12}


```
 read_s_byte_array(position, count) 
```

Akıştan işaretli bayt değerleri dizisini okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| position | int | Okunacak konum. |
| count | int | Öğe sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.SByte | işaretli bayt değerlerinin dizisi. |


### Method: read_s_int(position) {#read_s_int_position_13}


```
 read_s_int(position) 
```

Akıştan işaretli tamsayı değeri okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| position | int | Okunacak konum. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | işaretli tamsayı değeri. |


### Method: read_s_int_array(position, count) {#read_s_int_array_position_count_14}


```
 read_s_int_array(position, count) 
```

Akıştan işaretli tamsayı değerleri dizisini okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| position | int | Okunacak konum. |
| count | int | Öğe sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | işaretli tamsayı değerlerinin dizisi. |


### Method: read_s_rational(position) {#read_s_rational_position_15}


```
 read_s_rational(position) 
```

Akıştan tek bir işaretli rasyonel sayı değeri okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| position | int | Okunacak konum. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | işaretli rasyonel sayı. |


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_16}


```
 read_s_rational_array(position, count) 
```

Akıştan işaretli rasyonel değerleri dizisini okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| position | int | Okunacak konum. |
| count | int | Öğe sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffSRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | işaretli rasyonel değerlerin dizisi. |


### Method: read_s_short(position) {#read_s_short_position_17}


```
 read_s_short(position) 
```

Akıştan işaretli kısa değeri oku.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| position | int | Okunacak konum. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | işaretli kısa değer. |


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_18}


```
 read_s_short_array(position, count) 
```

Akıştan işaretli kısa değerler dizisini okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| position | int | Okunacak konum. |
| count | int | Öğe sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | işaretli kısa değerlerin dizisi. |


### Method: read_u_int(position) {#read_u_int_position_19}


```
 read_u_int(position) 
```

Akıştan işaretsiz tamsayı değerini oku.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| position | int | Okunacak konum. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | işaretsiz tamsayı değeri. |


### Method: read_u_int_array(position, count) {#read_u_int_array_position_count_20}


```
 read_u_int_array(position, count) 
```

Akıştan işaretsiz tamsayı değerleri dizisini okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| position | int | Okunacak konum. |
| count | int | Öğe sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | işaretsiz tamsayı değerlerinin dizisi. |


### Method: read_u_long(position) {#read_u_long_position_21}


```
 read_u_long(position) 
```

Akıştan işaretsiz uzun değer okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| position | int | Okunacak konum. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | İşaretsiz kısa değer. |


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_22}


```
 read_u_long_array(position, count) 
```

Akıştan ulong değerleri dizisini okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| position | int | Okunacak konum. |
| count | int | Öğe sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | ulong dizisi. |


### Method: read_u_short(position) {#read_u_short_position_23}


```
 read_u_short(position) 
```

Akıştan işaretsiz kısa değeri oku.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| position | int | Okunacak konum. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | İşaretsiz kısa değer. |


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_24}


```
 read_u_short_array(position, count) 
```

Akıştan işaretsiz tamsayı değerleri dizisini okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| position | int | Okunacak konum. |
| count | int | Öğe sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | işaretsiz tamsayı değerlerinin dizisi. |


### Method: to_stream_container(start_position) {#to_stream_container_start_position_25}


```
 to_stream_container(start_position) 
```

Temel veriyi akış konteynerine dönüştürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| start_position | int | Dönüştürmeye başlanacak başlangıç konumu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Dönüştürülmüş veriye sahip [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/). |


