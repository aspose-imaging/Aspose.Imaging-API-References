---
title: "TiffFloatType Clase"
type: docs
weight: 50
url: /es/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/
---

**Summary:** The tiff float type.

**Module:** [aspose.imaging.fileformats.tiff.tifftagtypes](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/)

**Full Name:** aspose.imaging.fileformats.tiff.tifftagtypes.TiffFloatType

**Inheritance:** TiffCommonArrayType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [TiffFloatType(tag_id)](#TiffFloatType_tag_id_1) | Inicializa una nueva instancia de la clase [TiffFloatType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/). |
| [TiffFloatType(tag_id)](#TiffFloatType_tag_id_2) | Inicializa una nueva instancia de la clase [TiffFloatType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| count | int | r | Obtiene el recuento de elementos. |
| data_size | int | r | Obtiene el tamaño del valor de la etiqueta. |
| element_size | System.Byte | r | Obtiene el tamaño del elemento en bytes. |
| id | int | r | Obtiene el id de la etiqueta como número. |
| is_valid | bool | r | Obtiene un valor que indica si los datos de la etiqueta son válidos. La etiqueta válida contiene datos que pueden preservarse. La etiqueta inválida no puede almacenarse. |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | r | Obtiene el id de la etiqueta. |
| tag_type | [TiffDataTypes](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffdatatypes/) | r | Obtiene el tipo de etiqueta. |
| valor | System.Object | r/w | Obtiene o establece el valor que contiene este tipo de datos. |
| values | float[] | r/w | Obtiene o establece los valores. |
| values_container | System.Array | r | Obtiene el contenedor de valores. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | Compara la instancia actual con otro objeto del mismo tipo y devuelve un entero que indica si la instancia actual precede, sigue o se encuentra en la misma posición en el orden de clasificación que el otro objeto. |
| [create_with_tag(tag_id)](#create_with_tag_tag_id_2) | Inicializa una nueva instancia de la clase [TiffFloatType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/). |
| [create_with_tag_id(tag_id)](#create_with_tag_id_tag_id_3) | Inicializa una nueva instancia de la clase [TiffFloatType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/). |
| [deep_clone()](#deep_clone__4) | Realiza una clonación profunda de esta instancia. |
| [get_additional_data_size(size_of_tag_value)](#get_additional_data_size_size_of_tag_value_5) | Obtiene el tamaño adicional del valor de la etiqueta en bytes (en caso de que la etiqueta no pueda contener todo el valor de la etiqueta). |
| [get_aligned_data_size(size_of_tag_value)](#get_aligned_data_size_size_of_tag_value_6) | Obtiene el tamaño de los datos alineado a un límite de 4 bytes (int) o 8 bytes (long). |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_7) | Lee los datos de la etiqueta. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_8) | Escribe los datos adicionales de la etiqueta. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_9) | Escribe el valor de la etiqueta o el desplazamiento adicional. |


### Constructor: TiffFloatType(tag_id) {#TiffFloatType_tag_id_1}


```
 TiffFloatType(tag_id) 
```

Inicializa una nueva instancia de la clase [TiffFloatType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | El id de la etiqueta. |

### Constructor: TiffFloatType(tag_id) {#TiffFloatType_tag_id_2}


```
 TiffFloatType(tag_id) 
```

Inicializa una nueva instancia de la clase [TiffFloatType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tag_id | int | El id de la etiqueta. |

### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

Compara la instancia actual con otro objeto del mismo tipo y devuelve un entero que indica si la instancia actual precede, sigue o se encuentra en la misma posición en el orden de clasificación que el otro objeto.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| obj | System.Object | Un objeto para comparar con esta instancia. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Un entero con signo de 32 bits que indica el orden relativo de los objetos que se comparan. El valor de retorno tiene estos significados:<br/>            Valor<br/>            Significado<br/>            Menor que cero<br/>            Esta instancia es menor que _obj_.<br/>            Cero<br/>            Esta instancia es igual a _obj_.<br/>            Mayor que cero<br/>            Esta instancia es mayor que _obj_. |


### Method: create_with_tag(tag_id)  [static] {#create_with_tag_tag_id_2}


```
 create_with_tag(tag_id) 
```

Inicializa una nueva instancia de la clase [TiffFloatType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | El id de la etiqueta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffFloatType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/) |  |


### Method: create_with_tag_id(tag_id)  [static] {#create_with_tag_id_tag_id_3}


```
 create_with_tag_id(tag_id) 
```

Inicializa una nueva instancia de la clase [TiffFloatType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tag_id | int | El id de la etiqueta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffFloatType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/) |  |


### Method: deep_clone() {#deep_clone__4}


```
 deep_clone() 
```

Realiza una clonación profunda de esta instancia.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Una clonación profunda de la instancia actual. |


### Method: get_additional_data_size(size_of_tag_value) {#get_additional_data_size_size_of_tag_value_5}


```
 get_additional_data_size(size_of_tag_value) 
```

Obtiene el tamaño adicional del valor de la etiqueta en bytes (en caso de que la etiqueta no pueda contener todo el valor de la etiqueta).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size_of_tag_value | System.Byte | Tamaño del valor de la etiqueta: 4 u 8 para BigTiff. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El tamaño adicional de los datos en bytes. |


### Method: get_aligned_data_size(size_of_tag_value) {#get_aligned_data_size_size_of_tag_value_6}


```
 get_aligned_data_size(size_of_tag_value) 
```

Obtiene el tamaño de los datos alineado a un límite de 4 bytes (int) o 8 bytes (long).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| size_of_tag_value | System.Byte | Tamaño del valor de la etiqueta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El tamaño de los datos alineado en bytes. |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_7}


```
 read_tag(data_stream, position) 
```

Lee los datos de la etiqueta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | El flujo de datos. |
| position | int | La posición de la etiqueta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | La etiqueta leída. |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_8}


```
 write_additional_data(data_stream) 
```

Escribe los datos adicionales de la etiqueta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | El flujo de datos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Los bytes reales escritos. |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_9}


```
 write_tag(data_stream, additional_data_offset) 
```

Escribe el valor de la etiqueta o el desplazamiento adicional.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | El flujo de datos. |
| additional_data_offset | int | El desplazamiento adicional de los datos. |

