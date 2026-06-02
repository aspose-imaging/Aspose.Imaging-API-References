---
title: "Clase TiffBigEndianStreamReader"
type: docs
weight: 50
url: /es/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/
---

**Summary:** The tiff stream for handling big endian tiff file format.

**Module:** [aspose.imaging.fileformats.tiff.filemanagement](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/)

**Full Name:** aspose.imaging.fileformats.tiff.filemanagement.TiffBigEndianStreamReader

**Inheritance:** TiffStreamReader

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [TiffBigEndianStreamReader(data)](#TiffBigEndianStreamReader_data_1) | Inicializa una nueva instancia de la clase [TiffBigEndianStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/). |
| [TiffBigEndianStreamReader(data, start_index)](#TiffBigEndianStreamReader_data_start_index_2) | Inicializa una nueva instancia de la clase [TiffBigEndianStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/). |
| [TiffBigEndianStreamReader(data, start_index, data_length)](#TiffBigEndianStreamReader_data_start_index_data_length_3) | Inicializa una nueva instancia de la clase [TiffBigEndianStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/). |
| [TiffBigEndianStreamReader(stream_container)](#TiffBigEndianStreamReader_stream_container_4) | Inicializa una nueva instancia de la clase [TiffBigEndianStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| length | int | r | Obtiene la longitud del lector. |
| throw_exceptions | bool | r/w | Obtiene o establece un valor que indica si se lanzan excepciones al procesar datos incorrectos (lectura o escritura en el flujo). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | Lee una matriz de valores byte del flujo. |
| [read_bytes(position, count)](#read_bytes_position_count_2) | Lee una matriz de valores byte sin signo del flujo. |
| [read_double(position)](#read_double_position_3) | Lee un solo valor double del flujo. |
| [read_double_array(position, count)](#read_double_array_position_count_4) | Lee una matriz de valores double del flujo. |
| [read_float(position)](#read_float_position_5) | Lee un solo valor float del flujo. |
| [read_float_array(position, count)](#read_float_array_position_count_6) | Lee una matriz de valores float del flujo. |
| [read_long(position)](#read_long_position_7) | Lee un valor unsigned long del flujo. |
| [read_long_array(position, count)](#read_long_array_position_count_8) | Lee una matriz de valores ulong del flujo. |
| [read_rational(position)](#read_rational_position_9) | Lee un solo valor de número racional del flujo. |
| [read_rational_array(position, count)](#read_rational_array_position_count_10) | Lee una matriz de valores racionales del flujo. |
| [read_s_byte(position)](#read_s_byte_position_11) | Lee datos de byte con signo del flujo. |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_12) | Lee una matriz de valores byte con signo del flujo. |
| [read_s_int(position)](#read_s_int_position_13) | Lee un valor entero con signo del flujo. |
| [read_s_int_array(position, count)](#read_s_int_array_position_count_14) | Lee una matriz de valores enteros con signo del flujo. |
| [read_s_rational(position)](#read_s_rational_position_15) | Lee un solo valor de número racional con signo del flujo. |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_16) | Lee una matriz de valores racionales con signo del flujo. |
| [read_s_short(position)](#read_s_short_position_17) | Leer el valor short con signo del flujo. |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_18) | Lee una matriz de valores short con signo del flujo. |
| [read_u_int(position)](#read_u_int_position_19) | Leer el valor entero sin signo del flujo. |
| [read_u_int_array(position, count)](#read_u_int_array_position_count_20) | Lee una matriz de valores enteros sin signo del flujo. |
| [read_u_long(position)](#read_u_long_position_21) | Lee un valor unsigned long del flujo. |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_22) | Lee una matriz de valores ulong del flujo. |
| [read_u_short(position)](#read_u_short_position_23) | Leer el valor short sin signo del flujo. |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_24) | Lee una matriz de valores enteros sin signo del flujo. |
| [to_stream_container(start_position)](#to_stream_container_start_position_25) | Convierte los datos subyacentes al contenedor del flujo. |


### Constructor: TiffBigEndianStreamReader(data) {#TiffBigEndianStreamReader_data_1}


```
 TiffBigEndianStreamReader(data) 
```

Inicializa una nueva instancia de la clase [TiffBigEndianStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | System.Byte | Los datos de la matriz de bytes. |

### Constructor: TiffBigEndianStreamReader(data, start_index) {#TiffBigEndianStreamReader_data_start_index_2}


```
 TiffBigEndianStreamReader(data, start_index) 
```

Inicializa una nueva instancia de la clase [TiffBigEndianStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | System.Byte | Los datos de la matriz de bytes. |
| start_index | int | El índice de inicio en _data_. |

### Constructor: TiffBigEndianStreamReader(data, start_index, data_length) {#TiffBigEndianStreamReader_data_start_index_data_length_3}


```
 TiffBigEndianStreamReader(data, start_index, data_length) 
```

Inicializa una nueva instancia de la clase [TiffBigEndianStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | System.Byte | Los datos de la matriz de bytes. |
| start_index | int | El índice de inicio en _data_. |
| data_length | int | Longitud de los datos. |

### Constructor: TiffBigEndianStreamReader(stream_container) {#TiffBigEndianStreamReader_stream_container_4}


```
 TiffBigEndianStreamReader(stream_container) 
```

Inicializa una nueva instancia de la clase [TiffBigEndianStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | El contenedor del flujo. |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


```
 read_bytes(array, array_index, position, count) 
```

Lee una matriz de valores byte del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matriz | System.Byte | La matriz a rellenar. |
| array_index | int | El índice de la matriz donde comenzar a colocar valores. |
| position | int | La posición del flujo desde la cual leer. |
| count | int | El recuento de elementos a leer. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | La matriz de valores byte. |


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


```
 read_bytes(position, count) 
```

Lee una matriz de valores byte sin signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición desde la cual leer. |
| count | int | El recuento de elementos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Byte | La matriz de valores byte sin signo. |


### Method: read_double(position) {#read_double_position_3}


```
 read_double(position) 
```

Lee un solo valor double del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición desde la cual leer. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| float | El valor doble único. |


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


```
 read_double_array(position, count) 
```

Lee una matriz de valores double del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición desde la cual leer. |
| count | int | El recuento de elementos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| float[] | La matriz de valores dobles. |


### Method: read_float(position) {#read_float_position_5}


```
 read_float(position) 
```

Lee un solo valor float del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición desde la cual leer. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| float | El valor flotante único. |


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


```
 read_float_array(position, count) 
```

Lee una matriz de valores float del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición desde la cual leer. |
| count | int | El recuento de elementos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| float[] | La matriz de valores flotantes. |


### Method: read_long(position) {#read_long_position_7}


```
 read_long(position) 
```

Lee un valor unsigned long del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición desde la cual leer. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Un valor short sin signo. |


### Method: read_long_array(position, count) {#read_long_array_position_count_8}


```
 read_long_array(position, count) 
```

Lee una matriz de valores ulong del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición desde la cual leer. |
| count | int | El recuento de elementos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | La matriz ulong. |


### Method: read_rational(position) {#read_rational_position_9}


```
 read_rational(position) 
```

Lee un solo valor de número racional del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición desde la cual leer. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | El número racional. |


### Method: read_rational_array(position, count) {#read_rational_array_position_count_10}


```
 read_rational_array(position, count) 
```

Lee una matriz de valores racionales del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición desde la cual leer. |
| count | int | El recuento de elementos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | La matriz de valores racionales. |


### Method: read_s_byte(position) {#read_s_byte_position_11}


```
 read_s_byte(position) 
```

Lee datos de byte con signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición desde la cual leer. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.SByte | El valor de byte con signo. |


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_12}


```
 read_s_byte_array(position, count) 
```

Lee una matriz de valores byte con signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición desde la cual leer. |
| count | int | El recuento de elementos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.SByte | La matriz de valores de byte con signo. |


### Method: read_s_int(position) {#read_s_int_position_13}


```
 read_s_int(position) 
```

Lee un valor entero con signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición desde la cual leer. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Un valor entero con signo. |


### Method: read_s_int_array(position, count) {#read_s_int_array_position_count_14}


```
 read_s_int_array(position, count) 
```

Lee una matriz de valores enteros con signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición desde la cual leer. |
| count | int | El recuento de elementos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | La matriz de valores enteros con signo. |


### Method: read_s_rational(position) {#read_s_rational_position_15}


```
 read_s_rational(position) 
```

Lee un solo valor de número racional con signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición desde la cual leer. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | El número racional con signo. |


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_16}


```
 read_s_rational_array(position, count) 
```

Lee una matriz de valores racionales con signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición desde la cual leer. |
| count | int | El recuento de elementos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffSRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | La matriz de valores racionales con signo. |


### Method: read_s_short(position) {#read_s_short_position_17}


```
 read_s_short(position) 
```

Leer el valor short con signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición desde la cual leer. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Un valor short con signo. |


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_18}


```
 read_s_short_array(position, count) 
```

Lee una matriz de valores short con signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición desde la cual leer. |
| count | int | El recuento de elementos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | La matriz de valores short con signo. |


### Method: read_u_int(position) {#read_u_int_position_19}


```
 read_u_int(position) 
```

Leer el valor entero sin signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición desde la cual leer. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Un valor entero sin signo. |


### Method: read_u_int_array(position, count) {#read_u_int_array_position_count_20}


```
 read_u_int_array(position, count) 
```

Lee una matriz de valores enteros sin signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición desde la cual leer. |
| count | int | El recuento de elementos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | La matriz de valores enteros sin signo. |


### Method: read_u_long(position) {#read_u_long_position_21}


```
 read_u_long(position) 
```

Lee un valor unsigned long del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición desde la cual leer. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Un valor short sin signo. |


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_22}


```
 read_u_long_array(position, count) 
```

Lee una matriz de valores ulong del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición desde la cual leer. |
| count | int | El recuento de elementos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | La matriz ulong. |


### Method: read_u_short(position) {#read_u_short_position_23}


```
 read_u_short(position) 
```

Leer el valor short sin signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición desde la cual leer. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Un valor short sin signo. |


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_24}


```
 read_u_short_array(position, count) 
```

Lee una matriz de valores enteros sin signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición desde la cual leer. |
| count | int | El recuento de elementos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | La matriz de valores enteros sin signo. |


### Method: to_stream_container(start_position) {#to_stream_container_start_position_25}


```
 to_stream_container(start_position) 
```

Convierte los datos subyacentes al contenedor del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| start_position | int | La posición inicial desde la cual iniciar la conversión. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | El [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) con datos convertidos. |


