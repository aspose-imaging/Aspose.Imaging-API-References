---
title: "GifBlocksRegistry 类"
type: docs
weight: 30
url: /zh/python-net/aspose.imaging.fileformats.gif/gifblocksregistry/
---

**Summary:** Represents the gif blocks openers registry.

**Module:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Name:** aspose.imaging.fileformats.gif.GifBlocksRegistry

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IGifBlockLoaderDescriptor[]](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | r | 获取已注册的描述符。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [get_first_supported_descriptor(stream)](#get_first_supported_descriptor_stream_1) | 获取第一个受支持的打开器描述符。 |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | 通过其类型名称获取第一个受支持的描述符。 |
| [load_block_by_first_supported_descriptor(stream, container_palette)](#load_block_by_first_supported_descriptor_stream_container_palette_3) | 使用首次找到的适用于指定 _stream_ 的打开器加载 gif 块。 |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | 注册打开器。 |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | 注销打开器。 |


### Method: get_first_supported_descriptor(stream)  [static] {#get_first_supported_descriptor_stream_1}


```
 get_first_supported_descriptor(stream) 
```

获取第一个受支持的打开器描述符。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 该流。 |

**Returns**

| Type | Description |
| :- | :- |
| [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | gif 块打开器描述符，如果此类流不支持任何打开器描述符，则为 null。 |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


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
| [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | 首次找到的打开器描述符，如果未找到此类描述符，则为 null。 |


### Method: load_block_by_first_supported_descriptor(stream, container_palette)  [static] {#load_block_by_first_supported_descriptor_stream_container_palette_3}


```
 load_block_by_first_supported_descriptor(stream, container_palette) 
```

使用首次找到的适用于指定 _stream_ 的打开器加载 gif 块。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 该流。 |
| container_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 容器调色板。 |

**Returns**

| Type | Description |
| :- | :- |
| [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | 已加载的 gif 块，如果未找到打开器，则为 null。 |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

注册打开器。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| opener_descriptor | [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | 要注册的打开器描述符。 |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

注销打开器。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| opener_descriptor | [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | 要注销的打开器描述符。 |

