---
title: "ImageLoadersRegistry 类"
type: docs
weight: 5720
url: /zh/python-net/aspose.imaging/imageloadersregistry/
---

**Summary:** Represents the image loaders registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageLoadersRegistry

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageLoaderDescriptor[]](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | r | 获取已注册的描述符。 |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | 获取已注册的图像加载格式。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_first_supported_loader(stream, load_options)](#create_first_supported_loader_stream_load_options_1) | 创建第一个符合指定 _stream_ 且可选的 _loadOptions_ 的加载器。 |
| [get_first_supported_descriptor(stream, load_options)](#get_first_supported_descriptor_stream_load_options_2) | 获取第一个符合指定 _stream_ 且可选的 _loadOptions_ 的受支持描述符。 |
| [get_first_supported_descriptor_by_file_format(file_format)](#get_first_supported_descriptor_by_file_format_file_format_3) | 通过其类型名称获取第一个受支持的文件格式。 |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_4) | 通过其类型名称获取第一个受支持的描述符。 |
| [register(image_loader_descriptor)](#register_image_loader_descriptor_5) | 注册指定的图像加载器描述符。 |
| [register_loader(loader_descriptor)](#register_loader_loader_descriptor_6) | 注册加载器。 |
| [unregister_loader(loader_descriptor)](#unregister_loader_loader_descriptor_7) | 注销加载器。 |


### Method: create_first_supported_loader(stream, load_options)  [static] {#create_first_supported_loader_stream_load_options_1}


```
 create_first_supported_loader(stream, load_options) 
```

创建第一个符合指定 _stream_ 且可选的 _loadOptions_ 的加载器。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 该流。 |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | 加载选项。 |

**Returns**

| Type | Description |
| :- | :- |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | 支持指定 _stream_ 和 _loadOptions_ 的加载器，如果未找到则为 null。 |


### Method: get_first_supported_descriptor(stream, load_options)  [static] {#get_first_supported_descriptor_stream_load_options_2}


```
 get_first_supported_descriptor(stream, load_options) 
```

获取第一个符合指定 _stream_ 且可选的 _loadOptions_ 的受支持描述符。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 该流。 |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | 加载选项。 |

**Returns**

| Type | Description |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | 支持指定 _stream_ 和 _loadOptions_ 的加载器描述符，如果未找到则为 null。 |


### Method: get_first_supported_descriptor_by_file_format(file_format)  [static] {#get_first_supported_descriptor_by_file_format_file_format_3}


```
 get_first_supported_descriptor_by_file_format(file_format) 
```

通过其类型名称获取第一个受支持的文件格式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | 受支持的描述符文件格式。 |

**Returns**

| Type | Description |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | 第一个找到的加载器描述符，如果未找到则为 null。 |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_4}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

通过其类型名称获取第一个受支持的描述符。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| descriptor_type_name | string | 描述符类型名称。 |

**Returns**

| Type | Description |
| :- | :- |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | 第一个找到的加载器描述符，如果未找到则为 null。 |


### Method: register(image_loader_descriptor)  [static] {#register_image_loader_descriptor_5}


```
 register(image_loader_descriptor) 
```

注册指定的图像加载器描述符。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image_loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | 图像加载器描述符。 |

### Method: register_loader(loader_descriptor)  [static] {#register_loader_loader_descriptor_6}


```
 register_loader(loader_descriptor) 
```

注册加载器。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | 要注册的加载器描述符。 |

### Method: unregister_loader(loader_descriptor)  [static] {#unregister_loader_loader_descriptor_7}


```
 unregister_loader(loader_descriptor) 
```

注销加载器。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | 要注销的加载器描述符。 |

