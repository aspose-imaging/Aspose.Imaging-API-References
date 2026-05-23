---
title: "ImageLoadersRegistry Klasse"
type: docs
weight: 5720
url: /de/python-net/aspose.imaging/imageloadersregistry/
---

**Summary:** Represents the image loaders registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageLoadersRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageLoaderDescriptor[]](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | r | Ruft die registrierten Deskriptoren ab. |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Ruft die registrierten Bildladeformate ab. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_first_supported_loader(stream, load_options)](#create_first_supported_loader_stream_load_options_1) | Erstellt den zuerst gefundenen Loader, der für den angegebenen _stream_ geeignet ist und optional die _loadOptions_. |
| [get_first_supported_descriptor(stream, load_options)](#get_first_supported_descriptor_stream_load_options_2) | Ruft den zuerst gefundenen unterstützten Deskriptor ab, der für den angegebenen _stream_ geeignet ist und optional die _loadOptions_. |
| [get_first_supported_descriptor_by_file_format(file_format)](#get_first_supported_descriptor_by_file_format_file_format_3) | Ruft das erste unterstützte Dateiformat anhand seines Typnamens ab. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_4) | Ruft den ersten unterstützten Deskriptor anhand seines Typnamens ab. |
| [register(image_loader_descriptor)](#register_image_loader_descriptor_5) | Registriert den angegebenen Bild-Loader-Deskriptor. |
| [register_loader(loader_descriptor)](#register_loader_loader_descriptor_6) | Registriert den Loader. |
| [unregister_loader(loader_descriptor)](#unregister_loader_loader_descriptor_7) | Meldet den Loader ab. |


### Method: create_first_supported_loader(stream, load_options)  [static] {#create_first_supported_loader_stream_load_options_1}


```
 create_first_supported_loader(stream, load_options) 
```

Erstellt den zuerst gefundenen Loader, der für den angegebenen _stream_ geeignet ist und optional die _loadOptions_.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Die Ladeoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | Der Loader, der den angegebenen _stream_ und _loadOptions_ unterstützt, oder null, wenn kein solcher Loader gefunden wird. |


### Method: get_first_supported_descriptor(stream, load_options)  [static] {#get_first_supported_descriptor_stream_load_options_2}


```
 get_first_supported_descriptor(stream, load_options) 
```

Ruft den zuerst gefundenen unterstützten Deskriptor ab, der für den angegebenen _stream_ geeignet ist und optional die _loadOptions_.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Die Ladeoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Der Loader-Deskriptor, der den angegebenen _stream_ und _loadOptions_ unterstützt, oder null, wenn kein solcher Deskriptor gefunden wird. |


### Method: get_first_supported_descriptor_by_file_format(file_format)  [static] {#get_first_supported_descriptor_by_file_format_file_format_3}


```
 get_first_supported_descriptor_by_file_format(file_format) 
```

Ruft das erste unterstützte Dateiformat anhand seines Typnamens ab.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Das unterstützte Deskriptor-Dateiformat. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Der zuerst gefundene Loader-Deskriptor oder null, wenn kein solcher Deskriptor gefunden wird. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_4}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Ruft den ersten unterstützten Deskriptor anhand seines Typnamens ab.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| descriptor_type_name | string | Der Deskriptor-Typname. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Der zuerst gefundene Loader-Deskriptor oder null, wenn kein solcher Deskriptor gefunden wird. |


### Method: register(image_loader_descriptor)  [static] {#register_image_loader_descriptor_5}


```
 register(image_loader_descriptor) 
```

Registriert den angegebenen Bild-Loader-Deskriptor.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Der Bild-Loader-Deskriptor. |

### Method: register_loader(loader_descriptor)  [static] {#register_loader_loader_descriptor_6}


```
 register_loader(loader_descriptor) 
```

Registriert den Loader.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Der zu registrierende Loader-Deskriptor. |

### Method: unregister_loader(loader_descriptor)  [static] {#unregister_loader_loader_descriptor_7}


```
 unregister_loader(loader_descriptor) 
```

Meldet den Loader ab.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Der zu deregistrierende Loader-Deskriptor. |

