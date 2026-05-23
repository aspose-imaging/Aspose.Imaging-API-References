---
title: "ImageLoadersRegistry klass"
type: docs
weight: 5720
url: /sv/python-net/aspose.imaging/imageloadersregistry/
---

**Summary:** Represents the image loaders registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageLoadersRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageLoaderDescriptor[]](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | r | Hämtar de registrerade beskrivarna. |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Hämtar de registrerade bildläsningsformaten. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_first_supported_loader(stream, load_options)](#create_first_supported_loader_stream_load_options_1) | Skapar den först hittade laddaren som är lämplig för den angivna _stream_ och eventuellt _loadOptions_. |
| [get_first_supported_descriptor(stream, load_options)](#get_first_supported_descriptor_stream_load_options_2) | Hämtar den först hittade stödjade beskrivaren som är lämplig för den angivna _stream_ och eventuellt _loadOptions_. |
| [get_first_supported_descriptor_by_file_format(file_format)](#get_first_supported_descriptor_by_file_format_file_format_3) | Hämtar det första stödjade filformatet efter dess typnamn. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_4) | Hämtar den första stödjade beskrivaren efter dess typnamn. |
| [register(image_loader_descriptor)](#register_image_loader_descriptor_5) | Registrerar den angivna bildladdarbeskrivaren. |
| [register_loader(loader_descriptor)](#register_loader_loader_descriptor_6) | Registrerar laddaren. |
| [unregister_loader(loader_descriptor)](#unregister_loader_loader_descriptor_7) | Avregistrerar laddaren. |


### Method: create_first_supported_loader(stream, load_options)  [static] {#create_first_supported_loader_stream_load_options_1}


```
 create_first_supported_loader(stream, load_options) 
```

Skapar den först hittade laddaren som är lämplig för den angivna _stream_ och eventuellt _loadOptions_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Laddningsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | Laddaren som stöder den angivna _stream_ och _loadOptions_ eller null om ingen sådan laddare hittas. |


### Method: get_first_supported_descriptor(stream, load_options)  [static] {#get_first_supported_descriptor_stream_load_options_2}


```
 get_first_supported_descriptor(stream, load_options) 
```

Hämtar den först hittade stödjade beskrivaren som är lämplig för den angivna _stream_ och eventuellt _loadOptions_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Laddningsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Laddarbeskrivaren som stöder den angivna _stream_ och _loadOptions_ eller null om ingen sådan beskrivare hittas. |


### Method: get_first_supported_descriptor_by_file_format(file_format)  [static] {#get_first_supported_descriptor_by_file_format_file_format_3}


```
 get_first_supported_descriptor_by_file_format(file_format) 
```

Hämtar det första stödjade filformatet efter dess typnamn.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Det stödjade beskrivarfilsformatet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Den först hittade laddarbeskrivaren eller null om ingen sådan beskrivare hittas. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_4}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Hämtar den första stödjade beskrivaren efter dess typnamn.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| descriptor_type_name | string | Beskrivartypnamnet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Den först hittade laddarbeskrivaren eller null om ingen sådan beskrivare hittas. |


### Method: register(image_loader_descriptor)  [static] {#register_image_loader_descriptor_5}


```
 register(image_loader_descriptor) 
```

Registrerar den angivna bildladdarbeskrivaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Bildladdarbeskrivaren. |

### Method: register_loader(loader_descriptor)  [static] {#register_loader_loader_descriptor_6}


```
 register_loader(loader_descriptor) 
```

Registrerar laddaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Laddarbeskrivaren att registrera. |

### Method: unregister_loader(loader_descriptor)  [static] {#unregister_loader_loader_descriptor_7}


```
 unregister_loader(loader_descriptor) 
```

Avregistrerar laddaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Laddarbeskrivaren att avregistrera. |

