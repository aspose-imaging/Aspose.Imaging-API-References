---
title: "Clase ImageLoadersRegistry"
type: docs
weight: 5720
url: /es/python-net/aspose.imaging/imageloadersregistry/
---

**Summary:** Represents the image loaders registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageLoadersRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageLoaderDescriptor[]](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | r | Obtiene los descriptores registrados. |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Obtiene los formatos de carga de imagen registrados. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_first_supported_loader(stream, load_options)](#create_first_supported_loader_stream_load_options_1) | Crea el primer cargador encontrado adecuado para el _stream_ especificado y opcionalmente para los _loadOptions_. |
| [get_first_supported_descriptor(stream, load_options)](#get_first_supported_descriptor_stream_load_options_2) | Obtiene el primer descriptor compatible encontrado adecuado para el _stream_ especificado y opcionalmente para los _loadOptions_. |
| [get_first_supported_descriptor_by_file_format(file_format)](#get_first_supported_descriptor_by_file_format_file_format_3) | Obtiene el primer formato de archivo compatible por su nombre de tipo. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_4) | Obtiene el primer descriptor compatible por su nombre de tipo. |
| [register(image_loader_descriptor)](#register_image_loader_descriptor_5) | Registra el descriptor de cargador de imagen especificado. |
| [register_loader(loader_descriptor)](#register_loader_loader_descriptor_6) | Registra el cargador. |
| [unregister_loader(loader_descriptor)](#unregister_loader_loader_descriptor_7) | Desregistra el cargador. |


### Method: create_first_supported_loader(stream, load_options)  [static] {#create_first_supported_loader_stream_load_options_1}


```
 create_first_supported_loader(stream, load_options) 
```

Crea el primer cargador encontrado adecuado para el _stream_ especificado y opcionalmente para los _loadOptions_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Las opciones de carga. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | El cargador que admite el _stream_ y los _loadOptions_ especificados o null si no se encuentra tal cargador. |


### Method: get_first_supported_descriptor(stream, load_options)  [static] {#get_first_supported_descriptor_stream_load_options_2}


```
 get_first_supported_descriptor(stream, load_options) 
```

Obtiene el primer descriptor compatible encontrado adecuado para el _stream_ especificado y opcionalmente para los _loadOptions_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Las opciones de carga. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | El descriptor de cargador que admite el _stream_ y los _loadOptions_ especificados o null si no se encuentra tal descriptor. |


### Method: get_first_supported_descriptor_by_file_format(file_format)  [static] {#get_first_supported_descriptor_by_file_format_file_format_3}


```
 get_first_supported_descriptor_by_file_format(file_format) 
```

Obtiene el primer formato de archivo compatible por su nombre de tipo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | El formato de archivo del descriptor compatible. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | El primer descriptor de cargador encontrado o null si no se encuentra tal descriptor. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_4}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Obtiene el primer descriptor compatible por su nombre de tipo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| descriptor_type_name | string | El nombre del tipo de descriptor. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | El primer descriptor de cargador encontrado o null si no se encuentra tal descriptor. |


### Method: register(image_loader_descriptor)  [static] {#register_image_loader_descriptor_5}


```
 register(image_loader_descriptor) 
```

Registra el descriptor de cargador de imagen especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | El descriptor del cargador de imagen. |

### Method: register_loader(loader_descriptor)  [static] {#register_loader_loader_descriptor_6}


```
 register_loader(loader_descriptor) 
```

Registra el cargador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | El descriptor del cargador a registrar. |

### Method: unregister_loader(loader_descriptor)  [static] {#unregister_loader_loader_descriptor_7}


```
 unregister_loader(loader_descriptor) 
```

Desregistra el cargador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | El descriptor del cargador a desregistrar. |

