---
title: "الفئة BigTiffReader"
type: docs
weight: 10
url: /ar/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/
---

**Summary:** The little endian BigTiff reader.

**Module:** [aspose.imaging.fileformats.tiff.filemanagement.bigtiff](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/)

**Full Name:** aspose.imaging.fileformats.tiff.filemanagement.bigtiff.BigTiffReader

**Inheritance:** TiffStreamReader

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [BigTiffReader(data)](#BigTiffReader_data_1) | يُنشئ مثلاً جديدًا من الفئة [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/) |
| [BigTiffReader(data, start_index)](#BigTiffReader_data_start_index_2) | يُنشئ مثلاً جديدًا من الفئة [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/) |
| [BigTiffReader(data, start_index, data_length)](#BigTiffReader_data_start_index_data_length_3) | يُنشئ مثلاً جديدًا من الفئة [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/) |
| [BigTiffReader(stream_container)](#BigTiffReader_stream_container_4) | يُنشئ مثلاً جديدًا من الفئة [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| length | int | r | يحصل على طول القارئ. |
| throw_exceptions | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الاستثناءات تُرمى عند معالجة البيانات غير الصحيحة (القراءة أو الكتابة إلى التدفق). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | يقرأ مصفوفة من قيم البايت من التدفق. |
| [read_bytes(position, count)](#read_bytes_position_count_2) | يقرأ مصفوفة من قيم البايت غير الموقّعة من التدفق. |
| [read_double(position)](#read_double_position_3) | يقرأ قيمة مزدوجة واحدة من التدفق. |
| [read_double_array(position, count)](#read_double_array_position_count_4) | يقرأ مصفوفة من القيم المزدوجة من التدفق. |
| [read_float(position)](#read_float_position_5) | يقرأ قيمة عائمة واحدة من التدفق. |
| [read_float_array(position, count)](#read_float_array_position_count_6) | يقرأ مصفوفة من القيم العائمة من التدفق. |
| [read_long(position)](#read_long_position_7) | يقرأ قيمة طويلة غير موقعة من التدفق. |
| [read_long_array(position, count)](#read_long_array_position_count_8) | يقرأ مصفوفة من قيم ulong من التدفق. |
| [read_rational(position)](#read_rational_position_9) | يقرأ قيمة عدد كسرية واحدة من التدفق. |
| [read_rational_array(position, count)](#read_rational_array_position_count_10) | يقرأ مصفوفة من القيم الكسرية من التدفق. |
| [read_s_byte(position)](#read_s_byte_position_11) | يقرأ بيانات بايت موقعة من التدفق. |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_12) | يقرأ مصفوفة من قيم البايت الموقعة من التدفق. |
| [read_s_int(position)](#read_s_int_position_13) | يقرأ قيمة عدد صحيح موقعة من التدفق. |
| [read_s_int_array(position, count)](#read_s_int_array_position_count_14) | يقرأ مصفوفة من قيم الأعداد الصحيحة الموقعة من التدفق. |
| [read_s_rational(position)](#read_s_rational_position_15) | يقرأ قيمة عدد كسرية موقعة واحدة من التدفق. |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_16) | يقرأ مصفوفة من القيم الكسرية الموقعة من التدفق. |
| [read_s_short(position)](#read_s_short_position_17) | قراءة قيمة signed short من الدفق. |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_18) | يقوم بقراءة مصفوفة من قيم signed short من الدفق. |
| [read_u_int(position)](#read_u_int_position_19) | قراءة قيمة unsigned integer من الدفق. |
| [read_u_int_array(position, count)](#read_u_int_array_position_count_20) | يقوم بقراءة مصفوفة من قيم unsigned integer من الدفق. |
| [read_u_long(position)](#read_u_long_position_21) | يقرأ قيمة طويلة غير موقعة من التدفق. |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_22) | يقرأ مصفوفة من قيم ulong من التدفق. |
| [read_u_short(position)](#read_u_short_position_23) | قراءة قيمة unsigned short من الدفق. |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_24) | يقوم بقراءة مصفوفة من قيم unsigned integer من الدفق. |
| [to_stream_container(start_position)](#to_stream_container_start_position_25) | يحول البيانات الأساسية إلى حاوية الدفق. |


### Constructor: BigTiffReader(data) {#BigTiffReader_data_1}


```
 BigTiffReader(data) 
```

يُنشئ مثلاً جديدًا من الفئة [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| البيانات | System.Byte | بيانات مصفوفة البايت. |

### Constructor: BigTiffReader(data, start_index) {#BigTiffReader_data_start_index_2}


```
 BigTiffReader(data, start_index) 
```

يُنشئ مثلاً جديدًا من الفئة [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| البيانات | System.Byte | بيانات مصفوفة البايت. |
| start_index | int | فهرس البداية في _data_. |

### Constructor: BigTiffReader(data, start_index, data_length) {#BigTiffReader_data_start_index_data_length_3}


```
 BigTiffReader(data, start_index, data_length) 
```

يُنشئ مثلاً جديدًا من الفئة [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| البيانات | System.Byte | بيانات مصفوفة البايت. |
| start_index | int | فهرس البداية في _data_. |
| data_length | int | طول البيانات. |

### Constructor: BigTiffReader(stream_container) {#BigTiffReader_stream_container_4}


```
 BigTiffReader(stream_container) 
```

يُنشئ مثلاً جديدًا من الفئة [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | حاوية الدفق. |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


```
 read_bytes(array, array_index, position, count) 
```

يقرأ مصفوفة من قيم البايت من التدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| array | System.Byte | المصفوفة للتعبئة. |
| array_index | int | فهرس المصفوفة للبدء بوضع القيم فيه. |
| position | int | موضع الدفق للقراءة منه. |
| count | int | عدد العناصر للقراءة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | مصفوفة قيم البايت. |


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


```
 read_bytes(position, count) 
```

يقرأ مصفوفة من قيم البايت غير الموقّعة من التدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| position | int | الموضع للقراءة منه. |
| count | int | عدد العناصر. |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Byte | مصفوفة قيم unsigned byte. |


### Method: read_double(position) {#read_double_position_3}


```
 read_double(position) 
```

يقرأ قيمة مزدوجة واحدة من التدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| position | int | الموضع للقراءة منه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| float | القيمة المزدوجة المفردة. |


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


```
 read_double_array(position, count) 
```

يقرأ مصفوفة من القيم المزدوجة من التدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| position | int | الموضع للقراءة منه. |
| count | int | عدد العناصر. |

**Returns**

| نوع | الوصف |
| :- | :- |
| float[] | مصفوفة القيم المزدوجة. |


### Method: read_float(position) {#read_float_position_5}


```
 read_float(position) 
```

يقرأ قيمة عائمة واحدة من التدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| position | int | الموضع للقراءة منه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| float | القيمة الفاصلة المفردة. |


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


```
 read_float_array(position, count) 
```

يقرأ مصفوفة من القيم العائمة من التدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| position | int | الموضع للقراءة منه. |
| count | int | عدد العناصر. |

**Returns**

| نوع | الوصف |
| :- | :- |
| float[] | مصفوفة القيم الفاصلة. |


### Method: read_long(position) {#read_long_position_7}


```
 read_long(position) 
```

يقرأ قيمة طويلة غير موقعة من التدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| position | int | الموضع للقراءة منه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | قيمة unsigned short. |


### Method: read_long_array(position, count) {#read_long_array_position_count_8}


```
 read_long_array(position, count) 
```

يقرأ مصفوفة من قيم ulong من التدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| position | int | الموضع للقراءة منه. |
| count | int | عدد العناصر. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | مصفوفة ulong. |


### Method: read_rational(position) {#read_rational_position_9}


```
 read_rational(position) 
```

يقرأ قيمة عدد كسرية واحدة من التدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| position | int | الموضع للقراءة منه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | العدد النسبي. |


### Method: read_rational_array(position, count) {#read_rational_array_position_count_10}


```
 read_rational_array(position, count) 
```

يقرأ مصفوفة من القيم الكسرية من التدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| position | int | الموضع للقراءة منه. |
| count | int | عدد العناصر. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | مصفوفة القيم النسبية. |


### Method: read_s_byte(position) {#read_s_byte_position_11}


```
 read_s_byte(position) 
```

يقرأ بيانات بايت موقعة من التدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| position | int | الموضع للقراءة منه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.SByte | قيمة البايت الموقعة. |


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_12}


```
 read_s_byte_array(position, count) 
```

يقرأ مصفوفة من قيم البايت الموقعة من التدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| position | int | الموضع للقراءة منه. |
| count | int | عدد العناصر. |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.SByte | مصفوفة قيم البايت الموقعة. |


### Method: read_s_int(position) {#read_s_int_position_13}


```
 read_s_int(position) 
```

يقرأ قيمة عدد صحيح موقعة من التدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| position | int | الموضع للقراءة منه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | قيمة عدد صحيح موقّع. |


### Method: read_s_int_array(position, count) {#read_s_int_array_position_count_14}


```
 read_s_int_array(position, count) 
```

يقرأ مصفوفة من قيم الأعداد الصحيحة الموقعة من التدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| position | int | الموضع للقراءة منه. |
| count | int | عدد العناصر. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | مصفوفة قيم الأعداد الصحيحة الموقعة. |


### Method: read_s_rational(position) {#read_s_rational_position_15}


```
 read_s_rational(position) 
```

يقرأ قيمة عدد كسرية موقعة واحدة من التدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| position | int | الموضع للقراءة منه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | العدد النسبي الموقّع. |


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_16}


```
 read_s_rational_array(position, count) 
```

يقرأ مصفوفة من القيم الكسرية الموقعة من التدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| position | int | الموضع للقراءة منه. |
| count | int | عدد العناصر. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffSRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | مصفوفة القيم النسبية الموقعة. |


### Method: read_s_short(position) {#read_s_short_position_17}


```
 read_s_short(position) 
```

قراءة قيمة signed short من الدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| position | int | الموضع للقراءة منه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | قيمة short موقّعة. |


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_18}


```
 read_s_short_array(position, count) 
```

يقوم بقراءة مصفوفة من قيم signed short من الدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| position | int | الموضع للقراءة منه. |
| count | int | عدد العناصر. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | مصفوفة قيم short الموقعة. |


### Method: read_u_int(position) {#read_u_int_position_19}


```
 read_u_int(position) 
```

قراءة قيمة unsigned integer من الدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| position | int | الموضع للقراءة منه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | قيمة عدد صحيح غير موقّع. |


### Method: read_u_int_array(position, count) {#read_u_int_array_position_count_20}


```
 read_u_int_array(position, count) 
```

يقوم بقراءة مصفوفة من قيم unsigned integer من الدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| position | int | الموضع للقراءة منه. |
| count | int | عدد العناصر. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | مصفوفة قيم الأعداد الصحيحة غير الموقعة. |


### Method: read_u_long(position) {#read_u_long_position_21}


```
 read_u_long(position) 
```

يقرأ قيمة طويلة غير موقعة من التدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| position | int | الموضع للقراءة منه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | قيمة unsigned short. |


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_22}


```
 read_u_long_array(position, count) 
```

يقرأ مصفوفة من قيم ulong من التدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| position | int | الموضع للقراءة منه. |
| count | int | عدد العناصر. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | مصفوفة ulong. |


### Method: read_u_short(position) {#read_u_short_position_23}


```
 read_u_short(position) 
```

قراءة قيمة unsigned short من الدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| position | int | الموضع للقراءة منه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | قيمة unsigned short. |


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_24}


```
 read_u_short_array(position, count) 
```

يقوم بقراءة مصفوفة من قيم unsigned integer من الدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| position | int | الموضع للقراءة منه. |
| count | int | عدد العناصر. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int[] | مصفوفة قيم الأعداد الصحيحة غير الموقعة. |


### Method: to_stream_container(start_position) {#to_stream_container_start_position_25}


```
 to_stream_container(start_position) 
```

يحول البيانات الأساسية إلى حاوية الدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| start_position | int | موضع البداية للبدء في التحويل من. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | الـ [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) مع البيانات المحوّلة. |


