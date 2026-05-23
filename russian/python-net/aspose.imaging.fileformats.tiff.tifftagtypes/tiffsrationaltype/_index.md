---
title: "Класс TiffSRationalType"
type: docs
weight: 140
url: /ru/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/
---

**Summary:** The tiff signed rational type.

**Module:** [aspose.imaging.fileformats.tiff.tifftagtypes](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/)

**Full Name:** aspose.imaging.fileformats.tiff.tifftagtypes.TiffSRationalType

**Inheritance:** TiffCommonArrayType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffSRationalType(tag_id)](#TiffSRationalType_tag_id_1) | Инициализирует новый экземпляр [TiffSRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/) класса. |
| [TiffSRationalType(tag_id)](#TiffSRationalType_tag_id_2) | Инициализирует новый экземпляр [TiffSRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/) класса. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| count | int | r | Получает количество элементов. |
| data_size | int | r | Получает размер значения тега. |
| element_size | System.Byte | r | Получает размер элемента в байтах. |
| id | int | r | Получает идентификатор тега как число. |
| is_valid | bool | r | Получает значение, указывающее, действительны ли данные тега. Действительный тег содержит данные, которые могут быть сохранены. Недействительный тег не может быть сохранён. |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | r | Получает идентификатор тега. |
| tag_type | [TiffDataTypes](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffdatatypes/) | r | Получает тип тега. |
| значение | System.Object | r/w | Получает или задает значение, которое содержит этот тип данных. |
| values | [TiffSRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | Получает или задает значения. |
| values_container | System.Array | r | Получает контейнер значений. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | Сравнивает текущий экземпляр с другим объектом того же типа и возвращает целое число, указывающее, предшествует ли текущий экземпляр, следует ли за ним или находится в том же положении в порядке сортировки, что и другой объект. |
| [create_with_tag(tag_id)](#create_with_tag_tag_id_2) | Инициализирует новый экземпляр [TiffSRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/) класса. |
| [create_with_tag_id(tag_id)](#create_with_tag_id_tag_id_3) | Инициализирует новый экземпляр [TiffSRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/) класса. |
| [deep_clone()](#deep_clone__4) | Выполняет глубокое клонирование этого экземпляра. |
| [get_additional_data_size(size_of_tag_value)](#get_additional_data_size_size_of_tag_value_5) | Получает размер дополнительного значения тега в байтах (в случае, если тег не может вместить всё значение тега). |
| [get_aligned_data_size(size_of_tag_value)](#get_aligned_data_size_size_of_tag_value_6) | Получает размер данных, выровненный по границе 4‑байтов (int) или 8‑байтов (long). |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_7) | Читает данные тега. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_8) | Записывает дополнительные данные тега. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_9) | Записывает значение тега или дополнительное смещение. |


### Constructor: TiffSRationalType(tag_id) {#TiffSRationalType_tag_id_1}


```
 TiffSRationalType(tag_id) 
```

Инициализирует новый экземпляр [TiffSRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/) класса.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Идентификатор тега. |

### Constructor: TiffSRationalType(tag_id) {#TiffSRationalType_tag_id_2}


```
 TiffSRationalType(tag_id) 
```

Инициализирует новый экземпляр [TiffSRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/) класса.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tag_id | int | Идентификатор тега. |

### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

Сравнивает текущий экземпляр с другим объектом того же типа и возвращает целое число, указывающее, предшествует ли текущий экземпляр, следует ли за ним или находится в том же положении в порядке сортировки, что и другой объект.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| obj | System.Object | Объект для сравнения с этим экземпляром. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | 32‑разрядное знаковое целое число, указывающее относительный порядок сравниваемых объектов. Возвращаемое значение имеет следующие значения:<br/>            Значение<br/>            Смысл<br/>            Меньше нуля<br/>            Этот экземпляр меньше _obj_.<br/>            Ноль<br/>            Этот экземпляр равен _obj_.<br/>            Больше нуля<br/>            Этот экземпляр больше _obj_. |


### Method: create_with_tag(tag_id)  [static] {#create_with_tag_tag_id_2}


```
 create_with_tag(tag_id) 
```

Инициализирует новый экземпляр [TiffSRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/) класса.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Идентификатор тега. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffSRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/) |  |


### Method: create_with_tag_id(tag_id)  [static] {#create_with_tag_id_tag_id_3}


```
 create_with_tag_id(tag_id) 
```

Инициализирует новый экземпляр [TiffSRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/) класса.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tag_id | int | Идентификатор тега. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffSRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/) |  |


### Method: deep_clone() {#deep_clone__4}


```
 deep_clone() 
```

Выполняет глубокое клонирование этого экземпляра.

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Глубокая копия текущего экземпляра. |


### Method: get_additional_data_size(size_of_tag_value) {#get_additional_data_size_size_of_tag_value_5}


```
 get_additional_data_size(size_of_tag_value) 
```

Получает размер дополнительного значения тега в байтах (в случае, если тег не может вместить всё значение тега).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size_of_tag_value | System.Byte | Размер значения тега: 4 или 8 для BigTiff. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Размер дополнительных данных в байтах. |


### Method: get_aligned_data_size(size_of_tag_value) {#get_aligned_data_size_size_of_tag_value_6}


```
 get_aligned_data_size(size_of_tag_value) 
```

Получает размер данных, выровненный по границе 4‑байтов (int) или 8‑байтов (long).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size_of_tag_value | System.Byte | Размер значения тега. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Выровненный размер данных в байтах. |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_7}


```
 read_tag(data_stream, position) 
```

Читает данные тега.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | Поток данных. |
| position | int | Позиция тега. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Прочитанный тег. |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_8}


```
 write_additional_data(data_stream) 
```

Записывает дополнительные данные тега.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | Поток данных. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Фактически записанные байты. |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_9}


```
 write_tag(data_stream, additional_data_offset) 
```

Записывает значение тега или дополнительное смещение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | Поток данных. |
| additional_data_offset | int | Смещение дополнительных данных. |

