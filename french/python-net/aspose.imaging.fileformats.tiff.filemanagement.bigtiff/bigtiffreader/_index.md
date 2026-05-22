---
title: "Classe BigTiffReader"
type: docs
weight: 10
url: /fr/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/
---

**Summary:** The little endian BigTiff reader.

**Module:** [aspose.imaging.fileformats.tiff.filemanagement.bigtiff](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/)

**Full Name:** aspose.imaging.fileformats.tiff.filemanagement.bigtiff.BigTiffReader

**Inheritance:** TiffStreamReader

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BigTiffReader(data)](#BigTiffReader_data_1) | Initialise une nouvelle instance de la classe [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/). |
| [BigTiffReader(data, start_index)](#BigTiffReader_data_start_index_2) | Initialise une nouvelle instance de la classe [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/). |
| [BigTiffReader(data, start_index, data_length)](#BigTiffReader_data_start_index_data_length_3) | Initialise une nouvelle instance de la classe [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/). |
| [BigTiffReader(stream_container)](#BigTiffReader_stream_container_4) | Initialise une nouvelle instance de la classe [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| length | int | r | Obtient la longueur du lecteur. |
| throw_exceptions | bool | r/w | Obtient ou définit une valeur indiquant si des exceptions sont levées lors d'un traitement de données incorrect (lecture ou écriture du flux). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | Lit un tableau de valeurs d'octet du flux. |
| [read_bytes(position, count)](#read_bytes_position_count_2) | Lit un tableau de valeurs d'octet non signées du flux. |
| [read_double(position)](#read_double_position_3) | Lit une seule valeur double du flux. |
| [read_double_array(position, count)](#read_double_array_position_count_4) | Lit un tableau de valeurs double du flux. |
| [read_float(position)](#read_float_position_5) | Lit une seule valeur flottante du flux. |
| [read_float_array(position, count)](#read_float_array_position_count_6) | Lit un tableau de valeurs flottantes du flux. |
| [read_long(position)](#read_long_position_7) | Lit une valeur unsigned long du flux. |
| [read_long_array(position, count)](#read_long_array_position_count_8) | Lit un tableau de valeurs ulong du flux. |
| [read_rational(position)](#read_rational_position_9) | Lit une seule valeur de nombre rationnel du flux. |
| [read_rational_array(position, count)](#read_rational_array_position_count_10) | Lit un tableau de valeurs rationnelles du flux. |
| [read_s_byte(position)](#read_s_byte_position_11) | Lit des données d'octet signé du flux. |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_12) | Lit un tableau de valeurs d'octet signées du flux. |
| [read_s_int(position)](#read_s_int_position_13) | Lit une valeur d'entier signé du flux. |
| [read_s_int_array(position, count)](#read_s_int_array_position_count_14) | Lit un tableau de valeurs d'entiers signés du flux. |
| [read_s_rational(position)](#read_s_rational_position_15) | Lit une seule valeur de nombre rationnel signé du flux. |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_16) | Lit un tableau de valeurs rationnelles signées du flux. |
| [read_s_short(position)](#read_s_short_position_17) | Lire la valeur short signée depuis le flux. |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_18) | Lit un tableau de valeurs short signées depuis le flux. |
| [read_u_int(position)](#read_u_int_position_19) | Lire la valeur entier non signé depuis le flux. |
| [read_u_int_array(position, count)](#read_u_int_array_position_count_20) | Lit un tableau de valeurs entiers non signés depuis le flux. |
| [read_u_long(position)](#read_u_long_position_21) | Lit une valeur unsigned long du flux. |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_22) | Lit un tableau de valeurs ulong du flux. |
| [read_u_short(position)](#read_u_short_position_23) | Lire la valeur short non signé depuis le flux. |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_24) | Lit un tableau de valeurs entiers non signés depuis le flux. |
| [to_stream_container(start_position)](#to_stream_container_start_position_25) | Convertit les données sous-jacentes en conteneur de flux. |


### Constructor: BigTiffReader(data) {#BigTiffReader_data_1}


```
 BigTiffReader(data) 
```

Initialise une nouvelle instance de la classe [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| données | System.Byte | Les données du tableau d'octets. |

### Constructor: BigTiffReader(data, start_index) {#BigTiffReader_data_start_index_2}


```
 BigTiffReader(data, start_index) 
```

Initialise une nouvelle instance de la classe [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| données | System.Byte | Les données du tableau d'octets. |
| start_index | int | L'index de départ dans _data_. |

### Constructor: BigTiffReader(data, start_index, data_length) {#BigTiffReader_data_start_index_data_length_3}


```
 BigTiffReader(data, start_index, data_length) 
```

Initialise une nouvelle instance de la classe [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| données | System.Byte | Les données du tableau d'octets. |
| start_index | int | L'index de départ dans _data_. |
| data_length | int | Longueur des données. |

### Constructor: BigTiffReader(stream_container) {#BigTiffReader_stream_container_4}


```
 BigTiffReader(stream_container) 
```

Initialise une nouvelle instance de la classe [BigTiffReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Le conteneur de flux. |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


```
 read_bytes(array, array_index, position, count) 
```

Lit un tableau de valeurs d'octet du flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| array | System.Byte | Le tableau à remplir. |
| array_index | int | L'index du tableau où commencer à placer les valeurs. |
| position | int | La position du flux à lire. |
| count | int | Le nombre d'éléments à lire. |

**Returns**

| Type | Description |
| :- | :- |
| int | Le tableau de valeurs d'octets. |


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


```
 read_bytes(position, count) 
```

Lit un tableau de valeurs d'octet non signées du flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position à lire. |
| count | int | Le nombre d'éléments. |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | Le tableau de valeurs d'octets non signés. |


### Method: read_double(position) {#read_double_position_3}


```
 read_double(position) 
```

Lit une seule valeur double du flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position à lire. |

**Returns**

| Type | Description |
| :- | :- |
| float | La valeur double unique. |


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


```
 read_double_array(position, count) 
```

Lit un tableau de valeurs double du flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position à lire. |
| count | int | Le nombre d'éléments. |

**Returns**

| Type | Description |
| :- | :- |
| float[] | Le tableau de valeurs double. |


### Method: read_float(position) {#read_float_position_5}


```
 read_float(position) 
```

Lit une seule valeur flottante du flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position à lire. |

**Returns**

| Type | Description |
| :- | :- |
| float | La valeur float unique. |


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


```
 read_float_array(position, count) 
```

Lit un tableau de valeurs flottantes du flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position à lire. |
| count | int | Le nombre d'éléments. |

**Returns**

| Type | Description |
| :- | :- |
| float[] | Le tableau de valeurs float. |


### Method: read_long(position) {#read_long_position_7}


```
 read_long(position) 
```

Lit une valeur unsigned long du flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position à lire. |

**Returns**

| Type | Description |
| :- | :- |
| int | Une valeur short non signée. |


### Method: read_long_array(position, count) {#read_long_array_position_count_8}


```
 read_long_array(position, count) 
```

Lit un tableau de valeurs ulong du flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position à lire. |
| count | int | Le nombre d'éléments. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Le tableau ulong. |


### Method: read_rational(position) {#read_rational_position_9}


```
 read_rational(position) 
```

Lit une seule valeur de nombre rationnel du flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position à lire. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Le nombre rationnel. |


### Method: read_rational_array(position, count) {#read_rational_array_position_count_10}


```
 read_rational_array(position, count) 
```

Lit un tableau de valeurs rationnelles du flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position à lire. |
| count | int | Le nombre d'éléments. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | Le tableau de valeurs rationnelles. |


### Method: read_s_byte(position) {#read_s_byte_position_11}


```
 read_s_byte(position) 
```

Lit des données d'octet signé du flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position à lire. |

**Returns**

| Type | Description |
| :- | :- |
| System.SByte | La valeur du byte signé. |


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_12}


```
 read_s_byte_array(position, count) 
```

Lit un tableau de valeurs d'octet signées du flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position à lire. |
| count | int | Le nombre d'éléments. |

**Returns**

| Type | Description |
| :- | :- |
| System.SByte | Le tableau de valeurs de byte signé. |


### Method: read_s_int(position) {#read_s_int_position_13}


```
 read_s_int(position) 
```

Lit une valeur d'entier signé du flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position à lire. |

**Returns**

| Type | Description |
| :- | :- |
| int | Une valeur d'integer signé. |


### Method: read_s_int_array(position, count) {#read_s_int_array_position_count_14}


```
 read_s_int_array(position, count) 
```

Lit un tableau de valeurs d'entiers signés du flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position à lire. |
| count | int | Le nombre d'éléments. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Le tableau de valeurs d'integer signé. |


### Method: read_s_rational(position) {#read_s_rational_position_15}


```
 read_s_rational(position) 
```

Lit une seule valeur de nombre rationnel signé du flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position à lire. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Le nombre rationnel signé. |


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_16}


```
 read_s_rational_array(position, count) 
```

Lit un tableau de valeurs rationnelles signées du flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position à lire. |
| count | int | Le nombre d'éléments. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Le tableau de valeurs rationnelles signées. |


### Method: read_s_short(position) {#read_s_short_position_17}


```
 read_s_short(position) 
```

Lire la valeur short signée depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position à lire. |

**Returns**

| Type | Description |
| :- | :- |
| int | Une valeur short signée. |


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_18}


```
 read_s_short_array(position, count) 
```

Lit un tableau de valeurs short signées depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position à lire. |
| count | int | Le nombre d'éléments. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Le tableau de valeurs short signées. |


### Method: read_u_int(position) {#read_u_int_position_19}


```
 read_u_int(position) 
```

Lire la valeur entier non signé depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position à lire. |

**Returns**

| Type | Description |
| :- | :- |
| int | Une valeur d'unsigned integer. |


### Method: read_u_int_array(position, count) {#read_u_int_array_position_count_20}


```
 read_u_int_array(position, count) 
```

Lit un tableau de valeurs entiers non signés depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position à lire. |
| count | int | Le nombre d'éléments. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Le tableau de valeurs d'unsigned integer. |


### Method: read_u_long(position) {#read_u_long_position_21}


```
 read_u_long(position) 
```

Lit une valeur unsigned long du flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position à lire. |

**Returns**

| Type | Description |
| :- | :- |
| int | Une valeur short non signée. |


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_22}


```
 read_u_long_array(position, count) 
```

Lit un tableau de valeurs ulong du flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position à lire. |
| count | int | Le nombre d'éléments. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Le tableau ulong. |


### Method: read_u_short(position) {#read_u_short_position_23}


```
 read_u_short(position) 
```

Lire la valeur short non signé depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position à lire. |

**Returns**

| Type | Description |
| :- | :- |
| int | Une valeur short non signée. |


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_24}


```
 read_u_short_array(position, count) 
```

Lit un tableau de valeurs entiers non signés depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position à lire. |
| count | int | Le nombre d'éléments. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Le tableau de valeurs d'unsigned integer. |


### Method: to_stream_container(start_position) {#to_stream_container_start_position_25}


```
 to_stream_container(start_position) 
```

Convertit les données sous-jacentes en conteneur de flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| start_position | int | La position de départ à partir de laquelle commencer la conversion. |

**Returns**

| Type | Description |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Le [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) avec les données converties. |


