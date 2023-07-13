---
title: GifBlocksRegistry Class
type: docs
weight: 30
url: /python-net/aspose.imaging.fileformats.gif/gifblocksregistry/
---

Represents the gif blocks openers registry.

**Module:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Name:** aspose.imaging.fileformats.gif.GifBlocksRegistry

**Aspose.Imaging Version:** 23.6

The GifBlocksRegistry type exposes the following members:
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| registered_descriptors [static] | [IGifBlockLoaderDescriptor[]](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor) | r | Gets the registered descriptors. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_0) | Gets the first supported descriptor by its type name. |
| [get_first_supported_descriptor(stream)](#get_first_supported_descriptor_stream_1) | Gets the first supported opener descriptor. |
| [load_block_by_first_supported_descriptor(stream, container_palette)](#load_block_by_first_supported_descriptor_stream_container_palette_2) | Loads gif block using first found opener suitable for the specified <paramref name="stream" />. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_3) | Registers the opener. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_4) | Unregisters the opener. |

### get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_0}


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
| [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor) | The first found opener descriptor or null if not such descriptor is found. |


### get_first_supported_descriptor(stream)  [static] {#get_first_supported_descriptor_stream_1}


```
 get_first_supported_descriptor(stream) 
```

Gets the first supported opener descriptor.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |

**Returns**

| Type | Description |
| :- | :- |
| [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor) | The gif block opener descriptor or null if no opener descriptor supported for such stream. |


### load_block_by_first_supported_descriptor(stream, container_palette)  [static] {#load_block_by_first_supported_descriptor_stream_container_palette_2}


```
 load_block_by_first_supported_descriptor(stream, container_palette) 
```

Loads gif block using first found opener suitable for the specified <paramref name="stream" />.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |
| container_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The container palette. |

**Returns**

| Type | Description |
| :- | :- |
| [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock) | The loaded gif block or null if no opener is found. |


### register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_3}


```
 register_opener(opener_descriptor) 
```

Registers the opener.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| opener_descriptor | [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor) | The opener descriptor to register. |

### unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_4}


```
 unregister_opener(opener_descriptor) 
```

Unregisters the opener.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| opener_descriptor | [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor) | The opener descriptor to unregister. |

