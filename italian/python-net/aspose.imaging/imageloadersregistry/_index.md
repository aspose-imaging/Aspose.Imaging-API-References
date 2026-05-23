---
title: "Classe ImageLoadersRegistry"
type: docs
weight: 5720
url: /it/python-net/aspose.imaging/imageloadersregistry/
---

**Summary:** Represents the image loaders registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageLoadersRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageLoaderDescriptor[]](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | r | Ottiene i descrittori registrati. |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Ottiene i formati di caricamento immagine registrati. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_first_supported_loader(stream, load_options)](#create_first_supported_loader_stream_load_options_1) | Crea il primo loader trovato adatto per lo _stream_ specificato e opzionalmente le _loadOptions_. |
| [get_first_supported_descriptor(stream, load_options)](#get_first_supported_descriptor_stream_load_options_2) | Ottiene il primo descrittore supportato trovato adatto per lo _stream_ specificato e opzionalmente le _loadOptions_. |
| [get_first_supported_descriptor_by_file_format(file_format)](#get_first_supported_descriptor_by_file_format_file_format_3) | Ottiene il primo formato file supportato per il suo nome di tipo. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_4) | Ottiene il primo descrittore supportato per il suo nome di tipo. |
| [register(image_loader_descriptor)](#register_image_loader_descriptor_5) | Registra il descrittore del loader immagine specificato. |
| [register_loader(loader_descriptor)](#register_loader_loader_descriptor_6) | Registra il loader. |
| [unregister_loader(loader_descriptor)](#unregister_loader_loader_descriptor_7) | Annulla la registrazione del loader. |


### Method: create_first_supported_loader(stream, load_options)  [static] {#create_first_supported_loader_stream_load_options_1}


```
 create_first_supported_loader(stream, load_options) 
```

Crea il primo loader trovato adatto per lo _stream_ specificato e opzionalmente le _loadOptions_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Lo stream. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Le opzioni di caricamento. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | Il loader che supporta lo _stream_ e le _loadOptions_ specificati o null se non viene trovato alcun loader. |


### Method: get_first_supported_descriptor(stream, load_options)  [static] {#get_first_supported_descriptor_stream_load_options_2}


```
 get_first_supported_descriptor(stream, load_options) 
```

Ottiene il primo descrittore supportato trovato adatto per lo _stream_ specificato e opzionalmente le _loadOptions_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Lo stream. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Le opzioni di caricamento. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Il descrittore del loader che supporta lo _stream_ e le _loadOptions_ specificati o null se non viene trovato alcun descrittore. |


### Method: get_first_supported_descriptor_by_file_format(file_format)  [static] {#get_first_supported_descriptor_by_file_format_file_format_3}


```
 get_first_supported_descriptor_by_file_format(file_format) 
```

Ottiene il primo formato file supportato per il suo nome di tipo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Il formato file del descrittore supportato. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Il primo descrittore di loader trovato o null se non viene trovato alcun descrittore. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_4}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Ottiene il primo descrittore supportato per il suo nome di tipo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| descriptor_type_name | string | Il nome del tipo di descrittore. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Il primo descrittore di loader trovato o null se non viene trovato alcun descrittore. |


### Method: register(image_loader_descriptor)  [static] {#register_image_loader_descriptor_5}


```
 register(image_loader_descriptor) 
```

Registra il descrittore del loader immagine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Il descrittore del loader immagine. |

### Method: register_loader(loader_descriptor)  [static] {#register_loader_loader_descriptor_6}


```
 register_loader(loader_descriptor) 
```

Registra il loader.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Il descrittore del loader da registrare. |

### Method: unregister_loader(loader_descriptor)  [static] {#unregister_loader_loader_descriptor_7}


```
 unregister_loader(loader_descriptor) 
```

Annulla la registrazione del loader.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Il descrittore del loader da annullare la registrazione. |

