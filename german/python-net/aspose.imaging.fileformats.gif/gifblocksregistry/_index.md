---
title: "GifBlocksRegistry Klasse"
type: docs
weight: 30
url: /de/python-net/aspose.imaging.fileformats.gif/gifblocksregistry/
---

**Summary:** Represents the gif blocks openers registry.

**Module:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Name:** aspose.imaging.fileformats.gif.GifBlocksRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IGifBlockLoaderDescriptor[]](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | r | Ruft die registrierten Deskriptoren ab. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_first_supported_descriptor(stream)](#get_first_supported_descriptor_stream_1) | Gibt den ersten unterstützten Öffner-Deskriptor zurück. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Ruft den ersten unterstützten Deskriptor anhand seines Typnamens ab. |
| [load_block_by_first_supported_descriptor(stream, container_palette)](#load_block_by_first_supported_descriptor_stream_container_palette_3) | Lädt den GIF-Block mit dem zuerst gefundenen Öffner, der für den angegebenen _stream_ geeignet ist. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Registriert den Öffner. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Deregistriert den Öffner. |


### Method: get_first_supported_descriptor(stream)  [static] {#get_first_supported_descriptor_stream_1}


```
 get_first_supported_descriptor(stream) 
```

Gibt den ersten unterstützten Öffner-Deskriptor zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | Der GIF-Block-Öffner-Deskriptor oder null, wenn kein Öffner-Deskriptor für einen solchen Stream unterstützt wird. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


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
| [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | Der zuerst gefundene Öffner-Deskriptor oder null, wenn ein solcher Deskriptor nicht gefunden wird. |


### Method: load_block_by_first_supported_descriptor(stream, container_palette)  [static] {#load_block_by_first_supported_descriptor_stream_container_palette_3}


```
 load_block_by_first_supported_descriptor(stream, container_palette) 
```

Lädt den GIF-Block mit dem zuerst gefundenen Öffner, der für den angegebenen _stream_ geeignet ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream. |
| container_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die Container-Palette. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | Der geladene GIF-Block oder null, wenn kein Öffner gefunden wird. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Registriert den Öffner.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| opener_descriptor | [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | Der zu registrierende Öffner-Deskriptor. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Deregistriert den Öffner.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| opener_descriptor | [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | Der zu deregistrierende Öffner-Deskriptor. |

