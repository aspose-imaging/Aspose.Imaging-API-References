---
title: "Clase DataStreamSupporter"
type: docs
weight: 1360
url: /es/python-net/aspose.imaging/datastreamsupporter/
---

**Summary:** The data stream container.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.DataStreamSupporter

**Inheritance:** DisposableObject

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Obtiene el flujo de datos del objeto. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está disposed. |
| is_cached | bool | r | Obtiene un valor que indica si los datos del objeto están en caché actualmente y no se requiere lectura de datos. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| cache_data() | Almacena en caché los datos y garantiza que no se realizará una carga adicional de datos desde el [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/) subyacente. |
| save() | Guarda los datos del objeto en el [DataStreamSupporter](/imaging/python-net/aspose.imaging/datastreamsupporter/) actual. |
| [save(file_path)](#save_file_path_1) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| [save(file_path, over_write)](#save_file_path_over_write_2) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| [save(stream)](#save_stream_3) | Guarda los datos del objeto en el flujo especificado. |
| [save_to_stream(stream)](#save_to_stream_stream_4) | Guarda los datos del objeto en el flujo especificado. |


### Method: save(file_path) {#save_file_path_1}


```
 save(file_path) 
```

Guarda los datos del objeto en la ubicación de archivo especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar los datos del objeto. |

### Method: save(file_path, over_write) {#save_file_path_over_write_2}


```
 save(file_path, over_write) 
```

Guarda los datos del objeto en la ubicación de archivo especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar los datos del objeto. |
| sobrescribir | bool | si se establece en <c>true</c> sobrescribe el contenido del archivo, de lo contrario se añadirá. |

### Method: save(stream) {#save_stream_3}


```
 save(stream) 
```

Guarda los datos del objeto en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos del objeto. |

### Method: save_to_stream(stream) {#save_to_stream_stream_4}


```
 save_to_stream(stream) 
```

Guarda los datos del objeto en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos del objeto. |

