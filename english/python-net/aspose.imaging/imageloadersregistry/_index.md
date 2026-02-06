---
title: ImageLoadersRegistry Class
type: docs
weight: 5720
url: /python-net/aspose.imaging/imageloadersregistry/
---

**Summary:** Represents the image loaders registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageLoadersRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageLoaderDescriptor[]](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | r | Gets the registered descriptors. |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Gets the registered image loading formats. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_first_supported_loader(stream, load_options)](#create_first_supported_loader_stream_load_options_1) | Creates the first found loader suitable for the specified _stream_ and optionally the _loadOptions_. |
| [get_first_supported_descriptor(stream, load_options)](#get_first_supported_descriptor_stream_load_options_2) | Gets the fist found supported descriptor suitable for the specified _stream_ and optionally the _loadOptions_. |
| [get_first_supported_descriptor_by_file_format(file_format)](#get_first_supported_descriptor_by_file_format_file_format_3) | Gets the first supported file format by its type name. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_4) | Gets the first supported descriptor by its type name. |
| [register(image_loader_descriptor)](#register_image_loader_descriptor_5) | Registers the specified image loader descriptor. |
| [register_loader(loader_descriptor)](#register_loader_loader_descriptor_6) | Registers the loader. |
| [unregister_loader(loader_descriptor)](#unregister_loader_loader_descriptor_7) | Unregisters the loader. |


### Method: create_first_supported_loader(stream, load_options)  [static] {#create_first_supported_loader_stream_load_options_1}


```
 create_first_supported_loader(stream, load_options) 
```

Creates the first found loader suitable for the specified _stream_ and optionally the _loadOptions_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | The loader which supports the specified _stream_ and _loadOptions_ or null if no such loader is found. |


### Method: get_first_supported_descriptor(stream, load_options)  [static] {#get_first_supported_descriptor_stream_load_options_2}


```
 get_first_supported_descriptor(stream, load_options) 
```

Gets the fist found supported descriptor suitable for the specified _stream_ and optionally the _loadOptions_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | The loader descriptor which supports the specified _stream_ and _loadOptions_ or null if no such descriptor is found. |


### Method: get_first_supported_descriptor_by_file_format(file_format)  [static] {#get_first_supported_descriptor_by_file_format_file_format_3}


```
 get_first_supported_descriptor_by_file_format(file_format) 
```

Gets the first supported file format by its type name.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | The supported descriptor file format. |

**Returns**

| Type | Description |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | The first found loader descriptor or null if not such descriptor is found. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_4}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Gets the first supported descriptor by its type name.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| descriptor_type_name | string | The descriptor type name. |

**Returns**

| Type | Description |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | The first found loader descriptor or null if not such descriptor is found. |


### Method: register(image_loader_descriptor)  [static] {#register_image_loader_descriptor_5}


```
 register(image_loader_descriptor) 
```

Registers the specified image loader descriptor.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | The image loader descriptor. |

### Method: register_loader(loader_descriptor)  [static] {#register_loader_loader_descriptor_6}


```
 register_loader(loader_descriptor) 
```

Registers the loader.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | The loader descriptor to register. |

### Method: unregister_loader(loader_descriptor)  [static] {#unregister_loader_loader_descriptor_7}


```
 unregister_loader(loader_descriptor) 
```

Unregisters the loader.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | The loader descriptor to unregister. |

