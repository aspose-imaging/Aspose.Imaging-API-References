---
title: "GifBlocksRegistry klass"
type: docs
weight: 30
url: /sv/python-net/aspose.imaging.fileformats.gif/gifblocksregistry/
---

**Summary:** Represents the gif blocks openers registry.

**Module:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Name:** aspose.imaging.fileformats.gif.GifBlocksRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IGifBlockLoaderDescriptor[]](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | r | Hämtar de registrerade beskrivarna. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_first_supported_descriptor(stream)](#get_first_supported_descriptor_stream_1) | Hämtar den första stödda öppnarebeskrivaren. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Hämtar den första stödjade beskrivaren efter dess typnamn. |
| [load_block_by_first_supported_descriptor(stream, container_palette)](#load_block_by_first_supported_descriptor_stream_container_palette_3) | Laddar gif‑block med den först hittade öppnaren som är lämplig för den angivna _stream_. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Registrerar öppnaren. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Avregistrerar öppnaren. |


### Method: get_first_supported_descriptor(stream)  [static] {#get_first_supported_descriptor_stream_1}


```
 get_first_supported_descriptor(stream) 
```

Hämtar den första stödda öppnarebeskrivaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | Gif‑blockets öppnarebeskrivning eller null om ingen öppnarebeskrivning stöds för sådan stream. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


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
| [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | Den först hittade öppnarebeskrivningen eller null om ingen sådan beskrivning hittas. |


### Method: load_block_by_first_supported_descriptor(stream, container_palette)  [static] {#load_block_by_first_supported_descriptor_stream_container_palette_3}


```
 load_block_by_first_supported_descriptor(stream, container_palette) 
```

Laddar gif‑block med den först hittade öppnaren som är lämplig för den angivna _stream_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen. |
| container_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Behållarpaletten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | Det laddade gif‑blocket eller null om ingen öppnare hittas. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Registrerar öppnaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| opener_descriptor | [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | Öppnarebeskrivningen att registrera. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Avregistrerar öppnaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| opener_descriptor | [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | Öppnarebeskrivningen att avregistrera. |

