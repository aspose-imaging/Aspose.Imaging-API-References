---
title: "Класс BigTiffReader"
type: docs
weight: 10
url: /ru/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/
---

**Summary:** The little endian BigTiff reader.

**Module:** [aspose.imaging.fileformats.tiff.filemanagement.bigtiff](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/)

**Full Name:** aspose.imaging.fileformats.tiff.filemanagement.bigtiff.BigTiffReader

**Inheritance:** TiffStreamReader

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BigTiffReader(data)](#BigTiffReader_data_1) | Инициализирует новый экземпляр класса [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/). |
| [BigTiffReader(data, start_index)](#BigTiffReader_data_start_index_2) | Инициализирует новый экземпляр класса [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/). |
| [BigTiffReader(data, start_index, data_length)](#BigTiffReader_data_start_index_data_length_3) | Инициализирует новый экземпляр класса [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/). |
| [BigTiffReader(stream_container)](#BigTiffReader_stream_container_4) | Инициализирует новый экземпляр класса [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| length | int | r | Получает длину читателя. |
| throw_exceptions | bool | r/w | Получает или задает значение, указывающее, выбрасываются ли исключения при некорректной обработке данных (чтении или записи в поток). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | Считывает массив байтовых значений из потока. |
| [read_bytes(position, count)](#read_bytes_position_count_2) | Считывает массив беззнаковых байтовых значений из потока. |
| [read_double(position)](#read_double_position_3) | Считывает одно двойное значение из потока. |
| [read_double_array(position, count)](#read_double_array_position_count_4) | Считывает массив двойных значений из потока. |
| [read_float(position)](#read_float_position_5) | Считывает одно значение с плавающей запятой из потока. |
| [read_float_array(position, count)](#read_float_array_position_count_6) | Считывает массив значений с плавающей запятой из потока. |
| [read_long(position)](#read_long_position_7) | Считывает беззнаковое значение типа unsigned long из потока. |
| [read_long_array(position, count)](#read_long_array_position_count_8) | Считывает массив значений типа ulong из потока. |
| [read_rational(position)](#read_rational_position_9) | Считывает одно рациональное число из потока. |
| [read_rational_array(position, count)](#read_rational_array_position_count_10) | Считывает массив рациональных чисел из потока. |
| [read_s_byte(position)](#read_s_byte_position_11) | Считывает данные знакового байта из потока. |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_12) | Считывает массив значений знаковых байтов из потока. |
| [read_s_int(position)](#read_s_int_position_13) | Считывает значение знакового целого числа из потока. |
| [read_s_int_array(position, count)](#read_s_int_array_position_count_14) | Считывает массив значений знаковых целых чисел из потока. |
| [read_s_rational(position)](#read_s_rational_position_15) | Считывает одно знаковое рациональное число из потока. |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_16) | Считывает массив знаковых рациональных чисел из потока. |
| [read_s_short(position)](#read_s_short_position_17) | Прочитать знаковое значение short из потока. |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_18) | Читает массив знаковых значений short из потока. |
| [read_u_int(position)](#read_u_int_position_19) | Прочитать беззнаковое значение integer из потока. |
| [read_u_int_array(position, count)](#read_u_int_array_position_count_20) | Читает массив беззнаковых значений integer из потока. |
| [read_u_long(position)](#read_u_long_position_21) | Считывает беззнаковое значение типа unsigned long из потока. |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_22) | Считывает массив значений типа ulong из потока. |
| [read_u_short(position)](#read_u_short_position_23) | Прочитать беззнаковое значение short из потока. |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_24) | Читает массив беззнаковых значений integer из потока. |
| [to_stream_container(start_position)](#to_stream_container_start_position_25) | Преобразует базовые данные в контейнер потока. |


### Constructor: BigTiffReader(data) {#BigTiffReader_data_1}


```
 BigTiffReader(data) 
```

Инициализирует новый экземпляр класса [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | System.Byte | Массив байтов данных. |

### Constructor: BigTiffReader(data, start_index) {#BigTiffReader_data_start_index_2}


```
 BigTiffReader(data, start_index) 
```

Инициализирует новый экземпляр класса [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | System.Byte | Массив байтов данных. |
| start_index | int | Начальный индекс в _data_. |

### Constructor: BigTiffReader(data, start_index, data_length) {#BigTiffReader_data_start_index_data_length_3}


```
 BigTiffReader(data, start_index, data_length) 
```

Инициализирует новый экземпляр класса [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | System.Byte | Массив байтов данных. |
| start_index | int | Начальный индекс в _data_. |
| data_length | int | Длина данных. |

### Constructor: BigTiffReader(stream_container) {#BigTiffReader_stream_container_4}


```
 BigTiffReader(stream_container) 
```

Инициализирует новый экземпляр класса [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Контейнер потока. |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


```
 read_bytes(array, array_index, position, count) 
```

Считывает массив байтовых значений из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| array | System.Byte | Массив для заполнения. |
| array_index | int | Индекс массива, с которого начинать помещать значения. |
| position | int | Позиция потока для чтения. |
| count | int | Количество элементов для чтения. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Массив значений байт. |


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


```
 read_bytes(position, count) 
```

Считывает массив беззнаковых байтовых значений из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция для чтения. |
| count | int | Количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Byte | Массив беззнаковых значений байт. |


### Method: read_double(position) {#read_double_position_3}


```
 read_double(position) 
```

Считывает одно двойное значение из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция для чтения. |

**Returns**

| Тип | Описание |
| :- | :- |
| float | Одно значение double. |


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


```
 read_double_array(position, count) 
```

Считывает массив двойных значений из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция для чтения. |
| count | int | Количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| float[] | Массив значений double. |


### Method: read_float(position) {#read_float_position_5}


```
 read_float(position) 
```

Считывает одно значение с плавающей запятой из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция для чтения. |

**Returns**

| Тип | Описание |
| :- | :- |
| float | Одно значение float. |


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


```
 read_float_array(position, count) 
```

Считывает массив значений с плавающей запятой из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция для чтения. |
| count | int | Количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| float[] | Массив значений float. |


### Method: read_long(position) {#read_long_position_7}


```
 read_long(position) 
```

Считывает беззнаковое значение типа unsigned long из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция для чтения. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Беззнаковое значение short. |


### Method: read_long_array(position, count) {#read_long_array_position_count_8}


```
 read_long_array(position, count) 
```

Считывает массив значений типа ulong из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция для чтения. |
| count | int | Количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Массив ulong. |


### Method: read_rational(position) {#read_rational_position_9}


```
 read_rational(position) 
```

Считывает одно рациональное число из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция для чтения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Рациональное число. |


### Method: read_rational_array(position, count) {#read_rational_array_position_count_10}


```
 read_rational_array(position, count) 
```

Считывает массив рациональных чисел из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция для чтения. |
| count | int | Количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Массив рациональных значений. |


### Method: read_s_byte(position) {#read_s_byte_position_11}


```
 read_s_byte(position) 
```

Считывает данные знакового байта из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция для чтения. |

**Returns**

| Тип | Описание |
| :- | :- |
| System.SByte | Значение знакового байта. |


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_12}


```
 read_s_byte_array(position, count) 
```

Считывает массив значений знаковых байтов из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция для чтения. |
| count | int | Количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| System.SByte | Массив значений знаковых байтов. |


### Method: read_s_int(position) {#read_s_int_position_13}


```
 read_s_int(position) 
```

Считывает значение знакового целого числа из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция для чтения. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Значение знакового целого. |


### Method: read_s_int_array(position, count) {#read_s_int_array_position_count_14}


```
 read_s_int_array(position, count) 
```

Считывает массив значений знаковых целых чисел из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция для чтения. |
| count | int | Количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Массив значений знаковых целых. |


### Method: read_s_rational(position) {#read_s_rational_position_15}


```
 read_s_rational(position) 
```

Считывает одно знаковое рациональное число из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция для чтения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Знаковое рациональное число. |


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_16}


```
 read_s_rational_array(position, count) 
```

Считывает массив знаковых рациональных чисел из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция для чтения. |
| count | int | Количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffSRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Массив значений знаковых рациональных чисел. |


### Method: read_s_short(position) {#read_s_short_position_17}


```
 read_s_short(position) 
```

Прочитать знаковое значение short из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция для чтения. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Значение знакового short. |


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_18}


```
 read_s_short_array(position, count) 
```

Читает массив знаковых значений short из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция для чтения. |
| count | int | Количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Массив значений знаковых short. |


### Method: read_u_int(position) {#read_u_int_position_19}


```
 read_u_int(position) 
```

Прочитать беззнаковое значение integer из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция для чтения. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Значение беззнакового целого. |


### Method: read_u_int_array(position, count) {#read_u_int_array_position_count_20}


```
 read_u_int_array(position, count) 
```

Читает массив беззнаковых значений integer из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция для чтения. |
| count | int | Количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Массив значений беззнаковых целых. |


### Method: read_u_long(position) {#read_u_long_position_21}


```
 read_u_long(position) 
```

Считывает беззнаковое значение типа unsigned long из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция для чтения. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Беззнаковое значение short. |


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_22}


```
 read_u_long_array(position, count) 
```

Считывает массив значений типа ulong из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция для чтения. |
| count | int | Количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Массив ulong. |


### Method: read_u_short(position) {#read_u_short_position_23}


```
 read_u_short(position) 
```

Прочитать беззнаковое значение short из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция для чтения. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Беззнаковое значение short. |


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_24}


```
 read_u_short_array(position, count) 
```

Читает массив беззнаковых значений integer из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция для чтения. |
| count | int | Количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Массив значений беззнаковых целых. |


### Method: to_stream_container(start_position) {#to_stream_container_start_position_25}


```
 to_stream_container(start_position) 
```

Преобразует базовые данные в контейнер потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| start_position | int | Начальная позиция, с которой начинается преобразование. |

**Returns**

| Тип | Описание |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Объект [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) с преобразованными данными. |


