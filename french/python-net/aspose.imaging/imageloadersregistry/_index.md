---
title: "Classe ImageLoadersRegistry"
type: docs
weight: 5720
url: /fr/python-net/aspose.imaging/imageloadersregistry/
---

**Summary:** Represents the image loaders registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageLoadersRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageLoaderDescriptor[]](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | r | Obtient les descripteurs enregistrés. |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Obtient les formats de chargement d'images enregistrés. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_first_supported_loader(stream, load_options)](#create_first_supported_loader_stream_load_options_1) | Crée le premier chargeur trouvé adapté au _stream_ spécifié et éventuellement aux _loadOptions_. |
| [get_first_supported_descriptor(stream, load_options)](#get_first_supported_descriptor_stream_load_options_2) | Obtient le premier descripteur pris en charge trouvé adapté au _stream_ spécifié et éventuellement aux _loadOptions_. |
| [get_first_supported_descriptor_by_file_format(file_format)](#get_first_supported_descriptor_by_file_format_file_format_3) | Obtient le premier format de fichier pris en charge par son nom de type. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_4) | Obtient le premier descripteur pris en charge par son nom de type. |
| [register(image_loader_descriptor)](#register_image_loader_descriptor_5) | Enregistre le descripteur de chargeur d'image spécifié. |
| [register_loader(loader_descriptor)](#register_loader_loader_descriptor_6) | Enregistre le chargeur. |
| [unregister_loader(loader_descriptor)](#unregister_loader_loader_descriptor_7) | Désenregistre le chargeur. |


### Method: create_first_supported_loader(stream, load_options)  [static] {#create_first_supported_loader_stream_load_options_1}


```
 create_first_supported_loader(stream, load_options) 
```

Crée le premier chargeur trouvé adapté au _stream_ spécifié et éventuellement aux _loadOptions_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Les options de chargement. |

**Returns**

| Type | Description |
| :- | :- |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | Le chargeur qui prend en charge le _stream_ et les _loadOptions_ spécifiés ou null si aucun chargeur de ce type n'est trouvé. |


### Method: get_first_supported_descriptor(stream, load_options)  [static] {#get_first_supported_descriptor_stream_load_options_2}


```
 get_first_supported_descriptor(stream, load_options) 
```

Obtient le premier descripteur pris en charge trouvé adapté au _stream_ spécifié et éventuellement aux _loadOptions_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Les options de chargement. |

**Returns**

| Type | Description |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Le descripteur de chargeur qui prend en charge le _stream_ et les _loadOptions_ spécifiés ou null si aucun descripteur de ce type n'est trouvé. |


### Method: get_first_supported_descriptor_by_file_format(file_format)  [static] {#get_first_supported_descriptor_by_file_format_file_format_3}


```
 get_first_supported_descriptor_by_file_format(file_format) 
```

Obtient le premier format de fichier pris en charge par son nom de type.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Le format de fichier du descripteur pris en charge. |

**Returns**

| Type | Description |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Le premier descripteur de chargeur trouvé ou null si aucun descripteur de ce type n'est trouvé. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_4}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Obtient le premier descripteur pris en charge par son nom de type.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| descriptor_type_name | string | Le nom du type de descripteur. |

**Returns**

| Type | Description |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Le premier descripteur de chargeur trouvé ou null si aucun descripteur de ce type n'est trouvé. |


### Method: register(image_loader_descriptor)  [static] {#register_image_loader_descriptor_5}


```
 register(image_loader_descriptor) 
```

Enregistre le descripteur de chargeur d'image spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image_loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Le descripteur du chargeur d'image. |

### Method: register_loader(loader_descriptor)  [static] {#register_loader_loader_descriptor_6}


```
 register_loader(loader_descriptor) 
```

Enregistre le chargeur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Le descripteur du chargeur à enregistrer. |

### Method: unregister_loader(loader_descriptor)  [static] {#unregister_loader_loader_descriptor_7}


```
 unregister_loader(loader_descriptor) 
```

Désenregistre le chargeur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Le descripteur du chargeur à désenregistrer. |

